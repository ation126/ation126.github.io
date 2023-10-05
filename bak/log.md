# 20231005 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41524
self.closeSec=1696493999, self.tradeDate='20231005', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27591.1, self.close=27588.7, self.high=27591.1, self.low=27581.0, self.vol=298.891, self.amt=8244874.4067 
127.0.0.1 - - [05/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-05 16:20:06,492:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231005   155500    155959  ...         0.0        0.0       0
5952  20231005   160000    160459  ...         0.0        0.0       0
5953  20231005   160500    160959  ...         0.0        0.0       0
5954  20231005   161000    161459  ...         0.0        0.0       0
5955  20231005   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 16:20:06,500:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696493999, self.tradeDate='20231005', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27591.1, self.close=27588.7, self.high=27591.1, self.low=27581.0, self.vol=298.891, self.amt=8244874.4067, ukdf['pct'].iloc[-1]=-8.7e-05 , ukdf['amount'].iloc[-1]=8244874.4067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-10028.3697902421', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27585.01846835', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41525
self.closeSec=1696494299, self.tradeDate='20231005', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27587.2, self.close=27581.4, self.high=27589.4, self.low=27578.1, self.vol=232.993, self.amt=6426606.3726 
2023-10-05 16:25:00,783:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231005   160000    160459  ...         0.0        0.0       0
5953  20231005   160500    160959  ...         0.0        0.0       0
5954  20231005   161000    161459  ...         0.0        0.0       0
5955  20231005   161500    161959  ...         0.0        0.0       0
5956  20231005   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 16:25:00,784:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696494299, self.tradeDate='20231005', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27587.2, self.close=27581.4, self.high=27589.4, self.low=27578.1, self.vol=232.993, self.amt=6426606.3726, ukdf['pct'].iloc[-1]=-0.000265 , ukdf['amount'].iloc[-1]=6426606.3726, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-10010.0088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27583.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [05/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41522 

self.closeSec=1696492799, self.tradeDate='20231005', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27584.7, self.close=27595.4, self.high=27598.4, self.low=27583.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41523 

self.closeSec=1696493099, self.tradeDate='20231005', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27595.4, self.close=27593.4, self.high=27603.5, self.low=27587.1 
127.0.0.1 - - [05/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41524 

self.closeSec=1696493399, self.tradeDate='20231005', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27594.0, self.close=27589.1, self.high=27596.0, self.low=27579.5 
127.0.0.1 - - [05/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41525 

self.closeSec=1696493699, self.tradeDate='20231005', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27589.1, self.close=27591.1, self.high=27596.1, self.low=27585.0 
127.0.0.1 - - [05/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41526 

self.closeSec=1696493999, self.tradeDate='20231005', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27591.1, self.close=27588.7, self.high=27591.1, self.low=27581.0 
127.0.0.1 - - [05/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [05/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41527 

self.closeSec=1696494299, self.tradeDate='20231005', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27587.2, self.close=27581.4, self.high=27589.4, self.low=27578.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-05 16:00:18,583:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231005    132959  27678.6  ...  56.250000  0.520309  0.311575
5786  20231005    135959  27659.0  ...  56.250000  0.512924  0.321629
5787  20231005    142959  27625.8  ...  56.250000  0.509615  0.332782
5788  20231005    145959  27611.6  ...  56.666667  0.516546  0.339339
5789  20231005    152959  27643.0  ...  56.250000  0.503193  0.352546

[5 rows x 33 columns]
0.5738007380073801
acc is : 0.5738007380073801
2023-10-05 16:00:18,659:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.492030  0.507970       0  ...  0.971984  -1.0    0.0  1.040333
538     1  0.484722  0.515278       0  ...  0.972519  -1.0    0.0  1.039760
539     1  0.490345  0.509655       1  ...  0.971353  -1.0    0.0  1.041007
540     0  0.503935  0.496065       0  ...  0.973493  -1.0    0.0  1.038713
541     1  0.475016  0.524984       1  ...  0.973027  -1.0    0.0  1.039211

[5 rows x 10 columns]
2023-10-05 16:00:18,672:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491883  0.508117       0  ...  0.971984  -1.0    0.0  1.040505
46     1  0.484395  0.515605       0  ...  0.972519  -1.0    0.0  1.039780
47     1  0.490118  0.509882       1  ...  0.971353  -1.0    0.0  1.040658
48     0  0.503596  0.496404       0  ...  0.973493  -1.0    0.0  1.038217
49     1  0.475016  0.524984       1  ...  0.973027  -1.0    0.0  1.039211

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.906', 'enterprice': '28298.9', 'countrevence': '0', 'unrealprofit': '16923.18565521188', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27590.99463502', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20759 

self.closeSec=1696490999, self.tradeDate='20231005', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27592.1', self.close='27582.1'
127.0.0.1 - - [05/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20760 

self.closeSec=1696491599, self.tradeDate='20231005', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27582', self.close='27555.9'
127.0.0.1 - - [05/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20761 

self.closeSec=1696492199, self.tradeDate='20231005', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27555.8', self.close='27585'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20762 

self.closeSec=1696492799, self.tradeDate='20231005', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27585', self.close='27595.3'
127.0.0.1 - - [05/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20763 

self.closeSec=1696493399, self.tradeDate='20231005', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27595.4', self.close='27589.1'
127.0.0.1 - - [05/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20764 

self.closeSec=1696493999, self.tradeDate='20231005', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27589.1', self.close='27587.2'
127.0.0.1 - - [05/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20762 

self.closeSec=1696490999, self.tradeDate='20231005', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27592.1', self.close='27582.1'
127.0.0.1 - - [05/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20763 

self.closeSec=1696491599, self.tradeDate='20231005', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27582', self.close='27555.9'
127.0.0.1 - - [05/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20764 

self.closeSec=1696492199, self.tradeDate='20231005', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27555.8', self.close='27585'
127.0.0.1 - - [05/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20765 

self.closeSec=1696492799, self.tradeDate='20231005', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27585', self.close='27595.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20766 

self.closeSec=1696493399, self.tradeDate='20231005', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27595.4', self.close='27589.1'
127.0.0.1 - - [05/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20767 

self.closeSec=1696493999, self.tradeDate='20231005', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27589.1', self.close='27587.2'
127.0.0.1 - - [05/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20762 

self.closeSec=1696490999, self.tradeDate='20231005', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27592.1', self.close='27582.1'
127.0.0.1 - - [05/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20763 

self.closeSec=1696491599, self.tradeDate='20231005', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27582', self.close='27555.9'
127.0.0.1 - - [05/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20764 

self.closeSec=1696492199, self.tradeDate='20231005', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27555.8', self.close='27585'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20765 

self.closeSec=1696492799, self.tradeDate='20231005', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27585', self.close='27595.3'
127.0.0.1 - - [05/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20766 

self.closeSec=1696493399, self.tradeDate='20231005', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27595.4', self.close='27589.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20767 

self.closeSec=1696493999, self.tradeDate='20231005', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27589.1', self.close='27587.2'
127.0.0.1 - - [05/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41524
self.closeSec=1696493999, self.tradeDate='20231005', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27591.1, self.close=27588.7, self.high=27591.1, self.low=27581.0, self.vol=298.891, self.amt=8244874.4067 
127.0.0.1 - - [05/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-05 16:20:06,491:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231005   155500    155959  ...         0.0        0.0       0
5952  20231005   160000    160459  ...         0.0        0.0       0
5953  20231005   160500    160959  ...         0.0        0.0       0
5954  20231005   161000    161459  ...         0.0        0.0       0
5955  20231005   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 16:20:06,500:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696493999, self.tradeDate='20231005', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27591.1, self.close=27588.7, self.high=27591.1, self.low=27581.0, self.vol=298.891, self.amt=8244874.4067, ukdf['pct'].iloc[-1]=-8.7e-05 , ukdf['amount'].iloc[-1]=8244874.4067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '27522.16693298735', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27585.01846835', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41525
self.closeSec=1696494299, self.tradeDate='20231005', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27587.2, self.close=27581.4, self.high=27589.4, self.low=27578.1, self.vol=232.993, self.amt=6426606.3726 
2023-10-05 16:25:00,792:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231005   160000    160459  ...         0.0        0.0       0
5953  20231005   160500    160959  ...         0.0        0.0       0
5954  20231005   161000    161459  ...         0.0        0.0       0
5955  20231005   161500    161959  ...         0.0        0.0       0
5956  20231005   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 16:25:00,793:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696494299, self.tradeDate='20231005', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27587.2, self.close=27581.4, self.high=27589.4, self.low=27578.1, self.vol=232.993, self.amt=6426606.3726, ukdf['pct'].iloc[-1]=-0.000265 , ukdf['amount'].iloc[-1]=6426606.3726, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '27473.1977', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27583.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231005   040000    075959  1696463999  ...    721  0.842262  0.259653     NaN
722  20231005   080000    115959  1696478399  ...    722  0.758658  0.072150     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-16548.1888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27637.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1223948.6721539998, self.flagDict['side']='buy', self.tradeCount=29, self.count=865127.0.0.1 - - [05/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1696492799, self.tradeDate='20231005', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27638.0, self.close=27595.4, self.high=27688.4, self.low=27533.1, self.vol=23302.294, self.amt=643546761.13508 
2023-10-05 16:00:01,520:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696492799, self.tradeDate='20231005', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27638.0, self.close=27595.4, self.high=27688.4, self.low=27533.1, self.vol=23302.294, self.amt=643546761.13508 
2023-10-05 16:00:01,533:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231004   200000    235959  ...  55560.010  1.525355e+09 -0.006226
720  20231005   000000    035959  ...  72612.137  2.005745e+09  0.007908
721  20231005   040000    075959  ...  34252.297  9.490155e+08  0.005604
722  20231005   080000    115959  ...  34795.969  9.651662e+08 -0.004373
723  20231005   120000    155959  ...  23302.294  6.435468e+08 -0.001552

[5 rows x 11 columns]
2023-10-05 16:00:02,262:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231004   200000    235959  1696435199  ...    719  0.955153  0.504670     NaN
720  20231005   000000    035959  1696449599  ...    720  0.921129  0.440461     NaN
721  20231005   040000    075959  1696463999  ...    721  0.842262  0.259653     NaN
722  20231005   080000    115959  1696478399  ...    722  0.758658  0.072150     NaN
723  20231005   120000    155959  1696492799  ...    723  0.646229 -0.194907     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-18349.9472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27595.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


