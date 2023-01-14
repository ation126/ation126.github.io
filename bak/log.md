# 20230114 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [14/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13850
self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20913.8, self.close=20930.3, self.high=20940.0, self.low=20910.0, self.vol=709.33, self.amt=14842761.4586 
2023-01-14 16:10:01,473:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230114   154500    154959  ...         0.0        0.0       0
5950  20230114   155000    155459  ...         0.0        0.0       0
5951  20230114   155500    155959  ...         0.0        0.0       0
5952  20230114   160000    160459  ...         0.0        0.0       0
5953  20230114   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 16:10:01,473:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20913.8, self.close=20930.3, self.high=20940.0, self.low=20910.0, self.vol=709.33, self.amt=14842761.4586, ukdf['pct'].iloc[-1]=0.000837 , ukdf['amount'].iloc[-1]=14842761.4586, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-264727.40363138032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20928.51901807', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13851
self.closeSec=1673684099, self.tradeDate='20230114', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20930.3, self.close=20933.5, self.high=20950.0, self.low=20928.0, self.vol=782.868, self.amt=16393125.4011 
127.0.0.1 - - [14/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-14 16:15:00,654:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230114   155000    155459  ...         0.0        0.0       0
5951  20230114   155500    155959  ...         0.0        0.0       0
5952  20230114   160000    160459  ...         0.0        0.0       0
5953  20230114   160500    160959  ...         0.0        0.0       0
5954  20230114   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 16:15:00,654:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673684099, self.tradeDate='20230114', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20930.3, self.close=20933.5, self.high=20950.0, self.low=20928.0, self.vol=782.868, self.amt=16393125.4011, ukdf['pct'].iloc[-1]=0.000153 , ukdf['amount'].iloc[-1]=16393125.4011, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-265021.1216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20933.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=319, self.factor=0.13536859142804403, self.count=14416 

self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20913.8, self.close=20930.3, self.high=20940.0, self.low=20910.0 
2023-01-14 16:10:01,453:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20913.8, self.close=20930.3, self.high=20940.0, self.low=20910.0   
2023-01-14 16:10:01,512:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230114   154500    154959  1673682599  ...  20855.5  0.000709   1629    3
1630  20230114   155000    155459  1673682899  ...  20888.4  0.000158   1630    4
1631  20230114   155500    155959  1673683199  ...  20902.0  0.000679   1631    5
1632  20230114   160000    160459  1673683499  ...  20893.4 -0.000182   1632    0
1633  20230114   160500    160959  1673683799  ...  20910.0  0.000837   1633    1

[5 rows x 11 columns]
2023-01-14 16:10:01,512:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=319, self.factor=0.13536859142804403, self.count=14417 

self.closeSec=1673684099, self.tradeDate='20230114', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20930.3, self.close=20933.5, self.high=20950.0, self.low=20928.0 
2023-01-14 16:15:00,573:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673684099, self.tradeDate='20230114', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20930.3, self.close=20933.5, self.high=20950.0, self.low=20928.0   
127.0.0.1 - - [14/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-14 16:15:00,642:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230114   155000    155459  1673682899  ...  20888.4  0.000158   1630    4
1631  20230114   155500    155959  1673683199  ...  20902.0  0.000679   1631    5
1632  20230114   160000    160459  1673683499  ...  20893.4 -0.000182   1632    0
1633  20230114   160500    160959  1673683799  ...  20910.0  0.000837   1633    1
1634  20230114   161000    161459  1673684099  ...  20928.0  0.000153   1634    2

[5 rows x 11 columns]
2023-01-14 16:15:00,643:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-14 16:00:33,351:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230114    132959  20920.3  ...  56.666667  0.722287  0.188602
5787  20230114    135959  20845.4  ...  57.083333  0.723699  0.192551
5788  20230114    142959  20864.3  ...  57.083333  0.727678  0.194909
5789  20230114    145959  20919.1  ...  57.500000  0.731699  0.195756
5790  20230114    152959  20974.7  ...  57.083333  0.725517  0.197312

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-01-14 16:00:33,523:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.511030  0.488970       1  ...  1.054653   1.0    0.0  1.250175
538     0  0.533242  0.466758       1  ...  1.057412   1.0    0.0  1.253447
539     0  0.533435  0.466565       1  ...  1.060228   1.0    0.0  1.256784
540     0  0.542400  0.457600       0  ...  1.058636   1.0    0.0  1.254897
541     0  0.526733  0.473267       0  ...  1.057291   1.0    0.0  1.253303

[5 rows x 10 columns]
2023-01-14 16:00:33,551:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511327  0.488673       1  ...  1.125244   1.0    0.0  1.249756
46     0  0.533468  0.466532       1  ...  1.057412   1.0    0.0  1.252254
47     0  0.533505  0.466495       1  ...  1.131192   1.0    0.0  1.258526
48     0  0.542653  0.457347       0  ...  1.058636   1.0    0.0  1.255875
49     0  0.526733  0.473267       0  ...  1.057291   1.0    0.0  1.253303

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230114   154000    154959  1673682599  20911.5  20899.1 -0.000593
2023-01-14 15:50:00,572:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7207 

self.closeSec=1673683199, self.tradeDate='20230114', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20899.1', self.close='20916.5'
2023-01-14 16:00:01,004:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673683199, self.tradeDate='20230114', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20899.1', self.close='20916.5'
2023-01-14 16:00:01,067:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230114   151000    151959  1673680799  20952.5  20931.9 -0.000983
524  20230114   152000    152959  1673681399  20934.2  20943.1  0.000535
525  20230114   153000    153959  1673681999    20943  20911.5 -0.001509
526  20230114   154000    154959  1673682599  20911.5  20899.1 -0.000593
527  20230114   155000    155959  1673683199  20899.1  20916.5  0.000833
2023-01-14 16:00:01,067:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7208 

self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20913', self.close='20930.3'
2023-01-14 16:10:01,524:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20913', self.close='20930.3'
2023-01-14 16:10:01,569:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230114   152000    152959  1673681399  20934.2  20943.1  0.000535
525  20230114   153000    153959  1673681999    20943  20911.5 -0.001509
526  20230114   154000    154959  1673682599  20911.5  20899.1 -0.000593
527  20230114   155000    155959  1673683199  20899.1  20916.5  0.000833
528  20230114   160000    160959  1673683799    20913  20930.3  0.000660
2023-01-14 16:10:01,569:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230114   154000    154959  1673682599  20911.5  20899.1
2023-01-14 15:50:00,619:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7208 

self.closeSec=1673683199, self.tradeDate='20230114', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20899.1', self.close='20916.5'
2023-01-14 16:00:00,978:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673683199, self.tradeDate='20230114', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20899.1', self.close='20916.5'
2023-01-14 16:00:01,017:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230114   151000    151959  1673680799  20952.5  20931.9
17516  20230114   152000    152959  1673681399  20934.2  20943.1
17517  20230114   153000    153959  1673681999    20943  20911.5
17518  20230114   154000    154959  1673682599  20911.5  20899.1
17519  20230114   155000    155959  1673683199  20899.1  20916.5
2023-01-14 16:00:01,021:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7209 

self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20913', self.close='20930.3'
2023-01-14 16:10:01,552:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20913', self.close='20930.3'
2023-01-14 16:10:01,585:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230114   152000    152959  1673681399  20934.2  20943.1
17517  20230114   153000    153959  1673681999    20943  20911.5
17518  20230114   154000    154959  1673682599  20911.5  20899.1
17519  20230114   155000    155959  1673683199  20899.1  20916.5
17520  20230114   160000    160959  1673683799    20913  20930.3
2023-01-14 16:10:01,585:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230114   154000    154959  1673682599  20911.5  20899.1
2023-01-14 15:50:00,623:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7208 

self.closeSec=1673683199, self.tradeDate='20230114', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='20899.1', self.close='20916.5'
127.0.0.1 - - [14/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-14 16:00:01,041:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673683199, self.tradeDate='20230114', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='20899.1', self.close='20916.5'
2023-01-14 16:00:01,079:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230114   151000    151959  1673680799  20952.5  20931.9
12188  20230114   152000    152959  1673681399  20934.2  20943.1
12189  20230114   153000    153959  1673681999    20943  20911.5
12190  20230114   154000    154959  1673682599  20911.5  20899.1
12191  20230114   155000    155959  1673683199  20899.1  20916.5
2023-01-14 16:00:01,079:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7209 

self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='20913', self.close='20930.3'
2023-01-14 16:10:01,543:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='20913', self.close='20930.3'
2023-01-14 16:10:01,580:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230114   152000    152959  1673681399  20934.2  20943.1
12189  20230114   153000    153959  1673681999    20943  20911.5
12190  20230114   154000    154959  1673682599  20911.5  20899.1
12191  20230114   155000    155959  1673683199  20899.1  20916.5
12192  20230114   160000    160959  1673683799    20913  20930.3
2023-01-14 16:10:01,580:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [14/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9848
self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=20913.8, self.close=20930.3, self.high=20940.0, self.low=20910.0, self.vol=709.33, self.amt=14842761.4586 
2023-01-14 16:10:01,525:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230114   154500    154959  ...         0.0        0.0       0
5950  20230114   155000    155459  ...         0.0        0.0       0
5951  20230114   155500    155959  ...         0.0        0.0       0
5952  20230114   160000    160459  ...         0.0        0.0       0
5953  20230114   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 16:10:01,525:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673683799, self.tradeDate='20230114', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=20913.8, self.close=20930.3, self.high=20940.0, self.low=20910.0, self.vol=709.33, self.amt=14842761.4586, ukdf['pct'].iloc[-1]=0.000837 , ukdf['amount'].iloc[-1]=14842761.4586, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9849
self.closeSec=1673684099, self.tradeDate='20230114', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=20930.3, self.close=20933.5, self.high=20950.0, self.low=20928.0, self.vol=782.868, self.amt=16393125.4011 
127.0.0.1 - - [14/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-14 16:15:00,665:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230114   155000    155459  ...         0.0        0.0       0
5951  20230114   155500    155959  ...         0.0        0.0       0
5952  20230114   160000    160459  ...         0.0        0.0       0
5953  20230114   160500    160959  ...         0.0        0.0       0
5954  20230114   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 16:15:00,665:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673684099, self.tradeDate='20230114', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=20930.3, self.close=20933.5, self.high=20950.0, self.low=20928.0, self.vol=782.868, self.amt=16393125.4011, ukdf['pct'].iloc[-1]=0.000153 , ukdf['amount'].iloc[-1]=16393125.4011, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230114   040000    075959  1673654399  ...    721  1.235840  1.402725     1.0
722  20230114   080000    115959  1673668799  ...    722  1.534216  2.042994     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '194699.66056599616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20995.68710431', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [14/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=300
self.closeSec=1673683199, self.tradeDate='20230114', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=20996.2, self.close=20916.5, self.high=21060.0, self.low=20801.3, self.vol=75863.507, self.amt=1587466253.6121 
2023-01-14 16:00:00,841:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673683199, self.tradeDate='20230114', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=20996.2, self.close=20916.5, self.high=21060.0, self.low=20801.3, self.vol=75863.507, self.amt=1587466253.6121 
2023-01-14 16:00:00,875:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230113   200000    235959  ...  200752.474  3.826630e+09  0.018021
720  20230114   000000    035959  ...  170547.519  3.282301e+09  0.005215
721  20230114   040000    075959  ...  253648.534  4.995445e+09  0.029520
722  20230114   080000    115959  ...  400665.223  8.322359e+09  0.053985
723  20230114   120000    155959  ...   75863.507  1.587466e+09 -0.003967

[5 rows x 11 columns]
2023-01-14 16:00:03,109:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230113   200000    235959  1673625599  ...    719  1.171959  1.306448     1.0
720  20230114   000000    035959  1673639999  ...    720  1.163214  1.258982     1.0
721  20230114   040000    075959  1673654399  ...    721  1.235840  1.402725     1.0
722  20230114   080000    115959  1673668799  ...    722  1.534216  2.042994     1.0
723  20230114   120000    155959  1673683199  ...    723  1.289315  1.435970     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '190402.73287100736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20911.65769851', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


