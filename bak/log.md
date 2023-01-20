# 20230120 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [20/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15578
self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20951.2, self.close=20965.3, self.high=20972.6, self.low=20944.2, self.vol=819.063, self.amt=17166825.5376 
2023-01-20 16:10:01,517:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230120   154500    154959  ...         0.0        0.0       0
5950  20230120   155000    155459  ...         0.0        0.0       0
5951  20230120   155500    155959  ...         0.0        0.0       0
5952  20230120   160000    160459  ...         0.0        0.0       0
5953  20230120   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-20 16:10:01,517:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20951.2, self.close=20965.3, self.high=20972.6, self.low=20944.2, self.vol=819.063, self.amt=17166825.5376, ukdf['pct'].iloc[-1]=0.000668 , ukdf['amount'].iloc[-1]=17166825.5376, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-266940.736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20965.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15579
self.closeSec=1674202499, self.tradeDate='20230120', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20965.3, self.close=20952.5, self.high=20969.1, self.low=20949.0, self.vol=582.226, self.amt=12204054.8605 
2023-01-20 16:15:00,781:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230120   155000    155459  ...         0.0        0.0       0
5951  20230120   155500    155959  ...         0.0        0.0       0
5952  20230120   160000    160459  ...         0.0        0.0       0
5953  20230120   160500    160959  ...         0.0        0.0       0
5954  20230120   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-20 16:15:00,781:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674202499, self.tradeDate='20230120', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20965.3, self.close=20952.5, self.high=20969.1, self.low=20949.0, self.vol=582.226, self.amt=12204054.8605, ukdf['pct'].iloc[-1]=-0.000611 , ukdf['amount'].iloc[-1]=12204054.8605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-266234.57869636288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20953.56513388', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=30, self.factor=0.4281371819997917, self.count=16144 

self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20951.2, self.close=20965.3, self.high=20972.6, self.low=20944.2 
2023-01-20 16:10:01,468:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20951.2, self.close=20965.3, self.high=20972.6, self.low=20944.2   
2023-01-20 16:10:01,605:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230120   154500    154959  1674200999  ...  20967.1 -0.000238   1629    3
1630  20230120   155000    155459  1674201299  ...  20945.0 -0.001292   1630    4
1631  20230120   155500    155959  1674201599  ...  20948.6  0.000263   1631    5
1632  20230120   160000    160459  1674201899  ...  20945.7 -0.000134   1632    0
1633  20230120   160500    160959  1674202199  ...  20944.2  0.000668   1633    1

[5 rows x 11 columns]
2023-01-20 16:10:01,605:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=30, self.factor=0.4281371819997917, self.count=16145 

