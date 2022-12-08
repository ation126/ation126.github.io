# 20221208 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [08/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3194
self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16820.3, self.close=16823.9, self.high=16826.4, self.low=16818.2, self.vol=624.786, self.amt=10511235.9836 
2022-12-08 16:10:01,459:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221208   154500    154959  ...    0.104301   0.253278       0
5950  20221208   155000    155459  ...    0.104104   0.253082       0
5951  20221208   155500    155959  ...    0.103906   0.252885       0
5952  20221208   160000    160459  ...    0.103705   0.252681       0
5953  20221208   160500    160959  ...    0.103504   0.252473       0

[5 rows x 18 columns]
2022-12-08 16:10:01,460:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16820.3, self.close=16823.9, self.high=16826.4, self.low=16818.2, self.vol=624.786, self.amt=10511235.9836, ukdf['pct'].iloc[-1]=0.000214 , ukdf['amount'].iloc[-1]=10511235.9836, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.10350368169824, signal=0, value_std=0.2524734410947538 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17665.29376376432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16822.86045207', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3195
self.closeSec=1670487299, self.tradeDate='20221208', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16822.7, self.close=16817.9, self.high=16824.0, self.low=16817.1, self.vol=289.359, self.amt=4866977.0425 
127.0.0.1 - - [08/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-08 16:15:00,555:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221208   155000    155459  ...    0.104104   0.253082       0
5951  20221208   155500    155959  ...    0.103906   0.252885       0
5952  20221208   160000    160459  ...    0.103705   0.252681       0
5953  20221208   160500    160959  ...    0.103504   0.252473       0
5954  20221208   161000    161459  ...    0.103309   0.252282       0

[5 rows x 18 columns]
2022-12-08 16:15:00,555:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670487299, self.tradeDate='20221208', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16822.7, self.close=16817.9, self.high=16824.0, self.low=16817.1, self.vol=289.359, self.amt=4866977.0425, ukdf['pct'].iloc[-1]=-0.000357 , ukdf['amount'].iloc[-1]=4866977.0425, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.10330873097323234, signal=0, value_std=0.25228225435286844 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17442.43211445184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16819.15695484', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16820.3, self.close=16823.9, self.high=16826.4, self.low=16818.2 
127.0.0.1 - - [08/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-08 16:10:01,448:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16820.3, self.close=16823.9, self.high=16826.4, self.low=16818.2   
2022-12-08 16:10:01,477:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221208   154500    154959  1670485799  ...  16810.6  0.000006   1629    3
1630  20221208   155000    155459  1670486099  ...  16815.9  0.000071   1630    4
1631  20221208   155500    155959  1670486399  ...  16814.2 -0.000107   1631    5
1632  20221208   160000    160459  1670486699  ...  16815.2  0.000214   1632    0
1633  20221208   160500    160959  1670486999  ...  16818.2  0.000214   1633    1

[5 rows x 11 columns]
2022-12-08 16:10:01,478:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6836105873636402, self.count=3761 

self.closeSec=1670487299, self.tradeDate='20221208', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16822.7, self.close=16817.9, self.high=16824.0, self.low=16817.1 
2022-12-08 16:15:00,518:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670487299, self.tradeDate='20221208', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16822.7, self.close=16817.9, self.high=16824.0, self.low=16817.1   
2022-12-08 16:15:00,546:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221208   155000    155459  1670486099  ...  16815.9  0.000071   1630    4
1631  20221208   155500    155959  1670486399  ...  16814.2 -0.000107   1631    5
1632  20221208   160000    160459  1670486699  ...  16815.2  0.000214   1632    0
1633  20221208   160500    160959  1670486999  ...  16818.2  0.000214   1633    1
1634  20221208   161000    161459  1670487299  ...  16817.1 -0.000357   1634    2

[5 rows x 11 columns]
2022-12-08 16:15:00,546:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-08 16:00:25,556:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221208    132959  16805.4  ...  50.833333  0.449033  0.553822
5787  20221208    135959  16804.6  ...  51.250000  0.452353  0.555465
5788  20221208    142959  16810.2  ...  51.250000  0.443478  0.566046
5789  20221208    145959  16792.5  ...  51.666667  0.444782  0.574860
5790  20221208    152959  16794.3  ...  52.083333  0.455081  0.574696

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2022-12-08 16:00:25,666:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.483548  0.516452       1  ...  0.948592  -1.0    0.0  1.021493
538     1  0.485437  0.514563       0  ...  0.949602  -1.0    0.0  1.020405
539     1  0.479851  0.520149       1  ...  0.949483  -1.0    0.0  1.020533
540     1  0.486602  0.513398       1  ...  0.948544  -1.0    0.0  1.021542
541     1  0.491398  0.508602       1  ...  0.948223  -1.0    0.0  1.021888

[5 rows x 10 columns]
2022-12-08 16:00:25,684:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484632  0.515368       1  ...  1.012739  -1.0    0.0  1.023832
46     1  0.486127  0.513873       0  ...  0.949602  -1.0    0.0  1.021411
47     1  0.480114  0.519886       1  ...  0.949483  -1.0    0.0  1.020998
48     1  0.486257  0.513743       1  ...  0.948544  -1.0    0.0  1.020271
49     1  0.491398  0.508602       1  ...  0.948223  -1.0    0.0  1.021888

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '5757.1844975008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16816.27645176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221208   154000    154959  1670485799  16831.7  16817.4 -0.000850
2022-12-08 15:50:00,560:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1879 

self.closeSec=1670486399, self.tradeDate='20221208', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16817.3', self.close='16816.7'
127.0.0.1 - - [08/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-08 16:00:01,122:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670486399, self.tradeDate='20221208', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16817.3', self.close='16816.7'
2022-12-08 16:00:01,145:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221208   151000    151959  1670483999  16808.8  16814.7  0.000345
524  20221208   152000    152959  1670484599  16814.7    16811 -0.000220
525  20221208   153000    153959  1670485199  16810.9  16831.7  0.001231
526  20221208   154000    154959  1670485799  16831.7  16817.4 -0.000850
527  20221208   155000    155959  1670486399  16817.3  16816.7 -0.000042
2022-12-08 16:00:01,145:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1880 

self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16816.8', self.close='16822.8'
2022-12-08 16:10:01,535:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16816.8', self.close='16822.8'
2022-12-08 16:10:01,561:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221208   152000    152959  1670484599  16814.7    16811 -0.000220
525  20221208   153000    153959  1670485199  16810.9  16831.7  0.001231
526  20221208   154000    154959  1670485799  16831.7  16817.4 -0.000850
527  20221208   155000    155959  1670486399  16817.3  16816.7 -0.000042
528  20221208   160000    160959  1670486999  16816.8  16822.8  0.000363
2022-12-08 16:10:01,561:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221208   154000    154959  1670485799  16831.7  16817.4
2022-12-08 15:50:00,583:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1880 

self.closeSec=1670486399, self.tradeDate='20221208', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16817.3', self.close='16816.7'
127.0.0.1 - - [08/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-08 16:00:01,116:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670486399, self.tradeDate='20221208', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16817.3', self.close='16816.7'
2022-12-08 16:00:01,143:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221208   151000    151959  1670483999  16808.8  16814.7
17516  20221208   152000    152959  1670484599  16814.7    16811
17517  20221208   153000    153959  1670485199  16810.9  16831.7
17518  20221208   154000    154959  1670485799  16831.7  16817.4
17519  20221208   155000    155959  1670486399  16817.3  16816.7
2022-12-08 16:00:01,143:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1881 

self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16816.8', self.close='16822.8'
2022-12-08 16:10:01,551:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16816.8', self.close='16822.8'
127.0.0.1 - - [08/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-08 16:10:01,579:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221208   152000    152959  1670484599  16814.7    16811
17517  20221208   153000    153959  1670485199  16810.9  16831.7
17518  20221208   154000    154959  1670485799  16831.7  16817.4
17519  20221208   155000    155959  1670486399  16817.3  16816.7
17520  20221208   160000    160959  1670486999  16816.8  16822.8
2022-12-08 16:10:01,579:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221208   154000    154959  1670485799  16831.7  16817.4
2022-12-08 15:50:00,571:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1880 

self.closeSec=1670486399, self.tradeDate='20221208', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16817.3', self.close='16816.7'
2022-12-08 16:00:01,112:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670486399, self.tradeDate='20221208', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16817.3', self.close='16816.7'
127.0.0.1 - - [08/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-08 16:00:01,137:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221208   151000    151959  1670483999  16808.8  16814.7
12188  20221208   152000    152959  1670484599  16814.7    16811
12189  20221208   153000    153959  1670485199  16810.9  16831.7
12190  20221208   154000    154959  1670485799  16831.7  16817.4
12191  20221208   155000    155959  1670486399  16817.3  16816.7
2022-12-08 16:00:01,137:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1881 

self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16816.8', self.close='16822.8'
2022-12-08 16:10:01,553:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670486999, self.tradeDate='20221208', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16816.8', self.close='16822.8'
127.0.0.1 - - [08/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-08 16:10:01,567:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221208   152000    152959  1670484599  16814.7    16811
12189  20221208   153000    153959  1670485199  16810.9  16831.7
12190  20221208   154000    154959  1670485799  16831.7  16817.4
12191  20221208   155000    155959  1670486399  16817.3  16816.7
12192  20221208   160000    160959  1670486999  16816.8  16822.8
2022-12-08 16:10:01,567:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221208   040000    075959  1670457599  ...    721  0.877063  1.638632     1.0
722  20221208   080000    115959  1670471999  ...    722  0.895266  1.664155     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-27898.2098', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16825.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  127.0.0.1 - - [08/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=78
self.closeSec=1670486399, self.tradeDate='20221208', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16825.6, self.close=16816.7, self.high=16837.7, self.low=16776.9, self.vol=28765.766, self.amt=483508051.2516 
2022-12-08 16:00:00,980:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670486399, self.tradeDate='20221208', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16825.6, self.close=16816.7, self.high=16837.7, self.low=16776.9, self.vol=28765.766, self.amt=483508051.2516 
2022-12-08 16:00:01,015:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221207   200000    235959  ...  70616.715  1.188355e+09  0.002502
720  20221208   000000    035959  ...  34665.520  5.824289e+08 -0.001283
721  20221208   040000    075959  ...  24456.653  4.114483e+08  0.001220
722  20221208   080000    115959  ...  38479.151  6.475756e+08 -0.000143
723  20221208   120000    155959  ...  28765.766  4.835081e+08 -0.000529

[5 rows x 11 columns]
2022-12-08 16:00:02,771:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221207   200000    235959  1670428799  ...    719  0.741914  1.167551     1.0
720  20221208   000000    035959  1670443199  ...    720  0.808755  1.407951     1.0
721  20221208   040000    075959  1670457599  ...    721  0.877063  1.638632     1.0
722  20221208   080000    115959  1670471999  ...    722  0.895266  1.664155     1.0
723  20221208   120000    155959  1670486399  ...    723  0.947182  1.810544     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-28403.40534583666', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16816.98215097', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


