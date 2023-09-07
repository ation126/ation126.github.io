# 20230907 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33364
self.closeSec=1694045999, self.tradeDate='20230907', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25753.7, self.close=25753.7, self.high=25755.7, self.low=25752.4, self.vol=113.342, self.amt=2918974.2383 
127.0.0.1 - - [07/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-07 08:20:05,867:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230907   075500    075959  ...         0.0        0.0       0
5856  20230907   080000    080459  ...         0.0        0.0       0
5857  20230907   080500    080959  ...         0.0        0.0       0
5858  20230907   081000    081459  ...         0.0        0.0       0
5859  20230907   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 08:20:05,873:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694045999, self.tradeDate='20230907', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25753.7, self.close=25753.7, self.high=25755.7, self.low=25752.4, self.vol=113.342, self.amt=2918974.2383, ukdf['pct'].iloc[-1]=4e-06 , ukdf['amount'].iloc[-1]=2918974.2383, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15478.53216563478', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25753.41557047', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33365
self.closeSec=1694046299, self.tradeDate='20230907', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25753.8, self.close=25740.1, self.high=25753.8, self.low=25730.2, self.vol=377.515, self.amt=9717068.0474 
2023-09-07 08:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230907   080000    080459  ...         0.0        0.0       0
5857  20230907   080500    080959  ...         0.0        0.0       0
5858  20230907   081000    081459  ...         0.0        0.0       0
5859  20230907   081500    081959  ...         0.0        0.0       0
5860  20230907   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 08:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694046299, self.tradeDate='20230907', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25753.8, self.close=25740.1, self.high=25753.8, self.low=25730.2, self.vol=377.515, self.amt=9717068.0474, ukdf['pct'].iloc[-1]=-0.000528 , ukdf['amount'].iloc[-1]=9717068.0474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15665.3574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25740', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [07/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33362 

self.closeSec=1694044799, self.tradeDate='20230907', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25753.5, self.close=25747.4, self.high=25757.2, self.low=25743.2 
127.0.0.1 - - [07/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33363 

self.closeSec=1694045099, self.tradeDate='20230907', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25747.4, self.close=25747.8, self.high=25750.7, self.low=25745.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33364 

self.closeSec=1694045399, self.tradeDate='20230907', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25747.9, self.close=25758.0, self.high=25758.0, self.low=25745.7 
127.0.0.1 - - [07/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33365 

self.closeSec=1694045699, self.tradeDate='20230907', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25758.0, self.close=25753.6, self.high=25761.9, self.low=25752.9 
127.0.0.1 - - [07/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33366 

self.closeSec=1694045999, self.tradeDate='20230907', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25753.7, self.close=25753.7, self.high=25755.7, self.low=25752.4 
127.0.0.1 - - [07/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33367 

self.closeSec=1694046299, self.tradeDate='20230907', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25753.8, self.close=25740.1, self.high=25753.8, self.low=25730.2 
127.0.0.1 - - [07/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-07 08:00:17,755:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230907    052959  25671.5  ...  50.416667  0.498534  0.591127
5770  20230907    055959  25734.5  ...  50.000000  0.491730  0.582958
5771  20230907    062959  25711.9  ...  50.000000  0.499619  0.572974
5772  20230907    065959  25737.7  ...  50.000000  0.498544  0.563977
5773  20230907    072959  25734.0  ...  50.000000  0.509290  0.552374

[5 rows x 33 columns]
0.5277777777777778
acc is : 0.5277777777777778
2023-09-07 08:00:17,814:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.520413  0.479587       0  ...  0.995358   1.0    0.0  0.988205
536     1  0.489574  0.510426       1  ...  0.996353   1.0    0.0  0.989192
537     0  0.504188  0.495812       0  ...  0.996218   1.0    0.0  0.989058
538     1  0.499070  0.500930       1  ...  0.997569   1.0    0.0  0.990399
539     0  0.510555  0.489445       0  ...  0.996736   1.0    0.0  0.989573

[5 rows x 10 columns]
2023-09-07 08:00:17,825:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519842  0.480158       0  ...  0.995358   1.0    0.0  0.987393
46     1  0.489258  0.510742       1  ...  0.996353   1.0    0.0  0.988748
47     0  0.504145  0.495855       0  ...  0.996218   1.0    0.0  0.988742
48     1  0.499422  0.500578       1  ...  0.997569   1.0    0.0  0.991173
49     0  0.510555  0.489445       0  ...  0.996736   1.0    0.0  0.989573

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.331', 'enterprice': '25653.5', 'countrevence': '0', 'unrealprofit': '2714.20080087186', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25749.30321206', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16679 

self.closeSec=1694042999, self.tradeDate='20230907', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25770.1', self.close='25768.9'
127.0.0.1 - - [07/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16680 

self.closeSec=1694043599, self.tradeDate='20230907', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25768.9', self.close='25751.9'
127.0.0.1 - - [07/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16681 

self.closeSec=1694044199, self.tradeDate='20230907', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25751.9', self.close='25760.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16682 

self.closeSec=1694044799, self.tradeDate='20230907', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25760.4', self.close='25747.4'
127.0.0.1 - - [07/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16683 

self.closeSec=1694045399, self.tradeDate='20230907', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25747.4', self.close='25758'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16684 

self.closeSec=1694045999, self.tradeDate='20230907', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25758', self.close='25753.7'
127.0.0.1 - - [07/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16682 

self.closeSec=1694042999, self.tradeDate='20230907', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25770.1', self.close='25768.9'
127.0.0.1 - - [07/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16683 

self.closeSec=1694043599, self.tradeDate='20230907', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25768.9', self.close='25751.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16684 

self.closeSec=1694044199, self.tradeDate='20230907', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25751.9', self.close='25760.5'
127.0.0.1 - - [07/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16685 

self.closeSec=1694044799, self.tradeDate='20230907', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25760.4', self.close='25747.4'
127.0.0.1 - - [07/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16686 

self.closeSec=1694045399, self.tradeDate='20230907', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25747.4', self.close='25758'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16687 

self.closeSec=1694045999, self.tradeDate='20230907', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25758', self.close='25753.7'
127.0.0.1 - - [07/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16682 

self.closeSec=1694042999, self.tradeDate='20230907', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25770.1', self.close='25768.9'
127.0.0.1 - - [07/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16683 

self.closeSec=1694043599, self.tradeDate='20230907', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25768.9', self.close='25751.9'
127.0.0.1 - - [07/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16684 

self.closeSec=1694044199, self.tradeDate='20230907', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25751.9', self.close='25760.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16685 

self.closeSec=1694044799, self.tradeDate='20230907', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25760.4', self.close='25747.4'
127.0.0.1 - - [07/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16686 

self.closeSec=1694045399, self.tradeDate='20230907', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25747.4', self.close='25758'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16687 

self.closeSec=1694045999, self.tradeDate='20230907', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25758', self.close='25753.7'
127.0.0.1 - - [07/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33364
self.closeSec=1694045999, self.tradeDate='20230907', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25753.7, self.close=25753.7, self.high=25755.7, self.low=25752.4, self.vol=113.342, self.amt=2918974.2383 
127.0.0.1 - - [07/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-07 08:20:05,865:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230907   075500    075959  ...         0.0        0.0       0
5856  20230907   080000    080459  ...         0.0        0.0       0
5857  20230907   080500    080959  ...         0.0        0.0       0
5858  20230907   081000    081459  ...         0.0        0.0       0
5859  20230907   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 08:20:05,871:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694045999, self.tradeDate='20230907', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25753.7, self.close=25753.7, self.high=25755.7, self.low=25752.4, self.vol=113.342, self.amt=2918974.2383, ukdf['pct'].iloc[-1]=4e-06 , ukdf['amount'].iloc[-1]=2918974.2383, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-40505.39629717373', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25753.41557047', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33365
self.closeSec=1694046299, self.tradeDate='20230907', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25753.8, self.close=25740.1, self.high=25753.8, self.low=25730.2, self.vol=377.515, self.amt=9717068.0474 
127.0.0.1 - - [07/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-07 08:25:00,798:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230907   080000    080459  ...         0.0        0.0       0
5857  20230907   080500    080959  ...         0.0        0.0       0
5858  20230907   081000    081459  ...         0.0        0.0       0
5859  20230907   081500    081959  ...         0.0        0.0       0
5860  20230907   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 08:25:00,798:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694046299, self.tradeDate='20230907', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25753.8, self.close=25740.1, self.high=25753.8, self.low=25730.2, self.vol=377.515, self.amt=9717068.0474, ukdf['pct'].iloc[-1]=-0.000528 , ukdf['amount'].iloc[-1]=9717068.0474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-41003.664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25740', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230906   200000    235959  1694015999  ...    719  0.281480 -0.322471     NaN
720  20230907   000000    035959  1694030399  ...    720  0.018381 -1.059710    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '12064.347', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25681.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=695
self.closeSec=1694044799, self.tradeDate='20230907', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25679.5, self.close=25747.4, self.high=25776.0, self.low=25641.6, self.vol=19974.218, self.amt=513819878.0486 
127.0.0.1 - - [07/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-07 08:00:01,579:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694044799, self.tradeDate='20230907', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25679.5, self.close=25747.4, self.high=25776.0, self.low=25641.6, self.vol=19974.218, self.amt=513819878.0486 
2023-09-07 08:00:01,592:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230906   120000    155959  ...   14492.862  3.731917e+08 -0.002138
718  20230906   160000    195959  ...   13681.083  3.520082e+08  0.000276
719  20230906   200000    235959  ...   58993.312  1.512453e+09 -0.005668
720  20230907   000000    035959  ...  127581.603  3.276441e+09  0.004031
721  20230907   040000    075959  ...   19974.218  5.138199e+08  0.002648

[5 rows x 11 columns]
2023-09-07 08:00:02,285:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230906   120000    155959  1693987199  ...    717  0.235360 -0.430896     NaN
718  20230906   160000    195959  1694001599  ...    718  0.257673 -0.377964     NaN
719  20230906   200000    235959  1694015999  ...    719  0.281480 -0.322471     NaN
720  20230907   000000    035959  1694030399  ...    720  0.018381 -1.059710    -1.0
721  20230907   040000    075959  1694044799  ...    721  0.022021 -1.049607    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '8284.9473', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25747.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


