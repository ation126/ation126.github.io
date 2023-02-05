# 20230205 16:35:46

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20190
self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23372.1, self.close=23374.9, self.high=23374.9, self.low=23367.5, self.vol=177.721, self.amt=4153291.3188 
127.0.0.1 - - [05/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-05 16:30:00,885:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230205   160500    160959  ...         0.0        0.0       0
5954  20230205   161000    161459  ...         0.0        0.0       0
5955  20230205   161500    161959  ...         0.0        0.0       0
5956  20230205   162000    162459  ...         0.0        0.0       0
5957  20230205   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 16:30:00,888:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23372.1, self.close=23374.9, self.high=23374.9, self.low=23367.5, self.vol=177.721, self.amt=4153291.3188, ukdf['pct'].iloc[-1]=0.00012 , ukdf['amount'].iloc[-1]=4153291.3188, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-411993.07601220496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23375.76829321', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20191
self.closeSec=1675586099, self.tradeDate='20230205', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23374.9, self.close=23380.0, self.high=23386.7, self.low=23367.8, self.vol=333.754, self.amt=7802593.4212 
127.0.0.1 - - [05/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-05 16:35:00,579:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230205   161000    161459  ...         0.0        0.0       0
5955  20230205   161500    161959  ...         0.0        0.0       0
5956  20230205   162000    162459  ...         0.0        0.0       0
5957  20230205   162500    162959  ...         0.0        0.0       0
5958  20230205   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 16:35:00,579:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675586099, self.tradeDate='20230205', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23374.9, self.close=23380.0, self.high=23386.7, self.low=23367.8, self.vol=333.754, self.amt=7802593.4212, ukdf['pct'].iloc[-1]=0.000218 , ukdf['amount'].iloc[-1]=7802593.4212, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-412247.7232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23380', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1636  20230205   162000    162459  1675585499  ...  23367.1 -0.000013   1636    4
1637  20230205   162500    162959  1675585799  ...  23367.5  0.000120   1637    5

[5 rows x 11 columns]
2023-02-05 16:30:00,825:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-05 16:30:00,889:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230205   142500    142959  1675578599  ...  0.000240   1613    5  0.601772
230  20230205   145500    145959  1675580399  ... -0.000038   1619    5  0.598475
231  20230205   152500    152959  1675582199  ...  0.000210   1625    5  0.595696
232  20230205   155500    155959  1675583999  ... -0.000098   1631    5  0.593562
233  20230205   162500    162959  1675585799  ...  0.000120   1637    5  0.591636

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.591636017796598, self.count=20757 

self.closeSec=1675586099, self.tradeDate='20230205', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23374.9, self.close=23380.0, self.high=23386.7, self.low=23367.8 
2023-02-05 16:35:00,479:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675586099, self.tradeDate='20230205', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23374.9, self.close=23380.0, self.high=23386.7, self.low=23367.8   
127.0.0.1 - - [05/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-05 16:35:00,516:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230205   161000    161459  1675584899  ...  23372.9 -0.000265   1634    2
1635  20230205   161500    161959  1675585199  ...  23367.7 -0.000128   1635    3
1636  20230205   162000    162459  1675585499  ...  23367.1 -0.000013   1636    4
1637  20230205   162500    162959  1675585799  ...  23367.5  0.000120   1637    5
1638  20230205   163000    163459  1675586099  ...  23367.8  0.000218   1638    0

[5 rows x 11 columns]
2023-02-05 16:35:00,516:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-05 16:30:32,068:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230205    135959  23370.0  ...  46.250000  0.487767  0.621120
5788  20230205    142959  23374.3  ...  45.833333  0.481442  0.621107
5789  20230205    145959  23355.1  ...  45.833333  0.493890  0.614873
5790  20230205    152959  23390.8  ...  45.416667  0.491854  0.610107
5791  20230205    155959  23384.8  ...  45.000000  0.489212  0.607007

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-02-05 16:30:32,235:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.499951  0.500049       0  ...  0.981372  -1.0    0.0  1.043659
538     1  0.492718  0.507282       1  ...  0.979880  -1.0    0.0  1.045245
539     0  0.504992  0.495008       0  ...  0.980131  -1.0    0.0  1.044977
540     1  0.495233  0.504767       0  ...  0.980454  -1.0    0.0  1.044633
541     1  0.493692  0.506308       0  ...  0.980702  -1.0    0.0  1.044369

[5 rows x 10 columns]
2023-02-05 16:30:32,255:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499646  0.500354       0  ...  0.991366  -1.0    0.0  1.032959
46     1  0.491931  0.508069       1  ...  0.979880  -1.0    0.0  1.033733
47     0  0.504841  0.495159       0  ...  0.980131  -1.0    0.0  1.037439
48     1  0.494563  0.505437       0  ...  0.980454  -1.0    0.0  1.032193
49     1  0.493692  0.506308       0  ...  0.980702  -1.0    0.0  1.044369

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '9599.38112607845', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23377.91077665', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230205   160000    160959  1675584599    23377  23381.6  0.000197
2023-02-05 16:10:01,545:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10377 

self.closeSec=1675585199, self.tradeDate='20230205', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23381.7', self.close='23372.4'
2023-02-05 16:20:00,773:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675585199, self.tradeDate='20230205', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23381.7', self.close='23372.4'
127.0.0.1 - - [05/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-05 16:20:00,816:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230205   153000    153959  1675582799  23384.8  23380.1 -0.000201
526  20230205   154000    154959  1675583399  23380.1  23374.8 -0.000227
527  20230205   155000    155959  1675583999  23374.8    23377  0.000094
528  20230205   160000    160959  1675584599    23377  23381.6  0.000197
529  20230205   161000    161959  1675585199  23381.7  23372.4 -0.000393
2023-02-05 16:20:00,819:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [05/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10378 

self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23372.4', self.close='23374.9'
2023-02-05 16:30:01,040:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23372.4', self.close='23374.9'
2023-02-05 16:30:01,056:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230205   154000    154959  1675583399  23380.1  23374.8 -0.000227
527  20230205   155000    155959  1675583999  23374.8    23377  0.000094
528  20230205   160000    160959  1675584599    23377  23381.6  0.000197
529  20230205   161000    161959  1675585199  23381.7  23372.4 -0.000393
530  20230205   162000    162959  1675585799  23372.4  23374.9  0.000107
2023-02-05 16:30:01,056:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230205   160000    160959  1675584599    23377  23381.6
2023-02-05 16:10:01,595:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10378 

self.closeSec=1675585199, self.tradeDate='20230205', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23381.7', self.close='23372.4'
2023-02-05 16:20:00,764:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675585199, self.tradeDate='20230205', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23381.7', self.close='23372.4'
2023-02-05 16:20:00,809:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230205   153000    153959  1675582799  23384.8  23380.1
17518  20230205   154000    154959  1675583399  23380.1  23374.8
17519  20230205   155000    155959  1675583999  23374.8    23377
17520  20230205   160000    160959  1675584599    23377  23381.6
17521  20230205   161000    161959  1675585199  23381.7  23372.4
2023-02-05 16:20:00,809:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10379 

self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23372.4', self.close='23374.9'
2023-02-05 16:30:01,029:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23372.4', self.close='23374.9'
127.0.0.1 - - [05/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-05 16:30:01,055:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230205   154000    154959  1675583399  23380.1  23374.8
17519  20230205   155000    155959  1675583999  23374.8    23377
17520  20230205   160000    160959  1675584599    23377  23381.6
17521  20230205   161000    161959  1675585199  23381.7  23372.4
17522  20230205   162000    162959  1675585799  23372.4  23374.9
2023-02-05 16:30:01,055:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230205   160000    160959  1675584599    23377  23381.6
2023-02-05 16:10:01,552:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10378 

self.closeSec=1675585199, self.tradeDate='20230205', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23381.7', self.close='23372.4'
2023-02-05 16:20:00,806:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675585199, self.tradeDate='20230205', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23381.7', self.close='23372.4'
127.0.0.1 - - [05/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-05 16:20:00,824:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230205   153000    153959  1675582799  23384.8  23380.1
12190  20230205   154000    154959  1675583399  23380.1  23374.8
12191  20230205   155000    155959  1675583999  23374.8    23377
12192  20230205   160000    160959  1675584599    23377  23381.6
12193  20230205   161000    161959  1675585199  23381.7  23372.4
2023-02-05 16:20:00,825:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10379 

self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23372.4', self.close='23374.9'
2023-02-05 16:30:01,017:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23372.4', self.close='23374.9'
127.0.0.1 - - [05/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-05 16:30:01,057:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230205   154000    154959  1675583399  23380.1  23374.8
12191  20230205   155000    155959  1675583999  23374.8    23377
12192  20230205   160000    160959  1675584599    23377  23381.6
12193  20230205   161000    161959  1675585199  23381.7  23372.4
12194  20230205   162000    162959  1675585799  23372.4  23374.9
2023-02-05 16:30:01,057:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16188
self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23372.1, self.close=23374.9, self.high=23374.9, self.low=23367.5, self.vol=177.721, self.amt=4153291.3188 
127.0.0.1 - - [05/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-05 16:30:00,887:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230205   160500    160959  ...         0.0        0.0       0
5954  20230205   161000    161459  ...         0.0        0.0       0
5955  20230205   161500    161959  ...         0.0        0.0       0
5956  20230205   162000    162459  ...         0.0        0.0       0
5957  20230205   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 16:30:00,887:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675585799, self.tradeDate='20230205', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23372.1, self.close=23374.9, self.high=23374.9, self.low=23367.5, self.vol=177.721, self.amt=4153291.3188, ukdf['pct'].iloc[-1]=0.00012 , ukdf['amount'].iloc[-1]=4153291.3188, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16189
self.closeSec=1675586099, self.tradeDate='20230205', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23374.9, self.close=23380.0, self.high=23386.7, self.low=23367.8, self.vol=333.754, self.amt=7802593.4212 
127.0.0.1 - - [05/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-05 16:35:00,577:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230205   161000    161459  ...         0.0        0.0       0
5955  20230205   161500    161959  ...         0.0        0.0       0
5956  20230205   162000    162459  ...         0.0        0.0       0
5957  20230205   162500    162959  ...         0.0        0.0       0
5958  20230205   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 16:35:00,579:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675586099, self.tradeDate='20230205', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23374.9, self.close=23380.0, self.high=23386.7, self.low=23367.8, self.vol=333.754, self.amt=7802593.4212, ukdf['pct'].iloc[-1]=0.000218 , ukdf['amount'].iloc[-1]=7802593.4212, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230205   040000    075959  1675555199  ...    721  0.548186 -0.055113     NaN
722  20230205   080000    115959  1675569599  ...    722  0.640686  0.249238     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-13899.676123029', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23343.36875775', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [05/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=432
self.closeSec=1675583999, self.tradeDate='20230205', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23343.3, self.close=23377.0, self.high=23436.0, self.low=23327.5, self.vol=20096.361, self.amt=469779651.3213 
2023-02-05 16:00:01,679:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675583999, self.tradeDate='20230205', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23343.3, self.close=23377.0, self.high=23436.0, self.low=23327.5, self.vol=20096.361, self.amt=469779651.3213 
2023-02-05 16:00:01,699:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230204   200000    235959  ...  70032.864  1.643729e+09  0.002607
720  20230205   000000    035959  ...  25724.048  6.025431e+08  0.000307
721  20230205   040000    075959  ...  27115.818  6.335307e+08 -0.004469
722  20230205   080000    115959  ...  34347.877  8.003898e+08  0.000892
723  20230205   120000    155959  ...  20096.361  4.697797e+08  0.001439

[5 rows x 11 columns]
2023-02-05 16:00:03,668:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230204   200000    235959  1675526399  ...    719  0.606331  0.137386     NaN
720  20230205   000000    035959  1675540799  ...    720  0.578135  0.034442     NaN
721  20230205   040000    075959  1675555199  ...    721  0.548186 -0.055113     NaN
722  20230205   080000    115959  1675569599  ...    722  0.640686  0.249238     NaN
723  20230205   120000    155959  1675583999  ...    723  0.579785  0.060318     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-12526.15226886324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23378.61985759', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


