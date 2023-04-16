# 20230417 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40437
self.closeSec=1681661999, self.tradeDate='20230417', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30302.7, self.close=30297.5, self.high=30304.4, self.low=30297.4, self.vol=293.024, self.amt=8878729.8964 
127.0.0.1 - - [17/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-17 00:20:07,407:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230416   235500    235959  ...         0.0        0.0       0
5753  20230417   000000    000459  ...         0.0        0.0       0
5754  20230417   000500    000959  ...         0.0        0.0       0
5755  20230417   001000    001459  ...         0.0        0.0       0
5756  20230417   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 00:20:07,417:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681661999, self.tradeDate='20230417', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30302.7, self.close=30297.5, self.high=30304.4, self.low=30297.4, self.vol=293.024, self.amt=8878729.8964, ukdf['pct'].iloc[-1]=-0.000172 , ukdf['amount'].iloc[-1]=8878729.8964, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-828402.10420786416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30295.62052991', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40438
self.closeSec=1681662299, self.tradeDate='20230417', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30297.4, self.close=30302.0, self.high=30304.6, self.low=30292.9, self.vol=346.494, self.amt=10498396.1568 
2023-04-17 00:25:01,599:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230417   000000    000459  ...         0.0        0.0       0
5754  20230417   000500    000959  ...         0.0        0.0       0
5755  20230417   001000    001459  ...         0.0        0.0       0
5756  20230417   001500    001959  ...         0.0        0.0       0
5757  20230417   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 00:25:01,599:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681662299, self.tradeDate='20230417', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30297.4, self.close=30302.0, self.high=30304.6, self.low=30292.9, self.vol=346.494, self.amt=10498396.1568, ukdf['pct'].iloc[-1]=0.000149 , ukdf['amount'].iloc[-1]=10498396.1568, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-828792.0128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30302.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1681661099, self.tradeDate='20230417', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=30324.7, self.close=30311.1, self.high=30327.4, self.low=30311.1 

--ukdf-hist--: overDate='20230412' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [17/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41001 

self.closeSec=1681661399, self.tradeDate='20230417', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=30311.1, self.close=30307.3, self.high=30313.7, self.low=30306.5 
127.0.0.1 - - [17/Apr/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41002 

self.closeSec=1681661699, self.tradeDate='20230417', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=30307.4, self.close=30302.7, self.high=30310.0, self.low=30300.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41003 

self.closeSec=1681661999, self.tradeDate='20230417', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30302.7, self.close=30297.5, self.high=30304.4, self.low=30297.4 
127.0.0.1 - - [17/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41004 

self.closeSec=1681662299, self.tradeDate='20230417', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30297.4, self.close=30302.0, self.high=30304.6, self.low=30292.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-17 00:00:36,358:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230416    212959  30250.1  ...  53.750000  0.471604  0.506328
5802  20230416    215959  30230.2  ...  53.750000  0.475428  0.507869
5803  20230416    222959  30241.0  ...  54.166667  0.484658  0.503395
5804  20230416    225959  30267.1  ...  54.583333  0.497335  0.490914
5805  20230416    232959  30304.0  ...  54.583333  0.506491  0.473127

[5 rows x 33 columns]
0.5386029411764706
acc is : 0.5386029411764706
2023-04-17 00:00:36,524:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.508549  0.491451       1  ...  1.039063  -1.0    0.0  1.061952
540     0  0.516870  0.483130       1  ...  1.038163  -1.0    0.0  1.062872
541     0  0.524045  0.475955       1  ...  1.036901  -1.0    0.0  1.064165
542     0  0.527078  0.472922       1  ...  1.035970  -1.0    0.0  1.065120
543     0  0.526028  0.473972       0  ...  1.036195  -1.0    0.0  1.064888

[5 rows x 10 columns]
2023-04-17 00:00:36,558:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507216  0.492784       1  ...  1.065128  -1.0    0.0  1.058425
46     0  0.516067  0.483933       1  ...  1.064205  -1.0    0.0  1.060366
47     0  0.523702  0.476298       1  ...  1.036901  -1.0    0.0  1.062553
48     0  0.526737  0.473263       1  ...  1.035970  -1.0    0.0  1.063506
49     0  0.526028  0.473972       0  ...  1.036195  -1.0    0.0  1.064888

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [16/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20497 

self.closeSec=1681658999, self.tradeDate='20230416', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30309.6', self.close='30331.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20498 

self.closeSec=1681659599, self.tradeDate='20230416', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30331.3', self.close='30339.8'
127.0.0.1 - - [16/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20499 

self.closeSec=1681660199, self.tradeDate='20230416', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30339.8', self.close='30332.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20500 

self.closeSec=1681660799, self.tradeDate='20230416', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30332.5', self.close='30324.6'
127.0.0.1 - - [17/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20501 

self.closeSec=1681661399, self.tradeDate='20230417', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30324.7', self.close='30307.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20502 

self.closeSec=1681661999, self.tradeDate='20230417', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30307.4', self.close='30297.5'
127.0.0.1 - - [17/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [16/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20498 

self.closeSec=1681658999, self.tradeDate='20230416', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30309.6', self.close='30331.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20499 

self.closeSec=1681659599, self.tradeDate='20230416', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30331.3', self.close='30339.8'
127.0.0.1 - - [16/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20500 

self.closeSec=1681660199, self.tradeDate='20230416', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30339.8', self.close='30332.6'
127.0.0.1 - - [16/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20501 

self.closeSec=1681660799, self.tradeDate='20230416', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30332.5', self.close='30324.6'
127.0.0.1 - - [17/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20502 

self.closeSec=1681661399, self.tradeDate='20230417', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30324.7', self.close='30307.3'
127.0.0.1 - - [17/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20503 

self.closeSec=1681661999, self.tradeDate='20230417', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30307.4', self.close='30297.5'
127.0.0.1 - - [17/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20498 

self.closeSec=1681658999, self.tradeDate='20230416', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30309.6', self.close='30331.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20499 

self.closeSec=1681659599, self.tradeDate='20230416', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30331.3', self.close='30339.8'
127.0.0.1 - - [16/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20500 

self.closeSec=1681660199, self.tradeDate='20230416', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30339.8', self.close='30332.6'
127.0.0.1 - - [16/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20501 

self.closeSec=1681660799, self.tradeDate='20230416', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30332.5', self.close='30324.6'
127.0.0.1 - - [17/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20502 

self.closeSec=1681661399, self.tradeDate='20230417', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30324.7', self.close='30307.3'
127.0.0.1 - - [17/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20503 

self.closeSec=1681661999, self.tradeDate='20230417', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30307.4', self.close='30297.5'
127.0.0.1 - - [17/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36435
self.closeSec=1681661999, self.tradeDate='20230417', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30302.7, self.close=30297.5, self.high=30304.4, self.low=30297.4, self.vol=293.024, self.amt=8878729.8964 
127.0.0.1 - - [17/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-17 00:20:07,181:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230416   235500    235959  ...         0.0        0.0       0
5753  20230417   000000    000459  ...         0.0        0.0       0
5754  20230417   000500    000959  ...         0.0        0.0       0
5755  20230417   001000    001459  ...         0.0        0.0       0
5756  20230417   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 00:20:07,197:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681661999, self.tradeDate='20230417', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30302.7, self.close=30297.5, self.high=30304.4, self.low=30297.4, self.vol=293.024, self.amt=8878729.8964, ukdf['pct'].iloc[-1]=-0.000172 , ukdf['amount'].iloc[-1]=8878729.8964, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [17/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36436
self.closeSec=1681662299, self.tradeDate='20230417', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30297.4, self.close=30302.0, self.high=30304.6, self.low=30292.9, self.vol=346.494, self.amt=10498396.1568 
2023-04-17 00:25:01,600:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230417   000000    000459  ...         0.0        0.0       0
5754  20230417   000500    000959  ...         0.0        0.0       0
5755  20230417   001000    001459  ...         0.0        0.0       0
5756  20230417   001500    001959  ...         0.0        0.0       0
5757  20230417   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 00:25:01,601:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681662299, self.tradeDate='20230417', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30297.4, self.close=30302.0, self.high=30304.6, self.low=30292.9, self.vol=346.494, self.amt=10498396.1568, ukdf['pct'].iloc[-1]=0.000149 , ukdf['amount'].iloc[-1]=10498396.1568, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230416   120000    155959  1681631999  ...    723  0.301863 -0.379727     NaN
724  20230416   160000    195959  1681646399  ...    724  0.253665 -0.475176     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '102133.86799458915', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30214.75133761', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=854
self.closeSec=1681660799, self.tradeDate='20230416', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30220.1, self.close=30324.6, self.high=30363.2, self.low=30142.5, self.vol=40127.599, self.amt=1214259913.17398 
127.0.0.1 - - [17/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-17 00:00:01,782:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681660799, self.tradeDate='20230416', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30220.1, self.close=30324.6, self.high=30363.2, self.low=30142.5, self.vol=40127.599, self.amt=1214259913.17398 
2023-04-17 00:00:01,814:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230416   040000    075959  ...  22141.798  6.708111e+08 -0.001270
722  20230416   080000    115959  ...  26508.945  8.011411e+08 -0.001037
723  20230416   120000    155959  ...  21303.215  6.457237e+08  0.002704
724  20230416   160000    195959  ...  23037.583  6.974998e+08 -0.003650
725  20230416   200000    235959  ...  40127.599  1.214260e+09  0.003458

[5 rows x 11 columns]
2023-04-17 00:00:04,015:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230416   040000    075959  1681603199  ...    721  0.295218 -0.415715     NaN
722  20230416   080000    115959  1681617599  ...    722  0.288443 -0.418886     NaN
723  20230416   120000    155959  1681631999  ...    723  0.301863 -0.379727     NaN
724  20230416   160000    195959  1681646399  ...    724  0.253665 -0.475176     NaN
725  20230416   200000    235959  1681660799  ...    725  0.214799 -0.550551     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '107902.5705', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30324.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


