# 20230504 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45429
self.closeSec=1683159599, self.tradeDate='20230504', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29067.2, self.close=29052.0, self.high=29097.6, self.low=29040.1, self.vol=1515.341, self.amt=44049907.0893 
127.0.0.1 - - [04/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-04 08:20:07,683:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230504   075500    075959  ...         0.0        0.0       0
5856  20230504   080000    080459  ...         0.0        0.0       0
5857  20230504   080500    080959  ...         0.0        0.0       0
5858  20230504   081000    081459  ...         0.0        0.0       0
5859  20230504   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 08:20:07,695:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683159599, self.tradeDate='20230504', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29067.2, self.close=29052.0, self.high=29097.6, self.low=29040.1, self.vol=1515.341, self.amt=44049907.0893, ukdf['pct'].iloc[-1]=-0.000523 , ukdf['amount'].iloc[-1]=44049907.0893, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-754007.20348311504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29059.33196429', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45430
self.closeSec=1683159899, self.tradeDate='20230504', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29051.9, self.close=29049.4, self.high=29059.4, self.low=29023.9, self.vol=945.822, self.amt=27471740.3813 
2023-05-04 08:25:01,710:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230504   080000    080459  ...         0.0        0.0       0
5857  20230504   080500    080959  ...         0.0        0.0       0
5858  20230504   081000    081459  ...         0.0        0.0       0
5859  20230504   081500    081959  ...         0.0        0.0       0
5860  20230504   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 08:25:01,711:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683159899, self.tradeDate='20230504', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29051.9, self.close=29049.4, self.high=29059.4, self.low=29023.9, self.vol=945.822, self.amt=27471740.3813, ukdf['pct'].iloc[-1]=-8.9e-05 , ukdf['amount'].iloc[-1]=27471740.3813, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-753448.93449262144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29050.05469444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45991 

self.closeSec=1683158399, self.tradeDate='20230504', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28994.9, self.close=29018.4, self.high=29018.4, self.low=28982.7 
127.0.0.1 - - [04/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45992 

self.closeSec=1683158699, self.tradeDate='20230504', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29018.4, self.close=29043.1, self.high=29059.1, self.low=29010.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45993 

self.closeSec=1683158999, self.tradeDate='20230504', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29043.1, self.close=28997.8, self.high=29051.6, self.low=28988.7 
127.0.0.1 - - [04/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45994 

self.closeSec=1683159299, self.tradeDate='20230504', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28997.8, self.close=29067.2, self.high=29077.0, self.low=28980.0 
127.0.0.1 - - [04/May/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45995 

self.closeSec=1683159599, self.tradeDate='20230504', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29067.2, self.close=29052.0, self.high=29097.6, self.low=29040.1 
127.0.0.1 - - [04/May/2023 08:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45996 

self.closeSec=1683159899, self.tradeDate='20230504', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29051.9, self.close=29049.4, self.high=29059.4, self.low=29023.9 
127.0.0.1 - - [04/May/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-04 08:00:19,518:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230504    052959  28503.5  ...  49.583333  0.554463  0.498805
5770  20230504    055959  28835.9  ...  50.000000  0.564880  0.474942
5771  20230504    062959  28915.1  ...  50.000000  0.595843  0.448336
5772  20230504    065959  29169.0  ...  50.000000  0.583663  0.427635
5773  20230504    072959  29096.1  ...  50.000000  0.572875  0.412042

[5 rows x 33 columns]
0.55
acc is : 0.55
2023-05-04 08:00:19,584:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
535     0  0.594559  0.405441       1  ...  0.836115   1.0 -0.0016  1.045599
536     0  0.558505  0.441495       1  ...  0.843459   1.0  0.0000  1.054784
537     0  0.610390  0.389610       0  ...  0.841348   1.0  0.0000  1.052144
538     0  0.536737  0.463263       0  ...  0.839443   1.0  0.0000  1.049761
539     0  0.525750  0.474250       0  ...  0.839104   1.0  0.0000  1.049338

[5 rows x 10 columns]
2023-05-04 08:00:19,596:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.594359  0.405641       1  ...  0.842161   1.0 -0.0016  1.052331
46     0  0.558576  0.441424       1  ...  0.849559   1.0  0.0000  1.057074
47     0  0.610400  0.389600       0  ...  0.844405   1.0  0.0000  1.055450
48     0  0.537045  0.462955       0  ...  0.842493   1.0  0.0000  1.048283
49     0  0.525750  0.474250       0  ...  0.839104   1.0  0.0000  1.049338

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [04/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22993 

self.closeSec=1683156599, self.tradeDate='20230504', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29066.9', self.close='29030.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22994 

self.closeSec=1683157199, self.tradeDate='20230504', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29030.1', self.close='28979.4'
127.0.0.1 - - [04/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22995 

self.closeSec=1683157799, self.tradeDate='20230504', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28979.5', self.close='28963.9'
127.0.0.1 - - [04/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22996 

self.closeSec=1683158399, self.tradeDate='20230504', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28964', self.close='29018.4'
127.0.0.1 - - [04/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22997 

self.closeSec=1683158999, self.tradeDate='20230504', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29018.4', self.close='28997.9'
127.0.0.1 - - [04/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22998 

self.closeSec=1683159599, self.tradeDate='20230504', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28997.8', self.close='29052'
127.0.0.1 - - [04/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22994 

self.closeSec=1683156599, self.tradeDate='20230504', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29066.9', self.close='29030.1'
127.0.0.1 - - [04/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22995 

self.closeSec=1683157199, self.tradeDate='20230504', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29030.1', self.close='28979.4'
127.0.0.1 - - [04/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22996 

self.closeSec=1683157799, self.tradeDate='20230504', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28979.5', self.close='28963.9'
127.0.0.1 - - [04/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22997 

self.closeSec=1683158399, self.tradeDate='20230504', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28964', self.close='29018.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22998 

self.closeSec=1683158999, self.tradeDate='20230504', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29018.4', self.close='28997.9'
127.0.0.1 - - [04/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22999 

self.closeSec=1683159599, self.tradeDate='20230504', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28997.8', self.close='29052'
127.0.0.1 - - [04/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [04/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22994 

self.closeSec=1683156599, self.tradeDate='20230504', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29066.9', self.close='29030.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22995 

self.closeSec=1683157199, self.tradeDate='20230504', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29030.1', self.close='28979.4'
127.0.0.1 - - [04/May/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22996 

self.closeSec=1683157799, self.tradeDate='20230504', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28979.5', self.close='28963.9'
127.0.0.1 - - [04/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22997 

self.closeSec=1683158399, self.tradeDate='20230504', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28964', self.close='29018.4'
127.0.0.1 - - [04/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22998 

self.closeSec=1683158999, self.tradeDate='20230504', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29018.4', self.close='28997.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22999 

self.closeSec=1683159599, self.tradeDate='20230504', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28997.8', self.close='29052'
127.0.0.1 - - [04/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41427
self.closeSec=1683159599, self.tradeDate='20230504', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29067.2, self.close=29052.0, self.high=29097.6, self.low=29040.1, self.vol=1515.341, self.amt=44049907.0893 
127.0.0.1 - - [04/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-04 08:20:07,681:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230504   075500    075959  ...         0.0        0.0       0
5856  20230504   080000    080459  ...         0.0        0.0       0
5857  20230504   080500    080959  ...         0.0        0.0       0
5858  20230504   081000    081459  ...         0.0        0.0       0
5859  20230504   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 08:20:07,694:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683159599, self.tradeDate='20230504', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29067.2, self.close=29052.0, self.high=29097.6, self.low=29040.1, self.vol=1515.341, self.amt=44049907.0893, ukdf['pct'].iloc[-1]=-0.000523 , ukdf['amount'].iloc[-1]=44049907.0893, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [04/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41428
self.closeSec=1683159899, self.tradeDate='20230504', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29051.9, self.close=29049.4, self.high=29059.4, self.low=29023.9, self.vol=945.822, self.amt=27471740.3813 
2023-05-04 08:25:01,682:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230504   080000    080459  ...         0.0        0.0       0
5857  20230504   080500    080959  ...         0.0        0.0       0
5858  20230504   081000    081459  ...         0.0        0.0       0
5859  20230504   081500    081959  ...         0.0        0.0       0
5860  20230504   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 08:25:01,683:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683159899, self.tradeDate='20230504', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29051.9, self.close=29049.4, self.high=29059.4, self.low=29023.9, self.vol=945.822, self.amt=27471740.3813, ukdf['pct'].iloc[-1]=-8.9e-05 , ukdf['amount'].iloc[-1]=27471740.3813, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230503   200000    235959  1683129599  ...    719  0.606136 -0.059211     NaN
720  20230504   000000    035959  1683143999  ...    720  0.609041 -0.053257     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '48510.2771165558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28302.9362619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [04/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=958
self.closeSec=1683158399, self.tradeDate='20230504', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28308.8, self.close=29018.4, self.high=29258.4, self.low=28267.3, self.vol=157117.84, self.amt=4540650732.17692 
2023-05-04 08:00:01,851:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683158399, self.tradeDate='20230504', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28308.8, self.close=29018.4, self.high=29258.4, self.low=28267.3, self.vol=157117.84, self.amt=4540650732.17692 
2023-05-04 08:00:01,915:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230503   120000    155959  ...   44177.432  1.261075e+09  0.004662
718  20230503   160000    195959  ...   52280.691  1.497084e+09 -0.003607
719  20230503   200000    235959  ...  135071.937  3.821706e+09 -0.008491
720  20230504   000000    035959  ...  229709.193  6.540452e+09  0.000569
721  20230504   040000    075959  ...  157117.840  4.540651e+09  0.025066

[5 rows x 11 columns]
2023-05-04 08:00:03,826:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230503   120000    155959  1683100799  ...    717  0.575571 -0.147166     NaN
718  20230503   160000    195959  1683115199  ...    718  0.584878 -0.120900     NaN
719  20230503   200000    235959  1683129599  ...    719  0.606136 -0.059211     NaN
720  20230504   000000    035959  1683143999  ...    720  0.609041 -0.053257     NaN
721  20230504   040000    075959  1683158399  ...    721  0.558697 -0.207774     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '14977.26763268162', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29020.71119841', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


