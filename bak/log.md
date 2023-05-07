# 20230507 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46389
self.closeSec=1683447599, self.tradeDate='20230507', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28922.5, self.close=28920.3, self.high=28948.0, self.low=28916.4, self.vol=575.688, self.amt=16656285.9008 
127.0.0.1 - - [07/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-07 16:20:06,185:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230507   155500    155959  ...         0.0        0.0       0
5952  20230507   160000    160459  ...         0.0        0.0       0
5953  20230507   160500    160959  ...         0.0        0.0       0
5954  20230507   161000    161459  ...         0.0        0.0       0
5955  20230507   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 16:20:06,194:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683447599, self.tradeDate='20230507', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28922.5, self.close=28920.3, self.high=28948.0, self.low=28916.4, self.vol=575.688, self.amt=16656285.9008, ukdf['pct'].iloc[-1]=-7.6e-05 , ukdf['amount'].iloc[-1]=16656285.9008, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-745825.44456474336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28923.36814286', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46390
self.closeSec=1683447899, self.tradeDate='20230507', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28920.3, self.close=28914.7, self.high=28934.7, self.low=28910.1, self.vol=518.132, self.amt=14983192.9595 
2023-05-07 16:25:02,108:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230507   160000    160459  ...         0.0        0.0       0
5953  20230507   160500    160959  ...         0.0        0.0       0
5954  20230507   161000    161459  ...         0.0        0.0       0
5955  20230507   161500    161959  ...         0.0        0.0       0
5956  20230507   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 16:25:02,109:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683447899, self.tradeDate='20230507', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28920.3, self.close=28914.7, self.high=28934.7, self.low=28910.1, self.vol=518.132, self.amt=14983192.9595, ukdf['pct'].iloc[-1]=-0.000194 , ukdf['amount'].iloc[-1]=14983192.9595, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-745354.18433968928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28915.53677778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [07/May/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46951 

self.closeSec=1683446399, self.tradeDate='20230507', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28908.7, self.close=28891.9, self.high=28914.1, self.low=28888.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46952 

self.closeSec=1683446699, self.tradeDate='20230507', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28891.8, self.close=28935.7, self.high=28935.7, self.low=28890.2 
127.0.0.1 - - [07/May/2023 16:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46953 

self.closeSec=1683446999, self.tradeDate='20230507', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28935.7, self.close=28932.4, self.high=28937.6, self.low=28924.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46954 

self.closeSec=1683447299, self.tradeDate='20230507', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28932.4, self.close=28922.5, self.high=28950.0, self.low=28920.1 
127.0.0.1 - - [07/May/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46955 

self.closeSec=1683447599, self.tradeDate='20230507', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28922.5, self.close=28920.3, self.high=28948.0, self.low=28916.4 
127.0.0.1 - - [07/May/2023 16:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46956 

self.closeSec=1683447899, self.tradeDate='20230507', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28920.3, self.close=28914.7, self.high=28934.7, self.low=28910.1 
127.0.0.1 - - [07/May/2023 16:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-07 16:00:18,995:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230507    132959  28828.9  ...  50.000000  0.463866  0.577836
5786  20230507    135959  28821.0  ...  50.000000  0.473756  0.569487
5787  20230507    142959  28869.9  ...  50.000000  0.471132  0.561131
5788  20230507    145959  28855.5  ...  50.000000  0.480030  0.550219
5789  20230507    152959  28899.4  ...  49.583333  0.475640  0.541708

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2023-05-07 16:00:19,078:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.499856  0.500144       1  ...  0.982779  -1.0    0.0  1.020610
538     0  0.516948  0.483052       0  ...  0.983273  -1.0    0.0  1.020098
539     0  0.502369  0.497631       1  ...  0.981777  -1.0    0.0  1.021650
540     0  0.516117  0.483883       0  ...  0.982578  -1.0    0.0  1.020815
541     1  0.499505  0.500495       1  ...  0.982031  -1.0    0.0  1.021384

[5 rows x 10 columns]
2023-05-07 16:00:19,090:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500500  0.499500       1  ...  0.982779  -1.0    0.0  1.023059
46     0  0.517519  0.482481       0  ...  0.983273  -1.0    0.0  1.021278
47     0  0.502422  0.497578       1  ...  0.981777  -1.0    0.0  1.021660
48     0  0.516017  0.483983       0  ...  0.982578  -1.0    0.0  1.016471
49     1  0.499505  0.500495       1  ...  0.982031  -1.0    0.0  1.021384

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23473 

self.closeSec=1683444599, self.tradeDate='20230507', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28903.9', self.close='28875.8'
127.0.0.1 - - [07/May/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23474 

self.closeSec=1683445199, self.tradeDate='20230507', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28875.9', self.close='28898.9'
127.0.0.1 - - [07/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23475 

self.closeSec=1683445799, self.tradeDate='20230507', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28898.9', self.close='28912.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23476 

self.closeSec=1683446399, self.tradeDate='20230507', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28912.6', self.close='28891.9'
127.0.0.1 - - [07/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23477 

self.closeSec=1683446999, self.tradeDate='20230507', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28891.8', self.close='28932.4'
127.0.0.1 - - [07/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23478 

self.closeSec=1683447599, self.tradeDate='20230507', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28932.4', self.close='28920.3'
127.0.0.1 - - [07/May/2023 16:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [07/May/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23474 

self.closeSec=1683444599, self.tradeDate='20230507', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28903.9', self.close='28875.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23475 

self.closeSec=1683445199, self.tradeDate='20230507', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28875.9', self.close='28898.9'
127.0.0.1 - - [07/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23476 

self.closeSec=1683445799, self.tradeDate='20230507', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28898.9', self.close='28912.5'
127.0.0.1 - - [07/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23477 

self.closeSec=1683446399, self.tradeDate='20230507', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28912.6', self.close='28891.9'
127.0.0.1 - - [07/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23478 

self.closeSec=1683446999, self.tradeDate='20230507', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28891.8', self.close='28932.4'
127.0.0.1 - - [07/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23479 

self.closeSec=1683447599, self.tradeDate='20230507', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28932.4', self.close='28920.3'
127.0.0.1 - - [07/May/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [07/May/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23474 

self.closeSec=1683444599, self.tradeDate='20230507', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28903.9', self.close='28875.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23475 

self.closeSec=1683445199, self.tradeDate='20230507', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28875.9', self.close='28898.9'
127.0.0.1 - - [07/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23476 

self.closeSec=1683445799, self.tradeDate='20230507', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28898.9', self.close='28912.5'
127.0.0.1 - - [07/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23477 

self.closeSec=1683446399, self.tradeDate='20230507', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28912.6', self.close='28891.9'
127.0.0.1 - - [07/May/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23478 

self.closeSec=1683446999, self.tradeDate='20230507', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28891.8', self.close='28932.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23479 

self.closeSec=1683447599, self.tradeDate='20230507', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28932.4', self.close='28920.3'
127.0.0.1 - - [07/May/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42387
self.closeSec=1683447599, self.tradeDate='20230507', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28922.5, self.close=28920.3, self.high=28948.0, self.low=28916.4, self.vol=575.688, self.amt=16656285.9008 
127.0.0.1 - - [07/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-07 16:20:06,015:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230507   155500    155959  ...         0.0        0.0       0
5952  20230507   160000    160459  ...         0.0        0.0       0
5953  20230507   160500    160959  ...         0.0        0.0       0
5954  20230507   161000    161459  ...         0.0        0.0       0
5955  20230507   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 16:20:06,023:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683447599, self.tradeDate='20230507', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28922.5, self.close=28920.3, self.high=28948.0, self.low=28916.4, self.vol=575.688, self.amt=16656285.9008, ukdf['pct'].iloc[-1]=-7.6e-05 , ukdf['amount'].iloc[-1]=16656285.9008, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42388
self.closeSec=1683447899, self.tradeDate='20230507', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28920.3, self.close=28914.7, self.high=28934.7, self.low=28910.1, self.vol=518.132, self.amt=14983192.9595 
127.0.0.1 - - [07/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-05-07 16:25:02,105:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230507   160000    160459  ...         0.0        0.0       0
5953  20230507   160500    160959  ...         0.0        0.0       0
5954  20230507   161000    161459  ...         0.0        0.0       0
5955  20230507   161500    161959  ...         0.0        0.0       0
5956  20230507   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 16:25:02,105:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683447899, self.tradeDate='20230507', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28920.3, self.close=28914.7, self.high=28934.7, self.low=28910.1, self.vol=518.132, self.amt=14983192.9595, ukdf['pct'].iloc[-1]=-0.000194 , ukdf['amount'].iloc[-1]=14983192.9595, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230507   040000    075959  1683417599  ...    721  0.308148 -0.931649    -1.0
722  20230507   080000    115959  1683431999  ...    722  0.301008 -0.932714    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '25554.746', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28794.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=978
self.closeSec=1683446399, self.tradeDate='20230507', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28790.8, self.close=28891.9, self.high=28943.0, self.low=28771.9, self.vol=27761.69, self.amt=801381356.5212 
127.0.0.1 - - [07/May/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-05-07 16:00:02,083:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683446399, self.tradeDate='20230507', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28790.8, self.close=28891.9, self.high=28943.0, self.low=28771.9, self.vol=27761.69, self.amt=801381356.5212 
2023-05-07 16:00:02,107:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230506   200000    235959  ...  181672.364  5.225998e+09 -0.024145
720  20230507   000000    035959  ...   77210.531  2.222132e+09  0.009595
721  20230507   040000    075959  ...   38973.798  1.121836e+09  0.000205
722  20230507   080000    115959  ...   63343.561  1.830321e+09 -0.001630
723  20230507   120000    155959  ...   27761.690  8.013814e+08  0.003512

[5 rows x 11 columns]
2023-05-07 16:00:03,479:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230506   200000    235959  1683388799  ...    719  0.274583 -1.074422    -1.0
720  20230507   000000    035959  1683403199  ...    720  0.310965 -0.943053    -1.0
721  20230507   040000    075959  1683417599  ...    721  0.308148 -0.931649    -1.0
722  20230507   080000    115959  1683431999  ...    722  0.301008 -0.932714    -1.0
723  20230507   120000    155959  1683446399  ...    723  0.262112 -1.028641    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '20851.63928385174', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28894.97012107', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


