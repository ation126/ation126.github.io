# 20230430 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44181
self.closeSec=1682785199, self.tradeDate='20230430', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29258.0, self.close=29262.2, self.high=29268.7, self.low=29254.5, self.vol=322.309, self.amt=9431653.3663 
127.0.0.1 - - [30/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-30 00:20:06,595:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230429   235500    235959  ...         0.0        0.0       0
5753  20230430   000000    000459  ...         0.0        0.0       0
5754  20230430   000500    000959  ...         0.0        0.0       0
5755  20230430   001000    001459  ...         0.0        0.0       0
5756  20230430   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 00:20:06,598:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682785199, self.tradeDate='20230430', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29258.0, self.close=29262.2, self.high=29268.7, self.low=29254.5, self.vol=322.309, self.amt=9431653.3663, ukdf['pct'].iloc[-1]=0.000144 , ukdf['amount'].iloc[-1]=9431653.3663, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-766228.86342077376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29262.43054076', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44182
self.closeSec=1682785499, self.tradeDate='20230430', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29262.3, self.close=29242.4, self.high=29262.4, self.low=29242.4, self.vol=521.462, self.amt=15253533.7972 
127.0.0.1 - - [30/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-30 00:25:01,630:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230430   000000    000459  ...         0.0        0.0       0
5754  20230430   000500    000959  ...         0.0        0.0       0
5755  20230430   001000    001459  ...         0.0        0.0       0
5756  20230430   001500    001959  ...         0.0        0.0       0
5757  20230430   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 00:25:01,632:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682785499, self.tradeDate='20230430', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29262.3, self.close=29242.4, self.high=29262.4, self.low=29242.4, self.vol=521.462, self.amt=15253533.7972, ukdf['pct'].iloc[-1]=-0.000677 , ukdf['amount'].iloc[-1]=15253533.7972, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-765081.95321168928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29243.37127778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [30/Apr/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230425' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [30/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44745 

self.closeSec=1682784599, self.tradeDate='20230430', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29274.6, self.close=29248.7, self.high=29274.7, self.low=29244.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44746 

self.closeSec=1682784899, self.tradeDate='20230430', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29250.0, self.close=29258.0, self.high=29266.5, self.low=29248.9 
127.0.0.1 - - [30/Apr/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44747 

self.closeSec=1682785199, self.tradeDate='20230430', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29258.0, self.close=29262.2, self.high=29268.7, self.low=29254.5 
127.0.0.1 - - [30/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44748 

self.closeSec=1682785499, self.tradeDate='20230430', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29262.3, self.close=29242.4, self.high=29262.4, self.low=29242.4 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-30 00:00:20,900:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230429    212959  29269.1  ...  52.083333  0.521613  0.349351
5802  20230429    215959  29334.3  ...  52.083333  0.527842  0.340076
5803  20230429    222959  29371.9  ...  52.083333  0.523305  0.336961
5804  20230429    225959  29347.2  ...  52.083333  0.518095  0.346024
5805  20230429    232959  29319.1  ...  52.500000  0.518408  0.354028

[5 rows x 33 columns]
0.5698529411764706
acc is : 0.5698529411764706
2023-04-30 00:00:20,989:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.528191  0.471809       1  ...  0.822714  -1.0    0.0  0.987062
540     0  0.527349  0.472651       0  ...  0.823403  -1.0    0.0  0.986235
541     0  0.507392  0.492608       0  ...  0.824195  -1.0    0.0  0.985287
542     0  0.505704  0.494296       1  ...  0.824144  -1.0    0.0  0.985348
543     0  0.512650  0.487350       0  ...  0.825909  -1.0    0.0  0.983238

[5 rows x 10 columns]
2023-04-30 00:00:21,009:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.529482  0.470518       1  ...  0.806091  -1.0    0.0  0.989349
46     0  0.528746  0.471254       0  ...  0.799087  -1.0    0.0  0.988025
47     0  0.508210  0.491790       0  ...  0.799855  -1.0    0.0  0.986839
48     0  0.506119  0.493881       1  ...  0.799806  -1.0    0.0  0.986900
49     0  0.512650  0.487350       0  ...  0.825909  -1.0    0.0  0.983238

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22369 

self.closeSec=1682782199, self.tradeDate='20230429', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29312.2', self.close='29320.9'
127.0.0.1 - - [29/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22370 

self.closeSec=1682782799, self.tradeDate='20230429', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29320.8', self.close='29312'
127.0.0.1 - - [29/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22371 

self.closeSec=1682783399, self.tradeDate='20230429', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29312.1', self.close='29260.3'
127.0.0.1 - - [30/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22372 

self.closeSec=1682783999, self.tradeDate='20230429', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29260.4', self.close='29258.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22373 

self.closeSec=1682784599, self.tradeDate='20230430', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29258', self.close='29248.7'
127.0.0.1 - - [30/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22374 

self.closeSec=1682785199, self.tradeDate='20230430', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29250', self.close='29262.2'
127.0.0.1 - - [30/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [29/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22370 

self.closeSec=1682782199, self.tradeDate='20230429', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29312.2', self.close='29320.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22371 

self.closeSec=1682782799, self.tradeDate='20230429', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29320.8', self.close='29312'
127.0.0.1 - - [29/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22372 

self.closeSec=1682783399, self.tradeDate='20230429', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29312.1', self.close='29260.3'
127.0.0.1 - - [29/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22373 

self.closeSec=1682783999, self.tradeDate='20230429', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29260.4', self.close='29258.1'
127.0.0.1 - - [30/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22374 

self.closeSec=1682784599, self.tradeDate='20230430', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29258', self.close='29248.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22375 

self.closeSec=1682785199, self.tradeDate='20230430', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29250', self.close='29262.2'
127.0.0.1 - - [30/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [29/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22370 

self.closeSec=1682782199, self.tradeDate='20230429', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29312.2', self.close='29320.9'
127.0.0.1 - - [29/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22371 

self.closeSec=1682782799, self.tradeDate='20230429', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29320.8', self.close='29312'
127.0.0.1 - - [29/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22372 

self.closeSec=1682783399, self.tradeDate='20230429', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29312.1', self.close='29260.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22373 

self.closeSec=1682783999, self.tradeDate='20230429', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29260.4', self.close='29258.1'
127.0.0.1 - - [30/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22374 

self.closeSec=1682784599, self.tradeDate='20230430', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29258', self.close='29248.7'
127.0.0.1 - - [30/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22375 

self.closeSec=1682785199, self.tradeDate='20230430', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29250', self.close='29262.2'
127.0.0.1 - - [30/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40179
self.closeSec=1682785199, self.tradeDate='20230430', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29258.0, self.close=29262.2, self.high=29268.7, self.low=29254.5, self.vol=322.309, self.amt=9431653.3663 
127.0.0.1 - - [30/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-30 00:20:06,592:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230429   235500    235959  ...         0.0        0.0       0
5753  20230430   000000    000459  ...         0.0        0.0       0
5754  20230430   000500    000959  ...         0.0        0.0       0
5755  20230430   001000    001459  ...         0.0        0.0       0
5756  20230430   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 00:20:06,595:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682785199, self.tradeDate='20230430', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29258.0, self.close=29262.2, self.high=29268.7, self.low=29254.5, self.vol=322.309, self.amt=9431653.3663, ukdf['pct'].iloc[-1]=0.000144 , ukdf['amount'].iloc[-1]=9431653.3663, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40180
self.closeSec=1682785499, self.tradeDate='20230430', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29262.3, self.close=29242.4, self.high=29262.4, self.low=29242.4, self.vol=521.462, self.amt=15253533.7972 
127.0.0.1 - - [30/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-30 00:25:01,626:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230430   000000    000459  ...         0.0        0.0       0
5754  20230430   000500    000959  ...         0.0        0.0       0
5755  20230430   001000    001459  ...         0.0        0.0       0
5756  20230430   001500    001959  ...         0.0        0.0       0
5757  20230430   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 00:25:01,627:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682785499, self.tradeDate='20230430', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29262.3, self.close=29242.4, self.high=29262.4, self.low=29242.4, self.vol=521.462, self.amt=15253533.7972, ukdf['pct'].iloc[-1]=-0.000677 , ukdf['amount'].iloc[-1]=15253533.7972, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230429   120000    155959  1682755199  ...    723  0.428820 -0.812974    -1.0
724  20230429   160000    195959  1682769599  ...    724  0.328351 -1.150894    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '789.5342', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29324.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [30/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=932
self.closeSec=1682783999, self.tradeDate='20230429', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29323.4, self.close=29258.1, self.high=29385.0, self.low=29200.2, self.vol=38754.353, self.amt=1136094881.8641 
2023-04-30 00:00:03,159:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682783999, self.tradeDate='20230429', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29323.4, self.close=29258.1, self.high=29385.0, self.low=29200.2, self.vol=38754.353, self.amt=1136094881.8641 
2023-04-30 00:00:03,193:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230429   040000    075959  ...  33331.207  9.776626e+08 -0.000600
722  20230429   080000    115959  ...  39776.622  1.165452e+09  0.000983
723  20230429   120000    155959  ...  36929.533  1.083732e+09  0.000174
724  20230429   160000    195959  ...  35064.791  1.026637e+09 -0.000358
725  20230429   200000    235959  ...  38754.353  1.136095e+09 -0.002227

[5 rows x 11 columns]
2023-04-30 00:00:04,728:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230429   040000    075959  1682726399  ...    721  0.588055 -0.271519     NaN
722  20230429   080000    115959  1682740799  ...    722  0.509761 -0.538935     NaN
723  20230429   120000    155959  1682755199  ...    723  0.428820 -0.812974    -1.0
724  20230429   160000    195959  1682769599  ...    724  0.328351 -1.150894    -1.0
725  20230429   200000    235959  1682783999  ...    725  0.222407 -1.497885    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '3758.5758165186', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29260.8475873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


