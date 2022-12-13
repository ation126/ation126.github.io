# 20221213 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4634
self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17161.5, self.close=17149.0, self.high=17161.5, self.low=17147.3, self.vol=737.623, self.amt=12651507.3485 
127.0.0.1 - - [13/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-13 16:10:01,475:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221213   154500    154959  ...         0.0        0.0       0
5950  20221213   155000    155459  ...         0.0        0.0       0
5951  20221213   155500    155959  ...         0.0        0.0       0
5952  20221213   160000    160459  ...         0.0        0.0       0
5953  20221213   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-13 16:10:01,476:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17161.5, self.close=17149.0, self.high=17161.5, self.low=17147.3, self.vol=737.623, self.amt=12651507.3485, ukdf['pct'].iloc[-1]=-0.000723 , ukdf['amount'].iloc[-1]=12651507.3485, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-37369.30992592992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17150.30023142', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4635
self.closeSec=1670919299, self.tradeDate='20221213', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17149.0, self.close=17150.3, self.high=17152.4, self.low=17148.9, self.vol=359.185, self.amt=6160283.729 
127.0.0.1 - - [13/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-13 16:15:00,561:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221213   155000    155459  ...         0.0        0.0       0
5951  20221213   155500    155959  ...         0.0        0.0       0
5952  20221213   160000    160459  ...         0.0        0.0       0
5953  20221213   160500    160959  ...         0.0        0.0       0
5954  20221213   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-13 16:15:00,561:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670919299, self.tradeDate='20221213', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17149.0, self.close=17150.3, self.high=17152.4, self.low=17148.9, self.vol=359.185, self.amt=6160283.729, ukdf['pct'].iloc[-1]=7.6e-05 , ukdf['amount'].iloc[-1]=6160283.729, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-37375.3136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17150.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.4039995287676567, self.count=5200 

self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17161.5, self.close=17149.0, self.high=17161.5, self.low=17147.3 
2022-12-13 16:10:01,422:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17161.5, self.close=17149.0, self.high=17161.5, self.low=17147.3   
2022-12-13 16:10:01,456:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221213   154500    154959  1670917799  ...  17149.2  0.000676   1629    3
1630  20221213   155000    155459  1670918099  ...  17153.0 -0.000501   1630    4
1631  20221213   155500    155959  1670918399  ...  17145.2  0.000082   1631    5
1632  20221213   160000    160459  1670918699  ...  17154.5  0.000256   1632    0
1633  20221213   160500    160959  1670918999  ...  17147.3 -0.000723   1633    1

[5 rows x 11 columns]
2022-12-13 16:10:01,456:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.4039995287676567, self.count=5201 

self.closeSec=1670919299, self.tradeDate='20221213', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17149.0, self.close=17150.3, self.high=17152.4, self.low=17148.9 
2022-12-13 16:15:00,531:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670919299, self.tradeDate='20221213', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17149.0, self.close=17150.3, self.high=17152.4, self.low=17148.9   
2022-12-13 16:15:00,541:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221213   155000    155459  1670918099  ...  17153.0 -0.000501   1630    4
1631  20221213   155500    155959  1670918399  ...  17145.2  0.000082   1631    5
1632  20221213   160000    160459  1670918699  ...  17154.5  0.000256   1632    0
1633  20221213   160500    160959  1670918999  ...  17147.3 -0.000723   1633    1
1634  20221213   161000    161459  1670919299  ...  17148.9  0.000076   1634    2

[5 rows x 11 columns]
2022-12-13 16:15:00,541:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-13 16:00:17,125:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221213    132959  17161.1  ...  54.166667  0.564223  0.323120
5787  20221213    135959  17167.2  ...  54.166667  0.572251  0.313390
5788  20221213    142959  17179.3  ...  54.583333  0.575275  0.303284
5789  20221213    145959  17185.2  ...  54.166667  0.542701  0.302382
5790  20221213    152959  17143.8  ...  53.750000  0.533440  0.304104

[5 rows x 33 columns]
0.5811808118081181
acc is : 0.5811808118081181
2022-12-13 16:00:17,225:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.501356  0.498644       1  ...  0.981463   1.0    0.0  1.008897
538     0  0.504112  0.495888       1  ...  0.981749   1.0    0.0  1.009190
539     0  0.501912  0.498088       0  ...  0.979372   1.0    0.0  1.006747
540     1  0.485916  0.514084       0  ...  0.978658   1.0    0.0  1.006013
541     1  0.490805  0.509195       1  ...  0.980132   1.0    0.0  1.007528

[5 rows x 10 columns]
2022-12-13 16:00:17,251:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501354  0.498646       1  ...  0.981463   1.0    0.0  1.013276
46     0  0.504587  0.495413       1  ...  0.981749   1.0    0.0  1.014415
47     0  0.501900  0.498100       0  ...  0.979372   1.0    0.0  1.010170
48     1  0.486408  0.513592       0  ...  0.978658   1.0    0.0  1.010017
49     1  0.490805  0.509195       1  ...  0.980132   1.0    0.0  1.007528

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-2108.6262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17157', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221213   154000    154959  1670917799  17130.8  17164.2  0.002090
2022-12-13 15:50:00,580:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2599 

self.closeSec=1670918399, self.tradeDate='20221213', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17164.2', self.close='17157'
2022-12-13 16:00:01,155:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670918399, self.tradeDate='20221213', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17164.2', self.close='17157'
2022-12-13 16:00:01,195:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221213   151000    151959  1670915999  17133.2  17093.7 -0.002311
524  20221213   152000    152959  1670916599  17094.9  17131.1  0.002188
525  20221213   153000    153959  1670917199  17131.2  17128.4 -0.000158
526  20221213   154000    154959  1670917799  17130.8  17164.2  0.002090
527  20221213   155000    155959  1670918399  17164.2    17157 -0.000419
2022-12-13 16:00:01,195:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2600 

self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17156.9', self.close='17149'
2022-12-13 16:10:01,506:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17156.9', self.close='17149'
2022-12-13 16:10:01,520:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221213   152000    152959  1670916599  17094.9  17131.1  0.002188
525  20221213   153000    153959  1670917199  17131.2  17128.4 -0.000158
526  20221213   154000    154959  1670917799  17130.8  17164.2  0.002090
527  20221213   155000    155959  1670918399  17164.2    17157 -0.000419
528  20221213   160000    160959  1670918999  17156.9    17149 -0.000466
2022-12-13 16:10:01,520:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221213   154000    154959  1670917799  17130.8  17164.2
2022-12-13 15:50:00,549:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2600 

self.closeSec=1670918399, self.tradeDate='20221213', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17164.2', self.close='17157'
2022-12-13 16:00:01,140:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670918399, self.tradeDate='20221213', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17164.2', self.close='17157'
2022-12-13 16:00:01,166:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221213   151000    151959  1670915999  17133.2  17093.7
17516  20221213   152000    152959  1670916599  17094.9  17131.1
17517  20221213   153000    153959  1670917199  17131.2  17128.4
17518  20221213   154000    154959  1670917799  17130.8  17164.2
17519  20221213   155000    155959  1670918399  17164.2    17157
2022-12-13 16:00:01,166:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2601 

self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17156.9', self.close='17149'
2022-12-13 16:10:01,545:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17156.9', self.close='17149'
2022-12-13 16:10:01,568:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221213   152000    152959  1670916599  17094.9  17131.1
17517  20221213   153000    153959  1670917199  17131.2  17128.4
17518  20221213   154000    154959  1670917799  17130.8  17164.2
17519  20221213   155000    155959  1670918399  17164.2    17157
17520  20221213   160000    160959  1670918999  17156.9    17149
2022-12-13 16:10:01,568:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221213   154000    154959  1670917799  17130.8  17164.2
2022-12-13 15:50:00,559:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2600 

self.closeSec=1670918399, self.tradeDate='20221213', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17164.2', self.close='17157'
127.0.0.1 - - [13/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-13 16:00:01,120:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670918399, self.tradeDate='20221213', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17164.2', self.close='17157'
2022-12-13 16:00:01,133:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221213   151000    151959  1670915999  17133.2  17093.7
12188  20221213   152000    152959  1670916599  17094.9  17131.1
12189  20221213   153000    153959  1670917199  17131.2  17128.4
12190  20221213   154000    154959  1670917799  17130.8  17164.2
12191  20221213   155000    155959  1670918399  17164.2    17157
2022-12-13 16:00:01,133:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [13/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2601 

self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17156.9', self.close='17149'
2022-12-13 16:10:01,539:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17156.9', self.close='17149'
2022-12-13 16:10:01,559:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221213   152000    152959  1670916599  17094.9  17131.1
12189  20221213   153000    153959  1670917199  17131.2  17128.4
12190  20221213   154000    154959  1670917799  17130.8  17164.2
12191  20221213   155000    155959  1670918399  17164.2    17157
12192  20221213   160000    160959  1670918999  17156.9    17149
2022-12-13 16:10:01,560:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=632
self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17161.5, self.close=17149.0, self.high=17161.5, self.low=17147.3, self.vol=737.623, self.amt=12651507.3485 
2022-12-13 16:10:01,477:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221213   154500    154959  ...    0.444969   0.275970       0
5950  20221213   155000    155459  ...    0.444623   0.276111       0
5951  20221213   155500    155959  ...    0.444277   0.276252       0
5952  20221213   160000    160459  ...    0.443933   0.276393       0
5953  20221213   160500    160959  ...    0.443588   0.276534       0

[5 rows x 18 columns]
2022-12-13 16:10:01,477:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670918999, self.tradeDate='20221213', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17161.5, self.close=17149.0, self.high=17161.5, self.low=17147.3, self.vol=737.623, self.amt=12651507.3485, ukdf['pct'].iloc[-1]=-0.000723 , ukdf['amount'].iloc[-1]=12651507.3485, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.4435876411172554, signal=0, value_std=0.27653359511254516 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [13/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=633
self.closeSec=1670919299, self.tradeDate='20221213', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17149.0, self.close=17150.3, self.high=17152.4, self.low=17148.9, self.vol=359.185, self.amt=6160283.729 
2022-12-13 16:15:00,590:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221213   155000    155459  ...    0.444623   0.276111       0
5951  20221213   155500    155959  ...    0.444277   0.276252       0
5952  20221213   160000    160459  ...    0.443933   0.276393       0
5953  20221213   160500    160959  ...    0.443588   0.276534       0
5954  20221213   161000    161459  ...    0.443241   0.276672       0

[5 rows x 18 columns]
2022-12-13 16:15:00,590:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670919299, self.tradeDate='20221213', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17149.0, self.close=17150.3, self.high=17152.4, self.low=17148.9, self.vol=359.185, self.amt=6160283.729, ukdf['pct'].iloc[-1]=7.6e-05 , ukdf['amount'].iloc[-1]=6160283.729, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.44324093728167246, signal=0, value_std=0.2766721982423556 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221213   040000    075959  1670889599  ...    721  0.362269 -0.663837    -1.0
722  20221213   080000    115959  1670903999  ...    722  0.345440 -0.749277    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.578', 'enterprice': '16978.7', 'countrevence': '0', 'unrealprofit': '-9630.2232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17143.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [13/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=993583.7103114001, self.flagDict['side']='sell', self.tradeCount=5, self.count=108
self.closeSec=1670918399, self.tradeDate='20221213', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17143.1, self.close=17157.0, self.high=17197.9, self.low=17076.0, self.vol=55625.343, self.amt=953614926.6349 
2022-12-13 16:00:01,021:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670918399, self.tradeDate='20221213', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17143.1, self.close=17157.0, self.high=17197.9, self.low=17076.0, self.vol=55625.343, self.amt=953614926.6349 
2022-12-13 16:00:01,080:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221212   200000    235959  ...  71821.147  1.219596e+09  0.001302
720  20221213   000000    035959  ...  25169.941  4.279414e+08  0.002106
721  20221213   040000    075959  ...  82215.013  1.409712e+09  0.009644
722  20221213   080000    115959  ...  36929.287  6.334437e+08 -0.003302
723  20221213   120000    155959  ...  55625.343  9.536149e+08  0.000805

[5 rows x 11 columns]
2022-12-13 16:00:02,422:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221212   200000    235959  1670860799  ...    719  0.200578 -1.259185    -1.0
720  20221213   000000    035959  1670875199  ...    720  0.151814 -1.462439    -1.0
721  20221213   040000    075959  1670889599  ...    721  0.362269 -0.663837    -1.0
722  20221213   080000    115959  1670903999  ...    722  0.345440 -0.749277    -1.0
723  20221213   120000    155959  1670918399  ...    723  0.315132 -0.874432    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.578', 'enterprice': '16978.7', 'countrevence': '0', 'unrealprofit': '-10444.4574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17157', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


