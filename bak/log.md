# 20230109 16:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12410
self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17193.2, self.close=17184.4, self.high=17194.4, self.low=17180.0, self.vol=830.125, self.amt=14264952.0891 
127.0.0.1 - - [09/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-09 16:10:01,507:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230109   154500    154959  ...         0.0        0.0       0
5950  20230109   155000    155459  ...         0.0        0.0       0
5951  20230109   155500    155959  ...         0.0        0.0       0
5952  20230109   160000    160459  ...         0.0        0.0       0
5953  20230109   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 16:10:01,509:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17193.2, self.close=17184.4, self.high=17194.4, self.low=17180.0, self.vol=830.125, self.amt=14264952.0891, ukdf['pct'].iloc[-1]=-0.000512 , ukdf['amount'].iloc[-1]=14264952.0891, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-39421.2976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17184.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12411
self.closeSec=1673252099, self.tradeDate='20230109', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17184.4, self.close=17184.5, self.high=17187.0, self.low=17184.4, self.vol=219.443, self.amt=3771316.1127 
2023-01-09 16:15:00,624:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230109   155000    155459  ...         0.0        0.0       0
5951  20230109   155500    155959  ...         0.0        0.0       0
5952  20230109   160000    160459  ...         0.0        0.0       0
5953  20230109   160500    160959  ...         0.0        0.0       0
5954  20230109   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 16:15:00,624:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673252099, self.tradeDate='20230109', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17184.4, self.close=17184.5, self.high=17187.0, self.low=17184.4, self.vol=219.443, self.amt=3771316.1127, ukdf['pct'].iloc[-1]=6e-06 , ukdf['amount'].iloc[-1]=3771316.1127, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-39432.62827985184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17184.58829234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=79, self.factor=0.35051367023371754, self.count=12976 

self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17193.2, self.close=17184.4, self.high=17194.4, self.low=17180.0 
2023-01-09 16:10:01,444:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17193.2, self.close=17184.4, self.high=17194.4, self.low=17180.0   
2023-01-09 16:10:01,457:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230109   154500    154959  1673250599  ...  17186.8  0.000209   1629    3
1630  20230109   155000    155459  1673250899  ...  17188.2 -0.000029   1630    4
1631  20230109   155500    155959  1673251199  ...  17189.7 -0.000012   1631    5
1632  20230109   160000    160459  1673251499  ...  17187.0  0.000198   1632    0
1633  20230109   160500    160959  1673251799  ...  17180.0 -0.000512   1633    1

[5 rows x 11 columns]
2023-01-09 16:10:01,457:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=79, self.factor=0.35051367023371754, self.count=12977 

self.closeSec=1673252099, self.tradeDate='20230109', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17184.4, self.close=17184.5, self.high=17187.0, self.low=17184.4 
2023-01-09 16:15:00,546:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673252099, self.tradeDate='20230109', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17184.4, self.close=17184.5, self.high=17187.0, self.low=17184.4   
127.0.0.1 - - [09/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-09 16:15:00,600:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230109   155000    155459  1673250899  ...  17188.2 -0.000029   1630    4
1631  20230109   155500    155959  1673251199  ...  17189.7 -0.000012   1631    5
1632  20230109   160000    160459  1673251499  ...  17187.0  0.000198   1632    0
1633  20230109   160500    160959  1673251799  ...  17180.0 -0.000512   1633    1
1634  20230109   161000    161459  1673252099  ...  17184.4  0.000006   1634    2

[5 rows x 11 columns]
2023-01-09 16:15:00,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-09 16:00:19,889:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230109    132959  17216.1  ...  52.500000  0.679365  0.322760
5787  20230109    135959  17226.6  ...  52.083333  0.649948  0.311702
5788  20230109    142959  17195.0  ...  52.083333  0.653053  0.300119
5789  20230109    145959  17201.4  ...  51.666667  0.634655  0.293354
5790  20230109    152959  17180.9  ...  52.083333  0.641739  0.284256

[5 rows x 33 columns]
0.5608856088560885
acc is : 0.5608856088560885
2023-01-09 16:00:20,002:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     0  0.515633  0.484367       0  ...  NaN   NaN -0.0016  1.037362
538     0  0.503216  0.496784       1  ...  NaN   NaN -0.0016  1.037748
539     0  0.510244  0.489756       0  ...  NaN   NaN -0.0016  1.036511
540     1  0.498141  0.501859       1  ...  NaN   NaN -0.0016  1.037362
541     0  0.508025  0.491975       0  ...  NaN   NaN -0.0016  1.037048

[5 rows x 10 columns]
2023-01-09 16:00:20,033:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.515670  0.484330       0  ...  NaN   NaN -0.0016  1.041402
46     0  0.503403  0.496597       1  ...  NaN   NaN -0.0016  1.039862
47     0  0.510605  0.489395       0  ...  NaN   NaN -0.0016  1.038811
48     1  0.498303  0.501697       1  ...  NaN   NaN -0.0016  1.039054
49     0  0.508025  0.491975       0  ...  NaN   NaN -0.0016  1.037048

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '20740.9056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17189.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230109   154000    154959  1673250599    17184  17190.5  0.000372
2023-01-09 15:50:00,565:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6487 

self.closeSec=1673251199, self.tradeDate='20230109', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17190.6', self.close='17189.7'
2023-01-09 16:00:00,980:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673251199, self.tradeDate='20230109', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17190.6', self.close='17189.7'
2023-01-09 16:00:01,031:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230109   151000    151959  1673248799  17178.8  17184.1  0.000309
524  20230109   152000    152959  1673249399  17184.1    17195  0.000634
525  20230109   153000    153959  1673249999    17195  17184.1 -0.000634
526  20230109   154000    154959  1673250599    17184  17190.5  0.000372
527  20230109   155000    155959  1673251199  17190.6  17189.7 -0.000047
2023-01-09 16:00:01,031:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6488 
127.0.0.1 - - [09/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17189.8', self.close='17184.4'
2023-01-09 16:10:01,551:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17189.8', self.close='17184.4'
2023-01-09 16:10:01,584:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230109   152000    152959  1673249399  17184.1    17195  0.000634
525  20230109   153000    153959  1673249999    17195  17184.1 -0.000634
526  20230109   154000    154959  1673250599    17184  17190.5  0.000372
527  20230109   155000    155959  1673251199  17190.6  17189.7 -0.000047
528  20230109   160000    160959  1673251799  17189.8  17184.4 -0.000308
2023-01-09 16:10:01,584:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230109   154000    154959  1673250599    17184  17190.5
2023-01-09 15:50:00,591:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6488 

self.closeSec=1673251199, self.tradeDate='20230109', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17190.6', self.close='17189.7'
127.0.0.1 - - [09/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-09 16:00:00,973:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673251199, self.tradeDate='20230109', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17190.6', self.close='17189.7'
2023-01-09 16:00:01,002:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230109   151000    151959  1673248799  17178.8  17184.1
17516  20230109   152000    152959  1673249399  17184.1    17195
17517  20230109   153000    153959  1673249999    17195  17184.1
17518  20230109   154000    154959  1673250599    17184  17190.5
17519  20230109   155000    155959  1673251199  17190.6  17189.7
2023-01-09 16:00:01,003:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6489 

self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17189.8', self.close='17184.4'
2023-01-09 16:10:01,524:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17189.8', self.close='17184.4'
2023-01-09 16:10:01,558:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230109   152000    152959  1673249399  17184.1    17195
17517  20230109   153000    153959  1673249999    17195  17184.1
17518  20230109   154000    154959  1673250599    17184  17190.5
17519  20230109   155000    155959  1673251199  17190.6  17189.7
17520  20230109   160000    160959  1673251799  17189.8  17184.4
2023-01-09 16:10:01,558:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230109   154000    154959  1673250599    17184  17190.5
2023-01-09 15:50:00,567:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6488 

self.closeSec=1673251199, self.tradeDate='20230109', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17190.6', self.close='17189.7'
2023-01-09 16:00:00,992:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673251199, self.tradeDate='20230109', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17190.6', self.close='17189.7'
2023-01-09 16:00:01,030:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230109   151000    151959  1673248799  17178.8  17184.1
12188  20230109   152000    152959  1673249399  17184.1    17195
12189  20230109   153000    153959  1673249999    17195  17184.1
12190  20230109   154000    154959  1673250599    17184  17190.5
12191  20230109   155000    155959  1673251199  17190.6  17189.7
2023-01-09 16:00:01,031:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6489 

self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17189.8', self.close='17184.4'
2023-01-09 16:10:01,547:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17189.8', self.close='17184.4'
127.0.0.1 - - [09/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-09 16:10:01,563:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230109   152000    152959  1673249399  17184.1    17195
12189  20230109   153000    153959  1673249999    17195  17184.1
12190  20230109   154000    154959  1673250599    17184  17190.5
12191  20230109   155000    155959  1673251199  17190.6  17189.7
12192  20230109   160000    160959  1673251799  17189.8  17184.4
2023-01-09 16:10:01,563:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [09/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8408
self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17193.2, self.close=17184.4, self.high=17194.4, self.low=17180.0, self.vol=830.125, self.amt=14264952.0891 
2023-01-09 16:10:01,506:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230109   154500    154959  ...         0.0        0.0       0
5950  20230109   155000    155459  ...         0.0        0.0       0
5951  20230109   155500    155959  ...         0.0        0.0       0
5952  20230109   160000    160459  ...         0.0        0.0       0
5953  20230109   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 16:10:01,507:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673251799, self.tradeDate='20230109', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17193.2, self.close=17184.4, self.high=17194.4, self.low=17180.0, self.vol=830.125, self.amt=14264952.0891, ukdf['pct'].iloc[-1]=-0.000512 , ukdf['amount'].iloc[-1]=14264952.0891, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8409
self.closeSec=1673252099, self.tradeDate='20230109', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17184.4, self.close=17184.5, self.high=17187.0, self.low=17184.4, self.vol=219.443, self.amt=3771316.1127 
2023-01-09 16:15:00,621:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230109   155000    155459  ...         0.0        0.0       0
5951  20230109   155500    155959  ...         0.0        0.0       0
5952  20230109   160000    160459  ...         0.0        0.0       0
5953  20230109   160500    160959  ...         0.0        0.0       0
5954  20230109   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 16:15:00,623:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673252099, self.tradeDate='20230109', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17184.4, self.close=17184.5, self.high=17187.0, self.low=17184.4, self.vol=219.443, self.amt=3771316.1127, ukdf['pct'].iloc[-1]=6e-06 , ukdf['amount'].iloc[-1]=3771316.1127, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-01-09 12:00:08,458:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41498F1673236803124I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673236803221085, 'quantity': '52.715', 'price': '17188.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673236802798, 'updatetime': 1673236803221, 'tradetype': 'usdt', 'selfid': 41498, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673236803221, 'clientorderid': '41498F1673236803124I0L65', 'price': '17188.2', 'quantity': '52.715', 'commission': '906.075963', 'commissionasset': 'USDT', 'tradetime': 1673236803221, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673236803221}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jan/2023 12:00:08] "POST / HTTP/1.1" 200 -
2023-01-09 12:00:08,583:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41499F1673236808432I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673236808551624, 'quantity': '51.136', 'price': '17188.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673236808233, 'updatetime': 1673236808551, 'tradetype': 'usdt', 'selfid': 41499, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673236808551, 'clientorderid': '41499F1673236808432I0L65', 'price': '17188.2', 'quantity': '51.136', 'commission': '878.9357952', 'commissionasset': 'USDT', 'tradetime': 1673236808551, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673236808551}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jan/2023 12:00:08] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Jan/2023 12:00:08] "POST / HTTP/1.1" 200 -
2023-01-09 12:00:08,797:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41499F1673236808432I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673236808551624, 'quantity': '51.136', 'price': '17188.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673236808233, 'updatetime': 1673236808551, 'tradetype': 'usdt', 'selfid': 41499, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673236808551, 'clientorderid': '41499F1673236808432I0L65', 'price': '17188.2', 'quantity': '51.136', 'commission': '878.9357952', 'commissionasset': 'USDT', 'tradetime': 1673236808551, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673236808551}], 'gatetype': 'simulator', 'handletime': 0}
--handleKline--: 127.0.0.1 - - [09/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=270
self.closeSec=1673251199, self.tradeDate='20230109', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17188.1, self.close=17189.7, self.high=17248.0, self.low=17171.7, self.vol=35863.212, self.amt=617096152.5793 
2023-01-09 16:00:00,863:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673251199, self.tradeDate='20230109', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17188.1, self.close=17189.7, self.high=17248.0, self.low=17171.7, self.vol=35863.212, self.amt=617096152.5793 
2023-01-09 16:00:00,890:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230108   200000    235959  ...  27048.995  4.585836e+08  0.004244
720  20230109   000000    035959  ...  31183.879  5.282959e+08 -0.004114
721  20230109   040000    075959  ...  60866.075  1.036432e+09  0.012015
722  20230109   080000    115959  ...  85195.644  1.463026e+09  0.003767
723  20230109   120000    155959  ...  35863.212  6.170962e+08  0.000087

[5 rows x 11 columns]
2023-01-09 16:00:02,460:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230108   200000    235959  1673193599  ...    719  0.221401 -0.395178     NaN
720  20230109   000000    035959  1673207999  ...    720  0.236135 -0.354664     NaN
721  20230109   040000    075959  1673222399  ...    721  0.338125 -0.011355     NaN
722  20230109   080000    115959  1673236799  ...    722  0.565325  0.768820     1.0
723  20230109   120000    155959  1673251199  ...    723  0.651387  1.049407     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '76.704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17189.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


