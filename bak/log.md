# 20221213 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [13/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4538
self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17196.9, self.close=17174.4, self.high=17198.8, self.low=17170.0, self.vol=2384.588, self.amt=40973160.8508 
2022-12-13 08:10:01,491:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221213   074500    074959  ...         0.0        0.0       0
5854  20221213   075000    075459  ...         0.0        0.0       0
5855  20221213   075500    075959  ...         0.0        0.0       0
5856  20221213   080000    080459  ...         0.0        0.0       0
5857  20221213   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-13 08:10:01,492:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17196.9, self.close=17174.4, self.high=17198.8, self.low=17170.0, self.vol=2384.588, self.amt=40973160.8508, ukdf['pct'].iloc[-1]=-0.001308 , ukdf['amount'].iloc[-1]=40973160.8508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-38819.5376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17174.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4539
self.closeSec=1670890499, self.tradeDate='20221213', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17174.4, self.close=17171.7, self.high=17180.2, self.low=17171.7, self.vol=890.078, self.amt=15288109.3078 
127.0.0.1 - - [13/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-13 08:15:00,633:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221213   075000    075459  ...         0.0        0.0       0
5855  20221213   075500    075959  ...         0.0        0.0       0
5856  20221213   080000    080459  ...         0.0        0.0       0
5857  20221213   080500    080959  ...         0.0        0.0       0
5858  20221213   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-13 08:15:00,633:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670890499, self.tradeDate='20221213', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17174.4, self.close=17171.7, self.high=17180.2, self.low=17171.7, self.vol=890.078, self.amt=15288109.3078, ukdf['pct'].iloc[-1]=-0.000157 , ukdf['amount'].iloc[-1]=15288109.3078, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-38663.08', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17171.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5159256320529322, self.count=5104 

self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17196.9, self.close=17174.4, self.high=17198.8, self.low=17170.0 
2022-12-13 08:10:01,424:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17196.9, self.close=17174.4, self.high=17198.8, self.low=17170.0   
2022-12-13 08:10:01,454:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221213   074500    074959  1670888999  ...  17190.0 -0.000378   1533    3
1534  20221213   075000    075459  1670889299  ...  17197.9  0.000331   1534    4
1535  20221213   075500    075959  1670889599  ...  17191.0 -0.000128   1535    5
1536  20221213   080000    080459  1670889899  ...  17196.9 -0.000174   1536    0
1537  20221213   080500    080959  1670890199  ...  17170.0 -0.001308   1537    1

[5 rows x 11 columns]
2022-12-13 08:10:01,454:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5159256320529322, self.count=5105 

self.closeSec=1670890499, self.tradeDate='20221213', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17174.4, self.close=17171.7, self.high=17180.2, self.low=17171.7 
2022-12-13 08:15:00,537:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670890499, self.tradeDate='20221213', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17174.4, self.close=17171.7, self.high=17180.2, self.low=17171.7   
2022-12-13 08:15:00,609:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221213   075000    075459  1670889299  ...  17197.9  0.000331   1534    4
1535  20221213   075500    075959  1670889599  ...  17191.0 -0.000128   1535    5
1536  20221213   080000    080459  1670889899  ...  17196.9 -0.000174   1536    0
1537  20221213   080500    080959  1670890199  ...  17170.0 -0.001308   1537    1
1538  20221213   081000    081459  1670890499  ...  17171.7 -0.000157   1538    2

[5 rows x 11 columns]
2022-12-13 08:15:00,609:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-13 08:00:17,373:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221213    052959  17114.4  ...  55.000000  0.585991  0.500961
5771  20221213    055959  17173.7  ...  54.583333  0.581039  0.476890
5772  20221213    062959  17167.5  ...  54.583333  0.572961  0.456376
5773  20221213    065959  17157.4  ...  54.166667  0.566794  0.438900
5774  20221213    072959  17149.1  ...  54.166667  0.580782  0.418614

[5 rows x 33 columns]
0.5711645101663586
acc is : 0.5711645101663586
2022-12-13 08:00:17,457:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.526985  0.473015       0  ...  0.980732   1.0    0.0  1.012068
537     0  0.512944  0.487056       0  ...  0.980143   1.0    0.0  1.011460
538     0  0.509502  0.490498       0  ...  0.979692   1.0    0.0  1.010995
539     0  0.507430  0.492570       1  ...  0.981063   1.0    0.0  1.012410
540     0  0.510151  0.489849       1  ...  0.982588   1.0    0.0  1.013984

[5 rows x 10 columns]
2022-12-13 08:00:17,469:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526604  0.473396       0  ...  0.980732   1.0    0.0  1.011608
46     0  0.513606  0.486394       0  ...  0.980143   1.0    0.0  1.012505
47     0  0.509257  0.490743       0  ...  0.979692   1.0    0.0  1.010304
48     0  0.508127  0.491873       1  ...  0.981063   1.0    0.0  1.012410
49     0  0.510151  0.489849       1  ...  0.982588   1.0    0.0  1.013984

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-377.89', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17202.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221213   074000    074959  1670888999  17165.2    17198  0.001917
2022-12-13 07:50:00,620:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2551 

self.closeSec=1670889599, self.tradeDate='20221213', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17197.9', self.close='17200'
127.0.0.1 - - [13/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-13 08:00:01,370:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670889599, self.tradeDate='20221213', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17197.9', self.close='17200'
2022-12-13 08:00:01,383:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221213   071000    071959  1670887199  17156.7  17161.5  0.000286
620  20221213   072000    072959  1670887799  17161.5  17173.3  0.000688
621  20221213   073000    073959  1670888399  17173.4  17165.1 -0.000477
622  20221213   074000    074959  1670888999  17165.2    17198  0.001917
623  20221213   075000    075959  1670889599  17197.9    17200  0.000116
2022-12-13 08:00:01,383:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2552 

self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17200', self.close='17174.4'
2022-12-13 08:10:01,524:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17200', self.close='17174.4'
127.0.0.1 - - [13/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-13 08:10:01,544:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221213   072000    072959  1670887799  17161.5  17173.3  0.000688
621  20221213   073000    073959  1670888399  17173.4  17165.1 -0.000477
622  20221213   074000    074959  1670888999  17165.2    17198  0.001917
623  20221213   075000    075959  1670889599  17197.9    17200  0.000116
624  20221213   080000    080959  1670890199    17200  17174.4 -0.001488
2022-12-13 08:10:01,544:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221213   074000    074959  1670888999  17165.2    17198
2022-12-13 07:50:00,640:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2552 

self.closeSec=1670889599, self.tradeDate='20221213', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17197.9', self.close='17200'
127.0.0.1 - - [13/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-13 08:00:01,410:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670889599, self.tradeDate='20221213', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17197.9', self.close='17200'
2022-12-13 08:00:01,433:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221213   071000    071959  1670887199  17156.7  17161.5
17468  20221213   072000    072959  1670887799  17161.5  17173.3
17469  20221213   073000    073959  1670888399  17173.4  17165.1
17470  20221213   074000    074959  1670888999  17165.2    17198
17471  20221213   075000    075959  1670889599  17197.9    17200
2022-12-13 08:00:01,433:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2553 

self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17200', self.close='17174.4'
2022-12-13 08:10:01,529:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17200', self.close='17174.4'
2022-12-13 08:10:01,548:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221213   072000    072959  1670887799  17161.5  17173.3
17469  20221213   073000    073959  1670888399  17173.4  17165.1
17470  20221213   074000    074959  1670888999  17165.2    17198
17471  20221213   075000    075959  1670889599  17197.9    17200
17472  20221213   080000    080959  1670890199    17200  17174.4
2022-12-13 08:10:01,548:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221213   074000    074959  1670888999  17165.2    17198
2022-12-13 07:50:00,635:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2552 

self.closeSec=1670889599, self.tradeDate='20221213', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17197.9', self.close='17200'
127.0.0.1 - - [13/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-13 08:00:01,398:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670889599, self.tradeDate='20221213', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17197.9', self.close='17200'
2022-12-13 08:00:01,423:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221213   071000    071959  1670887199  17156.7  17161.5
12140  20221213   072000    072959  1670887799  17161.5  17173.3
12141  20221213   073000    073959  1670888399  17173.4  17165.1
12142  20221213   074000    074959  1670888999  17165.2    17198
12143  20221213   075000    075959  1670889599  17197.9    17200
2022-12-13 08:00:01,424:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2553 

self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17200', self.close='17174.4'
2022-12-13 08:10:01,527:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17200', self.close='17174.4'
127.0.0.1 - - [13/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-13 08:10:01,540:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221213   072000    072959  1670887799  17161.5  17173.3
12141  20221213   073000    073959  1670888399  17173.4  17165.1
12142  20221213   074000    074959  1670888999  17165.2    17198
12143  20221213   075000    075959  1670889599  17197.9    17200
12144  20221213   080000    080959  1670890199    17200  17174.4
2022-12-13 08:10:01,540:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=536
self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17196.9, self.close=17174.4, self.high=17198.8, self.low=17170.0, self.vol=2384.588, self.amt=40973160.8508 
2022-12-13 08:10:01,499:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221213   074500    074959  ...    0.479523   0.261334       0
5854  20221213   075000    075459  ...    0.479204   0.261545       0
5855  20221213   075500    075959  ...    0.478883   0.261755       0
5856  20221213   080000    080459  ...    0.478563   0.261964       0
5857  20221213   080500    080959  ...    0.478244   0.262174       0

[5 rows x 18 columns]
2022-12-13 08:10:01,499:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670890199, self.tradeDate='20221213', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17196.9, self.close=17174.4, self.high=17198.8, self.low=17170.0, self.vol=2384.588, self.amt=40973160.8508, ukdf['pct'].iloc[-1]=-0.001308 , ukdf['amount'].iloc[-1]=40973160.8508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.47824396059120367, signal=0, value_std=0.2621738019729853 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [13/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=537
self.closeSec=1670890499, self.tradeDate='20221213', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17174.4, self.close=17171.7, self.high=17180.2, self.low=17171.7, self.vol=890.078, self.amt=15288109.3078 
2022-12-13 08:15:00,632:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221213   075000    075459  ...    0.479204   0.261545       0
5855  20221213   075500    075959  ...    0.478883   0.261755       0
5856  20221213   080000    080459  ...    0.478563   0.261964       0
5857  20221213   080500    080959  ...    0.478244   0.262174       0
5858  20221213   081000    081459  ...    0.477923   0.262382       0

[5 rows x 18 columns]
2022-12-13 08:15:00,634:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670890499, self.tradeDate='20221213', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17174.4, self.close=17171.7, self.high=17180.2, self.low=17171.7, self.vol=890.078, self.amt=15288109.3078, ukdf['pct'].iloc[-1]=-0.000157 , ukdf['amount'].iloc[-1]=15288109.3078, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.47792342309678737, signal=0, value_std=0.26238201331370414 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221212   200000    235959  1670860799  ...    719  0.200578 -1.259185    -1.0
720  20221213   000000    035959  1670875199  ...    720  0.151814 -1.462439    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.578', 'enterprice': '16978.7', 'countrevence': '0', 'unrealprofit': '-3473.6754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17038', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [13/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=993583.7103114001, self.flagDict['side']='sell', self.tradeCount=5, self.count=106
self.closeSec=1670889599, self.tradeDate='20221213', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17035.6, self.close=17200.0, self.high=17237.9, self.low=17035.6, self.vol=82215.013, self.amt=1409711916.1141 
2022-12-13 08:00:01,250:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670889599, self.tradeDate='20221213', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17035.6, self.close=17200.0, self.high=17237.9, self.low=17035.6, self.vol=82215.013, self.amt=1409711916.1141 
2022-12-13 08:00:01,302:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221212   120000    155959  ...  27433.054  4.641777e+08  0.000420
718  20221212   160000    195959  ...  36001.638  6.103408e+08  0.003647
719  20221212   200000    235959  ...  71821.147  1.219596e+09  0.001302
720  20221213   000000    035959  ...  25169.941  4.279414e+08  0.002106
721  20221213   040000    075959  ...  82215.013  1.409712e+09  0.009644

[5 rows x 11 columns]
2022-12-13 08:00:02,759:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221212   120000    155959  1670831999  ...    717  0.378032 -0.551198     NaN
718  20221212   160000    195959  1670846399  ...    718  0.299141 -0.866888    -1.0
719  20221212   200000    235959  1670860799  ...    719  0.200578 -1.259185    -1.0
720  20221213   000000    035959  1670875199  ...    720  0.151814 -1.462439    -1.0
721  20221213   040000    075959  1670889599  ...    721  0.362269 -0.663837    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.578', 'enterprice': '16978.7', 'countrevence': '0', 'unrealprofit': '-12963.3114', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17200', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


