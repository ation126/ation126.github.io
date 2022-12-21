# 20221221 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [21/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6938
self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16807.4, self.close=16796.0, self.high=16807.5, self.low=16795.7, self.vol=527.323, self.amt=8859488.7989 
2022-12-21 16:10:01,485:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221221   154500    154959  ...         0.0        0.0       0
5950  20221221   155000    155459  ...         0.0        0.0       0
5951  20221221   155500    155959  ...         0.0        0.0       0
5952  20221221   160000    160459  ...         0.0        0.0       0
5953  20221221   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 16:10:01,485:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16807.4, self.close=16796.0, self.high=16807.5, self.low=16795.7, self.vol=527.323, self.amt=8859488.7989, ukdf['pct'].iloc[-1]=-0.000678 , ukdf['amount'].iloc[-1]=8859488.7989, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16042.9216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16795.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6939
self.closeSec=1671610499, self.tradeDate='20221221', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16796.0, self.close=16811.7, self.high=16811.7, self.low=16795.1, self.vol=462.17, self.amt=7765227.8071 
2022-12-21 16:15:00,606:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221221   155000    155459  ...         0.0        0.0       0
5951  20221221   155500    155959  ...         0.0        0.0       0
5952  20221221   160000    160459  ...         0.0        0.0       0
5953  20221221   160500    160959  ...         0.0        0.0       0
5954  20221221   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 16:15:00,607:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671610499, self.tradeDate='20221221', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16796.0, self.close=16811.7, self.high=16811.7, self.low=16795.1, self.vol=462.17, self.amt=7765227.8071, ukdf['pct'].iloc[-1]=0.000935 , ukdf['amount'].iloc[-1]=7765227.8071, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16993.7024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16811.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16807.4, self.close=16796.0, self.high=16807.5, self.low=16795.7 
2022-12-21 16:10:01,459:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16807.4, self.close=16796.0, self.high=16807.5, self.low=16795.7   
127.0.0.1 - - [21/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-21 16:10:01,472:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221221   154500    154959  1671608999  ...  16821.6 -0.000024   1629    3
1630  20221221   155000    155459  1671609299  ...  16809.7 -0.000161   1630    4
1631  20221221   155500    155959  1671609599  ...  16806.0 -0.000624   1631    5
1632  20221221   160000    160459  1671609899  ...  16792.7 -0.000107   1632    0
1633  20221221   160500    160959  1671610199  ...  16795.7 -0.000678   1633    1

[5 rows x 11 columns]
2022-12-21 16:10:01,472:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=6, self.factor=0.45169593578626926, self.count=7505 

self.closeSec=1671610499, self.tradeDate='20221221', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16796.0, self.close=16811.7, self.high=16811.7, self.low=16795.1 
2022-12-21 16:15:00,548:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671610499, self.tradeDate='20221221', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16796.0, self.close=16811.7, self.high=16811.7, self.low=16795.1   
2022-12-21 16:15:00,589:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221221   155000    155459  1671609299  ...  16809.7 -0.000161   1630    4
1631  20221221   155500    155959  1671609599  ...  16806.0 -0.000624   1631    5
1632  20221221   160000    160459  1671609899  ...  16792.7 -0.000107   1632    0
1633  20221221   160500    160959  1671610199  ...  16795.7 -0.000678   1633    1
1634  20221221   161000    161459  1671610499  ...  16795.1  0.000935   1634    2

[5 rows x 11 columns]
2022-12-21 16:15:00,596:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-21 16:00:19,837:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221221    132959  16786.0  ...  49.166667  0.513289  0.462918
5787  20221221    135959  16813.3  ...  49.166667  0.518326  0.472739
5788  20221221    142959  16826.5  ...  49.583333  0.519939  0.481139
5789  20221221    145959  16830.8  ...  49.166667  0.519221  0.489289
5790  20221221    152959  16829.0  ...  48.750000  0.519092  0.496951

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2022-12-21 16:00:20,020:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.496021  0.503979       1  ...  1.099653   1.0    0.0  0.981406
538     1  0.496667  0.503333       1  ...  1.099928   1.0    0.0  0.981651
539     1  0.491827  0.508173       0  ...  1.099817   1.0    0.0  0.981552
540     1  0.494124  0.505876       0  ...  1.099797   1.0    0.0  0.981534
541     1  0.497707  0.502293       0  ...  1.098523   1.0    0.0  0.980397

[5 rows x 10 columns]
2022-12-21 16:00:20,057:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496185  0.503815       1  ...  1.099653   1.0    0.0  0.982673
46     1  0.496355  0.503645       1  ...  1.099928   1.0    0.0  0.982419
47     1  0.491894  0.508106       0  ...  1.099817   1.0    0.0  0.982888
48     1  0.493802  0.506198       0  ...  1.099797   1.0    0.0  0.981511
49     1  0.497707  0.502293       0  ...  1.098523   1.0    0.0  0.980397

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '4508.88434698848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16807.52154691', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221221   154000    154959  1671608999  16818.8  16822.4  0.000214
2022-12-21 15:50:00,828:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3751 

self.closeSec=1671609599, self.tradeDate='20221221', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16822.5', self.close='16809.2'
2022-12-21 16:00:01,405:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671609599, self.tradeDate='20221221', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16822.5', self.close='16809.2'
127.0.0.1 - - [21/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-21 16:00:01,421:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221221   151000    151959  1671607199  16829.5  16831.2  0.000095
524  20221221   152000    152959  1671607799  16831.4  16828.7 -0.000149
525  20221221   153000    153959  1671608399  16828.8  16818.8 -0.000588
526  20221221   154000    154959  1671608999  16818.8  16822.4  0.000214
527  20221221   155000    155959  1671609599  16822.5  16809.2 -0.000785
2022-12-21 16:00:01,421:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3752 

self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16809.1', self.close='16796'
2022-12-21 16:10:01,535:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16809.1', self.close='16796'
127.0.0.1 - - [21/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-21 16:10:01,543:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221221   152000    152959  1671607799  16831.4  16828.7 -0.000149
525  20221221   153000    153959  1671608399  16828.8  16818.8 -0.000588
526  20221221   154000    154959  1671608999  16818.8  16822.4  0.000214
527  20221221   155000    155959  1671609599  16822.5  16809.2 -0.000785
528  20221221   160000    160959  1671610199  16809.1    16796 -0.000785
2022-12-21 16:10:01,544:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221221   154000    154959  1671608999  16818.8  16822.4
2022-12-21 15:50:00,804:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3752 

self.closeSec=1671609599, self.tradeDate='20221221', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16822.5', self.close='16809.2'
127.0.0.1 - - [21/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-21 16:00:01,453:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671609599, self.tradeDate='20221221', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16822.5', self.close='16809.2'
2022-12-21 16:00:01,504:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221221   151000    151959  1671607199  16829.5  16831.2
17516  20221221   152000    152959  1671607799  16831.4  16828.7
17517  20221221   153000    153959  1671608399  16828.8  16818.8
17518  20221221   154000    154959  1671608999  16818.8  16822.4
17519  20221221   155000    155959  1671609599  16822.5  16809.2
2022-12-21 16:00:01,505:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3753 

self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16809.1', self.close='16796'
2022-12-21 16:10:01,544:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16809.1', self.close='16796'
127.0.0.1 - - [21/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-21 16:10:01,566:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221221   152000    152959  1671607799  16831.4  16828.7
17517  20221221   153000    153959  1671608399  16828.8  16818.8
17518  20221221   154000    154959  1671608999  16818.8  16822.4
17519  20221221   155000    155959  1671609599  16822.5  16809.2
17520  20221221   160000    160959  1671610199  16809.1    16796
2022-12-21 16:10:01,566:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221221   154000    154959  1671608999  16818.8  16822.4
2022-12-21 15:50:00,793:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3752 

self.closeSec=1671609599, self.tradeDate='20221221', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16822.5', self.close='16809.2'
2022-12-21 16:00:01,451:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671609599, self.tradeDate='20221221', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16822.5', self.close='16809.2'
2022-12-21 16:00:01,501:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221221   151000    151959  1671607199  16829.5  16831.2
12188  20221221   152000    152959  1671607799  16831.4  16828.7
12189  20221221   153000    153959  1671608399  16828.8  16818.8
12190  20221221   154000    154959  1671608999  16818.8  16822.4
12191  20221221   155000    155959  1671609599  16822.5  16809.2
2022-12-21 16:00:01,501:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3753 

self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16809.1', self.close='16796'
2022-12-21 16:10:01,555:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16809.1', self.close='16796'
127.0.0.1 - - [21/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-21 16:10:01,562:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221221   152000    152959  1671607799  16831.4  16828.7
12189  20221221   153000    153959  1671608399  16828.8  16818.8
12190  20221221   154000    154959  1671608999  16818.8  16822.4
12191  20221221   155000    155959  1671609599  16822.5  16809.2
12192  20221221   160000    160959  1671610199  16809.1    16796
2022-12-21 16:10:01,562:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [21/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2936
self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16807.4, self.close=16796.0, self.high=16807.5, self.low=16795.7, self.vol=527.323, self.amt=8859488.7989 
2022-12-21 16:10:01,500:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221221   154500    154959  ...         0.0        0.0       0
5950  20221221   155000    155459  ...         0.0        0.0       0
5951  20221221   155500    155959  ...         0.0        0.0       0
5952  20221221   160000    160459  ...         0.0        0.0       0
5953  20221221   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 16:10:01,500:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671610199, self.tradeDate='20221221', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16807.4, self.close=16796.0, self.high=16807.5, self.low=16795.7, self.vol=527.323, self.amt=8859488.7989, ukdf['pct'].iloc[-1]=-0.000678 , ukdf['amount'].iloc[-1]=8859488.7989, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2937
self.closeSec=1671610499, self.tradeDate='20221221', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16796.0, self.close=16811.7, self.high=16811.7, self.low=16795.1, self.vol=462.17, self.amt=7765227.8071 
127.0.0.1 - - [21/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-21 16:15:00,606:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221221   155000    155459  ...         0.0        0.0       0
5951  20221221   155500    155959  ...         0.0        0.0       0
5952  20221221   160000    160459  ...         0.0        0.0       0
5953  20221221   160500    160959  ...         0.0        0.0       0
5954  20221221   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 16:15:00,608:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671610499, self.tradeDate='20221221', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16796.0, self.close=16811.7, self.high=16811.7, self.low=16795.1, self.vol=462.17, self.amt=7765227.8071, ukdf['pct'].iloc[-1]=0.000935 , ukdf['amount'].iloc[-1]=7765227.8071, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221221   040000    075959  1671580799  ...    721  0.011155 -2.410683    -1.0
722  20221221   080000    115959  1671595199  ...    722  0.033927 -2.244878    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5717.9831184234', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16830.23451095', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=156
self.closeSec=1671609599, self.tradeDate='20221221', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16829.9, self.close=16809.2, self.high=16848.2, self.low=16761.2, self.vol=27534.062, self.amt=462934719.196 
127.0.0.1 - - [21/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-21 16:00:01,084:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671609599, self.tradeDate='20221221', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16829.9, self.close=16809.2, self.high=16848.2, self.low=16761.2, self.vol=27534.062, self.amt=462934719.196 
2022-12-21 16:00:01,162:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221220   200000    235959  ...  131483.196  2.220090e+09  0.006296
720  20221221   000000    035959  ...   81655.657  1.374707e+09 -0.000958
721  20221221   040000    075959  ...   35569.835  6.002760e+08 -0.000444
722  20221221   080000    115959  ...   33529.575  5.648337e+08 -0.003399
723  20221221   120000    155959  ...   27534.062  4.629347e+08 -0.001224

[5 rows x 11 columns]
2022-12-21 16:00:02,851:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221220   200000    235959  1671551999  ...    719  0.026394 -2.594419    -1.0
720  20221221   000000    035959  1671566399  ...    720  0.008696 -2.530130    -1.0
721  20221221   040000    075959  1671580799  ...    721  0.011155 -2.410683    -1.0
722  20221221   080000    115959  1671595199  ...    722  0.033927 -2.244878    -1.0
723  20221221   120000    155959  1671609599  ...    723  0.031652 -2.167219    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-4595.3292', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16809.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


