# 20230105 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [05/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11258
self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16818.0, self.close=16815.3, self.high=16822.0, self.low=16815.2, self.vol=322.777, self.amt=5428937.0013 
2023-01-05 16:10:01,606:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230105   154500    154959  ...         0.0        0.0       0
5950  20230105   155000    155459  ...         0.0        0.0       0
5951  20230105   155500    155959  ...         0.0        0.0       0
5952  20230105   160000    160459  ...         0.0        0.0       0
5953  20230105   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 16:10:01,610:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16818.0, self.close=16815.3, self.high=16822.0, self.low=16815.2, self.vol=322.777, self.amt=5428937.0013, ukdf['pct'].iloc[-1]=-0.000161 , ukdf['amount'].iloc[-1]=5428937.0013, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17218.42798346144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16815.43447194', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11259
self.closeSec=1672906499, self.tradeDate='20230105', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16815.3, self.close=16815.2, self.high=16819.2, self.low=16815.1, self.vol=245.016, self.amt=4120308.882 
2023-01-05 16:15:00,633:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230105   155000    155459  ...         0.0        0.0       0
5951  20230105   155500    155959  ...         0.0        0.0       0
5952  20230105   160000    160459  ...         0.0        0.0       0
5953  20230105   160500    160959  ...         0.0        0.0       0
5954  20230105   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 16:15:00,634:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672906499, self.tradeDate='20230105', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16815.3, self.close=16815.2, self.high=16819.2, self.low=16815.1, self.vol=245.016, self.amt=4120308.882, ukdf['pct'].iloc[-1]=-6e-06 , ukdf['amount'].iloc[-1]=4120308.882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17307.36932581312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16816.91249212', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=134, self.factor=0.48883415335811736, self.count=11824 

self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16818.0, self.close=16815.3, self.high=16822.0, self.low=16815.2 
2023-01-05 16:10:01,417:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16818.0, self.close=16815.3, self.high=16822.0, self.low=16815.2   
2023-01-05 16:10:01,521:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230105   154500    154959  1672904999  ...  16806.0 -0.000006   1629    3
1630  20230105   155000    155459  1672905299  ...  16806.0  0.000595   1630    4
1631  20230105   155500    155959  1672905599  ...  16815.9  0.000000   1631    5
1632  20230105   160000    160459  1672905899  ...  16816.0  0.000119   1632    0
1633  20230105   160500    160959  1672906199  ...  16815.2 -0.000161   1633    1

[5 rows x 11 columns]
2023-01-05 16:10:01,521:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=134, self.factor=0.48883415335811736, self.count=11825 

self.closeSec=1672906499, self.tradeDate='20230105', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16815.3, self.close=16815.2, self.high=16819.2, self.low=16815.1 
2023-01-05 16:15:00,553:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672906499, self.tradeDate='20230105', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16815.3, self.close=16815.2, self.high=16819.2, self.low=16815.1   
2023-01-05 16:15:00,611:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230105   155000    155459  1672905299  ...  16806.0  0.000595   1630    4
1631  20230105   155500    155959  1672905599  ...  16815.9  0.000000   1631    5
1632  20230105   160000    160459  1672905899  ...  16816.0  0.000119   1632    0
1633  20230105   160500    160959  1672906199  ...  16815.2 -0.000161   1633    1
1634  20230105   161000    161459  1672906499  ...  16815.1 -0.000006   1634    2

[5 rows x 11 columns]
2023-01-05 16:15:00,611:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-05 16:00:17,635:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230105    132959  16829.0  ...  49.166667  0.537437  0.566702
5787  20230105    135959  16834.1  ...  49.583333  0.538750  0.572863
5788  20230105    142959  16836.2  ...  49.166667  0.523588  0.584828
5789  20230105    145959  16815.1  ...  49.166667  0.520315  0.597356
5790  20230105    152959  16810.4  ...  48.750000  0.503691  0.616091

