# 20230416 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40341
self.closeSec=1681633199, self.tradeDate='20230416', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30328.8, self.close=30341.3, self.high=30341.3, self.low=30328.8, self.vol=240.45, self.amt=7293865.582 
127.0.0.1 - - [16/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-16 16:20:07,454:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230416   155500    155959  ...         0.0        0.0       0
5945  20230416   160000    160459  ...         0.0        0.0       0
5946  20230416   160500    160959  ...         0.0        0.0       0
5947  20230416   161000    161459  ...         0.0        0.0       0
5948  20230416   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 16:20:07,464:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681633199, self.tradeDate='20230416', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30328.8, self.close=30341.3, self.high=30341.3, self.low=30328.8, self.vol=240.45, self.amt=7293865.582, ukdf['pct'].iloc[-1]=0.000409 , ukdf['amount'].iloc[-1]=7293865.582, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-831169.29290241888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30341.60545238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40342
self.closeSec=1681633499, self.tradeDate='20230416', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30341.2, self.close=30323.6, self.high=30345.1, self.low=30321.5, self.vol=353.728, self.amt=10731019.7862 
127.0.0.1 - - [16/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-16 16:25:01,590:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230416   160000    160459  ...         0.0        0.0       0
5946  20230416   160500    160959  ...         0.0        0.0       0
5947  20230416   161000    161459  ...         0.0        0.0       0
5948  20230416   161500    161959  ...         0.0        0.0       0
5949  20230416   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 16:25:01,594:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681633499, self.tradeDate='20230416', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30341.2, self.close=30323.6, self.high=30345.1, self.low=30321.5, self.vol=353.728, self.amt=10731019.7862, ukdf['pct'].iloc[-1]=-0.000583 , ukdf['amount'].iloc[-1]=10731019.7862, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-830248.54923925664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30326.30460714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40903 

self.closeSec=1681631999, self.tradeDate='20230416', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30338.7, self.close=30330.8, self.high=30338.7, self.low=30325.1 
127.0.0.1 - - [16/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40904 

self.closeSec=1681632299, self.tradeDate='20230416', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=30330.8, self.close=30327.8, self.high=30338.8, self.low=30323.9 
127.0.0.1 - - [16/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40905 

self.closeSec=1681632599, self.tradeDate='20230416', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=30327.9, self.close=30325.4, self.high=30327.9, self.low=30322.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40906 

self.closeSec=1681632899, self.tradeDate='20230416', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=30325.4, self.close=30328.9, self.high=30330.0, self.low=30316.0 
127.0.0.1 - - [16/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40907 

self.closeSec=1681633199, self.tradeDate='20230416', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30328.8, self.close=30341.3, self.high=30341.3, self.low=30328.8 
127.0.0.1 - - [16/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40908 

self.closeSec=1681633499, self.tradeDate='20230416', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30341.2, self.close=30323.6, self.high=30345.1, self.low=30321.5 
127.0.0.1 - - [16/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-16 16:00:35,670:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230416    132959  30291.7  ...  54.166667  0.492890  0.599051
5786  20230416    135959  30303.5  ...  54.166667  0.490914  0.589524
5787  20230416    142959  30296.7  ...  54.166667  0.495103  0.574740
5788  20230416    145959  30310.8  ...  54.166667  0.488772  0.565304
5789  20230416    152959  30289.2  ...  54.166667  0.499446  0.549368

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-04-16 16:00:35,824:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.518635  0.481365       0  ...  1.043263  -1.0    0.0  1.072883
538     0  0.516664  0.483336       1  ...  1.042781  -1.0    0.0  1.073378
539     0  0.521127  0.478873       0  ...  1.043524  -1.0    0.0  1.072613
540     0  0.509742  0.490258       1  ...  1.042308  -1.0    0.0  1.073863
541     0  0.521252  0.478748       1  ...  1.042088  -1.0    0.0  1.074090

[5 rows x 10 columns]
2023-04-16 16:00:35,845:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518517  0.481483       0  ...  1.026956  -1.0    0.0  1.073361
46     0  0.517046  0.482954       1  ...  1.042781  -1.0    0.0  1.075698
47     0  0.521974  0.478026       0  ...  1.043524  -1.0    0.0  1.077704
48     0  0.510138  0.489862       1  ...  1.026016  -1.0    0.0  1.077044
49     0  0.521252  0.478748       1  ...  1.042088  -1.0    0.0  1.074090

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [16/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20449 

self.closeSec=1681630199, self.tradeDate='20230416', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30300', self.close='30324.4'
127.0.0.1 - - [16/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20450 

self.closeSec=1681630799, self.tradeDate='20230416', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30324.3', self.close='30360.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20451 

self.closeSec=1681631399, self.tradeDate='20230416', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30360.6', self.close='30348.1'
127.0.0.1 - - [16/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20452 

self.closeSec=1681631999, self.tradeDate='20230416', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30348', self.close='30330.8'
127.0.0.1 - - [16/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20453 

self.closeSec=1681632599, self.tradeDate='20230416', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30330.8', self.close='30325.4'
127.0.0.1 - - [16/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20454 

self.closeSec=1681633199, self.tradeDate='20230416', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30325.4', self.close='30341.3'
127.0.0.1 - - [16/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20450 

self.closeSec=1681630199, self.tradeDate='20230416', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30300', self.close='30324.4'
127.0.0.1 - - [16/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20451 

self.closeSec=1681630799, self.tradeDate='20230416', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30324.3', self.close='30360.5'
127.0.0.1 - - [16/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20452 

self.closeSec=1681631399, self.tradeDate='20230416', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30360.6', self.close='30348.1'
127.0.0.1 - - [16/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20453 

self.closeSec=1681631999, self.tradeDate='20230416', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30348', self.close='30330.8'
127.0.0.1 - - [16/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20454 

self.closeSec=1681632599, self.tradeDate='20230416', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30330.8', self.close='30325.4'
127.0.0.1 - - [16/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20455 

self.closeSec=1681633199, self.tradeDate='20230416', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30325.4', self.close='30341.3'
127.0.0.1 - - [16/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20450 

self.closeSec=1681630199, self.tradeDate='20230416', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30300', self.close='30324.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20451 

self.closeSec=1681630799, self.tradeDate='20230416', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30324.3', self.close='30360.5'
127.0.0.1 - - [16/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20452 

self.closeSec=1681631399, self.tradeDate='20230416', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30360.6', self.close='30348.1'
127.0.0.1 - - [16/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20453 

self.closeSec=1681631999, self.tradeDate='20230416', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30348', self.close='30330.8'
127.0.0.1 - - [16/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20454 

self.closeSec=1681632599, self.tradeDate='20230416', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30330.8', self.close='30325.4'
127.0.0.1 - - [16/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20455 

self.closeSec=1681633199, self.tradeDate='20230416', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30325.4', self.close='30341.3'
127.0.0.1 - - [16/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36339
self.closeSec=1681633199, self.tradeDate='20230416', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30328.8, self.close=30341.3, self.high=30341.3, self.low=30328.8, self.vol=240.45, self.amt=7293865.582 
127.0.0.1 - - [16/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-16 16:20:07,026:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230416   155500    155959  ...         0.0        0.0       0
5945  20230416   160000    160459  ...         0.0        0.0       0
5946  20230416   160500    160959  ...         0.0        0.0       0
5947  20230416   161000    161459  ...         0.0        0.0       0
5948  20230416   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 16:20:07,035:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681633199, self.tradeDate='20230416', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30328.8, self.close=30341.3, self.high=30341.3, self.low=30328.8, self.vol=240.45, self.amt=7293865.582, ukdf['pct'].iloc[-1]=0.000409 , ukdf['amount'].iloc[-1]=7293865.582, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36340
self.closeSec=1681633499, self.tradeDate='20230416', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30341.2, self.close=30323.6, self.high=30345.1, self.low=30321.5, self.vol=353.728, self.amt=10731019.7862 
2023-04-16 16:25:01,616:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230416   160000    160459  ...         0.0        0.0       0
5946  20230416   160500    160959  ...         0.0        0.0       0
5947  20230416   161000    161459  ...         0.0        0.0       0
5948  20230416   161500    161959  ...         0.0        0.0       0
5949  20230416   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 16:25:01,617:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681633499, self.tradeDate='20230416', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30341.2, self.close=30323.6, self.high=30345.1, self.low=30321.5, self.vol=353.728, self.amt=10731019.7862, ukdf['pct'].iloc[-1]=-0.000583 , ukdf['amount'].iloc[-1]=10731019.7862, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230416   040000    075959  1681603199  ...    721  0.295218 -0.415715     NaN
722  20230416   080000    115959  1681617599  ...    722  0.288443 -0.418886     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '103932.4365', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30249', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [16/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=852
self.closeSec=1681631999, self.tradeDate='20230416', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30249.0, self.close=30330.8, self.high=30397.4, self.low=30240.5, self.vol=21303.215, self.amt=645723694.08456 
2023-04-16 16:00:02,010:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681631999, self.tradeDate='20230416', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30249.0, self.close=30330.8, self.high=30397.4, self.low=30240.5, self.vol=21303.215, self.amt=645723694.08456 
2023-04-16 16:00:02,104:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230415   200000    235959  ...  32820.069  9.963811e+08 -0.001683
720  20230416   000000    035959  ...  38861.466  1.176269e+09 -0.000033
721  20230416   040000    075959  ...  22141.798  6.708111e+08 -0.001270
722  20230416   080000    115959  ...  26508.945  8.011411e+08 -0.001037
723  20230416   120000    155959  ...  21303.215  6.457237e+08  0.002704

[5 rows x 11 columns]
2023-04-16 16:00:05,268:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230415   200000    235959  1681574399  ...    719  0.323811 -0.377998     NaN
720  20230416   000000    035959  1681588799  ...    720  0.300235 -0.416641     NaN
721  20230416   040000    075959  1681603199  ...    721  0.295218 -0.415715     NaN
722  20230416   080000    115959  1681617599  ...    722  0.288443 -0.418886     NaN
723  20230416   120000    155959  1681631999  ...    723  0.301863 -0.379727     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '108222.912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30330.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


