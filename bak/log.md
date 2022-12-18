# 20221218 16:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6074
self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16747.4, self.close=16751.2, self.high=16758.7, self.low=16745.3, self.vol=787.224, self.amt=13188148.6033 
2022-12-18 16:10:01,509:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221218   154500    154959  ...         0.0        0.0       0
5950  20221218   155000    155459  ...         0.0        0.0       0
5951  20221218   155500    155959  ...         0.0        0.0       0
5952  20221218   160000    160459  ...         0.0        0.0       0
5953  20221218   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-18 16:10:01,509:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16747.4, self.close=16751.2, self.high=16758.7, self.low=16745.3, self.vol=787.224, self.amt=13188148.6033, ukdf['pct'].iloc[-1]=0.000227 , ukdf['amount'].iloc[-1]=13188148.6033, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-13353.0544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16751.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6075
self.closeSec=1671351299, self.tradeDate='20221218', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16751.2, self.close=16744.2, self.high=16754.9, self.low=16742.9, self.vol=385.21, self.amt=6451270.6402 
2022-12-18 16:15:00,616:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221218   155000    155459  ...         0.0        0.0       0
5951  20221218   155500    155959  ...         0.0        0.0       0
5952  20221218   160000    160459  ...         0.0        0.0       0
5953  20221218   160500    160959  ...         0.0        0.0       0
5954  20221218   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-18 16:15:00,617:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671351299, self.tradeDate='20221218', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16751.2, self.close=16744.2, self.high=16754.9, self.low=16742.9, self.vol=385.21, self.amt=6451270.6402, ukdf['pct'].iloc[-1]=-0.000418 , ukdf['amount'].iloc[-1]=6451270.6402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-12937.84', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16744.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=9, self.factor=0.5409797519820518, self.count=6640 

self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16747.4, self.close=16751.2, self.high=16758.7, self.low=16745.3 
2022-12-18 16:10:01,416:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16747.4, self.close=16751.2, self.high=16758.7, self.low=16745.3   
2022-12-18 16:10:01,464:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221218   154500    154959  1671349799  ...  16728.9 -0.000060   1629    3
1630  20221218   155000    155459  1671350099  ...  16732.2  0.000203   1630    4
1631  20221218   155500    155959  1671350399  ...  16731.2  0.000000   1631    5
1632  20221218   160000    160459  1671350699  ...  16739.8  0.000448   1632    0
1633  20221218   160500    160959  1671350999  ...  16745.3  0.000227   1633    1

[5 rows x 11 columns]
2022-12-18 16:10:01,464:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=9, self.factor=0.5409797519820518, self.count=6641 

self.closeSec=1671351299, self.tradeDate='20221218', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16751.2, self.close=16744.2, self.high=16754.9, self.low=16742.9 
2022-12-18 16:15:00,534:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671351299, self.tradeDate='20221218', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16751.2, self.close=16744.2, self.high=16754.9, self.low=16742.9   
2022-12-18 16:15:00,586:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221218   155000    155459  1671350099  ...  16732.2  0.000203   1630    4
1631  20221218   155500    155959  1671350399  ...  16731.2  0.000000   1631    5
1632  20221218   160000    160459  1671350699  ...  16739.8  0.000448   1632    0
1633  20221218   160500    160959  1671350999  ...  16745.3  0.000227   1633    1
1634  20221218   161000    161459  1671351299  ...  16742.9 -0.000418   1634    2

[5 rows x 11 columns]
2022-12-18 16:15:00,586:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-18 16:00:18,446:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221218    132959  16756.3  ...  48.333333  0.447189  0.406488
5787  20221218    135959  16738.8  ...  47.916667  0.444607  0.405331
5788  20221218    142959  16732.0  ...  47.500000  0.441628  0.407504
5789  20221218    145959  16725.6  ...  47.916667  0.443506  0.407926
5790  20221218    152959  16728.0  ...  48.333333  0.450757  0.402143

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2022-12-18 16:00:18,539:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.498936  0.501064       0  ...  1.075418  -1.0    0.0  0.980981
538     0  0.501541  0.498459       0  ...  1.075926  -1.0    0.0  0.980518
539     1  0.499378  0.500622       1  ...  1.075675  -1.0    0.0  0.980746
540     1  0.498262  0.501738       1  ...  1.074711  -1.0    0.0  0.981626
541     0  0.504674  0.495326       0  ...  1.074910  -1.0    0.0  0.981444

