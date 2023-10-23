# 20231024 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46804
self.closeSec=1698077999, self.tradeDate='20231024', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30889.9, self.close=30958.5, self.high=30970.0, self.low=30878.2, self.vol=2259.525, self.amt=69911196.3849 
127.0.0.1 - - [24/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-24 00:20:17,342:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231023   235500    235959  ...         0.0        0.0       0
5760  20231024   000000    000459  ...         0.0        0.0       0
5761  20231024   000500    000959  ...         0.0        0.0       0
5762  20231024   001000    001459  ...         0.0        0.0       0
5763  20231024   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 00:20:17,354:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698077999, self.tradeDate='20231024', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30889.9, self.close=30958.5, self.high=30970.0, self.low=30878.2, self.vol=2259.525, self.amt=69911196.3849, ukdf['pct'].iloc[-1]=0.002218 , ukdf['amount'].iloc[-1]=69911196.3849, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-57061.785', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30962.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46805
self.closeSec=1698078299, self.tradeDate='20231024', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30959.4, self.close=30904.1, self.high=30996.8, self.low=30853.9, self.vol=4035.566, self.amt=124793836.06034 
127.0.0.1 - - [24/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-24 00:25:03,618:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231024   000000    000459  ...         0.0        0.0       0
5761  20231024   000500    000959  ...         0.0        0.0       0
5762  20231024   001000    001459  ...         0.0        0.0       0
5763  20231024   001500    001959  ...         0.0        0.0       0
5764  20231024   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 00:25:03,626:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698078299, self.tradeDate='20231024', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30959.4, self.close=30904.1, self.high=30996.8, self.low=30853.9, self.vol=4035.566, self.amt=124793836.06034, ukdf['pct'].iloc[-1]=-0.001757 , ukdf['amount'].iloc[-1]=124793836.06034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-56239.41582960954', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30903.34720879', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1698077099, self.tradeDate='20231024', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=30864.1, self.close=30839.6, self.high=30902.1, self.low=30825.2 

--ukdf-hist--: overDate='20231019' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [24/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46804 

self.closeSec=1698077399, self.tradeDate='20231024', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=30844.0, self.close=30939.5, self.high=30944.9, self.low=30837.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46805 

self.closeSec=1698077699, self.tradeDate='20231024', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=30946.3, self.close=30890.0, self.high=30974.9, self.low=30876.6 
127.0.0.1 - - [24/Oct/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46806 

self.closeSec=1698077999, self.tradeDate='20231024', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30889.9, self.close=30958.5, self.high=30970.0, self.low=30878.2 
127.0.0.1 - - [24/Oct/2023 00:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46807 

self.closeSec=1698078299, self.tradeDate='20231024', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30959.4, self.close=30904.1, self.high=30996.8, self.low=30853.9 
127.0.0.1 - - [24/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-24 00:00:18,169:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231023    212959  30648.8  ...  54.583333  0.570112  0.327416
5802  20231023    215959  30555.7  ...  55.000000  0.574840  0.326089
5803  20231023    222959  30590.9  ...  55.416667  0.580505  0.322559
5804  20231023    225959  30637.1  ...  55.833333  0.594522  0.313439
5805  20231023    232959  30762.7  ...  55.833333  0.602823  0.301357

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-10-24 00:00:18,237:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.496396  0.503604       1  ...  0.989618   1.0    0.0  1.141548
540     0  0.524601  0.475399       1  ...  0.991054   1.0    0.0  1.143205
541     0  0.528992  0.471008       1  ...  0.994707   1.0    0.0  1.147418
542     0  0.551479  0.448521       1  ...  0.996945   1.0    0.0  1.150000
543     0  0.546925  0.453075       1  ...  0.998475   1.0    0.0  1.151765

[5 rows x 10 columns]
2023-10-24 00:00:18,249:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496668  0.503332       1  ...  0.989618   1.0    0.0  1.138189
46     0  0.525882  0.474118       1  ...  1.011152   1.0    0.0  1.140945
47     0  0.529427  0.470573       1  ...  0.994707   1.0    0.0  1.146648
48     0  0.551944  0.448056       1  ...  0.996945   1.0    0.0  1.149228
49     0  0.546925  0.453075       1  ...  0.998475   1.0    0.0  1.151765

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.157', 'enterprice': '29765.1', 'countrevence': '0', 'unrealprofit': '23253.6587', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30864.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23399 

self.closeSec=1698074999, self.tradeDate='20231023', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30775.8', self.close='30819.2'
127.0.0.1 - - [23/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23400 

self.closeSec=1698075599, self.tradeDate='20231023', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30821', self.close='30845'

--handleKline--:  127.0.0.1 - - [23/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23401 

self.closeSec=1698076199, self.tradeDate='20231023', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30848.7', self.close='30878.9'
127.0.0.1 - - [24/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23402 

self.closeSec=1698076799, self.tradeDate='20231023', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30878.4', self.close='30866.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23403 

self.closeSec=1698077399, self.tradeDate='20231024', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30864.1', self.close='30939.5'
127.0.0.1 - - [24/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23404 

self.closeSec=1698077999, self.tradeDate='20231024', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30946.3', self.close='30959.4'
127.0.0.1 - - [24/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23402 

self.closeSec=1698074999, self.tradeDate='20231023', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30775.8', self.close='30819.2'
127.0.0.1 - - [23/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23403 

self.closeSec=1698075599, self.tradeDate='20231023', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30821', self.close='30845'
127.0.0.1 - - [23/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23404 

self.closeSec=1698076199, self.tradeDate='20231023', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30848.7', self.close='30878.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23405 

self.closeSec=1698076799, self.tradeDate='20231023', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30878.4', self.close='30866.5'
127.0.0.1 - - [24/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23406 

self.closeSec=1698077399, self.tradeDate='20231024', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30864.1', self.close='30939.5'
127.0.0.1 - - [24/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23407 

self.closeSec=1698077999, self.tradeDate='20231024', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30946.3', self.close='30959.4'
127.0.0.1 - - [24/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23402 

self.closeSec=1698074999, self.tradeDate='20231023', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30775.8', self.close='30819.2'
127.0.0.1 - - [23/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23403 

self.closeSec=1698075599, self.tradeDate='20231023', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30821', self.close='30845'
127.0.0.1 - - [23/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23404 

self.closeSec=1698076199, self.tradeDate='20231023', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30848.7', self.close='30878.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23405 

self.closeSec=1698076799, self.tradeDate='20231023', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30878.4', self.close='30866.5'
127.0.0.1 - - [24/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23406 

self.closeSec=1698077399, self.tradeDate='20231024', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30864.1', self.close='30939.5'
127.0.0.1 - - [24/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23407 

self.closeSec=1698077999, self.tradeDate='20231024', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30946.3', self.close='30959.4'
127.0.0.1 - - [24/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46804
self.closeSec=1698077999, self.tradeDate='20231024', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30889.9, self.close=30958.5, self.high=30970.0, self.low=30878.2, self.vol=2259.525, self.amt=69911196.3849 
127.0.0.1 - - [24/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-24 00:20:17,302:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231023   235500    235959  ...         0.0        0.0       0
5760  20231024   000000    000459  ...         0.0        0.0       0
5761  20231024   000500    000959  ...         0.0        0.0       0
5762  20231024   001000    001459  ...         0.0        0.0       0
5763  20231024   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 00:20:17,314:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698077999, self.tradeDate='20231024', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30889.9, self.close=30958.5, self.high=30970.0, self.low=30878.2, self.vol=2259.525, self.amt=69911196.3849, ukdf['pct'].iloc[-1]=0.002218 , ukdf['amount'].iloc[-1]=69911196.3849, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '152961.4944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30962.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46805
self.closeSec=1698078299, self.tradeDate='20231024', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30959.4, self.close=30904.1, self.high=30996.8, self.low=30853.9, self.vol=4035.566, self.amt=124793836.06034 
127.0.0.1 - - [24/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-24 00:25:03,616:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231024   000000    000459  ...         0.0        0.0       0
5761  20231024   000500    000959  ...         0.0        0.0       0
5762  20231024   001000    001459  ...         0.0        0.0       0
5763  20231024   001500    001959  ...         0.0        0.0       0
5764  20231024   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 00:25:03,619:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698078299, self.tradeDate='20231024', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30959.4, self.close=30904.1, self.high=30996.8, self.low=30853.9, self.vol=4035.566, self.amt=124793836.06034, ukdf['pct'].iloc[-1]=-0.001757 , ukdf['amount'].iloc[-1]=124793836.06034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '150768.21468166939', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30903.34720879', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231023   120000    155959  1698047999  ...    723  0.892948  0.299264     NaN
724  20231023   160000    195959  1698062399  ...    724  0.822363  0.173331     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '46096.8345', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30653.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [24/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=975
self.closeSec=1698076799, self.tradeDate='20231023', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30644.4, self.close=30866.5, self.high=30963.2, self.low=30378.5, self.vol=89649.14, self.amt=2751677631.08064 
2023-10-24 00:00:01,547:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698076799, self.tradeDate='20231023', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30644.4, self.close=30866.5, self.high=30963.2, self.low=30378.5, self.vol=89649.14, self.amt=2751677631.08064 
2023-10-24 00:00:01,577:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20231023   040000    075959  ...   33501.912  1.001635e+09  0.005082
722  20231023   080000    115959  ...  128693.194  3.906155e+09  0.024765
723  20231023   120000    155959  ...  109840.976  3.375397e+09 -0.007011
724  20231023   160000    195959  ...   67535.437  2.062828e+09  0.004451
725  20231023   200000    235959  ...   89649.140  2.751678e+09  0.007248

[5 rows x 11 columns]
2023-10-24 00:00:02,287:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231023   040000    075959  1698019199  ...    721  0.864482  0.277100     NaN
722  20231023   080000    115959  1698033599  ...    722  0.870523  0.275271     NaN
723  20231023   120000    155959  1698047999  ...    723  0.892948  0.299264     NaN
724  20231023   160000    195959  1698062399  ...    724  0.822363  0.173331     NaN
725  20231023   200000    235959  1698076799  ...    725  0.790494  0.109719     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '54870.11778821043', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30865.81487363', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


