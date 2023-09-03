# 20230903 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32308
self.closeSec=1693729199, self.tradeDate='20230903', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25892.4, self.close=25891.3, self.high=25899.8, self.low=25880.0, self.vol=416.367, self.amt=10779503.7653 
127.0.0.1 - - [03/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-03 16:20:05,207:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230903   155500    155959  ...         0.0        0.0       0
5940  20230903   160000    160459  ...         0.0        0.0       0
5941  20230903   160500    160959  ...         0.0        0.0       0
5942  20230903   161000    161459  ...         0.0        0.0       0
5943  20230903   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 16:20:05,215:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693729199, self.tradeDate='20230903', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25892.4, self.close=25891.3, self.high=25899.8, self.low=25880.0, self.vol=416.367, self.amt=10779503.7653, ukdf['pct'].iloc[-1]=-4.6e-05 , ukdf['amount'].iloc[-1]=10779503.7653, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13559.7462', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25891.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32309
self.closeSec=1693729499, self.tradeDate='20230903', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25891.2, self.close=25878.5, self.high=25894.0, self.low=25878.4, self.vol=371.855, self.amt=9625964.5615 
127.0.0.1 - - [03/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-03 16:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230903   160000    160459  ...         0.0        0.0       0
5941  20230903   160500    160959  ...         0.0        0.0       0
5942  20230903   161000    161459  ...         0.0        0.0       0
5943  20230903   161500    161959  ...         0.0        0.0       0
5944  20230903   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 16:25:00,792:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693729499, self.tradeDate='20230903', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25891.2, self.close=25878.5, self.high=25894.0, self.low=25878.4, self.vol=371.855, self.amt=9625964.5615, ukdf['pct'].iloc[-1]=-0.000494 , ukdf['amount'].iloc[-1]=9625964.5615, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13711.55067966486', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25880.29920439', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [03/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32306 

self.closeSec=1693727999, self.tradeDate='20230903', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25926.7, self.close=25941.4, self.high=25943.6, self.low=25926.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32307 

self.closeSec=1693728299, self.tradeDate='20230903', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25941.5, self.close=25931.0, self.high=25943.7, self.low=25924.3 
127.0.0.1 - - [03/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32308 

self.closeSec=1693728599, self.tradeDate='20230903', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25931.0, self.close=25919.5, self.high=25935.3, self.low=25919.5 
127.0.0.1 - - [03/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32309 

self.closeSec=1693728899, self.tradeDate='20230903', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25919.5, self.close=25892.5, self.high=25919.6, self.low=25879.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32310 

self.closeSec=1693729199, self.tradeDate='20230903', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25892.4, self.close=25891.3, self.high=25899.8, self.low=25880.0 
127.0.0.1 - - [03/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32311 

self.closeSec=1693729499, self.tradeDate='20230903', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25891.2, self.close=25878.5, self.high=25894.0, self.low=25878.4 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-03 16:00:18,498:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230903    132959  25862.5  ...  46.250000  0.477557  0.507826
5786  20230903    135959  25885.0  ...  46.250000  0.477525  0.500774
5787  20230903    142959  25885.0  ...  46.250000  0.476624  0.494996
5788  20230903    145959  25882.2  ...  46.666667  0.482996  0.484457
5789  20230903    152959  25899.4  ...  46.250000  0.481923  0.475542

[5 rows x 33 columns]
0.5239852398523985
acc is : 0.5239852398523985
2023-09-03 16:00:18,557:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502627  0.497373       1  ...  1.002255  -1.0    0.0  0.994529
538     1  0.497762  0.502238       0  ...  1.002359  -1.0    0.0  0.994425
539     1  0.495961  0.504039       1  ...  1.001689  -1.0    0.0  0.995090
540     0  0.502806  0.497194       0  ...  1.001809  -1.0    0.0  0.994971
541     1  0.496221  0.503779       1  ...  1.000068  -1.0    0.0  0.996700

[5 rows x 10 columns]
2023-09-03 16:00:18,568:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503582  0.496418       1  ...  1.013133  -1.0    0.0  1.003388
46     1  0.498181  0.501819       0  ...  1.013238  -1.0    0.0  0.999077
47     1  0.496215  0.503785       1  ...  1.012561  -1.0    0.0  0.994436
48     0  0.502566  0.497434       0  ...  1.001809  -1.0    0.0  0.993151
49     1  0.496221  0.503779       1  ...  1.000068  -1.0    0.0  0.996700

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '19468.7619', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25941.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16151 

self.closeSec=1693726199, self.tradeDate='20230903', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25920.1', self.close='25896.4'
127.0.0.1 - - [03/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16152 

self.closeSec=1693726799, self.tradeDate='20230903', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25896.5', self.close='25917.6'
127.0.0.1 - - [03/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16153 

self.closeSec=1693727399, self.tradeDate='20230903', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25917.5', self.close='25928.9'
127.0.0.1 - - [03/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16154 

self.closeSec=1693727999, self.tradeDate='20230903', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25928.9', self.close='25941.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16155 

self.closeSec=1693728599, self.tradeDate='20230903', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25941.5', self.close='25919.5'
127.0.0.1 - - [03/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16156 

self.closeSec=1693729199, self.tradeDate='20230903', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25919.5', self.close='25891.3'
127.0.0.1 - - [03/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16154 

self.closeSec=1693726199, self.tradeDate='20230903', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25920.1', self.close='25896.4'
127.0.0.1 - - [03/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16155 

self.closeSec=1693726799, self.tradeDate='20230903', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25896.5', self.close='25917.6'
127.0.0.1 - - [03/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16156 

self.closeSec=1693727399, self.tradeDate='20230903', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25917.5', self.close='25928.9'
127.0.0.1 - - [03/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16157 

self.closeSec=1693727999, self.tradeDate='20230903', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25928.9', self.close='25941.4'
127.0.0.1 - - [03/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16158 

self.closeSec=1693728599, self.tradeDate='20230903', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25941.5', self.close='25919.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16159 

self.closeSec=1693729199, self.tradeDate='20230903', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25919.5', self.close='25891.3'
127.0.0.1 - - [03/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16154 

self.closeSec=1693726199, self.tradeDate='20230903', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25920.1', self.close='25896.4'
127.0.0.1 - - [03/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16155 

self.closeSec=1693726799, self.tradeDate='20230903', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25896.5', self.close='25917.6'
127.0.0.1 - - [03/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16156 

self.closeSec=1693727399, self.tradeDate='20230903', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25917.5', self.close='25928.9'
127.0.0.1 - - [03/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16157 

self.closeSec=1693727999, self.tradeDate='20230903', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25928.9', self.close='25941.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16158 

self.closeSec=1693728599, self.tradeDate='20230903', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25941.5', self.close='25919.5'
127.0.0.1 - - [03/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16159 

self.closeSec=1693729199, self.tradeDate='20230903', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25919.5', self.close='25891.3'
127.0.0.1 - - [03/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32308
self.closeSec=1693729199, self.tradeDate='20230903', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25892.4, self.close=25891.3, self.high=25899.8, self.low=25880.0, self.vol=416.367, self.amt=10779503.7653 
127.0.0.1 - - [03/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-03 16:20:05,204:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230903   155500    155959  ...         0.0        0.0       0
5940  20230903   160000    160459  ...         0.0        0.0       0
5941  20230903   160500    160959  ...         0.0        0.0       0
5942  20230903   161000    161459  ...         0.0        0.0       0
5943  20230903   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 16:20:05,207:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693729199, self.tradeDate='20230903', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25892.4, self.close=25891.3, self.high=25899.8, self.low=25880.0, self.vol=416.367, self.amt=10779503.7653, ukdf['pct'].iloc[-1]=-4.6e-05 , ukdf['amount'].iloc[-1]=10779503.7653, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35384.2307', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25891.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32309
self.closeSec=1693729499, self.tradeDate='20230903', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25891.2, self.close=25878.5, self.high=25894.0, self.low=25878.4, self.vol=371.855, self.amt=9625964.5615 
2023-09-03 16:25:00,793:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230903   160000    160459  ...         0.0        0.0       0
5941  20230903   160500    160959  ...         0.0        0.0       0
5942  20230903   161000    161459  ...         0.0        0.0       0
5943  20230903   161500    161959  ...         0.0        0.0       0
5944  20230903   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 16:25:00,793:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693729499, self.tradeDate='20230903', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25891.2, self.close=25878.5, self.high=25894.0, self.low=25878.4, self.vol=371.855, self.amt=9625964.5615, ukdf['pct'].iloc[-1]=-0.000494 , ukdf['amount'].iloc[-1]=9625964.5615, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35792.81124975101', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25880.29920439', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230903   040000    075959  1693699199  ...    721  0.829327  1.340573     1.0
722  20230903   080000    115959  1693713599  ...    722  0.819361  1.286562     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-113527.16491664652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25850.86202549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=673
self.closeSec=1693727999, self.tradeDate='20230903', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25850.0, self.close=25941.4, self.high=25943.6, self.low=25849.9, self.vol=11059.332, self.amt=286428322.4218 
127.0.0.1 - - [03/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-03 16:00:01,577:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693727999, self.tradeDate='20230903', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25850.0, self.close=25941.4, self.high=25943.6, self.low=25849.9, self.vol=11059.332, self.amt=286428322.4218 
2023-09-03 16:00:01,592:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230902   200000    235959  ...  31794.939  8.226471e+08  0.003097
720  20230903   000000    035959  ...  22126.255  5.714335e+08 -0.002257
721  20230903   040000    075959  ...   9378.742  2.424156e+08  0.001328
722  20230903   080000    115959  ...  10366.408  2.680259e+08 -0.000228
723  20230903   120000    155959  ...  11059.332  2.864283e+08  0.003536

[5 rows x 11 columns]
2023-09-03 16:00:02,319:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230902   200000    235959  1693670399  ...    719  0.671203  0.911753     1.0
720  20230903   000000    035959  1693684799  ...    720  0.869357  1.490222     1.0
721  20230903   040000    075959  1693699199  ...    721  0.829327  1.340573     1.0
722  20230903   080000    115959  1693713599  ...    722  0.819361  1.286562     1.0
723  20230903   120000    155959  1693727999  ...    723  0.789376  1.178070     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-108337.9596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25941.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


