# 20221217 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5786
self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16739.5, self.close=16723.7, self.high=16746.2, self.low=16722.5, self.vol=1062.933, self.amt=17787936.7493 
2022-12-17 16:10:01,424:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221217   154500    154959  ...         0.0        0.0       0
5950  20221217   155000    155459  ...         0.0        0.0       0
5951  20221217   155500    155959  ...         0.0        0.0       0
5952  20221217   160000    160459  ...         0.0        0.0       0
5953  20221217   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-17 16:10:01,425:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16739.5, self.close=16723.7, self.high=16746.2, self.low=16722.5, self.vol=1062.933, self.amt=17787936.7493, ukdf['pct'].iloc[-1]=-0.000944 , ukdf['amount'].iloc[-1]=17787936.7493, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-11758.97141913808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16724.70965533', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5787
self.closeSec=1671264899, self.tradeDate='20221217', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16724.5, self.close=16714.3, self.high=16724.9, self.low=16714.2, self.vol=738.829, self.amt=12353889.7247 
2022-12-17 16:15:00,609:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221217   155000    155459  ...         0.0        0.0       0
5951  20221217   155500    155959  ...         0.0        0.0       0
5952  20221217   160000    160459  ...         0.0        0.0       0
5953  20221217   160500    160959  ...         0.0        0.0       0
5954  20221217   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-17 16:15:00,610:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671264899, self.tradeDate='20221217', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16724.5, self.close=16714.3, self.high=16724.9, self.low=16714.2, self.vol=738.829, self.amt=12353889.7247, ukdf['pct'].iloc[-1]=-0.000562 , ukdf['amount'].iloc[-1]=12353889.7247, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-11152.2422517456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16714.6270781', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16739.5, self.close=16723.7, self.high=16746.2, self.low=16722.5 
2022-12-17 16:10:01,403:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16739.5, self.close=16723.7, self.high=16746.2, self.low=16722.5   
127.0.0.1 - - [17/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-17 16:10:01,456:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221217   154500    154959  1671263399  ...  16700.4 -0.000556   1629    3
1630  20221217   155000    155459  1671263699  ...  16710.5  0.000903   1630    4
1631  20221217   155500    155959  1671263999  ...  16725.3  0.000604   1631    5
1632  20221217   160000    160459  1671264299  ...  16728.0  0.000090   1632    0
1633  20221217   160500    160959  1671264599  ...  16722.5 -0.000944   1633    1

[5 rows x 11 columns]
2022-12-17 16:10:01,456:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8274162987156188, self.count=6353 

self.closeSec=1671264899, self.tradeDate='20221217', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16724.5, self.close=16714.3, self.high=16724.9, self.low=16714.2 
2022-12-17 16:15:00,532:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671264899, self.tradeDate='20221217', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16724.5, self.close=16714.3, self.high=16724.9, self.low=16714.2   
127.0.0.1 - - [17/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-17 16:15:00,568:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221217   155000    155459  1671263699  ...  16710.5  0.000903   1630    4
1631  20221217   155500    155959  1671263999  ...  16725.3  0.000604   1631    5
1632  20221217   160000    160459  1671264299  ...  16728.0  0.000090   1632    0
1633  20221217   160500    160959  1671264599  ...  16722.5 -0.000944   1633    1
1634  20221217   161000    161459  1671264899  ...  16714.2 -0.000562   1634    2

[5 rows x 11 columns]
2022-12-17 16:15:00,568:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-17 16:00:17,737:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221217    132959  16699.9  ...  49.166667  0.389319  0.829502
5787  20221217    135959  16714.2  ...  48.750000  0.382565  0.821593
5788  20221217    142959  16681.8  ...  49.166667  0.383811  0.813768
5789  20221217    145959  16685.4  ...  49.166667  0.389550  0.804437
5790  20221217    152959  16702.4  ...  49.166667  0.386399  0.797467

[5 rows x 33 columns]
0.5608856088560885
acc is : 0.5608856088560885
2022-12-17 16:00:17,799:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.511719  0.488281       0  ...  1.078728  -1.0    0.0  0.979352
538     1  0.498956  0.501044       1  ...  1.078489  -1.0    0.0  0.979570
539     0  0.506285  0.493715       1  ...  1.077396  -1.0    0.0  0.980562
540     0  0.507999  0.492001       0  ...  1.078332  -1.0    0.0  0.979711
541     0  0.500324  0.499676       1  ...  1.075094  -1.0    0.0  0.982652

[5 rows x 10 columns]
2022-12-17 16:00:17,810:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511715  0.488285       0  ...  1.078728  -1.0    0.0  0.984915
46     1  0.499838  0.500162       1  ...  1.078489  -1.0    0.0  0.985552
47     0  0.506181  0.493819       1  ...  1.077396  -1.0    0.0  0.984916
48     0  0.508292  0.491708       0  ...  1.078332  -1.0    0.0  0.981849
49     0  0.500324  0.499676       1  ...  1.075094  -1.0    0.0  0.982652

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '38913.62377816368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16737.91789258', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221217   154000    154959  1671263399  16708.4  16712.7  0.000251
2022-12-17 15:50:00,551:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3175 

self.closeSec=1671263999, self.tradeDate='20221217', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16712.7', self.close='16738'
2022-12-17 16:00:01,224:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671263999, self.tradeDate='20221217', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16712.7', self.close='16738'
2022-12-17 16:00:01,252:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221217   151000    151959  1671261599    16680    16698  0.001073
524  20221217   152000    152959  1671262199  16698.1  16687.8 -0.000611
525  20221217   153000    153959  1671262799  16687.9  16708.5  0.001240
526  20221217   154000    154959  1671263399  16708.4  16712.7  0.000251
527  20221217   155000    155959  1671263999  16712.7    16738  0.001514
2022-12-17 16:00:01,252:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3176 

self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16737.9', self.close='16724.6'
2022-12-17 16:10:01,556:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16737.9', self.close='16724.6'
2022-12-17 16:10:01,591:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221217   152000    152959  1671262199  16698.1  16687.8 -0.000611
525  20221217   153000    153959  1671262799  16687.9  16708.5  0.001240
526  20221217   154000    154959  1671263399  16708.4  16712.7  0.000251
527  20221217   155000    155959  1671263999  16712.7    16738  0.001514
528  20221217   160000    160959  1671264599  16737.9  16724.6 -0.000801
2022-12-17 16:10:01,592:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221217   154000    154959  1671263399  16708.4  16712.7
2022-12-17 15:50:00,580:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3176 

self.closeSec=1671263999, self.tradeDate='20221217', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16712.7', self.close='16738'
127.0.0.1 - - [17/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-17 16:00:01,241:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671263999, self.tradeDate='20221217', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16712.7', self.close='16738'
2022-12-17 16:00:01,265:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221217   151000    151959  1671261599    16680    16698
17516  20221217   152000    152959  1671262199  16698.1  16687.8
17517  20221217   153000    153959  1671262799  16687.9  16708.5
17518  20221217   154000    154959  1671263399  16708.4  16712.7
17519  20221217   155000    155959  1671263999  16712.7    16738
2022-12-17 16:00:01,265:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3177 

self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16737.9', self.close='16724.6'
2022-12-17 16:10:01,531:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16737.9', self.close='16724.6'
127.0.0.1 - - [17/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-17 16:10:01,545:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221217   152000    152959  1671262199  16698.1  16687.8
17517  20221217   153000    153959  1671262799  16687.9  16708.5
17518  20221217   154000    154959  1671263399  16708.4  16712.7
17519  20221217   155000    155959  1671263999  16712.7    16738
17520  20221217   160000    160959  1671264599  16737.9  16724.6
2022-12-17 16:10:01,545:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221217   154000    154959  1671263399  16708.4  16712.7
2022-12-17 15:50:00,569:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3176 

self.closeSec=1671263999, self.tradeDate='20221217', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16712.7', self.close='16738'
2022-12-17 16:00:01,251:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671263999, self.tradeDate='20221217', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16712.7', self.close='16738'
2022-12-17 16:00:01,280:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221217   151000    151959  1671261599    16680    16698
12188  20221217   152000    152959  1671262199  16698.1  16687.8
12189  20221217   153000    153959  1671262799  16687.9  16708.5
12190  20221217   154000    154959  1671263399  16708.4  16712.7
12191  20221217   155000    155959  1671263999  16712.7    16738
2022-12-17 16:00:01,281:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3177 

self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16737.9', self.close='16724.6'
2022-12-17 16:10:01,525:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16737.9', self.close='16724.6'
127.0.0.1 - - [17/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-17 16:10:01,553:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221217   152000    152959  1671262199  16698.1  16687.8
12189  20221217   153000    153959  1671262799  16687.9  16708.5
12190  20221217   154000    154959  1671263399  16708.4  16712.7
12191  20221217   155000    155959  1671263999  16712.7    16738
12192  20221217   160000    160959  1671264599  16737.9  16724.6
2022-12-17 16:10:01,553:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1784
self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16739.5, self.close=16723.7, self.high=16746.2, self.low=16722.5, self.vol=1062.933, self.amt=17787936.7493 
127.0.0.1 - - [17/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-17 16:10:01,466:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221217   154500    154959  ...    0.110268   0.251476       0
5950  20221217   155000    155459  ...    0.109936   0.251200       0
5951  20221217   155500    155959  ...    0.109604   0.250924       0
5952  20221217   160000    160459  ...    0.109276   0.250655       0
5953  20221217   160500    160959  ...    0.108950   0.250390       0

[5 rows x 18 columns]
2022-12-17 16:10:01,466:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671264599, self.tradeDate='20221217', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16739.5, self.close=16723.7, self.high=16746.2, self.low=16722.5, self.vol=1062.933, self.amt=17787936.7493, ukdf['pct'].iloc[-1]=-0.000944 , ukdf['amount'].iloc[-1]=17787936.7493, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.10894975398176049, signal=0, value_std=0.25038954410269276 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1785
self.closeSec=1671264899, self.tradeDate='20221217', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16724.5, self.close=16714.3, self.high=16724.9, self.low=16714.2, self.vol=738.829, self.amt=12353889.7247 
127.0.0.1 - - [17/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-17 16:15:00,610:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221217   155000    155459  ...    0.109936   0.251200       0
5951  20221217   155500    155959  ...    0.109604   0.250924       0
5952  20221217   160000    160459  ...    0.109276   0.250655       0
5953  20221217   160500    160959  ...    0.108950   0.250390       0
5954  20221217   161000    161459  ...    0.108624   0.250125       0

[5 rows x 18 columns]
2022-12-17 16:15:00,611:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671264899, self.tradeDate='20221217', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16724.5, self.close=16714.3, self.high=16724.9, self.low=16714.2, self.vol=738.829, self.amt=12353889.7247, ukdf['pct'].iloc[-1]=-0.000562 , ukdf['amount'].iloc[-1]=12353889.7247, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.10862437597961587, signal=0, value_std=0.25012486004126544 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221217   040000    075959  1671235199  ...    721  0.600340 -0.225650     NaN
722  20221217   080000    115959  1671249599  ...    722  0.673979  0.003568     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-58090.2756', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16669.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [17/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=132
self.closeSec=1671263999, self.tradeDate='20221217', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16667.5, self.close=16738.0, self.high=16764.0, self.low=16647.7, self.vol=45721.15, self.amt=763597423.9619 
2022-12-17 16:00:01,099:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671263999, self.tradeDate='20221217', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16667.5, self.close=16738.0, self.high=16764.0, self.low=16647.7, self.vol=45721.15, self.amt=763597423.9619 
2022-12-17 16:00:01,149:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221216   200000    235959  ...  107276.345  1.821694e+09 -0.003338
720  20221217   000000    035959  ...  114774.620  1.931465e+09 -0.006208
721  20221217   040000    075959  ...  134056.770  2.240063e+09 -0.013787
722  20221217   080000    115959  ...   66363.998  1.105574e+09  0.002611
723  20221217   120000    155959  ...   45721.150  7.635974e+08  0.004230

[5 rows x 11 columns]
2022-12-17 16:00:02,660:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221216   200000    235959  1671206399  ...    719  0.692185  0.053751     NaN
720  20221217   000000    035959  1671220799  ...    720  0.669449 -0.015307     NaN
721  20221217   040000    075959  1671235199  ...    721  0.600340 -0.225650     NaN
722  20221217   080000    115959  1671249599  ...    722  0.673979  0.003568     NaN
723  20221217   120000    155959  1671263999  ...    723  0.729073  0.174966     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-54393.53090609436', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16738.38078999', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


