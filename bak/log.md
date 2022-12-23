# 20221223 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7418
self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16797.0, self.close=16803.0, self.high=16805.1, self.low=16795.9, self.vol=483.623, self.amt=8124704.1887 
127.0.0.1 - - [23/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-23 08:10:01,475:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221223   074500    074959  ...         0.0        0.0       0
5854  20221223   075000    075459  ...         0.0        0.0       0
5855  20221223   075500    075959  ...         0.0        0.0       0
5856  20221223   080000    080459  ...         0.0        0.0       0
5857  20221223   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 08:10:01,476:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16797.0, self.close=16803.0, self.high=16805.1, self.low=16795.9, self.vol=483.623, self.amt=8124704.1887, ukdf['pct'].iloc[-1]=0.000363 , ukdf['amount'].iloc[-1]=8124704.1887, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16470.1712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16803', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7419
self.closeSec=1671754499, self.tradeDate='20221223', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16803.0, self.close=16793.4, self.high=16805.0, self.low=16785.4, self.vol=831.884, self.amt=13970995.3508 
127.0.0.1 - - [23/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-23 08:15:00,821:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221223   075000    075459  ...         0.0        0.0       0
5855  20221223   075500    075959  ...         0.0        0.0       0
5856  20221223   080000    080459  ...         0.0        0.0       0
5857  20221223   080500    080959  ...         0.0        0.0       0
5858  20221223   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 08:15:00,821:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671754499, self.tradeDate='20221223', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16803.0, self.close=16793.4, self.high=16805.0, self.low=16785.4, self.vol=831.884, self.amt=13970995.3508, ukdf['pct'].iloc[-1]=-0.000571 , ukdf['amount'].iloc[-1]=13970995.3508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15935.02538932032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16794.10698932', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=86, self.factor=0.4560630346214608, self.count=7984 

self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16797.0, self.close=16803.0, self.high=16805.1, self.low=16795.9 
2022-12-23 08:10:01,428:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16797.0, self.close=16803.0, self.high=16805.1, self.low=16795.9   
2022-12-23 08:10:01,467:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221223   074500    074959  1671752999  ...  16813.7 -0.000107   1533    3
1534  20221223   075000    075459  1671753299  ...  16811.9 -0.000113   1534    4
1535  20221223   075500    075959  1671753599  ...  16813.0  0.000000   1535    5
1536  20221223   080000    080459  1671753899  ...  16794.4 -0.001106   1536    0
1537  20221223   080500    080959  1671754199  ...  16795.9  0.000363   1537    1

[5 rows x 11 columns]
2022-12-23 08:10:01,468:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=86, self.factor=0.4560630346214608, self.count=7985 

self.closeSec=1671754499, self.tradeDate='20221223', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16803.0, self.close=16793.4, self.high=16805.0, self.low=16785.4 
2022-12-23 08:15:00,775:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671754499, self.tradeDate='20221223', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16803.0, self.close=16793.4, self.high=16805.0, self.low=16785.4   
127.0.0.1 - - [23/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-23 08:15:00,825:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221223   075000    075459  1671753299  ...  16811.9 -0.000113   1534    4
1535  20221223   075500    075959  1671753599  ...  16813.0  0.000000   1535    5
1536  20221223   080000    080459  1671753899  ...  16794.4 -0.001106   1536    0
1537  20221223   080500    080959  1671754199  ...  16795.9  0.000363   1537    1
1538  20221223   081000    081459  1671754499  ...  16785.4 -0.000571   1538    2

[5 rows x 11 columns]
2022-12-23 08:15:00,825:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-23 08:00:17,382:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221223    052959  16775.4  ...  50.833333  0.518903  0.568777
5771  20221223    055959  16811.6  ...  50.416667  0.509215  0.546184
5772  20221223    062959  16791.6  ...  50.416667  0.513111  0.523267
5773  20221223    065959  16800.1  ...  50.000000  0.510747  0.502923
5774  20221223    072959  16795.2  ...  50.000000  0.515914  0.481560

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2022-12-23 08:00:17,485:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.526924  0.473076       0  ...  1.097373   1.0    0.0  0.978138
537     0  0.508235  0.491765       1  ...  1.097921   1.0    0.0  0.978627
538     0  0.514032  0.485968       0  ...  1.097608   1.0    0.0  0.978348
539     1  0.497943  0.502057       1  ...  1.098320   1.0    0.0  0.978983
540     0  0.502787  0.497213       1  ...  1.098934   1.0    0.0  0.979530

[5 rows x 10 columns]
2022-12-23 08:00:17,510:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.527515  0.472485       0  ...  1.097373   1.0    0.0  0.979359
46     0  0.508613  0.491387       1  ...  1.097921   1.0    0.0  0.979769
47     0  0.514178  0.485822       0  ...  1.097608   1.0    0.0  0.979101
48     1  0.497943  0.502057       1  ...  1.098320   1.0    0.0  0.978983
49     0  0.502787  0.497213       1  ...  1.098934   1.0    0.0  0.979530

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '4975.776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16818.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221223   074000    074959  1671752999  16821.6  16817.4 -0.000256
2022-12-23 07:50:00,589:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3991 

self.closeSec=1671753599, self.tradeDate='20221223', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16817.4', self.close='16815.5'
127.0.0.1 - - [23/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-23 08:00:01,184:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671753599, self.tradeDate='20221223', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16817.4', self.close='16815.5'
2022-12-23 08:00:01,200:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221223   071000    071959  1671751199  16813.8  16814.8  0.000054
620  20221223   072000    072959  1671751799  16814.9  16806.1 -0.000517
621  20221223   073000    073959  1671752399  16806.2  16821.7  0.000928
622  20221223   074000    074959  1671752999  16821.6  16817.4 -0.000256
623  20221223   075000    075959  1671753599  16817.4  16815.5 -0.000113
2022-12-23 08:00:01,200:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3992 

self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16815.5', self.close='16803'
2022-12-23 08:10:01,524:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16815.5', self.close='16803'
2022-12-23 08:10:01,547:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221223   072000    072959  1671751799  16814.9  16806.1 -0.000517
621  20221223   073000    073959  1671752399  16806.2  16821.7  0.000928
622  20221223   074000    074959  1671752999  16821.6  16817.4 -0.000256
623  20221223   075000    075959  1671753599  16817.4  16815.5 -0.000113
624  20221223   080000    080959  1671754199  16815.5    16803 -0.000743
2022-12-23 08:10:01,547:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221223   074000    074959  1671752999  16821.6  16817.4
2022-12-23 07:50:00,616:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3992 

self.closeSec=1671753599, self.tradeDate='20221223', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16817.4', self.close='16815.5'
127.0.0.1 - - [23/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-23 08:00:01,160:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671753599, self.tradeDate='20221223', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16817.4', self.close='16815.5'
2022-12-23 08:00:01,172:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221223   071000    071959  1671751199  16813.8  16814.8
17468  20221223   072000    072959  1671751799  16814.9  16806.1
17469  20221223   073000    073959  1671752399  16806.2  16821.7
17470  20221223   074000    074959  1671752999  16821.6  16817.4
17471  20221223   075000    075959  1671753599  16817.4  16815.5
2022-12-23 08:00:01,172:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3993 

self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16815.5', self.close='16803'
2022-12-23 08:10:01,539:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16815.5', self.close='16803'
2022-12-23 08:10:01,551:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221223   072000    072959  1671751799  16814.9  16806.1
17469  20221223   073000    073959  1671752399  16806.2  16821.7
17470  20221223   074000    074959  1671752999  16821.6  16817.4
17471  20221223   075000    075959  1671753599  16817.4  16815.5
17472  20221223   080000    080959  1671754199  16815.5    16803
2022-12-23 08:10:01,551:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221223   074000    074959  1671752999  16821.6  16817.4
2022-12-23 07:50:00,613:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [23/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3992 

self.closeSec=1671753599, self.tradeDate='20221223', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16817.4', self.close='16815.5'
2022-12-23 08:00:01,195:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671753599, self.tradeDate='20221223', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16817.4', self.close='16815.5'
2022-12-23 08:00:01,255:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221223   071000    071959  1671751199  16813.8  16814.8
12140  20221223   072000    072959  1671751799  16814.9  16806.1
12141  20221223   073000    073959  1671752399  16806.2  16821.7
12142  20221223   074000    074959  1671752999  16821.6  16817.4
12143  20221223   075000    075959  1671753599  16817.4  16815.5
2022-12-23 08:00:01,255:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [23/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3993 

self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16815.5', self.close='16803'
2022-12-23 08:10:01,548:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16815.5', self.close='16803'
2022-12-23 08:10:01,566:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221223   072000    072959  1671751799  16814.9  16806.1
12141  20221223   073000    073959  1671752399  16806.2  16821.7
12142  20221223   074000    074959  1671752999  16821.6  16817.4
12143  20221223   075000    075959  1671753599  16817.4  16815.5
12144  20221223   080000    080959  1671754199  16815.5    16803
2022-12-23 08:10:01,566:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3416
self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16797.0, self.close=16803.0, self.high=16805.1, self.low=16795.9, self.vol=483.623, self.amt=8124704.1887 
127.0.0.1 - - [23/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-23 08:10:01,477:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221223   074500    074959  ...         0.0        0.0       0
5854  20221223   075000    075459  ...         0.0        0.0       0
5855  20221223   075500    075959  ...         0.0        0.0       0
5856  20221223   080000    080459  ...         0.0        0.0       0
5857  20221223   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 08:10:01,477:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671754199, self.tradeDate='20221223', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16797.0, self.close=16803.0, self.high=16805.1, self.low=16795.9, self.vol=483.623, self.amt=8124704.1887, ukdf['pct'].iloc[-1]=0.000363 , ukdf['amount'].iloc[-1]=8124704.1887, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3417
self.closeSec=1671754499, self.tradeDate='20221223', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16803.0, self.close=16793.4, self.high=16805.0, self.low=16785.4, self.vol=831.884, self.amt=13970995.3508 
127.0.0.1 - - [23/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-23 08:15:00,793:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221223   075000    075459  ...         0.0        0.0       0
5855  20221223   075500    075959  ...         0.0        0.0       0
5856  20221223   080000    080459  ...         0.0        0.0       0
5857  20221223   080500    080959  ...         0.0        0.0       0
5858  20221223   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 08:15:00,794:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671754499, self.tradeDate='20221223', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16803.0, self.close=16793.4, self.high=16805.0, self.low=16785.4, self.vol=831.884, self.amt=13970995.3508, ukdf['pct'].iloc[-1]=-0.000571 , ukdf['amount'].iloc[-1]=13970995.3508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221222   200000    235959  1671724799  ...    719  0.035780 -1.677523    -1.0
720  20221223   000000    035959  1671739199  ...    720  0.047576 -1.601173    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '3437.1568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16658.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [23/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=166
self.closeSec=1671753599, self.tradeDate='20221223', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16658.3, self.close=16815.4, self.high=16849.4, self.low=16643.6, self.vol=77053.704, self.amt=1293022793.0882 
2022-12-23 08:00:01,038:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671753599, self.tradeDate='20221223', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16658.3, self.close=16815.4, self.high=16849.4, self.low=16643.6, self.vol=77053.704, self.amt=1293022793.0882 
2022-12-23 08:00:01,064:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221222   120000    155959  ...  20542.365  3.453780e+08 -0.001454
718  20221222   160000    195959  ...  27422.375  4.614884e+08  0.000452
719  20221222   200000    235959  ...  98813.975  1.650437e+09 -0.011653
720  20221223   000000    035959  ...  63297.216  1.051686e+09  0.001611
721  20221223   040000    075959  ...  77053.704  1.293023e+09  0.009431

[5 rows x 11 columns]
2022-12-23 08:00:02,499:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221222   120000    155959  1671695999  ...    717  0.036387 -1.774678    -1.0
718  20221222   160000    195959  1671710399  ...    718  0.037604 -1.720944    -1.0
719  20221222   200000    235959  1671724799  ...    719  0.035780 -1.677523    -1.0
720  20221223   000000    035959  1671739199  ...    720  0.047576 -1.601173    -1.0
721  20221223   040000    075959  1671753599  ...    721  0.047321 -1.558658    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-4979.6076', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16816.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


