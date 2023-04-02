# 20230402 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36316
self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28376.6, self.close=28394.8, self.high=28397.9, self.low=28360.0, self.vol=1013.91, self.amt=28771842.8546 
127.0.0.1 - - [02/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 16:20:08,730:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230402   155500    155959  ...         0.0        0.0       0
5952  20230402   160000    160459  ...         0.0        0.0       0
5953  20230402   160500    160959  ...         0.0        0.0       0
5954  20230402   161000    161459  ...         0.0        0.0       0
5955  20230402   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 16:20:08,750:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28376.6, self.close=28394.8, self.high=28397.9, self.low=28360.0, self.vol=1013.91, self.amt=28771842.8546, ukdf['pct'].iloc[-1]=0.000641 , ukdf['amount'].iloc[-1]=28771842.8546, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-714066.4688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28395.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36317
self.closeSec=1680423899, self.tradeDate='20230402', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28394.8, self.close=28398.0, self.high=28400.7, self.low=28386.5, self.vol=379.828, self.amt=10785344.6844 
2023-04-02 16:25:01,589:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230402   160000    160459  ...         0.0        0.0       0
5953  20230402   160500    160959  ...         0.0        0.0       0
5954  20230402   161000    161459  ...         0.0        0.0       0
5955  20230402   161500    161959  ...         0.0        0.0       0
5956  20230402   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 16:25:01,591:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680423899, self.tradeDate='20230402', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28394.8, self.close=28398.0, self.high=28400.7, self.low=28386.5, self.vol=379.828, self.amt=10785344.6844, ukdf['pct'].iloc[-1]=0.000113 , ukdf['amount'].iloc[-1]=10785344.6844, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-714204.8736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28397.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28376.6, self.close=28394.8, self.high=28397.9, self.low=28360.0 
127.0.0.1 - - [02/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-02 16:20:06,409:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28376.6, self.close=28394.8, self.high=28397.9, self.low=28360.0   
2023-04-02 16:20:07,420:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230402   155500    155959  1680422399  ...  28392.0 -0.000306   1631    5
1632  20230402   160000    160459  1680422699  ...  28380.0 -0.000113   1632    0
1633  20230402   160500    160959  1680422999  ...  28398.0  0.000049   1633    1
1634  20230402   161000    161459  1680423299  ...  28369.3 -0.000806   1634    2
1635  20230402   161500    161959  1680423599  ...  28360.0  0.000641   1635    3

[5 rows x 11 columns]
2023-04-02 16:20:07,429:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=37, self.factor=0.48213122354743887, self.count=36883 

self.closeSec=1680423899, self.tradeDate='20230402', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28394.8, self.close=28398.0, self.high=28400.7, self.low=28386.5 
127.0.0.1 - - [02/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-02 16:25:01,531:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680423899, self.tradeDate='20230402', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28394.8, self.close=28398.0, self.high=28400.7, self.low=28386.5   
2023-04-02 16:25:01,560:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230402   160000    160459  1680422699  ...  28380.0 -0.000113   1632    0
1633  20230402   160500    160959  1680422999  ...  28398.0  0.000049   1633    1
1634  20230402   161000    161459  1680423299  ...  28369.3 -0.000806   1634    2
1635  20230402   161500    161959  1680423599  ...  28360.0  0.000641   1635    3
1636  20230402   162000    162459  1680423899  ...  28386.5  0.000113   1636    4

[5 rows x 11 columns]
2023-04-02 16:25:01,560:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-02 16:00:34,713:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230402    132959  28370.0  ...  52.916667  0.512642  0.479295
5787  20230402    135959  28412.3  ...  52.916667  0.521430  0.467781
5788  20230402    142959  28454.0  ...  52.500000  0.513261  0.463093
5789  20230402    145959  28418.1  ...  52.916667  0.519065  0.454144
5790  20230402    152959  28445.1  ...  53.333333  0.519130  0.445741

[5 rows x 33 columns]
0.522140221402214
acc is : 0.522140221402214
2023-04-02 16:00:34,874:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.535142  0.464858       1  ...  0.955276   1.0    0.0  1.015667
538     0  0.530046  0.469954       0  ...  0.954071   1.0    0.0  1.014385
539     0  0.515524  0.484476       1  ...  0.954980   1.0    0.0  1.015352
540     0  0.528764  0.471236       1  ...  0.954990   1.0    0.0  1.015363
541     0  0.530001  0.469999       0  ...  0.953510   1.0    0.0  1.013789

[5 rows x 10 columns]
2023-04-02 16:00:34,914:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.533930  0.466070       1  ...  0.955276   1.0    0.0  1.015518
46     0  0.527624  0.472376       0  ...  0.954071   1.0    0.0  1.011256
47     0  0.513825  0.486175       1  ...  0.954980   1.0    0.0  1.012598
48     0  0.527693  0.472307       1  ...  0.954990   1.0    0.0  1.013540
49     0  0.530001  0.469999       0  ...  0.953510   1.0    0.0  1.013789

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230402   155000    155959  1680422399    28430  28401.3 -0.001009
2023-04-02 16:00:02,200:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18440 

self.closeSec=1680422999, self.tradeDate='20230402', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28401.3', self.close='28399.5'
2023-04-02 16:10:01,595:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680422999, self.tradeDate='20230402', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28401.3', self.close='28399.5'
127.0.0.1 - - [02/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-02 16:10:01,620:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230402   152000    152959  1680420599  28440.6  28445.4  0.000169
525  20230402   153000    153959  1680421199  28445.5    28440 -0.000190
526  20230402   154000    154959  1680421799    28440    28430 -0.000352
527  20230402   155000    155959  1680422399    28430  28401.3 -0.001009
528  20230402   160000    160959  1680422999  28401.3  28399.5 -0.000063
2023-04-02 16:10:01,620:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18441 

self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28399.5', self.close='28394.8'
127.0.0.1 - - [02/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 16:20:07,201:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28399.5', self.close='28394.8'
2023-04-02 16:20:08,009:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230402   153000    153959  1680421199  28445.5    28440 -0.000190
526  20230402   154000    154959  1680421799    28440    28430 -0.000352
527  20230402   155000    155959  1680422399    28430  28401.3 -0.001009
528  20230402   160000    160959  1680422999  28401.3  28399.5 -0.000063
529  20230402   161000    161959  1680423599  28399.5  28394.8 -0.000165
2023-04-02 16:20:08,010:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230402   155000    155959  1680422399    28430  28401.3
2023-04-02 16:00:02,249:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18441 

self.closeSec=1680422999, self.tradeDate='20230402', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28401.3', self.close='28399.5'
2023-04-02 16:10:01,623:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680422999, self.tradeDate='20230402', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28401.3', self.close='28399.5'
2023-04-02 16:10:01,670:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230402   152000    152959  1680420599  28440.6  28445.4
17517  20230402   153000    153959  1680421199  28445.5    28440
17518  20230402   154000    154959  1680421799    28440    28430
17519  20230402   155000    155959  1680422399    28430  28401.3
17520  20230402   160000    160959  1680422999  28401.3  28399.5
2023-04-02 16:10:01,670:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18442 

self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28399.5', self.close='28394.8'
127.0.0.1 - - [02/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 16:20:10,014:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28399.5', self.close='28394.8'
2023-04-02 16:20:10,141:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230402   153000    153959  1680421199  28445.5    28440
17518  20230402   154000    154959  1680421799    28440    28430
17519  20230402   155000    155959  1680422399    28430  28401.3
17520  20230402   160000    160959  1680422999  28401.3  28399.5
17521  20230402   161000    161959  1680423599  28399.5  28394.8
2023-04-02 16:20:10,142:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230402   155000    155959  1680422399    28430  28401.3
2023-04-02 16:00:02,180:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18441 

self.closeSec=1680422999, self.tradeDate='20230402', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28401.3', self.close='28399.5'
2023-04-02 16:10:01,606:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680422999, self.tradeDate='20230402', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28401.3', self.close='28399.5'
127.0.0.1 - - [02/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-02 16:10:01,650:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230402   152000    152959  1680420599  28440.6  28445.4
12189  20230402   153000    153959  1680421199  28445.5    28440
12190  20230402   154000    154959  1680421799    28440    28430
12191  20230402   155000    155959  1680422399    28430  28401.3
12192  20230402   160000    160959  1680422999  28401.3  28399.5
2023-04-02 16:10:01,651:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18442 

self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28399.5', self.close='28394.8'
127.0.0.1 - - [02/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 16:20:09,591:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28399.5', self.close='28394.8'
2023-04-02 16:20:09,850:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230402   153000    153959  1680421199  28445.5    28440
12190  20230402   154000    154959  1680421799    28440    28430
12191  20230402   155000    155959  1680422399    28430  28401.3
12192  20230402   160000    160959  1680422999  28401.3  28399.5
12193  20230402   161000    161959  1680423599  28399.5  28394.8
2023-04-02 16:20:09,850:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32314
self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28376.6, self.close=28394.8, self.high=28397.9, self.low=28360.0, self.vol=1013.91, self.amt=28771842.8546 
127.0.0.1 - - [02/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-02 16:20:07,761:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230402   155500    155959  ...         0.0        0.0       0
5952  20230402   160000    160459  ...         0.0        0.0       0
5953  20230402   160500    160959  ...         0.0        0.0       0
5954  20230402   161000    161459  ...         0.0        0.0       0
5955  20230402   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 16:20:07,789:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680423599, self.tradeDate='20230402', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28376.6, self.close=28394.8, self.high=28397.9, self.low=28360.0, self.vol=1013.91, self.amt=28771842.8546, ukdf['pct'].iloc[-1]=0.000641 , ukdf['amount'].iloc[-1]=28771842.8546, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32315
self.closeSec=1680423899, self.tradeDate='20230402', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28394.8, self.close=28398.0, self.high=28400.7, self.low=28386.5, self.vol=379.828, self.amt=10785344.6844 
127.0.0.1 - - [02/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-02 16:25:01,590:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230402   160000    160459  ...         0.0        0.0       0
5953  20230402   160500    160959  ...         0.0        0.0       0
5954  20230402   161000    161459  ...         0.0        0.0       0
5955  20230402   161500    161959  ...         0.0        0.0       0
5956  20230402   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 16:25:01,590:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680423899, self.tradeDate='20230402', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28394.8, self.close=28398.0, self.high=28400.7, self.low=28386.5, self.vol=379.828, self.amt=10785344.6844, ukdf['pct'].iloc[-1]=0.000113 , ukdf['amount'].iloc[-1]=10785344.6844, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230401   200000    235959  ...  49661.974  1.407624e+09  0.000765
720  20230402   000000    035959  ...  28679.320  8.133134e+08 -0.000666
721  20230402   040000    075959  ...  36734.183  1.046074e+09  0.002661
722  20230402   080000    115959  ...  28921.926  8.218985e+08  0.000675
723  20230402   120000    155959  ...  21969.846  6.245725e+08 -0.002168

[5 rows x 11 columns]
2023-04-02 16:00:04,961:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230401   200000    235959  1680364799  ...    719  0.553578  0.328353     NaN
720  20230402   000000    035959  1680379199  ...    720  0.429529 -0.014972     NaN
721  20230402   040000    075959  1680393599  ...    721  0.388136 -0.118582     NaN
722  20230402   080000    115959  1680407999  ...    722  0.246313 -0.513289     NaN
723  20230402   120000    155959  1680422399  ...    723  0.086417 -0.958243    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '-4944.1044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28401.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '-4944.1044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28401.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-04-02 16:00:10,685:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1483827.9389481', 'total': '1483827.9389481', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-04-02 16:00:10,872:INFO:s_rsrs:main.py:269:openSell:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 52.088, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42099F1680422410867I0L65'}
2023-04-02 16:00:10,900:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:4021600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230402, closeTime:155959, close:28401.3, sign:-1, total:1483827.9389481, side:sell  
127.0.0.1 - - [02/Apr/2023 16:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Apr/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-04-02 16:00:10,909:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42098F1680422405581I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680422405677053, 'quantity': '52.153', 'price': '28401.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680422405278, 'updatetime': 1680422405677, 'tradetype': 'usdt', 'selfid': 42098, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680422405677, 'clientorderid': '42098F1680422405581I0L65', 'price': '28401.2', 'quantity': '52.153', 'commission': '1481.2077836', 'commissionasset': 'USDT', 'tradetime': 1680422405677, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680422405677}], 'gatetype': 'simulator', 'handletime': 0}
2023-04-02 16:00:10,910:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42098F1680422405581I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680422405677053, 'quantity': '52.153', 'price': '28401.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680422405278, 'updatetime': 1680422405677, 'tradetype': 'usdt', 'selfid': 42098, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680422405677, 'clientorderid': '42098F1680422405581I0L65', 'price': '28401.2', 'quantity': '52.153', 'commission': '1481.2077836', 'commissionasset': 'USDT', 'tradetime': 1680422405677, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680422405677}], 'gatetype': 'simulator', 'handletime': 0}
2023-04-02 16:00:11,007:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42099F1680422410867I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680422410965795, 'quantity': '52.088', 'price': '28398.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680422410698, 'updatetime': 1680422410965, 'tradetype': 'usdt', 'selfid': 42099, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680422410965, 'clientorderid': '42099F1680422410867I0L65', 'price': '28398.8', 'quantity': '52.088', 'commission': '1479.2366944', 'commissionasset': 'USDT', 'tradetime': 1680422410965, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680422410965}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Apr/2023 16:00:11] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Apr/2023 16:00:11] "POST / HTTP/1.1" 200 -
2023-04-02 16:00:11,311:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42099F1680422410867I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680422410965795, 'quantity': '52.088', 'price': '28398.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680422410698, 'updatetime': 1680422410965, 'tradetype': 'usdt', 'selfid': 42099, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680422410965, 'clientorderid': '42099F1680422410867I0L65', 'price': '28398.8', 'quantity': '52.088', 'commission': '1479.2366944', 'commissionasset': 'USDT', 'tradetime': 1680422410965, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680422410965}], 'gatetype': 'simulator', 'handletime': 0}


