# 20230921 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37492
self.closeSec=1695284399, self.tradeDate='20230921', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27006.0, self.close=26985.1, self.high=27006.0, self.low=26980.2, self.vol=407.264, self.amt=10993183.5264 
127.0.0.1 - - [21/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-21 16:20:06,363:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230921   155500    155959  ...         0.0        0.0       0
5952  20230921   160000    160459  ...         0.0        0.0       0
5953  20230921   160500    160959  ...         0.0        0.0       0
5954  20230921   161000    161459  ...         0.0        0.0       0
5955  20230921   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 16:20:06,372:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695284399, self.tradeDate='20230921', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27006.0, self.close=26985.1, self.high=27006.0, self.low=26980.2, self.vol=407.264, self.amt=10993183.5264, ukdf['pct'].iloc[-1]=-0.000774 , ukdf['amount'].iloc[-1]=10993183.5264, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-1672.5126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26985', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37493
self.closeSec=1695284699, self.tradeDate='20230921', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26985.0, self.close=26958.6, self.high=26987.9, self.low=26958.5, self.vol=514.547, self.amt=13876144.5282 
2023-09-21 16:25:00,770:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230921   160000    160459  ...         0.0        0.0       0
5953  20230921   160500    160959  ...         0.0        0.0       0
5954  20230921   161000    161459  ...         0.0        0.0       0
5955  20230921   161500    161959  ...         0.0        0.0       0
5956  20230921   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 16:25:00,770:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695284699, self.tradeDate='20230921', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26985.0, self.close=26958.6, self.high=26987.9, self.low=26958.5, self.vol=514.547, self.amt=13876144.5282, ukdf['pct'].iloc[-1]=-0.000982 , ukdf['amount'].iloc[-1]=13876144.5282, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-1340.88276814536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26961.18628236', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [21/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37490 

self.closeSec=1695283199, self.tradeDate='20230921', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26976.6, self.close=26978.4, self.high=26983.4, self.low=26969.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37491 

self.closeSec=1695283499, self.tradeDate='20230921', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26978.4, self.close=26972.0, self.high=26978.4, self.low=26960.6 
127.0.0.1 - - [21/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37492 

self.closeSec=1695283799, self.tradeDate='20230921', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26972.0, self.close=26963.7, self.high=26976.0, self.low=26958.4 
127.0.0.1 - - [21/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37493 

self.closeSec=1695284099, self.tradeDate='20230921', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26963.7, self.close=27006.0, self.high=27008.0, self.low=26963.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37494 

self.closeSec=1695284399, self.tradeDate='20230921', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27006.0, self.close=26985.1, self.high=27006.0, self.low=26980.2 
127.0.0.1 - - [21/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37495 

self.closeSec=1695284699, self.tradeDate='20230921', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26985.0, self.close=26958.6, self.high=26987.9, self.low=26958.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-21 16:00:19,315:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230921    132959  27078.6  ...  52.500000  0.498457  0.503598
5786  20230921    135959  27029.1  ...  52.916667  0.504760  0.498560
5787  20230921    142959  27059.1  ...  52.916667  0.492282  0.500945
5788  20230921    145959  26995.8  ...  52.916667  0.505061  0.495917
5789  20230921    152959  27060.6  ...  52.500000  0.496263  0.496231

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2023-09-21 16:00:19,380:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.484372  0.515628       1  ...  0.884629  -1.0    0.0  1.046276
538     0  0.504705  0.495295       0  ...  0.886568  -1.0    0.0  1.043983
539     1  0.476889  0.523111       1  ...  0.884575  -1.0    0.0  1.046330
540     0  0.512161  0.487839       0  ...  0.885944  -1.0    0.0  1.044710
541     1  0.480233  0.519767       0  ...  0.887263  -1.0    0.0  1.043155

[5 rows x 10 columns]
2023-09-21 16:00:19,394:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484401  0.515599       1  ...  0.884629  -1.0    0.0  1.044789
46     0  0.504782  0.495218       0  ...  0.886568  -1.0    0.0  1.042995
47     1  0.476918  0.523082       1  ...  0.884575  -1.0    0.0  1.045102
48     0  0.512248  0.487752       0  ...  0.885944  -1.0    0.0  1.044815
49     1  0.480233  0.519767       0  ...  0.887263  -1.0    0.0  1.043155

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '4022.489', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26974.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18743 

self.closeSec=1695281399, self.tradeDate='20230921', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27012.1', self.close='27018.6'
127.0.0.1 - - [21/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18744 

self.closeSec=1695281999, self.tradeDate='20230921', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27018.6', self.close='27002.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18745 

self.closeSec=1695282599, self.tradeDate='20230921', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27002.4', self.close='26983.6'
127.0.0.1 - - [21/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18746 

self.closeSec=1695283199, self.tradeDate='20230921', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26983.5', self.close='26978.4'
127.0.0.1 - - [21/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18747 

self.closeSec=1695283799, self.tradeDate='20230921', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26978.4', self.close='26963.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18748 

self.closeSec=1695284399, self.tradeDate='20230921', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26963.7', self.close='26985.1'
127.0.0.1 - - [21/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [21/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18746 

self.closeSec=1695281399, self.tradeDate='20230921', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27012.1', self.close='27018.6'
127.0.0.1 - - [21/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18747 

self.closeSec=1695281999, self.tradeDate='20230921', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27018.6', self.close='27002.3'
127.0.0.1 - - [21/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18748 

self.closeSec=1695282599, self.tradeDate='20230921', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27002.4', self.close='26983.6'
127.0.0.1 - - [21/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18749 

self.closeSec=1695283199, self.tradeDate='20230921', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26983.5', self.close='26978.4'
127.0.0.1 - - [21/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18750 

self.closeSec=1695283799, self.tradeDate='20230921', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26978.4', self.close='26963.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18751 

self.closeSec=1695284399, self.tradeDate='20230921', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26963.7', self.close='26985.1'
127.0.0.1 - - [21/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [21/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18746 

self.closeSec=1695281399, self.tradeDate='20230921', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27012.1', self.close='27018.6'
127.0.0.1 - - [21/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18747 

self.closeSec=1695281999, self.tradeDate='20230921', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27018.6', self.close='27002.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18748 

self.closeSec=1695282599, self.tradeDate='20230921', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27002.4', self.close='26983.6'
127.0.0.1 - - [21/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18749 

self.closeSec=1695283199, self.tradeDate='20230921', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26983.5', self.close='26978.4'
127.0.0.1 - - [21/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18750 

self.closeSec=1695283799, self.tradeDate='20230921', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26978.4', self.close='26963.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18751 

self.closeSec=1695284399, self.tradeDate='20230921', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26963.7', self.close='26985.1'
127.0.0.1 - - [21/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37492
self.closeSec=1695284399, self.tradeDate='20230921', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27006.0, self.close=26985.1, self.high=27006.0, self.low=26980.2, self.vol=407.264, self.amt=10993183.5264 
127.0.0.1 - - [21/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-21 16:20:06,357:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230921   155500    155959  ...         0.0        0.0       0
5952  20230921   160000    160459  ...         0.0        0.0       0
5953  20230921   160500    160959  ...         0.0        0.0       0
5954  20230921   161000    161459  ...         0.0        0.0       0
5955  20230921   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 16:20:06,364:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695284399, self.tradeDate='20230921', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27006.0, self.close=26985.1, self.high=27006.0, self.low=26980.2, self.vol=407.264, self.amt=10993183.5264, ukdf['pct'].iloc[-1]=-0.000774 , ukdf['amount'].iloc[-1]=10993183.5264, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '5236.881', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26985', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [21/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37493
self.closeSec=1695284699, self.tradeDate='20230921', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26985.0, self.close=26958.6, self.high=26987.9, self.low=26958.5, self.vol=514.547, self.amt=13876144.5282 
2023-09-21 16:25:00,776:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230921   160000    160459  ...         0.0        0.0       0
5953  20230921   160500    160959  ...         0.0        0.0       0
5954  20230921   161000    161459  ...         0.0        0.0       0
5955  20230921   161500    161959  ...         0.0        0.0       0
5956  20230921   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 16:25:00,776:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695284699, self.tradeDate='20230921', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26985.0, self.close=26958.6, self.high=26987.9, self.low=26958.5, self.vol=514.547, self.amt=13876144.5282, ukdf['pct'].iloc[-1]=-0.000982 , ukdf['amount'].iloc[-1]=13876144.5282, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '4352.41571313276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26961.18628236', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230921   040000    075959  1695254399  ...    721  1.168680  2.155180     1.0
722  20230921   080000    115959  1695268799  ...    722  1.072655  1.830405     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-11249.3205', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27029.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [21/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=781
self.closeSec=1695283199, self.tradeDate='20230921', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27026.9, self.close=26978.4, self.high=27092.4, self.low=26966.1, self.vol=23776.748, self.amt=642649551.1925 
2023-09-21 16:00:01,542:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695283199, self.tradeDate='20230921', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27026.9, self.close=26978.4, self.high=27092.4, self.low=26966.1, self.vol=23776.748, self.amt=642649551.1925 
2023-09-21 16:00:01,556:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230920   200000    235959  ...   57520.038  1.559204e+09  0.002991
720  20230921   000000    035959  ...  107623.432  2.913957e+09 -0.009272
721  20230921   040000    075959  ...   45455.539  1.231102e+09  0.007175
722  20230921   080000    115959  ...   30051.717  8.117329e+08 -0.002977
723  20230921   120000    155959  ...   23776.748  6.426496e+08 -0.001798

[5 rows x 11 columns]
2023-09-21 16:00:02,224:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230920   200000    235959  1695225599  ...    719  1.263330  2.615045     1.0
720  20230921   000000    035959  1695239999  ...    720  1.206814  2.349063     1.0
721  20230921   040000    075959  1695254399  ...    721  1.168680  2.155180     1.0
722  20230921   080000    115959  1695268799  ...    722  1.072655  1.830405     1.0
723  20230921   120000    155959  1695283199  ...    723  0.918522  1.378474     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-13847.38734104253', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26978.74386081', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


