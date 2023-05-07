# 20230508 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46485
self.closeSec=1683476399, self.tradeDate='20230508', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28958.4, self.close=28910.2, self.high=28961.7, self.low=28901.4, self.vol=680.267, self.amt=19680034.441 
127.0.0.1 - - [08/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-08 00:20:06,688:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230507   235500    235959  ...         0.0        0.0       0
5760  20230508   000000    000459  ...         0.0        0.0       0
5761  20230508   000500    000959  ...         0.0        0.0       0
5762  20230508   001000    001459  ...         0.0        0.0       0
5763  20230508   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 00:20:06,699:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683476399, self.tradeDate='20230508', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28958.4, self.close=28910.2, self.high=28961.7, self.low=28901.4, self.vol=680.267, self.amt=19680034.441, ukdf['pct'].iloc[-1]=-0.001664 , ukdf['amount'].iloc[-1]=19680034.441, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-745159.408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28912.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46486
self.closeSec=1683476699, self.tradeDate='20230508', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28910.1, self.close=28856.8, self.high=28914.6, self.low=28856.3, self.vol=1457.993, self.amt=42113655.1034 
127.0.0.1 - - [08/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-08 00:25:02,145:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230508   000000    000459  ...         0.0        0.0       0
5761  20230508   000500    000959  ...         0.0        0.0       0
5762  20230508   001000    001459  ...         0.0        0.0       0
5763  20230508   001500    001959  ...         0.0        0.0       0
5764  20230508   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 00:25:02,147:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683476699, self.tradeDate='20230508', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28910.1, self.close=28856.8, self.high=28914.6, self.low=28856.3, self.vol=1457.993, self.amt=42113655.1034, ukdf['pct'].iloc[-1]=-0.001847 , ukdf['amount'].iloc[-1]=42113655.1034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-742116.39316783088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28861.73142063', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [08/May/2023 00:05:02] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230503' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47049 

self.closeSec=1683475799, self.tradeDate='20230508', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28948.0, self.close=28909.9, self.high=28948.2, self.low=28906.0 
127.0.0.1 - - [08/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47050 

self.closeSec=1683476099, self.tradeDate='20230508', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28909.9, self.close=28958.4, self.high=28963.0, self.low=28899.9 
127.0.0.1 - - [08/May/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47051 

self.closeSec=1683476399, self.tradeDate='20230508', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28958.4, self.close=28910.2, self.high=28961.7, self.low=28901.4 
127.0.0.1 - - [08/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 00:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47052 

self.closeSec=1683476699, self.tradeDate='20230508', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28910.1, self.close=28856.8, self.high=28914.6, self.low=28856.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-08 00:00:21,798:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230507    212959  28905.1  ...  50.416667  0.484797  0.487475
5802  20230507    215959  28895.3  ...  50.833333  0.487703  0.484427
5803  20230507    222959  28908.6  ...  50.833333  0.490025  0.480215
5804  20230507    225959  28919.2  ...  51.250000  0.513909  0.461759
5805  20230507    232959  29031.9  ...  50.833333  0.492525  0.457729

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-05-08 00:00:21,893:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.502248  0.497752       1  ...  0.981432  -1.0    0.0  1.019168
540     0  0.514662  0.485338       1  ...  0.981072  -1.0    0.0  1.019542
541     0  0.507873  0.492127       1  ...  0.977252  -1.0    0.0  1.023511
542     0  0.530691  0.469309       0  ...  0.980696  -1.0    0.0  1.019905
543     1  0.481509  0.518491       1  ...  0.980577  -1.0    0.0  1.020028

[5 rows x 10 columns]
2023-05-08 00:00:21,918:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502501  0.497499       1  ...  0.981432  -1.0    0.0  1.019765
46     0  0.514618  0.485382       1  ...  0.981072  -1.0    0.0  1.019089
47     0  0.508123  0.491877       1  ...  0.977252  -1.0    0.0  1.024411
48     0  0.530962  0.469038       0  ...  0.980696  -1.0    0.0  1.020801
49     1  0.481509  0.518491       1  ...  0.980577  -1.0    0.0  1.020028

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [07/May/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23521 

self.closeSec=1683473399, self.tradeDate='20230507', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28946.5', self.close='28929.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23522 

self.closeSec=1683473999, self.tradeDate='20230507', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28929.7', self.close='28933.3'
127.0.0.1 - - [07/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23523 

self.closeSec=1683474599, self.tradeDate='20230507', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28933.2', self.close='28943'
127.0.0.1 - - [07/May/2023 23:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23524 

self.closeSec=1683475199, self.tradeDate='20230507', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28943', self.close='28933.1'
127.0.0.1 - - [08/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23525 

self.closeSec=1683475799, self.tradeDate='20230508', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28933.1', self.close='28909.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23526 

self.closeSec=1683476399, self.tradeDate='20230508', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28909.9', self.close='28910.2'
127.0.0.1 - - [08/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23522 

self.closeSec=1683473399, self.tradeDate='20230507', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28946.5', self.close='28929.6'
127.0.0.1 - - [07/May/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23523 

self.closeSec=1683473999, self.tradeDate='20230507', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28929.7', self.close='28933.3'
127.0.0.1 - - [07/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23524 

self.closeSec=1683474599, self.tradeDate='20230507', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28933.2', self.close='28943'
127.0.0.1 - - [08/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23525 

self.closeSec=1683475199, self.tradeDate='20230507', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28943', self.close='28933.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23526 

self.closeSec=1683475799, self.tradeDate='20230508', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28933.1', self.close='28909.9'
127.0.0.1 - - [08/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23527 

self.closeSec=1683476399, self.tradeDate='20230508', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28909.9', self.close='28910.2'
127.0.0.1 - - [08/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [07/May/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23522 

self.closeSec=1683473399, self.tradeDate='20230507', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28946.5', self.close='28929.6'
127.0.0.1 - - [07/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23523 

self.closeSec=1683473999, self.tradeDate='20230507', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28929.7', self.close='28933.3'
127.0.0.1 - - [07/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23524 

self.closeSec=1683474599, self.tradeDate='20230507', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28933.2', self.close='28943'
127.0.0.1 - - [08/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23525 

self.closeSec=1683475199, self.tradeDate='20230507', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28943', self.close='28933.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23526 

self.closeSec=1683475799, self.tradeDate='20230508', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28933.1', self.close='28909.9'
127.0.0.1 - - [08/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23527 

self.closeSec=1683476399, self.tradeDate='20230508', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28909.9', self.close='28910.2'
127.0.0.1 - - [08/May/2023 00:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42483
self.closeSec=1683476399, self.tradeDate='20230508', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28958.4, self.close=28910.2, self.high=28961.7, self.low=28901.4, self.vol=680.267, self.amt=19680034.441 
127.0.0.1 - - [08/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-08 00:20:06,687:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230507   235500    235959  ...         0.0        0.0       0
5760  20230508   000000    000459  ...         0.0        0.0       0
5761  20230508   000500    000959  ...         0.0        0.0       0
5762  20230508   001000    001459  ...         0.0        0.0       0
5763  20230508   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 00:20:06,701:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683476399, self.tradeDate='20230508', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28958.4, self.close=28910.2, self.high=28961.7, self.low=28901.4, self.vol=680.267, self.amt=19680034.441, ukdf['pct'].iloc[-1]=-0.001664 , ukdf['amount'].iloc[-1]=19680034.441, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42484
self.closeSec=1683476699, self.tradeDate='20230508', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28910.1, self.close=28856.8, self.high=28914.6, self.low=28856.3, self.vol=1457.993, self.amt=42113655.1034 
127.0.0.1 - - [08/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-08 00:25:02,143:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230508   000000    000459  ...         0.0        0.0       0
5761  20230508   000500    000959  ...         0.0        0.0       0
5762  20230508   001000    001459  ...         0.0        0.0       0
5763  20230508   001500    001959  ...         0.0        0.0       0
5764  20230508   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 00:25:02,144:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683476699, self.tradeDate='20230508', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28910.1, self.close=28856.8, self.high=28914.6, self.low=28856.3, self.vol=1457.993, self.amt=42113655.1034, ukdf['pct'].iloc[-1]=-0.001847 , ukdf['amount'].iloc[-1]=42113655.1034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230507   120000    155959  1683446399  ...    723  0.262112 -1.028641    -1.0
724  20230507   160000    195959  1683460799  ...    724  0.233096 -1.092998    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '23643.9798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28835.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [08/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=980
self.closeSec=1683475199, self.tradeDate='20230507', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28826.5, self.close=28933.1, self.high=29088.3, self.low=28825.0, self.vol=58996.19, self.amt=1707798488.8809 
2023-05-08 00:00:03,153:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683475199, self.tradeDate='20230507', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28826.5, self.close=28933.1, self.high=29088.3, self.low=28825.0, self.vol=58996.19, self.amt=1707798488.8809 
2023-05-08 00:00:03,221:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230507   040000    075959  ...  38973.798  1.121836e+09  0.000205
722  20230507   080000    115959  ...  63343.561  1.830321e+09 -0.001630
723  20230507   120000    155959  ...  27761.690  8.013814e+08  0.003512
724  20230507   160000    195959  ...  44539.548  1.283918e+09 -0.002264
725  20230507   200000    235959  ...  58996.190  1.707798e+09  0.003698

[5 rows x 11 columns]
2023-05-08 00:00:05,261:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230507   040000    075959  1683417599  ...    721  0.308148 -0.931649    -1.0
722  20230507   080000    115959  1683431999  ...    722  0.301008 -0.932714    -1.0
723  20230507   120000    155959  1683446399  ...    723  0.262112 -1.028641    -1.0
724  20230507   160000    195959  1683460799  ...    724  0.233096 -1.092998    -1.0
725  20230507   200000    235959  1683475199  ...    725  0.210014 -1.138046    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '18902.1028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28936.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


