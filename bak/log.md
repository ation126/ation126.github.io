# 20230428 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43605
self.closeSec=1682612399, self.tradeDate='20230428', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29070.6, self.close=29033.9, self.high=29114.9, self.low=29030.4, self.vol=1406.49, self.amt=40895412.2889 
127.0.0.1 - - [28/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-28 00:20:06,324:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230427   235500    235959  ...         0.0        0.0       0
5753  20230428   000000    000459  ...         0.0        0.0       0
5754  20230428   000500    000959  ...         0.0        0.0       0
5755  20230428   001000    001459  ...         0.0        0.0       0
5756  20230428   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 00:20:06,329:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682612399, self.tradeDate='20230428', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29070.6, self.close=29033.9, self.high=29114.9, self.low=29030.4, self.vol=1406.49, self.amt=40895412.2889, ukdf['pct'].iloc[-1]=-0.001262 , ukdf['amount'].iloc[-1]=40895412.2889, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-752593.63461784464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29035.84138889', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43606
self.closeSec=1682612699, self.tradeDate='20230428', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29034.0, self.close=29040.1, self.high=29073.8, self.low=29001.0, self.vol=2823.103, self.amt=81955960.4115 
127.0.0.1 - - [28/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-28 00:25:01,585:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230428   000000    000459  ...         0.0        0.0       0
5754  20230428   000500    000959  ...         0.0        0.0       0
5755  20230428   001000    001459  ...         0.0        0.0       0
5756  20230428   001500    001959  ...         0.0        0.0       0
5757  20230428   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 00:25:01,586:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682612699, self.tradeDate='20230428', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29034.0, self.close=29040.1, self.high=29073.8, self.low=29001.0, self.vol=2823.103, self.amt=81955960.4115, ukdf['pct'].iloc[-1]=0.000214 , ukdf['amount'].iloc[-1]=81955960.4115, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-753084.5872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [28/Apr/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230423' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44169 

self.closeSec=1682611799, self.tradeDate='20230428', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29111.9, self.close=29066.0, self.high=29123.2, self.low=29062.6 
127.0.0.1 - - [28/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44170 

self.closeSec=1682612099, self.tradeDate='20230428', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29066.0, self.close=29070.6, self.high=29104.8, self.low=29064.7 
127.0.0.1 - - [28/Apr/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44171 

self.closeSec=1682612399, self.tradeDate='20230428', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29070.6, self.close=29033.9, self.high=29114.9, self.low=29030.4 
127.0.0.1 - - [28/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44172 

self.closeSec=1682612699, self.tradeDate='20230428', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29034.0, self.close=29040.1, self.high=29073.8, self.low=29001.0 


## /root/FIL/strategy/logic/log.txt ----- -----

5802  20230427    215959  28875.1  ...  55.416667  0.524285  0.365908
5803  20230427    222959  28920.0  ...  55.416667  0.530001  0.362178
5804  20230427    225959  28994.0  ...  55.000000  0.527451  0.358247
5805  20230427    232959  28964.8  ...  55.416667  0.550303  0.343642

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-04-28 00:00:20,720:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     1  0.498281  0.501719       1  ...  0.843879  -1.0  0.0000  0.953490
540     0  0.501159  0.498841       1  ...  0.841726  -1.0  0.0000  0.955923
541     0  0.523436  0.476564       0  ...  0.842571  -1.0  0.0000  0.954963
542     1  0.497833  0.502167       1  ...  0.833809  -1.0  0.0000  0.964894
543     0  0.586578  0.413422       0  ...  0.828791   1.0 -0.0016  0.960631

[5 rows x 10 columns]
2023-04-28 00:00:20,731:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.498155  0.501845       1  ...  0.843879  -1.0  0.0000  0.954122
46     0  0.501901  0.498099       1  ...  0.841726  -1.0  0.0000  0.957239
47     0  0.523261  0.476739       0  ...  0.842571  -1.0  0.0000  0.955165
48     1  0.498266  0.501734       1  ...  0.833809  -1.0  0.0000  0.965097
49     0  0.586578  0.413422       0  ...  0.828791   1.0 -0.0016  0.960631

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-04-28 00:00:21,252:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '26.251', 'buy' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:765539.5373', 'result': 'success', 'clientorderid': ''}
2023-04-28 00:00:21,270:INFO:logic:main.py:494:insertFactor:885513: curDateTime:4280000, name:logic, symbol:BTCUSDT, tradeDate:20230427, closeTime:235959, close:29136.7, sign:1, total:767183.2585902, side:buy  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [27/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22081 

self.closeSec=1682609399, self.tradeDate='20230427', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29035.8', self.close='29266'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22082 

self.closeSec=1682609999, self.tradeDate='20230427', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29265.9', self.close='29285.4'
127.0.0.1 - - [27/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22083 

self.closeSec=1682610599, self.tradeDate='20230427', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29285.4', self.close='29087.8'
127.0.0.1 - - [28/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22084 

self.closeSec=1682611199, self.tradeDate='20230427', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29084.7', self.close='29136.7'
127.0.0.1 - - [28/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22085 

self.closeSec=1682611799, self.tradeDate='20230428', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29136.6', self.close='29066'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22086 

self.closeSec=1682612399, self.tradeDate='20230428', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29066', self.close='29033.9'
127.0.0.1 - - [28/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22082 

self.closeSec=1682609399, self.tradeDate='20230427', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29035.8', self.close='29266'
127.0.0.1 - - [27/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22083 

self.closeSec=1682609999, self.tradeDate='20230427', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29265.9', self.close='29285.4'
127.0.0.1 - - [27/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22084 

self.closeSec=1682610599, self.tradeDate='20230427', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29285.4', self.close='29087.8'
127.0.0.1 - - [27/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22085 

self.closeSec=1682611199, self.tradeDate='20230427', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29084.7', self.close='29136.7'
127.0.0.1 - - [28/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22086 

self.closeSec=1682611799, self.tradeDate='20230428', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29136.6', self.close='29066'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22087 

self.closeSec=1682612399, self.tradeDate='20230428', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29066', self.close='29033.9'
127.0.0.1 - - [28/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [27/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22082 

self.closeSec=1682609399, self.tradeDate='20230427', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29035.8', self.close='29266'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22083 

self.closeSec=1682609999, self.tradeDate='20230427', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29265.9', self.close='29285.4'
127.0.0.1 - - [27/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22084 

self.closeSec=1682610599, self.tradeDate='20230427', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29285.4', self.close='29087.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22085 

self.closeSec=1682611199, self.tradeDate='20230427', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29084.7', self.close='29136.7'
127.0.0.1 - - [28/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22086 

self.closeSec=1682611799, self.tradeDate='20230428', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29136.6', self.close='29066'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22087 

self.closeSec=1682612399, self.tradeDate='20230428', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29066', self.close='29033.9'
127.0.0.1 - - [28/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39603
self.closeSec=1682612399, self.tradeDate='20230428', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29070.6, self.close=29033.9, self.high=29114.9, self.low=29030.4, self.vol=1406.49, self.amt=40895412.2889 
127.0.0.1 - - [28/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-28 00:20:06,323:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230427   235500    235959  ...         0.0        0.0       0
5753  20230428   000000    000459  ...         0.0        0.0       0
5754  20230428   000500    000959  ...         0.0        0.0       0
5755  20230428   001000    001459  ...         0.0        0.0       0
5756  20230428   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 00:20:06,328:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682612399, self.tradeDate='20230428', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29070.6, self.close=29033.9, self.high=29114.9, self.low=29030.4, self.vol=1406.49, self.amt=40895412.2889, ukdf['pct'].iloc[-1]=-0.001262 , ukdf['amount'].iloc[-1]=40895412.2889, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [28/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39604
self.closeSec=1682612699, self.tradeDate='20230428', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29034.0, self.close=29040.1, self.high=29073.8, self.low=29001.0, self.vol=2823.103, self.amt=81955960.4115 
2023-04-28 00:25:01,572:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230428   000000    000459  ...         0.0        0.0       0
5754  20230428   000500    000959  ...         0.0        0.0       0
5755  20230428   001000    001459  ...         0.0        0.0       0
5756  20230428   001500    001959  ...         0.0        0.0       0
5757  20230428   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 00:25:01,582:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682612699, self.tradeDate='20230428', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29034.0, self.close=29040.1, self.high=29073.8, self.low=29001.0, self.vol=2823.103, self.amt=81955960.4115, ukdf['pct'].iloc[-1]=0.000214 , ukdf['amount'].iloc[-1]=81955960.4115, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230427   120000    155959  1682582399  ...    723  1.012936  1.100041     1.0
724  20230427   160000    195959  1682596799  ...    724  0.910117  0.768211     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '-1029.138', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28926.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  127.0.0.1 - - [28/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1352827.6996185002, self.flagDict['side']='buy', self.tradeCount=32, self.count=920
self.closeSec=1682611199, self.tradeDate='20230427', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28921.2, self.close=29136.7, self.high=29600.0, self.low=28650.0, self.vol=206699.481, self.amt=6004047283.92739 
2023-04-28 00:00:03,199:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682611199, self.tradeDate='20230427', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28921.2, self.close=29136.7, self.high=29600.0, self.low=28650.0, self.vol=206699.481, self.amt=6004047283.92739 
2023-04-28 00:00:03,258:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230427   040000    075959  ...  333531.894  9.343430e+09  0.018534
722  20230427   080000    115959  ...  231823.014  6.719884e+09  0.016929
723  20230427   120000    155959  ...  112459.212  3.256536e+09  0.000118
724  20230427   160000    195959  ...   98201.412  2.844151e+09  0.001427
725  20230427   200000    235959  ...  206699.481  6.004047e+09  0.007451

[5 rows x 11 columns]
2023-04-28 00:00:04,852:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230427   040000    075959  1682553599  ...    721  0.870679  0.595804     NaN
722  20230427   080000    115959  1682567999  ...    722  1.028601  1.137396     1.0
723  20230427   120000    155959  1682582399  ...    723  1.012936  1.100041     1.0
724  20230427   160000    195959  1682596799  ...    724  0.910117  0.768211     1.0
725  20230427   200000    235959  1682611199  ...    725  0.972886  0.997366     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '9135.9387', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29143.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


