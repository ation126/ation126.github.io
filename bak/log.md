# 20221216 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [16/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5402
self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17371.0, self.close=17346.5, self.high=17371.1, self.low=17344.1, self.vol=970.005, self.amt=16833049.1939 
2022-12-16 08:10:01,552:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221216   074500    074959  ...         0.0        0.0       0
5854  20221216   075000    075459  ...         0.0        0.0       0
5855  20221216   075500    075959  ...         0.0        0.0       0
5856  20221216   080000    080459  ...         0.0        0.0       0
5857  20221216   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-16 08:10:01,556:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17371.0, self.close=17346.5, self.high=17371.1, self.low=17344.1, self.vol=970.005, self.amt=16833049.1939, ukdf['pct'].iloc[-1]=-0.001497 , ukdf['amount'].iloc[-1]=16833049.1939, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-49271.13882125072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17348.08388097', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5403
self.closeSec=1671149699, self.tradeDate='20221216', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17346.5, self.close=17367.9, self.high=17384.0, self.low=17346.2, self.vol=1291.726, self.amt=22435493.7215 
2022-12-16 08:15:00,798:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221216   075000    075459  ...         0.0        0.0       0
5855  20221216   075500    075959  ...         0.0        0.0       0
5856  20221216   080000    080459  ...         0.0        0.0       0
5857  20221216   080500    080959  ...         0.0        0.0       0
5858  20221216   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-16 08:15:00,798:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671149699, self.tradeDate='20221216', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17346.5, self.close=17367.9, self.high=17384.0, self.low=17346.2, self.vol=1291.726, self.amt=22435493.7215, ukdf['pct'].iloc[-1]=0.001234 , ukdf['amount'].iloc[-1]=22435493.7215, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-50464.09372333776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17367.90831101', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7431054397731853, self.count=5968 

self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17371.0, self.close=17346.5, self.high=17371.1, self.low=17344.1 
2022-12-16 08:10:01,430:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17371.0, self.close=17346.5, self.high=17371.1, self.low=17344.1   
2022-12-16 08:10:01,514:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221216   074500    074959  1671148199  ...  17335.1  0.001569   1533    3
1534  20221216   075000    075459  1671148499  ...  17334.1 -0.001267   1534    4
1535  20221216   075500    075959  1671148799  ...  17343.0  0.000502   1535    5
1536  20221216   080000    080459  1671149099  ...  17338.3  0.001193   1536    0
1537  20221216   080500    080959  1671149399  ...  17344.1 -0.001497   1537    1

[5 rows x 11 columns]
2022-12-16 08:10:01,517:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7431054397731853, self.count=5969 

self.closeSec=1671149699, self.tradeDate='20221216', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17346.5, self.close=17367.9, self.high=17384.0, self.low=17346.2 
2022-12-16 08:15:00,756:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671149699, self.tradeDate='20221216', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17346.5, self.close=17367.9, self.high=17384.0, self.low=17346.2   
2022-12-16 08:15:00,780:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221216   075000    075459  1671148499  ...  17334.1 -0.001267   1534    4
1535  20221216   075500    075959  1671148799  ...  17343.0  0.000502   1535    5
1536  20221216   080000    080459  1671149099  ...  17338.3  0.001193   1536    0
1537  20221216   080500    080959  1671149399  ...  17344.1 -0.001497   1537    1
1538  20221216   081000    081459  1671149699  ...  17346.2  0.001234   1538    2

[5 rows x 11 columns]
2022-12-16 08:15:00,780:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-16 08:00:17,494:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221216    052959  17410.2  ...  49.583333  0.427155  0.830865
5771  20221216    055959  17402.1  ...  49.583333  0.423327  0.830259
5772  20221216    062959  17388.9  ...  49.166667  0.409209  0.830646
5773  20221216    065959  17340.0  ...  49.166667  0.407705  0.831735
5774  20221216    072959  17334.7  ...  49.583333  0.408321  0.832549

[5 rows x 33 columns]
0.5822550831792976
acc is : 0.5822550831792976
2022-12-16 08:00:17,579:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.498228  0.501772       0  ...  1.049891  -1.0    0.0  1.023358
537     1  0.493776  0.506224       0  ...  1.052898  -1.0    0.0  1.020427
538     1  0.480428  0.519572       0  ...  1.053226  -1.0    0.0  1.020109
539     1  0.488323  0.511677       1  ...  1.053135  -1.0    0.0  1.020198
540     1  0.493319  0.506681       1  ...  1.052053  -1.0    0.0  1.021245

