# 20230827 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30100
self.closeSec=1693066799, self.tradeDate='20230827', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26035.6, self.close=26021.1, self.high=26035.7, self.low=26020.2, self.vol=505.168, self.amt=13147800.862 
127.0.0.1 - - [27/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-27 00:20:05,628:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230826   235500    235959  ...         0.0        0.0       0
5748  20230827   000000    000459  ...         0.0        0.0       0
5749  20230827   000500    000959  ...         0.0        0.0       0
5750  20230827   001000    001459  ...         0.0        0.0       0
5751  20230827   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 00:20:05,648:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693066799, self.tradeDate='20230827', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26035.6, self.close=26021.1, self.high=26035.7, self.low=26020.2, self.vol=505.168, self.amt=13147800.862, ukdf['pct'].iloc[-1]=-0.000557 , ukdf['amount'].iloc[-1]=13147800.862, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11683.914', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26025.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30101
self.closeSec=1693067099, self.tradeDate='20230827', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26021.1, self.close=26027.7, self.high=26027.8, self.low=26021.0, self.vol=158.46, self.amt=4123930.9829 
2023-08-27 00:25:00,762:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230827   000000    000459  ...         0.0        0.0       0
5749  20230827   000500    000959  ...         0.0        0.0       0
5750  20230827   001000    001459  ...         0.0        0.0       0
5751  20230827   001500    001959  ...         0.0        0.0       0
5752  20230827   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 00:25:00,763:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693067099, self.tradeDate='20230827', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26021.1, self.close=26027.7, self.high=26027.8, self.low=26021.0, self.vol=158.46, self.amt=4123930.9829, ukdf['pct'].iloc[-1]=0.000254 , ukdf['amount'].iloc[-1]=4123930.9829, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11657.4546', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26027.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [27/Aug/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230822' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [27/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30100 

self.closeSec=1693066199, self.tradeDate='20230827', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26047.5, self.close=26046.3, self.high=26048.5, self.low=26046.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30101 

self.closeSec=1693066499, self.tradeDate='20230827', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26046.3, self.close=26035.6, self.high=26046.3, self.low=26035.6 
127.0.0.1 - - [27/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30102 

self.closeSec=1693066799, self.tradeDate='20230827', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26035.6, self.close=26021.1, self.high=26035.7, self.low=26020.2 
127.0.0.1 - - [27/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30103 

self.closeSec=1693067099, self.tradeDate='20230827', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26021.1, self.close=26027.7, self.high=26027.8, self.low=26021.0 
127.0.0.1 - - [27/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-27 00:00:17,516:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230826    212959  26016.4  ...  51.666667  0.483151  0.431080
5802  20230826    215959  26019.0  ...  51.666667  0.488131  0.425885
5803  20230826    222959  26034.4  ...  51.666667  0.483379  0.435588
5804  20230826    225959  26019.1  ...  51.666667  0.495740  0.431532
5805  20230826    232959  26056.9  ...  51.666667  0.490197  0.433819

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-08-27 00:00:17,579:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.492040  0.507960       1  ...  1.071532  -1.0    0.0  0.887129
540     0  0.500159  0.499841       0  ...  1.072166  -1.0    0.0  0.886604
541     1  0.483288  0.516712       1  ...  1.070600  -1.0    0.0  0.887899
542     0  0.507436  0.492564       0  ...  1.071323  -1.0    0.0  0.887299
543     1  0.486688  0.513312       1  ...  1.071294  -1.0    0.0  0.887323

[5 rows x 10 columns]
2023-08-27 00:00:17,590:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492068  0.507932       1  ...  1.071532  -1.0    0.0  0.886718
46     0  0.500208  0.499792       0  ...  1.064849  -1.0    0.0  0.886474
47     1  0.483275  0.516725       1  ...  1.070600  -1.0    0.0  0.887388
48     0  0.507523  0.492477       0  ...  1.071323  -1.0    0.0  0.886789
49     1  0.486688  0.513312       1  ...  1.071294  -1.0    0.0  0.887323

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '10112.3442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26043.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15047 

self.closeSec=1693063799, self.tradeDate='20230826', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26053.1', self.close='26039.4'
127.0.0.1 - - [26/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15048 

self.closeSec=1693064399, self.tradeDate='20230826', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26039.3', self.close='26043'
127.0.0.1 - - [26/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15049 

self.closeSec=1693064999, self.tradeDate='20230826', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26043', self.close='26040.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15050 

self.closeSec=1693065599, self.tradeDate='20230826', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26040.1', self.close='26040.2'
127.0.0.1 - - [27/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15051 

self.closeSec=1693066199, self.tradeDate='20230827', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26040.2', self.close='26046.3'
127.0.0.1 - - [27/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15052 

self.closeSec=1693066799, self.tradeDate='20230827', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26046.3', self.close='26021.1'
127.0.0.1 - - [27/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15050 

self.closeSec=1693063799, self.tradeDate='20230826', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26053.1', self.close='26039.4'
127.0.0.1 - - [26/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15051 

self.closeSec=1693064399, self.tradeDate='20230826', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26039.3', self.close='26043'
127.0.0.1 - - [26/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15052 

self.closeSec=1693064999, self.tradeDate='20230826', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26043', self.close='26040.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15053 

self.closeSec=1693065599, self.tradeDate='20230826', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26040.1', self.close='26040.2'
127.0.0.1 - - [27/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15054 

self.closeSec=1693066199, self.tradeDate='20230827', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26040.2', self.close='26046.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15055 

self.closeSec=1693066799, self.tradeDate='20230827', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26046.3', self.close='26021.1'
127.0.0.1 - - [27/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15050 

self.closeSec=1693063799, self.tradeDate='20230826', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26053.1', self.close='26039.4'

--handleKline--:  127.0.0.1 - - [26/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15051 

self.closeSec=1693064399, self.tradeDate='20230826', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26039.3', self.close='26043'
127.0.0.1 - - [26/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15052 

self.closeSec=1693064999, self.tradeDate='20230826', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26043', self.close='26040.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15053 

self.closeSec=1693065599, self.tradeDate='20230826', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26040.1', self.close='26040.2'
127.0.0.1 - - [27/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15054 

self.closeSec=1693066199, self.tradeDate='20230827', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26040.2', self.close='26046.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15055 

self.closeSec=1693066799, self.tradeDate='20230827', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26046.3', self.close='26021.1'
127.0.0.1 - - [27/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30100
self.closeSec=1693066799, self.tradeDate='20230827', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26035.6, self.close=26021.1, self.high=26035.7, self.low=26020.2, self.vol=505.168, self.amt=13147800.862 
127.0.0.1 - - [27/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-27 00:20:05,621:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230826   235500    235959  ...         0.0        0.0       0
5748  20230827   000000    000459  ...         0.0        0.0       0
5749  20230827   000500    000959  ...         0.0        0.0       0
5750  20230827   001000    001459  ...         0.0        0.0       0
5751  20230827   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 00:20:05,635:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693066799, self.tradeDate='20230827', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26035.6, self.close=26021.1, self.high=26035.7, self.low=26020.2, self.vol=505.168, self.amt=13147800.862, ukdf['pct'].iloc[-1]=-0.000557 , ukdf['amount'].iloc[-1]=13147800.862, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-30385.0521', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26025.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [27/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30101
self.closeSec=1693067099, self.tradeDate='20230827', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26021.1, self.close=26027.7, self.high=26027.8, self.low=26021.0, self.vol=158.46, self.amt=4123930.9829 
2023-08-27 00:25:00,761:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230827   000000    000459  ...         0.0        0.0       0
5749  20230827   000500    000959  ...         0.0        0.0       0
5750  20230827   001000    001459  ...         0.0        0.0       0
5751  20230827   001500    001959  ...         0.0        0.0       0
5752  20230827   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 00:25:00,761:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693067099, self.tradeDate='20230827', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26021.1, self.close=26027.7, self.high=26027.8, self.low=26021.0, self.vol=158.46, self.amt=4123930.9829, ukdf['pct'].iloc[-1]=0.000254 , ukdf['amount'].iloc[-1]=4123930.9829, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-30314.4842', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26027.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230826   120000    155959  1693036799  ...    723  0.154498 -0.485747     NaN
724  20230826   160000    195959  1693051199  ...    724  0.150684 -0.481358     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174518.7868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26036.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=627
self.closeSec=1693065599, self.tradeDate='20230826', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26036.0, self.close=26040.1, self.high=26070.0, self.low=25969.0, self.vol=12983.287, self.amt=337927186.8796 
127.0.0.1 - - [27/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-27 00:00:01,535:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693065599, self.tradeDate='20230826', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26036.0, self.close=26040.1, self.high=26070.0, self.low=25969.0, self.vol=12983.287, self.amt=337927186.8796 
2023-08-27 00:00:01,560:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230826   040000    075959  ...  17754.194  4.621762e+08  0.003459
722  20230826   080000    115959  ...  13952.931  3.636576e+08  0.000948
723  20230826   120000    155959  ...   8045.871  2.096201e+08 -0.001407
724  20230826   160000    195959  ...  12714.098  3.307631e+08 -0.000146
725  20230826   200000    235959  ...  12983.287  3.379272e+08  0.000161

[5 rows x 11 columns]
2023-08-27 00:00:02,279:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230826   040000    075959  1693007999  ...    721  0.169228 -0.477095     NaN
722  20230826   080000    115959  1693022399  ...    722  0.162292 -0.480094     NaN
723  20230826   120000    155959  1693036799  ...    723  0.154498 -0.485747     NaN
724  20230826   160000    195959  1693051199  ...    724  0.150684 -0.481358     NaN
725  20230826   200000    235959  1693065599  ...    725  0.155291 -0.455290     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174328.6512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26040.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


