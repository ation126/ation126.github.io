# 20231026 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47380
self.closeSec=1698250799, self.tradeDate='20231026', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=35094.1, self.close=34887.8, self.high=35148.4, self.low=34827.0, self.vol=7471.204, self.amt=261335602.75555 
127.0.0.1 - - [26/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-10-26 00:20:07,038:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231025   235500    235959  ...         0.0        0.0       0
5760  20231026   000000    000459  ...         0.0        0.0       0
5761  20231026   000500    000959  ...         0.0        0.0       0
5762  20231026   001000    001459  ...         0.0        0.0       0
5763  20231026   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 00:20:07,041:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698250799, self.tradeDate='20231026', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=35094.1, self.close=34887.8, self.high=35148.4, self.low=34827.0, self.vol=7471.204, self.amt=261335602.75555, ukdf['pct'].iloc[-1]=-0.005842 , ukdf['amount'].iloc[-1]=261335602.75555, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-111572.3268', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34876.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47381
self.closeSec=1698251099, self.tradeDate='20231026', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=34865.9, self.close=34769.1, self.high=34917.3, self.low=34708.1, self.vol=5374.762, self.amt=187052446.29444 
127.0.0.1 - - [26/Oct/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-10-26 00:25:04,123:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231026   000000    000459  ...         0.0        0.0       0
5761  20231026   000500    000959  ...         0.0        0.0       0
5762  20231026   001000    001459  ...         0.0        0.0       0
5763  20231026   001500    001959  ...         0.0        0.0       0
5764  20231026   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 00:25:04,126:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698251099, self.tradeDate='20231026', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=34865.9, self.close=34769.1, self.high=34917.3, self.low=34708.1, self.vol=5374.762, self.amt=187052446.29444, ukdf['pct'].iloc[-1]=-0.003402 , ukdf['amount'].iloc[-1]=187052446.29444, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-110101.74408212496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34771.10020696', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1698249899, self.tradeDate='20231026', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=34841.5, self.close=34850.0, self.high=34914.7, self.low=34781.4 

--ukdf-hist--: overDate='20231021' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47380 

self.closeSec=1698250199, self.tradeDate='20231026', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=34847.2, self.close=34959.6, self.high=34966.0, self.low=34844.0 
127.0.0.1 - - [26/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47381 

self.closeSec=1698250499, self.tradeDate='20231026', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=34962.0, self.close=35092.8, self.high=35154.3, self.low=34905.0 
127.0.0.1 - - [26/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47382 

self.closeSec=1698250799, self.tradeDate='20231026', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=35094.1, self.close=34887.8, self.high=35148.4, self.low=34827.0 
127.0.0.1 - - [26/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47383 

self.closeSec=1698251099, self.tradeDate='20231026', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=34865.9, self.close=34769.1, self.high=34917.3, self.low=34708.1 
127.0.0.1 - - [26/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-26 00:00:18,813:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231025    212959  34333.1  ...  56.250000  0.586494  0.373656
5802  20231025    215959  34459.8  ...  56.250000  0.588175  0.360186
5803  20231025    222959  34483.1  ...  56.666667  0.591784  0.345511
5804  20231025    225959  34537.6  ...  56.666667  0.605832  0.325349
5805  20231025    232959  34765.4  ...  57.083333  0.607509  0.307938

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-10-26 00:00:18,883:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.569852  0.430148       1  ...  1.100519   1.0    0.0  1.283956
540     0  0.551009  0.448991       1  ...  1.102335   1.0    0.0  1.286074
541     0  0.562623  0.437377       1  ...  1.109574   1.0    0.0  1.294519
542     0  0.602836  0.397164       1  ...  1.110454   1.0    0.0  1.295547
543     0  0.566973  0.433027       1  ...  1.111852   1.0    0.0  1.297178

[5 rows x 10 columns]
2023-10-26 00:00:18,897:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.569306  0.430694       1  ...  1.100519   1.0    0.0  1.284420
46     0  0.550638  0.449362       1  ...  1.102335   1.0    0.0  1.286352
47     0  0.562353  0.437647       1  ...  1.109574   1.0    0.0  1.294577
48     0  0.602928  0.397072       1  ...  1.110454   1.0    0.0  1.295605
49     0  0.566973  0.433027       1  ...  1.111852   1.0    0.0  1.297178

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '20.978', 'enterprice': '33828.2', 'countrevence': '0', 'unrealprofit': '20993.03169758262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34828.91654579', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23687 

self.closeSec=1698247799, self.tradeDate='20231025', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='34727.2', self.close='34794.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23688 

self.closeSec=1698248399, self.tradeDate='20231025', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='34797.4', self.close='34811.9'
127.0.0.1 - - [25/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23689 

self.closeSec=1698248999, self.tradeDate='20231025', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='34811.8', self.close='34970.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23690 

self.closeSec=1698249599, self.tradeDate='20231025', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='34963.4', self.close='34838.3'
127.0.0.1 - - [26/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23691 

self.closeSec=1698250199, self.tradeDate='20231026', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='34841.5', self.close='34959.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23692 

self.closeSec=1698250799, self.tradeDate='20231026', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='34962', self.close='34870.6'
127.0.0.1 - - [26/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [25/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23690 

self.closeSec=1698247799, self.tradeDate='20231025', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='34727.2', self.close='34794.5'
127.0.0.1 - - [25/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23691 

self.closeSec=1698248399, self.tradeDate='20231025', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='34797.4', self.close='34811.9'
127.0.0.1 - - [25/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23692 

self.closeSec=1698248999, self.tradeDate='20231025', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='34811.8', self.close='34970.7'
127.0.0.1 - - [26/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23693 

self.closeSec=1698249599, self.tradeDate='20231025', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='34963.4', self.close='34838.3'
127.0.0.1 - - [26/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23694 

self.closeSec=1698250199, self.tradeDate='20231026', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='34841.5', self.close='34959.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23695 

self.closeSec=1698250799, self.tradeDate='20231026', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='34962', self.close='34870.6'
127.0.0.1 - - [26/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23690 

self.closeSec=1698247799, self.tradeDate='20231025', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='34727.2', self.close='34794.5'
127.0.0.1 - - [25/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23691 127.0.0.1 - - [25/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -


self.closeSec=1698248399, self.tradeDate='20231025', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='34797.4', self.close='34811.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23692 

self.closeSec=1698248999, self.tradeDate='20231025', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='34811.8', self.close='34970.7'
127.0.0.1 - - [25/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23693 

self.closeSec=1698249599, self.tradeDate='20231025', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='34963.4', self.close='34838.3'
127.0.0.1 - - [26/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23694 

self.closeSec=1698250199, self.tradeDate='20231026', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='34841.5', self.close='34959.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23695 

self.closeSec=1698250799, self.tradeDate='20231026', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='34962', self.close='34870.6'
127.0.0.1 - - [26/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47380
self.closeSec=1698250799, self.tradeDate='20231026', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=35094.1, self.close=34887.8, self.high=35148.4, self.low=34827.0, self.vol=7471.204, self.amt=261335602.75555 
127.0.0.1 - - [26/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-10-26 00:20:07,029:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231025   235500    235959  ...         0.0        0.0       0
5760  20231026   000000    000459  ...         0.0        0.0       0
5761  20231026   000500    000959  ...         0.0        0.0       0
5762  20231026   001000    001459  ...         0.0        0.0       0
5763  20231026   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 00:20:07,040:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698250799, self.tradeDate='20231026', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=35094.1, self.close=34887.8, self.high=35148.4, self.low=34827.0, self.vol=7471.204, self.amt=261335602.75555, ukdf['pct'].iloc[-1]=-0.005842 , ukdf['amount'].iloc[-1]=261335602.75555, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '298342.5107', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34876.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47381
self.closeSec=1698251099, self.tradeDate='20231026', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=34865.9, self.close=34769.1, self.high=34917.3, self.low=34708.1, self.vol=5374.762, self.amt=187052446.29444 
127.0.0.1 - - [26/Oct/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-10-26 00:25:04,123:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231026   000000    000459  ...         0.0        0.0       0
5761  20231026   000500    000959  ...         0.0        0.0       0
5762  20231026   001000    001459  ...         0.0        0.0       0
5763  20231026   001500    001959  ...         0.0        0.0       0
5764  20231026   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 00:25:04,125:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698251099, self.tradeDate='20231026', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=34865.9, self.close=34769.1, self.high=34917.3, self.low=34708.1, self.vol=5374.762, self.amt=187052446.29444, ukdf['pct'].iloc[-1]=-0.003402 , ukdf['amount'].iloc[-1]=187052446.29444, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '294420.42878670136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34771.10020696', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231025   120000    155959  1698220799  ...    723  1.167537  0.441805     NaN
724  20231025   160000    195959  1698235199  ...    724  1.112812  0.341099     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '192618.177', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34196.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=987
self.closeSec=1698249599, self.tradeDate='20231025', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=34195.5, self.close=34838.3, self.high=35035.0, self.low=34191.8, self.vol=133242.385, self.amt=4610592613.0755 
127.0.0.1 - - [26/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-10-26 00:00:01,524:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698249599, self.tradeDate='20231025', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=34195.5, self.close=34838.3, self.high=35035.0, self.low=34191.8, self.vol=133242.385, self.amt=4610592613.0755 
2023-10-26 00:00:01,540:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20231025   040000    075959  ...   87728.961  2.975642e+09  0.003699
722  20231025   080000    115959  ...   57592.236  1.962838e+09  0.002530
723  20231025   120000    155959  ...   54108.207  1.839219e+09 -0.004394
724  20231025   160000    195959  ...   73788.503  2.519740e+09  0.010108
725  20231025   200000    235959  ...  133242.385  4.610593e+09  0.018795

[5 rows x 11 columns]
2023-10-26 00:00:02,274:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231025   040000    075959  1698191999  ...    721  1.339134  0.738939     1.0
722  20231025   080000    115959  1698206399  ...    722  1.245298  0.577926     NaN
723  20231025   120000    155959  1698220799  ...    723  1.167537  0.441805     NaN
724  20231025   160000    195959  1698235199  ...    724  1.112812  0.341099     NaN
725  20231025   200000    235959  1698249599  ...    725  1.072746  0.263102     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '219423.02193530541', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34844.27052381', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


