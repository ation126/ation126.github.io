# 20230906 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32980
self.closeSec=1693930799, self.tradeDate='20230906', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25804.8, self.close=25786.7, self.high=25807.8, self.low=25773.8, self.vol=608.733, self.amt=15699885.2961 
127.0.0.1 - - [06/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-06 00:20:05,761:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230905   235500    235959  ...         0.0        0.0       0
5760  20230906   000000    000459  ...         0.0        0.0       0
5761  20230906   000500    000959  ...         0.0        0.0       0
5762  20230906   001000    001459  ...         0.0        0.0       0
5763  20230906   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 00:20:05,765:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693930799, self.tradeDate='20230906', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25804.8, self.close=25786.7, self.high=25807.8, self.low=25773.8, self.vol=608.733, self.amt=15699885.2961, ukdf['pct'].iloc[-1]=-0.000698 , ukdf['amount'].iloc[-1]=15699885.2961, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15011.1529128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25786.9772', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32981
self.closeSec=1693931099, self.tradeDate='20230906', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25786.4, self.close=25791.1, self.high=25794.9, self.low=25759.1, self.vol=593.747, self.amt=15303776.791 
2023-09-06 00:25:00,772:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230906   000000    000459  ...         0.0        0.0       0
5761  20230906   000500    000959  ...         0.0        0.0       0
5762  20230906   001000    001459  ...         0.0        0.0       0
5763  20230906   001500    001959  ...         0.0        0.0       0
5764  20230906   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 00:25:00,772:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693931099, self.tradeDate='20230906', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25786.4, self.close=25791.1, self.high=25794.9, self.low=25759.1, self.vol=593.747, self.amt=15303776.791, ukdf['pct'].iloc[-1]=0.000171 , ukdf['amount'].iloc[-1]=15303776.791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14949.6506451435', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25791.39356275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [06/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230901' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32980 

self.closeSec=1693930199, self.tradeDate='20230906', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25733.7, self.close=25776.1, self.high=25782.0, self.low=25733.6 
127.0.0.1 - - [06/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32981 

self.closeSec=1693930499, self.tradeDate='20230906', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25775.2, self.close=25804.7, self.high=25804.8, self.low=25767.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32982 

self.closeSec=1693930799, self.tradeDate='20230906', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25804.8, self.close=25786.7, self.high=25807.8, self.low=25773.8 
127.0.0.1 - - [06/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32983 

self.closeSec=1693931099, self.tradeDate='20230906', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25786.4, self.close=25791.1, self.high=25794.9, self.low=25759.1 
127.0.0.1 - - [06/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-06 00:00:20,546:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230905    212959  25809.7  ...  47.083333  0.481606  0.555403
5802  20230905    215959  25771.1  ...  47.083333  0.466192  0.553279
5803  20230905    222959  25724.4  ...  47.083333  0.454478  0.557327
5804  20230905    225959  25687.7  ...  47.083333  0.459874  0.556856
5805  20230905    232959  25702.1  ...  47.083333  0.453283  0.560031

[5 rows x 33 columns]
0.5386029411764706
acc is : 0.5386029411764706
2023-09-06 00:00:20,624:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.482796  0.517204       0  ...  0.992450  -1.0    0.0  0.990570
540     1  0.475401  0.524599       0  ...  0.993866  -1.0    0.0  0.989156
541     1  0.471853  0.528147       1  ...  0.993313  -1.0    0.0  0.989707
542     1  0.491530  0.508470       0  ...  0.994109  -1.0    0.0  0.988914
543     1  0.472700  0.527300       1  ...  0.991542  -1.0    0.0  0.991467

[5 rows x 10 columns]
2023-09-06 00:00:20,639:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.482992  0.517008       0  ...  0.992450  -1.0    0.0  0.988366
46     1  0.476004  0.523996       0  ...  0.993866  -1.0    0.0  0.987810
47     1  0.471527  0.528473       1  ...  0.993313  -1.0    0.0  0.986925
48     1  0.491669  0.508331       0  ...  0.994109  -1.0    0.0  0.986134
49     1  0.472700  0.527300       1  ...  0.991542  -1.0    0.0  0.991467

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '24618.9362', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25745.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16487 

self.closeSec=1693927799, self.tradeDate='20230905', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25830.2', self.close='25681.5'
127.0.0.1 - - [05/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [05/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16488 

self.closeSec=1693928399, self.tradeDate='20230905', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25681.4', self.close='25768.3'
127.0.0.1 - - [05/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16489 

self.closeSec=1693928999, self.tradeDate='20230905', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25769', self.close='25773.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16490 

self.closeSec=1693929599, self.tradeDate='20230905', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25773.1', self.close='25747.8'
127.0.0.1 - - [06/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16491 

self.closeSec=1693930199, self.tradeDate='20230906', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25747.9', self.close='25776.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16492 

self.closeSec=1693930799, self.tradeDate='20230906', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25775.2', self.close='25786.4'
127.0.0.1 - - [06/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16490 

self.closeSec=1693927799, self.tradeDate='20230905', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25830.2', self.close='25681.5'
127.0.0.1 - - [05/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16491 

self.closeSec=1693928399, self.tradeDate='20230905', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25681.4', self.close='25768.3'
127.0.0.1 - - [05/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [05/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16492 

self.closeSec=1693928999, self.tradeDate='20230905', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25769', self.close='25773.2'

--handleKline--: 127.0.0.1 - - [06/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16493 

self.closeSec=1693929599, self.tradeDate='20230905', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25773.1', self.close='25747.8'
127.0.0.1 - - [06/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16494 

self.closeSec=1693930199, self.tradeDate='20230906', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25747.9', self.close='25776.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16495 

self.closeSec=1693930799, self.tradeDate='20230906', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25775.2', self.close='25786.4'
127.0.0.1 - - [06/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16490 

self.closeSec=1693927799, self.tradeDate='20230905', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25830.2', self.close='25681.5'
127.0.0.1 - - [05/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16491 

self.closeSec=1693928399, self.tradeDate='20230905', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25681.4', self.close='25768.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16492 

self.closeSec=1693928999, self.tradeDate='20230905', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25769', self.close='25773.2'
127.0.0.1 - - [05/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16493 

self.closeSec=1693929599, self.tradeDate='20230905', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25773.1', self.close='25747.8'
127.0.0.1 - - [06/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16494 

self.closeSec=1693930199, self.tradeDate='20230906', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25747.9', self.close='25776.1'
127.0.0.1 - - [06/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16495 

self.closeSec=1693930799, self.tradeDate='20230906', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25775.2', self.close='25786.4'
127.0.0.1 - - [06/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32980
self.closeSec=1693930799, self.tradeDate='20230906', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25804.8, self.close=25786.7, self.high=25807.8, self.low=25773.8, self.vol=608.733, self.amt=15699885.2961 
127.0.0.1 - - [06/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-06 00:20:05,752:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230905   235500    235959  ...         0.0        0.0       0
5760  20230906   000000    000459  ...         0.0        0.0       0
5761  20230906   000500    000959  ...         0.0        0.0       0
5762  20230906   001000    001459  ...         0.0        0.0       0
5763  20230906   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 00:20:05,763:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693930799, self.tradeDate='20230906', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25804.8, self.close=25786.7, self.high=25807.8, self.low=25773.8, self.vol=608.733, self.amt=15699885.2961, ukdf['pct'].iloc[-1]=-0.000698 , ukdf['amount'].iloc[-1]=15699885.2961, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-39258.8838148', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25786.9772', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32981
self.closeSec=1693931099, self.tradeDate='20230906', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25786.4, self.close=25791.1, self.high=25794.9, self.low=25759.1, self.vol=593.747, self.amt=15303776.791 
2023-09-06 00:25:00,765:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230906   000000    000459  ...         0.0        0.0       0
5761  20230906   000500    000959  ...         0.0        0.0       0
5762  20230906   001000    001459  ...         0.0        0.0       0
5763  20230906   001500    001959  ...         0.0        0.0       0
5764  20230906   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 00:25:00,765:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693931099, self.tradeDate='20230906', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25786.4, self.close=25791.1, self.high=25794.9, self.low=25759.1, self.vol=593.747, self.amt=15303776.791, ukdf['pct'].iloc[-1]=0.000171 , ukdf['amount'].iloc[-1]=15303776.791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-39094.85568590225', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25791.39356275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230905   120000    155959  1693900799  ...    723  0.005918 -1.076044    -1.0
724  20230905   160000    195959  1693915199  ...    724  0.004898 -1.066787    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '6884.1108', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25771.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=687
self.closeSec=1693929599, self.tradeDate='20230905', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25771.3, self.close=25747.8, self.high=25900.0, self.low=25610.0, self.vol=67199.02, self.amt=1730131385.43464 
127.0.0.1 - - [06/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-06 00:00:01,641:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693929599, self.tradeDate='20230905', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25771.3, self.close=25747.8, self.high=25900.0, self.low=25610.0, self.vol=67199.02, self.amt=1730131385.43464 
2023-09-06 00:00:01,657:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230905   040000    075959  ...  39711.730  1.022570e+09 -0.002589
722  20230905   080000    115959  ...  30823.803  7.916805e+08 -0.005125
723  20230905   120000    155959  ...  20015.690  5.144326e+08  0.001674
724  20230905   160000    195959  ...  29224.242  7.520790e+08  0.001811
725  20230905   200000    235959  ...  67199.020  1.730131e+09 -0.000912

[5 rows x 11 columns]
2023-09-06 00:00:02,403:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230905   040000    075959  1693871999  ...    721  0.000329 -1.127232    -1.0
722  20230905   080000    115959  1693886399  ...    722  0.005837 -1.092392    -1.0
723  20230905   120000    155959  1693900799  ...    723  0.005918 -1.076044    -1.0
724  20230905   160000    195959  1693915199  ...    724  0.004898 -1.066787    -1.0
725  20230905   200000    235959  1693929599  ...    725  0.002931 -1.066895    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '8262.0765', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25747.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


