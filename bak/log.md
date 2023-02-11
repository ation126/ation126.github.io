# 20230211 08:36:06

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21822
self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21639.9, self.close=21628.0, self.high=21642.5, self.low=21624.2, self.vol=564.794, self.amt=12218355.0757 
127.0.0.1 - - [11/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-11 08:30:00,807:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230211   080500    080959  ...         0.0        0.0       0
5858  20230211   081000    081459  ...         0.0        0.0       0
5859  20230211   081500    081959  ...         0.0        0.0       0
5860  20230211   082000    082459  ...         0.0        0.0       0
5861  20230211   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 08:30:00,807:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21639.9, self.close=21628.0, self.high=21642.5, self.low=21624.2, self.vol=564.794, self.amt=12218355.0757, ukdf['pct'].iloc[-1]=-0.00055 , ukdf['amount'].iloc[-1]=12218355.0757, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-306825.3888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21628.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21823
self.closeSec=1676075699, self.tradeDate='20230211', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21628.1, self.close=21658.1, self.high=21667.7, self.low=21623.8, self.vol=1169.927, self.amt=25329445.3415 
127.0.0.1 - - [11/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-11 08:35:00,499:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230211   081000    081459  ...         0.0        0.0       0
5859  20230211   081500    081959  ...         0.0        0.0       0
5860  20230211   082000    082459  ...         0.0        0.0       0
5861  20230211   082500    082959  ...         0.0        0.0       0
5862  20230211   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 08:35:00,500:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676075699, self.tradeDate='20230211', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21628.1, self.close=21658.1, self.high=21667.7, self.low=21623.8, self.vol=1169.927, self.amt=25329445.3415, ukdf['pct'].iloc[-1]=0.001392 , ukdf['amount'].iloc[-1]=25329445.3415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-308618.98356135088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21657.90581563', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1541  20230211   082500    082959  1676075399  ...  21624.2 -0.000550   1541    5

[5 rows x 11 columns]
2023-02-11 08:30:00,779:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-11 08:30:00,839:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230211   062500    062959  1676068199  ... -0.001284   1517    5  0.773105
214  20230211   065500    065959  1676069999  ... -0.000663   1523    5  0.775999
215  20230211   072500    072959  1676071799  ...  0.000051   1529    5  0.777406
216  20230211   075500    075959  1676073599  ... -0.000509   1535    5  0.776540
217  20230211   082500    082959  1676075399  ... -0.000550   1541    5  0.775105

[5 rows x 12 columns]
2023-02-11 08:30:00,859:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2110830, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230211, closeTime:082959, close:21628.0, total:909224.3076578999, factor:0.7751050494786227, factorCnt:0, side:buy 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7751050494786227, self.count=22389 

self.closeSec=1676075699, self.tradeDate='20230211', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21628.1, self.close=21658.1, self.high=21667.7, self.low=21623.8 
2023-02-11 08:35:00,434:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676075699, self.tradeDate='20230211', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21628.1, self.close=21658.1, self.high=21667.7, self.low=21623.8   
127.0.0.1 - - [11/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-11 08:35:00,479:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230211   081000    081459  1676074499  ...  21596.4 -0.000708   1538    2
1539  20230211   081500    081959  1676074799  ...  21595.1  0.000037   1539    3
1540  20230211   082000    082459  1676075099  ...  21597.2  0.001977   1540    4
1541  20230211   082500    082959  1676075399  ...  21624.2 -0.000550   1541    5
1542  20230211   083000    083459  1676075699  ...  21623.8  0.001392   1542    0

[5 rows x 11 columns]
2023-02-11 08:35:00,480:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-11 08:30:32,135:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230211    055959  21623.7  ...  44.166667  0.369554  0.683412
5772  20230211    062959  21521.5  ...  44.166667  0.373824  0.687839
5773  20230211    065959  21537.2  ...  44.166667  0.380076  0.688598
5774  20230211    072959  21560.5  ...  44.583333  0.386141  0.686217
5775  20230211    075959  21583.0  ...  45.000000  0.395687  0.679367

[5 rows x 33 columns]
0.5101663585951941
acc is : 0.5101663585951941
2023-02-11 08:30:32,269:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.467756  0.532244       1  ...  1.014161  -1.0    0.0  0.931939
537     1  0.485051  0.514949       1  ...  1.013069  -1.0    0.0  0.932943
538     1  0.490343  0.509657       1  ...  1.012012  -1.0    0.0  0.933917
539     1  0.494936  0.505064       1  ...  1.010342  -1.0    0.0  0.935457
540     0  0.508384  0.491616       1  ...  1.009903  -1.0    0.0  0.935864

[5 rows x 10 columns]
2023-02-11 08:30:32,304:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.467205  0.532795       1  ...  1.014161  -1.0    0.0  0.928676
46     1  0.484910  0.515090       1  ...  1.013069  -1.0    0.0  0.930527
47     1  0.489562  0.510438       1  ...  1.012012  -1.0    0.0  0.931474
48     1  0.494244  0.505756       1  ...  1.010342  -1.0    0.0  0.933011
49     0  0.508384  0.491616       1  ...  1.009903  -1.0    0.0  0.935864

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '41801.8172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21628.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230211   080000    080959  1676074199  21618.6  21611.7 -0.000319
2023-02-11 08:10:01,537:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11193 

self.closeSec=1676074799, self.tradeDate='20230211', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21611.8', self.close='21597.2'
2023-02-11 08:20:00,523:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676074799, self.tradeDate='20230211', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21611.8', self.close='21597.2'
2023-02-11 08:20:00,542:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230211   073000    073959  1676072399    21583  21622.2  0.001816
622  20230211   074000    074959  1676072999  21622.1  21612.8 -0.000435
623  20230211   075000    075959  1676073599  21612.7  21618.6  0.000268
624  20230211   080000    080959  1676074199  21618.6  21611.7 -0.000319
625  20230211   081000    081959  1676074799  21611.8  21597.2 -0.000671
2023-02-11 08:20:00,544:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11194 

self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21597.2', self.close='21628.1'
2023-02-11 08:30:01,290:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21597.2', self.close='21628.1'
2023-02-11 08:30:01,313:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230211   074000    074959  1676072999  21622.1  21612.8 -0.000435
623  20230211   075000    075959  1676073599  21612.7  21618.6  0.000268
624  20230211   080000    080959  1676074199  21618.6  21611.7 -0.000319
625  20230211   081000    081959  1676074799  21611.8  21597.2 -0.000671
626  20230211   082000    082959  1676075399  21597.2  21628.1  0.001431
2023-02-11 08:30:01,313:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230211   080000    080959  1676074199  21618.6  21611.7
2023-02-11 08:10:01,564:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11194 

self.closeSec=1676074799, self.tradeDate='20230211', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21611.8', self.close='21597.2'
127.0.0.1 - - [11/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-11 08:20:00,573:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676074799, self.tradeDate='20230211', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21611.8', self.close='21597.2'
2023-02-11 08:20:00,605:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230211   073000    073959  1676072399    21583  21622.2
17470  20230211   074000    074959  1676072999  21622.1  21612.8
17471  20230211   075000    075959  1676073599  21612.7  21618.6
17472  20230211   080000    080959  1676074199  21618.6  21611.7
17473  20230211   081000    081959  1676074799  21611.8  21597.2
2023-02-11 08:20:00,610:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11195 

self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21597.2', self.close='21628.1'
2023-02-11 08:30:01,332:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21597.2', self.close='21628.1'
2023-02-11 08:30:01,356:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230211   074000    074959  1676072999  21622.1  21612.8
17471  20230211   075000    075959  1676073599  21612.7  21618.6
17472  20230211   080000    080959  1676074199  21618.6  21611.7
17473  20230211   081000    081959  1676074799  21611.8  21597.2
17474  20230211   082000    082959  1676075399  21597.2  21628.1
2023-02-11 08:30:01,357:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230211   080000    080959  1676074199  21618.6  21611.7
2023-02-11 08:10:01,586:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11194 

self.closeSec=1676074799, self.tradeDate='20230211', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21611.8', self.close='21597.2'
2023-02-11 08:20:00,551:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676074799, self.tradeDate='20230211', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21611.8', self.close='21597.2'
2023-02-11 08:20:00,596:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230211   073000    073959  1676072399    21583  21622.2
12142  20230211   074000    074959  1676072999  21622.1  21612.8
12143  20230211   075000    075959  1676073599  21612.7  21618.6
12144  20230211   080000    080959  1676074199  21618.6  21611.7
12145  20230211   081000    081959  1676074799  21611.8  21597.2
2023-02-11 08:20:00,596:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11195 

self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21597.2', self.close='21628.1'
2023-02-11 08:30:01,323:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21597.2', self.close='21628.1'
127.0.0.1 - - [11/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-11 08:30:01,341:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230211   074000    074959  1676072999  21622.1  21612.8
12143  20230211   075000    075959  1676073599  21612.7  21618.6
12144  20230211   080000    080959  1676074199  21618.6  21611.7
12145  20230211   081000    081959  1676074799  21611.8  21597.2
12146  20230211   082000    082959  1676075399  21597.2  21628.1
2023-02-11 08:30:01,342:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [11/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17820
self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21639.9, self.close=21628.0, self.high=21642.5, self.low=21624.2, self.vol=564.794, self.amt=12218355.0757 
2023-02-11 08:30:00,803:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230211   080500    080959  ...         0.0        0.0       0
5858  20230211   081000    081459  ...         0.0        0.0       0
5859  20230211   081500    081959  ...         0.0        0.0       0
5860  20230211   082000    082459  ...         0.0        0.0       0
5861  20230211   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 08:30:00,807:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676075399, self.tradeDate='20230211', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21639.9, self.close=21628.0, self.high=21642.5, self.low=21624.2, self.vol=564.794, self.amt=12218355.0757, ukdf['pct'].iloc[-1]=-0.00055 , ukdf['amount'].iloc[-1]=12218355.0757, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17821
self.closeSec=1676075699, self.tradeDate='20230211', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21628.1, self.close=21658.1, self.high=21667.7, self.low=21623.8, self.vol=1169.927, self.amt=25329445.3415 
127.0.0.1 - - [11/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-11 08:35:00,495:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230211   081000    081459  ...         0.0        0.0       0
5859  20230211   081500    081959  ...         0.0        0.0       0
5860  20230211   082000    082459  ...         0.0        0.0       0
5861  20230211   082500    082959  ...         0.0        0.0       0
5862  20230211   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 08:35:00,495:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676075699, self.tradeDate='20230211', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21628.1, self.close=21658.1, self.high=21667.7, self.low=21623.8, self.vol=1169.927, self.amt=25329445.3415, ukdf['pct'].iloc[-1]=0.001392 , ukdf['amount'].iloc[-1]=25329445.3415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230210   200000    235959  1676044799  ...    719  0.696660  0.969925     1.0
720  20230211   000000    035959  1676059199  ...    720  0.736998  1.139375     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '1572.997993425', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21766.83246375', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [11/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=466
self.closeSec=1676073599, self.tradeDate='20230211', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=21764.0, self.close=21618.6, self.high=21785.4, self.low=21405.0, self.vol=69883.004, self.amt=1508449702.1226 
2023-02-11 08:00:01,301:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676073599, self.tradeDate='20230211', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=21764.0, self.close=21618.6, self.high=21785.4, self.low=21405.0, self.vol=69883.004, self.amt=1508449702.1226 
2023-02-11 08:00:01,338:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230210   120000    155959  ...   68529.707  1.493235e+09  0.003873
718  20230210   160000    195959  ...   48365.698  1.055254e+09 -0.008008
719  20230210   200000    235959  ...  120581.027  2.621305e+09 -0.003572
720  20230211   000000    035959  ...   86728.383  1.878822e+09  0.005275
721  20230211   040000    075959  ...   69883.004  1.508450e+09 -0.006644

[5 rows x 11 columns]
2023-02-11 08:00:03,808:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230210   120000    155959  1676015999  ...    717  0.608215  0.590645     NaN
718  20230210   160000    195959  1676030399  ...    718  0.674292  0.884227     1.0
719  20230210   200000    235959  1676044799  ...    719  0.696660  0.969925     1.0
720  20230211   000000    035959  1676059199  ...    720  0.736998  1.139375     1.0
721  20230211   040000    075959  1676073599  ...    721  0.751064  1.182652     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '-4804.986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21618.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


