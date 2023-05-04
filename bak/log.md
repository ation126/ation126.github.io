# 20230505 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45621
self.closeSec=1683217199, self.tradeDate='20230505', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28875.0, self.close=28920.0, self.high=28925.0, self.low=28865.1, self.vol=2021.133, self.amt=58412367.8491 
127.0.0.1 - - [05/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-05 00:20:06,506:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230504   235500    235959  ...         0.0        0.0       0
5760  20230505   000000    000459  ...         0.0        0.0       0
5761  20230505   000500    000959  ...         0.0        0.0       0
5762  20230505   001000    001459  ...         0.0        0.0       0
5763  20230505   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 00:20:06,516:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683217199, self.tradeDate='20230505', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28875.0, self.close=28920.0, self.high=28925.0, self.low=28865.1, self.vol=2021.133, self.amt=58412367.8491, ukdf['pct'].iloc[-1]=0.001562 , ukdf['amount'].iloc[-1]=58412367.8491, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-745354.0348546824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28915.53429365', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45622
self.closeSec=1683217499, self.tradeDate='20230505', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28919.9, self.close=28920.9, self.high=28924.9, self.low=28895.7, self.vol=1157.955, self.amt=33477013.8214 
2023-05-05 00:25:02,054:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230505   000000    000459  ...         0.0        0.0       0
5761  20230505   000500    000959  ...         0.0        0.0       0
5762  20230505   001000    001459  ...         0.0        0.0       0
5763  20230505   001500    001959  ...         0.0        0.0       0
5764  20230505   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 00:25:02,055:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683217499, self.tradeDate='20230505', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28919.9, self.close=28920.9, self.high=28924.9, self.low=28895.7, self.vol=1157.955, self.amt=33477013.8214, ukdf['pct'].iloc[-1]=3.1e-05 , ukdf['amount'].iloc[-1]=33477013.8214, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-745676.9216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28920.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [05/May/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230430' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46185 

self.closeSec=1683216599, self.tradeDate='20230505', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28816.0, self.close=28863.5, self.high=28864.8, self.low=28790.5 
127.0.0.1 - - [05/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46186 

self.closeSec=1683216899, self.tradeDate='20230505', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28863.4, self.close=28874.9, self.high=28884.2, self.low=28829.8 
127.0.0.1 - - [05/May/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46187 

self.closeSec=1683217199, self.tradeDate='20230505', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28875.0, self.close=28920.0, self.high=28925.0, self.low=28865.1 
127.0.0.1 - - [05/May/2023 00:20:03] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [05/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46188 

self.closeSec=1683217499, self.tradeDate='20230505', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28919.9, self.close=28920.9, self.high=28924.9, self.low=28895.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-05 00:00:22,166:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230504    212959  29045.0  ...  51.250000  0.517556  0.218232
5802  20230504    215959  28870.0  ...  50.833333  0.497093  0.239525
5803  20230504    222959  28745.6  ...  51.250000  0.512244  0.253992
5804  20230504    225959  28841.2  ...  51.250000  0.500775  0.271522
5805  20230504    232959  28769.9  ...  51.250000  0.517668  0.283420

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-05-05 00:00:22,257:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     1  0.438335  0.561665       0  ...  0.837069  -1.0 -0.0016  1.037575
540     1  0.444007  0.555993       1  ...  0.834282  -1.0  0.0000  1.041029
541     1  0.495294  0.504706       0  ...  0.836345  -1.0  0.0000  1.038456
542     1  0.455896  0.544104       1  ...  0.833167  -1.0  0.0000  1.042401
543     0  0.507631  0.492369       0  ...  0.834013  -1.0  0.0000  1.041343

[5 rows x 10 columns]
2023-05-05 00:00:22,287:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.437792  0.562208       0  ...  0.837069  -1.0 -0.0016  1.042157
46     1  0.444420  0.555580       1  ...  0.834282  -1.0  0.0000  1.045926
47     1  0.494891  0.505109       0  ...  0.836345  -1.0  0.0000  1.042996
48     1  0.456108  0.543892       1  ...  0.833167  -1.0  0.0000  1.046958
49     0  0.507631  0.492369       0  ...  0.834013  -1.0  0.0000  1.041343

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23089 

self.closeSec=1683214199, self.tradeDate='20230504', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28864.1', self.close='28879.3'
127.0.0.1 - - [04/May/2023 23:30:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23090 

self.closeSec=1683214799, self.tradeDate='20230504', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28879.3', self.close='28842.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23091 

self.closeSec=1683215399, self.tradeDate='20230504', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28842.4', self.close='28849.9'
127.0.0.1 - - [04/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23092 

self.closeSec=1683215999, self.tradeDate='20230504', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28849.9', self.close='28850'
127.0.0.1 - - [05/May/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23093 

self.closeSec=1683216599, self.tradeDate='20230505', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28850', self.close='28863.5'
127.0.0.1 - - [05/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23094 

self.closeSec=1683217199, self.tradeDate='20230505', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28863.4', self.close='28920'
127.0.0.1 - - [05/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [04/May/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23090 

self.closeSec=1683214199, self.tradeDate='20230504', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28864.1', self.close='28879.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23091 

self.closeSec=1683214799, self.tradeDate='20230504', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28879.3', self.close='28842.3'
127.0.0.1 - - [04/May/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23092 

self.closeSec=1683215399, self.tradeDate='20230504', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28842.4', self.close='28849.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23093 

self.closeSec=1683215999, self.tradeDate='20230504', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28849.9', self.close='28850'
127.0.0.1 - - [05/May/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23094 

self.closeSec=1683216599, self.tradeDate='20230505', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28850', self.close='28863.5'
127.0.0.1 - - [05/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23095 

self.closeSec=1683217199, self.tradeDate='20230505', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28863.4', self.close='28920'
127.0.0.1 - - [05/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23090 

self.closeSec=1683214199, self.tradeDate='20230504', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28864.1', self.close='28879.3'
127.0.0.1 - - [04/May/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23091 

self.closeSec=1683214799, self.tradeDate='20230504', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28879.3', self.close='28842.3'
127.0.0.1 - - [04/May/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [04/May/2023 23:50:02] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23092 

self.closeSec=1683215399, self.tradeDate='20230504', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28842.4', self.close='28849.9'

--handleKline--:  127.0.0.1 - - [05/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23093 

self.closeSec=1683215999, self.tradeDate='20230504', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28849.9', self.close='28850'
127.0.0.1 - - [05/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23094 

self.closeSec=1683216599, self.tradeDate='20230505', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28850', self.close='28863.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23095 

self.closeSec=1683217199, self.tradeDate='20230505', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28863.4', self.close='28920'
127.0.0.1 - - [05/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41619
self.closeSec=1683217199, self.tradeDate='20230505', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28875.0, self.close=28920.0, self.high=28925.0, self.low=28865.1, self.vol=2021.133, self.amt=58412367.8491 
127.0.0.1 - - [05/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-05 00:20:06,439:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230504   235500    235959  ...         0.0        0.0       0
5760  20230505   000000    000459  ...         0.0        0.0       0
5761  20230505   000500    000959  ...         0.0        0.0       0
5762  20230505   001000    001459  ...         0.0        0.0       0
5763  20230505   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 00:20:06,448:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683217199, self.tradeDate='20230505', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28875.0, self.close=28920.0, self.high=28925.0, self.low=28865.1, self.vol=2021.133, self.amt=58412367.8491, ukdf['pct'].iloc[-1]=0.001562 , ukdf['amount'].iloc[-1]=58412367.8491, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [05/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41620
self.closeSec=1683217499, self.tradeDate='20230505', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28919.9, self.close=28920.9, self.high=28924.9, self.low=28895.7, self.vol=1157.955, self.amt=33477013.8214 
2023-05-05 00:25:02,070:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230505   000000    000459  ...         0.0        0.0       0
5761  20230505   000500    000959  ...         0.0        0.0       0
5762  20230505   001000    001459  ...         0.0        0.0       0
5763  20230505   001500    001959  ...         0.0        0.0       0
5764  20230505   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 00:25:02,070:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683217499, self.tradeDate='20230505', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28919.9, self.close=28920.9, self.high=28924.9, self.low=28895.7, self.vol=1157.955, self.amt=33477013.8214, ukdf['pct'].iloc[-1]=3.1e-05 , ukdf['amount'].iloc[-1]=33477013.8214, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230504   120000    155959  1683187199  ...    723  0.587248 -0.124703     NaN
724  20230504   160000    195959  1683201599  ...    724  0.643034  0.033319     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '8941.8252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29149.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=962
self.closeSec=1683215999, self.tradeDate='20230504', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29145.0, self.close=28850.0, self.high=29221.5, self.low=28660.0, self.vol=145934.75, self.amt=4214656741.9984 
2023-05-05 00:00:01,905:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683215999, self.tradeDate='20230504', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29145.0, self.close=28850.0, self.high=29221.5, self.low=28660.0, self.vol=145934.75, self.amt=4214656741.9984 
127.0.0.1 - - [05/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-05-05 00:00:01,971:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230504   040000    075959  ...  157117.840  4.540651e+09  0.025066
722  20230504   080000    115959  ...   48827.682  1.418092e+09  0.002285
723  20230504   120000    155959  ...   50341.471  1.465750e+09 -0.001241
724  20230504   160000    195959  ...   78089.723  2.277858e+09  0.003319
725  20230504   200000    235959  ...  145934.750  4.214657e+09 -0.010122

[5 rows x 11 columns]
2023-05-05 00:00:04,517:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230504   040000    075959  1683158399  ...    721  0.558697 -0.207774     NaN
722  20230504   080000    115959  1683172799  ...    722  0.575833 -0.157035     NaN
723  20230504   120000    155959  1683187199  ...    723  0.587248 -0.124703     NaN
724  20230504   160000    195959  1683201599  ...    724  0.643034  0.033319     NaN
725  20230504   200000    235959  1683215999  ...    725  0.693773  0.177212     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '22891.24788997046', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28851.31224603', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


