# 20221207 18:35:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2934
self.closeSec=1670408999, self.tradeDate='20221207', self.openTime='182500', self.closeTime='182959', self.symbol='BTCUSDT', self.open=16792.7, self.close=16793.9, self.high=16794.6, self.low=16791.0, self.vol=617.309, self.amt=10366697.8876 
127.0.0.1 - - [07/Dec/2022 18:30:00] "POST / HTTP/1.1" 200 -
2022-12-07 18:30:00,567:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5977  20221207   180500    180959  ...    0.149898   0.286117       0
5978  20221207   181000    181459  ...    0.149734   0.286034       0
5979  20221207   181500    181959  ...    0.149569   0.285950       0
5980  20221207   182000    182459  ...    0.149412   0.285876       0
5981  20221207   182500    182959  ...    0.149255   0.285803       0

[5 rows x 18 columns]
2022-12-07 18:30:00,567:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670408999, self.tradeDate='20221207', self.openTime='182500', self.closeTime='182959',self.symbol='BTCUSDT',self.open=16792.7, self.close=16793.9, self.high=16794.6, self.low=16791.0, self.vol=617.309, self.amt=10366697.8876, ukdf['pct'].iloc[-1]=7.1e-05 , ukdf['amount'].iloc[-1]=10366697.8876, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5981, value=0.0, value_mean=0.1492549228632622, signal=0, value_std=0.28580278057593356 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15937.95005966176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16794.15559126', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2935
self.closeSec=1670409299, self.tradeDate='20221207', self.openTime='183000', self.closeTime='183459', self.symbol='BTCUSDT', self.open=16793.8, self.close=16809.3, self.high=16812.8, self.low=16793.8, self.vol=1006.821, self.amt=16921422.1828 
127.0.0.1 - - [07/Dec/2022 18:35:00] "POST / HTTP/1.1" 200 -
2022-12-07 18:35:00,487:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5978  20221207   181000    181459  ...    0.149734   0.286034       0
5979  20221207   181500    181959  ...    0.149569   0.285950       0
5980  20221207   182000    182459  ...    0.149412   0.285876       0
5981  20221207   182500    182959  ...    0.149255   0.285803       0
5982  20221207   183000    183459  ...    0.149100   0.285733       0

[5 rows x 18 columns]
2022-12-07 18:35:00,488:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670409299, self.tradeDate='20221207', self.openTime='183000', self.closeTime='183459',self.symbol='BTCUSDT',self.open=16793.8, self.close=16809.3, self.high=16812.8, self.low=16793.8, self.vol=1006.821, self.amt=16921422.1828, ukdf['pct'].iloc[-1]=0.000917 , ukdf['amount'].iloc[-1]=16921422.1828, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5982, value=0.0, value_mean=0.1491000590201236, signal=0, value_std=0.28573255969239364 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16890.57519388576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16809.98624026', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1661  20221207   182500    182959  1670408999  ...  16791.0  0.000071   1661    5

[5 rows x 11 columns]
2022-12-07 18:30:00,564:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2022-12-07 18:30:00,606:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
233  20221207   162500    162959  1670401799  ...  0.001851   1637    5  0.586474
234  20221207   165500    165959  1670403599  ...  0.000429   1643    5  0.594024
235  20221207   172500    172959  1670405399  ... -0.000398   1649    5  0.599502
236  20221207   175500    175959  1670407199  ...  0.000648   1655    5  0.603873
237  20221207   182500    182959  1670408999  ...  0.000071   1661    5  0.610459

