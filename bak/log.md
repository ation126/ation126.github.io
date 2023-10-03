# 20231003 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40948
self.closeSec=1696321199, self.tradeDate='20231003', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27579.0, self.close=27600.9, self.high=27604.0, self.low=27578.9, self.vol=556.427, self.amt=15351883.9924 
127.0.0.1 - - [03/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-03 16:20:05,645:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231003   155500    155959  ...         0.0        0.0       0
5952  20231003   160000    160459  ...         0.0        0.0       0
5953  20231003   160500    160959  ...         0.0        0.0       0
5954  20231003   161000    161459  ...         0.0        0.0       0
5955  20231003   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 16:20:05,654:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696321199, self.tradeDate='20231003', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27579.0, self.close=27600.9, self.high=27604.0, self.low=27578.9, self.vol=556.427, self.amt=15351883.9924, ukdf['pct'].iloc[-1]=0.000798 , ukdf['amount'].iloc[-1]=15351883.9924, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-10258.04762578992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27601.51120392', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40949
self.closeSec=1696321499, self.tradeDate='20231003', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27600.8, self.close=27612.1, self.high=27618.1, self.low=27599.0, self.vol=665.649, self.amt=18378303.542 
127.0.0.1 - - [03/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-10-03 16:25:00,782:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231003   160000    160459  ...         0.0        0.0       0
5953  20231003   160500    160959  ...         0.0        0.0       0
5954  20231003   161000    161459  ...         0.0        0.0       0
5955  20231003   161500    161959  ...         0.0        0.0       0
5956  20231003   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 16:25:00,783:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696321499, self.tradeDate='20231003', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27600.8, self.close=27612.1, self.high=27618.1, self.low=27599.0, self.vol=665.649, self.amt=18378303.542, ukdf['pct'].iloc[-1]=0.000406 , ukdf['amount'].iloc[-1]=18378303.542, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-10407.38742849894', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27612.23501569', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [03/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40946 

self.closeSec=1696319999, self.tradeDate='20231003', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27540.8, self.close=27528.0, self.high=27540.8, self.low=27519.8 
127.0.0.1 - - [03/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40947 

self.closeSec=1696320299, self.tradeDate='20231003', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27528.0, self.close=27561.4, self.high=27561.4, self.low=27525.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40948 

self.closeSec=1696320599, self.tradeDate='20231003', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27561.4, self.close=27578.5, self.high=27578.5, self.low=27556.6 
127.0.0.1 - - [03/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40949 

self.closeSec=1696320899, self.tradeDate='20231003', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27578.5, self.close=27578.9, self.high=27579.0, self.low=27570.0 
127.0.0.1 - - [03/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40950 

self.closeSec=1696321199, self.tradeDate='20231003', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27579.0, self.close=27600.9, self.high=27604.0, self.low=27578.9 
127.0.0.1 - - [03/Oct/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40951 

self.closeSec=1696321499, self.tradeDate='20231003', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27600.8, self.close=27612.1, self.high=27618.1, self.low=27599.0 
127.0.0.1 - - [03/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-03 16:00:18,415:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231003    132959  27620.0  ...  55.833333  0.491258  0.676032
5786  20231003    135959  27579.5  ...  55.833333  0.486927  0.683016
5787  20231003    142959  27552.7  ...  56.250000  0.492164  0.687997
5788  20231003    145959  27585.9  ...  56.250000  0.498490  0.690785
5789  20231003    152959  27621.9  ...  56.250000  0.489688  0.696019

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-10-03 16:00:18,491:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485042  0.514958       0  ...  0.950877  -1.0    0.0  1.034649
538     1  0.488290  0.511710       1  ...  0.949797  -1.0    0.0  1.035824
539     0  0.504804  0.495196       1  ...  0.948492  -1.0    0.0  1.037247
540     0  0.510624  0.489376       0  ...  0.950332  -1.0    0.0  1.035235
541     1  0.479639  0.520361       0  ...  0.951721  -1.0    0.0  1.033721

[5 rows x 10 columns]
2023-10-03 16:00:18,507:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484820  0.515180       0  ...  0.932895  -1.0    0.0  1.036732
46     1  0.488170  0.511830       1  ...  0.949797  -1.0    0.0  1.038206
47     0  0.505137  0.494863       1  ...  0.948492  -1.0    0.0  1.040259
48     0  0.510848  0.489152       0  ...  0.950332  -1.0    0.0  1.039439
49     1  0.479639  0.520361       0  ...  0.951721  -1.0    0.0  1.033721

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.906', 'enterprice': '28298.9', 'countrevence': '0', 'unrealprofit': '18364.5892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27530.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [03/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20471 

self.closeSec=1696318199, self.tradeDate='20231003', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27572.5', self.close='27568.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20472 

self.closeSec=1696318799, self.tradeDate='20231003', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27568.2', self.close='27552.7'
127.0.0.1 - - [03/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20473 

self.closeSec=1696319399, self.tradeDate='20231003', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27552.7', self.close='27557.9'
127.0.0.1 - - [03/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20474 

self.closeSec=1696319999, self.tradeDate='20231003', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27557.8', self.close='27528'
127.0.0.1 - - [03/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20475 

self.closeSec=1696320599, self.tradeDate='20231003', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27528', self.close='27578.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20476 

self.closeSec=1696321199, self.tradeDate='20231003', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27578.5', self.close='27600.9'
127.0.0.1 - - [03/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20474 

self.closeSec=1696318199, self.tradeDate='20231003', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27572.5', self.close='27568.3'
127.0.0.1 - - [03/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20475 

self.closeSec=1696318799, self.tradeDate='20231003', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27568.2', self.close='27552.7'
127.0.0.1 - - [03/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20476 

self.closeSec=1696319399, self.tradeDate='20231003', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27552.7', self.close='27557.9'

--handleKline--: 127.0.0.1 - - [03/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20477 

self.closeSec=1696319999, self.tradeDate='20231003', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27557.8', self.close='27528'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20478 

self.closeSec=1696320599, self.tradeDate='20231003', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27528', self.close='27578.5'
127.0.0.1 - - [03/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20479 

self.closeSec=1696321199, self.tradeDate='20231003', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27578.5', self.close='27600.9'
127.0.0.1 - - [03/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [03/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20474 

self.closeSec=1696318199, self.tradeDate='20231003', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27572.5', self.close='27568.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20475 

self.closeSec=1696318799, self.tradeDate='20231003', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27568.2', self.close='27552.7'
127.0.0.1 - - [03/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20476 

self.closeSec=1696319399, self.tradeDate='20231003', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27552.7', self.close='27557.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20477 

self.closeSec=1696319999, self.tradeDate='20231003', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27557.8', self.close='27528'
127.0.0.1 - - [03/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20478 

self.closeSec=1696320599, self.tradeDate='20231003', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27528', self.close='27578.5'
127.0.0.1 - - [03/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20479 

self.closeSec=1696321199, self.tradeDate='20231003', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27578.5', self.close='27600.9'
127.0.0.1 - - [03/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40948
self.closeSec=1696321199, self.tradeDate='20231003', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27579.0, self.close=27600.9, self.high=27604.0, self.low=27578.9, self.vol=556.427, self.amt=15351883.9924 
127.0.0.1 - - [03/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-03 16:20:05,644:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231003   155500    155959  ...         0.0        0.0       0
5952  20231003   160000    160459  ...         0.0        0.0       0
5953  20231003   160500    160959  ...         0.0        0.0       0
5954  20231003   161000    161459  ...         0.0        0.0       0
5955  20231003   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 16:20:05,653:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696321199, self.tradeDate='20231003', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27579.0, self.close=27600.9, self.high=27604.0, self.low=27578.9, self.vol=556.427, self.amt=15351883.9924, ukdf['pct'].iloc[-1]=0.000798 , ukdf['amount'].iloc[-1]=15351883.9924, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '28134.72362479272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27601.51120392', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40949
self.closeSec=1696321499, self.tradeDate='20231003', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27600.8, self.close=27612.1, self.high=27618.1, self.low=27599.0, self.vol=665.649, self.amt=18378303.542 
2023-10-03 16:25:00,793:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231003   160000    160459  ...         0.0        0.0       0
5953  20231003   160500    160959  ...         0.0        0.0       0
5954  20231003   161000    161459  ...         0.0        0.0       0
5955  20231003   161500    161959  ...         0.0        0.0       0
5956  20231003   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 16:25:00,793:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696321499, self.tradeDate='20231003', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27600.8, self.close=27612.1, self.high=27618.1, self.low=27599.0, self.vol=665.649, self.amt=18378303.542, ukdf['pct'].iloc[-1]=0.000406 , ukdf['amount'].iloc[-1]=18378303.542, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '28533.01671774229', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27612.23501569', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231003   040000    075959  1696291199  ...    721  1.177827  1.194833     1.0
722  20231003   080000    115959  1696305599  ...    722  1.166157  1.143800     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-18716.30705635964', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27587.52261373', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [03/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1223948.6721539998, self.flagDict['side']='buy', self.tradeCount=29, self.count=853
self.closeSec=1696319999, self.tradeDate='20231003', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27585.8, self.close=27528.0, self.high=27665.0, self.low=27510.1, self.vol=24064.809, self.amt=663830965.7391 
2023-10-03 16:00:01,536:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696319999, self.tradeDate='20231003', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27585.8, self.close=27528.0, self.high=27665.0, self.low=27510.1, self.vol=24064.809, self.amt=663830965.7391 
2023-10-03 16:00:01,549:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231002   200000    235959  ...  142170.052  4.021523e+09 -0.005503
720  20231003   000000    035959  ...  130185.968  3.631271e+09 -0.002594
721  20231003   040000    075959  ...   88961.527  2.450607e+09 -0.016941
722  20231003   080000    115959  ...   39247.062  1.079420e+09  0.003788
723  20231003   120000    155959  ...   24064.809  6.638310e+08 -0.002095

[5 rows x 11 columns]
2023-10-03 16:00:02,235:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231002   200000    235959  1696262399  ...    719  0.947660  0.684216     1.0
720  20231003   000000    035959  1696276799  ...    720  1.130921  1.105921     1.0
721  20231003   040000    075959  1696291199  ...    721  1.177827  1.194833     1.0
722  20231003   080000    115959  1696305599  ...    722  1.166157  1.143800     1.0
723  20231003   120000    155959  1696319999  ...    723  1.122867  1.016519     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-21319.35', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27528', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


