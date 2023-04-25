# 20230425 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42933
self.closeSec=1682410799, self.tradeDate='20230425', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27283.4, self.close=27286.1, self.high=27299.3, self.low=27263.4, self.vol=1038.836, self.amt=28338317.5376 
127.0.0.1 - - [25/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-04-25 16:20:05,647:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230425   155500    155959  ...         0.0        0.0       0
5945  20230425   160000    160459  ...         0.0        0.0       0
5946  20230425   160500    160959  ...         0.0        0.0       0
5947  20230425   161000    161459  ...         0.0        0.0       0
5948  20230425   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 16:20:05,667:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682410799, self.tradeDate='20230425', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27283.4, self.close=27286.1, self.high=27299.3, self.low=27263.4, self.vol=1038.836, self.amt=28338317.5376, ukdf['pct'].iloc[-1]=9.9e-05 , ukdf['amount'].iloc[-1]=28338317.5376, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-647253.056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27285.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42934
self.closeSec=1682411099, self.tradeDate='20230425', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27286.0, self.close=27218.9, self.high=27286.1, self.low=27176.6, self.vol=4956.279, self.amt=134846798.3881 
127.0.0.1 - - [25/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-25 16:25:01,584:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230425   160000    160459  ...         0.0        0.0       0
5946  20230425   160500    160959  ...         0.0        0.0       0
5947  20230425   161000    161459  ...         0.0        0.0       0
5948  20230425   161500    161959  ...         0.0        0.0       0
5949  20230425   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 16:25:01,584:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682411099, self.tradeDate='20230425', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27286.0, self.close=27218.9, self.high=27286.1, self.low=27176.6, self.vol=4956.279, self.amt=134846798.3881, ukdf['pct'].iloc[-1]=-0.002463 , ukdf['amount'].iloc[-1]=134846798.3881, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-643251.352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27218.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43495 

self.closeSec=1682409599, self.tradeDate='20230425', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27264.3, self.close=27252.3, self.high=27270.6, self.low=27243.7 
127.0.0.1 - - [25/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43496 

self.closeSec=1682409899, self.tradeDate='20230425', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27252.4, self.close=27214.2, self.high=27264.4, self.low=27214.2 
127.0.0.1 - - [25/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43497 

self.closeSec=1682410199, self.tradeDate='20230425', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27214.3, self.close=27274.0, self.high=27278.7, self.low=27210.8 
127.0.0.1 - - [25/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43498 

self.closeSec=1682410499, self.tradeDate='20230425', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27274.0, self.close=27283.4, self.high=27290.2, self.low=27259.4 
127.0.0.1 - - [25/Apr/2023 16:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43499 

self.closeSec=1682410799, self.tradeDate='20230425', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27283.4, self.close=27286.1, self.high=27299.3, self.low=27263.4 
127.0.0.1 - - [25/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43500 

self.closeSec=1682411099, self.tradeDate='20230425', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27286.0, self.close=27218.9, self.high=27286.1, self.low=27176.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-25 16:00:21,415:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230425    132959  27398.5  ...  51.666667  0.476997  0.470038
5786  20230425    135959  27366.1  ...  51.666667  0.483302  0.464252
5787  20230425    142959  27400.8  ...  51.666667  0.487066  0.457084
5788  20230425    145959  27421.5  ...  51.666667  0.474375  0.456756
5789  20230425    152959  27347.0  ...  51.666667  0.472385  0.457457

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-04-25 16:00:21,521:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.505062  0.494938       1  ...  0.824705   1.0    0.0  0.891332
538     0  0.521120  0.478880       1  ...  0.825328   1.0    0.0  0.892006
539     0  0.522772  0.477228       0  ...  0.823086   1.0    0.0  0.889582
540     0  0.500234  0.499766       0  ...  0.822731   1.0    0.0  0.889198
541     0  0.509554  0.490446       0  ...  0.820235   1.0    0.0  0.886502

[5 rows x 10 columns]
2023-04-25 16:00:21,546:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505202  0.494798       1  ...  0.824705   1.0    0.0  0.904684
46     0  0.521630  0.478370       1  ...  0.825328   1.0    0.0  0.905359
47     0  0.522946  0.477054       0  ...  0.823086   1.0    0.0  0.900677
48     1  0.499992  0.500008       0  ...  0.822731   1.0    0.0  0.899578
49     0  0.509554  0.490446       0  ...  0.820235   1.0    0.0  0.886502

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21745 

self.closeSec=1682407799, self.tradeDate='20230425', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27387.7', self.close='27335.2'
127.0.0.1 - - [25/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21746 

self.closeSec=1682408399, self.tradeDate='20230425', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27335.2', self.close='27278.2'
127.0.0.1 - - [25/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21747 

self.closeSec=1682408999, self.tradeDate='20230425', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27278.1', self.close='27275.7'
127.0.0.1 - - [25/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21748 

self.closeSec=1682409599, self.tradeDate='20230425', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27275.6', self.close='27252.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21749 

self.closeSec=1682410199, self.tradeDate='20230425', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27252.4', self.close='27274'
127.0.0.1 - - [25/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21750 

self.closeSec=1682410799, self.tradeDate='20230425', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27274', self.close='27286.1'
127.0.0.1 - - [25/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [25/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21746 

self.closeSec=1682407799, self.tradeDate='20230425', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27387.7', self.close='27335.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21747 

self.closeSec=1682408399, self.tradeDate='20230425', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27335.2', self.close='27278.2'
127.0.0.1 - - [25/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21748 

self.closeSec=1682408999, self.tradeDate='20230425', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27278.1', self.close='27275.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21749 

self.closeSec=1682409599, self.tradeDate='20230425', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27275.6', self.close='27252.3'
127.0.0.1 - - [25/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21750 

self.closeSec=1682410199, self.tradeDate='20230425', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27252.4', self.close='27274'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21751 

self.closeSec=1682410799, self.tradeDate='20230425', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27274', self.close='27286.1'
127.0.0.1 - - [25/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21746 

self.closeSec=1682407799, self.tradeDate='20230425', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27387.7', self.close='27335.2'
127.0.0.1 - - [25/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21747 

self.closeSec=1682408399, self.tradeDate='20230425', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27335.2', self.close='27278.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21748 

self.closeSec=1682408999, self.tradeDate='20230425', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27278.1', self.close='27275.7'
127.0.0.1 - - [25/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21749 

self.closeSec=1682409599, self.tradeDate='20230425', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27275.6', self.close='27252.3'
127.0.0.1 - - [25/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21750 

self.closeSec=1682410199, self.tradeDate='20230425', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27252.4', self.close='27274'
127.0.0.1 - - [25/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21751 

self.closeSec=1682410799, self.tradeDate='20230425', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27274', self.close='27286.1'
127.0.0.1 - - [25/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38931
self.closeSec=1682410799, self.tradeDate='20230425', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27283.4, self.close=27286.1, self.high=27299.3, self.low=27263.4, self.vol=1038.836, self.amt=28338317.5376 
127.0.0.1 - - [25/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-25 16:20:06,055:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230425   155500    155959  ...         0.0        0.0       0
5945  20230425   160000    160459  ...         0.0        0.0       0
5946  20230425   160500    160959  ...         0.0        0.0       0
5947  20230425   161000    161459  ...         0.0        0.0       0
5948  20230425   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 16:20:06,067:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682410799, self.tradeDate='20230425', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27283.4, self.close=27286.1, self.high=27299.3, self.low=27263.4, self.vol=1038.836, self.amt=28338317.5376, ukdf['pct'].iloc[-1]=9.9e-05 , ukdf['amount'].iloc[-1]=28338317.5376, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38932
self.closeSec=1682411099, self.tradeDate='20230425', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27286.0, self.close=27218.9, self.high=27286.1, self.low=27176.6, self.vol=4956.279, self.amt=134846798.3881 
127.0.0.1 - - [25/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-25 16:25:01,653:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230425   160000    160459  ...         0.0        0.0       0
5946  20230425   160500    160959  ...         0.0        0.0       0
5947  20230425   161000    161459  ...         0.0        0.0       0
5948  20230425   161500    161959  ...         0.0        0.0       0
5949  20230425   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 16:25:01,655:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682411099, self.tradeDate='20230425', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27286.0, self.close=27218.9, self.high=27286.1, self.low=27176.6, self.vol=4956.279, self.amt=134846798.3881, ukdf['pct'].iloc[-1]=-0.002463 , ukdf['amount'].iloc[-1]=134846798.3881, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230425   040000    075959  1682380799  ...    721  0.628881 -0.321602     NaN
722  20230425   080000    115959  1682395199  ...    722  0.589595 -0.430115     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-49143.537', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27334.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [25/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=906
self.closeSec=1682409599, self.tradeDate='20230425', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27337.6, self.close=27252.3, self.high=27452.8, self.low=27222.7, self.vol=45282.567, self.amt=1238376146.9306 
2023-04-25 16:00:01,973:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682409599, self.tradeDate='20230425', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27337.6, self.close=27252.3, self.high=27452.8, self.low=27222.7, self.vol=45282.567, self.amt=1238376146.9306 
2023-04-25 16:00:02,049:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230424   200000    235959  ...  135196.378  3.711698e+09 -0.010312
720  20230425   000000    035959  ...  141565.215  3.860182e+09  0.004322
721  20230425   040000    075959  ...   37313.066  1.023684e+09  0.004519
722  20230425   080000    115959  ...   43907.361  1.204137e+09 -0.005815
723  20230425   120000    155959  ...   45282.567  1.238376e+09 -0.003120

[5 rows x 11 columns]
2023-04-25 16:00:04,299:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230424   200000    235959  1682351999  ...    719  1.016895  0.705436     1.0
720  20230425   000000    035959  1682366399  ...    720  0.742974 -0.015014     NaN
721  20230425   040000    075959  1682380799  ...    721  0.628881 -0.321602     NaN
722  20230425   080000    115959  1682395199  ...    722  0.589595 -0.430115     NaN
723  20230425   120000    155959  1682409599  ...    723  0.571203 -0.484200     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-53386.00066125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27253.31425', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


