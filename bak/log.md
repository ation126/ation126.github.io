# 20230407 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37756
self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27858.8, self.close=27856.0, self.high=27871.1, self.low=27825.6, self.vol=1177.536, self.amt=32796394.4225 
127.0.0.1 - - [07/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 16:20:09,936:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230407   155500    155959  ...         0.0        0.0       0
5952  20230407   160000    160459  ...         0.0        0.0       0
5953  20230407   160500    160959  ...         0.0        0.0       0
5954  20230407   161000    161459  ...         0.0        0.0       0
5955  20230407   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 16:20:09,947:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27858.8, self.close=27856.0, self.high=27871.1, self.low=27825.6, self.vol=1177.536, self.amt=32796394.4225, ukdf['pct'].iloc[-1]=-0.000104 , ukdf['amount'].iloc[-1]=32796394.4225, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-681570.7061734952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27855.58799145', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37757
self.closeSec=1680855899, self.tradeDate='20230407', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27855.9, self.close=27872.5, self.high=27873.0, self.low=27837.1, self.vol=1010.746, self.amt=28155187.3718 
2023-04-07 16:25:01,707:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230407   160000    160459  ...         0.0        0.0       0
5953  20230407   160500    160959  ...         0.0        0.0       0
5954  20230407   161000    161459  ...         0.0        0.0       0
5955  20230407   161500    161959  ...         0.0        0.0       0
5956  20230407   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 16:25:01,707:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680855899, self.tradeDate='20230407', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27855.9, self.close=27872.5, self.high=27873.0, self.low=27837.1, self.vol=1010.746, self.amt=28155187.3718, ukdf['pct'].iloc[-1]=0.000592 , ukdf['amount'].iloc[-1]=28155187.3718, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-682588.4032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27872.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27858.8, self.close=27856.0, self.high=27871.1, self.low=27825.6 
127.0.0.1 - - [07/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-07 16:20:07,427:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27858.8, self.close=27856.0, self.high=27871.1, self.low=27825.6   
2023-04-07 16:20:08,727:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230407   155500    155959  1680854399  ...  27755.0  0.000108   1631    5
1632  20230407   160000    160459  1680854699  ...  27785.0  0.000255   1632    0
1633  20230407   160500    160959  1680854999  ...  27820.5  0.000747   1633    1
1634  20230407   161000    161459  1680855299  ...  27830.8  0.000323   1634    2
1635  20230407   161500    161959  1680855599  ...  27825.6 -0.000104   1635    3

[5 rows x 11 columns]
2023-04-07 16:20:08,727:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=24, self.factor=0.5435140205739103, self.count=38323 

self.closeSec=1680855899, self.tradeDate='20230407', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27855.9, self.close=27872.5, self.high=27873.0, self.low=27837.1 
127.0.0.1 - - [07/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-07 16:25:01,656:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680855899, self.tradeDate='20230407', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27855.9, self.close=27872.5, self.high=27873.0, self.low=27837.1   
2023-04-07 16:25:01,686:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230407   160000    160459  1680854699  ...  27785.0  0.000255   1632    0
1633  20230407   160500    160959  1680854999  ...  27820.5  0.000747   1633    1
1634  20230407   161000    161459  1680855299  ...  27830.8  0.000323   1634    2
1635  20230407   161500    161959  1680855599  ...  27825.6 -0.000104   1635    3
1636  20230407   162000    162459  1680855899  ...  27837.1  0.000592   1636    4

[5 rows x 11 columns]
2023-04-07 16:25:01,686:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-07 16:00:30,874:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230407    132959  28010.0  ...  47.500000  0.478447  0.385860
5787  20230407    135959  27964.2  ...  47.083333  0.478325  0.388851
5788  20230407    142959  27963.6  ...  47.083333  0.472575  0.395433
5789  20230407    145959  27935.7  ...  47.083333  0.475893  0.402315
5790  20230407    152959  27950.1  ...  46.666667  0.468397  0.414046

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-04-07 16:00:31,050:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.505142  0.494858       0  ...  0.959278   1.0    0.0  0.999317
538     0  0.515549  0.484451       0  ...  0.958321   1.0    0.0  0.998320
539     0  0.504391  0.495609       1  ...  0.958815   1.0    0.0  0.998835
540     0  0.510763  0.489237       0  ...  0.957583   1.0    0.0  0.997552
541     0  0.500507  0.499493       0  ...  0.954424   1.0    0.0  0.994261

[5 rows x 10 columns]
2023-04-07 16:00:31,085:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505497  0.494503       0  ...  0.959278   1.0    0.0  0.997713
46     0  0.516040  0.483960       0  ...  0.958321   1.0    0.0  0.996408
47     0  0.505366  0.494634       1  ...  0.958815   1.0    0.0  0.999850
48     0  0.511236  0.488764       0  ...  0.957583   1.0    0.0  0.997959
49     0  0.500507  0.499493       0  ...  0.954424   1.0    0.0  0.994261

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230407   155000    155959  1680854399  27859.9  27822.1 -0.001357
2023-04-07 16:00:01,978:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19160 

self.closeSec=1680854999, self.tradeDate='20230407', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27822.1', self.close='27849.9'
2023-04-07 16:10:01,584:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680854999, self.tradeDate='20230407', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27822.1', self.close='27849.9'
2023-04-07 16:10:01,638:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230407   152000    152959  1680852599  27904.9  27914.2  0.000355
525  20230407   153000    153959  1680853199  27914.2  27883.2 -0.001111
526  20230407   154000    154959  1680853799  27883.1  27859.9 -0.000836
527  20230407   155000    155959  1680854399  27859.9  27822.1 -0.001357
528  20230407   160000    160959  1680854999  27822.1  27849.9  0.000999
2023-04-07 16:10:01,641:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19161 

self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27850', self.close='27856'
127.0.0.1 - - [07/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 16:20:08,297:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27850', self.close='27856'
2023-04-07 16:20:09,227:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230407   153000    153959  1680853199  27914.2  27883.2 -0.001111
526  20230407   154000    154959  1680853799  27883.1  27859.9 -0.000836
527  20230407   155000    155959  1680854399  27859.9  27822.1 -0.001357
528  20230407   160000    160959  1680854999  27822.1  27849.9  0.000999
529  20230407   161000    161959  1680855599    27850    27856  0.000219
2023-04-07 16:20:09,237:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230407   155000    155959  1680854399  27859.9  27822.1
2023-04-07 16:00:01,975:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19161 

self.closeSec=1680854999, self.tradeDate='20230407', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27822.1', self.close='27849.9'
127.0.0.1 - - [07/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-07 16:10:01,633:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680854999, self.tradeDate='20230407', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27822.1', self.close='27849.9'
2023-04-07 16:10:01,658:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230407   152000    152959  1680852599  27904.9  27914.2
17517  20230407   153000    153959  1680853199  27914.2  27883.2
17518  20230407   154000    154959  1680853799  27883.1  27859.9
17519  20230407   155000    155959  1680854399  27859.9  27822.1
17520  20230407   160000    160959  1680854999  27822.1  27849.9
2023-04-07 16:10:01,658:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19162 

self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27850', self.close='27856'
127.0.0.1 - - [07/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 16:20:11,884:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27850', self.close='27856'
2023-04-07 16:20:12,022:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230407   153000    153959  1680853199  27914.2  27883.2
17518  20230407   154000    154959  1680853799  27883.1  27859.9
17519  20230407   155000    155959  1680854399  27859.9  27822.1
17520  20230407   160000    160959  1680854999  27822.1  27849.9
17521  20230407   161000    161959  1680855599    27850    27856
2023-04-07 16:20:12,022:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230407   155000    155959  1680854399  27859.9  27822.1
2023-04-07 16:00:01,980:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19161 

self.closeSec=1680854999, self.tradeDate='20230407', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27822.1', self.close='27849.9'
2023-04-07 16:10:01,586:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680854999, self.tradeDate='20230407', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27822.1', self.close='27849.9'
127.0.0.1 - - [07/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-07 16:10:01,652:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230407   152000    152959  1680852599  27904.9  27914.2
12189  20230407   153000    153959  1680853199  27914.2  27883.2
12190  20230407   154000    154959  1680853799  27883.1  27859.9
12191  20230407   155000    155959  1680854399  27859.9  27822.1
12192  20230407   160000    160959  1680854999  27822.1  27849.9
2023-04-07 16:10:01,652:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19162 

self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27850', self.close='27856'
127.0.0.1 - - [07/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 16:20:11,344:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27850', self.close='27856'
2023-04-07 16:20:11,631:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230407   153000    153959  1680853199  27914.2  27883.2
12190  20230407   154000    154959  1680853799  27883.1  27859.9
12191  20230407   155000    155959  1680854399  27859.9  27822.1
12192  20230407   160000    160959  1680854999  27822.1  27849.9
12193  20230407   161000    161959  1680855599    27850    27856
2023-04-07 16:20:11,631:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33754
self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27858.8, self.close=27856.0, self.high=27871.1, self.low=27825.6, self.vol=1177.536, self.amt=32796394.4225 
127.0.0.1 - - [07/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-07 16:20:09,596:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230407   155500    155959  ...         0.0        0.0       0
5952  20230407   160000    160459  ...         0.0        0.0       0
5953  20230407   160500    160959  ...         0.0        0.0       0
5954  20230407   161000    161459  ...         0.0        0.0       0
5955  20230407   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 16:20:09,618:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680855599, self.tradeDate='20230407', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27858.8, self.close=27856.0, self.high=27871.1, self.low=27825.6, self.vol=1177.536, self.amt=32796394.4225, ukdf['pct'].iloc[-1]=-0.000104 , ukdf['amount'].iloc[-1]=32796394.4225, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33755
self.closeSec=1680855899, self.tradeDate='20230407', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27855.9, self.close=27872.5, self.high=27873.0, self.low=27837.1, self.vol=1010.746, self.amt=28155187.3718 
127.0.0.1 - - [07/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-07 16:25:01,714:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230407   160000    160459  ...         0.0        0.0       0
5953  20230407   160500    160959  ...         0.0        0.0       0
5954  20230407   161000    161459  ...         0.0        0.0       0
5955  20230407   161500    161959  ...         0.0        0.0       0
5956  20230407   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 16:25:01,715:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680855899, self.tradeDate='20230407', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27855.9, self.close=27872.5, self.high=27873.0, self.low=27837.1, self.vol=1010.746, self.amt=28155187.3718, ukdf['pct'].iloc[-1]=0.000592 , ukdf['amount'].iloc[-1]=28155187.3718, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230407   040000    075959  1680825599  ...    721  0.131946 -0.455118     NaN
722  20230407   080000    115959  1680839999  ...    722  0.122961 -0.495959     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '19335.0656', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28027.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [07/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=798
self.closeSec=1680854399, self.tradeDate='20230407', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28022.2, self.close=27822.1, self.high=28052.2, self.low=27755.0, self.vol=43961.294, self.amt=1226720936.0258 
2023-04-07 16:00:01,815:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680854399, self.tradeDate='20230407', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28022.2, self.close=27822.1, self.high=28052.2, self.low=27755.0, self.vol=43961.294, self.amt=1226720936.0258 
2023-04-07 16:00:01,886:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230406   200000    235959  ...  102413.306  2.862261e+09  0.005169
720  20230407   000000    035959  ...   45472.386  1.275123e+09 -0.002646
721  20230407   040000    075959  ...   34378.119  9.624497e+08  0.000636
722  20230407   080000    115959  ...   27954.246  7.831085e+08 -0.000021
723  20230407   120000    155959  ...   43961.294  1.226721e+09 -0.007141

[5 rows x 11 columns]
2023-04-07 16:00:03,879:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230406   200000    235959  1680796799  ...    719  0.143949 -0.399815     NaN
720  20230407   000000    035959  1680811199  ...    720  0.136631 -0.433788     NaN
721  20230407   040000    075959  1680825599  ...    721  0.131946 -0.455118     NaN
722  20230407   080000    115959  1680839999  ...    722  0.122961 -0.495959     NaN
723  20230407   120000    155959  1680854399  ...    723  0.137208 -0.434237     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '30044.3584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27822', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