[5 rows x 10 columns]
2022-12-18 16:00:18,556:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498968  0.501032       0  ...  1.075418  -1.0    0.0  0.986138
46     0  0.501282  0.498718       0  ...  1.075926  -1.0    0.0  0.980385
47     1  0.498820  0.501180       1  ...  1.075675  -1.0    0.0  0.979471
48     1  0.498330  0.501670       1  ...  1.074711  -1.0    0.0  0.981401
49     0  0.504674  0.495326       0  ...  1.074910  -1.0    0.0  0.981444

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '38709.61965101376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16743.32856856', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221218   154000    154959  1671349799    16743  16736.5 -0.000394
2022-12-18 15:50:00,554:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3319 

self.closeSec=1671350399, self.tradeDate='20221218', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16736.4', self.close='16739.9'
127.0.0.1 - - [18/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-18 16:00:01,158:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671350399, self.tradeDate='20221218', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16736.4', self.close='16739.9'
2022-12-18 16:00:01,207:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221218   151000    151959  1671347999  16738.5  16730.9 -0.000448
524  20221218   152000    152959  1671348599  16730.9  16743.1  0.000729
525  20221218   153000    153959  1671349199  16743.1  16743.1  0.000000
526  20221218   154000    154959  1671349799    16743  16736.5 -0.000394
527  20221218   155000    155959  1671350399  16736.4  16739.9  0.000203
2022-12-18 16:00:01,207:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3320 

self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16739.9', self.close='16751.2'
2022-12-18 16:10:01,539:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16739.9', self.close='16751.2'
2022-12-18 16:10:01,574:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221218   152000    152959  1671348599  16730.9  16743.1  0.000729
525  20221218   153000    153959  1671349199  16743.1  16743.1  0.000000
526  20221218   154000    154959  1671349799    16743  16736.5 -0.000394
527  20221218   155000    155959  1671350399  16736.4  16739.9  0.000203
528  20221218   160000    160959  1671350999  16739.9  16751.2  0.000675
2022-12-18 16:10:01,574:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221218   154000    154959  1671349799    16743  16736.5
2022-12-18 15:50:00,564:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3320 

self.closeSec=1671350399, self.tradeDate='20221218', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16736.4', self.close='16739.9'
127.0.0.1 - - [18/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-18 16:00:01,184:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671350399, self.tradeDate='20221218', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16736.4', self.close='16739.9'
2022-12-18 16:00:01,211:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221218   151000    151959  1671347999  16738.5  16730.9
17516  20221218   152000    152959  1671348599  16730.9  16743.1
17517  20221218   153000    153959  1671349199  16743.1  16743.1
17518  20221218   154000    154959  1671349799    16743  16736.5
17519  20221218   155000    155959  1671350399  16736.4  16739.9
2022-12-18 16:00:01,211:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3321 

self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16739.9', self.close='16751.2'
2022-12-18 16:10:01,544:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16739.9', self.close='16751.2'
2022-12-18 16:10:01,566:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221218   152000    152959  1671348599  16730.9  16743.1
17517  20221218   153000    153959  1671349199  16743.1  16743.1
17518  20221218   154000    154959  1671349799    16743  16736.5
17519  20221218   155000    155959  1671350399  16736.4  16739.9
17520  20221218   160000    160959  1671350999  16739.9  16751.2
2022-12-18 16:10:01,567:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221218   154000    154959  1671349799    16743  16736.5
2022-12-18 15:50:00,562:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3320 

self.closeSec=1671350399, self.tradeDate='20221218', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16736.4', self.close='16739.9'
2022-12-18 16:00:01,169:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671350399, self.tradeDate='20221218', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16736.4', self.close='16739.9'
2022-12-18 16:00:01,193:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221218   151000    151959  1671347999  16738.5  16730.9
12188  20221218   152000    152959  1671348599  16730.9  16743.1
12189  20221218   153000    153959  1671349199  16743.1  16743.1
12190  20221218   154000    154959  1671349799    16743  16736.5
12191  20221218   155000    155959  1671350399  16736.4  16739.9
2022-12-18 16:00:01,193:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3321 

self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16739.9', self.close='16751.2'
2022-12-18 16:10:01,552:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16739.9', self.close='16751.2'
2022-12-18 16:10:01,575:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221218   152000    152959  1671348599  16730.9  16743.1
12189  20221218   153000    153959  1671349199  16743.1  16743.1
12190  20221218   154000    154959  1671349799    16743  16736.5
12191  20221218   155000    155959  1671350399  16736.4  16739.9
12192  20221218   160000    160959  1671350999  16739.9  16751.2
2022-12-18 16:10:01,576:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2072
self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16747.4, self.close=16751.2, self.high=16758.7, self.low=16745.3, self.vol=787.224, self.amt=13188148.6033 
127.0.0.1 - - [18/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-18 16:10:01,506:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221218   154500    154959  ...    0.014042   0.102591       0
5950  20221218   155000    155459  ...    0.013558   0.100434       0
5951  20221218   155500    155959  ...    0.013100   0.098478       0
5952  20221218   160000    160459  ...    0.012640   0.096454       0
5953  20221218   160500    160959  ...    0.012180   0.094378       0

[5 rows x 18 columns]
2022-12-18 16:10:01,508:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671350999, self.tradeDate='20221218', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16747.4, self.close=16751.2, self.high=16758.7, self.low=16745.3, self.vol=787.224, self.amt=13188148.6033, ukdf['pct'].iloc[-1]=0.000227 , ukdf['amount'].iloc[-1]=13188148.6033, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.012179571117409664, signal=0, value_std=0.09437751186350149 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2073
self.closeSec=1671351299, self.tradeDate='20221218', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16751.2, self.close=16744.2, self.high=16754.9, self.low=16742.9, self.vol=385.21, self.amt=6451270.6402 
127.0.0.1 - - [18/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-18 16:15:00,609:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221218   155000    155459  ...    0.013558   0.100434       0
5951  20221218   155500    155959  ...    0.013100   0.098478       0
5952  20221218   160000    160459  ...    0.012640   0.096454       0
5953  20221218   160500    160959  ...    0.012180   0.094378       0
5954  20221218   161000    161459  ...    0.011723   0.092296       0

[5 rows x 18 columns]
2022-12-18 16:15:00,609:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671351299, self.tradeDate='20221218', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16751.2, self.close=16744.2, self.high=16754.9, self.low=16742.9, self.vol=385.21, self.amt=6451270.6402, ukdf['pct'].iloc[-1]=-0.000418 , ukdf['amount'].iloc[-1]=6451270.6402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.011723392945792449, signal=0, value_std=0.09229555563194092 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221218   040000    075959  1671321599  ...    721  0.914646  0.718202     1.0
722  20221218   080000    115959  1671335999  ...    722  0.956051  0.829937     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-54499.3764', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16736.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=138
self.closeSec=1671350399, self.tradeDate='20221218', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16736.5, self.close=16739.9, self.high=16795.0, self.low=16709.5, self.vol=26928.603, self.amt=451013734.4175 
127.0.0.1 - - [18/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-18 16:00:01,036:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671350399, self.tradeDate='20221218', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16736.5, self.close=16739.9, self.high=16795.0, self.low=16709.5, self.vol=26928.603, self.amt=451013734.4175 
2022-12-18 16:00:01,065:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221217   200000    235959  ...  40968.291  6.830872e+08 -0.000491
720  20221218   000000    035959  ...  23775.354  3.965878e+08 -0.000491
721  20221218   040000    075959  ...  33778.374  5.650731e+08  0.005023
722  20221218   080000    115959  ...  19014.025  3.180544e+08 -0.001879
723  20221218   120000    155959  ...  26928.603  4.510137e+08  0.000203

[5 rows x 11 columns]
2022-12-18 16:00:02,608:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221217   200000    235959  1671292799  ...    719  0.839180  0.506705     NaN
720  20221218   000000    035959  1671307199  ...    720  0.894041  0.665375     1.0
721  20221218   040000    075959  1671321599  ...    721  0.914646  0.718202     1.0
722  20221218   080000    115959  1671335999  ...    722  0.956051  0.829937     1.0
723  20221218   120000    155959  1671350399  ...    723  1.003667  0.955392     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-54149.43163940844', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16742.94885771', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


