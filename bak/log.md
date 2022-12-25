# 20221225 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [25/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7994
self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16827.7, self.close=16825.6, self.high=16828.9, self.low=16825.6, self.vol=166.735, self.amt=2805660.0617 
2022-12-25 08:10:01,484:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221225   074500    074959  ...         0.0        0.0       0
5854  20221225   075000    075459  ...         0.0        0.0       0
5855  20221225   075500    075959  ...         0.0        0.0       0
5856  20221225   080000    080459  ...         0.0        0.0       0
5857  20221225   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 08:10:01,484:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16827.7, self.close=16825.6, self.high=16828.9, self.low=16825.6, self.vol=166.735, self.amt=2805660.0617, ukdf['pct'].iloc[-1]=-0.000131 , ukdf['amount'].iloc[-1]=2805660.0617, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17836.1664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16825.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7995
self.closeSec=1671927299, self.tradeDate='20221225', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16825.6, self.close=16825.6, self.high=16825.7, self.low=16825.6, self.vol=62.802, self.amt=1056684.4955 
127.0.0.1 - - [25/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-25 08:15:00,593:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221225   075000    075459  ...         0.0        0.0       0
5855  20221225   075500    075959  ...         0.0        0.0       0
5856  20221225   080000    080459  ...         0.0        0.0       0
5857  20221225   080500    080959  ...         0.0        0.0       0
5858  20221225   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 08:15:00,593:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671927299, self.tradeDate='20221225', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16825.6, self.close=16825.6, self.high=16825.7, self.low=16825.6, self.vol=62.802, self.amt=1056684.4955, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=1056684.4955, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17836.1664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16825.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16827.7, self.close=16825.6, self.high=16828.9, self.low=16825.6 
2022-12-25 08:10:01,433:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16827.7, self.close=16825.6, self.high=16828.9, self.low=16825.6   
127.0.0.1 - - [25/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-25 08:10:01,480:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221225   074500    074959  1671925799  ...  16831.9 -0.000095   1533    3
1534  20221225   075000    075459  1671926099  ...  16825.9 -0.000279   1534    4
1535  20221225   075500    075959  1671926399  ...  16827.2  0.000107   1535    5
1536  20221225   080000    080459  1671926699  ...  16824.4 -0.000071   1536    0
1537  20221225   080500    080959  1671926999  ...  16825.6 -0.000131   1537    1

[5 rows x 11 columns]
2022-12-25 08:10:01,480:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=182, self.factor=0.42271737999424985, self.count=8561 

self.closeSec=1671927299, self.tradeDate='20221225', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16825.6, self.close=16825.6, self.high=16825.7, self.low=16825.6 
2022-12-25 08:15:00,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671927299, self.tradeDate='20221225', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16825.6, self.close=16825.6, self.high=16825.7, self.low=16825.6   
127.0.0.1 - - [25/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-25 08:15:00,578:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221225   075000    075459  1671926099  ...  16825.9 -0.000279   1534    4
1535  20221225   075500    075959  1671926399  ...  16827.2  0.000107   1535    5
1536  20221225   080000    080459  1671926699  ...  16824.4 -0.000071   1536    0
1537  20221225   080500    080959  1671926999  ...  16825.6 -0.000131   1537    1
1538  20221225   081000    081459  1671927299  ...  16825.6  0.000000   1538    2

[5 rows x 11 columns]
2022-12-25 08:15:00,578:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-25 08:00:20,306:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221225    052959  16833.1  ...  50.000000  0.522298  0.358087
5771  20221225    055959  16837.5  ...  50.000000  0.501708  0.379397
5772  20221225    062959  16817.0  ...  50.000000  0.498074  0.403494
5773  20221225    065959  16813.3  ...  50.416667  0.504117  0.419520
5774  20221225    072959  16819.5  ...  50.416667  0.504914  0.433629

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2022-12-25 08:00:20,433:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.496783  0.503217       0  ...  1.072305   1.0    0.0  0.948361
537     1  0.489355  0.510645       0  ...  1.072069   1.0    0.0  0.948152
538     1  0.492287  0.507713       1  ...  1.072458   1.0    0.0  0.948496
539     1  0.495151  0.504849       1  ...  1.072509   1.0    0.0  0.948541
540     1  0.494259  0.505741       1  ...  1.073064   1.0    0.0  0.949032

[5 rows x 10 columns]
2022-12-25 08:00:20,459:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496679  0.503321       0  ...  1.072305   1.0    0.0  0.947463
46     1  0.488967  0.511033       0  ...  1.072069   1.0    0.0  0.945098
47     1  0.492132  0.507868       1  ...  1.072458   1.0    0.0  0.947358
48     1  0.495259  0.504741       1  ...  1.072509   1.0    0.0  0.948541
49     1  0.494259  0.505741       1  ...  1.073064   1.0    0.0  0.949032

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5418.0672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16828.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221225   074000    074959  1671925799  16828.2    16832  0.000220
2022-12-25 07:50:00,767:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4279 

self.closeSec=1671926399, self.tradeDate='20221225', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16831.9', self.close='16829'
127.0.0.1 - - [25/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-25 08:00:01,152:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671926399, self.tradeDate='20221225', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16831.9', self.close='16829'
2022-12-25 08:00:01,212:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221225   071000    071959  1671923999  16818.9  16834.9  0.000951
620  20221225   072000    072959  1671924599    16835  16820.2 -0.000873
621  20221225   073000    073959  1671925199  16820.3  16828.3  0.000482
622  20221225   074000    074959  1671925799  16828.2    16832  0.000220
623  20221225   075000    075959  1671926399  16831.9    16829 -0.000178
2022-12-25 08:00:01,212:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4280 

self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16829', self.close='16825.6'
2022-12-25 08:10:01,520:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16829', self.close='16825.6'
127.0.0.1 - - [25/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-25 08:10:01,540:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221225   072000    072959  1671924599    16835  16820.2 -0.000873
621  20221225   073000    073959  1671925199  16820.3  16828.3  0.000482
622  20221225   074000    074959  1671925799  16828.2    16832  0.000220
623  20221225   075000    075959  1671926399  16831.9    16829 -0.000178
624  20221225   080000    080959  1671926999    16829  16825.6 -0.000202
2022-12-25 08:10:01,540:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221225   074000    074959  1671925799  16828.2    16832
2022-12-25 07:50:00,818:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4280 

self.closeSec=1671926399, self.tradeDate='20221225', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16831.9', self.close='16829'
2022-12-25 08:00:01,138:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671926399, self.tradeDate='20221225', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16831.9', self.close='16829'
2022-12-25 08:00:01,158:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221225   071000    071959  1671923999  16818.9  16834.9
17468  20221225   072000    072959  1671924599    16835  16820.2
17469  20221225   073000    073959  1671925199  16820.3  16828.3
17470  20221225   074000    074959  1671925799  16828.2    16832
17471  20221225   075000    075959  1671926399  16831.9    16829
2022-12-25 08:00:01,158:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4281 

self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16829', self.close='16825.6'
2022-12-25 08:10:01,531:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16829', self.close='16825.6'
2022-12-25 08:10:01,553:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221225   072000    072959  1671924599    16835  16820.2
17469  20221225   073000    073959  1671925199  16820.3  16828.3
17470  20221225   074000    074959  1671925799  16828.2    16832
17471  20221225   075000    075959  1671926399  16831.9    16829
17472  20221225   080000    080959  1671926999    16829  16825.6
2022-12-25 08:10:01,554:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221225   074000    074959  1671925799  16828.2    16832
2022-12-25 07:50:00,820:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4280 

self.closeSec=1671926399, self.tradeDate='20221225', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16831.9', self.close='16829'
2022-12-25 08:00:01,192:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671926399, self.tradeDate='20221225', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16831.9', self.close='16829'
2022-12-25 08:00:01,242:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221225   071000    071959  1671923999  16818.9  16834.9
12140  20221225   072000    072959  1671924599    16835  16820.2
12141  20221225   073000    073959  1671925199  16820.3  16828.3
12142  20221225   074000    074959  1671925799  16828.2    16832
12143  20221225   075000    075959  1671926399  16831.9    16829
2022-12-25 08:00:01,247:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4281 

self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16829', self.close='16825.6'
2022-12-25 08:10:01,530:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16829', self.close='16825.6'
127.0.0.1 - - [25/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-25 08:10:01,542:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221225   072000    072959  1671924599    16835  16820.2
12141  20221225   073000    073959  1671925199  16820.3  16828.3
12142  20221225   074000    074959  1671925799  16828.2    16832
12143  20221225   075000    075959  1671926399  16831.9    16829
12144  20221225   080000    080959  1671926999    16829  16825.6
2022-12-25 08:10:01,542:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3992
self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16827.7, self.close=16825.6, self.high=16828.9, self.low=16825.6, self.vol=166.735, self.amt=2805660.0617 
127.0.0.1 - - [25/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-25 08:10:01,499:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221225   074500    074959  ...         0.0        0.0       0
5854  20221225   075000    075459  ...         0.0        0.0       0
5855  20221225   075500    075959  ...         0.0        0.0       0
5856  20221225   080000    080459  ...         0.0        0.0       0
5857  20221225   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 08:10:01,500:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671926999, self.tradeDate='20221225', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16827.7, self.close=16825.6, self.high=16828.9, self.low=16825.6, self.vol=166.735, self.amt=2805660.0617, ukdf['pct'].iloc[-1]=-0.000131 , ukdf['amount'].iloc[-1]=2805660.0617, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3993
self.closeSec=1671927299, self.tradeDate='20221225', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16825.6, self.close=16825.6, self.high=16825.7, self.low=16825.6, self.vol=62.802, self.amt=1056684.4955 
127.0.0.1 - - [25/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-25 08:15:00,589:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221225   075000    075459  ...         0.0        0.0       0
5855  20221225   075500    075959  ...         0.0        0.0       0
5856  20221225   080000    080459  ...         0.0        0.0       0
5857  20221225   080500    080959  ...         0.0        0.0       0
5858  20221225   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 08:15:00,590:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671927299, self.tradeDate='20221225', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16825.6, self.close=16825.6, self.high=16825.7, self.low=16825.6, self.vol=62.802, self.amt=1056684.4955, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=1056684.4955, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221224   200000    235959  1671897599  ...    719  0.002641 -1.316021    -1.0
720  20221225   000000    035959  1671911999  ...    720  0.018419 -1.252596    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5956.3152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16834.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [25/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=178
self.closeSec=1671926399, self.tradeDate='20221225', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16834.6, self.close=16828.9, self.high=16847.1, self.low=16803.6, self.vol=13189.41, self.amt=221923937.5278 
2022-12-25 08:00:01,045:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671926399, self.tradeDate='20221225', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16834.6, self.close=16828.9, self.high=16847.1, self.low=16803.6, self.vol=13189.41, self.amt=221923937.5278 
2022-12-25 08:00:01,118:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221224   120000    155959  ...  15969.157  2.686288e+08  0.000410
718  20221224   160000    195959  ...  12975.412  2.183272e+08 -0.001247
719  20221224   200000    235959  ...  12508.365  2.103864e+08  0.000654
720  20221225   000000    035959  ...  12443.214  2.094663e+08  0.000261
721  20221225   040000    075959  ...  13189.410  2.219239e+08 -0.000339

[5 rows x 11 columns]
2022-12-25 08:00:02,826:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221224   120000    155959  1671868799  ...    717  0.005509 -1.369103    -1.0
718  20221224   160000    195959  1671883199  ...    718  0.003998 -1.342539    -1.0
719  20221224   200000    235959  1671897599  ...    719  0.002641 -1.316021    -1.0
720  20221225   000000    035959  1671911999  ...    720  0.018419 -1.252596    -1.0
721  20221225   040000    075959  1671926399  ...    721  0.016321 -1.231471    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5646.7576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16828.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


