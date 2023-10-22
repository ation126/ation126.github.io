# 20231023 00:26:10

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46516
self.closeSec=1697991599, self.tradeDate='20231023', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29814.2, self.close=29848.5, self.high=29854.2, self.low=29814.2, self.vol=1023.87, self.amt=30547699.7854 
127.0.0.1 - - [23/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -
2023-10-23 00:20:17,706:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231022   235500    235959  ...         0.0        0.0       0
5760  20231023   000000    000459  ...         0.0        0.0       0
5761  20231023   000500    000959  ...         0.0        0.0       0
5762  20231023   001000    001459  ...         0.0        0.0       0
5763  20231023   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 00:20:17,726:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697991599, self.tradeDate='20231023', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29814.2, self.close=29848.5, self.high=29854.2, self.low=29814.2, self.vol=1023.87, self.amt=30547699.7854, ukdf['pct'].iloc[-1]=0.00115 , ukdf['amount'].iloc[-1]=30547699.7854, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41580.51302198442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29850.71882967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46517
self.closeSec=1697991899, self.tradeDate='20231023', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29848.6, self.close=29848.2, self.high=29867.4, self.low=29848.2, self.vol=531.645, self.amt=15872937.7055 
127.0.0.1 - - [23/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-23 00:25:03,557:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231023   000000    000459  ...         0.0        0.0       0
5761  20231023   000500    000959  ...         0.0        0.0       0
5762  20231023   001000    001459  ...         0.0        0.0       0
5763  20231023   001500    001959  ...         0.0        0.0       0
5764  20231023   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 00:25:03,562:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697991899, self.tradeDate='20231023', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29848.6, self.close=29848.2, self.high=29867.4, self.low=29848.2, self.vol=531.645, self.amt=15872937.7055, ukdf['pct'].iloc[-1]=-1e-05 , ukdf['amount'].iloc[-1]=15872937.7055, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41595.14649342162', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29851.76963187', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1697990699, self.tradeDate='20231023', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=29815.3, self.close=29812.7, self.high=29823.0, self.low=29789.2 

--ukdf-hist--: overDate='20231018' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [23/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46516 

self.closeSec=1697990999, self.tradeDate='20231023', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29812.7, self.close=29797.1, self.high=29812.7, self.low=29794.0 
127.0.0.1 - - [23/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46517 

self.closeSec=1697991299, self.tradeDate='20231023', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29799.3, self.close=29814.2, self.high=29814.2, self.low=29796.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46518 

self.closeSec=1697991599, self.tradeDate='20231023', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29814.2, self.close=29848.5, self.high=29854.2, self.low=29814.2 
127.0.0.1 - - [23/Oct/2023 00:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46519 

self.closeSec=1697991899, self.tradeDate='20231023', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29848.6, self.close=29848.2, self.high=29867.4, self.low=29848.2 
127.0.0.1 - - [23/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-23 00:00:17,334:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231022    212959  29882.1  ...  55.000000  0.547932  0.565186
5802  20231022    215959  29940.0  ...  54.583333  0.546379  0.565840
5803  20231022    222959  29933.0  ...  54.166667  0.529173  0.570070
5804  20231022    225959  29849.5  ...  54.166667  0.530873  0.573116
5805  20231022    232959  29862.2  ...  54.166667  0.527977  0.575661

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-10-23 00:00:17,395:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.526927  0.473073       0  ...  0.943258   1.0    0.0  1.108104
540     0  0.510691  0.489309       0  ...  0.940743   1.0    0.0  1.105150
541     1  0.486099  0.513901       1  ...  0.941027   1.0    0.0  1.105483
542     0  0.506154  0.493846       0  ...  0.940605   1.0    0.0  1.104987
543     0  0.502704  0.497296       0  ...  0.939549   1.0    0.0  1.103747

[5 rows x 10 columns]
2023-10-23 00:00:17,406:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.527570  0.472430       0  ...  0.943258   1.0    0.0  1.105963
46     0  0.511395  0.488605       0  ...  0.940743   1.0    0.0  1.103239
47     1  0.486526  0.513474       1  ...  0.941027   1.0    0.0  1.104265
48     0  0.506577  0.493423       0  ...  0.940605   1.0    0.0  1.103770
49     0  0.502704  0.497296       0  ...  0.939549   1.0    0.0  1.103747

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.157', 'enterprice': '29765.1', 'countrevence': '0', 'unrealprofit': '1064.84192346914', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29815.43047802', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [22/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23255 

self.closeSec=1697988599, self.tradeDate='20231022', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29853.7', self.close='29848.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23256 

self.closeSec=1697989199, self.tradeDate='20231022', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29848.5', self.close='29815.3'
127.0.0.1 - - [22/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23257 

self.closeSec=1697989799, self.tradeDate='20231022', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29815.4', self.close='29787.7'
127.0.0.1 - - [22/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23258 

self.closeSec=1697990399, self.tradeDate='20231022', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29787.6', self.close='29815.3'
127.0.0.1 - - [23/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23259 

self.closeSec=1697990999, self.tradeDate='20231023', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29815.3', self.close='29797.1'
127.0.0.1 - - [23/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23260 

self.closeSec=1697991599, self.tradeDate='20231023', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29799.3', self.close='29848.5'
127.0.0.1 - - [23/Oct/2023 00:20:12] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [22/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23258 

self.closeSec=1697988599, self.tradeDate='20231022', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29853.7', self.close='29848.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23259 

self.closeSec=1697989199, self.tradeDate='20231022', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29848.5', self.close='29815.3'
127.0.0.1 - - [22/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23260 

self.closeSec=1697989799, self.tradeDate='20231022', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29815.4', self.close='29787.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23261 

self.closeSec=1697990399, self.tradeDate='20231022', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29787.6', self.close='29815.3'
127.0.0.1 - - [23/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23262 

self.closeSec=1697990999, self.tradeDate='20231023', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29815.3', self.close='29797.1'
127.0.0.1 - - [23/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23263 

self.closeSec=1697991599, self.tradeDate='20231023', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29799.3', self.close='29848.5'
127.0.0.1 - - [23/Oct/2023 00:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23258 

self.closeSec=1697988599, self.tradeDate='20231022', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29853.7', self.close='29848.8'
127.0.0.1 - - [22/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23259 

self.closeSec=1697989199, self.tradeDate='20231022', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29848.5', self.close='29815.3'
127.0.0.1 - - [22/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23260 

self.closeSec=1697989799, self.tradeDate='20231022', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29815.4', self.close='29787.7'
127.0.0.1 - - [22/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23261 

self.closeSec=1697990399, self.tradeDate='20231022', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29787.6', self.close='29815.3'
127.0.0.1 - - [23/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23262 

self.closeSec=1697990999, self.tradeDate='20231023', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29815.3', self.close='29797.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23263 

self.closeSec=1697991599, self.tradeDate='20231023', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29799.3', self.close='29848.5'
127.0.0.1 - - [23/Oct/2023 00:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46516
self.closeSec=1697991599, self.tradeDate='20231023', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29814.2, self.close=29848.5, self.high=29854.2, self.low=29814.2, self.vol=1023.87, self.amt=30547699.7854 
127.0.0.1 - - [23/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-23 00:20:17,716:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231022   235500    235959  ...         0.0        0.0       0
5760  20231023   000000    000459  ...         0.0        0.0       0
5761  20231023   000500    000959  ...         0.0        0.0       0
5762  20231023   001000    001459  ...         0.0        0.0       0
5763  20231023   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 00:20:17,746:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697991599, self.tradeDate='20231023', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29814.2, self.close=29848.5, self.high=29854.2, self.low=29814.2, self.vol=1023.87, self.amt=30547699.7854, ukdf['pct'].iloc[-1]=0.00115 , ukdf['amount'].iloc[-1]=30547699.7854, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '111672.54405277347', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29850.71882967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46517
self.closeSec=1697991899, self.tradeDate='20231023', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29848.6, self.close=29848.2, self.high=29867.4, self.low=29848.2, self.vol=531.645, self.amt=15872937.7055 
127.0.0.1 - - [23/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-23 00:25:03,558:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231023   000000    000459  ...         0.0        0.0       0
5761  20231023   000500    000959  ...         0.0        0.0       0
5762  20231023   001000    001459  ...         0.0        0.0       0
5763  20231023   001500    001959  ...         0.0        0.0       0
5764  20231023   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 00:25:03,563:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697991899, self.tradeDate='20231023', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29848.6, self.close=29848.2, self.high=29867.4, self.low=29848.2, self.vol=531.645, self.amt=15872937.7055, ukdf['pct'].iloc[-1]=-1e-05 , ukdf['amount'].iloc[-1]=15872937.7055, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '111711.57189728367', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29851.76963187', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231022   120000    155959  1697961599  ...    723  0.958796  0.474248     NaN
724  20231022   160000    195959  1697975999  ...    724  0.971829  0.482675     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '14894.74490312235', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29899.31568635', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=969
self.closeSec=1697990399, self.tradeDate='20231022', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29895.9, self.close=29815.3, self.high=29962.6, self.low=29760.6, self.vol=23241.182, self.amt=694117897.6682 
127.0.0.1 - - [23/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-10-23 00:00:01,523:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697990399, self.tradeDate='20231022', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29895.9, self.close=29815.3, self.high=29962.6, self.low=29760.6, self.vol=23241.182, self.amt=694117897.6682 
2023-10-23 00:00:01,537:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231022   040000    075959  ...  28156.934  8.439439e+08 -0.007750
722  20231022   080000    115959  ...  25140.467  7.520558e+08  0.000060
723  20231022   120000    155959  ...  63562.834  1.903340e+09 -0.003224
724  20231022   160000    195959  ...  35444.616  1.058783e+09  0.003198
725  20231022   200000    235959  ...  23241.182  6.941179e+08 -0.002696

[5 rows x 11 columns]
2023-10-23 00:00:02,328:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231022   040000    075959  1697932799  ...    721  0.991878  0.550760     NaN
722  20231022   080000    115959  1697947199  ...    722  0.948324  0.469893     NaN
723  20231022   120000    155959  1697961599  ...    723  0.958796  0.474248     NaN
724  20231022   160000    195959  1697975999  ...    724  0.971829  0.482675     NaN
725  20231022   200000    235959  1697990399  ...    725  0.948686  0.433889     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '11419.7721', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29815.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