[5 rows x 33 columns]
0.511070110701107
acc is : 0.511070110701107
2023-01-05 16:00:17,717:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     1  0.498705  0.501295       1  ...  NaN   NaN -0.0016  1.000059
538     1  0.498951  0.501049       0  ...  NaN   NaN -0.0016  0.998812
539     1  0.491178  0.508822       0  ...  NaN   NaN -0.0016  0.998539
540     1  0.493144  0.506856       0  ...  NaN   NaN -0.0016  0.997125
541     1  0.485088  0.514912       1  ...  NaN   NaN -0.0016  0.998865

[5 rows x 10 columns]
2023-01-05 16:00:17,727:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.499689  0.500311       1  ...  NaN   NaN -0.0016  1.000993
46     1  0.499659  0.500341       0  ...  NaN   NaN -0.0016  0.999697
47     1  0.491617  0.508383       0  ...  NaN   NaN -0.0016  0.998907
48     1  0.493344  0.506656       0  ...  NaN   NaN -0.0016  0.997398
49     1  0.485088  0.514912       1  ...  NaN   NaN -0.0016  0.998865

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '4891.37119979328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16816.51531226', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230105   154000    154959  1672904999  16809.4    16806 -0.000196
2023-01-05 15:50:00,558:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5911 

self.closeSec=1672905599, self.tradeDate='20230105', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16806.1', self.close='16816'
127.0.0.1 - - [05/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-05 16:00:00,848:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672905599, self.tradeDate='20230105', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16806.1', self.close='16816'
2023-01-05 16:00:00,860:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230105   151000    151959  1672903199  16807.9  16805.4 -0.000149
524  20230105   152000    152959  1672903799  16805.4  16786.7 -0.001113
525  20230105   153000    153959  1672904399  16788.2  16809.3  0.001346
526  20230105   154000    154959  1672904999  16809.4    16806 -0.000196
527  20230105   155000    155959  1672905599  16806.1    16816  0.000595
2023-01-05 16:00:00,860:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [05/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5912 

self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16816.1', self.close='16815.3'
2023-01-05 16:10:01,544:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16816.1', self.close='16815.3'
2023-01-05 16:10:01,603:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230105   152000    152959  1672903799  16805.4  16786.7 -0.001113
525  20230105   153000    153959  1672904399  16788.2  16809.3  0.001346
526  20230105   154000    154959  1672904999  16809.4    16806 -0.000196
527  20230105   155000    155959  1672905599  16806.1    16816  0.000595
528  20230105   160000    160959  1672906199  16816.1  16815.3 -0.000042
2023-01-05 16:10:01,603:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230105   154000    154959  1672904999  16809.4    16806
2023-01-05 15:50:00,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5912 

self.closeSec=1672905599, self.tradeDate='20230105', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16806.1', self.close='16816'
2023-01-05 16:00:00,868:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672905599, self.tradeDate='20230105', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16806.1', self.close='16816'
2023-01-05 16:00:00,941:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230105   151000    151959  1672903199  16807.9  16805.4
17516  20230105   152000    152959  1672903799  16805.4  16786.7
17517  20230105   153000    153959  1672904399  16788.2  16809.3
17518  20230105   154000    154959  1672904999  16809.4    16806
17519  20230105   155000    155959  1672905599  16806.1    16816
2023-01-05 16:00:00,941:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5913 

self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16816.1', self.close='16815.3'
127.0.0.1 - - [05/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 16:10:01,573:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16816.1', self.close='16815.3'
2023-01-05 16:10:01,608:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230105   152000    152959  1672903799  16805.4  16786.7
17517  20230105   153000    153959  1672904399  16788.2  16809.3
17518  20230105   154000    154959  1672904999  16809.4    16806
17519  20230105   155000    155959  1672905599  16806.1    16816
17520  20230105   160000    160959  1672906199  16816.1  16815.3
2023-01-05 16:10:01,608:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230105   154000    154959  1672904999  16809.4    16806
2023-01-05 15:50:00,563:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [05/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5912 

self.closeSec=1672905599, self.tradeDate='20230105', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16806.1', self.close='16816'
2023-01-05 16:00:00,860:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672905599, self.tradeDate='20230105', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16806.1', self.close='16816'
2023-01-05 16:00:00,911:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230105   151000    151959  1672903199  16807.9  16805.4
12188  20230105   152000    152959  1672903799  16805.4  16786.7
12189  20230105   153000    153959  1672904399  16788.2  16809.3
12190  20230105   154000    154959  1672904999  16809.4    16806
12191  20230105   155000    155959  1672905599  16806.1    16816
2023-01-05 16:00:00,911:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5913 

self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16816.1', self.close='16815.3'
2023-01-05 16:10:01,564:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16816.1', self.close='16815.3'
127.0.0.1 - - [05/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 16:10:01,600:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230105   152000    152959  1672903799  16805.4  16786.7
12189  20230105   153000    153959  1672904399  16788.2  16809.3
12190  20230105   154000    154959  1672904999  16809.4    16806
12191  20230105   155000    155959  1672905599  16806.1    16816
12192  20230105   160000    160959  1672906199  16816.1  16815.3
2023-01-05 16:10:01,604:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7256
self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16818.0, self.close=16815.3, self.high=16822.0, self.low=16815.2, self.vol=322.777, self.amt=5428937.0013 
127.0.0.1 - - [05/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 16:10:01,617:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230105   154500    154959  ...         0.0        0.0       0
5950  20230105   155000    155459  ...         0.0        0.0       0
5951  20230105   155500    155959  ...         0.0        0.0       0
5952  20230105   160000    160459  ...         0.0        0.0       0
5953  20230105   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 16:10:01,617:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672906199, self.tradeDate='20230105', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16818.0, self.close=16815.3, self.high=16822.0, self.low=16815.2, self.vol=322.777, self.amt=5428937.0013, ukdf['pct'].iloc[-1]=-0.000161 , ukdf['amount'].iloc[-1]=5428937.0013, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [05/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7257
self.closeSec=1672906499, self.tradeDate='20230105', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16815.3, self.close=16815.2, self.high=16819.2, self.low=16815.1, self.vol=245.016, self.amt=4120308.882 
2023-01-05 16:15:00,626:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230105   155000    155459  ...         0.0        0.0       0
5951  20230105   155500    155959  ...         0.0        0.0       0
5952  20230105   160000    160459  ...         0.0        0.0       0
5953  20230105   160500    160959  ...         0.0        0.0       0
5954  20230105   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 16:15:00,626:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672906499, self.tradeDate='20230105', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16815.3, self.close=16815.2, self.high=16819.2, self.low=16815.1, self.vol=245.016, self.amt=4120308.882, ukdf['pct'].iloc[-1]=-6e-06 , ukdf['amount'].iloc[-1]=4120308.882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230105   040000    075959  1672876799  ...    721  0.969185  2.583625     1.0
722  20230105   080000    115959  1672891199  ...    722  0.959977  2.435706     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '5065.92', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16819.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=246
self.closeSec=1672905599, self.tradeDate='20230105', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16819.0, self.close=16816.0, self.high=16840.7, self.low=16782.4, self.vol=16536.782, self.amt=278049590.2119 
127.0.0.1 - - [05/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-05 16:00:00,758:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672905599, self.tradeDate='20230105', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16819.0, self.close=16816.0, self.high=16840.7, self.low=16782.4, self.vol=16536.782, self.amt=278049590.2119 
2023-01-05 16:00:00,779:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230104   200000    235959  ...   60470.868  1.016581e+09  0.001177
720  20230105   000000    035959  ...  109449.124  1.847913e+09 -0.000635
721  20230105   040000    075959  ...   30171.855  5.073708e+08  0.000374
722  20230105   080000    115959  ...   19519.003  3.285506e+08 -0.001377
723  20230105   120000    155959  ...   16536.782  2.780496e+08 -0.000178

[5 rows x 11 columns]
2023-01-05 16:00:02,265:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230104   200000    235959  1672847999  ...    719  0.864275  2.479193     1.0
720  20230105   000000    035959  1672862399  ...    720  0.990559  2.795060     1.0
721  20230105   040000    075959  1672876799  ...    721  0.969185  2.583625     1.0
722  20230105   080000    115959  1672891199  ...    722  0.959977  2.435706     1.0
723  20230105   120000    155959  1672905599  ...    723  0.872667  2.061405     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '4965.796655805', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16817.2026465', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


