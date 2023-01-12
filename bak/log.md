# 20230112 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13274
self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=18113.1, self.close=18090.6, self.high=18118.4, self.low=18081.1, self.vol=1655.5, self.amt=29958040.2736 
127.0.0.1 - - [12/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-12 16:10:01,477:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230112   154500    154959  ...         0.0        0.0       0
5950  20230112   155000    155459  ...         0.0        0.0       0
5951  20230112   155500    155959  ...         0.0        0.0       0
5952  20230112   160000    160459  ...         0.0        0.0       0
5953  20230112   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 16:10:01,478:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=18113.1, self.close=18090.6, self.high=18118.4, self.low=18081.1, self.vol=1655.5, self.amt=29958040.2736, ukdf['pct'].iloc[-1]=-0.001248 , ukdf['amount'].iloc[-1]=29958040.2736, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-93952.7888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18090.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13275
self.closeSec=1673511299, self.tradeDate='20230112', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=18090.6, self.close=18095.0, self.high=18106.4, self.low=18062.0, self.vol=2829.26, self.amt=51169101.2384 
127.0.0.1 - - [12/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-12 16:15:00,818:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230112   155000    155459  ...         0.0        0.0       0
5951  20230112   155500    155959  ...         0.0        0.0       0
5952  20230112   160000    160459  ...         0.0        0.0       0
5953  20230112   160500    160959  ...         0.0        0.0       0
5954  20230112   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 16:15:00,818:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673511299, self.tradeDate='20230112', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=18090.6, self.close=18095.0, self.high=18106.4, self.low=18062.0, self.vol=2829.26, self.amt=51169101.2384, ukdf['pct'].iloc[-1]=0.000243 , ukdf['amount'].iloc[-1]=51169101.2384, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-94211.5456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18094.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=223, self.factor=0.2509922040800771, self.count=13840 

self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=18113.1, self.close=18090.6, self.high=18118.4, self.low=18081.1 
2023-01-12 16:10:01,429:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=18113.1, self.close=18090.6, self.high=18118.4, self.low=18081.1   
2023-01-12 16:10:01,468:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230112   154500    154959  1673509799  ...  18112.2  0.000585   1629    3
1630  20230112   155000    155459  1673510099  ...  18111.2 -0.000265   1630    4
1631  20230112   155500    155959  1673510399  ...  18118.0  0.000618   1631    5
1632  20230112   160000    160459  1673510699  ...  18111.4 -0.000888   1632    0
1633  20230112   160500    160959  1673510999  ...  18081.1 -0.001248   1633    1

[5 rows x 11 columns]
2023-01-12 16:10:01,468:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=223, self.factor=0.2509922040800771, self.count=13841 

self.closeSec=1673511299, self.tradeDate='20230112', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=18090.6, self.close=18095.0, self.high=18106.4, self.low=18062.0 
2023-01-12 16:15:00,746:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673511299, self.tradeDate='20230112', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=18090.6, self.close=18095.0, self.high=18106.4, self.low=18062.0   
2023-01-12 16:15:00,784:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230112   155000    155459  1673510099  ...  18111.2 -0.000265   1630    4
1631  20230112   155500    155959  1673510399  ...  18118.0  0.000618   1631    5
1632  20230112   160000    160459  1673510699  ...  18111.4 -0.000888   1632    0
1633  20230112   160500    160959  1673510999  ...  18081.1 -0.001248   1633    1
1634  20230112   161000    161459  1673511299  ...  18062.0  0.000243   1634    2

[5 rows x 11 columns]
2023-01-12 16:15:00,788:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-12 16:00:18,555:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230112    132959  18206.3  ...  56.250000  0.712885  0.218881
5787  20230112    135959  18159.5  ...  56.250000  0.676231  0.223760
5788  20230112    142959  18080.6  ...  56.666667  0.684814  0.225814
5789  20230112    145959  18121.7  ...  56.666667  0.688999  0.226488
5790  20230112    152959  18142.0  ...  56.666667  0.690970  0.226531

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2023-01-12 16:00:18,640:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.505784  0.494216       0  ...  1.006467   1.0    0.0  1.094004
538     1  0.487339  0.512661       1  ...  1.008749   1.0    0.0  1.096485
539     0  0.516457  0.483543       1  ...  1.009885   1.0    0.0  1.097719
540     0  0.517895  0.482105       1  ...  1.010419   1.0    0.0  1.098300
541     0  0.514723  0.485277       0  ...  1.009178   1.0    0.0  1.096950

[5 rows x 10 columns]
2023-01-12 16:00:18,654:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505836  0.494164       0  ...  1.006467   1.0    0.0  1.094792
46     1  0.487314  0.512686       1  ...  1.008749   1.0    0.0  1.096889
47     0  0.516206  0.483794       1  ...  1.009885   1.0    0.0  1.097015
48     0  0.517621  0.482379       1  ...  1.010419   1.0    0.0  1.097476
49     0  0.514723  0.485277       0  ...  1.009178   1.0    0.0  1.096950

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '60773.43511319328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18130.52170601', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230112   154000    154959  1673509799  18145.7  18122.9 -0.001256
2023-01-12 15:50:00,586:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6919 

self.closeSec=1673510399, self.tradeDate='20230112', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='18123', self.close='18129.3'
2023-01-12 16:00:01,139:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673510399, self.tradeDate='20230112', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='18123', self.close='18129.3'
2023-01-12 16:00:01,202:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230112   151000    151959  1673507999  18142.9  18157.5  0.000805
524  20230112   152000    152959  1673508599  18157.5  18151.6 -0.000325
525  20230112   153000    153959  1673509199  18151.7  18145.7 -0.000325
526  20230112   154000    154959  1673509799  18145.7  18122.9 -0.001256
527  20230112   155000    155959  1673510399    18123  18129.3  0.000353
2023-01-12 16:00:01,202:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6920 

self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='18129.2', self.close='18090.6'
2023-01-12 16:10:01,555:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='18129.2', self.close='18090.6'
2023-01-12 16:10:01,576:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230112   152000    152959  1673508599  18157.5  18151.6 -0.000325
525  20230112   153000    153959  1673509199  18151.7  18145.7 -0.000325
526  20230112   154000    154959  1673509799  18145.7  18122.9 -0.001256
527  20230112   155000    155959  1673510399    18123  18129.3  0.000353
528  20230112   160000    160959  1673510999  18129.2  18090.6 -0.002135
2023-01-12 16:10:01,576:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230112   154000    154959  1673509799  18145.7  18122.9
2023-01-12 15:50:00,593:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6920 

self.closeSec=1673510399, self.tradeDate='20230112', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='18123', self.close='18129.3'
127.0.0.1 - - [12/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-12 16:00:01,173:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673510399, self.tradeDate='20230112', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='18123', self.close='18129.3'
2023-01-12 16:00:01,213:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230112   151000    151959  1673507999  18142.9  18157.5
17516  20230112   152000    152959  1673508599  18157.5  18151.6
17517  20230112   153000    153959  1673509199  18151.7  18145.7
17518  20230112   154000    154959  1673509799  18145.7  18122.9
17519  20230112   155000    155959  1673510399    18123  18129.3
2023-01-12 16:00:01,213:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6921 

self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='18129.2', self.close='18090.6'
2023-01-12 16:10:01,515:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='18129.2', self.close='18090.6'
127.0.0.1 - - [12/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-12 16:10:01,528:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230112   152000    152959  1673508599  18157.5  18151.6
17517  20230112   153000    153959  1673509199  18151.7  18145.7
17518  20230112   154000    154959  1673509799  18145.7  18122.9
17519  20230112   155000    155959  1673510399    18123  18129.3
17520  20230112   160000    160959  1673510999  18129.2  18090.6
2023-01-12 16:10:01,528:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230112   154000    154959  1673509799  18145.7  18122.9
2023-01-12 15:50:00,617:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [12/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6920 

self.closeSec=1673510399, self.tradeDate='20230112', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='18123', self.close='18129.3'
2023-01-12 16:00:01,149:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673510399, self.tradeDate='20230112', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='18123', self.close='18129.3'
2023-01-12 16:00:01,200:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230112   151000    151959  1673507999  18142.9  18157.5
12188  20230112   152000    152959  1673508599  18157.5  18151.6
12189  20230112   153000    153959  1673509199  18151.7  18145.7
12190  20230112   154000    154959  1673509799  18145.7  18122.9
12191  20230112   155000    155959  1673510399    18123  18129.3
2023-01-12 16:00:01,200:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [12/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6921 

self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='18129.2', self.close='18090.6'
2023-01-12 16:10:01,507:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='18129.2', self.close='18090.6'
2023-01-12 16:10:01,523:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230112   152000    152959  1673508599  18157.5  18151.6
12189  20230112   153000    153959  1673509199  18151.7  18145.7
12190  20230112   154000    154959  1673509799  18145.7  18122.9
12191  20230112   155000    155959  1673510399    18123  18129.3
12192  20230112   160000    160959  1673510999  18129.2  18090.6
2023-01-12 16:10:01,523:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [12/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9272
self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=18113.1, self.close=18090.6, self.high=18118.4, self.low=18081.1, self.vol=1655.5, self.amt=29958040.2736 
2023-01-12 16:10:01,475:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230112   154500    154959  ...         0.0        0.0       0
5950  20230112   155000    155459  ...         0.0        0.0       0
5951  20230112   155500    155959  ...         0.0        0.0       0
5952  20230112   160000    160459  ...         0.0        0.0       0
5953  20230112   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 16:10:01,475:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673510999, self.tradeDate='20230112', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=18113.1, self.close=18090.6, self.high=18118.4, self.low=18081.1, self.vol=1655.5, self.amt=29958040.2736, ukdf['pct'].iloc[-1]=-0.001248 , ukdf['amount'].iloc[-1]=29958040.2736, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [12/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9273
self.closeSec=1673511299, self.tradeDate='20230112', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=18090.6, self.close=18095.0, self.high=18106.4, self.low=18062.0, self.vol=2829.26, self.amt=51169101.2384 
2023-01-12 16:15:00,820:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230112   155000    155459  ...         0.0        0.0       0
5951  20230112   155500    155959  ...         0.0        0.0       0
5952  20230112   160000    160459  ...         0.0        0.0       0
5953  20230112   160500    160959  ...         0.0        0.0       0
5954  20230112   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 16:15:00,820:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673511299, self.tradeDate='20230112', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=18090.6, self.close=18095.0, self.high=18106.4, self.low=18062.0, self.vol=2829.26, self.amt=51169101.2384, ukdf['pct'].iloc[-1]=0.000243 , ukdf['amount'].iloc[-1]=51169101.2384, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230112   040000    075959  1673481599  ...    721  1.297732  2.310525     1.0
722  20230112   080000    115959  1673495999  ...    722  1.606024  3.041440     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '52665.58437958272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18218.11208502', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=288
self.closeSec=1673510399, self.tradeDate='20230112', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=18217.1, self.close=18129.3, self.high=18233.0, self.low=18070.0, self.vol=51547.124, self.amt=935565332.7663 
127.0.0.1 - - [12/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-12 16:00:00,993:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673510399, self.tradeDate='20230112', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=18217.1, self.close=18129.3, self.high=18233.0, self.low=18070.0, self.vol=51547.124, self.amt=935565332.7663 
2023-01-12 16:00:01,013:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230111   200000    235959  ...   62512.096  1.086442e+09 -0.005933
720  20230112   000000    035959  ...   86210.349  1.504725e+09  0.012427
721  20230112   040000    075959  ...  144426.875  2.562553e+09  0.022519
722  20230112   080000    115959  ...  167796.454  3.045955e+09  0.015701
723  20230112   120000    155959  ...   51547.124  9.355653e+08 -0.004825

[5 rows x 11 columns]
2023-01-12 16:00:02,435:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230111   200000    235959  1673452799  ...    719  1.065789  1.736196     1.0
720  20230112   000000    035959  1673467199  ...    720  1.084789  1.748467     1.0
721  20230112   040000    075959  1673481599  ...    721  1.297732  2.310525     1.0
722  20230112   080000    115959  1673495999  ...    722  1.606024  3.041440     1.0
723  20230112   120000    155959  1673510399  ...    723  1.335643  2.179508     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '48295.3037739456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18132.6482121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


