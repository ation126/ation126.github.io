# 20230417 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40533
self.closeSec=1681690799, self.tradeDate='20230417', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30288.0, self.close=30226.0, self.high=30292.8, self.low=30206.0, self.vol=2441.718, self.amt=73815003.432 
127.0.0.1 - - [17/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-17 08:20:07,302:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230417   075500    075959  ...         0.0        0.0       0
5849  20230417   080000    080459  ...         0.0        0.0       0
5850  20230417   080500    080959  ...         0.0        0.0       0
5851  20230417   081000    081459  ...         0.0        0.0       0
5852  20230417   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 08:20:07,320:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681690799, self.tradeDate='20230417', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30288.0, self.close=30226.0, self.high=30292.8, self.low=30206.0, self.vol=2441.718, self.amt=73815003.432, ukdf['pct'].iloc[-1]=-0.002044 , ukdf['amount'].iloc[-1]=73815003.432, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-824128.59138811648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30224.60363248', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40534
self.closeSec=1681691099, self.tradeDate='20230417', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30227.2, self.close=30188.1, self.high=30246.0, self.low=30187.7, self.vol=2388.611, self.amt=72161410.0825 
127.0.0.1 - - [17/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-17 08:25:01,617:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230417   080000    080459  ...         0.0        0.0       0
5850  20230417   080500    080959  ...         0.0        0.0       0
5851  20230417   081000    081459  ...         0.0        0.0       0
5852  20230417   081500    081959  ...         0.0        0.0       0
5853  20230417   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 08:25:01,618:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681691099, self.tradeDate='20230417', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30227.2, self.close=30188.1, self.high=30246.0, self.low=30187.7, self.vol=2388.611, self.amt=72161410.0825, ukdf['pct'].iloc[-1]=-0.001254 , ukdf['amount'].iloc[-1]=72161410.0825, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-822200.44228260192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30192.56180342', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [17/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41095 

self.closeSec=1681689599, self.tradeDate='20230417', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30285.4, self.close=30286.6, self.high=30291.9, self.low=30278.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41096 

self.closeSec=1681689899, self.tradeDate='20230417', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=30286.6, self.close=30292.1, self.high=30293.6, self.low=30277.3 
127.0.0.1 - - [17/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41097 

self.closeSec=1681690199, self.tradeDate='20230417', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=30292.0, self.close=30266.3, self.high=30292.1, self.low=30265.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41098 

self.closeSec=1681690499, self.tradeDate='20230417', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=30266.4, self.close=30287.9, self.high=30307.4, self.low=30233.2 
127.0.0.1 - - [17/Apr/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41099 

self.closeSec=1681690799, self.tradeDate='20230417', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30288.0, self.close=30226.0, self.high=30292.8, self.low=30206.0 
127.0.0.1 - - [17/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41100 

self.closeSec=1681691099, self.tradeDate='20230417', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30227.2, self.close=30188.1, self.high=30246.0, self.low=30187.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-17 08:00:33,992:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230417    052959  30334.4  ...  53.333333  0.495282  0.404908
5770  20230417    055959  30303.2  ...  53.333333  0.515858  0.407088
5771  20230417    062959  30377.2  ...  53.333333  0.497320  0.419725
5772  20230417    065959  30311.0  ...  53.333333  0.498372  0.430913
5773  20230417    072959  30314.7  ...  53.333333  0.484637  0.449403

[5 rows x 33 columns]
0.5407407407407407
acc is : 0.5407407407407407
2023-04-17 08:00:34,161:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.498985  0.501015       1  ...  1.029806   1.0    0.0  1.082819
536     0  0.520071  0.479929       0  ...  1.027555   1.0    0.0  1.080452
537     0  0.501740  0.498260       1  ...  1.027684   1.0    0.0  1.080588
538     0  0.513554  0.486446       0  ...  1.025976   1.0    0.0  1.078791
539     1  0.499775  0.500225       1  ...  1.026732   1.0    0.0  1.079586

[5 rows x 10 columns]
2023-04-17 08:00:34,213:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499923  0.500077       1  ...  1.021061   1.0    0.0  1.085016
46     0  0.520899  0.479101       0  ...  1.027555   1.0    0.0  1.081956
47     0  0.502600  0.497400       1  ...  1.027684   1.0    0.0  1.086443
48     0  0.514563  0.485437       0  ...  1.025976   1.0    0.0  1.083457
49     1  0.499775  0.500225       1  ...  1.026732   1.0    0.0  1.079586

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20545 

self.closeSec=1681687799, self.tradeDate='20230417', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30299', self.close='30264.3'
127.0.0.1 - - [17/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20546 

self.closeSec=1681688399, self.tradeDate='20230417', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30264.4', self.close='30257.9'
127.0.0.1 - - [17/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20547 

self.closeSec=1681688999, self.tradeDate='20230417', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30257.8', self.close='30250.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20548 

self.closeSec=1681689599, self.tradeDate='20230417', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30250.6', self.close='30286.6'
127.0.0.1 - - [17/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20549 

self.closeSec=1681690199, self.tradeDate='20230417', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30286.6', self.close='30266.3'
127.0.0.1 - - [17/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20550 

self.closeSec=1681690799, self.tradeDate='20230417', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30266.4', self.close='30226'
127.0.0.1 - - [17/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20546 

self.closeSec=1681687799, self.tradeDate='20230417', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30299', self.close='30264.3'
127.0.0.1 - - [17/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20547 

self.closeSec=1681688399, self.tradeDate='20230417', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30264.4', self.close='30257.9'
127.0.0.1 - - [17/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20548 

self.closeSec=1681688999, self.tradeDate='20230417', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30257.8', self.close='30250.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20549 

self.closeSec=1681689599, self.tradeDate='20230417', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30250.6', self.close='30286.6'
127.0.0.1 - - [17/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20550 

self.closeSec=1681690199, self.tradeDate='20230417', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30286.6', self.close='30266.3'
127.0.0.1 - - [17/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20551 

self.closeSec=1681690799, self.tradeDate='20230417', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30266.4', self.close='30226'
127.0.0.1 - - [17/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20546 

self.closeSec=1681687799, self.tradeDate='20230417', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30299', self.close='30264.3'
127.0.0.1 - - [17/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20547 

self.closeSec=1681688399, self.tradeDate='20230417', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30264.4', self.close='30257.9'
127.0.0.1 - - [17/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20548 

self.closeSec=1681688999, self.tradeDate='20230417', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30257.8', self.close='30250.6'
127.0.0.1 - - [17/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20549 

self.closeSec=1681689599, self.tradeDate='20230417', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30250.6', self.close='30286.6'
127.0.0.1 - - [17/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20550 

self.closeSec=1681690199, self.tradeDate='20230417', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30286.6', self.close='30266.3'
127.0.0.1 - - [17/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20551 

self.closeSec=1681690799, self.tradeDate='20230417', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30266.4', self.close='30226'
127.0.0.1 - - [17/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36531
self.closeSec=1681690799, self.tradeDate='20230417', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30288.0, self.close=30226.0, self.high=30292.8, self.low=30206.0, self.vol=2441.718, self.amt=73815003.432 
127.0.0.1 - - [17/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-17 08:20:07,266:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230417   075500    075959  ...         0.0        0.0       0
5849  20230417   080000    080459  ...         0.0        0.0       0
5850  20230417   080500    080959  ...         0.0        0.0       0
5851  20230417   081000    081459  ...         0.0        0.0       0
5852  20230417   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 08:20:07,272:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681690799, self.tradeDate='20230417', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30288.0, self.close=30226.0, self.high=30292.8, self.low=30206.0, self.vol=2441.718, self.amt=73815003.432, ukdf['pct'].iloc[-1]=-0.002044 , ukdf['amount'].iloc[-1]=73815003.432, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36532
self.closeSec=1681691099, self.tradeDate='20230417', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30227.2, self.close=30188.1, self.high=30246.0, self.low=30187.7, self.vol=2388.611, self.amt=72161410.0825 
127.0.0.1 - - [17/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-17 08:25:01,570:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230417   080000    080459  ...         0.0        0.0       0
5850  20230417   080500    080959  ...         0.0        0.0       0
5851  20230417   081000    081459  ...         0.0        0.0       0
5852  20230417   081500    081959  ...         0.0        0.0       0
5853  20230417   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-17 08:25:01,571:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681691099, self.tradeDate='20230417', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30227.2, self.close=30188.1, self.high=30246.0, self.low=30187.7, self.vol=2388.611, self.amt=72161410.0825, ukdf['pct'].iloc[-1]=-0.001254 , ukdf['amount'].iloc[-1]=72161410.0825, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230416   200000    235959  1681660799  ...    719  0.214799 -0.550551     NaN
720  20230417   000000    035959  1681675199  ...    720  0.438516 -0.065699     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '106999.3746651564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30307.40118376', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [17/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=856
self.closeSec=1681689599, self.tradeDate='20230417', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30306.0, self.close=30286.6, self.high=30399.9, self.low=30170.9, self.vol=41632.548, self.amt=1261524525.90243 
2023-04-17 08:00:01,914:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681689599, self.tradeDate='20230417', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30306.0, self.close=30286.6, self.high=30399.9, self.low=30170.9, self.vol=41632.548, self.amt=1261524525.90243 
2023-04-17 08:00:01,984:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230416   120000    155959  ...  21303.215  6.457237e+08  0.002704
718  20230416   160000    195959  ...  23037.583  6.974998e+08 -0.003650
719  20230416   200000    235959  ...  40127.599  1.214260e+09  0.003458
720  20230417   000000    035959  ...  57612.650  1.751918e+09 -0.000613
721  20230417   040000    075959  ...  41632.548  1.261525e+09 -0.000640

[5 rows x 11 columns]
2023-04-17 08:00:04,570:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230416   120000    155959  1681631999  ...    717  0.301863 -0.379727     NaN
718  20230416   160000    195959  1681646399  ...    718  0.253665 -0.475176     NaN
719  20230416   200000    235959  1681660799  ...    719  0.214799 -0.550551     NaN
720  20230417   000000    035959  1681675199  ...    720  0.438516 -0.065699     NaN
721  20230417   040000    075959  1681689599  ...    721  0.410187 -0.127665     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '105991.72835171805', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30288.21340287', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


