# 20230422 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41877
self.closeSec=1682093999, self.tradeDate='20230422', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28043.9, self.close=28079.1, self.high=28086.4, self.low=28028.4, self.vol=2681.742, self.amt=75254637.8747 
127.0.0.1 - - [22/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-04-22 00:20:03,945:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230421   235500    235959  ...         0.0        0.0       0
5753  20230422   000000    000459  ...         0.0        0.0       0
5754  20230422   000500    000959  ...         0.0        0.0       0
5755  20230422   001000    001459  ...         0.0        0.0       0
5756  20230422   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 00:20:03,949:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682093999, self.tradeDate='20230422', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28043.9, self.close=28079.1, self.high=28086.4, self.low=28028.4, self.vol=2681.742, self.amt=75254637.8747, ukdf['pct'].iloc[-1]=0.001252 , ukdf['amount'].iloc[-1]=75254637.8747, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695164.80763927824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28081.49369249', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41878
self.closeSec=1682094299, self.tradeDate='20230422', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28079.2, self.close=28029.7, self.high=28084.1, self.low=28020.1, self.vol=1573.744, self.amt=44140741.3392 
2023-04-22 00:25:01,559:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230422   000000    000459  ...         0.0        0.0       0
5754  20230422   000500    000959  ...         0.0        0.0       0
5755  20230422   001000    001459  ...         0.0        0.0       0
5756  20230422   001500    001959  ...         0.0        0.0       0
5757  20230422   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 00:25:01,559:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682094299, self.tradeDate='20230422', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28079.2, self.close=28029.7, self.high=28084.1, self.low=28020.1, self.vol=1573.744, self.amt=44140741.3392, ukdf['pct'].iloc[-1]=-0.001759 , ukdf['amount'].iloc[-1]=44140741.3392, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-692098.26984021632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28030.53421032', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [22/Apr/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230417' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [22/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42441 

self.closeSec=1682093399, self.tradeDate='20230422', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28035.6, self.close=27987.2, self.high=28042.9, self.low=27970.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42442 

self.closeSec=1682093699, self.tradeDate='20230422', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27987.1, self.close=28044.0, self.high=28044.4, self.low=27962.3 
127.0.0.1 - - [22/Apr/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42443 

self.closeSec=1682093999, self.tradeDate='20230422', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28043.9, self.close=28079.1, self.high=28086.4, self.low=28028.4 
127.0.0.1 - - [22/Apr/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42444 

self.closeSec=1682094299, self.tradeDate='20230422', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28079.2, self.close=28029.7, self.high=28084.1, self.low=28020.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-22 00:00:18,781:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230421    212959  28206.6  ...  49.583333  0.431612  0.721333
5802  20230421    215959  28153.5  ...  49.166667  0.425396  0.711747
5803  20230421    222959  28103.9  ...  49.166667  0.436876  0.688113
5804  20230421    225959  28172.8  ...  48.750000  0.421344  0.679797
5805  20230421    232959  28048.4  ...  48.750000  0.425166  0.669363

[5 rows x 33 columns]
0.49816176470588236
acc is : 0.49816176470588236
2023-04-22 00:00:18,875:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.532454  0.467546       0  ...  0.921996   1.0    0.0  0.993840
540     0  0.528636  0.471364       1  ...  0.924253   1.0    0.0  0.996273
541     0  0.555327  0.444673       0  ...  0.920172   1.0    0.0  0.991874
542     1  0.495948  0.504052       1  ...  0.920920   1.0    0.0  0.992680
543     0  0.526861  0.473139       0  ...  0.919660   1.0    0.0  0.991322

[5 rows x 10 columns]
2023-04-22 00:00:18,896:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.532585  0.467415       0  ...  0.921996   1.0    0.0  0.994068
46     0  0.529376  0.470624       1  ...  0.924253   1.0    0.0  0.997197
47     0  0.555874  0.444126       0  ...  0.920172   1.0    0.0  0.992590
48     1  0.496327  0.503673       1  ...  0.920920   1.0    0.0  0.993397
49     0  0.526861  0.473139       0  ...  0.919660   1.0    0.0  0.991322

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21217 

self.closeSec=1682090999, self.tradeDate='20230421', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28042.9', self.close='28071.2'
127.0.0.1 - - [21/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21218 

self.closeSec=1682091599, self.tradeDate='20230421', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28071.3', self.close='28079.8'
127.0.0.1 - - [21/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21219 

self.closeSec=1682092199, self.tradeDate='20230421', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28079.8', self.close='28013.8'
127.0.0.1 - - [22/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21220 

self.closeSec=1682092799, self.tradeDate='20230421', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28013.8', self.close='28032.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21221 

self.closeSec=1682093399, self.tradeDate='20230422', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28032.8', self.close='27987.2'
127.0.0.1 - - [22/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21222 

self.closeSec=1682093999, self.tradeDate='20230422', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27987.1', self.close='28079.1'
127.0.0.1 - - [22/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21218 

self.closeSec=1682090999, self.tradeDate='20230421', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28042.9', self.close='28071.2'
127.0.0.1 - - [21/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21219 

self.closeSec=1682091599, self.tradeDate='20230421', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28071.3', self.close='28079.8'
127.0.0.1 - - [21/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21220 

self.closeSec=1682092199, self.tradeDate='20230421', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28079.8', self.close='28013.8'
127.0.0.1 - - [21/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21221 

self.closeSec=1682092799, self.tradeDate='20230421', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28013.8', self.close='28032.8'
127.0.0.1 - - [22/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21222 

self.closeSec=1682093399, self.tradeDate='20230422', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28032.8', self.close='27987.2'
127.0.0.1 - - [22/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21223 

self.closeSec=1682093999, self.tradeDate='20230422', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27987.1', self.close='28079.1'
127.0.0.1 - - [22/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21218 

self.closeSec=1682090999, self.tradeDate='20230421', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28042.9', self.close='28071.2'
127.0.0.1 - - [21/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21219 

self.closeSec=1682091599, self.tradeDate='20230421', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28071.3', self.close='28079.8'
127.0.0.1 - - [21/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21220 

self.closeSec=1682092199, self.tradeDate='20230421', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28079.8', self.close='28013.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21221 

self.closeSec=1682092799, self.tradeDate='20230421', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28013.8', self.close='28032.8'
127.0.0.1 - - [22/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21222 

self.closeSec=1682093399, self.tradeDate='20230422', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28032.8', self.close='27987.2'
127.0.0.1 - - [22/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21223 

self.closeSec=1682093999, self.tradeDate='20230422', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27987.1', self.close='28079.1'
127.0.0.1 - - [22/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37875
self.closeSec=1682093999, self.tradeDate='20230422', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28043.9, self.close=28079.1, self.high=28086.4, self.low=28028.4, self.vol=2681.742, self.amt=75254637.8747 
127.0.0.1 - - [22/Apr/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-04-22 00:20:01,612:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230421   235500    235959  ...         0.0        0.0       0
5753  20230422   000000    000459  ...         0.0        0.0       0
5754  20230422   000500    000959  ...         0.0        0.0       0
5755  20230422   001000    001459  ...         0.0        0.0       0
5756  20230422   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 00:20:01,615:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682093999, self.tradeDate='20230422', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28043.9, self.close=28079.1, self.high=28086.4, self.low=28028.4, self.vol=2681.742, self.amt=75254637.8747, ukdf['pct'].iloc[-1]=0.001252 , ukdf['amount'].iloc[-1]=75254637.8747, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37876
self.closeSec=1682094299, self.tradeDate='20230422', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28079.2, self.close=28029.7, self.high=28084.1, self.low=28020.1, self.vol=1573.744, self.amt=44140741.3392 
127.0.0.1 - - [22/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-22 00:25:01,555:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230422   000000    000459  ...         0.0        0.0       0
5754  20230422   000500    000959  ...         0.0        0.0       0
5755  20230422   001000    001459  ...         0.0        0.0       0
5756  20230422   001500    001959  ...         0.0        0.0       0
5757  20230422   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 00:25:01,555:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682094299, self.tradeDate='20230422', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28079.2, self.close=28029.7, self.high=28084.1, self.low=28020.1, self.vol=1573.744, self.amt=44140741.3392, ukdf['pct'].iloc[-1]=-0.001759 , ukdf['amount'].iloc[-1]=44140741.3392, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230421   120000    155959  1682063999  ...    723  0.725958  0.377815     NaN
724  20230421   160000    195959  1682078399  ...    724  0.788889  0.510818     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-11280.94574860125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28055.08621825', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [22/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=884
self.closeSec=1682092799, self.tradeDate='20230421', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28054.5, self.close=28032.8, self.high=28300.0, self.low=27954.4, self.vol=126677.763, self.amt=3563100200.67609 
2023-04-22 00:00:01,803:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682092799, self.tradeDate='20230421', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28054.5, self.close=28032.8, self.high=28300.0, self.low=27954.4, self.vol=126677.763, self.amt=3563100200.67609 
2023-04-22 00:00:01,859:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230421   040000    075959  ...   69632.679  1.964323e+09  0.004920
722  20230421   080000    115959  ...   58395.542  1.648645e+09  0.002806
723  20230421   120000    155959  ...  119795.709  3.357784e+09 -0.005892
724  20230421   160000    195959  ...   80831.360  2.267150e+09 -0.003120
725  20230421   200000    235959  ...  126677.763  3.563100e+09 -0.000773

[5 rows x 11 columns]
2023-04-22 00:00:03,780:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230421   040000    075959  1682035199  ...    721  0.659259  0.250416     NaN
722  20230421   080000    115959  1682049599  ...    722  0.723722  0.386529     NaN
723  20230421   120000    155959  1682063999  ...    723  0.725958  0.377815     NaN
724  20230421   160000    195959  1682078399  ...    724  0.788889  0.510818     NaN
725  20230421   200000    235959  1682092799  ...    725  0.809080  0.543306     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-12451.3065', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28032.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


