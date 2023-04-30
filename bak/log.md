# 20230501 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44469
self.closeSec=1682871599, self.tradeDate='20230501', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29712.2, self.close=29754.1, self.high=29800.0, self.low=29706.0, self.vol=2537.225, self.amt=75515646.8502 
127.0.0.1 - - [01/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-01 00:20:06,103:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230430   235500    235959  ...         0.0        0.0       0
5760  20230501   000000    000459  ...         0.0        0.0       0
5761  20230501   000500    000959  ...         0.0        0.0       0
5762  20230501   001000    001459  ...         0.0        0.0       0
5763  20230501   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 00:20:06,107:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682871599, self.tradeDate='20230501', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29712.2, self.close=29754.1, self.high=29800.0, self.low=29706.0, self.vol=2537.225, self.amt=75515646.8502, ukdf['pct'].iloc[-1]=0.001407 , ukdf['amount'].iloc[-1]=75515646.8502, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-795289.58190579744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29745.35925794', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44470
self.closeSec=1682871899, self.tradeDate='20230501', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29754.0, self.close=29723.9, self.high=29788.0, self.low=29711.4, self.vol=1806.368, self.amt=53735690.0344 
127.0.0.1 - - [01/May/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-05-01 00:25:01,619:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230501   000000    000459  ...         0.0        0.0       0
5761  20230501   000500    000959  ...         0.0        0.0       0
5762  20230501   001000    001459  ...         0.0        0.0       0
5763  20230501   001500    001959  ...         0.0        0.0       0
5764  20230501   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 00:25:01,620:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682871899, self.tradeDate='20230501', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29754.0, self.close=29723.9, self.high=29788.0, self.low=29711.4, self.vol=1806.368, self.amt=53735690.0344, ukdf['pct'].iloc[-1]=-0.001015 , ukdf['amount'].iloc[-1]=53735690.0344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-794413.464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29730.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [01/May/2023 00:05:02] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230426' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [01/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45033 

self.closeSec=1682870999, self.tradeDate='20230501', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29815.8, self.close=29780.0, self.high=29828.3, self.low=29754.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45034 

self.closeSec=1682871299, self.tradeDate='20230501', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29780.0, self.close=29712.3, self.high=29800.0, self.low=29694.7 
127.0.0.1 - - [01/May/2023 00:15:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45035 

self.closeSec=1682871599, self.tradeDate='20230501', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29712.2, self.close=29754.1, self.high=29800.0, self.low=29706.0 
127.0.0.1 - - [01/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45036 

self.closeSec=1682871899, self.tradeDate='20230501', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29754.0, self.close=29723.9, self.high=29788.0, self.low=29711.4 


## /root/FIL/strategy/logic/log.txt ----- -----

5802  20230430    215959  29266.1  ...  50.833333  0.517179  0.411739
5803  20230430    222959  29277.9  ...  50.833333  0.512046  0.405576
5804  20230430    225959  29259.6  ...  51.250000  0.541789  0.391636
5805  20230430    232959  29377.0  ...  51.250000  0.627462  0.370986

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-05-01 00:00:24,285:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.522331  0.477669       1  ...  0.852450  -1.0  0.0000  0.973830
540     0  0.519016  0.480984       0  ...  0.852983  -1.0  0.0000  0.973221
541     0  0.513302  0.486698       1  ...  0.849564  -1.0  0.0000  0.977123
542     0  0.545421  0.454579       1  ...  0.837021  -1.0  0.0000  0.991548
543     0  0.626222  0.373778       0  ...  0.831007   1.0 -0.0016  0.986010

[5 rows x 10 columns]
2023-05-01 00:00:24,318:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.522166  0.477834       1  ...  0.852450  -1.0  0.0000  0.972688
46     0  0.519289  0.480711       0  ...  0.852983  -1.0  0.0000  0.975655
47     0  0.512966  0.487034       1  ...  0.849564  -1.0  0.0000  0.976074
48     0  0.544716  0.455284       1  ...  0.862492  -1.0  0.0000  0.990484
49     0  0.626222  0.373778       0  ...  0.831007   1.0 -0.0016  0.986010

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-05-01 00:00:24,561:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '25.802', 'buy' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:765406.0092', 'result': 'success', 'clientorderid': ''}
2023-05-01 00:00:24,588:INFO:logic:main.py:494:insertFactor:885513: curDateTime:5010000, name:logic, symbol:BTCUSDT, tradeDate:20230430, closeTime:235959, close:29644.2, sign:1, total:767183.2585902, side:buy  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22513 

self.closeSec=1682868599, self.tradeDate='20230430', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29835.1', self.close='29810.7'
127.0.0.1 - - [30/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22514 

self.closeSec=1682869199, self.tradeDate='20230430', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29810.7', self.close='29852.1'
127.0.0.1 - - [30/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22515 

self.closeSec=1682869799, self.tradeDate='20230430', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29852.2', self.close='29582.9'
127.0.0.1 - - [01/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22516 

self.closeSec=1682870399, self.tradeDate='20230430', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29592.3', self.close='29644.2'
127.0.0.1 - - [01/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22517 

self.closeSec=1682870999, self.tradeDate='20230501', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29644.4', self.close='29780'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22518 

self.closeSec=1682871599, self.tradeDate='20230501', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29780', self.close='29754.1'
127.0.0.1 - - [01/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [30/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22514 

self.closeSec=1682868599, self.tradeDate='20230430', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29835.1', self.close='29810.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22515 

self.closeSec=1682869199, self.tradeDate='20230430', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29810.7', self.close='29852.1'
127.0.0.1 - - [30/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22516 

self.closeSec=1682869799, self.tradeDate='20230430', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29852.2', self.close='29582.9'
127.0.0.1 - - [01/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22517 

self.closeSec=1682870399, self.tradeDate='20230430', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29592.3', self.close='29644.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22518 

self.closeSec=1682870999, self.tradeDate='20230501', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29644.4', self.close='29780'
127.0.0.1 - - [01/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22519 

self.closeSec=1682871599, self.tradeDate='20230501', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29780', self.close='29754.1'
127.0.0.1 - - [01/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22514 

self.closeSec=1682868599, self.tradeDate='20230430', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29835.1', self.close='29810.7'
127.0.0.1 - - [30/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22515 

self.closeSec=1682869199, self.tradeDate='20230430', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29810.7', self.close='29852.1'
127.0.0.1 - - [30/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22516 

self.closeSec=1682869799, self.tradeDate='20230430', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29852.2', self.close='29582.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22517 

self.closeSec=1682870399, self.tradeDate='20230430', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29592.3', self.close='29644.2'
127.0.0.1 - - [01/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22518 

self.closeSec=1682870999, self.tradeDate='20230501', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29644.4', self.close='29780'
127.0.0.1 - - [01/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22519 

self.closeSec=1682871599, self.tradeDate='20230501', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29780', self.close='29754.1'
127.0.0.1 - - [01/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40467
self.closeSec=1682871599, self.tradeDate='20230501', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29712.2, self.close=29754.1, self.high=29800.0, self.low=29706.0, self.vol=2537.225, self.amt=75515646.8502 
127.0.0.1 - - [01/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-01 00:20:06,003:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230430   235500    235959  ...         0.0        0.0       0
5760  20230501   000000    000459  ...         0.0        0.0       0
5761  20230501   000500    000959  ...         0.0        0.0       0
5762  20230501   001000    001459  ...         0.0        0.0       0
5763  20230501   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 00:20:06,021:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682871599, self.tradeDate='20230501', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29712.2, self.close=29754.1, self.high=29800.0, self.low=29706.0, self.vol=2537.225, self.amt=75515646.8502, ukdf['pct'].iloc[-1]=0.001407 , ukdf['amount'].iloc[-1]=75515646.8502, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/May/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40468
self.closeSec=1682871899, self.tradeDate='20230501', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29754.0, self.close=29723.9, self.high=29788.0, self.low=29711.4, self.vol=1806.368, self.amt=53735690.0344 
2023-05-01 00:25:01,620:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230501   000000    000459  ...         0.0        0.0       0
5761  20230501   000500    000959  ...         0.0        0.0       0
5762  20230501   001000    001459  ...         0.0        0.0       0
5763  20230501   001500    001959  ...         0.0        0.0       0
5764  20230501   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 00:25:01,621:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682871899, self.tradeDate='20230501', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29754.0, self.close=29723.9, self.high=29788.0, self.low=29711.4, self.vol=1806.368, self.amt=53735690.0344, ukdf['pct'].iloc[-1]=-0.001015 , ukdf['amount'].iloc[-1]=53735690.0344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230430   120000    155959  1682841599  ...    723  0.005092 -2.073333    -1.0
724  20230430   160000    195959  1682855999  ...    724  0.001353 -2.033160    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '7320.7106', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29184.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=938
self.closeSec=1682870399, self.tradeDate='20230430', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29184.6, self.close=29644.2, self.high=29950.0, self.low=29169.9, self.vol=142401.479, self.amt=4216873539.16601 
127.0.0.1 - - [01/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-01 00:00:03,213:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682870399, self.tradeDate='20230430', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29184.6, self.close=29644.2, self.high=29950.0, self.low=29169.9, self.vol=142401.479, self.amt=4216873539.16601 
2023-05-01 00:00:03,246:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230430   040000    075959  ...   19822.623  5.787364e+08 -0.000318
722  20230430   080000    115959  ...   25444.574  7.413127e+08 -0.001530
723  20230430   120000    155959  ...   24448.044  7.146395e+08  0.002880
724  20230430   160000    195959  ...   33318.971  9.743884e+08 -0.002304
725  20230430   200000    235959  ...  142401.479  4.216874e+09  0.015748

[5 rows x 11 columns]
2023-05-01 00:00:04,825:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230430   040000    075959  1682812799  ...    721  0.041425 -2.057776    -1.0
722  20230430   080000    115959  1682827199  ...    722  0.013603 -2.105147    -1.0
723  20230430   120000    155959  1682841599  ...    723  0.005092 -2.073333    -1.0
724  20230430   160000    195959  1682855999  ...    724  0.001353 -2.033160    -1.0
725  20230430   200000    235959  1682870399  ...    725  0.001188 -1.987370    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '-14440.5338', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29650.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


