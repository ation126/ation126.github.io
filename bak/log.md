# 20230207 16:34:09

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [07/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20765
self.closeSec=1675758299, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22882.0, self.close=22884.5, self.high=22887.2, self.low=22875.0, self.vol=515.046, self.amt=11783814.0959 
2023-02-07 16:25:01,471:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230207   160000    160459  ...         0.0        0.0       0
5953  20230207   160500    160959  ...         0.0        0.0       0
5954  20230207   161000    161459  ...         0.0        0.0       0
5955  20230207   161500    161959  ...         0.0        0.0       0
5956  20230207   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 16:25:01,472:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675758299, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22882.0, self.close=22884.5, self.high=22887.2, self.low=22875.0, self.vol=515.046, self.amt=11783814.0959, ukdf['pct'].iloc[-1]=0.000114 , ukdf['amount'].iloc[-1]=11783814.0959, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-382562.9024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22886.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20766
self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=22886.7, self.close=22891.2, self.high=22896.8, self.low=22882.0, self.vol=491.368, self.amt=11247011.7985 
2023-02-07 16:30:00,818:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230207   160500    160959  ...         0.0        0.0       0
5954  20230207   161000    161459  ...         0.0        0.0       0
5955  20230207   161500    161959  ...         0.0        0.0       0
5956  20230207   162000    162459  ...         0.0        0.0       0
5957  20230207   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 16:30:00,819:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=22886.7, self.close=22891.2, self.high=22896.8, self.low=22882.0, self.vol=491.368, self.amt=11247011.7985, ukdf['pct'].iloc[-1]=0.000293 , ukdf['amount'].iloc[-1]=11247011.7985, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-382844.03666197264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22891.37186689', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1635  20230207   161500    161959  1675757999  ...  22875.1  0.000337   1635    3
1636  20230207   162000    162459  1675758299  ...  22875.0  0.000114   1636    4

[5 rows x 11 columns]
2023-02-07 16:25:01,454:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=31, self.factor=0.5268113669145293, self.count=21332 

self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=22886.7, self.close=22891.2, self.high=22896.8, self.low=22882.0 
2023-02-07 16:30:00,745:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=22886.7, self.close=22891.2, self.high=22896.8, self.low=22882.0   
2023-02-07 16:30:00,761:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1633  20230207   160500    160959  1675757399  ...  22866.6 -0.001362   1633    1
1634  20230207   161000    161459  1675757699  ...  22866.9 -0.000350   1634    2
1635  20230207   161500    161959  1675757999  ...  22875.1  0.000337   1635    3
1636  20230207   162000    162459  1675758299  ...  22875.0  0.000114   1636    4
1637  20230207   162500    162959  1675758599  ...  22882.0  0.000293   1637    5

[5 rows x 11 columns]
2023-02-07 16:30:00,761:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-07 16:30:00,781:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230207   142500    142959  1675751399  ...  0.000654   1613    5  0.531262
230  20230207   145500    145959  1675753199  ... -0.000685   1619    5  0.529745
231  20230207   152500    152959  1675754999  ... -0.000344   1625    5  0.527695
232  20230207   155500    155959  1675756799  ... -0.000096   1631    5  0.526811
233  20230207   162500    162959  1675758599  ...  0.000293   1637    5  0.526748

[5 rows x 12 columns]


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-07 16:30:19,929:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230207    135959  22917.1  ...  45.000000  0.481959  0.508197
5788  20230207    142959  22928.0  ...  45.416667  0.491885  0.498438
5789  20230207    145959  22965.1  ...  45.000000  0.479289  0.495484
5790  20230207    152959  22916.6  ...  45.000000  0.482100  0.491448
5791  20230207    155959  22925.8  ...  45.000000  0.476974  0.490176

[5 rows x 33 columns]
0.496309963099631
acc is : 0.496309963099631
2023-02-07 16:30:20,038:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495389  0.504611       1  ...  0.999401  -1.0    0.0  1.003434
538     0  0.505588  0.494412       0  ...  1.001559  -1.0    0.0  1.001267
539     1  0.482412  0.517588       1  ...  1.001109  -1.0    0.0  1.001717
540     1  0.494580  0.505420       0  ...  1.001987  -1.0    0.0  1.000839
541     1  0.483602  0.516398       0  ...  1.002617  -1.0    0.0  1.000210

[5 rows x 10 columns]
2023-02-07 16:30:20,064:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493602  0.506398       1  ...  0.999401  -1.0    0.0  0.998778
46     0  0.503415  0.496585       0  ...  0.962668  -1.0    0.0  0.996239
47     1  0.480676  0.519324       1  ...  1.001109  -1.0    0.0  0.998724
48     1  0.493808  0.506192       0  ...  1.001987  -1.0    0.0  0.999428
49     1  0.483602  0.516398       0  ...  1.002617  -1.0    0.0  1.000210

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.436', 'enterprice': '22744.1', 'countrevence': '0', 'unrealprofit': '-4891.3488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22894.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230207   160000    160959  1675757399  22905.5  22882.2 -0.001022
2023-02-07 16:10:01,572:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10665 

self.closeSec=1675757999, self.tradeDate='20230207', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22882.2', self.close='22881.9'
2023-02-07 16:20:00,782:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675757999, self.tradeDate='20230207', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22882.2', self.close='22881.9'
2023-02-07 16:20:00,837:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230207   153000    153959  1675755599  22925.8    22898 -0.001208
526  20230207   154000    154959  1675756199  22897.9  22908.1  0.000441
527  20230207   155000    155959  1675756799  22908.1  22905.6 -0.000109
528  20230207   160000    160959  1675757399  22905.5  22882.2 -0.001022
529  20230207   161000    161959  1675757999  22882.2  22881.9 -0.000013
2023-02-07 16:20:00,837:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10666 

self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='22882', self.close='22891.1'
2023-02-07 16:30:01,395:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='22882', self.close='22891.1'
2023-02-07 16:30:01,461:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230207   154000    154959  1675756199  22897.9  22908.1  0.000441
527  20230207   155000    155959  1675756799  22908.1  22905.6 -0.000109
528  20230207   160000    160959  1675757399  22905.5  22882.2 -0.001022
529  20230207   161000    161959  1675757999  22882.2  22881.9 -0.000013
530  20230207   162000    162959  1675758599    22882  22891.1  0.000402
2023-02-07 16:30:01,461:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230207   160000    160959  1675757399  22905.5  22882.2
2023-02-07 16:10:01,548:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10666 

self.closeSec=1675757999, self.tradeDate='20230207', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22882.2', self.close='22881.9'
2023-02-07 16:20:00,814:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675757999, self.tradeDate='20230207', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22882.2', self.close='22881.9'
127.0.0.1 - - [07/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-07 16:20:00,848:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230207   153000    153959  1675755599  22925.8    22898
17518  20230207   154000    154959  1675756199  22897.9  22908.1
17519  20230207   155000    155959  1675756799  22908.1  22905.6
17520  20230207   160000    160959  1675757399  22905.5  22882.2
17521  20230207   161000    161959  1675757999  22882.2  22881.9
2023-02-07 16:20:00,848:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10667 

self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='22882', self.close='22891.1'
2023-02-07 16:30:01,431:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='22882', self.close='22891.1'
2023-02-07 16:30:01,461:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230207   154000    154959  1675756199  22897.9  22908.1
17519  20230207   155000    155959  1675756799  22908.1  22905.6
17520  20230207   160000    160959  1675757399  22905.5  22882.2
17521  20230207   161000    161959  1675757999  22882.2  22881.9
17522  20230207   162000    162959  1675758599    22882  22891.1
2023-02-07 16:30:01,461:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230207   160000    160959  1675757399  22905.5  22882.2
2023-02-07 16:10:01,543:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10666 

self.closeSec=1675757999, self.tradeDate='20230207', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22882.2', self.close='22881.9'
2023-02-07 16:20:00,800:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675757999, self.tradeDate='20230207', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22882.2', self.close='22881.9'
127.0.0.1 - - [07/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-07 16:20:00,838:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230207   153000    153959  1675755599  22925.8    22898
12190  20230207   154000    154959  1675756199  22897.9  22908.1
12191  20230207   155000    155959  1675756799  22908.1  22905.6
12192  20230207   160000    160959  1675757399  22905.5  22882.2
12193  20230207   161000    161959  1675757999  22882.2  22881.9
2023-02-07 16:20:00,838:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10667 

self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='22882', self.close='22891.1'
127.0.0.1 - - [07/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-07 16:30:01,412:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='22882', self.close='22891.1'
2023-02-07 16:30:01,463:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230207   154000    154959  1675756199  22897.9  22908.1
12191  20230207   155000    155959  1675756799  22908.1  22905.6
12192  20230207   160000    160959  1675757399  22905.5  22882.2
12193  20230207   161000    161959  1675757999  22882.2  22881.9
12194  20230207   162000    162959  1675758599    22882  22891.1
2023-02-07 16:30:01,464:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16763
self.closeSec=1675758299, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22882.0, self.close=22884.5, self.high=22887.2, self.low=22875.0, self.vol=515.046, self.amt=11783814.0959 
127.0.0.1 - - [07/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-07 16:25:01,486:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230207   160000    160459  ...         0.0        0.0       0
5953  20230207   160500    160959  ...         0.0        0.0       0
5954  20230207   161000    161459  ...         0.0        0.0       0
5955  20230207   161500    161959  ...         0.0        0.0       0
5956  20230207   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 16:25:01,487:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675758299, self.tradeDate='20230207', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22882.0, self.close=22884.5, self.high=22887.2, self.low=22875.0, self.vol=515.046, self.amt=11783814.0959, ukdf['pct'].iloc[-1]=0.000114 , ukdf['amount'].iloc[-1]=11783814.0959, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [07/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16764
self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=22886.7, self.close=22891.2, self.high=22896.8, self.low=22882.0, self.vol=491.368, self.amt=11247011.7985 
2023-02-07 16:30:00,812:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230207   160500    160959  ...         0.0        0.0       0
5954  20230207   161000    161459  ...         0.0        0.0       0
5955  20230207   161500    161959  ...         0.0        0.0       0
5956  20230207   162000    162459  ...         0.0        0.0       0
5957  20230207   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 16:30:00,813:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675758599, self.tradeDate='20230207', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=22886.7, self.close=22891.2, self.high=22896.8, self.low=22882.0, self.vol=491.368, self.amt=11247011.7985, ukdf['pct'].iloc[-1]=0.000293 , ukdf['amount'].iloc[-1]=11247011.7985, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230207   040000    075959  1675727999  ...    721  0.528222  0.049603     NaN
722  20230207   080000    115959  1675742399  ...    722  0.536839  0.106405     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-32211.5388', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22873.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [07/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=444
self.closeSec=1675756799, self.tradeDate='20230207', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22870.9, self.close=22905.6, self.high=22977.8, self.low=22854.8, self.vol=30655.972, self.amt=702336118.8055 
2023-02-07 16:00:01,146:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675756799, self.tradeDate='20230207', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22870.9, self.close=22905.6, self.high=22977.8, self.low=22854.8, self.vol=30655.972, self.amt=702336118.8055 
2023-02-07 16:00:01,177:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230206   200000    235959  ...   94648.260  2.164577e+09  0.007331
720  20230207   000000    035959  ...  105678.626  2.434439e+09 -0.000777
721  20230207   040000    075959  ...   67427.476  1.538921e+09 -0.011661
722  20230207   080000    115959  ...   36711.889  8.380403e+08  0.004974
723  20230207   120000    155959  ...   30655.972  7.023361e+08  0.001517

[5 rows x 11 columns]
2023-02-07 16:00:02,918:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230206   200000    235959  1675699199  ...    719  0.728452  0.727701     1.0
720  20230207   000000    035959  1675713599  ...    720  0.682212  0.585344     NaN
721  20230207   040000    075959  1675727999  ...    721  0.528222  0.049603     NaN
722  20230207   080000    115959  1675742399  ...    722  0.536839  0.106405     NaN
723  20230207   120000    155959  1675756799  ...    723  0.552062  0.189306     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-30960.7944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22905.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


