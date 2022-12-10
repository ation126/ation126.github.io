# 20221210 16:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [10/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3770
self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17145.7, self.close=17140.0, self.high=17145.8, self.low=17140.0, self.vol=243.288, self.amt=4170599.2888 
2022-12-10 16:10:01,468:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221210   154500    154959  ...         0.0        0.0       0
5950  20221210   155000    155459  ...         0.0        0.0       0
5951  20221210   155500    155959  ...         0.0        0.0       0
5952  20221210   160000    160459  ...         0.0        0.0       0
5953  20221210   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-10 16:10:01,470:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17145.7, self.close=17140.0, self.high=17145.8, self.low=17140.0, self.vol=243.288, self.amt=4170599.2888, ukdf['pct'].iloc[-1]=-0.000338 , ukdf['amount'].iloc[-1]=4170599.2888, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-36755.5008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17140.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3771
self.closeSec=1670660099, self.tradeDate='20221210', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17140.1, self.close=17142.0, self.high=17142.4, self.low=17140.0, self.vol=198.5, self.amt=3402610.9768 
127.0.0.1 - - [10/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-10 16:15:00,586:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221210   155000    155459  ...         0.0        0.0       0
5951  20221210   155500    155959  ...         0.0        0.0       0
5952  20221210   160000    160459  ...         0.0        0.0       0
5953  20221210   160500    160959  ...         0.0        0.0       0
5954  20221210   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-10 16:15:00,586:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670660099, self.tradeDate='20221210', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17140.1, self.close=17142.0, self.high=17142.4, self.low=17140.0, self.vol=198.5, self.amt=3402610.9768, ukdf['pct'].iloc[-1]=0.000117 , ukdf['amount'].iloc[-1]=3402610.9768, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-36869.8352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17142', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17145.7, self.close=17140.0, self.high=17145.8, self.low=17140.0 
2022-12-10 16:10:01,416:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17145.7, self.close=17140.0, self.high=17145.8, self.low=17140.0   
127.0.0.1 - - [10/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-10 16:10:01,448:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221210   154500    154959  1670658599  ...  17144.1  0.000373   1629    3
1630  20221210   155000    155459  1670658899  ...  17146.0 -0.000338   1630    4
1631  20221210   155500    155959  1670659199  ...  17143.9 -0.000082   1631    5
1632  20221210   160000    160459  1670659499  ...  17144.5  0.000070   1632    0
1633  20221210   160500    160959  1670659799  ...  17140.0 -0.000338   1633    1

[5 rows x 11 columns]
2022-12-10 16:10:01,448:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=31, self.factor=0.5199700669722268, self.count=4337 

self.closeSec=1670660099, self.tradeDate='20221210', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17140.1, self.close=17142.0, self.high=17142.4, self.low=17140.0 
2022-12-10 16:15:00,519:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670660099, self.tradeDate='20221210', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17140.1, self.close=17142.0, self.high=17142.4, self.low=17140.0   
2022-12-10 16:15:00,555:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221210   155000    155459  1670658899  ...  17146.0 -0.000338   1630    4
1631  20221210   155500    155959  1670659199  ...  17143.9 -0.000082   1631    5
1632  20221210   160000    160459  1670659499  ...  17144.5  0.000070   1632    0
1633  20221210   160500    160959  1670659799  ...  17140.0 -0.000338   1633    1
1634  20221210   161000    161459  1670660099  ...  17140.0  0.000117   1634    2

[5 rows x 11 columns]
2022-12-10 16:15:00,555:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-10 16:00:18,675:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221210    132959  17143.1  ...  55.833333  0.524706  0.678367
5787  20221210    135959  17133.6  ...  55.416667  0.519224  0.684217
5788  20221210    142959  17125.2  ...  55.833333  0.532903  0.684827
5789  20221210    145959  17148.2  ...  55.416667  0.527728  0.687034
5790  20221210    152959  17140.3  ...  55.416667  0.537605  0.685563

[5 rows x 33 columns]
0.5830258302583026
acc is : 0.5830258302583026
2022-12-10 16:00:18,775:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493203  0.506797       0  ...  0.976238   1.0    0.0  1.059124
538     1  0.491675  0.508325       1  ...  0.977538   1.0    0.0  1.060534
539     0  0.500103  0.499897       0  ...  0.977099   1.0    0.0  1.060058
540     1  0.492679  0.507321       1  ...  0.978045   1.0    0.0  1.061085
541     0  0.500115  0.499885       0  ...  0.977338   1.0    0.0  1.060318

[5 rows x 10 columns]
2022-12-10 16:00:18,795:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493152  0.506848       0  ...  0.976238   1.0    0.0  1.056387
46     1  0.491145  0.508855       1  ...  0.977538   1.0    0.0  1.056581
47     0  0.500073  0.499927       0  ...  0.977099   1.0    0.0  1.057749
48     1  0.492952  0.507048       1  ...  0.978045   1.0    0.0  1.063505
49     0  0.500115  0.499885       0  ...  0.977338   1.0    0.0  1.060318

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-2567.39765110242', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17144.85965622', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221210   154000    154959  1670658599    17143  17151.8  0.000507
2022-12-10 15:50:00,578:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2167 

self.closeSec=1670659199, self.tradeDate='20221210', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17151.8', self.close='17144.6'
127.0.0.1 - - [10/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
2022-12-10 16:00:00,981:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670659199, self.tradeDate='20221210', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17151.8', self.close='17144.6'
2022-12-10 16:00:01,005:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221210   151000    151959  1670656799  17140.3    17146  0.000333
524  20221210   152000    152959  1670657399    17146    17157  0.000642
525  20221210   153000    153959  1670657999    17157  17143.1 -0.000810
526  20221210   154000    154959  1670658599    17143  17151.8  0.000507
527  20221210   155000    155959  1670659199  17151.8  17144.6 -0.000420
2022-12-10 16:00:01,014:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2168 

self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17144.5', self.close='17140'
2022-12-10 16:10:01,499:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17144.5', self.close='17140'
127.0.0.1 - - [10/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-10 16:10:01,512:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221210   152000    152959  1670657399    17146    17157  0.000642
525  20221210   153000    153959  1670657999    17157  17143.1 -0.000810
526  20221210   154000    154959  1670658599    17143  17151.8  0.000507
527  20221210   155000    155959  1670659199  17151.8  17144.6 -0.000420
528  20221210   160000    160959  1670659799  17144.5    17140 -0.000268
2022-12-10 16:10:01,513:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221210   154000    154959  1670658599    17143  17151.8
2022-12-10 15:50:00,578:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2168 

self.closeSec=1670659199, self.tradeDate='20221210', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17151.8', self.close='17144.6'
2022-12-10 16:00:00,952:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670659199, self.tradeDate='20221210', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17151.8', self.close='17144.6'
2022-12-10 16:00:01,018:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221210   151000    151959  1670656799  17140.3    17146
17516  20221210   152000    152959  1670657399    17146    17157
17517  20221210   153000    153959  1670657999    17157  17143.1
17518  20221210   154000    154959  1670658599    17143  17151.8
17519  20221210   155000    155959  1670659199  17151.8  17144.6
2022-12-10 16:00:01,018:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2169 

self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17144.5', self.close='17140'
127.0.0.1 - - [10/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-10 16:10:01,536:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17144.5', self.close='17140'
2022-12-10 16:10:01,543:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221210   152000    152959  1670657399    17146    17157
17517  20221210   153000    153959  1670657999    17157  17143.1
17518  20221210   154000    154959  1670658599    17143  17151.8
17519  20221210   155000    155959  1670659199  17151.8  17144.6
17520  20221210   160000    160959  1670659799  17144.5    17140
2022-12-10 16:10:01,543:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221210   154000    154959  1670658599    17143  17151.8
2022-12-10 15:50:00,583:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2168 

self.closeSec=1670659199, self.tradeDate='20221210', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17151.8', self.close='17144.6'
2022-12-10 16:00:00,963:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670659199, self.tradeDate='20221210', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17151.8', self.close='17144.6'
2022-12-10 16:00:01,016:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221210   151000    151959  1670656799  17140.3    17146
12188  20221210   152000    152959  1670657399    17146    17157
12189  20221210   153000    153959  1670657999    17157  17143.1
12190  20221210   154000    154959  1670658599    17143  17151.8
12191  20221210   155000    155959  1670659199  17151.8  17144.6
2022-12-10 16:00:01,016:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2169 

self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17144.5', self.close='17140'
2022-12-10 16:10:01,501:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670659799, self.tradeDate='20221210', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17144.5', self.close='17140'
127.0.0.1 - - [10/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-10 16:10:01,520:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221210   152000    152959  1670657399    17146    17157
12189  20221210   153000    153959  1670657999    17157  17143.1
12190  20221210   154000    154959  1670658599    17143  17151.8
12191  20221210   155000    155959  1670659199  17151.8  17144.6
12192  20221210   160000    160959  1670659799  17144.5    17140
2022-12-10 16:10:01,520:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221210   040000    075959  1670630399  ...    721  0.608464  0.371435     NaN
722  20221210   080000    115959  1670644799  ...    722  0.581691  0.273686     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-9467.453', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17140', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [10/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=90
self.closeSec=1670659199, self.tradeDate='20221210', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17140.0, self.close=17144.6, self.high=17170.2, self.low=17122.0, self.vol=17751.416, self.amt=304324456.7822 
2022-12-10 16:00:00,864:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670659199, self.tradeDate='20221210', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17140.0, self.close=17144.6, self.high=17170.2, self.low=17122.0, self.vol=17751.416, self.amt=304324456.7822 
2022-12-10 16:00:00,909:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221209   200000    235959  ...  130054.486  2.233482e+09 -0.003563
720  20221210   000000    035959  ...   28838.384  4.944049e+08 -0.002068
721  20221210   040000    075959  ...   31474.007  5.384585e+08 -0.000753
722  20221210   080000    115959  ...   19761.717  3.386550e+08  0.001051
723  20221210   120000    155959  ...   17751.416  3.043245e+08  0.000268

[5 rows x 11 columns]
2022-12-10 16:00:02,145:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221209   200000    235959  1670601599  ...    719  0.637512  0.481243     NaN
720  20221210   000000    035959  1670615999  ...    720  0.584356  0.289338     NaN
721  20221210   040000    075959  1670630399  ...    721  0.608464  0.371435     NaN
722  20221210   080000    115959  1670644799  ...    722  0.581691  0.273686     NaN
723  20221210   120000    155959  1670659199  ...    723  0.558600  0.190165     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-9156.96223766994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17145.29648873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


