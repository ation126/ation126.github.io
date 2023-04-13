# 20230413 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39381
self.closeSec=1681345199, self.tradeDate='20230413', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29907.0, self.close=29841.9, self.high=29908.1, self.low=29836.7, self.vol=1188.52, self.amt=35494614.1292 
127.0.0.1 - - [13/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-13 08:20:07,170:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230413   075500    075959  ...         0.0        0.0       0
5849  20230413   080000    080459  ...         0.0        0.0       0
5850  20230413   080500    080959  ...         0.0        0.0       0
5851  20230413   081000    081459  ...         0.0        0.0       0
5852  20230413   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 08:20:07,174:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681345199, self.tradeDate='20230413', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29907.0, self.close=29841.9, self.high=29908.1, self.low=29836.7, self.vol=1188.52, self.amt=35494614.1292, ukdf['pct'].iloc[-1]=-0.002177 , ukdf['amount'].iloc[-1]=35494614.1292, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-801700.7776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29851.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39382
self.closeSec=1681345499, self.tradeDate='20230413', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29842.6, self.close=29918.0, self.high=29920.0, self.low=29842.6, self.vol=969.804, self.amt=28986836.1688 
127.0.0.1 - - [13/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-13 08:25:01,540:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230413   080000    080459  ...         0.0        0.0       0
5850  20230413   080500    080959  ...         0.0        0.0       0
5851  20230413   081000    081459  ...         0.0        0.0       0
5852  20230413   081500    081959  ...         0.0        0.0       0
5853  20230413   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 08:25:01,540:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681345499, self.tradeDate='20230413', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29842.6, self.close=29918.0, self.high=29920.0, self.low=29842.6, self.vol=969.804, self.amt=28986836.1688, ukdf['pct'].iloc[-1]=0.00255 , ukdf['amount'].iloc[-1]=28986836.1688, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-805747.24609674336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29919.14389286', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39943 

self.closeSec=1681343999, self.tradeDate='20230413', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29861.8, self.close=29875.0, self.high=29875.0, self.low=29860.0 
127.0.0.1 - - [13/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39944 

self.closeSec=1681344299, self.tradeDate='20230413', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29874.9, self.close=29897.4, self.high=29897.4, self.low=29874.9 
127.0.0.1 - - [13/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39945 

self.closeSec=1681344599, self.tradeDate='20230413', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29897.4, self.close=29896.4, self.high=29902.3, self.low=29864.9 
127.0.0.1 - - [13/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Apr/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39946 

self.closeSec=1681344899, self.tradeDate='20230413', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29896.3, self.close=29907.0, self.high=29909.8, self.low=29896.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39947 

self.closeSec=1681345199, self.tradeDate='20230413', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29907.0, self.close=29841.9, self.high=29908.1, self.low=29836.7 
127.0.0.1 - - [13/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39948 

self.closeSec=1681345499, self.tradeDate='20230413', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29842.6, self.close=29918.0, self.high=29920.0, self.low=29842.6 
127.0.0.1 - - [13/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-13 08:00:33,965:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230413    052959  29934.8  ...  52.083333  0.526786  0.664392
5770  20230413    055959  29930.6  ...  52.083333  0.527436  0.662370
5771  20230413    062959  29934.7  ...  51.666667  0.524780  0.661631
5772  20230413    065959  29920.0  ...  51.666667  0.509275  0.667739
5773  20230413    072959  29832.2  ...  51.666667  0.520420  0.668200

[5 rows x 33 columns]
0.5796296296296296
acc is : 0.5796296296296296
2023-04-13 08:00:34,131:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.512925  0.487075       1  ...  1.021595  -1.0    0.0  1.055767
536     0  0.520666  0.479334       0  ...  1.022100  -1.0    0.0  1.055245
537     0  0.517405  0.482595       0  ...  1.025096  -1.0    0.0  1.052152
538     1  0.492280  0.507720       1  ...  1.022773  -1.0    0.0  1.054536
539     0  0.523309  0.476691       0  ...  1.023621  -1.0    0.0  1.053662

[5 rows x 10 columns]
2023-04-13 08:00:34,167:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513809  0.486191       1  ...  1.021595  -1.0    0.0  1.055987
46     0  0.521058  0.478942       0  ...  1.022100  -1.0    0.0  1.053993
47     0  0.517393  0.482607       0  ...  1.025096  -1.0    0.0  1.049986
48     1  0.492783  0.507217       1  ...  1.022773  -1.0    0.0  1.056060
49     0  0.523309  0.476691       0  ...  1.023621  -1.0    0.0  1.053662

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19969 

self.closeSec=1681342199, self.tradeDate='20230413', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29902.9', self.close='29899.8'
127.0.0.1 - - [13/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19970 

self.closeSec=1681342799, self.tradeDate='20230413', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29899.8', self.close='29860.1'
127.0.0.1 - - [13/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19971 

self.closeSec=1681343399, self.tradeDate='20230413', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29860.1', self.close='29881.6'
127.0.0.1 - - [13/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19972 

self.closeSec=1681343999, self.tradeDate='20230413', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29881.5', self.close='29875'
127.0.0.1 - - [13/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19973 

self.closeSec=1681344599, self.tradeDate='20230413', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29874.9', self.close='29896.4'
127.0.0.1 - - [13/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19974 

self.closeSec=1681345199, self.tradeDate='20230413', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29896.3', self.close='29842.6'
127.0.0.1 - - [13/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19970 

self.closeSec=1681342199, self.tradeDate='20230413', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29902.9', self.close='29899.8'
127.0.0.1 - - [13/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19971 

self.closeSec=1681342799, self.tradeDate='20230413', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29899.8', self.close='29860.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19972 

self.closeSec=1681343399, self.tradeDate='20230413', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29860.1', self.close='29881.6'
127.0.0.1 - - [13/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19973 

self.closeSec=1681343999, self.tradeDate='20230413', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29881.5', self.close='29875'
127.0.0.1 - - [13/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19974 

self.closeSec=1681344599, self.tradeDate='20230413', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29874.9', self.close='29896.4'
127.0.0.1 - - [13/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19975 

self.closeSec=1681345199, self.tradeDate='20230413', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29896.3', self.close='29842.6'
127.0.0.1 - - [13/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19970 

self.closeSec=1681342199, self.tradeDate='20230413', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29902.9', self.close='29899.8'
127.0.0.1 - - [13/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19971 

self.closeSec=1681342799, self.tradeDate='20230413', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29899.8', self.close='29860.1'
127.0.0.1 - - [13/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19972 

self.closeSec=1681343399, self.tradeDate='20230413', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29860.1', self.close='29881.6'
127.0.0.1 - - [13/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19973 

self.closeSec=1681343999, self.tradeDate='20230413', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29881.5', self.close='29875'
127.0.0.1 - - [13/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19974 

self.closeSec=1681344599, self.tradeDate='20230413', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29874.9', self.close='29896.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19975 

self.closeSec=1681345199, self.tradeDate='20230413', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29896.3', self.close='29842.6'
127.0.0.1 - - [13/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35379
self.closeSec=1681345199, self.tradeDate='20230413', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29907.0, self.close=29841.9, self.high=29908.1, self.low=29836.7, self.vol=1188.52, self.amt=35494614.1292 
127.0.0.1 - - [13/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-13 08:20:07,187:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230413   075500    075959  ...         0.0        0.0       0
5849  20230413   080000    080459  ...         0.0        0.0       0
5850  20230413   080500    080959  ...         0.0        0.0       0
5851  20230413   081000    081459  ...         0.0        0.0       0
5852  20230413   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 08:20:07,193:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681345199, self.tradeDate='20230413', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29907.0, self.close=29841.9, self.high=29908.1, self.low=29836.7, self.vol=1188.52, self.amt=35494614.1292, ukdf['pct'].iloc[-1]=-0.002177 , ukdf['amount'].iloc[-1]=35494614.1292, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35380
self.closeSec=1681345499, self.tradeDate='20230413', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29842.6, self.close=29918.0, self.high=29920.0, self.low=29842.6, self.vol=969.804, self.amt=28986836.1688 
127.0.0.1 - - [13/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-13 08:25:01,594:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230413   080000    080459  ...         0.0        0.0       0
5850  20230413   080500    080959  ...         0.0        0.0       0
5851  20230413   081000    081459  ...         0.0        0.0       0
5852  20230413   081500    081959  ...         0.0        0.0       0
5853  20230413   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 08:25:01,596:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681345499, self.tradeDate='20230413', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29842.6, self.close=29918.0, self.high=29920.0, self.low=29842.6, self.vol=969.804, self.amt=28986836.1688, ukdf['pct'].iloc[-1]=0.00255 , ukdf['amount'].iloc[-1]=28986836.1688, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230412   200000    235959  1681315199  ...    719  1.148402  1.602193     1.0
720  20230413   000000    035959  1681329599  ...    720  1.122756  1.503012     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '79229.3805', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29778.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=832
self.closeSec=1681343999, self.tradeDate='20230413', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29789.5, self.close=29875.0, self.high=29970.0, self.low=29761.9, self.vol=40504.038, self.amt=1210339358.4062 
127.0.0.1 - - [13/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-13 08:00:01,928:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681343999, self.tradeDate='20230413', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29789.5, self.close=29875.0, self.high=29970.0, self.low=29761.9, self.vol=40504.038, self.amt=1210339358.4062 
2023-04-13 08:00:01,969:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230412   120000    155959  ...   47788.578  1.430809e+09  0.002159
718  20230412   160000    195959  ...   37903.678  1.135899e+09  0.000811
719  20230412   200000    235959  ...  266359.400  8.017304e+09 -0.001856
720  20230413   000000    035959  ...   77606.552  2.323241e+09 -0.005296
721  20230413   040000    075959  ...   40504.038  1.210339e+09  0.002874

[5 rows x 11 columns]
2023-04-13 08:00:04,665:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230412   120000    155959  1681286399  ...    717  1.174109  1.754042     1.0
718  20230412   160000    195959  1681300799  ...    718  1.126781  1.597307     1.0
719  20230412   200000    235959  1681315199  ...    719  1.148402  1.602193     1.0
720  20230413   000000    035959  1681329599  ...    720  1.122756  1.503012     1.0
721  20230413   040000    075959  1681343999  ...    721  1.082367  1.376775     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '84334.7071159551', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29875.81654034', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


