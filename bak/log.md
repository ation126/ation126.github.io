# 20230925 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38452
self.closeSec=1695572399, self.tradeDate='20230925', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26570.3, self.close=26562.1, self.high=26573.3, self.low=26562.0, self.vol=222.564, self.amt=5913360.5818 
127.0.0.1 - - [25/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-25 00:20:06,101:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230924   235500    235959  ...         0.0        0.0       0
5760  20230925   000000    000459  ...         0.0        0.0       0
5761  20230925   000500    000959  ...         0.0        0.0       0
5762  20230925   001000    001459  ...         0.0        0.0       0
5763  20230925   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 00:20:06,105:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695572399, self.tradeDate='20230925', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26570.3, self.close=26562.1, self.high=26573.3, self.low=26562.0, self.vol=222.564, self.amt=5913360.5818, ukdf['pct'].iloc[-1]=-0.000309 , ukdf['amount'].iloc[-1]=5913360.5818, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4195.174418787', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26563.6523755', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38453
self.closeSec=1695572699, self.tradeDate='20230925', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26562.0, self.close=26558.6, self.high=26562.1, self.low=26558.5, self.vol=70.825, self.amt=1881118.6296 
2023-09-25 00:25:00,785:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230925   000000    000459  ...         0.0        0.0       0
5761  20230925   000500    000959  ...         0.0        0.0       0
5762  20230925   001000    001459  ...         0.0        0.0       0
5763  20230925   001500    001959  ...         0.0        0.0       0
5764  20230925   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 00:25:00,786:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695572699, self.tradeDate='20230925', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26562.0, self.close=26558.6, self.high=26562.1, self.low=26558.5, self.vol=70.825, self.amt=1881118.6296, ukdf['pct'].iloc[-1]=-0.000132 , ukdf['amount'].iloc[-1]=1881118.6296, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4260.07217222598', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26558.99218927', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [25/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230920' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [25/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38452 

self.closeSec=1695571799, self.tradeDate='20230925', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26566.0, self.close=26560.9, self.high=26566.1, self.low=26560.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38453 

self.closeSec=1695572099, self.tradeDate='20230925', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26560.9, self.close=26570.3, self.high=26570.3, self.low=26560.9 
127.0.0.1 - - [25/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38454 

self.closeSec=1695572399, self.tradeDate='20230925', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26570.3, self.close=26562.1, self.high=26573.3, self.low=26562.0 
127.0.0.1 - - [25/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38455 

self.closeSec=1695572699, self.tradeDate='20230925', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26562.0, self.close=26558.6, self.high=26562.1, self.low=26558.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-25 00:00:17,912:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230924    212959  26591.0  ...  44.583333  0.491209  0.521505
5802  20230924    215959  26579.7  ...  44.583333  0.488963  0.519119
5803  20230924    222959  26576.5  ...  44.166667  0.487998  0.517208
5804  20230924    225959  26575.0  ...  44.166667  0.488954  0.514453
5805  20230924    232959  26576.4  ...  43.750000  0.480017  0.521383

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-09-25 00:00:17,974:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.492547  0.507453       0  ...  0.919280  -1.0    0.0  1.027425
540     1  0.493269  0.506731       0  ...  0.919329  -1.0    0.0  1.027371
541     1  0.494017  0.505983       1  ...  0.919284  -1.0    0.0  1.027421
542     1  0.495297  0.504703       0  ...  0.919723  -1.0    0.0  1.026930
543     1  0.490663  0.509337       1  ...  0.919636  -1.0    0.0  1.027027

[5 rows x 10 columns]
2023-09-25 00:00:17,986:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492686  0.507314       0  ...  0.919280  -1.0    0.0  1.025740
46     1  0.493286  0.506714       0  ...  0.919329  -1.0    0.0  1.024251
47     1  0.493801  0.506199       1  ...  0.919284  -1.0    0.0  1.023748
48     1  0.495186  0.504814       0  ...  0.919723  -1.0    0.0  1.023259
49     1  0.490663  0.509337       1  ...  0.919636  -1.0    0.0  1.027027

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '14511.251', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26566.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [24/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19223 

self.closeSec=1695569399, self.tradeDate='20230924', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26562.8', self.close='26563.6'
127.0.0.1 - - [24/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19224 

self.closeSec=1695569999, self.tradeDate='20230924', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26563.6', self.close='26555.9'

--handleKline--: 127.0.0.1 - - [24/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19225 

self.closeSec=1695570599, self.tradeDate='20230924', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26555.9', self.close='26561.3'
127.0.0.1 - - [25/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19226 

self.closeSec=1695571199, self.tradeDate='20230924', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26561.3', self.close='26566.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19227 

self.closeSec=1695571799, self.tradeDate='20230925', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26566', self.close='26560.9'
127.0.0.1 - - [25/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19228 

self.closeSec=1695572399, self.tradeDate='20230925', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26560.9', self.close='26562.1'
127.0.0.1 - - [25/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [24/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19226 

self.closeSec=1695569399, self.tradeDate='20230924', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26562.8', self.close='26563.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19227 

self.closeSec=1695569999, self.tradeDate='20230924', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26563.6', self.close='26555.9'
127.0.0.1 - - [24/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19228 

self.closeSec=1695570599, self.tradeDate='20230924', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26555.9', self.close='26561.3'
127.0.0.1 - - [24/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19229 

self.closeSec=1695571199, self.tradeDate='20230924', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26561.3', self.close='26566.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19230 

self.closeSec=1695571799, self.tradeDate='20230925', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26566', self.close='26560.9'
127.0.0.1 - - [25/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19231 

self.closeSec=1695572399, self.tradeDate='20230925', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26560.9', self.close='26562.1'
127.0.0.1 - - [25/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19226 

self.closeSec=1695569399, self.tradeDate='20230924', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26562.8', self.close='26563.6'
127.0.0.1 - - [24/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19227 

self.closeSec=1695569999, self.tradeDate='20230924', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26563.6', self.close='26555.9'
127.0.0.1 - - [24/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19228 

self.closeSec=1695570599, self.tradeDate='20230924', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26555.9', self.close='26561.3'
127.0.0.1 - - [25/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19229 

self.closeSec=1695571199, self.tradeDate='20230924', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26561.3', self.close='26566.1'
127.0.0.1 - - [25/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19230 

self.closeSec=1695571799, self.tradeDate='20230925', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26566', self.close='26560.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19231 

self.closeSec=1695572399, self.tradeDate='20230925', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26560.9', self.close='26562.1'
127.0.0.1 - - [25/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38452
self.closeSec=1695572399, self.tradeDate='20230925', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26570.3, self.close=26562.1, self.high=26573.3, self.low=26562.0, self.vol=222.564, self.amt=5913360.5818 
127.0.0.1 - - [25/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-25 00:20:06,110:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230924   235500    235959  ...         0.0        0.0       0
5760  20230925   000000    000459  ...         0.0        0.0       0
5761  20230925   000500    000959  ...         0.0        0.0       0
5762  20230925   001000    001459  ...         0.0        0.0       0
5763  20230925   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 00:20:06,112:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695572399, self.tradeDate='20230925', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26570.3, self.close=26562.1, self.high=26573.3, self.low=26562.0, self.vol=222.564, self.amt=5913360.5818, ukdf['pct'].iloc[-1]=-0.000309 , ukdf['amount'].iloc[-1]=5913360.5818, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10412.3911215545', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26563.6523755', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38453
self.closeSec=1695572699, self.tradeDate='20230925', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26562.0, self.close=26558.6, self.high=26562.1, self.low=26558.5, self.vol=70.825, self.amt=1881118.6296 
2023-09-25 00:25:00,775:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230925   000000    000459  ...         0.0        0.0       0
5761  20230925   000500    000959  ...         0.0        0.0       0
5762  20230925   001000    001459  ...         0.0        0.0       0
5763  20230925   001500    001959  ...         0.0        0.0       0
5764  20230925   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 00:25:00,775:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695572699, self.tradeDate='20230925', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26562.0, self.close=26558.6, self.high=26562.1, self.low=26558.5, self.vol=70.825, self.amt=1881118.6296, ukdf['pct'].iloc[-1]=-0.000132 , ukdf['amount'].iloc[-1]=1881118.6296, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10585.47509832293', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26558.99218927', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230924   120000    155959  1695542399  ...    723  1.179588  1.453880     1.0
724  20230924   160000    195959  1695556799  ...    724  1.180396  1.420219     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-33707.3319', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26587.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=801
self.closeSec=1695571199, self.tradeDate='20230924', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26587.5, self.close=26566.1, self.high=26618.7, self.low=26547.4, self.vol=9585.642, self.amt=254761737.1996 
127.0.0.1 - - [25/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-25 00:00:01,504:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695571199, self.tradeDate='20230924', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26587.5, self.close=26566.1, self.high=26618.7, self.low=26547.4, self.vol=9585.642, self.amt=254761737.1996 
2023-09-25 00:00:01,522:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...       vol           amt       pct
721  20230924   040000    075959  ...  7650.769  2.032407e+08 -0.001181
722  20230924   080000    115959  ...  5355.769  1.422734e+08 -0.000113
723  20230924   120000    155959  ...  7565.140  2.008375e+08 -0.000286
724  20230924   160000    195959  ...  9640.884  2.562574e+08  0.001326
725  20230924   200000    235959  ...  9585.642  2.547617e+08 -0.000809

[5 rows x 11 columns]
2023-09-25 00:00:02,368:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230924   040000    075959  1695513599  ...    721  1.214685  1.621132     1.0
722  20230924   080000    115959  1695527999  ...    722  1.231993  1.617838     1.0
723  20230924   120000    155959  1695542399  ...    723  1.179588  1.453880     1.0
724  20230924   160000    195959  1695556799  ...    724  1.180396  1.420219     1.0
725  20230924   200000    235959  1695571199  ...    725  1.143992  1.302496     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-34809.4098', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26566', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


