# 20221212 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4250
self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17018.1, self.close=17025.3, self.high=17028.4, self.low=17012.9, self.vol=2560.211, self.amt=43579264.4349 
127.0.0.1 - - [12/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 08:10:01,457:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221212   074500    074959  ...         0.0        0.0       0
5854  20221212   075000    075459  ...         0.0        0.0       0
5855  20221212   075500    075959  ...         0.0        0.0       0
5856  20221212   080000    080459  ...         0.0        0.0       0
5857  20221212   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-12 08:10:01,458:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17018.1, self.close=17025.3, self.high=17028.4, self.low=17012.9, self.vol=2560.211, self.amt=43579264.4349, ukdf['pct'].iloc[-1]=0.000423 , ukdf['amount'].iloc[-1]=43579264.4349, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-29841.2784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17025.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4251
self.closeSec=1670804099, self.tradeDate='20221212', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17025.2, self.close=16979.6, self.high=17027.3, self.low=16956.0, self.vol=6236.308, self.amt=105948508.64753 
2022-12-12 08:15:00,615:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221212   075000    075459  ...         0.0        0.0       0
5855  20221212   075500    075959  ...         0.0        0.0       0
5856  20221212   080000    080459  ...         0.0        0.0       0
5857  20221212   080500    080959  ...         0.0        0.0       0
5858  20221212   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-12 08:15:00,616:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670804099, self.tradeDate='20221212', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17025.2, self.close=16979.6, self.high=17027.3, self.low=16956.0, self.vol=6236.308, self.amt=105948508.64753, ukdf['pct'].iloc[-1]=-0.002684 , ukdf['amount'].iloc[-1]=105948508.64753, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-27097.2528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16979.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=111, self.factor=0.5565535495216826, self.count=4816 

self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17018.1, self.close=17025.3, self.high=17028.4, self.low=17012.9 
2022-12-12 08:10:01,404:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17018.1, self.close=17025.3, self.high=17028.4, self.low=17012.9   
2022-12-12 08:10:01,437:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221212   074500    074959  1670802599  ...  17069.1  0.000914   1533    3
1534  20221212   075000    075459  1670802899  ...  17084.1  0.000416   1534    4
1535  20221212   075500    075959  1670803199  ...  17076.7 -0.000889   1535    5
1536  20221212   080000    080459  1670803499  ...  16988.7 -0.003484   1536    0
1537  20221212   080500    080959  1670803799  ...  17012.9  0.000423   1537    1

[5 rows x 11 columns]
2022-12-12 08:10:01,437:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=111, self.factor=0.5565535495216826, self.count=4817 

self.closeSec=1670804099, self.tradeDate='20221212', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17025.2, self.close=16979.6, self.high=17027.3, self.low=16956.0 
2022-12-12 08:15:00,550:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670804099, self.tradeDate='20221212', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17025.2, self.close=16979.6, self.high=17027.3, self.low=16956.0   
127.0.0.1 - - [12/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-12 08:15:00,580:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221212   075000    075459  1670802899  ...  17084.1  0.000416   1534    4
1535  20221212   075500    075959  1670803199  ...  17076.7 -0.000889   1535    5
1536  20221212   080000    080459  1670803499  ...  16988.7 -0.003484   1536    0
1537  20221212   080500    080959  1670803799  ...  17012.9  0.000423   1537    1
1538  20221212   081000    081459  1670804099  ...  16956.0 -0.002684   1538    2

[5 rows x 11 columns]
2022-12-12 08:15:00,580:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-12 08:00:18,715:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221212    052959  17093.9  ...  54.583333  0.485098  0.476046
5771  20221212    055959  17122.0  ...  54.166667  0.472997  0.502239
5772  20221212    062959  17105.1  ...  54.583333  0.480128  0.523424
5773  20221212    065959  17114.1  ...  54.583333  0.464176  0.551317
5774  20221212    072959  17091.8  ...  54.583333  0.465713  0.570270

[5 rows x 33 columns]
0.5656192236598891
acc is : 0.5656192236598891
2022-12-12 08:00:18,817:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.490890  0.509110       0  ...  0.960004   1.0    0.0  1.020737
537     1  0.478331  0.521669       1  ...  0.960509   1.0    0.0  1.021274
538     1  0.489221  0.510779       0  ...  0.959252   1.0    0.0  1.019937
539     1  0.487274  0.512726       1  ...  0.959358   1.0    0.0  1.020050
540     1  0.492993  0.507007       0  ...  0.958455   1.0    0.0  1.019090

[5 rows x 10 columns]
2022-12-12 08:00:18,840:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490503  0.509497       0  ...  0.960004   1.0    0.0  1.014640
46     1  0.478682  0.521318       1  ...  0.960509   1.0    0.0  1.014530
47     1  0.489989  0.510011       0  ...  0.959252   1.0    0.0  1.014152
48     1  0.488408  0.511592       1  ...  0.959358   1.0    0.0  1.020050
49     1  0.492993  0.507007       0  ...  0.958455   1.0    0.0  1.019090

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-5236.74631067981', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17074.22141071', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221212   074000    074959  1670802599  17076.3  17085.6  0.000550
2022-12-12 07:50:00,580:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2407 

self.closeSec=1670803199, self.tradeDate='20221212', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17085.6', self.close='17077.6'
2022-12-12 08:00:01,276:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670803199, self.tradeDate='20221212', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17085.6', self.close='17077.6'
2022-12-12 08:00:01,317:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221212   071000    071959  1670800799  17116.1  17089.4 -0.001560
620  20221212   072000    072959  1670801399  17089.4  17093.7  0.000252
621  20221212   073000    073959  1670801999  17093.6  17076.2 -0.001024
622  20221212   074000    074959  1670802599  17076.3  17085.6  0.000550
623  20221212   075000    075959  1670803199  17085.6  17077.6 -0.000468
2022-12-12 08:00:01,317:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2408 

self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17077.3', self.close='17025.2'
2022-12-12 08:10:01,519:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17077.3', self.close='17025.2'
127.0.0.1 - - [12/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 08:10:01,554:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221212   072000    072959  1670801399  17089.4  17093.7  0.000252
621  20221212   073000    073959  1670801999  17093.6  17076.2 -0.001024
622  20221212   074000    074959  1670802599  17076.3  17085.6  0.000550
623  20221212   075000    075959  1670803199  17085.6  17077.6 -0.000468
624  20221212   080000    080959  1670803799  17077.3  17025.2 -0.003068
2022-12-12 08:10:01,554:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221212   074000    074959  1670802599  17076.3  17085.6
2022-12-12 07:50:00,560:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2408 

self.closeSec=1670803199, self.tradeDate='20221212', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17085.6', self.close='17077.6'
2022-12-12 08:00:01,261:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670803199, self.tradeDate='20221212', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17085.6', self.close='17077.6'
2022-12-12 08:00:01,303:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221212   071000    071959  1670800799  17116.1  17089.4
17468  20221212   072000    072959  1670801399  17089.4  17093.7
17469  20221212   073000    073959  1670801999  17093.6  17076.2
17470  20221212   074000    074959  1670802599  17076.3  17085.6
17471  20221212   075000    075959  1670803199  17085.6  17077.6
2022-12-12 08:00:01,303:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2409 

self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17077.3', self.close='17025.2'
127.0.0.1 - - [12/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 08:10:01,527:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17077.3', self.close='17025.2'
2022-12-12 08:10:01,536:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221212   072000    072959  1670801399  17089.4  17093.7
17469  20221212   073000    073959  1670801999  17093.6  17076.2
17470  20221212   074000    074959  1670802599  17076.3  17085.6
17471  20221212   075000    075959  1670803199  17085.6  17077.6
17472  20221212   080000    080959  1670803799  17077.3  17025.2
2022-12-12 08:10:01,537:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221212   074000    074959  1670802599  17076.3  17085.6
2022-12-12 07:50:00,528:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2408 

self.closeSec=1670803199, self.tradeDate='20221212', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17085.6', self.close='17077.6'
127.0.0.1 - - [12/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-12 08:00:01,262:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670803199, self.tradeDate='20221212', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17085.6', self.close='17077.6'
2022-12-12 08:00:01,308:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221212   071000    071959  1670800799  17116.1  17089.4
12140  20221212   072000    072959  1670801399  17089.4  17093.7
12141  20221212   073000    073959  1670801999  17093.6  17076.2
12142  20221212   074000    074959  1670802599  17076.3  17085.6
12143  20221212   075000    075959  1670803199  17085.6  17077.6
2022-12-12 08:00:01,308:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [12/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2409 

self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17077.3', self.close='17025.2'
2022-12-12 08:10:01,540:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17077.3', self.close='17025.2'
2022-12-12 08:10:01,568:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221212   072000    072959  1670801399  17089.4  17093.7
12141  20221212   073000    073959  1670801999  17093.6  17076.2
12142  20221212   074000    074959  1670802599  17076.3  17085.6
12143  20221212   075000    075959  1670803199  17085.6  17077.6
12144  20221212   080000    080959  1670803799  17077.3  17025.2
2022-12-12 08:10:01,568:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=248
self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17018.1, self.close=17025.3, self.high=17028.4, self.low=17012.9, self.vol=2560.211, self.amt=43579264.4349 
127.0.0.1 - - [12/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 08:10:01,456:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221212   074500    074959  ...    0.553662   0.169897       0
5854  20221212   075000    075459  ...    0.553457   0.170327       0
5855  20221212   075500    075959  ...    0.553254   0.170754       0
5856  20221212   080000    080459  ...    0.553050   0.171180       0
5857  20221212   080500    080959  ...    0.552846   0.171605       0

[5 rows x 18 columns]
2022-12-12 08:10:01,456:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670803799, self.tradeDate='20221212', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17018.1, self.close=17025.3, self.high=17028.4, self.low=17012.9, self.vol=2560.211, self.amt=43579264.4349, ukdf['pct'].iloc[-1]=0.000423 , ukdf['amount'].iloc[-1]=43579264.4349, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.5528462349965467, signal=0, value_std=0.17160515269019877 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=249
self.closeSec=1670804099, self.tradeDate='20221212', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17025.2, self.close=16979.6, self.high=17027.3, self.low=16956.0, self.vol=6236.308, self.amt=105948508.64753 
127.0.0.1 - - [12/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-12 08:15:00,580:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221212   075000    075459  ...    0.553457   0.170327       0
5855  20221212   075500    075959  ...    0.553254   0.170754       0
5856  20221212   080000    080459  ...    0.553050   0.171180       0
5857  20221212   080500    080959  ...    0.552846   0.171605       0
5858  20221212   081000    081459  ...    0.552643   0.172029       0

[5 rows x 18 columns]
2022-12-12 08:15:00,580:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670804099, self.tradeDate='20221212', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17025.2, self.close=16979.6, self.high=17027.3, self.low=16956.0, self.vol=6236.308, self.amt=105948508.64753, ukdf['pct'].iloc[-1]=-0.002684 , ukdf['amount'].iloc[-1]=105948508.64753, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.552642532875715, signal=0, value_std=0.17202862928203985 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221211   200000    235959  1670774399  ...    719  0.578351  0.236847     NaN
720  20221212   000000    035959  1670788799  ...    720  0.571626  0.203078     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-7686.26340996038', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17170.38431971', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [12/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=100
self.closeSec=1670803199, self.tradeDate='20221212', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17169.6, self.close=17077.6, self.high=17169.7, self.low=17060.0, self.vol=52598.599, self.amt=899699013.1034 
2022-12-12 08:00:01,167:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670803199, self.tradeDate='20221212', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17169.6, self.close=17077.6, self.high=17169.7, self.low=17060.0, self.vol=52598.599, self.amt=899699013.1034 
2022-12-12 08:00:01,193:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221211   120000    155959  ...  18948.471  3.252470e+08  0.001499
718  20221211   160000    195959  ...  16708.791  2.866225e+08 -0.000734
719  20221211   200000    235959  ...  19880.891  3.408058e+08 -0.000892
720  20221212   000000    035959  ...  46356.060  7.967647e+08  0.001400
721  20221212   040000    075959  ...  52598.599  8.996990e+08 -0.005353

[5 rows x 11 columns]
2022-12-12 08:00:02,817:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221211   120000    155959  1670745599  ...    717  0.516006  0.036525     NaN
718  20221211   160000    195959  1670759999  ...    718  0.597746  0.319120     NaN
719  20221211   200000    235959  1670774399  ...    719  0.578351  0.236847     NaN
720  20221212   000000    035959  1670788799  ...    720  0.571626  0.203078     NaN
721  20221212   040000    075959  1670803199  ...    721  0.507540 -0.038979     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-13137.1902', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17077.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


