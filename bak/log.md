# 20230824 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29236
self.closeSec=1692807599, self.tradeDate='20230824', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26185.0, self.close=26308.0, self.high=26410.0, self.low=26179.2, self.vol=16059.195, self.amt=422305774.8435 
127.0.0.1 - - [24/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-24 00:20:05,391:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230823   235500    235959  ...         0.0        0.0       0
5748  20230824   000000    000459  ...         0.0        0.0       0
5749  20230824   000500    000959  ...         0.0        0.0       0
5750  20230824   001000    001459  ...         0.0        0.0       0
5751  20230824   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 00:20:05,402:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692807599, self.tradeDate='20230824', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26185.0, self.close=26308.0, self.high=26410.0, self.low=26179.2, self.vol=16059.195, self.amt=422305774.8435, ukdf['pct'].iloc[-1]=0.004736 , ukdf['amount'].iloc[-1]=422305774.8435, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7457.11686158868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26329.41839282', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29237
self.closeSec=1692807899, self.tradeDate='20230824', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26308.0, self.close=26407.3, self.high=26444.0, self.low=26307.9, self.vol=11042.942, self.amt=291371803.2278 
127.0.0.1 - - [24/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-24 00:25:00,771:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230824   000000    000459  ...         0.0        0.0       0
5749  20230824   000500    000959  ...         0.0        0.0       0
5750  20230824   001000    001459  ...         0.0        0.0       0
5751  20230824   001500    001959  ...         0.0        0.0       0
5752  20230824   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 00:25:00,771:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692807899, self.tradeDate='20230824', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26308.0, self.close=26407.3, self.high=26444.0, self.low=26307.9, self.vol=11042.942, self.amt=291371803.2278, ukdf['pct'].iloc[-1]=0.003775 , ukdf['amount'].iloc[-1]=291371803.2278, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6355.8264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26408.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1692806699, self.tradeDate='20230824', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26134.3, self.close=26129.6, self.high=26149.6, self.low=26121.9 

--ukdf-hist--: overDate='20230819' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [24/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29236 

self.closeSec=1692806999, self.tradeDate='20230824', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26129.6, self.close=26122.6, self.high=26143.8, self.low=26113.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29237 

self.closeSec=1692807299, self.tradeDate='20230824', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26122.7, self.close=26184.0, self.high=26266.8, self.low=26122.6 
127.0.0.1 - - [24/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29238 

self.closeSec=1692807599, self.tradeDate='20230824', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26185.0, self.close=26308.0, self.high=26410.0, self.low=26179.2 
127.0.0.1 - - [24/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29239 

self.closeSec=1692807899, self.tradeDate='20230824', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26308.0, self.close=26407.3, self.high=26444.0, self.low=26307.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-24 00:00:17,335:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230823    212959  25832.6  ...  50.416667  0.456954  0.277294
5802  20230823    215959  25853.6  ...  50.833333  0.499924  0.271673
5803  20230823    222959  26003.9  ...  50.833333  0.497785  0.267021
5804  20230823    225959  25993.4  ...  51.250000  0.506300  0.260331
5805  20230823    232959  26027.5  ...  51.250000  0.524473  0.249568

[5 rows x 33 columns]
0.5386029411764706
acc is : 0.5386029411764706
2023-08-24 00:00:17,397:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.475642  0.524358       1  ...  1.073379  -1.0    0.0  0.884580
540     0  0.536882  0.463118       0  ...  1.073710  -1.0    0.0  0.884308
541     1  0.487275  0.512725       1  ...  1.072404  -1.0    0.0  0.885382
542     0  0.509807  0.490193       1  ...  1.069528  -1.0    0.0  0.887757
543     0  0.536699  0.463301       1  ...  1.068012  -1.0    0.0  0.889016

[5 rows x 10 columns]
2023-08-24 00:00:17,409:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.475855  0.524145       1  ...  1.073379  -1.0    0.0  0.884688
46     0  0.537036  0.462964       0  ...  1.073710  -1.0    0.0  0.884672
47     1  0.487211  0.512789       1  ...  1.072404  -1.0    0.0  0.884967
48     0  0.510388  0.489612       1  ...  1.069528  -1.0    0.0  0.887340
49     0  0.536699  0.463301       1  ...  1.068012  -1.0    0.0  0.889016

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.498', 'enterprice': '25851.1', 'countrevence': '0', 'unrealprofit': '-8578.0184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26141.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14615 

self.closeSec=1692804599, self.tradeDate='20230823', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26081.9', self.close='26097.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14616 

self.closeSec=1692805199, self.tradeDate='20230823', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26097.3', self.close='26151.7'
127.0.0.1 - - [23/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14617 

self.closeSec=1692805799, self.tradeDate='20230823', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26151.8', self.close='26108'
127.0.0.1 - - [24/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14618 

self.closeSec=1692806399, self.tradeDate='20230823', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26108.1', self.close='26134.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14619 

self.closeSec=1692806999, self.tradeDate='20230824', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26134.3', self.close='26122.6'
127.0.0.1 - - [24/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14620 

self.closeSec=1692807599, self.tradeDate='20230824', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26122.7', self.close='26308'
127.0.0.1 - - [24/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [23/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14618 

self.closeSec=1692804599, self.tradeDate='20230823', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26081.9', self.close='26097.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14619 

self.closeSec=1692805199, self.tradeDate='20230823', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26097.3', self.close='26151.7'
127.0.0.1 - - [23/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14620 

self.closeSec=1692805799, self.tradeDate='20230823', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26151.8', self.close='26108'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14621 

self.closeSec=1692806399, self.tradeDate='20230823', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26108.1', self.close='26134.3'
127.0.0.1 - - [24/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14622 

self.closeSec=1692806999, self.tradeDate='20230824', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26134.3', self.close='26122.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14623 

self.closeSec=1692807599, self.tradeDate='20230824', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26122.7', self.close='26308'
127.0.0.1 - - [24/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14618 

self.closeSec=1692804599, self.tradeDate='20230823', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26081.9', self.close='26097.3'
127.0.0.1 - - [23/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14619 

self.closeSec=1692805199, self.tradeDate='20230823', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26097.3', self.close='26151.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14620 

self.closeSec=1692805799, self.tradeDate='20230823', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26151.8', self.close='26108'
127.0.0.1 - - [23/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14621 

self.closeSec=1692806399, self.tradeDate='20230823', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26108.1', self.close='26134.3'
127.0.0.1 - - [24/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14622 

self.closeSec=1692806999, self.tradeDate='20230824', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26134.3', self.close='26122.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14623 

self.closeSec=1692807599, self.tradeDate='20230824', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26122.7', self.close='26308'
127.0.0.1 - - [24/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29236
self.closeSec=1692807599, self.tradeDate='20230824', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26185.0, self.close=26308.0, self.high=26410.0, self.low=26179.2, self.vol=16059.195, self.amt=422305774.8435 
127.0.0.1 - - [24/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-24 00:20:05,382:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230823   235500    235959  ...         0.0        0.0       0
5748  20230824   000000    000459  ...         0.0        0.0       0
5749  20230824   000500    000959  ...         0.0        0.0       0
5750  20230824   001000    001459  ...         0.0        0.0       0
5751  20230824   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 00:20:05,391:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692807599, self.tradeDate='20230824', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26185.0, self.close=26308.0, self.high=26410.0, self.low=26179.2, self.vol=16059.195, self.amt=422305774.8435, ukdf['pct'].iloc[-1]=0.004736 , ukdf['amount'].iloc[-1]=422305774.8435, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-19112.07547227238', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26329.41839282', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29237
self.closeSec=1692807899, self.tradeDate='20230824', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26308.0, self.close=26407.3, self.high=26444.0, self.low=26307.9, self.vol=11042.942, self.amt=291371803.2278 
127.0.0.1 - - [24/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-24 00:25:00,774:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230824   000000    000459  ...         0.0        0.0       0
5749  20230824   000500    000959  ...         0.0        0.0       0
5750  20230824   001000    001459  ...         0.0        0.0       0
5751  20230824   001500    001959  ...         0.0        0.0       0
5752  20230824   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 00:25:00,775:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692807899, self.tradeDate='20230824', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26308.0, self.close=26407.3, self.high=26444.0, self.low=26307.9, self.vol=11042.942, self.amt=291371803.2278, ukdf['pct'].iloc[-1]=0.003775 , ukdf['amount'].iloc[-1]=291371803.2278, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-16174.9055', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26408.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230823   120000    155959  1692777599  ...    723  0.020046 -1.058495    -1.0
724  20230823   160000    195959  1692791999  ...    724  0.015548 -1.068225    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '180087.36986728592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25928.13650916', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [24/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=609
self.closeSec=1692806399, self.tradeDate='20230823', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25928.1, self.close=26134.3, self.high=26187.0, self.low=25800.0, self.vol=89252.364, self.amt=2321153493.73994 
2023-08-24 00:00:01,535:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692806399, self.tradeDate='20230823', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25928.1, self.close=26134.3, self.high=26187.0, self.low=25800.0, self.vol=89252.364, self.amt=2321153493.73994 
2023-08-24 00:00:01,551:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230823   040000    075959  ...  102208.075  2.627786e+09  0.010758
722  20230823   080000    115959  ...   35799.297  9.329007e+08 -0.002008
723  20230823   120000    155959  ...   36125.446  9.412892e+08  0.002047
724  20230823   160000    195959  ...   31581.275  8.203121e+08 -0.004500
725  20230823   200000    235959  ...   89252.364  2.321153e+09  0.007953

[5 rows x 11 columns]
2023-08-24 00:00:02,354:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230823   040000    075959  1692748799  ...    721  0.020726 -1.055603    -1.0
722  20230823   080000    115959  1692763199  ...    722  0.019857 -1.058389    -1.0
723  20230823   120000    155959  1692777599  ...    723  0.020046 -1.058495    -1.0
724  20230823   160000    195959  1692791999  ...    724  0.015548 -1.068225    -1.0
725  20230823   200000    235959  1692806399  ...    725  0.012680 -1.068013    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '169493.0404', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26134.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


