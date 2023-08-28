# 20230828 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30580
self.closeSec=1693210799, self.tradeDate='20230828', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25916.0, self.close=25912.3, self.high=25916.0, self.low=25906.8, self.vol=288.751, self.amt=7481949.1898 
127.0.0.1 - - [28/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-28 16:20:05,039:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230828   155500    155959  ...         0.0        0.0       0
5940  20230828   160000    160459  ...         0.0        0.0       0
5941  20230828   160500    160959  ...         0.0        0.0       0
5942  20230828   161000    161459  ...         0.0        0.0       0
5943  20230828   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 16:20:05,053:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693210799, self.tradeDate='20230828', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25916.0, self.close=25912.3, self.high=25916.0, self.low=25906.8, self.vol=288.751, self.amt=7481949.1898, ukdf['pct'].iloc[-1]=-0.000139 , ukdf['amount'].iloc[-1]=7481949.1898, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13204.6332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25916.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30581
self.closeSec=1693211099, self.tradeDate='20230828', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25912.4, self.close=25943.9, self.high=25946.9, self.low=25912.3, self.vol=572.324, self.amt=14841803.6699 
2023-08-28 16:25:00,801:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230828   160000    160459  ...         0.0        0.0       0
5941  20230828   160500    160959  ...         0.0        0.0       0
5942  20230828   161000    161459  ...         0.0        0.0       0
5943  20230828   161500    161959  ...         0.0        0.0       0
5944  20230828   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 16:25:00,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693211099, self.tradeDate='20230828', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25912.4, self.close=25943.9, self.high=25946.9, self.low=25912.3, self.vol=572.324, self.amt=14841803.6699, ukdf['pct'].iloc[-1]=0.001219 , ukdf['amount'].iloc[-1]=14841803.6699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12796.9987756248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25945.9714652', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [28/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30578 

self.closeSec=1693209599, self.tradeDate='20230828', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25916.3, self.close=25923.0, self.high=25923.1, self.low=25905.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30579 

self.closeSec=1693209899, self.tradeDate='20230828', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25923.1, self.close=25943.8, self.high=25944.4, self.low=25918.9 
127.0.0.1 - - [28/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30580 

self.closeSec=1693210199, self.tradeDate='20230828', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25943.8, self.close=25926.1, self.high=25943.8, self.low=25923.3 
127.0.0.1 - - [28/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30581 

self.closeSec=1693210499, self.tradeDate='20230828', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25926.1, self.close=25915.9, self.high=25926.1, self.low=25913.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30582 

self.closeSec=1693210799, self.tradeDate='20230828', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25916.0, self.close=25912.3, self.high=25916.0, self.low=25906.8 
127.0.0.1 - - [28/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30583 

self.closeSec=1693211099, self.tradeDate='20230828', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25912.4, self.close=25943.9, self.high=25946.9, self.low=25912.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-28 16:00:17,951:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230828    132959  26012.9  ...  50.000000  0.466329  0.600729
5786  20230828    135959  25989.5  ...  49.583333  0.448149  0.606679
5787  20230828    142959  25950.1  ...  49.166667  0.439321  0.616296
5788  20230828    145959  25930.8  ...  49.166667  0.441543  0.624467
5789  20230828    152959  25934.8  ...  48.750000  0.428825  0.637992

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-08-28 16:00:18,016:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.481741  0.518259       0  ...  1.053142  -1.0    0.0  0.908428
538     1  0.473236  0.526764       0  ...  1.053941  -1.0    0.0  0.907738
539     1  0.478523  0.521477       1  ...  1.053783  -1.0    0.0  0.907875
540     1  0.485743  0.514257       0  ...  1.054945  -1.0    0.0  0.906873
541     1  0.473399  0.526601       1  ...  1.054261  -1.0    0.0  0.907462

[5 rows x 10 columns]
2023-08-28 16:00:18,028:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.481596  0.518404       0  ...  1.058553  -1.0    0.0  0.898057
46     1  0.473166  0.526834       0  ...  1.059356  -1.0    0.0  0.899117
47     1  0.478519  0.521481       1  ...  1.059197  -1.0    0.0  0.903198
48     1  0.485562  0.514438       0  ...  1.054945  -1.0    0.0  0.901179
49     1  0.473399  0.526601       1  ...  1.054261  -1.0    0.0  0.907462

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '13506.86797432546', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25923.55899634', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15287 

self.closeSec=1693207799, self.tradeDate='20230828', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25925.5', self.close='25906.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15288 

self.closeSec=1693208399, self.tradeDate='20230828', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25906.1', self.close='25898.4'
127.0.0.1 - - [28/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15289 

self.closeSec=1693208999, self.tradeDate='20230828', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25898.3', self.close='25909.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15290 

self.closeSec=1693209599, self.tradeDate='20230828', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25909.8', self.close='25923'
127.0.0.1 - - [28/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15291 

self.closeSec=1693210199, self.tradeDate='20230828', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25923.1', self.close='25926'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15292 

self.closeSec=1693210799, self.tradeDate='20230828', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25926.1', self.close='25912.3'
127.0.0.1 - - [28/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15290 

self.closeSec=1693207799, self.tradeDate='20230828', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25925.5', self.close='25906.2'
127.0.0.1 - - [28/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15291 

self.closeSec=1693208399, self.tradeDate='20230828', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25906.1', self.close='25898.4'
127.0.0.1 - - [28/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15292 

self.closeSec=1693208999, self.tradeDate='20230828', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25898.3', self.close='25909.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15293 

self.closeSec=1693209599, self.tradeDate='20230828', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25909.8', self.close='25923'
127.0.0.1 - - [28/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15294 

self.closeSec=1693210199, self.tradeDate='20230828', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25923.1', self.close='25926'
127.0.0.1 - - [28/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15295 

self.closeSec=1693210799, self.tradeDate='20230828', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25926.1', self.close='25912.3'
127.0.0.1 - - [28/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [28/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15290 

self.closeSec=1693207799, self.tradeDate='20230828', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25925.5', self.close='25906.2'
127.0.0.1 - - [28/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15291 

self.closeSec=1693208399, self.tradeDate='20230828', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25906.1', self.close='25898.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15292 

self.closeSec=1693208999, self.tradeDate='20230828', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25898.3', self.close='25909.7'
127.0.0.1 - - [28/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15293 

self.closeSec=1693209599, self.tradeDate='20230828', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25909.8', self.close='25923'
127.0.0.1 - - [28/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15294 

self.closeSec=1693210199, self.tradeDate='20230828', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25923.1', self.close='25926'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15295 

self.closeSec=1693210799, self.tradeDate='20230828', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25926.1', self.close='25912.3'
127.0.0.1 - - [28/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30580
self.closeSec=1693210799, self.tradeDate='20230828', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25916.0, self.close=25912.3, self.high=25916.0, self.low=25906.8, self.vol=288.751, self.amt=7481949.1898 
127.0.0.1 - - [28/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-28 16:20:05,034:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230828   155500    155959  ...         0.0        0.0       0
5940  20230828   160000    160459  ...         0.0        0.0       0
5941  20230828   160500    160959  ...         0.0        0.0       0
5942  20230828   161000    161459  ...         0.0        0.0       0
5943  20230828   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 16:20:05,037:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693210799, self.tradeDate='20230828', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25916.0, self.close=25912.3, self.high=25916.0, self.low=25906.8, self.vol=288.751, self.amt=7481949.1898, ukdf['pct'].iloc[-1]=-0.000139 , ukdf['amount'].iloc[-1]=7481949.1898, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-34440.8493', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25916.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30581
self.closeSec=1693211099, self.tradeDate='20230828', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25912.4, self.close=25943.9, self.high=25946.9, self.low=25912.3, self.vol=572.324, self.amt=14841803.6699 
127.0.0.1 - - [28/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-28 16:25:00,800:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230828   160000    160459  ...         0.0        0.0       0
5941  20230828   160500    160959  ...         0.0        0.0       0
5942  20230828   161000    161459  ...         0.0        0.0       0
5943  20230828   161500    161959  ...         0.0        0.0       0
5944  20230828   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 16:25:00,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693211099, self.tradeDate='20230828', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25912.4, self.close=25943.9, self.high=25946.9, self.low=25912.3, self.vol=572.324, self.amt=14841803.6699, ukdf['pct'].iloc[-1]=0.001219 , ukdf['amount'].iloc[-1]=14841803.6699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-33353.6778110068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25945.9714652', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230828   040000    075959  1693180799  ...    721  0.356459  0.461291     NaN
722  20230828   080000    115959  1693195199  ...    722  0.262611  0.118184     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '176265.82237698352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26002.50304396', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=637
self.closeSec=1693209599, self.tradeDate='20230828', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26002.0, self.close=25923.0, self.high=26024.7, self.low=25850.4, self.vol=30904.881, self.amt=801625121.62688 
127.0.0.1 - - [28/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-08-28 16:00:01,550:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693209599, self.tradeDate='20230828', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26002.0, self.close=25923.0, self.high=26024.7, self.low=25850.4, self.vol=30904.881, self.amt=801625121.62688 
2023-08-28 16:00:01,580:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230827   200000    235959  ...  21791.010  5.691195e+08  0.002372
720  20230828   000000    035959  ...  22000.852  5.742453e+08  0.000050
721  20230828   040000    075959  ...  11740.215  3.061151e+08 -0.000934
722  20230828   080000    115959  ...  26342.016  6.855075e+08 -0.003285
723  20230828   120000    155959  ...  30904.881  8.016251e+08 -0.003038

[5 rows x 11 columns]
2023-08-28 16:00:02,354:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230827   200000    235959  1693151999  ...    719  0.315218  0.156514     NaN
720  20230828   000000    035959  1693166399  ...    720  0.375165  0.435366     NaN
721  20230828   040000    075959  1693180799  ...    721  0.356459  0.461291     NaN
722  20230828   080000    115959  1693195199  ...    722  0.262611  0.118184     NaN
723  20230828   120000    155959  1693209599  ...    723  0.170310 -0.261334     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '180346.186', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25923.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