[5 rows x 10 columns]
2022-12-16 08:00:17,590:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498057  0.501943       0  ...  1.049891  -1.0    0.0  1.021536
46     1  0.493376  0.506624       0  ...  1.052898  -1.0    0.0  1.017195
47     1  0.480193  0.519807       0  ...  1.053226  -1.0    0.0  1.019270
48     1  0.488445  0.511555       1  ...  1.053135  -1.0    0.0  1.020198
49     1  0.493319  0.506681       1  ...  1.052053  -1.0    0.0  1.021245

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '15824.3688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17350.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221216   074000    074959  1671148199  17295.6  17365.1  0.004013
2022-12-16 07:50:00,576:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2983 

self.closeSec=1671148799, self.tradeDate='20221216', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17365', self.close='17351.8'
2022-12-16 08:00:01,264:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671148799, self.tradeDate='20221216', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17365', self.close='17351.8'
2022-12-16 08:00:01,302:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221216   071000    071959  1671146399  17356.2  17328.7 -0.001579
620  20221216   072000    072959  1671146999  17328.6  17335.2  0.000375
621  20221216   073000    073959  1671147599  17335.3  17295.7 -0.002279
622  20221216   074000    074959  1671148199  17295.6  17365.1  0.004013
623  20221216   075000    075959  1671148799    17365  17351.8 -0.000766
2022-12-16 08:00:01,302:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2984 

self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17351.9', self.close='17346.5'
2022-12-16 08:10:01,542:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17351.9', self.close='17346.5'
2022-12-16 08:10:01,584:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221216   072000    072959  1671146999  17328.6  17335.2  0.000375
621  20221216   073000    073959  1671147599  17335.3  17295.7 -0.002279
622  20221216   074000    074959  1671148199  17295.6  17365.1  0.004013
623  20221216   075000    075959  1671148799    17365  17351.8 -0.000766
624  20221216   080000    080959  1671149399  17351.9  17346.5 -0.000305
2022-12-16 08:10:01,584:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221216   074000    074959  1671148199  17295.6  17365.1
2022-12-16 07:50:00,579:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2984 

self.closeSec=1671148799, self.tradeDate='20221216', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17365', self.close='17351.8'
2022-12-16 08:00:01,287:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671148799, self.tradeDate='20221216', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17365', self.close='17351.8'
2022-12-16 08:00:01,313:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221216   071000    071959  1671146399  17356.2  17328.7
17468  20221216   072000    072959  1671146999  17328.6  17335.2
17469  20221216   073000    073959  1671147599  17335.3  17295.7
17470  20221216   074000    074959  1671148199  17295.6  17365.1
17471  20221216   075000    075959  1671148799    17365  17351.8
2022-12-16 08:00:01,313:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2985 

self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17351.9', self.close='17346.5'
2022-12-16 08:10:01,566:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17351.9', self.close='17346.5'
2022-12-16 08:10:01,605:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221216   072000    072959  1671146999  17328.6  17335.2
17469  20221216   073000    073959  1671147599  17335.3  17295.7
17470  20221216   074000    074959  1671148199  17295.6  17365.1
17471  20221216   075000    075959  1671148799    17365  17351.8
17472  20221216   080000    080959  1671149399  17351.9  17346.5
2022-12-16 08:10:01,605:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221216   074000    074959  1671148199  17295.6  17365.1
2022-12-16 07:50:00,595:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2984 

self.closeSec=1671148799, self.tradeDate='20221216', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17365', self.close='17351.8'
2022-12-16 08:00:01,278:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671148799, self.tradeDate='20221216', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17365', self.close='17351.8'
2022-12-16 08:00:01,310:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221216   071000    071959  1671146399  17356.2  17328.7
12140  20221216   072000    072959  1671146999  17328.6  17335.2
12141  20221216   073000    073959  1671147599  17335.3  17295.7
12142  20221216   074000    074959  1671148199  17295.6  17365.1
12143  20221216   075000    075959  1671148799    17365  17351.8
2022-12-16 08:00:01,310:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2985 

