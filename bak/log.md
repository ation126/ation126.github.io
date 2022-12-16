# 20221216 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5498
self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17490.8, self.close=17482.1, self.high=17492.0, self.low=17475.0, self.vol=1765.907, self.amt=30875456.7338 
127.0.0.1 - - [16/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-16 16:10:01,494:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221216   154500    154959  ...         0.0        0.0       0
5950  20221216   155000    155459  ...         0.0        0.0       0
5951  20221216   155500    155959  ...         0.0        0.0       0
5952  20221216   160000    160459  ...         0.0        0.0       0
5953  20221216   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-16 16:10:01,496:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17490.8, self.close=17482.1, self.high=17492.0, self.low=17475.0, self.vol=1765.907, self.amt=30875456.7338, ukdf['pct'].iloc[-1]=-0.000497 , ukdf['amount'].iloc[-1]=30875456.7338, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-57341.7104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17482.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5499
self.closeSec=1671178499, self.tradeDate='20221216', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17482.2, self.close=17467.1, self.high=17487.0, self.low=17462.7, self.vol=1262.955, self.amt=22071027.0109 
127.0.0.1 - - [16/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-16 16:15:00,827:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221216   155000    155459  ...         0.0        0.0       0
5951  20221216   155500    155959  ...         0.0        0.0       0
5952  20221216   160000    160459  ...         0.0        0.0       0
5953  20221216   160500    160959  ...         0.0        0.0       0
5954  20221216   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-16 16:15:00,828:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671178499, self.tradeDate='20221216', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17482.2, self.close=17467.1, self.high=17487.0, self.low=17462.7, self.vol=1262.955, self.amt=22071027.0109, ukdf['pct'].iloc[-1]=-0.000858 , ukdf['amount'].iloc[-1]=22071027.0109, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-56548.28902100464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17469.01498639', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7473526801957838, self.count=6064 

self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17490.8, self.close=17482.1, self.high=17492.0, self.low=17475.0 
2022-12-16 16:10:01,438:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17490.8, self.close=17482.1, self.high=17492.0, self.low=17475.0   
2022-12-16 16:10:01,482:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221216   154500    154959  1671176999  ...  17475.5 -0.000360   1629    3
1630  20221216   155000    155459  1671177299  ...  17479.6  0.002140   1630    4
1631  20221216   155500    155959  1671177599  ...  17491.8 -0.001193   1631    5
1632  20221216   160000    160459  1671177899  ...  17490.8 -0.000331   1632    0
1633  20221216   160500    160959  1671178199  ...  17475.0 -0.000497   1633    1

[5 rows x 11 columns]
2022-12-16 16:10:01,482:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7473526801957838, self.count=6065 

self.closeSec=1671178499, self.tradeDate='20221216', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17482.2, self.close=17467.1, self.high=17487.0, self.low=17462.7 
2022-12-16 16:15:00,762:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671178499, self.tradeDate='20221216', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17482.2, self.close=17467.1, self.high=17487.0, self.low=17462.7   
2022-12-16 16:15:00,803:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221216   155000    155459  1671177299  ...  17479.6  0.002140   1630    4
1631  20221216   155500    155959  1671177599  ...  17491.8 -0.001193   1631    5
1632  20221216   160000    160459  1671177899  ...  17490.8 -0.000331   1632    0
1633  20221216   160500    160959  1671178199  ...  17475.0 -0.000497   1633    1
1634  20221216   161000    161459  1671178499  ...  17462.7 -0.000858   1634    2

[5 rows x 11 columns]
2022-12-16 16:15:00,804:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-16 16:00:20,062:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221216    132959  17382.1  ...  50.000000  0.436199  0.766953
5787  20221216    135959  17384.1  ...  50.000000  0.444466  0.761339
5788  20221216    142959  17402.9  ...  49.583333  0.437216  0.759223
5789  20221216    145959  17382.0  ...  50.000000  0.451278  0.752438
5790  20221216    152959  17415.0  ...  50.000000  0.473579  0.738109

[5 rows x 33 columns]
0.5719557195571956
acc is : 0.5719557195571956
2022-12-16 16:00:20,166:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.499221  0.500779       1  ...  1.048979  -1.0    0.0  1.011496
538     0  0.505672  0.494328       0  ...  1.050274  -1.0    0.0  1.010247
539     1  0.493182  0.506818       1  ...  1.048274  -1.0    0.0  1.012170
540     0  0.508686  0.491314       1  ...  1.044964  -1.0    0.0  1.015367
541     0  0.521339  0.478661       1  ...  1.043379  -1.0    0.0  1.016907

[5 rows x 10 columns]
2022-12-16 16:00:20,180:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499483  0.500517       1  ...  1.048979  -1.0    0.0  1.018070
46     0  0.505919  0.494081       0  ...  1.050274  -1.0    0.0  1.015351
47     1  0.493566  0.506434       1  ...  1.048274  -1.0    0.0  1.018457
48     0  0.508860  0.491140       1  ...  1.044964  -1.0    0.0  1.020813
49     0  0.521339  0.478661       1  ...  1.043379  -1.0    0.0  1.016907

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '10180.08', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17500', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221216   154000    154959  1671176999  17465.1    17480  0.000847
2022-12-16 15:50:00,553:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Dec/2022 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3031 

self.closeSec=1671177599, self.tradeDate='20221216', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17480.1', self.close='17496.6'
2022-12-16 16:00:02,172:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671177599, self.tradeDate='20221216', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17480.1', self.close='17496.6'
2022-12-16 16:00:02,213:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221216   151000    151959  1671175199  17449.9  17461.2  0.000648
524  20221216   152000    152959  1671175799  17461.1  17470.1  0.000510
525  20221216   153000    153959  1671176399  17470.1  17465.2 -0.000280
526  20221216   154000    154959  1671176999  17465.1    17480  0.000847
527  20221216   155000    155959  1671177599  17480.1  17496.6  0.000950
2022-12-16 16:00:02,213:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3032 

self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17496.6', self.close='17482.1'
2022-12-16 16:10:01,746:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17496.6', self.close='17482.1'
127.0.0.1 - - [16/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-16 16:10:01,769:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221216   152000    152959  1671175799  17461.1  17470.1  0.000510
525  20221216   153000    153959  1671176399  17470.1  17465.2 -0.000280
526  20221216   154000    154959  1671176999  17465.1    17480  0.000847
527  20221216   155000    155959  1671177599  17480.1  17496.6  0.000950
528  20221216   160000    160959  1671178199  17496.6  17482.1 -0.000829
2022-12-16 16:10:01,769:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221216   154000    154959  1671176999  17465.1    17480
2022-12-16 15:50:00,579:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3032 

self.closeSec=1671177599, self.tradeDate='20221216', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17480.1', self.close='17496.6'
127.0.0.1 - - [16/Dec/2022 16:00:02] "POST / HTTP/1.1" 200 -
2022-12-16 16:00:02,156:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671177599, self.tradeDate='20221216', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17480.1', self.close='17496.6'
2022-12-16 16:00:02,181:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221216   151000    151959  1671175199  17449.9  17461.2
17516  20221216   152000    152959  1671175799  17461.1  17470.1
17517  20221216   153000    153959  1671176399  17470.1  17465.2
17518  20221216   154000    154959  1671176999  17465.1    17480
17519  20221216   155000    155959  1671177599  17480.1  17496.6
2022-12-16 16:00:02,187:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3033 

self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17496.6', self.close='17482.1'
127.0.0.1 - - [16/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-16 16:10:01,788:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17496.6', self.close='17482.1'
2022-12-16 16:10:01,812:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221216   152000    152959  1671175799  17461.1  17470.1
17517  20221216   153000    153959  1671176399  17470.1  17465.2
17518  20221216   154000    154959  1671176999  17465.1    17480
17519  20221216   155000    155959  1671177599  17480.1  17496.6
17520  20221216   160000    160959  1671178199  17496.6  17482.1
2022-12-16 16:10:01,812:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221216   154000    154959  1671176999  17465.1    17480
2022-12-16 15:50:00,576:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Dec/2022 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3032 

self.closeSec=1671177599, self.tradeDate='20221216', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17480.1', self.close='17496.6'
2022-12-16 16:00:02,185:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671177599, self.tradeDate='20221216', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17480.1', self.close='17496.6'
2022-12-16 16:00:02,221:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221216   151000    151959  1671175199  17449.9  17461.2
12188  20221216   152000    152959  1671175799  17461.1  17470.1
12189  20221216   153000    153959  1671176399  17470.1  17465.2
12190  20221216   154000    154959  1671176999  17465.1    17480
12191  20221216   155000    155959  1671177599  17480.1  17496.6
2022-12-16 16:00:02,225:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3033 

self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17496.6', self.close='17482.1'
2022-12-16 16:10:01,741:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17496.6', self.close='17482.1'
127.0.0.1 - - [16/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-16 16:10:01,784:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221216   152000    152959  1671175799  17461.1  17470.1
12189  20221216   153000    153959  1671176399  17470.1  17465.2
12190  20221216   154000    154959  1671176999  17465.1    17480
12191  20221216   155000    155959  1671177599  17480.1  17496.6
12192  20221216   160000    160959  1671178199  17496.6  17482.1
2022-12-16 16:10:01,784:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [16/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1496
self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17490.8, self.close=17482.1, self.high=17492.0, self.low=17475.0, self.vol=1765.907, self.amt=30875456.7338 
2022-12-16 16:10:01,538:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221216   154500    154959  ...    0.199851   0.305448       0
5950  20221216   155000    155459  ...    0.199566   0.305380       0
5951  20221216   155500    155959  ...    0.199292   0.305322       0
5952  20221216   160000    160459  ...    0.199018   0.305265       0
5953  20221216   160500    160959  ...    0.198743   0.305207       0

[5 rows x 18 columns]
2022-12-16 16:10:01,539:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671178199, self.tradeDate='20221216', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17490.8, self.close=17482.1, self.high=17492.0, self.low=17475.0, self.vol=1765.907, self.amt=30875456.7338, ukdf['pct'].iloc[-1]=-0.000497 , ukdf['amount'].iloc[-1]=30875456.7338, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.19874306616867907, signal=0, value_std=0.30520654465323493 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1497
self.closeSec=1671178499, self.tradeDate='20221216', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17482.2, self.close=17467.1, self.high=17487.0, self.low=17462.7, self.vol=1262.955, self.amt=22071027.0109 
2022-12-16 16:15:00,815:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221216   155000    155459  ...    0.199566   0.305380       0
5951  20221216   155500    155959  ...    0.199292   0.305322       0
5952  20221216   160000    160459  ...    0.199018   0.305265       0
5953  20221216   160500    160959  ...    0.198743   0.305207       0
5954  20221216   161000    161459  ...    0.198468   0.305148       0

[5 rows x 18 columns]
2022-12-16 16:15:00,815:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671178499, self.tradeDate='20221216', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17482.2, self.close=17467.1, self.high=17487.0, self.low=17462.7, self.vol=1262.955, self.amt=22071027.0109, ukdf['pct'].iloc[-1]=-0.000858 , ukdf['amount'].iloc[-1]=22071027.0109, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.19846802947439712, signal=0, value_std=0.30514757704117185 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221216   040000    075959  1671148799  ...    721  1.007399  1.067021     1.0
722  20221216   080000    115959  1671163199  ...    722  0.984127  0.976720     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-18034.65', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17418.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=126
self.closeSec=1671177599, self.tradeDate='20221216', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17418.8, self.close=17496.5, self.high=17528.0, self.low=17365.4, self.vol=41640.94, self.amt=726342339.1531 
127.0.0.1 - - [16/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-16 16:00:01,788:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671177599, self.tradeDate='20221216', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17418.8, self.close=17496.5, self.high=17528.0, self.low=17365.4, self.vol=41640.94, self.amt=726342339.1531 
2022-12-16 16:00:01,834:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221215   200000    235959  ...  146628.881  2.567878e+09 -0.016266
720  20221216   000000    035959  ...   78980.398  1.373762e+09  0.000637
721  20221216   040000    075959  ...   56639.741  9.830265e+08 -0.004709
722  20221216   080000    115959  ...   35550.559  6.182726e+08  0.003798
723  20221216   120000    155959  ...   41640.940  7.263423e+08  0.004455

[5 rows x 11 columns]
2022-12-16 16:00:03,290:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221215   200000    235959  1671119999  ...    719  1.039420  1.214469     1.0
720  20221216   000000    035959  1671134399  ...    720  1.017189  1.119037     1.0
721  20221216   040000    075959  1671148799  ...    721  1.007399  1.067021     1.0
722  20221216   080000    115959  1671163199  ...    722  0.984127  0.976720     1.0
723  20221216   120000    155959  1671177599  ...    723  0.991257  0.981591     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-13823.8932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17497.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


