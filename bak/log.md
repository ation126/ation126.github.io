# 20230319 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32284
self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26912.5, self.close=26990.0, self.high=26994.6, self.low=26888.5, self.vol=2369.241, self.amt=63838824.7037 
127.0.0.1 - - [19/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-19 16:20:05,760:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230319   155500    155959  ...         0.0        0.0       0
5952  20230319   160000    160459  ...         0.0        0.0       0
5953  20230319   160500    160959  ...         0.0        0.0       0
5954  20230319   161000    161459  ...         0.0        0.0       0
5955  20230319   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 16:20:05,771:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26912.5, self.close=26990.0, self.high=26994.6, self.low=26888.5, self.vol=2369.241, self.amt=63838824.7037, ukdf['pct'].iloc[-1]=0.00288 , ukdf['amount'].iloc[-1]=63838824.7037, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-629771.928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26994.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32285
self.closeSec=1679214299, self.tradeDate='20230319', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26990.0, self.close=27024.6, self.high=27076.0, self.low=26989.8, self.vol=4885.689, self.amt=132083674.0902 
127.0.0.1 - - [19/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-19 16:25:01,621:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230319   160000    160459  ...         0.0        0.0       0
5953  20230319   160500    160959  ...         0.0        0.0       0
5954  20230319   161000    161459  ...         0.0        0.0       0
5955  20230319   161500    161959  ...         0.0        0.0       0
5956  20230319   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 16:25:01,622:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679214299, self.tradeDate='20230319', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26990.0, self.close=27024.6, self.high=27076.0, self.low=26989.8, self.vol=4885.689, self.amt=132083674.0902, ukdf['pct'].iloc[-1]=0.001282 , ukdf['amount'].iloc[-1]=132083674.0902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-631637.5209966816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27025.8022766', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26912.5, self.close=26990.0, self.high=26994.6, self.low=26888.5 
127.0.0.1 - - [19/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 16:20:03,448:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26912.5, self.close=26990.0, self.high=26994.6, self.low=26888.5   
2023-03-19 16:20:04,097:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230319   155500    155959  1679212799  ...  26942.7  0.000519   1631    5
1632  20230319   160000    160459  1679213099  ...  26955.4  0.000289   1632    0
1633  20230319   160500    160959  1679213399  ...  26927.1 -0.000990   1633    1
1634  20230319   161000    161459  1679213699  ...  26868.7 -0.001188   1634    2
1635  20230319   161500    161959  1679213999  ...  26888.5  0.002880   1635    3

[5 rows x 11 columns]
2023-03-19 16:20:04,097:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=92, self.factor=0.48201613070619137, self.count=32851 

self.closeSec=1679214299, self.tradeDate='20230319', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26990.0, self.close=27024.6, self.high=27076.0, self.low=26989.8 
127.0.0.1 - - [19/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-19 16:25:01,523:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679214299, self.tradeDate='20230319', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26990.0, self.close=27024.6, self.high=27076.0, self.low=26989.8   
2023-03-19 16:25:01,597:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230319   160000    160459  1679213099  ...  26955.4  0.000289   1632    0
1633  20230319   160500    160959  1679213399  ...  26927.1 -0.000990   1633    1
1634  20230319   161000    161459  1679213699  ...  26868.7 -0.001188   1634    2
1635  20230319   161500    161959  1679213999  ...  26888.5  0.002880   1635    3
1636  20230319   162000    162459  1679214299  ...  26989.8  0.001282   1636    4

[5 rows x 11 columns]
2023-03-19 16:25:01,602:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-19 16:00:34,569:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230319    132959  27135.0  ...  48.750000  0.543333  0.448333
5787  20230319    135959  27145.2  ...  48.750000  0.531191  0.455220
5788  20230319    142959  27050.0  ...  48.333333  0.521361  0.466411
5789  20230319    145959  26971.1  ...  48.333333  0.515798  0.479576
5790  20230319    152959  26926.2  ...  48.750000  0.517828  0.490812

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-03-19 16:00:34,733:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.518542  0.481458       0  ...  1.124583  -1.0    0.0  1.216589
538     1  0.477461  0.522539       0  ...  1.127859  -1.0    0.0  1.213045
539     1  0.466153  0.533847       0  ...  1.129741  -1.0    0.0  1.211021
540     1  0.483792  0.516208       1  ...  1.129011  -1.0    0.0  1.211803
541     0  0.504200  0.495800       1  ...  1.128181  -1.0    0.0  1.212694

[5 rows x 10 columns]
2023-03-19 16:00:34,756:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519560  0.480440       0  ...  1.120147  -1.0    0.0  1.224093
46     1  0.477847  0.522153       0  ...  1.123410  -1.0    0.0  1.218591
47     1  0.465800  0.534200       0  ...  1.125284  -1.0    0.0  1.213597
48     1  0.484071  0.515929       1  ...  1.129011  -1.0    0.0  1.213151
49     0  0.504200  0.495800       1  ...  1.128181  -1.0    0.0  1.212694

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230319   155000    155959  1679212799  26964.6  26963.4 -0.000048
2023-03-19 16:00:02,572:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16424 

self.closeSec=1679213399, self.tradeDate='20230319', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26963.4', self.close='26944.5'
2023-03-19 16:10:01,602:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679213399, self.tradeDate='20230319', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26963.4', self.close='26944.5'
2023-03-19 16:10:01,640:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230319   152000    152959  1679210999  26939.5  26943.6  0.000152
525  20230319   153000    153959  1679211599  26943.6    26957  0.000497
526  20230319   154000    154959  1679212199  26956.9  26964.7  0.000286
527  20230319   155000    155959  1679212799  26964.6  26963.4 -0.000048
528  20230319   160000    160959  1679213399  26963.4  26944.5 -0.000701
2023-03-19 16:10:01,640:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16425 

self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26944.5', self.close='26990'
127.0.0.1 - - [19/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-19 16:20:04,456:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26944.5', self.close='26990'
2023-03-19 16:20:05,087:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230319   153000    153959  1679211599  26943.6    26957  0.000497
526  20230319   154000    154959  1679212199  26956.9  26964.7  0.000286
527  20230319   155000    155959  1679212799  26964.6  26963.4 -0.000048
528  20230319   160000    160959  1679213399  26963.4  26944.5 -0.000701
529  20230319   161000    161959  1679213999  26944.5    26990  0.001689
2023-03-19 16:20:05,087:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230319   155000    155959  1679212799  26964.6  26963.4
2023-03-19 16:00:02,539:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16425 

self.closeSec=1679213399, self.tradeDate='20230319', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26963.4', self.close='26944.5'
2023-03-19 16:10:01,641:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679213399, self.tradeDate='20230319', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26963.4', self.close='26944.5'
2023-03-19 16:10:01,702:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230319   152000    152959  1679210999  26939.5  26943.6
17517  20230319   153000    153959  1679211599  26943.6    26957
17518  20230319   154000    154959  1679212199  26956.9  26964.7
17519  20230319   155000    155959  1679212799  26964.6  26963.4
17520  20230319   160000    160959  1679213399  26963.4  26944.5
2023-03-19 16:10:01,709:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16426 

self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26944.5', self.close='26990'
127.0.0.1 - - [19/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-19 16:20:06,585:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26944.5', self.close='26990'
2023-03-19 16:20:06,641:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230319   153000    153959  1679211599  26943.6    26957
17518  20230319   154000    154959  1679212199  26956.9  26964.7
17519  20230319   155000    155959  1679212799  26964.6  26963.4
17520  20230319   160000    160959  1679213399  26963.4  26944.5
17521  20230319   161000    161959  1679213999  26944.5    26990
2023-03-19 16:20:06,644:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230319   155000    155959  1679212799  26964.6  26963.4
2023-03-19 16:00:02,578:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16425 

self.closeSec=1679213399, self.tradeDate='20230319', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26963.4', self.close='26944.5'
2023-03-19 16:10:01,626:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679213399, self.tradeDate='20230319', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26963.4', self.close='26944.5'
127.0.0.1 - - [19/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-19 16:10:01,635:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230319   152000    152959  1679210999  26939.5  26943.6
12189  20230319   153000    153959  1679211599  26943.6    26957
12190  20230319   154000    154959  1679212199  26956.9  26964.7
12191  20230319   155000    155959  1679212799  26964.6  26963.4
12192  20230319   160000    160959  1679213399  26963.4  26944.5
2023-03-19 16:10:01,635:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16426 

self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26944.5', self.close='26990'
127.0.0.1 - - [19/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-19 16:20:06,283:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26944.5', self.close='26990'
2023-03-19 16:20:06,474:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230319   153000    153959  1679211599  26943.6    26957
12190  20230319   154000    154959  1679212199  26956.9  26964.7
12191  20230319   155000    155959  1679212799  26964.6  26963.4
12192  20230319   160000    160959  1679213399  26963.4  26944.5
12193  20230319   161000    161959  1679213999  26944.5    26990
2023-03-19 16:20:06,475:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28282
self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26912.5, self.close=26990.0, self.high=26994.6, self.low=26888.5, self.vol=2369.241, self.amt=63838824.7037 
127.0.0.1 - - [19/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 16:20:01,693:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230319   155500    155959  ...         0.0        0.0       0
5952  20230319   160000    160459  ...         0.0        0.0       0
5953  20230319   160500    160959  ...         0.0        0.0       0
5954  20230319   161000    161459  ...         0.0        0.0       0
5955  20230319   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 16:20:01,697:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679213999, self.tradeDate='20230319', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26912.5, self.close=26990.0, self.high=26994.6, self.low=26888.5, self.vol=2369.241, self.amt=63838824.7037, ukdf['pct'].iloc[-1]=0.00288 , ukdf['amount'].iloc[-1]=63838824.7037, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28283
self.closeSec=1679214299, self.tradeDate='20230319', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26990.0, self.close=27024.6, self.high=27076.0, self.low=26989.8, self.vol=4885.689, self.amt=132083674.0902 
2023-03-19 16:25:01,529:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230319   160000    160459  ...         0.0        0.0       0
5953  20230319   160500    160959  ...         0.0        0.0       0
5954  20230319   161000    161459  ...         0.0        0.0       0
5955  20230319   161500    161959  ...         0.0        0.0       0
5956  20230319   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 16:25:01,530:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679214299, self.tradeDate='20230319', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26990.0, self.close=27024.6, self.high=27076.0, self.low=26989.8, self.vol=4885.689, self.amt=132083674.0902, ukdf['pct'].iloc[-1]=0.001282 , ukdf['amount'].iloc[-1]=132083674.0902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230319   040000    075959  1679183999  ...    721  0.986827  0.991055     1.0
722  20230319   080000    115959  1679198399  ...    722  1.015500  1.054881     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '-10810.820572874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27199.0367028', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=684
self.closeSec=1679212799, self.tradeDate='20230319', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27194.8, self.close=26963.4, self.high=27282.7, self.low=26815.9, self.vol=62219.778, self.amt=1681302531.524 
127.0.0.1 - - [19/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-03-19 16:00:02,370:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679212799, self.tradeDate='20230319', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27194.8, self.close=26963.4, self.high=27282.7, self.low=26815.9, self.vol=62219.778, self.amt=1681302531.524 
2023-03-19 16:00:02,391:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230318   200000    235959  ...  147089.406  4.027337e+09 -0.008058
720  20230319   000000    035959  ...  196552.142  5.335799e+09  0.003821
721  20230319   040000    075959  ...   95750.566  2.590727e+09 -0.015222
722  20230319   080000    115959  ...   54712.469  1.481492e+09  0.010692
723  20230319   120000    155959  ...   62219.778  1.681303e+09 -0.008505

[5 rows x 11 columns]
2023-03-19 16:00:05,569:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230318   200000    235959  1679155199  ...    719  0.763519  0.358986     NaN
720  20230319   000000    035959  1679169599  ...    720  0.887375  0.714094     1.0
721  20230319   040000    075959  1679183999  ...    721  0.986827  0.991055     1.0
722  20230319   080000    115959  1679198399  ...    722  1.015500  1.054881     1.0
723  20230319   120000    155959  1679212799  ...    723  1.010286  1.019974     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '-23486.897', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26963.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


