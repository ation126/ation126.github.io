# 20231016 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44692
self.closeSec=1697444399, self.tradeDate='20231016', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27850.1, self.close=27843.1, self.high=27865.8, self.low=27837.0, self.vol=1131.697, self.amt=31516661.7508 
127.0.0.1 - - [16/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-16 16:20:08,579:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231016   155500    155959  ...         0.0        0.0       0
5952  20231016   160000    160459  ...         0.0        0.0       0
5953  20231016   160500    160959  ...         0.0        0.0       0
5954  20231016   161000    161459  ...         0.0        0.0       0
5955  20231016   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 16:20:08,584:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697444399, self.tradeDate='20231016', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27850.1, self.close=27843.1, self.high=27865.8, self.low=27837.0, self.vol=1131.697, self.amt=31516661.7508, ukdf['pct'].iloc[-1]=-0.000262 , ukdf['amount'].iloc[-1]=31516661.7508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13578.8859293769', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27839.97438815', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44693
self.closeSec=1697444699, self.tradeDate='20231016', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27841.8, self.close=27836.4, self.high=27841.9, self.low=27801.6, self.vol=1259.33, self.amt=35037839.9571 
127.0.0.1 - - [16/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-16 16:25:03,062:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231016   160000    160459  ...         0.0        0.0       0
5953  20231016   160500    160959  ...         0.0        0.0       0
5954  20231016   161000    161459  ...         0.0        0.0       0
5955  20231016   161500    161959  ...         0.0        0.0       0
5956  20231016   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 16:25:03,071:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697444699, self.tradeDate='20231016', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27841.8, self.close=27836.4, self.high=27841.9, self.low=27801.6, self.vol=1259.33, self.amt=35037839.9571, ukdf['pct'].iloc[-1]=-0.000241 , ukdf['amount'].iloc[-1]=35037839.9571, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13511.63804228172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27835.14544322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44690 

self.closeSec=1697443199, self.tradeDate='20231016', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27835.9, self.close=27831.9, self.high=27840.0, self.low=27822.9 
127.0.0.1 - - [16/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44691 

self.closeSec=1697443499, self.tradeDate='20231016', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27837.2, self.close=27890.0, self.high=27890.0, self.low=27837.1 
127.0.0.1 - - [16/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44692 

self.closeSec=1697443799, self.tradeDate='20231016', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27888.8, self.close=27881.0, self.high=27890.2, self.low=27879.2 
127.0.0.1 - - [16/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44693 

self.closeSec=1697444099, self.tradeDate='20231016', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27880.3, self.close=27850.4, self.high=27881.2, self.low=27850.3 
127.0.0.1 - - [16/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44694 

self.closeSec=1697444399, self.tradeDate='20231016', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27850.1, self.close=27843.1, self.high=27865.8, self.low=27837.0 
127.0.0.1 - - [16/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44695 

self.closeSec=1697444699, self.tradeDate='20231016', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27841.8, self.close=27836.4, self.high=27841.9, self.low=27801.6 
127.0.0.1 - - [16/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-16 16:00:20,006:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231016    132959  27238.5  ...  52.083333  0.689092  0.374519
5786  20231016    135959  27757.8  ...  52.083333  0.710341  0.362210
5787  20231016    142959  27903.4  ...  52.083333  0.681422  0.355128
5788  20231016    145959  27814.3  ...  52.083333  0.676547  0.349283
5789  20231016    152959  27799.9  ...  52.500000  0.688034  0.339972

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-10-16 16:00:20,102:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.692279  0.307721       1  ...  0.946584   1.0    0.0  1.004069
538     0  0.602459  0.397541       0  ...  0.943494   1.0    0.0  1.000792
539     0  0.523705  0.476295       0  ...  0.942958   1.0    0.0  1.000223
540     0  0.544231  0.455769       1  ...  0.945662   1.0    0.0  1.003091
541     0  0.574505  0.425495       0  ...  0.944220   1.0    0.0  1.001561

[5 rows x 10 columns]
2023-10-16 16:00:20,123:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.692283  0.307717       1  ...  0.946584   1.0    0.0  1.005995
46     0  0.601889  0.398111       0  ...  0.943494   1.0    0.0  1.001534
47     0  0.524026  0.475974       0  ...  0.942958   1.0    0.0  1.001452
48     0  0.544637  0.455363       1  ...  0.945662   1.0    0.0  1.005398
49     0  0.574505  0.425495       0  ...  0.944220   1.0    0.0  1.001561

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.627', 'enterprice': '27009.6', 'countrevence': '0', 'unrealprofit': '19737.9958', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27845', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22343 

self.closeSec=1697441399, self.tradeDate='20231016', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27863', self.close='27879.7'
127.0.0.1 - - [16/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22344 

self.closeSec=1697441999, self.tradeDate='20231016', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27879.7', self.close='27889.1'
127.0.0.1 - - [16/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22345 

self.closeSec=1697442599, self.tradeDate='20231016', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27889.1', self.close='27837.9'
127.0.0.1 - - [16/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22346 

self.closeSec=1697443199, self.tradeDate='20231016', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27837.9', self.close='27831.9'
127.0.0.1 - - [16/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22347 

self.closeSec=1697443799, self.tradeDate='20231016', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27837.2', self.close='27881'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22348 

self.closeSec=1697444399, self.tradeDate='20231016', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27880.3', self.close='27841.9'
127.0.0.1 - - [16/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [16/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22346 

self.closeSec=1697441399, self.tradeDate='20231016', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27863', self.close='27879.7'
127.0.0.1 - - [16/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22347 

self.closeSec=1697441999, self.tradeDate='20231016', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27879.7', self.close='27889.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22348 

self.closeSec=1697442599, self.tradeDate='20231016', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27889.1', self.close='27837.9'
127.0.0.1 - - [16/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22349 

self.closeSec=1697443199, self.tradeDate='20231016', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27837.9', self.close='27831.9'
127.0.0.1 - - [16/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22350 

self.closeSec=1697443799, self.tradeDate='20231016', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27837.2', self.close='27881'
127.0.0.1 - - [16/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22351 

self.closeSec=1697444399, self.tradeDate='20231016', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27880.3', self.close='27841.9'
127.0.0.1 - - [16/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22346 

self.closeSec=1697441399, self.tradeDate='20231016', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27863', self.close='27879.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22347 

self.closeSec=1697441999, self.tradeDate='20231016', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27879.7', self.close='27889.1'
127.0.0.1 - - [16/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22348 

self.closeSec=1697442599, self.tradeDate='20231016', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27889.1', self.close='27837.9'
127.0.0.1 - - [16/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22349 

self.closeSec=1697443199, self.tradeDate='20231016', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27837.9', self.close='27831.9'
127.0.0.1 - - [16/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22350 

self.closeSec=1697443799, self.tradeDate='20231016', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27837.2', self.close='27881'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22351 

self.closeSec=1697444399, self.tradeDate='20231016', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27880.3', self.close='27841.9'
127.0.0.1 - - [16/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44692
self.closeSec=1697444399, self.tradeDate='20231016', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27850.1, self.close=27843.1, self.high=27865.8, self.low=27837.0, self.vol=1131.697, self.amt=31516661.7508 
127.0.0.1 - - [16/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-16 16:20:08,578:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231016   155500    155959  ...         0.0        0.0       0
5952  20231016   160000    160459  ...         0.0        0.0       0
5953  20231016   160500    160959  ...         0.0        0.0       0
5954  20231016   161000    161459  ...         0.0        0.0       0
5955  20231016   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 16:20:08,583:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697444399, self.tradeDate='20231016', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27850.1, self.close=27843.1, self.high=27865.8, self.low=27837.0, self.vol=1131.697, self.amt=31516661.7508, ukdf['pct'].iloc[-1]=-0.000262 , ukdf['amount'].iloc[-1]=31516661.7508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '36991.48475027915', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27839.97438815', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44693
self.closeSec=1697444699, self.tradeDate='20231016', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27841.8, self.close=27836.4, self.high=27841.9, self.low=27801.6, self.vol=1259.33, self.amt=35037839.9571 
127.0.0.1 - - [16/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-16 16:25:03,062:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231016   160000    160459  ...         0.0        0.0       0
5953  20231016   160500    160959  ...         0.0        0.0       0
5954  20231016   161000    161459  ...         0.0        0.0       0
5955  20231016   161500    161959  ...         0.0        0.0       0
5956  20231016   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 16:25:03,070:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697444699, self.tradeDate='20231016', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27841.8, self.close=27836.4, self.high=27841.9, self.low=27801.6, self.vol=1259.33, self.amt=35037839.9571, ukdf['pct'].iloc[-1]=-0.000241 , ukdf['amount'].iloc[-1]=35037839.9571, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '36811.25948105034', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27835.12192674', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

720  20231016   000000    035959  ...   33515.848  9.044073e+08  0.005371
721  20231016   040000    075959  ...   74881.965  2.033626e+09  0.004058
722  20231016   080000    115959  ...   30332.416  8.246226e+08  0.003007
723  20231016   120000    155959  ...  135348.480  3.756989e+09  0.022427

[5 rows x 11 columns]
2023-10-16 16:00:02,395:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231015   200000    235959  1697385599  ...    719  0.008915 -1.541141    -1.0
720  20231016   000000    035959  1697399999  ...    720  0.062670 -1.360868    -1.0
721  20231016   040000    075959  1697414399  ...    721  0.326582 -0.618872    -1.0
722  20231016   080000    115959  1697428799  ...    722  0.472551 -0.214699     NaN
723  20231016   120000    155959  1697443199  ...    723  1.659620  2.908893     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.1', 'enterprice': '26874.8', 'countrevence': '0', 'unrealprofit': '-45324.33', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27837.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.1', 'enterprice': '26874.8', 'countrevence': '0', 'unrealprofit': '-45324.33', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27837.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-16 16:00:09,353:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1222891.2812779', 'total': '1222891.2812779', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-16 16:00:09,861:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-10-16 16:00:09,861:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 43.806, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '43010F1697443209860I0L65'}
2023-10-16 16:00:09,884:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:10161600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20231016, closeTime:155959, close:27831.9, sign:1, total:1222891.2812779, side:buy  
127.0.0.1 - - [16/Oct/2023 16:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Oct/2023 16:00:09] "POST / HTTP/1.1" 200 -
2023-10-16 16:00:09,887:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43009F1697443204282I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697443204678579, 'quantity': '47.1', 'price': '27837.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697443203230, 'updatetime': 1697443204678, 'tradetype': 'usdt', 'selfid': 43009, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697443204678, 'clientorderid': '43009F1697443204282I0L65', 'price': '27837.2', 'quantity': '47.1', 'commission': '1311.13212', 'commissionasset': 'USDT', 'tradetime': 1697443204678, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697443204678}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-16 16:00:09,888:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43009F1697443204282I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697443204678579, 'quantity': '47.1', 'price': '27837.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697443203230, 'updatetime': 1697443204678, 'tradetype': 'usdt', 'selfid': 43009, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697443204678, 'clientorderid': '43009F1697443204282I0L65', 'price': '27837.2', 'quantity': '47.1', 'commission': '1311.13212', 'commissionasset': 'USDT', 'tradetime': 1697443204678, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697443204678}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Oct/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-10-16 16:00:10,316:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43010F1697443209860I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697443210278052, 'quantity': '43.806', 'price': '27840.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697443209366, 'updatetime': 1697443210278, 'tradetype': 'usdt', 'selfid': 43010, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697443210278, 'clientorderid': '43010F1697443209860I0L65', 'price': '27840.9', 'quantity': '43.806', 'commission': '1219.5984654', 'commissionasset': 'USDT', 'tradetime': 1697443210278, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697443210278}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-16 16:00:10,468:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43010F1697443209860I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697443210278052, 'quantity': '43.806', 'price': '27840.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697443209366, 'updatetime': 1697443210278, 'tradetype': 'usdt', 'selfid': 43010, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697443210278, 'clientorderid': '43010F1697443209860I0L65', 'price': '27840.9', 'quantity': '43.806', 'commission': '1219.5984654', 'commissionasset': 'USDT', 'tradetime': 1697443210278, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697443210278}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Oct/2023 16:00:10] "POST / HTTP/1.1" 200 -


