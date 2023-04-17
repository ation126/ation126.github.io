# 20230417 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40629
self.closeSec=1681719599, self.tradeDate='20230417', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29824.0, self.close=29892.0, self.high=29894.5, self.low=29823.9, self.vol=2154.871, self.amt=64346433.8708 
127.0.0.1 - - [17/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-17 16:20:07,510:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230417   155500    155959  ...         0.0        0.0       0
5945  20230417   160000    160459  ...         0.0        0.0       0
5946  20230417   160500    160959  ...         0.0        0.0       0
5947  20230417   161000    161459  ...         0.0        0.0       0
5948  20230417   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 16:20:07,521:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681719599, self.tradeDate='20230417', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29824.0, self.close=29892.0, self.high=29894.5, self.low=29823.9, self.vol=2154.871, self.amt=64346433.8708, ukdf['pct'].iloc[-1]=0.00228 , ukdf['amount'].iloc[-1]=64346433.8708, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-804019.80299933984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29890.43738034', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40630
self.closeSec=1681719899, self.tradeDate='20230417', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29892.1, self.close=29861.1, self.high=29892.5, self.low=29859.9, self.vol=1072.654, self.amt=32046897.3864 
127.0.0.1 - - [17/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-17 16:25:01,635:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230417   160000    160459  ...         0.0        0.0       0
5946  20230417   160500    160959  ...         0.0        0.0       0
5947  20230417   161000    161459  ...         0.0        0.0       0
5948  20230417   161500    161959  ...         0.0        0.0       0
5949  20230417   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 16:25:01,636:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681719899, self.tradeDate='20230417', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29892.1, self.close=29861.1, self.high=29892.5, self.low=29859.9, self.vol=1072.654, self.amt=32046897.3864, ukdf['pct'].iloc[-1]=-0.001034 , ukdf['amount'].iloc[-1]=32046897.3864, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-802289.24178982528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29861.67905128', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [17/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41191 

self.closeSec=1681718399, self.tradeDate='20230417', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29848.8, self.close=29831.1, self.high=29858.2, self.low=29822.0 
127.0.0.1 - - [17/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41192 

self.closeSec=1681718699, self.tradeDate='20230417', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29831.2, self.close=29850.0, self.high=29850.0, self.low=29812.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41193 

self.closeSec=1681718999, self.tradeDate='20230417', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29850.0, self.close=29827.9, self.high=29850.0, self.low=29781.6 
127.0.0.1 - - [17/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41194 

self.closeSec=1681719299, self.tradeDate='20230417', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29827.8, self.close=29824.0, self.high=29829.8, self.low=29811.1 
127.0.0.1 - - [17/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41195 

self.closeSec=1681719599, self.tradeDate='20230417', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29824.0, self.close=29892.0, self.high=29894.5, self.low=29823.9 
127.0.0.1 - - [17/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41196 

self.closeSec=1681719899, self.tradeDate='20230417', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29892.1, self.close=29861.1, self.high=29892.5, self.low=29859.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-17 16:00:35,440:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230417    132959  29968.6  ...  53.333333  0.427700  0.609203
5786  20230417    135959  29948.1  ...  53.750000  0.437495  0.613985
5787  20230417    142959  29983.9  ...  53.750000  0.428674  0.621782
5788  20230417    145959  29941.6  ...  53.333333  0.418160  0.633133
5789  20230417    152959  29890.1  ...  53.333333  0.419761  0.643279

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-04-17 16:00:35,608:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510594  0.489406       1  ...  1.023176  -1.0    0.0  1.066940
538     0  0.526042  0.473958       0  ...  1.024619  -1.0    0.0  1.065435
539     0  0.508288  0.491712       0  ...  1.026388  -1.0    0.0  1.063595
540     0  0.505511  0.494489       1  ...  1.026193  -1.0    0.0  1.063798
541     0  0.514560  0.485440       0  ...  1.028410  -1.0    0.0  1.061499

[5 rows x 10 columns]
2023-04-17 16:00:35,641:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511141  0.488859       1  ...  1.023176  -1.0    0.0  1.066124
46     0  0.526095  0.473905       0  ...  1.024619  -1.0    0.0  1.063263
47     0  0.507299  0.492701       0  ...  1.026388  -1.0    0.0  1.061431
48     0  0.505027  0.494973       1  ...  1.026193  -1.0    0.0  1.061863
49     0  0.514560  0.485440       0  ...  1.028410  -1.0    0.0  1.061499

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [17/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20593 

self.closeSec=1681716599, self.tradeDate='20230417', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29919.5', self.close='29895.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20594 

self.closeSec=1681717199, self.tradeDate='20230417', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29895.8', self.close='29900.1'
127.0.0.1 - - [17/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20595 

self.closeSec=1681717799, self.tradeDate='20230417', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29900', self.close='29873.5'
127.0.0.1 - - [17/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20596 

self.closeSec=1681718399, self.tradeDate='20230417', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29873.6', self.close='29831.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20597 

self.closeSec=1681718999, self.tradeDate='20230417', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29831.2', self.close='29827.9'
127.0.0.1 - - [17/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20598 

self.closeSec=1681719599, self.tradeDate='20230417', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29827.8', self.close='29892'
127.0.0.1 - - [17/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20594 

self.closeSec=1681716599, self.tradeDate='20230417', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29919.5', self.close='29895.7'
127.0.0.1 - - [17/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20595 

self.closeSec=1681717199, self.tradeDate='20230417', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29895.8', self.close='29900.1'
127.0.0.1 - - [17/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20596 

self.closeSec=1681717799, self.tradeDate='20230417', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29900', self.close='29873.5'
127.0.0.1 - - [17/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20597 

self.closeSec=1681718399, self.tradeDate='20230417', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29873.6', self.close='29831.1'
127.0.0.1 - - [17/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20598 

self.closeSec=1681718999, self.tradeDate='20230417', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29831.2', self.close='29827.9'
127.0.0.1 - - [17/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20599 

self.closeSec=1681719599, self.tradeDate='20230417', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29827.8', self.close='29892'
127.0.0.1 - - [17/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20594 

self.closeSec=1681716599, self.tradeDate='20230417', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29919.5', self.close='29895.7'
127.0.0.1 - - [17/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20595 

self.closeSec=1681717199, self.tradeDate='20230417', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29895.8', self.close='29900.1'
127.0.0.1 - - [17/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20596 

self.closeSec=1681717799, self.tradeDate='20230417', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29900', self.close='29873.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20597 

self.closeSec=1681718399, self.tradeDate='20230417', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29873.6', self.close='29831.1'
127.0.0.1 - - [17/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20598 

self.closeSec=1681718999, self.tradeDate='20230417', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29831.2', self.close='29827.9'
127.0.0.1 - - [17/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20599 

self.closeSec=1681719599, self.tradeDate='20230417', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29827.8', self.close='29892'
127.0.0.1 - - [17/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36627
self.closeSec=1681719599, self.tradeDate='20230417', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29824.0, self.close=29892.0, self.high=29894.5, self.low=29823.9, self.vol=2154.871, self.amt=64346433.8708 
127.0.0.1 - - [17/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-17 16:20:07,235:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230417   155500    155959  ...         0.0        0.0       0
5945  20230417   160000    160459  ...         0.0        0.0       0
5946  20230417   160500    160959  ...         0.0        0.0       0
5947  20230417   161000    161459  ...         0.0        0.0       0
5948  20230417   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 16:20:07,240:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681719599, self.tradeDate='20230417', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29824.0, self.close=29892.0, self.high=29894.5, self.low=29823.9, self.vol=2154.871, self.amt=64346433.8708, ukdf['pct'].iloc[-1]=0.00228 , ukdf['amount'].iloc[-1]=64346433.8708, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [17/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36628
self.closeSec=1681719899, self.tradeDate='20230417', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29892.1, self.close=29861.1, self.high=29892.5, self.low=29859.9, self.vol=1072.654, self.amt=32046897.3864 
2023-04-17 16:25:01,621:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230417   160000    160459  ...         0.0        0.0       0
5946  20230417   160500    160959  ...         0.0        0.0       0
5947  20230417   161000    161459  ...         0.0        0.0       0
5948  20230417   161500    161959  ...         0.0        0.0       0
5949  20230417   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 16:25:01,622:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681719899, self.tradeDate='20230417', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29892.1, self.close=29861.1, self.high=29892.5, self.low=29859.9, self.vol=1072.654, self.amt=32046897.3864, ukdf['pct'].iloc[-1]=-0.001034 , ukdf['amount'].iloc[-1]=32046897.3864, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230417   040000    075959  1681689599  ...    721  0.410187 -0.127665     NaN
722  20230417   080000    115959  1681703999  ...    722  0.218240 -0.543022     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '89091.6975', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29966.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=858
self.closeSec=1681718399, self.tradeDate='20230417', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29966.5, self.close=29831.1, self.high=29994.6, self.low=29822.0, self.vol=33276.831, self.amt=995610109.8246 
127.0.0.1 - - [17/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-04-17 16:00:01,796:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681718399, self.tradeDate='20230417', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29966.5, self.close=29831.1, self.high=29994.6, self.low=29822.0, self.vol=33276.831, self.amt=995610109.8246 
2023-04-17 16:00:01,861:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230416   200000    235959  ...   40127.599  1.214260e+09  0.003458
720  20230417   000000    035959  ...   57612.650  1.751918e+09 -0.000613
721  20230417   040000    075959  ...   41632.548  1.261525e+09 -0.000640
722  20230417   080000    115959  ...  111581.657  3.342124e+09 -0.010569
723  20230417   120000    155959  ...   33276.831  9.956101e+08 -0.004518

[5 rows x 11 columns]
2023-04-17 16:00:04,150:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230416   200000    235959  1681660799  ...    719  0.214799 -0.550551     NaN
720  20230417   000000    035959  1681675199  ...    720  0.438516 -0.065699     NaN
721  20230417   040000    075959  1681689599  ...    721  0.410187 -0.127665     NaN
722  20230417   080000    115959  1681703999  ...    722  0.218240 -0.543022     NaN
723  20230417   120000    155959  1681718399  ...    723  0.309766 -0.351132     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '81996.921', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29831.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


