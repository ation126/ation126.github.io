# 20231009 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42676
self.closeSec=1696839599, self.tradeDate='20231009', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27822.2, self.close=27806.2, self.high=27822.2, self.low=27802.6, self.vol=303.318, self.amt=8435735.2528 
127.0.0.1 - - [09/Oct/2023 16:20:10] "POST / HTTP/1.1" 200 -
2023-10-09 16:20:16,453:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231009   155500    155959  ...         0.0        0.0       0
5952  20231009   160000    160459  ...         0.0        0.0       0
5953  20231009   160500    160959  ...         0.0        0.0       0
5954  20231009   161000    161459  ...         0.0        0.0       0
5955  20231009   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 16:20:16,463:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696839599, self.tradeDate='20231009', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27822.2, self.close=27806.2, self.high=27822.2, self.low=27802.6, self.vol=303.318, self.amt=8435735.2528, ukdf['pct'].iloc[-1]=-0.000571 , ukdf['amount'].iloc[-1]=8435735.2528, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13116.65304237552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27806.78230952', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42677
self.closeSec=1696839899, self.tradeDate='20231009', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27806.2, self.close=27811.2, self.high=27820.7, self.low=27803.2, self.vol=291.146, self.amt=8097426.077 
2023-10-09 16:25:00,821:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231009   160000    160459  ...         0.0        0.0       0
5953  20231009   160500    160959  ...         0.0        0.0       0
5954  20231009   161000    161459  ...         0.0        0.0       0
5955  20231009   161500    161959  ...         0.0        0.0       0
5956  20231009   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 16:25:00,821:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696839899, self.tradeDate='20231009', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27806.2, self.close=27811.2, self.high=27820.7, self.low=27803.2, self.vol=291.146, self.amt=8097426.077, ukdf['pct'].iloc[-1]=0.00018 , ukdf['amount'].iloc[-1]=8097426.077, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13225.63064482572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27814.60778722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [09/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42674 

self.closeSec=1696838399, self.tradeDate='20231009', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27810.8, self.close=27803.7, self.high=27815.1, self.low=27801.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42675 

self.closeSec=1696838699, self.tradeDate='20231009', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27804.6, self.close=27818.1, self.high=27820.0, self.low=27793.6 
127.0.0.1 - - [09/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42676 

self.closeSec=1696838999, self.tradeDate='20231009', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27818.2, self.close=27813.8, self.high=27819.1, self.low=27807.0 
127.0.0.1 - - [09/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42677 

self.closeSec=1696839299, self.tradeDate='20231009', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27815.5, self.close=27822.1, self.high=27822.1, self.low=27807.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42678 

self.closeSec=1696839599, self.tradeDate='20231009', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27822.2, self.close=27806.2, self.high=27822.2, self.low=27802.6 
127.0.0.1 - - [09/Oct/2023 16:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42679 

self.closeSec=1696839899, self.tradeDate='20231009', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27806.2, self.close=27811.2, self.high=27820.7, self.low=27803.2 
127.0.0.1 - - [09/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-09 16:00:19,040:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231009    132959  27916.6  ...  51.250000  0.499435  0.401060
5786  20231009    135959  27870.5  ...  50.833333  0.492872  0.403181
5787  20231009    142959  27851.7  ...  51.250000  0.501077  0.400288
5788  20231009    145959  27875.1  ...  51.250000  0.506635  0.394263
5789  20231009    152959  27890.9  ...  51.250000  0.485463  0.401395

[5 rows x 33 columns]
0.5535055350553506
acc is : 0.5535055350553506
2023-10-09 16:00:19,106:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.483493  0.516507       0  ...  0.986689   1.0    0.0  1.053823
538     1  0.489331  0.510669       1  ...  0.987515   1.0    0.0  1.054704
539     0  0.502547  0.497453       1  ...  0.988078   1.0    0.0  1.055306
540     0  0.501010  0.498990       0  ...  0.985917   1.0    0.0  1.052998
541     1  0.477240  0.522760       0  ...  0.984985   1.0    0.0  1.052003

[5 rows x 10 columns]
2023-10-09 16:00:19,118:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483363  0.516637       0  ...  0.996086   1.0    0.0  1.058107
46     1  0.489335  0.510665       1  ...  0.996919   1.0    0.0  1.059954
47     0  0.502378  0.497622       1  ...  0.997488   1.0    0.0  1.058092
48     0  0.500726  0.499274       0  ...  0.995306   1.0    0.0  1.049116
49     1  0.477240  0.522760       0  ...  0.984985   1.0    0.0  1.052003

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.669', 'enterprice': '27936.3', 'countrevence': '0', 'unrealprofit': '-3234.07569381346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27799.66238566', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [09/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21335 

self.closeSec=1696836599, self.tradeDate='20231009', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27854', self.close='27830'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21336 

self.closeSec=1696837199, self.tradeDate='20231009', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27830', self.close='27832.6'
127.0.0.1 - - [09/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21337 

self.closeSec=1696837799, self.tradeDate='20231009', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27832.6', self.close='27820.5'
127.0.0.1 - - [09/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21338 

self.closeSec=1696838399, self.tradeDate='20231009', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27819.4', self.close='27804.6'
127.0.0.1 - - [09/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21339 

self.closeSec=1696838999, self.tradeDate='20231009', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27804.6', self.close='27813.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21340 

self.closeSec=1696839599, self.tradeDate='20231009', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27815.5', self.close='27806.2'
127.0.0.1 - - [09/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [09/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21338 

self.closeSec=1696836599, self.tradeDate='20231009', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27854', self.close='27830'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21339 

self.closeSec=1696837199, self.tradeDate='20231009', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27830', self.close='27832.6'
127.0.0.1 - - [09/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [09/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21340 

self.closeSec=1696837799, self.tradeDate='20231009', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27832.6', self.close='27820.5'
127.0.0.1 - - [09/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21341 

self.closeSec=1696838399, self.tradeDate='20231009', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27819.4', self.close='27804.6'
127.0.0.1 - - [09/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21342 

self.closeSec=1696838999, self.tradeDate='20231009', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27804.6', self.close='27813.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21343 

self.closeSec=1696839599, self.tradeDate='20231009', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27815.5', self.close='27806.2'
127.0.0.1 - - [09/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [09/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21338 

self.closeSec=1696836599, self.tradeDate='20231009', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27854', self.close='27830'
127.0.0.1 - - [09/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21339 

self.closeSec=1696837199, self.tradeDate='20231009', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27830', self.close='27832.6'

--handleKline--: 127.0.0.1 - - [09/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21340 

self.closeSec=1696837799, self.tradeDate='20231009', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27832.6', self.close='27820.5'
127.0.0.1 - - [09/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21341 

self.closeSec=1696838399, self.tradeDate='20231009', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27819.4', self.close='27804.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21342 

self.closeSec=1696838999, self.tradeDate='20231009', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27804.6', self.close='27813.8'
127.0.0.1 - - [09/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21343 

self.closeSec=1696839599, self.tradeDate='20231009', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27815.5', self.close='27806.2'
127.0.0.1 - - [09/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42676
self.closeSec=1696839599, self.tradeDate='20231009', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27822.2, self.close=27806.2, self.high=27822.2, self.low=27802.6, self.vol=303.318, self.amt=8435735.2528 
127.0.0.1 - - [09/Oct/2023 16:20:10] "POST / HTTP/1.1" 200 -
2023-10-09 16:20:16,443:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231009   155500    155959  ...         0.0        0.0       0
5952  20231009   160000    160459  ...         0.0        0.0       0
5953  20231009   160500    160959  ...         0.0        0.0       0
5954  20231009   161000    161459  ...         0.0        0.0       0
5955  20231009   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 16:20:16,452:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696839599, self.tradeDate='20231009', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27822.2, self.close=27806.2, self.high=27822.2, self.low=27802.6, self.vol=303.318, self.amt=8435735.2528, ukdf['pct'].iloc[-1]=-0.000571 , ukdf['amount'].iloc[-1]=8435735.2528, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '35758.69775788232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27806.78230952', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42677
self.closeSec=1696839899, self.tradeDate='20231009', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27806.2, self.close=27811.2, self.high=27820.7, self.low=27803.2, self.vol=291.146, self.amt=8097426.077 
2023-10-09 16:25:00,825:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231009   160000    160459  ...         0.0        0.0       0
5953  20231009   160500    160959  ...         0.0        0.0       0
5954  20231009   161000    161459  ...         0.0        0.0       0
5955  20231009   161500    161959  ...         0.0        0.0       0
5956  20231009   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 16:25:00,825:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696839899, self.tradeDate='20231009', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27806.2, self.close=27811.2, self.high=27820.7, self.low=27803.2, self.vol=291.146, self.amt=8097426.077, ukdf['pct'].iloc[-1]=0.00018 , ukdf['amount'].iloc[-1]=8097426.077, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '36049.34382513802', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27814.60778722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231009   040000    075959  1696809599  ...    721  0.083383 -1.253474    -1.0
722  20231009   080000    115959  1696823999  ...    722  0.082445 -1.234409    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '1373.3055', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27912.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=889
self.closeSec=1696838399, self.tradeDate='20231009', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27911.9, self.close=27803.7, self.high=27934.0, self.low=27800.0, self.vol=18808.51, self.amt=524019899.6259 
127.0.0.1 - - [09/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-09 16:00:01,514:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696838399, self.tradeDate='20231009', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27911.9, self.close=27803.7, self.high=27934.0, self.low=27800.0, self.vol=18808.51, self.amt=524019899.6259 
2023-10-09 16:00:01,534:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231008   200000    235959  ...  50313.962  1.401446e+09  0.003040
720  20231009   000000    035959  ...  23249.821  6.478884e+08 -0.000115
721  20231009   040000    075959  ...  22355.647  6.234754e+08  0.000750
722  20231009   080000    115959  ...  26462.524  7.379817e+08  0.000380
723  20231009   120000    155959  ...  18808.510  5.240199e+08 -0.003876

[5 rows x 11 columns]
2023-10-09 16:00:02,243:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231008   200000    235959  1696780799  ...    719  0.100098 -1.254552    -1.0
720  20231009   000000    035959  1696795199  ...    720  0.078013 -1.290971    -1.0
721  20231009   040000    075959  1696809599  ...    721  0.083383 -1.253474    -1.0
722  20231009   080000    115959  1696823999  ...    722  0.082445 -1.234409    -1.0
723  20231009   120000    155959  1696838399  ...    723  0.080186 -1.217978    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '6094.8606', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27804.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


