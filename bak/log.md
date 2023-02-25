# 20230225 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [25/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25948
self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23136.1, self.close=23126.8, self.high=23136.1, self.low=23120.5, self.vol=721.0, self.amt=16675384.8934 
2023-02-25 16:20:01,570:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230225   155500    155959  ...         0.0        0.0       0
5952  20230225   160000    160459  ...         0.0        0.0       0
5953  20230225   160500    160959  ...         0.0        0.0       0
5954  20230225   161000    161459  ...         0.0        0.0       0
5955  20230225   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 16:20:01,570:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23136.1, self.close=23126.8, self.high=23136.1, self.low=23120.5, self.vol=721.0, self.amt=16675384.8934, ukdf['pct'].iloc[-1]=-0.000398 , ukdf['amount'].iloc[-1]=16675384.8934, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-397011.16', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23126.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25949
self.closeSec=1677313499, self.tradeDate='20230225', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23126.8, self.close=23141.1, self.high=23141.4, self.low=23123.8, self.vol=743.707, self.amt=17206510.6679 
127.0.0.1 - - [25/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-25 16:25:01,752:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230225   160000    160459  ...         0.0        0.0       0
5953  20230225   160500    160959  ...         0.0        0.0       0
5954  20230225   161000    161459  ...         0.0        0.0       0
5955  20230225   161500    161959  ...         0.0        0.0       0
5956  20230225   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 16:25:01,752:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677313499, self.tradeDate='20230225', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23126.8, self.close=23141.1, self.high=23141.4, self.low=23123.8, self.vol=743.707, self.amt=17206510.6679, ukdf['pct'].iloc[-1]=0.000618 , ukdf['amount'].iloc[-1]=17206510.6679, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-397865.6592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23141', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23136.1, self.close=23126.8, self.high=23136.1, self.low=23120.5 
127.0.0.1 - - [25/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-25 16:20:01,492:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23136.1, self.close=23126.8, self.high=23136.1, self.low=23120.5   
2023-02-25 16:20:01,542:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230225   155500    155959  1677311999  ...  23092.3  0.000715   1631    5
1632  20230225   160000    160459  1677312299  ...  23091.3 -0.000437   1632    0
1633  20230225   160500    160959  1677312599  ...  23098.5  0.000801   1633    1
1634  20230225   161000    161459  1677312899  ...  23105.5  0.000818   1634    2
1635  20230225   161500    161959  1677313199  ...  23120.5 -0.000398   1635    3

[5 rows x 11 columns]
2023-02-25 16:20:01,542:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7932374538057403, self.count=26515 

self.closeSec=1677313499, self.tradeDate='20230225', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23126.8, self.close=23141.1, self.high=23141.4, self.low=23123.8 
2023-02-25 16:25:01,630:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677313499, self.tradeDate='20230225', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23126.8, self.close=23141.1, self.high=23141.4, self.low=23123.8   
127.0.0.1 - - [25/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-25 16:25:01,698:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230225   160000    160459  1677312299  ...  23091.3 -0.000437   1632    0
1633  20230225   160500    160959  1677312599  ...  23098.5  0.000801   1633    1
1634  20230225   161000    161459  1677312899  ...  23105.5  0.000818   1634    2
1635  20230225   161500    161959  1677313199  ...  23120.5 -0.000398   1635    3
1636  20230225   162000    162459  1677313499  ...  23123.8  0.000618   1636    4

[5 rows x 11 columns]
2023-02-25 16:25:01,698:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-25 16:00:34,258:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230225    132959  23117.7  ...  47.500000  0.390514  0.745105
5787  20230225    135959  23056.9  ...  47.083333  0.386512  0.749614
5788  20230225    142959  23030.2  ...  47.500000  0.394614  0.751962
5789  20230225    145959  23064.5  ...  47.500000  0.398255  0.753318
5790  20230225    152959  23079.9  ...  47.916667  0.398327  0.754568

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-02-25 16:00:34,421:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.509730  0.490270       0  ...  0.962352   1.0    0.0  1.059951
538     0  0.511004  0.488996       1  ...  0.963785   1.0    0.0  1.061530
539     0  0.530677  0.469323       1  ...  0.964429   1.0    0.0  1.062239
540     0  0.533125  0.466875       1  ...  0.964441   1.0    0.0  1.062253
541     0  0.530660  0.469340       1  ...  0.965632   1.0    0.0  1.063564

[5 rows x 10 columns]
2023-02-25 16:00:34,458:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509202  0.490798       0  ...  1.027588   1.0    0.0  1.064803
46     0  0.510068  0.489932       1  ...  1.029118   1.0    0.0  1.058111
47     0  0.529935  0.470065       1  ...  1.009506   1.0    0.0  1.060355
48     0  0.532743  0.467257       1  ...  0.964441   1.0    0.0  1.061217
49     0  0.530660  0.469340       1  ...  0.965632   1.0    0.0  1.063564

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.95', 'enterprice': '23067.1', 'countrevence': '0', 'unrealprofit': '1406.965', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23109.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230225   155000    155959  1677311999  23081.3  23108.7  0.001187
2023-02-25 16:00:02,231:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13256 

self.closeSec=1677312599, self.tradeDate='20230225', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23108.7', self.close='23117.1'
2023-02-25 16:10:01,628:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677312599, self.tradeDate='20230225', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23108.7', self.close='23117.1'
2023-02-25 16:10:01,655:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230225   152000    152959  1677310199  23082.8  23080.2 -0.000113
525  20230225   153000    153959  1677310799  23080.3  23088.8  0.000373
526  20230225   154000    154959  1677311399  23088.7  23081.3 -0.000325
527  20230225   155000    155959  1677311999  23081.3  23108.7  0.001187
528  20230225   160000    160959  1677312599  23108.7  23117.1  0.000363
2023-02-25 16:10:01,655:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13257 

self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23117.1', self.close='23126.8'
2023-02-25 16:20:01,608:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23117.1', self.close='23126.8'
127.0.0.1 - - [25/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-25 16:20:01,639:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230225   153000    153959  1677310799  23080.3  23088.8  0.000373
526  20230225   154000    154959  1677311399  23088.7  23081.3 -0.000325
527  20230225   155000    155959  1677311999  23081.3  23108.7  0.001187
528  20230225   160000    160959  1677312599  23108.7  23117.1  0.000363
529  20230225   161000    161959  1677313199  23117.1  23126.8  0.000420
2023-02-25 16:20:01,639:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230225   155000    155959  1677311999  23081.3  23108.7
2023-02-25 16:00:02,254:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13257 

self.closeSec=1677312599, self.tradeDate='20230225', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23108.7', self.close='23117.1'
2023-02-25 16:10:01,607:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677312599, self.tradeDate='20230225', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23108.7', self.close='23117.1'
127.0.0.1 - - [25/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-25 16:10:01,625:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230225   152000    152959  1677310199  23082.8  23080.2
17517  20230225   153000    153959  1677310799  23080.3  23088.8
17518  20230225   154000    154959  1677311399  23088.7  23081.3
17519  20230225   155000    155959  1677311999  23081.3  23108.7
17520  20230225   160000    160959  1677312599  23108.7  23117.1
2023-02-25 16:10:01,625:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13258 

self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23117.1', self.close='23126.8'
2023-02-25 16:20:01,644:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23117.1', self.close='23126.8'
2023-02-25 16:20:01,662:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230225   153000    153959  1677310799  23080.3  23088.8
17518  20230225   154000    154959  1677311399  23088.7  23081.3
17519  20230225   155000    155959  1677311999  23081.3  23108.7
17520  20230225   160000    160959  1677312599  23108.7  23117.1
17521  20230225   161000    161959  1677313199  23117.1  23126.8
2023-02-25 16:20:01,662:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230225   155000    155959  1677311999  23081.3  23108.7
2023-02-25 16:00:02,261:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13257 

self.closeSec=1677312599, self.tradeDate='20230225', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23108.7', self.close='23117.1'
2023-02-25 16:10:01,618:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677312599, self.tradeDate='20230225', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23108.7', self.close='23117.1'
2023-02-25 16:10:01,637:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230225   152000    152959  1677310199  23082.8  23080.2
12189  20230225   153000    153959  1677310799  23080.3  23088.8
12190  20230225   154000    154959  1677311399  23088.7  23081.3
12191  20230225   155000    155959  1677311999  23081.3  23108.7
12192  20230225   160000    160959  1677312599  23108.7  23117.1
2023-02-25 16:10:01,637:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13258 

self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23117.1', self.close='23126.8'
2023-02-25 16:20:01,639:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23117.1', self.close='23126.8'
2023-02-25 16:20:01,659:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230225   153000    153959  1677310799  23080.3  23088.8
12190  20230225   154000    154959  1677311399  23088.7  23081.3
12191  20230225   155000    155959  1677311999  23081.3  23108.7
12192  20230225   160000    160959  1677312599  23108.7  23117.1
12193  20230225   161000    161959  1677313199  23117.1  23126.8
2023-02-25 16:20:01,659:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21946
self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23136.1, self.close=23126.8, self.high=23136.1, self.low=23120.5, self.vol=721.0, self.amt=16675384.8934 
127.0.0.1 - - [25/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-25 16:20:01,576:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230225   155500    155959  ...         0.0        0.0       0
5952  20230225   160000    160459  ...         0.0        0.0       0
5953  20230225   160500    160959  ...         0.0        0.0       0
5954  20230225   161000    161459  ...         0.0        0.0       0
5955  20230225   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 16:20:01,578:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677313199, self.tradeDate='20230225', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23136.1, self.close=23126.8, self.high=23136.1, self.low=23120.5, self.vol=721.0, self.amt=16675384.8934, ukdf['pct'].iloc[-1]=-0.000398 , ukdf['amount'].iloc[-1]=16675384.8934, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [25/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21947
self.closeSec=1677313499, self.tradeDate='20230225', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23126.8, self.close=23141.1, self.high=23141.4, self.low=23123.8, self.vol=743.707, self.amt=17206510.6679 
2023-02-25 16:25:01,740:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230225   160000    160459  ...         0.0        0.0       0
5953  20230225   160500    160959  ...         0.0        0.0       0
5954  20230225   161000    161459  ...         0.0        0.0       0
5955  20230225   161500    161959  ...         0.0        0.0       0
5956  20230225   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 16:25:01,740:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677313499, self.tradeDate='20230225', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23126.8, self.close=23141.1, self.high=23141.4, self.low=23123.8, self.vol=743.707, self.amt=17206510.6679, ukdf['pct'].iloc[-1]=0.000618 , ukdf['amount'].iloc[-1]=17206510.6679, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

720  20230225   000000    035959  ...  235085.841  5.429878e+09 -0.007079
721  20230225   040000    075959  ...   89582.293  2.075756e+09  0.000160
722  20230225   080000    115959  ...   32612.850  7.540489e+08 -0.004777
723  20230225   120000    155959  ...   26914.175  6.208548e+08  0.001899

[5 rows x 11 columns]
2023-02-25 16:00:04,590:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230224   200000    235959  1677254399  ...    719  0.622744  0.003444     NaN
720  20230225   000000    035959  1677268799  ...    720  0.644271  0.046288     NaN
721  20230225   040000    075959  1677283199  ...    721  0.698404  0.175532     NaN
722  20230225   080000    115959  1677297599  ...    722  0.799119  0.424163     NaN
723  20230225   120000    155959  1677311999  ...    723  0.888594  0.642527     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '66588.7365', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23108.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '66588.7365', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23108.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-02-25 16:00:10,388:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '977636.9740257', 'total': '977636.9740257', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-02-25 16:00:10,638:DEBUG:s_rsrs:main.py:253:openBuy:185271: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-02-25 16:00:10,639:INFO:s_rsrs:main.py:254:openBuy:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 42.179, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41832F1677312010637I0L65'}
2023-02-25 16:00:10,656:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:2251600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230225, closeTime:155959, close:23108.7, sign:1, total:977636.9740257, side:buy  
127.0.0.1 - - [25/Feb/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-02-25 16:00:10,658:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41831F1677312005245I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677312005356130, 'quantity': '36.465', 'price': '23108.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677312004851, 'updatetime': 1677312005356, 'tradetype': 'usdt', 'selfid': 41831, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677312005356, 'clientorderid': '41831F1677312005245I0L65', 'price': '23108.8', 'quantity': '36.465', 'commission': '842.662392', 'commissionasset': 'USDT', 'tradetime': 1677312005356, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677312005356}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Feb/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-02-25 16:00:10,662:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41831F1677312005245I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677312005356130, 'quantity': '36.465', 'price': '23108.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677312004851, 'updatetime': 1677312005356, 'tradetype': 'usdt', 'selfid': 41831, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677312005356, 'clientorderid': '41831F1677312005245I0L65', 'price': '23108.8', 'quantity': '36.465', 'commission': '842.662392', 'commissionasset': 'USDT', 'tradetime': 1677312005356, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677312005356}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-25 16:00:10,791:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41832F1677312010637I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677312010735845, 'quantity': '42.179', 'price': '23108.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677312010435, 'updatetime': 1677312010735, 'tradetype': 'usdt', 'selfid': 41832, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677312010735, 'clientorderid': '41832F1677312010637I0L65', 'price': '23108.8', 'quantity': '42.179', 'commission': '974.7060752', 'commissionasset': 'USDT', 'tradetime': 1677312010735, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677312010735}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Feb/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-02-25 16:00:11,041:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41832F1677312010637I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677312010735845, 'quantity': '42.179', 'price': '23108.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677312010435, 'updatetime': 1677312010735, 'tradetype': 'usdt', 'selfid': 41832, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677312010735, 'clientorderid': '41832F1677312010637I0L65', 'price': '23108.8', 'quantity': '42.179', 'commission': '974.7060752', 'commissionasset': 'USDT', 'tradetime': 1677312010735, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677312010735}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Feb/2023 16:00:11] "POST / HTTP/1.1" 200 -


