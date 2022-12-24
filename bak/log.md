# 20221224 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [24/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7802
self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16835.0, self.close=16831.9, self.high=16835.1, self.low=16831.9, self.vol=237.88, self.amt=4004299.5829 
2022-12-24 16:10:01,499:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221224   154500    154959  ...         0.0        0.0       0
5950  20221224   155000    155459  ...         0.0        0.0       0
5951  20221224   155500    155959  ...         0.0        0.0       0
5952  20221224   160000    160459  ...         0.0        0.0       0
5953  20221224   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 16:10:01,499:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16835.0, self.close=16831.9, self.high=16835.1, self.low=16831.9, self.vol=237.88, self.amt=4004299.5829, ukdf['pct'].iloc[-1]=-0.000184 , ukdf['amount'].iloc[-1]=4004299.5829, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-18209.2576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16831.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7803
self.closeSec=1671869699, self.tradeDate='20221224', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16831.9, self.close=16827.0, self.high=16831.9, self.low=16826.3, self.vol=396.478, self.amt=6672262.7933 
127.0.0.1 - - [24/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-24 16:15:00,606:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221224   155000    155459  ...         0.0        0.0       0
5951  20221224   155500    155959  ...         0.0        0.0       0
5952  20221224   160000    160459  ...         0.0        0.0       0
5953  20221224   160500    160959  ...         0.0        0.0       0
5954  20221224   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 16:15:00,606:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671869699, self.tradeDate='20221224', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16831.9, self.close=16827.0, self.high=16831.9, self.low=16826.3, self.vol=396.478, self.amt=6672262.7933, ukdf['pct'].iloc[-1]=-0.000291 , ukdf['amount'].iloc[-1]=6672262.7933, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17937.86341335216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16827.38999291', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=150, self.factor=0.4621476861693164, self.count=8368 

self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16835.0, self.close=16831.9, self.high=16835.1, self.low=16831.9 
2022-12-24 16:10:01,426:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16835.0, self.close=16831.9, self.high=16835.1, self.low=16831.9   
2022-12-24 16:10:01,444:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221224   154500    154959  1671868199  ...  16832.8  0.000012   1629    3
1630  20221224   155000    155459  1671868499  ...  16828.8 -0.000160   1630    4
1631  20221224   155500    155959  1671868799  ...  16830.2  0.000594   1631    5
1632  20221224   160000    160459  1671869099  ...  16835.0 -0.000315   1632    0
1633  20221224   160500    160959  1671869399  ...  16831.9 -0.000184   1633    1

[5 rows x 11 columns]
2022-12-24 16:10:01,444:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=150, self.factor=0.4621476861693164, self.count=8369 

self.closeSec=1671869699, self.tradeDate='20221224', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16831.9, self.close=16827.0, self.high=16831.9, self.low=16826.3 
2022-12-24 16:15:00,545:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671869699, self.tradeDate='20221224', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16831.9, self.close=16827.0, self.high=16831.9, self.low=16826.3   
127.0.0.1 - - [24/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-24 16:15:00,625:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221224   155000    155459  1671868499  ...  16828.8 -0.000160   1630    4
1631  20221224   155500    155959  1671868799  ...  16830.2  0.000594   1631    5
1632  20221224   160000    160459  1671869099  ...  16835.0 -0.000315   1632    0
1633  20221224   160500    160959  1671869399  ...  16831.9 -0.000184   1633    1
1634  20221224   161000    161459  1671869699  ...  16826.3 -0.000291   1634    2

[5 rows x 11 columns]
2022-12-24 16:15:00,626:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-24 16:00:17,548:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221224    132959  16822.3  ...  49.166667  0.501341  0.501107
5787  20221224    135959  16807.1  ...  49.583333  0.507350  0.503305
5788  20221224    142959  16815.9  ...  49.166667  0.504465  0.506344
5789  20221224    145959  16811.8  ...  48.750000  0.503807  0.509402
5790  20221224    152959  16810.9  ...  48.750000  0.514362  0.508627

[5 rows x 33 columns]
0.525830258302583
acc is : 0.525830258302583
2022-12-24 16:00:17,635:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.491984  0.508016       1  ...  1.098954   1.0    0.0  0.980599
538     1  0.497317  0.502683       0  ...  1.098693   1.0    0.0  0.980366
539     1  0.493056  0.506944       0  ...  1.098634   1.0    0.0  0.980313
540     1  0.493541  0.506459       1  ...  1.099595   1.0    0.0  0.981170
541     1  0.499796  0.500204       1  ...  1.100555   1.0    0.0  0.982028

[5 rows x 10 columns]
2022-12-24 16:00:17,646:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491974  0.508026       1  ...  1.098954   1.0    0.0  0.980553
46     1  0.497073  0.502927       0  ...  1.098693   1.0    0.0  0.978950
47     1  0.492576  0.507424       0  ...  1.098634   1.0    0.0  0.977378
48     1  0.493426  0.506574       1  ...  1.099595   1.0    0.0  0.980410
49     1  0.499796  0.500204       1  ...  1.100555   1.0    0.0  0.982028

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5938.76492520384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16841.14364478', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221224   154000    154959  1671868199  16837.1    16833 -0.000249
2022-12-24 15:50:00,558:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4183 

self.closeSec=1671868799, self.tradeDate='20221224', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16833.1', self.close='16840.3'
127.0.0.1 - - [24/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-24 16:00:01,099:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671868799, self.tradeDate='20221224', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16833.1', self.close='16840.3'
2022-12-24 16:00:01,110:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221224   151000    151959  1671866399  16811.1  16809.8 -0.000077
524  20221224   152000    152959  1671866999  16809.8  16825.6  0.000940
525  20221224   153000    153959  1671867599  16825.7  16837.2  0.000689
526  20221224   154000    154959  1671868199  16837.1    16833 -0.000249
527  20221224   155000    155959  1671868799  16833.1  16840.3  0.000434
2022-12-24 16:00:01,110:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4184 

self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16840.2', self.close='16831.9'
2022-12-24 16:10:01,549:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16840.2', self.close='16831.9'
127.0.0.1 - - [24/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-24 16:10:01,577:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221224   152000    152959  1671866999  16809.8  16825.6  0.000940
525  20221224   153000    153959  1671867599  16825.7  16837.2  0.000689
526  20221224   154000    154959  1671868199  16837.1    16833 -0.000249
527  20221224   155000    155959  1671868799  16833.1  16840.3  0.000434
528  20221224   160000    160959  1671869399  16840.2  16831.9 -0.000499
2022-12-24 16:10:01,577:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221224   154000    154959  1671868199  16837.1    16833
2022-12-24 15:50:00,564:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4184 

self.closeSec=1671868799, self.tradeDate='20221224', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16833.1', self.close='16840.3'
2022-12-24 16:00:01,161:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671868799, self.tradeDate='20221224', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16833.1', self.close='16840.3'
2022-12-24 16:00:01,227:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221224   151000    151959  1671866399  16811.1  16809.8
17516  20221224   152000    152959  1671866999  16809.8  16825.6
17517  20221224   153000    153959  1671867599  16825.7  16837.2
17518  20221224   154000    154959  1671868199  16837.1    16833
17519  20221224   155000    155959  1671868799  16833.1  16840.3
2022-12-24 16:00:01,227:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4185 

self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16840.2', self.close='16831.9'
2022-12-24 16:10:01,560:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16840.2', self.close='16831.9'
2022-12-24 16:10:01,582:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221224   152000    152959  1671866999  16809.8  16825.6
17517  20221224   153000    153959  1671867599  16825.7  16837.2
17518  20221224   154000    154959  1671868199  16837.1    16833
17519  20221224   155000    155959  1671868799  16833.1  16840.3
17520  20221224   160000    160959  1671869399  16840.2  16831.9
2022-12-24 16:10:01,582:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221224   154000    154959  1671868199  16837.1    16833
2022-12-24 15:50:00,561:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4184 

self.closeSec=1671868799, self.tradeDate='20221224', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16833.1', self.close='16840.3'
2022-12-24 16:00:01,151:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671868799, self.tradeDate='20221224', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16833.1', self.close='16840.3'
127.0.0.1 - - [24/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-24 16:00:01,223:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221224   151000    151959  1671866399  16811.1  16809.8
12188  20221224   152000    152959  1671866999  16809.8  16825.6
12189  20221224   153000    153959  1671867599  16825.7  16837.2
12190  20221224   154000    154959  1671868199  16837.1    16833
12191  20221224   155000    155959  1671868799  16833.1  16840.3
2022-12-24 16:00:01,223:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [24/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4185 

self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16840.2', self.close='16831.9'
2022-12-24 16:10:01,590:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16840.2', self.close='16831.9'
2022-12-24 16:10:01,602:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221224   152000    152959  1671866999  16809.8  16825.6
12189  20221224   153000    153959  1671867599  16825.7  16837.2
12190  20221224   154000    154959  1671868199  16837.1    16833
12191  20221224   155000    155959  1671868799  16833.1  16840.3
12192  20221224   160000    160959  1671869399  16840.2  16831.9
2022-12-24 16:10:01,603:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3800
self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16835.0, self.close=16831.9, self.high=16835.1, self.low=16831.9, self.vol=237.88, self.amt=4004299.5829 
127.0.0.1 - - [24/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-24 16:10:01,515:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221224   154500    154959  ...         0.0        0.0       0
5950  20221224   155000    155459  ...         0.0        0.0       0
5951  20221224   155500    155959  ...         0.0        0.0       0
5952  20221224   160000    160459  ...         0.0        0.0       0
5953  20221224   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 16:10:01,517:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671869399, self.tradeDate='20221224', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16835.0, self.close=16831.9, self.high=16835.1, self.low=16831.9, self.vol=237.88, self.amt=4004299.5829, ukdf['pct'].iloc[-1]=-0.000184 , ukdf['amount'].iloc[-1]=4004299.5829, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3801
self.closeSec=1671869699, self.tradeDate='20221224', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16831.9, self.close=16827.0, self.high=16831.9, self.low=16826.3, self.vol=396.478, self.amt=6672262.7933 
2022-12-24 16:15:00,649:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221224   155000    155459  ...         0.0        0.0       0
5951  20221224   155500    155959  ...         0.0        0.0       0
5952  20221224   160000    160459  ...         0.0        0.0       0
5953  20221224   160500    160959  ...         0.0        0.0       0
5954  20221224   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 16:15:00,649:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671869699, self.tradeDate='20221224', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16831.9, self.close=16827.0, self.high=16831.9, self.low=16826.3, self.vol=396.478, self.amt=6672262.7933, ukdf['pct'].iloc[-1]=-0.000291 , ukdf['amount'].iloc[-1]=6672262.7933, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221224   040000    075959  1671839999  ...    721  0.026274 -1.387503    -1.0
722  20221224   080000    115959  1671854399  ...    722  0.000549 -1.414485    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5934.18044019196', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16834.28527393', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [24/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=174
self.closeSec=1671868799, self.tradeDate='20221224', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16833.3, self.close=16840.2, self.high=16850.0, self.low=16797.0, self.vol=15969.157, self.amt=268628779.5488 
2022-12-24 16:00:00,977:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671868799, self.tradeDate='20221224', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16833.3, self.close=16840.2, self.high=16850.0, self.low=16797.0, self.vol=15969.157, self.amt=268628779.5488 
2022-12-24 16:00:01,016:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221223   200000    235959  ...  123957.356  2.086381e+09 -0.000677
720  20221224   000000    035959  ...   18873.526  3.176618e+08  0.000743
721  20221224   040000    075959  ...   26104.665  4.384509e+08 -0.003688
722  20221224   080000    115959  ...   15312.893  2.573875e+08  0.003392
723  20221224   120000    155959  ...   15969.157  2.686288e+08  0.000410

[5 rows x 11 columns]
2022-12-24 16:00:02,503:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221223   200000    235959  1671811199  ...    719  0.046037 -1.408536    -1.0
720  20221224   000000    035959  1671825599  ...    720  0.041362 -1.385213    -1.0
721  20221224   040000    075959  1671839999  ...    721  0.026274 -1.387503    -1.0
722  20221224   080000    115959  1671854399  ...    722  0.000549 -1.414485    -1.0
723  20221224   120000    155959  1671868799  ...    723  0.005509 -1.369103    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-6255.1984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16840.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