self.closeSec=1674202499, self.tradeDate='20230120', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20965.3, self.close=20952.5, self.high=20969.1, self.low=20949.0 
2023-01-20 16:15:00,627:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674202499, self.tradeDate='20230120', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20965.3, self.close=20952.5, self.high=20969.1, self.low=20949.0   
127.0.0.1 - - [20/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-20 16:15:00,653:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230120   155000    155459  1674201299  ...  20945.0 -0.001292   1630    4
1631  20230120   155500    155959  1674201599  ...  20948.6  0.000263   1631    5
1632  20230120   160000    160459  1674201899  ...  20945.7 -0.000134   1632    0
1633  20230120   160500    160959  1674202199  ...  20944.2  0.000668   1633    1
1634  20230120   161000    161459  1674202499  ...  20949.0 -0.000611   1634    2

[5 rows x 11 columns]
2023-01-20 16:15:00,653:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-20 16:00:36,084:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230120    132959  20990.5  ...  51.666667  0.499847  0.293150
5787  20230120    135959  20978.7  ...  52.083333  0.499981  0.302517
5788  20230120    142959  20979.3  ...  52.083333  0.500186  0.311153
5789  20230120    145959  20977.4  ...  52.083333  0.490802  0.324086
5790  20230120    152959  20939.1  ...  52.500000  0.498073  0.332470

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-01-20 16:00:36,273:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493667  0.506333       1  ...  1.059684   1.0    0.0  1.221231
538     1  0.492850  0.507150       1  ...  1.059729   1.0    0.0  1.221283
539     1  0.492765  0.507235       0  ...  1.057653   1.0    0.0  1.218891
540     1  0.476140  0.523860       1  ...  1.059224   1.0    0.0  1.220701
541     0  0.507374  0.492626       0  ...  1.058406   1.0    0.0  1.219758

[5 rows x 10 columns]
2023-01-20 16:00:36,287:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493512  0.506488       1  ...  1.059684   1.0    0.0  1.237226
46     1  0.492871  0.507129       1  ...  1.059729   1.0    0.0  1.231043
47     1  0.492839  0.507161       0  ...  1.057653   1.0    0.0  1.222748
48     1  0.476102  0.523898       1  ...  1.059224   1.0    0.0  1.225996
49     0  0.507374  0.492626       0  ...  1.058406   1.0    0.0  1.219758

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.709', 'enterprice': '20883.4', 'countrevence': '0', 'unrealprofit': '2414.65011868613', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20955.03220857', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230120   154000    154959  1674200999  20965.8  20975.7  0.000472
2023-01-20 15:50:00,581:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8071 

self.closeSec=1674201599, self.tradeDate='20230120', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20975.6', self.close='20954.2'
2023-01-20 16:00:01,568:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674201599, self.tradeDate='20230120', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20975.6', self.close='20954.2'
2023-01-20 16:00:01,585:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230120   151000    151959  1674199199  20947.2  20914.9 -0.001547
524  20230120   152000    152959  1674199799  20914.9  20970.3  0.002649
525  20230120   153000    153959  1674200399  20970.3  20965.8 -0.000215
526  20230120   154000    154959  1674200999  20965.8  20975.7  0.000472
527  20230120   155000    155959  1674201599  20975.6  20954.2 -0.001025
2023-01-20 16:00:01,585:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8072 

self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20954.1', self.close='20965.3'
2023-01-20 16:10:01,535:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20954.1', self.close='20965.3'
127.0.0.1 - - [20/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-20 16:10:01,634:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230120   152000    152959  1674199799  20914.9  20970.3  0.002649
525  20230120   153000    153959  1674200399  20970.3  20965.8 -0.000215
526  20230120   154000    154959  1674200999  20965.8  20975.7  0.000472
527  20230120   155000    155959  1674201599  20975.6  20954.2 -0.001025
528  20230120   160000    160959  1674202199  20954.1  20965.3  0.000530
2023-01-20 16:10:01,635:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230120   154000    154959  1674200999  20965.8  20975.7
2023-01-20 15:50:00,574:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8072 

self.closeSec=1674201599, self.tradeDate='20230120', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20975.6', self.close='20954.2'
2023-01-20 16:00:01,576:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674201599, self.tradeDate='20230120', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20975.6', self.close='20954.2'
2023-01-20 16:00:01,610:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230120   151000    151959  1674199199  20947.2  20914.9
17516  20230120   152000    152959  1674199799  20914.9  20970.3
17517  20230120   153000    153959  1674200399  20970.3  20965.8
17518  20230120   154000    154959  1674200999  20965.8  20975.7
17519  20230120   155000    155959  1674201599  20975.6  20954.2
2023-01-20 16:00:01,612:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8073 

self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20954.1', self.close='20965.3'
2023-01-20 16:10:01,603:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20954.1', self.close='20965.3'
2023-01-20 16:10:01,640:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230120   152000    152959  1674199799  20914.9  20970.3
17517  20230120   153000    153959  1674200399  20970.3  20965.8
17518  20230120   154000    154959  1674200999  20965.8  20975.7
17519  20230120   155000    155959  1674201599  20975.6  20954.2
17520  20230120   160000    160959  1674202199  20954.1  20965.3
2023-01-20 16:10:01,640:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230120   154000    154959  1674200999  20965.8  20975.7
2023-01-20 15:50:00,570:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8072 

self.closeSec=1674201599, self.tradeDate='20230120', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20975.6', self.close='20954.2'
127.0.0.1 - - [20/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-20 16:00:01,589:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674201599, self.tradeDate='20230120', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20975.6', self.close='20954.2'
2023-01-20 16:00:01,662:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230120   151000    151959  1674199199  20947.2  20914.9
12188  20230120   152000    152959  1674199799  20914.9  20970.3
12189  20230120   153000    153959  1674200399  20970.3  20965.8
12190  20230120   154000    154959  1674200999  20965.8  20975.7
12191  20230120   155000    155959  1674201599  20975.6  20954.2
2023-01-20 16:00:01,662:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8073 

self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20954.1', self.close='20965.3'
127.0.0.1 - - [20/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-20 16:10:01,589:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20954.1', self.close='20965.3'
2023-01-20 16:10:01,637:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230120   152000    152959  1674199799  20914.9  20970.3
12189  20230120   153000    153959  1674200399  20970.3  20965.8
12190  20230120   154000    154959  1674200999  20965.8  20975.7
12191  20230120   155000    155959  1674201599  20975.6  20954.2
12192  20230120   160000    160959  1674202199  20954.1  20965.3
2023-01-20 16:10:01,638:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11576
self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20951.2, self.close=20965.3, self.high=20972.6, self.low=20944.2, self.vol=819.063, self.amt=17166825.5376 
127.0.0.1 - - [20/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-20 16:10:01,550:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230120   154500    154959  ...         0.0        0.0       0
5950  20230120   155000    155459  ...         0.0        0.0       0
5951  20230120   155500    155959  ...         0.0        0.0       0
5952  20230120   160000    160459  ...         0.0        0.0       0
5953  20230120   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-20 16:10:01,550:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674202199, self.tradeDate='20230120', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20951.2, self.close=20965.3, self.high=20972.6, self.low=20944.2, self.vol=819.063, self.amt=17166825.5376, ukdf['pct'].iloc[-1]=0.000668 , ukdf['amount'].iloc[-1]=17166825.5376, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11577
self.closeSec=1674202499, self.tradeDate='20230120', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20965.3, self.close=20952.5, self.high=20969.1, self.low=20949.0, self.vol=582.226, self.amt=12204054.8605 
127.0.0.1 - - [20/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-20 16:15:00,741:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230120   155000    155459  ...         0.0        0.0       0
5951  20230120   155500    155959  ...         0.0        0.0       0
5952  20230120   160000    160459  ...         0.0        0.0       0
5953  20230120   160500    160959  ...         0.0        0.0       0
5954  20230120   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-20 16:15:00,743:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674202499, self.tradeDate='20230120', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20965.3, self.close=20952.5, self.high=20969.1, self.low=20949.0, self.vol=582.226, self.amt=12204054.8605, ukdf['pct'].iloc[-1]=-0.000611 , ukdf['amount'].iloc[-1]=12204054.8605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230120   040000    075959  1674172799  ...    721  0.148034 -1.417982    -1.0
722  20230120   080000    115959  1674187199  ...    722  0.127783 -1.428838    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '4114.8718', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21086.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [20/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=336
self.closeSec=1674201599, self.tradeDate='20230120', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21086.2, self.close=20954.2, self.high=21125.0, self.low=20856.4, self.vol=54029.169, self.amt=1133558008.3459 
2023-01-20 16:00:01,431:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674201599, self.tradeDate='20230120', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21086.2, self.close=20954.2, self.high=21125.0, self.low=20856.4, self.vol=54029.169, self.amt=1133558008.3459 
2023-01-20 16:00:01,464:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230119   200000    235959  ...  108038.719  2.247319e+09  0.006239
720  20230120   000000    035959  ...   86336.471  1.809397e+09  0.010508
721  20230120   040000    075959  ...   66652.701  1.403445e+09 -0.001034
722  20230120   080000    115959  ...   49417.658  1.042931e+09  0.000850
723  20230120   120000    155959  ...   54029.169  1.133558e+09 -0.006260

[5 rows x 11 columns]
2023-01-20 16:00:03,356:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230119   200000    235959  1674143999  ...    719  0.166687 -1.446583    -1.0
720  20230120   000000    035959  1674158399  ...    720  0.157312 -1.432139    -1.0
721  20230120   040000    075959  1674172799  ...    721  0.148034 -1.417982    -1.0
722  20230120   080000    115959  1674187199  ...    722  0.127783 -1.428838    -1.0
723  20230120   120000    155959  1674201599  ...    723  0.154954 -1.334303    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '10744.32637011633', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20956.44564139', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


