# 20230920 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37012
self.closeSec=1695140399, self.tradeDate='20230920', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27451.6, self.close=27337.2, self.high=27472.5, self.low=27335.0, self.vol=4027.331, self.amt=110367931.4947 
127.0.0.1 - - [20/Sep/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-09-20 00:20:06,822:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230919   235500    235959  ...         0.0        0.0       0
5760  20230920   000000    000459  ...         0.0        0.0       0
5761  20230920   000500    000959  ...         0.0        0.0       0
5762  20230920   001000    001459  ...         0.0        0.0       0
5763  20230920   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 00:20:06,831:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695140399, self.tradeDate='20230920', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27451.6, self.close=27337.2, self.high=27472.5, self.low=27335.0, self.vol=4027.331, self.amt=110367931.4947, ukdf['pct'].iloc[-1]=-0.004062 , ukdf['amount'].iloc[-1]=110367931.4947, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-6787.44193196916', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27352.29350366', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37013
self.closeSec=1695140699, self.tradeDate='20230920', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27332.1, self.close=27318.9, self.high=27353.6, self.low=27279.0, self.vol=4222.945, self.amt=115334063.3468 
2023-09-20 00:25:00,819:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230920   000000    000459  ...         0.0        0.0       0
5761  20230920   000500    000959  ...         0.0        0.0       0
5762  20230920   001000    001459  ...         0.0        0.0       0
5763  20230920   001500    001959  ...         0.0        0.0       0
5764  20230920   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 00:25:00,820:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695140699, self.tradeDate='20230920', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27332.1, self.close=27318.9, self.high=27353.6, self.low=27279.0, self.vol=4222.945, self.amt=115334063.3468, ukdf['pct'].iloc[-1]=-0.000669 , ukdf['amount'].iloc[-1]=115334063.3468, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-6339.1152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27320.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1695139499, self.tradeDate='20230920', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27413.3, self.close=27378.6, self.high=27438.0, self.low=27334.0 

--ukdf-hist--: overDate='20230915' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [20/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37012 

self.closeSec=1695139799, self.tradeDate='20230920', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27370.4, self.close=27399.2, self.high=27413.3, self.low=27338.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37013 

self.closeSec=1695140099, self.tradeDate='20230920', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27400.0, self.close=27448.7, self.high=27457.0, self.low=27390.0 
127.0.0.1 - - [20/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37014 

self.closeSec=1695140399, self.tradeDate='20230920', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27451.6, self.close=27337.2, self.high=27472.5, self.low=27335.0 
127.0.0.1 - - [20/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37015 

self.closeSec=1695140699, self.tradeDate='20230920', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27332.1, self.close=27318.9, self.high=27353.6, self.low=27279.0 
127.0.0.1 - - [20/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-20 00:00:17,762:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230919    212959  27124.9  ...  52.500000  0.567685  0.500687
5802  20230919    215959  27155.3  ...  52.500000  0.525210  0.507092
5803  20230919    222959  26959.2  ...  52.500000  0.553149  0.500502
5804  20230919    225959  27120.0  ...  52.500000  0.558762  0.492951
5805  20230919    232959  27153.6  ...  52.916667  0.583919  0.472698

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-09-20 00:00:17,818:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.503341  0.496659       0  ...  0.934145   1.0  0.0000  1.027183
540     1  0.438753  0.561247       1  ...  0.927040  -1.0 -0.0016  1.033352
541     0  0.529319  0.470681       1  ...  0.925867  -1.0  0.0000  1.034659
542     1  0.498177  0.501823       1  ...  0.920350  -1.0  0.0000  1.040824
543     0  0.542572  0.457428       1  ...  0.917163  -1.0  0.0000  1.044429

[5 rows x 10 columns]
2023-09-20 00:00:17,829:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.502984  0.497016       0  ...  0.934145   1.0  0.0000  1.027250
46     1  0.439222  0.560778       1  ...  0.927040  -1.0 -0.0016  1.034649
47     0  0.528691  0.471309       1  ...  0.925867  -1.0  0.0000  1.033533
48     1  0.498052  0.501948       1  ...  0.920350  -1.0  0.0000  1.039691
49     0  0.542572  0.457428       1  ...  0.917163  -1.0  0.0000  1.044429

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '-7666.9774240374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27430.07461722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18503 

self.closeSec=1695137399, self.tradeDate='20230919', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27186.6', self.close='27305.7'
127.0.0.1 - - [19/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18504 

self.closeSec=1695137999, self.tradeDate='20230919', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27316', self.close='27359.7'
127.0.0.1 - - [19/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18505 

self.closeSec=1695138599, self.tradeDate='20230919', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27356', self.close='27287.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18506 

self.closeSec=1695139199, self.tradeDate='20230919', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27288', self.close='27413.2'
127.0.0.1 - - [20/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18507 

self.closeSec=1695139799, self.tradeDate='20230920', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27413.3', self.close='27399.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18508 

self.closeSec=1695140399, self.tradeDate='20230920', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27400', self.close='27337.2'
127.0.0.1 - - [20/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [19/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18506 

self.closeSec=1695137399, self.tradeDate='20230919', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27186.6', self.close='27305.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18507 

self.closeSec=1695137999, self.tradeDate='20230919', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27316', self.close='27359.7'
127.0.0.1 - - [19/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18508 

self.closeSec=1695138599, self.tradeDate='20230919', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27356', self.close='27287.9'
127.0.0.1 - - [19/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18509 

self.closeSec=1695139199, self.tradeDate='20230919', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27288', self.close='27413.2'
127.0.0.1 - - [20/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18510 

self.closeSec=1695139799, self.tradeDate='20230920', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27413.3', self.close='27399.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18511 

self.closeSec=1695140399, self.tradeDate='20230920', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27400', self.close='27337.2'
127.0.0.1 - - [20/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18506 

self.closeSec=1695137399, self.tradeDate='20230919', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27186.6', self.close='27305.7'
127.0.0.1 - - [19/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18507 

self.closeSec=1695137999, self.tradeDate='20230919', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27316', self.close='27359.7'
127.0.0.1 - - [19/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18508 

self.closeSec=1695138599, self.tradeDate='20230919', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27356', self.close='27287.9'
127.0.0.1 - - [19/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18509 

self.closeSec=1695139199, self.tradeDate='20230919', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27288', self.close='27413.2'
127.0.0.1 - - [20/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18510 

self.closeSec=1695139799, self.tradeDate='20230920', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27413.3', self.close='27399.2'
127.0.0.1 - - [20/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18511 

self.closeSec=1695140399, self.tradeDate='20230920', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27400', self.close='27337.2'
127.0.0.1 - - [20/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37012
self.closeSec=1695140399, self.tradeDate='20230920', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27451.6, self.close=27337.2, self.high=27472.5, self.low=27335.0, self.vol=4027.331, self.amt=110367931.4947 
127.0.0.1 - - [20/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-20 00:20:06,830:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230919   235500    235959  ...         0.0        0.0       0
5760  20230920   000000    000459  ...         0.0        0.0       0
5761  20230920   000500    000959  ...         0.0        0.0       0
5762  20230920   001000    001459  ...         0.0        0.0       0
5763  20230920   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 00:20:06,840:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695140399, self.tradeDate='20230920', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27451.6, self.close=27337.2, self.high=27472.5, self.low=27335.0, self.vol=4027.331, self.amt=110367931.4947, ukdf['pct'].iloc[-1]=-0.004062 , ukdf['amount'].iloc[-1]=110367931.4947, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '18878.52901943606', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27352.29350366', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [20/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37013
self.closeSec=1695140699, self.tradeDate='20230920', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27332.1, self.close=27318.9, self.high=27353.6, self.low=27279.0, self.vol=4222.945, self.amt=115334063.3468 
2023-09-20 00:25:00,844:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230920   000000    000459  ...         0.0        0.0       0
5761  20230920   000500    000959  ...         0.0        0.0       0
5762  20230920   001000    001459  ...         0.0        0.0       0
5763  20230920   001500    001959  ...         0.0        0.0       0
5764  20230920   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 00:25:00,844:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695140699, self.tradeDate='20230920', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27332.1, self.close=27318.9, self.high=27353.6, self.low=27279.0, self.vol=4222.945, self.amt=115334063.3468, ukdf['pct'].iloc[-1]=-0.000669 , ukdf['amount'].iloc[-1]=115334063.3468, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '17682.8301', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27320.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230919   120000    155959  1695110399  ...    723  0.641258  1.818063     1.0
724  20230919   160000    195959  1695124799  ...    724  0.899522  3.024665     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-1269.675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27226.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=771
self.closeSec=1695139199, self.tradeDate='20230919', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27224.4, self.close=27413.2, self.high=27480.0, self.low=26868.0, self.vol=148476.423, self.amt=4037186612.05117 
127.0.0.1 - - [20/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-20 00:00:01,599:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695139199, self.tradeDate='20230919', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27224.4, self.close=27413.2, self.high=27480.0, self.low=26868.0, self.vol=148476.423, self.amt=4037186612.05117 
2023-09-20 00:00:01,615:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230919   040000    075959  ...   29198.239  7.819548e+08 -0.001989
722  20230919   080000    115959  ...   28690.386  7.669091e+08  0.002064
723  20230919   120000    155959  ...   18919.447  5.073238e+08  0.001156
724  20230919   160000    195959  ...  126162.588  3.427120e+09  0.014399
725  20230919   200000    235959  ...  148476.423  4.037187e+09  0.007005

[5 rows x 11 columns]
2023-09-20 00:00:02,442:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230919   040000    075959  1695081599  ...    721  0.718198  2.142217     1.0
722  20230919   080000    115959  1695095999  ...    722  0.701469  2.075714     1.0
723  20230919   120000    155959  1695110399  ...    723  0.641258  1.818063     1.0
724  20230919   160000    195959  1695124799  ...    724  0.899522  3.024665     1.0
725  20230919   200000    235959  1695139199  ...    725  1.189022  3.968225     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '8222.4153', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27413.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