[5 rows x 12 columns]
2022-12-07 18:30:00,623:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:12071830, name:factorcheck2, symbol:BTCUSDT, tradeDate:20221207, closeTime:182959, close:16793.9, total:885250.3500135001, factor:0.6104591562878663, factorCnt:0, side:buy 
127.0.0.1 - - [07/Dec/2022 18:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6104591562878663, self.count=3501 

self.closeSec=1670409299, self.tradeDate='20221207', self.openTime='183000', self.closeTime='183459', self.symbol='BTCUSDT', self.open=16793.8, self.close=16809.3, self.high=16812.8, self.low=16793.8 
2022-12-07 18:35:00,432:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670409299, self.tradeDate='20221207', self.openTime='183000', self.closeTime='183459',self.symbol='BTCUSDT',self.open=16793.8, self.close=16809.3, self.high=16812.8, self.low=16793.8   
2022-12-07 18:35:00,451:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1658  20221207   181000    181459  1670408099  ...  16797.3 -0.000910   1658    2
1659  20221207   181500    181959  1670408399  ...  16790.2 -0.000095   1659    3
1660  20221207   182000    182459  1670408699  ...  16792.0 -0.000298   1660    4
1661  20221207   182500    182959  1670408999  ...  16791.0  0.000071   1661    5
1662  20221207   183000    183459  1670409299  ...  16793.8  0.000917   1662    0

[5 rows x 11 columns]
2022-12-07 18:35:00,451:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-07 18:30:23,393:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5791  20221207    155959  16807.3  ...  50.416667  0.386729  0.567871
5792  20221207    162959  16755.4  ...  50.833333  0.399597  0.579164
5793  20221207    165959  16780.9  ...  50.833333  0.402728  0.588875
5794  20221207    172959  16785.8  ...  51.250000  0.416873  0.594164
5795  20221207    175959  16812.5  ...  51.250000  0.423810  0.597220

[5 rows x 33 columns]
0.5285451197053407
acc is : 0.5285451197053407
2022-12-07 18:30:23,555:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
538     1  0.450636  0.549364       1  ...  0.950371  -1.0    0.0  1.009645
539     1  0.468528  0.531472       1  ...  0.950037  -1.0    0.0  1.010000
540     1  0.466841  0.533159       1  ...  0.948515  -1.0    0.0  1.011619
541     1  0.478415  0.521585       1  ...  0.947759  -1.0    0.0  1.012425
542     1  0.489999  0.510001       0  ...  0.949572  -1.0    0.0  1.010488

[5 rows x 10 columns]
2022-12-07 18:30:23,587:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.450379  0.549621       1  ...  0.950371  -1.0    0.0  1.007118
46     1  0.468509  0.531491       1  ...  0.950037  -1.0    0.0  1.009727
47     1  0.466497  0.533503       1  ...  0.948515  -1.0    0.0  1.011011
48     1  0.478047  0.521953       1  ...  0.947759  -1.0    0.0  1.011816
49     1  0.489999  0.510001       0  ...  0.949572  -1.0    0.0  1.010488

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '6561.912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16795.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

540  20221207   180000    180959  1670407799  16825.9  16814.7 -0.000672
2022-12-07 18:10:01,989:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Dec/2022 18:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1749 

self.closeSec=1670408399, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181959', self.symbol='BTCUSDT', self.open='16814.6', self.close='16797.7'
2022-12-07 18:20:00,513:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670408399, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181959',self.symbol='BTCUSDT',self.open='16814.6', self.close='16797.7'
2022-12-07 18:20:00,538:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
537  20221207   173000    173959  1670405999  16812.5  16799.9 -0.000755
538  20221207   174000    174959  1670406599  16799.9    16810  0.000601
539  20221207   175000    175959  1670407199    16810    16826  0.000952
540  20221207   180000    180959  1670407799  16825.9  16814.7 -0.000672
541  20221207   181000    181959  1670408399  16814.6  16797.7 -0.001011
2022-12-07 18:20:00,538:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Dec/2022 18:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1750 

self.closeSec=1670408999, self.tradeDate='20221207', self.openTime='182000', self.closeTime='182959', self.symbol='BTCUSDT', self.open='16797.8', self.close='16793.9'
2022-12-07 18:30:00,739:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670408999, self.tradeDate='20221207', self.openTime='182000', self.closeTime='182959',self.symbol='BTCUSDT',self.open='16797.8', self.close='16793.9'
2022-12-07 18:30:00,807:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
538  20221207   174000    174959  1670406599  16799.9    16810  0.000601
539  20221207   175000    175959  1670407199    16810    16826  0.000952
540  20221207   180000    180959  1670407799  16825.9  16814.7 -0.000672
541  20221207   181000    181959  1670408399  16814.6  16797.7 -0.001011
542  20221207   182000    182959  1670408999  16797.8  16793.9 -0.000226
2022-12-07 18:30:00,808:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17388  20221207   180000    180959  1670407799  16825.9  16814.7
2022-12-07 18:10:02,053:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Dec/2022 18:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1750 

self.closeSec=1670408399, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181959', self.symbol='BTCUSDT', self.open='16814.6', self.close='16797.7'
2022-12-07 18:20:00,519:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670408399, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181959',self.symbol='BTCUSDT',self.open='16814.6', self.close='16797.7'
2022-12-07 18:20:00,525:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17385  20221207   173000    173959  1670405999  16812.5  16799.9
17386  20221207   174000    174959  1670406599  16799.9    16810
17387  20221207   175000    175959  1670407199    16810    16826
17388  20221207   180000    180959  1670407799  16825.9  16814.7
17389  20221207   181000    181959  1670408399  16814.6  16797.7
2022-12-07 18:20:00,525:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Dec/2022 18:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1751 

self.closeSec=1670408999, self.tradeDate='20221207', self.openTime='182000', self.closeTime='182959', self.symbol='BTCUSDT', self.open='16797.8', self.close='16793.9'
2022-12-07 18:30:00,780:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670408999, self.tradeDate='20221207', self.openTime='182000', self.closeTime='182959',self.symbol='BTCUSDT',self.open='16797.8', self.close='16793.9'
2022-12-07 18:30:00,827:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17386  20221207   174000    174959  1670406599  16799.9    16810
17387  20221207   175000    175959  1670407199    16810    16826
17388  20221207   180000    180959  1670407799  16825.9  16814.7
17389  20221207   181000    181959  1670408399  16814.6  16797.7
17390  20221207   182000    182959  1670408999  16797.8  16793.9
2022-12-07 18:30:00,827:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12204  20221207   180000    180959  1670407799  16825.9  16814.7
2022-12-07 18:10:02,022:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1750 

self.closeSec=1670408399, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181959', self.symbol='BTCUSDT', self.open='16814.6', self.close='16797.7'
2022-12-07 18:20:00,536:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670408399, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181959',self.symbol='BTCUSDT',self.open='16814.6', self.close='16797.7'
127.0.0.1 - - [07/Dec/2022 18:20:00] "POST / HTTP/1.1" 200 -
2022-12-07 18:20:00,548:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12201  20221207   173000    173959  1670405999  16812.5  16799.9
12202  20221207   174000    174959  1670406599  16799.9    16810
12203  20221207   175000    175959  1670407199    16810    16826
12204  20221207   180000    180959  1670407799  16825.9  16814.7
12205  20221207   181000    181959  1670408399  16814.6  16797.7
2022-12-07 18:20:00,548:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Dec/2022 18:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1751 

self.closeSec=1670408999, self.tradeDate='20221207', self.openTime='182000', self.closeTime='182959', self.symbol='BTCUSDT', self.open='16797.8', self.close='16793.9'
2022-12-07 18:30:00,765:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670408999, self.tradeDate='20221207', self.openTime='182000', self.closeTime='182959',self.symbol='BTCUSDT',self.open='16797.8', self.close='16793.9'
2022-12-07 18:30:00,809:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12202  20221207   174000    174959  1670406599  16799.9    16810
12203  20221207   175000    175959  1670407199    16810    16826
12204  20221207   180000    180959  1670407799  16825.9  16814.7
12205  20221207   181000    181959  1670408399  16814.6  16797.7
12206  20221207   182000    182959  1670408999  16797.8  16793.9
2022-12-07 18:30:00,809:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0
722  20221207   080000    115959  1670385599  ...    722  1.084938  2.647182     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-16610.74134876276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17018.14662842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [07/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=72
self.closeSec=1670399999, self.tradeDate='20221207', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17017.4, self.close=16755.7, self.high=17036.6, self.low=16719.1, self.vol=97327.468, self.amt=1641000514.5662 
2022-12-07 16:00:00,889:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670399999, self.tradeDate='20221207', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17017.4, self.close=16755.7, self.high=17036.6, self.low=16719.1, self.vol=97327.468, self.amt=1641000514.5662 
2022-12-07 16:00:00,923:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221206   200000    235959  ...  69024.422  1.172189e+09  0.000018
720  20221207   000000    035959  ...  56413.953  9.566549e+08 -0.000636
721  20221207   040000    075959  ...  51125.606  8.698549e+08  0.006714
722  20221207   080000    115959  ...  42347.692  7.222808e+08 -0.003548
723  20221207   120000    155959  ...  97327.468  1.641001e+09 -0.015378

[5 rows x 11 columns]
2022-12-07 16:00:02,301:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221206   200000    235959  1670342399  ...    719  0.716348  1.398787     1.0
720  20221207   000000    035959  1670356799  ...    720  1.120770  3.120988     1.0
721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0
722  20221207   080000    115959  1670385599  ...    722  1.084938  2.647182     1.0
723  20221207   120000    155959  1670399999  ...    723  0.702535  1.042009     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-32007.63118873926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16755.49967267', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


