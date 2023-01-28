# 20230128 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17882
self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22984.5, self.close=22980.4, self.high=22998.6, self.low=22977.6, self.vol=579.29, self.amt=13318608.4377 
127.0.0.1 - - [28/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-28 16:10:01,481:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230128   154500    154959  ...         0.0        0.0       0
5950  20230128   155000    155459  ...         0.0        0.0       0
5951  20230128   155500    155959  ...         0.0        0.0       0
5952  20230128   160000    160459  ...         0.0        0.0       0
5953  20230128   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 16:10:01,482:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22984.5, self.close=22980.4, self.high=22998.6, self.low=22977.6, self.vol=579.29, self.amt=13318608.4377, ukdf['pct'].iloc[-1]=-0.000178 , ukdf['amount'].iloc[-1]=13318608.4377, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-388201.3936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22980.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17883
self.closeSec=1674893699, self.tradeDate='20230128', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22980.3, self.close=22975.8, self.high=22980.4, self.low=22963.2, self.vol=908.637, self.amt=20871155.8727 
2023-01-28 16:15:00,843:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230128   155000    155459  ...         0.0        0.0       0
5951  20230128   155500    155959  ...         0.0        0.0       0
5952  20230128   160000    160459  ...         0.0        0.0       0
5953  20230128   160500    160959  ...         0.0        0.0       0
5954  20230128   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 16:15:00,844:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674893699, self.tradeDate='20230128', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22980.3, self.close=22975.8, self.high=22980.4, self.low=22963.2, self.vol=908.637, self.amt=20871155.8727, ukdf['pct'].iloc[-1]=-0.0002 , ukdf['amount'].iloc[-1]=20871155.8727, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-387792.1968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22973.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22984.5, self.close=22980.4, self.high=22998.6, self.low=22977.6 
127.0.0.1 - - [28/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-28 16:10:01,435:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22984.5, self.close=22980.4, self.high=22998.6, self.low=22977.6   
2023-01-28 16:10:01,461:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230128   154500    154959  1674892199  ...  22977.4 -0.000431   1629    3
1630  20230128   155000    155459  1674892499  ...  22972.1  0.000500   1630    4
1631  20230128   155500    155959  1674892799  ...  22972.3 -0.000231   1631    5
1632  20230128   160000    160459  1674893099  ...  22971.1  0.000009   1632    0
1633  20230128   160500    160959  1674893399  ...  22977.6 -0.000178   1633    1

[5 rows x 11 columns]
2023-01-28 16:10:01,465:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=365, self.factor=0.45490648813747836, self.count=18449 

self.closeSec=1674893699, self.tradeDate='20230128', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22980.3, self.close=22975.8, self.high=22980.4, self.low=22963.2 
2023-01-28 16:15:00,785:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674893699, self.tradeDate='20230128', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22980.3, self.close=22975.8, self.high=22980.4, self.low=22963.2   
2023-01-28 16:15:00,812:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230128   155000    155459  1674892499  ...  22972.1  0.000500   1630    4
1631  20230128   155500    155959  1674892799  ...  22972.3 -0.000231   1631    5
1632  20230128   160000    160459  1674893099  ...  22971.1  0.000009   1632    0
1633  20230128   160500    160959  1674893399  ...  22977.6 -0.000178   1633    1
1634  20230128   161000    161459  1674893699  ...  22963.2 -0.000200   1634    2

[5 rows x 11 columns]
2023-01-28 16:15:00,812:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-28 16:00:18,215:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230128    132959  23083.9  ...  52.083333  0.509796  0.495847
5787  20230128    135959  23057.6  ...  52.083333  0.509713  0.506841
5788  20230128    142959  23057.3  ...  51.666667  0.500585  0.521449
5789  20230128    145959  23013.3  ...  51.666667  0.504378  0.533263
5790  20230128    152959  23031.8  ...  51.666667  0.488872  0.551742

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-01-28 16:00:18,319:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.508481  0.491519       0  ...  0.990803   1.0    0.0  1.092230
538     0  0.512178  0.487822       0  ...  0.988925   1.0    0.0  1.090160
539     1  0.496825  0.503175       1  ...  0.989711   1.0    0.0  1.091027
540     0  0.510214  0.489786       0  ...  0.986493   1.0    0.0  1.087479
541     1  0.487213  0.512787       1  ...  0.987666   1.0    0.0  1.088772

[5 rows x 10 columns]
2023-01-28 16:00:18,341:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508496  0.491504       0  ...  0.990803   1.0    0.0  1.087988
46     0  0.511440  0.488560       0  ...  0.988925   1.0    0.0  1.084764
47     1  0.496885  0.503115       1  ...  0.989711   1.0    0.0  1.087010
48     0  0.509441  0.490559       0  ...  0.986493   1.0    0.0  1.081612
49     1  0.487213  0.512787       1  ...  0.987666   1.0    0.0  1.088772

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.8', 'enterprice': '23035.8', 'countrevence': '0', 'unrealprofit': '-1598.52', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22983.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230128   154000    154959  1674892199  22979.4  22978.1 -0.000057
2023-01-28 15:50:00,614:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9223 

self.closeSec=1674892799, self.tradeDate='20230128', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22978.1', self.close='22984.3'
2023-01-28 16:00:01,836:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674892799, self.tradeDate='20230128', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22978.1', self.close='22984.3'
127.0.0.1 - - [28/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-28 16:00:01,868:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230128   151000    151959  1674890399  23017.4  22975.5 -0.001825
524  20230128   152000    152959  1674890999  22975.4    22957 -0.000805
525  20230128   153000    153959  1674891599  22956.9  22979.4  0.000976
526  20230128   154000    154959  1674892199  22979.4  22978.1 -0.000057
527  20230128   155000    155959  1674892799  22978.1  22984.3  0.000270
2023-01-28 16:00:01,868:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9224 

self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22984.3', self.close='22980.4'
2023-01-28 16:10:01,518:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22984.3', self.close='22980.4'
2023-01-28 16:10:01,552:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230128   152000    152959  1674890999  22975.4    22957 -0.000805
525  20230128   153000    153959  1674891599  22956.9  22979.4  0.000976
526  20230128   154000    154959  1674892199  22979.4  22978.1 -0.000057
527  20230128   155000    155959  1674892799  22978.1  22984.3  0.000270
528  20230128   160000    160959  1674893399  22984.3  22980.4 -0.000170
2023-01-28 16:10:01,553:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230128   154000    154959  1674892199  22979.4  22978.1
2023-01-28 15:50:00,593:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9224 

self.closeSec=1674892799, self.tradeDate='20230128', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22978.1', self.close='22984.3'
127.0.0.1 - - [28/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-28 16:00:01,848:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674892799, self.tradeDate='20230128', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22978.1', self.close='22984.3'
2023-01-28 16:00:01,878:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230128   151000    151959  1674890399  23017.4  22975.5
17516  20230128   152000    152959  1674890999  22975.4    22957
17517  20230128   153000    153959  1674891599  22956.9  22979.4
17518  20230128   154000    154959  1674892199  22979.4  22978.1
17519  20230128   155000    155959  1674892799  22978.1  22984.3
2023-01-28 16:00:01,878:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9225 

self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22984.3', self.close='22980.4'
2023-01-28 16:10:01,519:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22984.3', self.close='22980.4'
2023-01-28 16:10:01,531:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230128   152000    152959  1674890999  22975.4    22957
17517  20230128   153000    153959  1674891599  22956.9  22979.4
17518  20230128   154000    154959  1674892199  22979.4  22978.1
17519  20230128   155000    155959  1674892799  22978.1  22984.3
17520  20230128   160000    160959  1674893399  22984.3  22980.4
2023-01-28 16:10:01,532:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230128   154000    154959  1674892199  22979.4  22978.1
2023-01-28 15:50:00,616:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9224 

self.closeSec=1674892799, self.tradeDate='20230128', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22978.1', self.close='22984.3'
2023-01-28 16:00:01,844:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674892799, self.tradeDate='20230128', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22978.1', self.close='22984.3'
127.0.0.1 - - [28/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-28 16:00:01,872:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230128   151000    151959  1674890399  23017.4  22975.5
12188  20230128   152000    152959  1674890999  22975.4    22957
12189  20230128   153000    153959  1674891599  22956.9  22979.4
12190  20230128   154000    154959  1674892199  22979.4  22978.1
12191  20230128   155000    155959  1674892799  22978.1  22984.3
2023-01-28 16:00:01,872:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9225 

self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22984.3', self.close='22980.4'
2023-01-28 16:10:01,516:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22984.3', self.close='22980.4'
2023-01-28 16:10:01,531:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230128   152000    152959  1674890999  22975.4    22957
12189  20230128   153000    153959  1674891599  22956.9  22979.4
12190  20230128   154000    154959  1674892199  22979.4  22978.1
12191  20230128   155000    155959  1674892799  22978.1  22984.3
12192  20230128   160000    160959  1674893399  22984.3  22980.4
2023-01-28 16:10:01,531:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [28/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13880
self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22984.5, self.close=22980.4, self.high=22998.6, self.low=22977.6, self.vol=579.29, self.amt=13318608.4377 
2023-01-28 16:10:01,481:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230128   154500    154959  ...         0.0        0.0       0
5950  20230128   155000    155459  ...         0.0        0.0       0
5951  20230128   155500    155959  ...         0.0        0.0       0
5952  20230128   160000    160459  ...         0.0        0.0       0
5953  20230128   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 16:10:01,481:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674893399, self.tradeDate='20230128', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22984.5, self.close=22980.4, self.high=22998.6, self.low=22977.6, self.vol=579.29, self.amt=13318608.4377, ukdf['pct'].iloc[-1]=-0.000178 , ukdf['amount'].iloc[-1]=13318608.4377, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [28/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13881
self.closeSec=1674893699, self.tradeDate='20230128', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22980.3, self.close=22975.8, self.high=22980.4, self.low=22963.2, self.vol=908.637, self.amt=20871155.8727 
2023-01-28 16:15:00,843:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230128   155000    155459  ...         0.0        0.0       0
5951  20230128   155500    155959  ...         0.0        0.0       0
5952  20230128   160000    160459  ...         0.0        0.0       0
5953  20230128   160500    160959  ...         0.0        0.0       0
5954  20230128   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 16:15:00,844:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674893699, self.tradeDate='20230128', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22980.3, self.close=22975.8, self.high=22980.4, self.low=22963.2, self.vol=908.637, self.amt=20871155.8727, ukdf['pct'].iloc[-1]=-0.0002 , ukdf['amount'].iloc[-1]=20871155.8727, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230128   040000    075959  1674863999  ...    721  0.243670 -0.910256    -1.0
722  20230128   080000    115959  1674878399  ...    722  0.219206 -0.946683    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-7562.9256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23108.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [28/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=384
self.closeSec=1674892799, self.tradeDate='20230128', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23108.9, self.close=22984.3, self.high=23124.3, self.low=22942.9, self.vol=29492.397, self.amt=679077234.6367 
2023-01-28 16:00:01,572:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674892799, self.tradeDate='20230128', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23108.9, self.close=22984.3, self.high=23124.3, self.low=22942.9, self.vol=29492.397, self.amt=679077234.6367 
2023-01-28 16:00:01,602:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230127   200000    235959  ...  120970.159  2.779084e+09 -0.000962
720  20230128   000000    035959  ...   84096.917  1.945958e+09  0.013264
721  20230128   040000    075959  ...  121012.865  2.806965e+09 -0.007687
722  20230128   080000    115959  ...   30607.076  7.071304e+08  0.001777
723  20230128   120000    155959  ...   29492.397  6.790772e+08 -0.005396

[5 rows x 11 columns]
2023-01-28 16:00:03,054:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230127   200000    235959  1674835199  ...    719  0.129665 -1.199676    -1.0
720  20230128   000000    035959  1674849599  ...    720  0.183695 -1.064329    -1.0
721  20230128   040000    075959  1674863999  ...    721  0.243670 -0.910256    -1.0
722  20230128   080000    115959  1674878399  ...    722  0.219206 -0.946683    -1.0
723  20230128   120000    155959  1674892799  ...    723  0.205949 -0.956298    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-2362.3708', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22984.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