self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17351.9', self.close='17346.5'
127.0.0.1 - - [16/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-16 08:10:01,515:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17351.9', self.close='17346.5'
2022-12-16 08:10:01,599:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221216   072000    072959  1671146999  17328.6  17335.2
12141  20221216   073000    073959  1671147599  17335.3  17295.7
12142  20221216   074000    074959  1671148199  17295.6  17365.1
12143  20221216   075000    075959  1671148799    17365  17351.8
12144  20221216   080000    080959  1671149399  17351.9  17346.5
2022-12-16 08:10:01,599:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1400
self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17371.0, self.close=17346.5, self.high=17371.1, self.low=17344.1, self.vol=970.005, self.amt=16833049.1939 
127.0.0.1 - - [16/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-16 08:10:01,548:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221216   074500    074959  ...    0.231271   0.317100       0
5854  20221216   075000    075459  ...    0.231030   0.317099       0
5855  20221216   075500    075959  ...    0.230787   0.317098       0
5856  20221216   080000    080459  ...    0.230544   0.317096       0
5857  20221216   080500    080959  ...    0.230301   0.317093       0

[5 rows x 18 columns]
2022-12-16 08:10:01,548:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671149399, self.tradeDate='20221216', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17371.0, self.close=17346.5, self.high=17371.1, self.low=17344.1, self.vol=970.005, self.amt=16833049.1939, ukdf['pct'].iloc[-1]=-0.001497 , ukdf['amount'].iloc[-1]=16833049.1939, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.23030111151747057, signal=0, value_std=0.3170934695229891 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1401
self.closeSec=1671149699, self.tradeDate='20221216', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17346.5, self.close=17367.9, self.high=17384.0, self.low=17346.2, self.vol=1291.726, self.amt=22435493.7215 
2022-12-16 08:15:00,819:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221216   075000    075459  ...    0.231030   0.317099       0
5855  20221216   075500    075959  ...    0.230787   0.317098       0
5856  20221216   080000    080459  ...    0.230544   0.317096       0
5857  20221216   080500    080959  ...    0.230301   0.317093       0
5858  20221216   081000    081459  ...    0.230057   0.317090       0

[5 rows x 18 columns]
2022-12-16 08:15:00,820:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671149699, self.tradeDate='20221216', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17346.5, self.close=17367.9, self.high=17384.0, self.low=17346.2, self.vol=1291.726, self.amt=22435493.7215, ukdf['pct'].iloc[-1]=0.001234 , ukdf['amount'].iloc[-1]=22435493.7215, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.23005670562591893, signal=0, value_std=0.31709003900531824 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221215   200000    235959  1671119999  ...    719  1.039420  1.214469     1.0
720  20221216   000000    035959  1671134399  ...    720  1.017189  1.119037     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-17168.9868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17435', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [16/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=124
self.closeSec=1671148799, self.tradeDate='20221216', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17435.0, self.close=17353.0, self.high=17449.7, self.low=17258.0, self.vol=56639.741, self.amt=983026464.4828 
2022-12-16 08:00:01,153:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671148799, self.tradeDate='20221216', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17435.0, self.close=17353.0, self.high=17449.7, self.low=17258.0, self.vol=56639.741, self.amt=983026464.4828 
2022-12-16 08:00:01,216:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20221215   120000    155959  ...   27803.765  4.924763e+08 -0.002195
718  20221215   160000    195959  ...   52699.528  9.310796e+08  0.001476
719  20221215   200000    235959  ...  146628.881  2.567878e+09 -0.016266
720  20221216   000000    035959  ...   78980.398  1.373762e+09  0.000637
721  20221216   040000    075959  ...   56639.741  9.830265e+08 -0.004709

[5 rows x 11 columns]
2022-12-16 08:00:02,444:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221215   120000    155959  1671091199  ...    717  1.103680  1.479993     1.0
718  20221215   160000    195959  1671105599  ...    718  1.062907  1.317741     1.0
719  20221215   200000    235959  1671119999  ...    719  1.039420  1.214469     1.0
720  20221216   000000    035959  1671134399  ...    720  1.017189  1.119037     1.0
721  20221216   040000    075959  1671148799  ...    721  1.007399  1.067021     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-21614.862', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17351.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


