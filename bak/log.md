# 20221215 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5114
self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17809.4, self.close=17829.6, self.high=17829.8, self.low=17797.2, self.vol=897.209, self.amt=15981723.7329 
2022-12-15 08:10:01,483:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221215   074500    074959  ...         0.0        0.0       0
5854  20221215   075000    075459  ...         0.0        0.0       0
5855  20221215   075500    075959  ...         0.0        0.0       0
5856  20221215   080000    080459  ...         0.0        0.0       0
5857  20221215   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-15 08:10:01,483:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17809.4, self.close=17829.6, self.high=17829.8, self.low=17797.2, self.vol=897.209, self.amt=15981723.7329, ukdf['pct'].iloc[-1]=0.001123 , ukdf['amount'].iloc[-1]=15981723.7329, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-78252.8704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17829.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5115
self.closeSec=1671063299, self.tradeDate='20221215', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17829.7, self.close=17837.6, self.high=17839.8, self.low=17817.8, self.vol=768.155, self.amt=13696690.3267 
2022-12-15 08:15:00,853:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221215   075000    075459  ...         0.0        0.0       0
5855  20221215   075500    075959  ...         0.0        0.0       0
5856  20221215   080000    080459  ...         0.0        0.0       0
5857  20221215   080500    080959  ...         0.0        0.0       0
5858  20221215   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-15 08:15:00,856:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671063299, self.tradeDate='20221215', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17829.7, self.close=17837.6, self.high=17839.8, self.low=17817.8, self.vol=768.155, self.amt=13696690.3267, ukdf['pct'].iloc[-1]=0.000449 , ukdf['amount'].iloc[-1]=13696690.3267, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-78786.76061617456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17838.57214531', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17809.4, self.close=17829.6, self.high=17829.8, self.low=17797.2 
2022-12-15 08:10:01,452:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17809.4, self.close=17829.6, self.high=17829.8, self.low=17797.2   
127.0.0.1 - - [15/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-15 08:10:01,472:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221215   074500    074959  1671061799  ...  17811.0  0.000185   1533    3
1534  20221215   075000    075459  1671062099  ...  17794.7 -0.000690   1534    4
1535  20221215   075500    075959  1671062399  ...  17791.6  0.000107   1535    5
1536  20221215   080000    080459  1671062699  ...  17798.7  0.000320   1536    0
1537  20221215   080500    080959  1671062999  ...  17797.2  0.001123   1537    1

[5 rows x 11 columns]
2022-12-15 08:10:01,474:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=54, self.factor=0.35936761413492285, self.count=5681 

self.closeSec=1671063299, self.tradeDate='20221215', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17829.7, self.close=17837.6, self.high=17839.8, self.low=17817.8 
2022-12-15 08:15:00,755:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671063299, self.tradeDate='20221215', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17829.7, self.close=17837.6, self.high=17839.8, self.low=17817.8   
2022-12-15 08:15:00,800:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221215   075000    075459  1671062099  ...  17794.7 -0.000690   1534    4
1535  20221215   075500    075959  1671062399  ...  17791.6  0.000107   1535    5
1536  20221215   080000    080459  1671062699  ...  17798.7  0.000320   1536    0
1537  20221215   080500    080959  1671062999  ...  17797.2  0.001123   1537    1
1538  20221215   081000    081459  1671063299  ...  17817.8  0.000449   1538    2

[5 rows x 11 columns]
2022-12-15 08:15:00,800:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-15 08:00:23,879:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221215    052959  17762.0  ...  51.250000  0.545142  0.396695
5771  20221215    055959  17827.9  ...  50.833333  0.544675  0.421882
5772  20221215    062959  17828.1  ...  50.833333  0.550690  0.443320
5773  20221215    065959  17849.3  ...  50.416667  0.544405  0.465102
5774  20221215    072959  17829.7  ...  50.000000  0.536007  0.487818

[5 rows x 33 columns]
0.5933456561922366
acc is : 0.5933456561922366
2022-12-15 08:00:24,023:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.474406  0.525594       0  ...  1.024393  -1.0    0.0  1.051395
537     1  0.489859  0.510141       1  ...  1.023071  -1.0    0.0  1.052751
538     0  0.506607  0.493393       0  ...  1.024201  -1.0    0.0  1.051590
539     1  0.499238  0.500762       0  ...  1.025723  -1.0    0.0  1.050027
540     1  0.494112  0.505888       1  ...  1.025683  -1.0    0.0  1.050068

[5 rows x 10 columns]
2022-12-15 08:00:24,059:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.474256  0.525744       0  ...  1.024393  -1.0    0.0  1.051469
46     1  0.489851  0.510149       1  ...  1.023071  -1.0    0.0  1.053155
47     0  0.506833  0.493167       0  ...  1.024201  -1.0    0.0  1.052092
48     1  0.499238  0.500762       0  ...  1.025723  -1.0    0.0  1.050027
49     1  0.494112  0.505888       1  ...  1.025683  -1.0    0.0  1.050068

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '-1240.4616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17802.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221215   074000    074959  1671061799  17806.6  17814.2  0.000432
2022-12-15 07:50:00,571:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2839 

self.closeSec=1671062399, self.tradeDate='20221215', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17814.2', self.close='17803.9'
2022-12-15 08:00:01,454:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671062399, self.tradeDate='20221215', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17814.2', self.close='17803.9'
2022-12-15 08:00:01,484:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221215   071000    071959  1671059999  17818.1    17803 -0.000853
620  20221215   072000    072959  1671060599  17803.1  17803.2  0.000011
621  20221215   073000    073959  1671061199  17803.1  17806.5  0.000185
622  20221215   074000    074959  1671061799  17806.6  17814.2  0.000432
623  20221215   075000    075959  1671062399  17814.2  17803.9 -0.000578
2022-12-15 08:00:01,485:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2840 

self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17804', self.close='17829.6'
2022-12-15 08:10:01,533:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17804', self.close='17829.6'
2022-12-15 08:10:01,592:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221215   072000    072959  1671060599  17803.1  17803.2  0.000011
621  20221215   073000    073959  1671061199  17803.1  17806.5  0.000185
622  20221215   074000    074959  1671061799  17806.6  17814.2  0.000432
623  20221215   075000    075959  1671062399  17814.2  17803.9 -0.000578
624  20221215   080000    080959  1671062999    17804  17829.6  0.001444
2022-12-15 08:10:01,592:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221215   074000    074959  1671061799  17806.6  17814.2
2022-12-15 07:50:00,584:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2840 

self.closeSec=1671062399, self.tradeDate='20221215', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17814.2', self.close='17803.9'
127.0.0.1 - - [15/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-15 08:00:01,450:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671062399, self.tradeDate='20221215', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17814.2', self.close='17803.9'
2022-12-15 08:00:01,477:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221215   071000    071959  1671059999  17818.1    17803
17468  20221215   072000    072959  1671060599  17803.1  17803.2
17469  20221215   073000    073959  1671061199  17803.1  17806.5
17470  20221215   074000    074959  1671061799  17806.6  17814.2
17471  20221215   075000    075959  1671062399  17814.2  17803.9
2022-12-15 08:00:01,477:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2841 

self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17804', self.close='17829.6'
2022-12-15 08:10:01,576:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17804', self.close='17829.6'
127.0.0.1 - - [15/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-15 08:10:01,585:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221215   072000    072959  1671060599  17803.1  17803.2
17469  20221215   073000    073959  1671061199  17803.1  17806.5
17470  20221215   074000    074959  1671061799  17806.6  17814.2
17471  20221215   075000    075959  1671062399  17814.2  17803.9
17472  20221215   080000    080959  1671062999    17804  17829.6
2022-12-15 08:10:01,586:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221215   074000    074959  1671061799  17806.6  17814.2
2022-12-15 07:50:00,581:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2840 

self.closeSec=1671062399, self.tradeDate='20221215', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17814.2', self.close='17803.9'
2022-12-15 08:00:01,496:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671062399, self.tradeDate='20221215', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17814.2', self.close='17803.9'
2022-12-15 08:00:01,532:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221215   071000    071959  1671059999  17818.1    17803
12140  20221215   072000    072959  1671060599  17803.1  17803.2
12141  20221215   073000    073959  1671061199  17803.1  17806.5
12142  20221215   074000    074959  1671061799  17806.6  17814.2
12143  20221215   075000    075959  1671062399  17814.2  17803.9
2022-12-15 08:00:01,532:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2841 

self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17804', self.close='17829.6'
2022-12-15 08:10:01,562:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17804', self.close='17829.6'
2022-12-15 08:10:01,590:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221215   072000    072959  1671060599  17803.1  17803.2
12141  20221215   073000    073959  1671061199  17803.1  17806.5
12142  20221215   074000    074959  1671061799  17806.6  17814.2
12143  20221215   075000    075959  1671062399  17814.2  17803.9
12144  20221215   080000    080959  1671062999    17804  17829.6
2022-12-15 08:10:01,591:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1112
self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17809.4, self.close=17829.6, self.high=17829.8, self.low=17797.2, self.vol=897.209, self.amt=15981723.7329 
2022-12-15 08:10:01,518:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221215   074500    074959  ...    0.303861   0.313956       0
5854  20221215   075000    075459  ...    0.303516   0.313926       0
5855  20221215   075500    075959  ...    0.303171   0.313896       0
5856  20221215   080000    080459  ...    0.302826   0.313864       0
5857  20221215   080500    080959  ...    0.302478   0.313830       0

[5 rows x 18 columns]
2022-12-15 08:10:01,519:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671062999, self.tradeDate='20221215', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17809.4, self.close=17829.6, self.high=17829.8, self.low=17797.2, self.vol=897.209, self.amt=15981723.7329, ukdf['pct'].iloc[-1]=0.001123 , ukdf['amount'].iloc[-1]=15981723.7329, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.30247840286940975, signal=0, value_std=0.31383022031340996 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1113
self.closeSec=1671063299, self.tradeDate='20221215', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17829.7, self.close=17837.6, self.high=17839.8, self.low=17817.8, self.vol=768.155, self.amt=13696690.3267 
127.0.0.1 - - [15/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-15 08:15:00,856:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221215   075000    075459  ...    0.303516   0.313926       0
5855  20221215   075500    075959  ...    0.303171   0.313896       0
5856  20221215   080000    080459  ...    0.302826   0.313864       0
5857  20221215   080500    080959  ...    0.302478   0.313830       0
5858  20221215   081000    081459  ...    0.302130   0.313794       0

[5 rows x 18 columns]
2022-12-15 08:15:00,857:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671063299, self.tradeDate='20221215', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17829.7, self.close=17837.6, self.high=17839.8, self.low=17817.8, self.vol=768.155, self.amt=13696690.3267, ukdf['pct'].iloc[-1]=0.000449 , ukdf['amount'].iloc[-1]=13696690.3267, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.30212954968271083, signal=0, value_std=0.3137939855778698 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221214   200000    235959  1671033599  ...    719  1.005027  1.339233     1.0
720  20221215   000000    035959  1671047999  ...    720  1.150479  1.769464     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '1720.6392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17788.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=118
self.closeSec=1671062399, self.tradeDate='20221215', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17789.5, self.close=17803.9, self.high=17944.4, self.low=17659.4, self.vol=98675.813, self.amt=1756577558.9743 
127.0.0.1 - - [15/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-15 08:00:01,352:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671062399, self.tradeDate='20221215', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17789.5, self.close=17803.9, self.high=17944.4, self.low=17659.4, self.vol=98675.813, self.amt=1756577558.9743 
2022-12-15 08:00:01,370:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20221214   120000    155959  ...   22263.865  3.958589e+08  0.001389
718  20221214   160000    195959  ...   37760.719  6.730514e+08  0.000938
719  20221214   200000    235959  ...  137064.540  2.462616e+09  0.012898
720  20221215   000000    035959  ...  301024.945  5.433787e+09 -0.014634
721  20221215   040000    075959  ...   98675.813  1.756578e+09  0.000809

[5 rows x 11 columns]
2022-12-15 08:00:03,044:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221214   120000    155959  1671004799  ...    717  0.955077  1.230219     1.0
718  20221214   160000    195959  1671019199  ...    718  0.924404  1.102377     1.0
719  20221214   200000    235959  1671033599  ...    719  1.005027  1.339233     1.0
720  20221215   000000    035959  1671047999  ...    720  1.150479  1.769464     1.0
721  20221215   040000    075959  1671062399  ...    721  1.168074  1.773576     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '2548.8972', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17804', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


