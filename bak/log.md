# 20230119 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15290
self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20826.9, self.close=20842.8, self.high=20844.5, self.low=20817.7, self.vol=912.58, self.amt=19012274.0751 
127.0.0.1 - - [19/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 16:10:01,497:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230119   154500    154959  ...         0.0        0.0       0
5950  20230119   155000    155459  ...         0.0        0.0       0
5951  20230119   155500    155959  ...         0.0        0.0       0
5952  20230119   160000    160459  ...         0.0        0.0       0
5953  20230119   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 16:10:01,497:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20826.9, self.close=20842.8, self.high=20844.5, self.low=20817.7, self.vol=912.58, self.amt=19012274.0751, ukdf['pct'].iloc[-1]=0.000768 , ukdf['amount'].iloc[-1]=19012274.0751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-259534.1434915288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20842.21783255', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15291
self.closeSec=1674116099, self.tradeDate='20230119', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20842.9, self.close=20833.0, self.high=20848.0, self.low=20819.1, self.vol=860.698, self.amt=17933464.3029 
2023-01-19 16:15:00,795:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230119   155000    155459  ...         0.0        0.0       0
5951  20230119   155500    155959  ...         0.0        0.0       0
5952  20230119   160000    160459  ...         0.0        0.0       0
5953  20230119   160500    160959  ...         0.0        0.0       0
5954  20230119   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 16:15:00,796:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674116099, self.tradeDate='20230119', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20842.9, self.close=20833.0, self.high=20848.0, self.low=20819.1, self.vol=860.698, self.amt=17933464.3029, ukdf['pct'].iloc[-1]=-0.00047 , ukdf['amount'].iloc[-1]=17933464.3029, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-259014.35803510752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20833.58007902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20826.9, self.close=20842.8, self.high=20844.5, self.low=20817.7 
2023-01-19 16:10:01,421:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20826.9, self.close=20842.8, self.high=20844.5, self.low=20817.7   
127.0.0.1 - - [19/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 16:10:01,461:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230119   154500    154959  1674114599  ...  20821.2 -0.000034   1629    3
1630  20230119   155000    155459  1674114899  ...  20820.8 -0.000048   1630    4
1631  20230119   155500    155959  1674115199  ...  20810.5 -0.000279   1631    5
1632  20230119   160000    160459  1674115499  ...  20812.5  0.000418   1632    0
1633  20230119   160500    160959  1674115799  ...  20817.7  0.000768   1633    1

[5 rows x 11 columns]
2023-01-19 16:10:01,461:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6456986670912439, self.count=15857 

self.closeSec=1674116099, self.tradeDate='20230119', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20842.9, self.close=20833.0, self.high=20848.0, self.low=20819.1 
2023-01-19 16:15:00,684:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674116099, self.tradeDate='20230119', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20842.9, self.close=20833.0, self.high=20848.0, self.low=20819.1   
2023-01-19 16:15:00,707:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230119   155000    155459  1674114899  ...  20820.8 -0.000048   1630    4
1631  20230119   155500    155959  1674115199  ...  20810.5 -0.000279   1631    5
1632  20230119   160000    160459  1674115499  ...  20812.5  0.000418   1632    0
1633  20230119   160500    160959  1674115799  ...  20817.7  0.000768   1633    1
1634  20230119   161000    161459  1674116099  ...  20819.1 -0.000470   1634    2

[5 rows x 11 columns]
2023-01-19 16:15:00,707:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-19 16:00:34,017:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230119    132959  20812.5  ...  51.666667  0.462733  0.666397
5787  20230119    135959  20820.6  ...  51.250000  0.461689  0.666403
5788  20230119    142959  20814.8  ...  51.250000  0.465108  0.665574
5789  20230119    145959  20831.1  ...  50.833333  0.464753  0.664898
5790  20230119    152959  20828.6  ...  50.833333  0.464505  0.664335

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2023-01-19 16:00:34,188:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502223  0.497777       0  ...  1.098621  -1.0    0.0  1.230239
538     1  0.496050  0.503950       1  ...  1.097771  -1.0    0.0  1.231190
539     0  0.507082  0.492918       0  ...  1.097872  -1.0    0.0  1.231078
540     0  0.500390  0.499610       0  ...  1.097940  -1.0    0.0  1.231001
541     0  0.505375  0.494625       0  ...  1.098451  -1.0    0.0  1.230428

[5 rows x 10 columns]
2023-01-19 16:00:34,228:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502322  0.497678       0  ...  1.098621  -1.0    0.0  1.229439
46     1  0.495992  0.504008       1  ...  1.097771  -1.0    0.0  1.230151
47     0  0.507098  0.492902       0  ...  1.097872  -1.0    0.0  1.229835
48     0  0.500943  0.499057       0  ...  1.097940  -1.0    0.0  1.230150
49     0  0.505375  0.494625       0  ...  1.098451  -1.0    0.0  1.230428

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.395', 'enterprice': '20707.9', 'countrevence': '0', 'unrealprofit': '-4034.5335', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20825.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230119   154000    154959  1674114599  20805.4  20824.9  0.000937
2023-01-19 15:50:00,612:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7927 

self.closeSec=1674115199, self.tradeDate='20230119', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20824.9', self.close='20818.1'
2023-01-19 16:00:01,423:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674115199, self.tradeDate='20230119', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20824.9', self.close='20818.1'
2023-01-19 16:00:01,451:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230119   151000    151959  1674112799  20841.5  20825.3 -0.000777
524  20230119   152000    152959  1674113399  20825.3  20827.8  0.000120
525  20230119   153000    153959  1674113999  20827.9  20805.4 -0.001075
526  20230119   154000    154959  1674114599  20805.4  20824.9  0.000937
527  20230119   155000    155959  1674115199  20824.9  20818.1 -0.000327
2023-01-19 16:00:01,457:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7928 

self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20818.2', self.close='20842.8'
2023-01-19 16:10:01,542:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20818.2', self.close='20842.8'
127.0.0.1 - - [19/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 16:10:01,563:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230119   152000    152959  1674113399  20825.3  20827.8  0.000120
525  20230119   153000    153959  1674113999  20827.9  20805.4 -0.001075
526  20230119   154000    154959  1674114599  20805.4  20824.9  0.000937
527  20230119   155000    155959  1674115199  20824.9  20818.1 -0.000327
528  20230119   160000    160959  1674115799  20818.2  20842.8  0.001186
2023-01-19 16:10:01,564:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230119   154000    154959  1674114599  20805.4  20824.9
2023-01-19 15:50:00,618:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7928 

self.closeSec=1674115199, self.tradeDate='20230119', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20824.9', self.close='20818.1'
2023-01-19 16:00:01,411:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674115199, self.tradeDate='20230119', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20824.9', self.close='20818.1'
2023-01-19 16:00:01,465:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230119   151000    151959  1674112799  20841.5  20825.3
17516  20230119   152000    152959  1674113399  20825.3  20827.8
17517  20230119   153000    153959  1674113999  20827.9  20805.4
17518  20230119   154000    154959  1674114599  20805.4  20824.9
17519  20230119   155000    155959  1674115199  20824.9  20818.1
2023-01-19 16:00:01,465:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7929 

self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20818.2', self.close='20842.8'
2023-01-19 16:10:01,559:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20818.2', self.close='20842.8'
127.0.0.1 - - [19/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 16:10:01,577:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230119   152000    152959  1674113399  20825.3  20827.8
17517  20230119   153000    153959  1674113999  20827.9  20805.4
17518  20230119   154000    154959  1674114599  20805.4  20824.9
17519  20230119   155000    155959  1674115199  20824.9  20818.1
17520  20230119   160000    160959  1674115799  20818.2  20842.8
2023-01-19 16:10:01,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230119   154000    154959  1674114599  20805.4  20824.9
2023-01-19 15:50:00,607:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7928 

self.closeSec=1674115199, self.tradeDate='20230119', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20824.9', self.close='20818.1'
2023-01-19 16:00:01,428:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674115199, self.tradeDate='20230119', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20824.9', self.close='20818.1'
127.0.0.1 - - [19/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-19 16:00:01,468:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230119   151000    151959  1674112799  20841.5  20825.3
12188  20230119   152000    152959  1674113399  20825.3  20827.8
12189  20230119   153000    153959  1674113999  20827.9  20805.4
12190  20230119   154000    154959  1674114599  20805.4  20824.9
12191  20230119   155000    155959  1674115199  20824.9  20818.1
2023-01-19 16:00:01,468:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7929 

self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20818.2', self.close='20842.8'
2023-01-19 16:10:01,530:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20818.2', self.close='20842.8'
127.0.0.1 - - [19/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 16:10:01,566:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230119   152000    152959  1674113399  20825.3  20827.8
12189  20230119   153000    153959  1674113999  20827.9  20805.4
12190  20230119   154000    154959  1674114599  20805.4  20824.9
12191  20230119   155000    155959  1674115199  20824.9  20818.1
12192  20230119   160000    160959  1674115799  20818.2  20842.8
2023-01-19 16:10:01,566:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [19/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11288
self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20826.9, self.close=20842.8, self.high=20844.5, self.low=20817.7, self.vol=912.58, self.amt=19012274.0751 
2023-01-19 16:10:01,506:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230119   154500    154959  ...         0.0        0.0       0
5950  20230119   155000    155459  ...         0.0        0.0       0
5951  20230119   155500    155959  ...         0.0        0.0       0
5952  20230119   160000    160459  ...         0.0        0.0       0
5953  20230119   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 16:10:01,507:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674115799, self.tradeDate='20230119', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20826.9, self.close=20842.8, self.high=20844.5, self.low=20817.7, self.vol=912.58, self.amt=19012274.0751, ukdf['pct'].iloc[-1]=0.000768 , ukdf['amount'].iloc[-1]=19012274.0751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11289
self.closeSec=1674116099, self.tradeDate='20230119', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20842.9, self.close=20833.0, self.high=20848.0, self.low=20819.1, self.vol=860.698, self.amt=17933464.3029 
2023-01-19 16:15:00,783:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230119   155000    155459  ...         0.0        0.0       0
5951  20230119   155500    155959  ...         0.0        0.0       0
5952  20230119   160000    160459  ...         0.0        0.0       0
5953  20230119   160500    160959  ...         0.0        0.0       0
5954  20230119   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 16:15:00,784:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674116099, self.tradeDate='20230119', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20842.9, self.close=20833.0, self.high=20848.0, self.low=20819.1, self.vol=860.698, self.amt=17933464.3029, ukdf['pct'].iloc[-1]=-0.00047 , ukdf['amount'].iloc[-1]=17933464.3029, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230119   040000    075959  1674086399  ...    721  0.176794 -1.566888    -1.0
722  20230119   080000    115959  1674100799  ...    722  0.200767 -1.469262    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '21258.441069797', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20750.500551', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [19/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=330
self.closeSec=1674115199, self.tradeDate='20230119', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=20748.9, self.close=20818.1, self.high=20882.0, self.low=20745.1, self.vol=31249.692, self.amt=650769996.7361 
2023-01-19 16:00:01,328:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674115199, self.tradeDate='20230119', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=20748.9, self.close=20818.1, self.high=20882.0, self.low=20745.1, self.vol=31249.692, self.amt=650769996.7361 
2023-01-19 16:00:01,373:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230118   200000    235959  ...  269413.610  5.745100e+09 -0.007830
720  20230119   000000    035959  ...  320910.719  6.682469e+09 -0.006204
721  20230119   040000    075959  ...   93528.513  1.941499e+09 -0.010768
722  20230119   080000    115959  ...   43011.055  8.920198e+08  0.003332
723  20230119   120000    155959  ...   31249.692  6.507700e+08  0.003335

[5 rows x 11 columns]
2023-01-19 16:00:03,627:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230118   200000    235959  1674057599  ...    719  0.189080 -1.617061    -1.0
720  20230119   000000    035959  1674071999  ...    720  0.173649 -1.613879    -1.0
721  20230119   040000    075959  1674086399  ...    721  0.176794 -1.566888    -1.0
722  20230119   080000    115959  1674100799  ...    722  0.200767 -1.469262    -1.0
723  20230119   120000    155959  1674115199  ...    723  0.204434 -1.425282    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '17625.14913264315', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20821.66761145', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


