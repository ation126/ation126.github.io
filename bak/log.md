# 20230424 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42453
self.closeSec=1682266799, self.tradeDate='20230424', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27389.7, self.close=27444.4, self.high=27444.4, self.low=27389.6, self.vol=1805.625, self.amt=49501542.4501 
127.0.0.1 - - [24/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-24 00:20:05,019:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230423   235500    235959  ...         0.0        0.0       0
5753  20230424   000000    000459  ...         0.0        0.0       0
5754  20230424   000500    000959  ...         0.0        0.0       0
5755  20230424   001000    001459  ...         0.0        0.0       0
5756  20230424   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 00:20:05,022:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682266799, self.tradeDate='20230424', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27389.7, self.close=27444.4, self.high=27444.4, self.low=27389.6, self.vol=1805.625, self.amt=49501542.4501, ukdf['pct'].iloc[-1]=0.002067 , ukdf['amount'].iloc[-1]=49501542.4501, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-656905.52328342576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27445.70393651', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42454
self.closeSec=1682267099, self.tradeDate='20230424', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27444.3, self.close=27464.4, self.high=27474.2, self.low=27440.8, self.vol=1526.165, self.amt=41907248.6583 
127.0.0.1 - - [24/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-24 00:25:01,571:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230424   000000    000459  ...         0.0        0.0       0
5754  20230424   000500    000959  ...         0.0        0.0       0
5755  20230424   001000    001459  ...         0.0        0.0       0
5756  20230424   001500    001959  ...         0.0        0.0       0
5757  20230424   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 00:25:01,571:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682267099, self.tradeDate='20230424', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27444.3, self.close=27464.4, self.high=27474.2, self.low=27440.8, self.vol=1526.165, self.amt=41907248.6583, ukdf['pct'].iloc[-1]=0.000729 , ukdf['amount'].iloc[-1]=41907248.6583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-658030.5776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27464.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1682265899, self.tradeDate='20230424', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27460.2, self.close=27462.5, self.high=27468.7, self.low=27441.2 

--ukdf-hist--: overDate='20230419' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [24/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43017 

self.closeSec=1682266199, self.tradeDate='20230424', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27462.5, self.close=27441.5, self.high=27462.5, self.low=27431.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43018 

self.closeSec=1682266499, self.tradeDate='20230424', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27441.4, self.close=27387.8, self.high=27441.5, self.low=27355.5 
127.0.0.1 - - [24/Apr/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43019 

self.closeSec=1682266799, self.tradeDate='20230424', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27389.7, self.close=27444.4, self.high=27444.4, self.low=27389.6 
127.0.0.1 - - [24/Apr/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43020 

self.closeSec=1682267099, self.tradeDate='20230424', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27444.3, self.close=27464.4, self.high=27474.2, self.low=27440.8 
127.0.0.1 - - [24/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-24 00:00:19,549:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230423    212959  27594.1  ...  49.583333  0.479625  0.463099
5802  20230423    215959  27597.0  ...  49.583333  0.483277  0.468848
5803  20230423    222959  27614.6  ...  50.000000  0.485467  0.472820
5804  20230423    225959  27625.0  ...  49.583333  0.468686  0.488060
5805  20230423    232959  27539.0  ...  49.583333  0.441213  0.510441

[5 rows x 33 columns]
0.53125
acc is : 0.53125
2023-04-24 00:00:19,630:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.514256  0.485744       1  ...  0.889957   1.0    0.0  0.921119
540     0  0.516286  0.483714       1  ...  0.890292   1.0    0.0  0.921466
541     0  0.507977  0.492023       0  ...  0.887517   1.0    0.0  0.918594
542     1  0.479422  0.520578       0  ...  0.882619   1.0    0.0  0.913524
543     1  0.460354  0.539646       1  ...  0.884981   1.0    0.0  0.915969

[5 rows x 10 columns]
2023-04-24 00:00:19,642:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514632  0.485368       1  ...  0.889957   1.0    0.0  0.923695
46     0  0.516291  0.483709       1  ...  0.890292   1.0    0.0  0.923265
47     0  0.507656  0.492344       0  ...  0.887517   1.0    0.0  0.917132
48     1  0.478901  0.521099       0  ...  0.882619   1.0    0.0  0.912070
49     1  0.460354  0.539646       1  ...  0.884981   1.0    0.0  0.915969

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21505 

self.closeSec=1682263799, self.tradeDate='20230423', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27340', self.close='27386.9'
127.0.0.1 - - [23/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21506 

self.closeSec=1682264399, self.tradeDate='20230423', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27387', self.close='27386.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21507 

self.closeSec=1682264999, self.tradeDate='20230423', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27386.6', self.close='27407.9'
127.0.0.1 - - [23/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21508 

self.closeSec=1682265599, self.tradeDate='20230423', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27404.3', self.close='27460.2'
127.0.0.1 - - [24/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21509 

self.closeSec=1682266199, self.tradeDate='20230424', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27460.2', self.close='27441.5'
127.0.0.1 - - [24/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21510 

self.closeSec=1682266799, self.tradeDate='20230424', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27441.4', self.close='27444.4'
127.0.0.1 - - [24/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [23/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21506 

self.closeSec=1682263799, self.tradeDate='20230423', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27340', self.close='27386.9'
127.0.0.1 - - [23/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21507 

self.closeSec=1682264399, self.tradeDate='20230423', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27387', self.close='27386.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21508 

self.closeSec=1682264999, self.tradeDate='20230423', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27386.6', self.close='27407.9'
127.0.0.1 - - [23/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21509 

self.closeSec=1682265599, self.tradeDate='20230423', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27404.3', self.close='27460.2'
127.0.0.1 - - [24/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21510 

self.closeSec=1682266199, self.tradeDate='20230424', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27460.2', self.close='27441.5'
127.0.0.1 - - [24/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21511 

self.closeSec=1682266799, self.tradeDate='20230424', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27441.4', self.close='27444.4'
127.0.0.1 - - [24/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21506 

self.closeSec=1682263799, self.tradeDate='20230423', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27340', self.close='27386.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21507 

self.closeSec=1682264399, self.tradeDate='20230423', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27387', self.close='27386.6'
127.0.0.1 - - [23/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21508 

self.closeSec=1682264999, self.tradeDate='20230423', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27386.6', self.close='27407.9'
127.0.0.1 - - [23/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21509 

self.closeSec=1682265599, self.tradeDate='20230423', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27404.3', self.close='27460.2'
127.0.0.1 - - [24/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21510 

self.closeSec=1682266199, self.tradeDate='20230424', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27460.2', self.close='27441.5'
127.0.0.1 - - [24/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21511 

self.closeSec=1682266799, self.tradeDate='20230424', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27441.4', self.close='27444.4'
127.0.0.1 - - [24/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38451
self.closeSec=1682266799, self.tradeDate='20230424', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27389.7, self.close=27444.4, self.high=27444.4, self.low=27389.6, self.vol=1805.625, self.amt=49501542.4501 
127.0.0.1 - - [24/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-04-24 00:20:05,029:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230423   235500    235959  ...         0.0        0.0       0
5753  20230424   000000    000459  ...         0.0        0.0       0
5754  20230424   000500    000959  ...         0.0        0.0       0
5755  20230424   001000    001459  ...         0.0        0.0       0
5756  20230424   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 00:20:05,032:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682266799, self.tradeDate='20230424', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27389.7, self.close=27444.4, self.high=27444.4, self.low=27389.6, self.vol=1805.625, self.amt=49501542.4501, ukdf['pct'].iloc[-1]=0.002067 , ukdf['amount'].iloc[-1]=49501542.4501, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38452
self.closeSec=1682267099, self.tradeDate='20230424', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27444.3, self.close=27464.4, self.high=27474.2, self.low=27440.8, self.vol=1526.165, self.amt=41907248.6583 
127.0.0.1 - - [24/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-24 00:25:01,542:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230424   000000    000459  ...         0.0        0.0       0
5754  20230424   000500    000959  ...         0.0        0.0       0
5755  20230424   001000    001459  ...         0.0        0.0       0
5756  20230424   001500    001959  ...         0.0        0.0       0
5757  20230424   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 00:25:01,542:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682267099, self.tradeDate='20230424', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27444.3, self.close=27464.4, self.high=27474.2, self.low=27440.8, self.vol=1526.165, self.amt=41907248.6583, ukdf['pct'].iloc[-1]=0.000729 , ukdf['amount'].iloc[-1]=41907248.6583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230423   120000    155959  1682236799  ...    723  1.089573  1.040425     1.0
724  20230423   160000    195959  1682251199  ...    724  1.183101  1.241545     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-33252.498', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27636.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [24/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=896
self.closeSec=1682265599, self.tradeDate='20230423', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27632.8, self.close=27460.2, self.high=27729.0, self.low=27279.7, self.vol=70478.522, self.amt=1940021734.22536 
2023-04-24 00:00:01,794:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682265599, self.tradeDate='20230423', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27632.8, self.close=27460.2, self.high=27729.0, self.low=27279.7, self.vol=70478.522, self.amt=1940021734.22536 
2023-04-24 00:00:01,854:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230423   040000    075959  ...  52141.270  1.446621e+09  0.007336
722  20230423   080000    115959  ...  66658.757  1.837779e+09 -0.009422
723  20230423   120000    155959  ...  32611.861  9.003692e+08  0.005787
724  20230423   160000    195959  ...  49943.657  1.378846e+09 -0.002592
725  20230423   200000    235959  ...  70478.522  1.940022e+09 -0.006246

[5 rows x 11 columns]
2023-04-24 00:00:03,667:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230423   040000    075959  1682207999  ...    721  0.988576  0.835122     1.0
722  20230423   080000    115959  1682222399  ...    722  1.018294  0.888383     1.0
723  20230423   120000    155959  1682236799  ...    723  1.089573  1.040425     1.0
724  20230423   160000    195959  1682251199  ...    724  1.183101  1.241545     1.0
725  20230423   200000    235959  1682265599  ...    725  1.054536  0.905609     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-42531.8676579405', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27460.0005873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


