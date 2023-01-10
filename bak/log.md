# 20230110 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12602
self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17191.3, self.close=17180.7, self.high=17191.5, self.low=17175.3, self.vol=650.076, self.amt=11169067.3459 
127.0.0.1 - - [10/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-10 08:10:01,471:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230110   074500    074959  ...         0.0        0.0       0
5854  20230110   075000    075459  ...         0.0        0.0       0
5855  20230110   075500    075959  ...         0.0        0.0       0
5856  20230110   080000    080459  ...         0.0        0.0       0
5857  20230110   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 08:10:01,471:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17191.3, self.close=17180.7, self.high=17191.5, self.low=17175.3, self.vol=650.076, self.amt=11169067.3459, ukdf['pct'].iloc[-1]=-0.000622 , ukdf['amount'].iloc[-1]=11169067.3459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-39228.7344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17181.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12603
self.closeSec=1673309699, self.tradeDate='20230110', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17180.7, self.close=17178.2, self.high=17190.0, self.low=17176.4, self.vol=417.757, self.amt=7178442.0301 
127.0.0.1 - - [10/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-10 08:15:00,849:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230110   075000    075459  ...         0.0        0.0       0
5855  20230110   075500    075959  ...         0.0        0.0       0
5856  20230110   080000    080459  ...         0.0        0.0       0
5857  20230110   080500    080959  ...         0.0        0.0       0
5858  20230110   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 08:15:00,849:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673309699, self.tradeDate='20230110', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17180.7, self.close=17178.2, self.high=17190.0, self.low=17176.4, self.vol=417.757, self.amt=7178442.0301, ukdf['pct'].iloc[-1]=-0.000146 , ukdf['amount'].iloc[-1]=7178442.0301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-39069.2545265936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17178.5497761', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17191.3, self.close=17180.7, self.high=17191.5, self.low=17175.3 
2023-01-10 08:10:01,438:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17191.3, self.close=17180.7, self.high=17191.5, self.low=17175.3   
127.0.0.1 - - [10/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-10 08:10:01,453:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230110   074500    074959  1673308199  ...  17170.5 -0.000291   1533    3
1534  20230110   075000    075459  1673308499  ...  17175.2  0.000588   1534    4
1535  20230110   075500    075959  1673308799  ...  17169.9 -0.001018   1535    5
1536  20230110   080000    080459  1673309099  ...  17169.5  0.001252   1536    0
1537  20230110   080500    080959  1673309399  ...  17175.3 -0.000622   1537    1

[5 rows x 11 columns]
2023-01-10 08:10:01,453:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=111, self.factor=0.3470248353318524, self.count=13169 

self.closeSec=1673309699, self.tradeDate='20230110', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17180.7, self.close=17178.2, self.high=17190.0, self.low=17176.4 
2023-01-10 08:15:00,805:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673309699, self.tradeDate='20230110', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17180.7, self.close=17178.2, self.high=17190.0, self.low=17176.4   
2023-01-10 08:15:00,841:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230110   075000    075459  1673308499  ...  17175.2  0.000588   1534    4
1535  20230110   075500    075959  1673308799  ...  17169.9 -0.001018   1535    5
1536  20230110   080000    080459  1673309099  ...  17169.5  0.001252   1536    0
1537  20230110   080500    080959  1673309399  ...  17175.3 -0.000622   1537    1
1538  20230110   081000    081459  1673309699  ...  17176.4 -0.000146   1538    2

[5 rows x 11 columns]
2023-01-10 08:15:00,842:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-10 08:00:16,894:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230110    052959  17212.8  ...  52.500000  0.568191  0.243606
5771  20230110    055959  17226.0  ...  52.500000  0.533841  0.289207
5772  20230110    062959  17172.5  ...  52.500000  0.548846  0.323942
5773  20230110    065959  17200.9  ...  52.500000  0.547146  0.357169
5774  20230110    072959  17197.9  ...  52.083333  0.525837  0.389190

[5 rows x 33 columns]
0.55637707948244
acc is : 0.55637707948244
2023-01-10 08:00:16,998:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     1  0.495162  0.504838       0  ...  NaN   NaN -0.0016  1.033675
537     1  0.475412  0.524588       1  ...  NaN   NaN -0.0016  1.035457
538     0  0.501024  0.498976       0  ...  NaN   NaN -0.0016  1.035288
539     1  0.498083  0.501917       0  ...  NaN   NaN -0.0016  1.033127
540     1  0.488023  0.511977       1  ...  NaN   NaN -0.0016  1.033597

[5 rows x 10 columns]
2023-01-10 08:00:17,022:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.494992  0.505008       0  ...  NaN   NaN -0.0016  1.033781
46     1  0.475060  0.524940       1  ...  NaN   NaN -0.0016  1.034324
47     0  0.500856  0.499144       0  ...  NaN   NaN -0.0016  1.034466
48     1  0.498083  0.501917       0  ...  NaN   NaN -0.0016  1.033127
49     1  0.488023  0.511977       1  ...  NaN   NaN -0.0016  1.033597

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '20043.4464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17172.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230110   074000    074959  1673308199  17183.7  17177.3 -0.000372
2023-01-10 07:50:00,582:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6583 

self.closeSec=1673308799, self.tradeDate='20230110', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17177.4', self.close='17169.7'
2023-01-10 08:00:01,370:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673308799, self.tradeDate='20230110', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17177.4', self.close='17169.7'
2023-01-10 08:00:01,381:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230110   071000    071959  1673306399  17140.7  17168.7  0.001476
620  20230110   072000    072959  1673306999  17168.8  17162.1 -0.000384
621  20230110   073000    073959  1673307599    17162  17183.7  0.001259
622  20230110   074000    074959  1673308199  17183.7  17177.3 -0.000372
623  20230110   075000    075959  1673308799  17177.4  17169.7 -0.000442
2023-01-10 08:00:01,390:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6584 

self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17169.6', self.close='17180.7'
2023-01-10 08:10:01,525:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17169.6', self.close='17180.7'
127.0.0.1 - - [10/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-10 08:10:01,564:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230110   072000    072959  1673306999  17168.8  17162.1 -0.000384
621  20230110   073000    073959  1673307599    17162  17183.7  0.001259
622  20230110   074000    074959  1673308199  17183.7  17177.3 -0.000372
623  20230110   075000    075959  1673308799  17177.4  17169.7 -0.000442
624  20230110   080000    080959  1673309399  17169.6  17180.7  0.000641
2023-01-10 08:10:01,564:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230110   074000    074959  1673308199  17183.7  17177.3
2023-01-10 07:50:00,566:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6584 

self.closeSec=1673308799, self.tradeDate='20230110', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17177.4', self.close='17169.7'
2023-01-10 08:00:01,417:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673308799, self.tradeDate='20230110', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17177.4', self.close='17169.7'
2023-01-10 08:00:01,450:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230110   071000    071959  1673306399  17140.7  17168.7
17468  20230110   072000    072959  1673306999  17168.8  17162.1
17469  20230110   073000    073959  1673307599    17162  17183.7
17470  20230110   074000    074959  1673308199  17183.7  17177.3
17471  20230110   075000    075959  1673308799  17177.4  17169.7
2023-01-10 08:00:01,451:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6585 

self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17169.6', self.close='17180.7'
2023-01-10 08:10:01,530:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17169.6', self.close='17180.7'
127.0.0.1 - - [10/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-10 08:10:01,537:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230110   072000    072959  1673306999  17168.8  17162.1
17469  20230110   073000    073959  1673307599    17162  17183.7
17470  20230110   074000    074959  1673308199  17183.7  17177.3
17471  20230110   075000    075959  1673308799  17177.4  17169.7
17472  20230110   080000    080959  1673309399  17169.6  17180.7
2023-01-10 08:10:01,537:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230110   074000    074959  1673308199  17183.7  17177.3
2023-01-10 07:50:00,592:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6584 

self.closeSec=1673308799, self.tradeDate='20230110', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17177.4', self.close='17169.7'
2023-01-10 08:00:01,413:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673308799, self.tradeDate='20230110', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17177.4', self.close='17169.7'
2023-01-10 08:00:01,435:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230110   071000    071959  1673306399  17140.7  17168.7
12140  20230110   072000    072959  1673306999  17168.8  17162.1
12141  20230110   073000    073959  1673307599    17162  17183.7
12142  20230110   074000    074959  1673308199  17183.7  17177.3
12143  20230110   075000    075959  1673308799  17177.4  17169.7
2023-01-10 08:00:01,435:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6585 

self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17169.6', self.close='17180.7'
2023-01-10 08:10:01,546:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17169.6', self.close='17180.7'
2023-01-10 08:10:01,573:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230110   072000    072959  1673306999  17168.8  17162.1
12141  20230110   073000    073959  1673307599    17162  17183.7
12142  20230110   074000    074959  1673308199  17183.7  17177.3
12143  20230110   075000    075959  1673308799  17177.4  17169.7
12144  20230110   080000    080959  1673309399  17169.6  17180.7
2023-01-10 08:10:01,573:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [10/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8600
self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17191.3, self.close=17180.7, self.high=17191.5, self.low=17175.3, self.vol=650.076, self.amt=11169067.3459 
2023-01-10 08:10:01,495:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230110   074500    074959  ...         0.0        0.0       0
5854  20230110   075000    075459  ...         0.0        0.0       0
5855  20230110   075500    075959  ...         0.0        0.0       0
5856  20230110   080000    080459  ...         0.0        0.0       0
5857  20230110   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 08:10:01,496:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673309399, self.tradeDate='20230110', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17191.3, self.close=17180.7, self.high=17191.5, self.low=17175.3, self.vol=650.076, self.amt=11169067.3459, ukdf['pct'].iloc[-1]=-0.000622 , ukdf['amount'].iloc[-1]=11169067.3459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8601
self.closeSec=1673309699, self.tradeDate='20230110', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17180.7, self.close=17178.2, self.high=17190.0, self.low=17176.4, self.vol=417.757, self.amt=7178442.0301 
127.0.0.1 - - [10/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-10 08:15:00,880:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230110   075000    075459  ...         0.0        0.0       0
5855  20230110   075500    075959  ...         0.0        0.0       0
5856  20230110   080000    080459  ...         0.0        0.0       0
5857  20230110   080500    080959  ...         0.0        0.0       0
5858  20230110   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 08:15:00,880:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673309699, self.tradeDate='20230110', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17180.7, self.close=17178.2, self.high=17190.0, self.low=17176.4, self.vol=417.757, self.amt=7178442.0301, ukdf['pct'].iloc[-1]=-0.000146 , ukdf['amount'].iloc[-1]=7178442.0301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230109   200000    235959  1673279999  ...    719  0.801034  1.512647     1.0
720  20230110   000000    035959  1673294399  ...    720  0.904541  1.823699     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '4940.13586608832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17284.80778837', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [10/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=274
self.closeSec=1673308799, self.tradeDate='20230110', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17285.6, self.close=17169.7, self.high=17302.3, self.low=17118.3, self.vol=70626.832, self.amt=1214983822.8185 
2023-01-10 08:00:01,057:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673308799, self.tradeDate='20230110', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17285.6, self.close=17169.7, self.high=17302.3, self.low=17118.3, self.vol=70626.832, self.amt=1214983822.8185 
2023-01-10 08:00:01,101:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230109   120000    155959  ...  35863.212  6.170962e+08  0.000087
718  20230109   160000    195959  ...  50754.110  8.747792e+08  0.002467
719  20230109   200000    235959  ...  80348.391  1.386487e+09  0.001747
720  20230110   000000    035959  ...  77462.066  1.342329e+09  0.001361
721  20230110   040000    075959  ...  70626.832  1.214984e+09 -0.006711

[5 rows x 11 columns]
2023-01-10 08:00:02,591:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230109   120000    155959  1673251199  ...    717  0.651387  1.049407     1.0
718  20230109   160000    195959  1673265599  ...    718  0.719609  1.262125     1.0
719  20230109   200000    235959  1673279999  ...    719  0.801034  1.512647     1.0
720  20230110   000000    035959  1673294399  ...    720  0.904541  1.823699     1.0
721  20230110   040000    075959  1673308799  ...    721  0.950988  1.925823     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '-886.90631647488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17170.85593092', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


