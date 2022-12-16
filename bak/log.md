# 20221217 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5594
self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16951.9, self.close=16858.1, self.high=16954.4, self.low=16767.6, self.vol=15365.65, self.amt=258946139.1164 
2022-12-17 00:10:01,511:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221216   234500    234959  ...         0.0        0.0       0
5758  20221216   235000    235459  ...         0.0        0.0       0
5759  20221216   235500    235959  ...         0.0        0.0       0
5760  20221217   000000    000459  ...         0.0        0.0       0
5761  20221217   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-17 00:10:01,512:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16951.9, self.close=16858.1, self.high=16954.4, self.low=16767.6, self.vol=15365.65, self.amt=258946139.1164, ukdf['pct'].iloc[-1]=-0.005539 , ukdf['amount'].iloc[-1]=258946139.1164, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-19801.39314107952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16858.35798227', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5595
self.closeSec=1671207299, self.tradeDate='20221217', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16858.2, self.close=16909.9, self.high=16920.0, self.low=16847.1, self.vol=7548.379, self.amt=127382459.7801 
2022-12-17 00:15:00,588:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221216   235000    235459  ...         0.0        0.0       0
5759  20221216   235500    235959  ...         0.0        0.0       0
5760  20221217   000000    000459  ...         0.0        0.0       0
5761  20221217   000500    000959  ...         0.0        0.0       0
5762  20221217   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-17 00:15:00,588:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671207299, self.tradeDate='20221217', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16858.2, self.close=16909.9, self.high=16920.0, self.low=16847.1, self.vol=7548.379, self.amt=127382459.7801, ukdf['pct'].iloc[-1]=0.003073 , ukdf['amount'].iloc[-1]=127382459.7801, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-23281.2671966336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16916.1862536', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8026324330594174, self.count=6160 

self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16951.9, self.close=16858.1, self.high=16954.4, self.low=16767.6 
2022-12-17 00:10:01,438:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16951.9, self.close=16858.1, self.high=16954.4, self.low=16767.6   
2022-12-17 00:10:01,486:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221216   234500    234959  1671205799  ...  16948.0 -0.000006   1725    3
1438  20221216   235000    235459  1671206099  ...  16953.5 -0.000413   1726    4
1439  20221216   235500    235959  1671206399  ...  16951.5  0.000383   1727    5
1440  20221217   000000    000459  1671206699  ...  16938.6 -0.000578   1440    0
1441  20221217   000500    000959  1671206999  ...  16767.6 -0.005539   1441    1

[5 rows x 11 columns]
2022-12-17 00:10:01,486:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8026324330594174, self.count=6161 

self.closeSec=1671207299, self.tradeDate='20221217', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16858.2, self.close=16909.9, self.high=16920.0, self.low=16847.1 
2022-12-17 00:15:00,549:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671207299, self.tradeDate='20221217', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16858.2, self.close=16909.9, self.high=16920.0, self.low=16847.1   
2022-12-17 00:15:00,586:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221216   235000    235459  1671206099  ...  16953.5 -0.000413   1726    4
1439  20221216   235500    235959  1671206399  ...  16951.5  0.000383   1727    5
1440  20221217   000000    000459  1671206699  ...  16938.6 -0.000578   1440    0
1441  20221217   000500    000959  1671206999  ...  16767.6 -0.005539   1441    1
1442  20221217   001000    001459  1671207299  ...  16847.1  0.003073   1442    2

[5 rows x 11 columns]
2022-12-17 00:15:00,586:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-17 00:00:19,828:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221216    212959  17025.1  ...  50.000000  0.359626  0.779784
5803  20221216    215959  16985.1  ...  50.000000  0.349751  0.791347
5804  20221216    222959  16939.0  ...  50.416667  0.384752  0.788819
5805  20221216    225959  17028.8  ...  50.000000  0.381734  0.787828
5806  20221216    232959  17019.2  ...  50.000000  0.361605  0.796426

[5 rows x 33 columns]
0.5661764705882353
acc is : 0.5661764705882353
2022-12-17 00:00:19,949:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.490495  0.509505       0  ...  1.077382  -1.0    0.0  0.978991
540     1  0.480474  0.519526       1  ...  1.071416  -1.0    0.0  0.984413
541     0  0.521112  0.478888       0  ...  1.072265  -1.0    0.0  0.983632
542     1  0.498533  0.501467       0  ...  1.078181  -1.0    0.0  0.978205
543     1  0.468427  0.531573       1  ...  1.075856  -1.0    0.0  0.980315

[5 rows x 10 columns]
2022-12-17 00:00:19,973:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490685  0.509315       0  ...  1.077382  -1.0    0.0  0.979388
46     1  0.480542  0.519458       1  ...  1.071416  -1.0    0.0  0.984606
47     0  0.521118  0.478882       0  ...  1.072265  -1.0    0.0  0.983826
48     1  0.498292  0.501708       0  ...  1.078181  -1.0    0.0  0.977883
49     1  0.468427  0.531573       1  ...  1.075856  -1.0    0.0  0.980315

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '30494.34659430072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16961.21720257', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-17 00:00:01,269:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221216   231000    231959  1671203999  16985.2  16965.2 -0.001172
572  20221216   232000    232959  1671204599  16964.9  16924.2 -0.002417
573  20221216   233000    233959  1671205199  16923.2  16962.6  0.002269
574  20221216   234000    234959  1671205799  16962.6  16962.3 -0.000018
575  20221216   235000    235959  1671206399  16962.3  16961.8 -0.000029
2022-12-17 00:00:01,270:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.794', 'enterprice': '17404.3', 'countrevence': '0', 'unrealprofit': '23776.37804288708', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16962.31059518', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-17 00:00:02,363:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-17 00:00:02,364:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.794, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41372F1671206402140I0L59'}
2022-12-17 00:00:02,388:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12170000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221216, closeTime:235959, close:16961.8, total:935310.6672857999, mom:-0.00031502590958210064, thd:0.0, side:buy 
127.0.0.1 - - [17/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-17 00:00:02,778:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41372F1671206402140I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671206402751525, 'quantity': '53.794', 'price': '16961.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671206401554, 'updatetime': 1671206402751, 'tradetype': 'usdt', 'selfid': 41372, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671206402751, 'clientorderid': '41372F1671206402140I0L59', 'price': '16961.8', 'quantity': '53.794', 'commission': '912.4430692', 'commissionasset': 'USDT', 'tradetime': 1671206402751, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671206402751}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-17 00:00:03,031:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41372F1671206402140I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671206402751525, 'quantity': '53.794', 'price': '16961.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671206401554, 'updatetime': 1671206402751, 'tradetype': 'usdt', 'selfid': 41372, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671206402751, 'clientorderid': '41372F1671206402140I0L59', 'price': '16961.8', 'quantity': '53.794', 'commission': '912.4430692', 'commissionasset': 'USDT', 'tradetime': 1671206402751, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671206402751}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3080 

self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16961.8', self.close='16860.4'
2022-12-17 00:10:01,539:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16961.8', self.close='16860.4'
2022-12-17 00:10:01,576:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221216   232000    232959  1671204599  16964.9  16924.2 -0.002417
573  20221216   233000    233959  1671205199  16923.2  16962.6  0.002269
574  20221216   234000    234959  1671205799  16962.6  16962.3 -0.000018
575  20221216   235000    235959  1671206399  16962.3  16961.8 -0.000029
576  20221217   000000    000959  1671206999  16961.8  16860.4 -0.005978
2022-12-17 00:10:01,576:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-16 23:50:00,587:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3080 

self.closeSec=1671206399, self.tradeDate='20221216', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16962.3', self.close='16961.8'
2022-12-17 00:00:01,284:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671206399, self.tradeDate='20221216', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16962.3', self.close='16961.8'
2022-12-17 00:00:01,310:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221216   231000    231959  1671203999  16985.2  16965.2
17420  20221216   232000    232959  1671204599  16964.9  16924.2
17421  20221216   233000    233959  1671205199  16923.2  16962.6
17422  20221216   234000    234959  1671205799  16962.6  16962.3
17423  20221216   235000    235959  1671206399  16962.3  16961.8
2022-12-17 00:00:01,311:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-17 00:00:01,471:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12170000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221216, closeTime:235959, close:16961.8, total:947411.5003109, pct_pre:-0.022187132152393096, thd:0.35482636659065653, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3081 

self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16961.8', self.close='16860.4'
127.0.0.1 - - [17/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-17 00:10:01,542:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16961.8', self.close='16860.4'
2022-12-17 00:10:01,554:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221216   232000    232959  1671204599  16964.9  16924.2
17421  20221216   233000    233959  1671205199  16923.2  16962.6
17422  20221216   234000    234959  1671205799  16962.6  16962.3
17423  20221216   235000    235959  1671206399  16962.3  16961.8
17424  20221217   000000    000959  1671206999  16961.8  16860.4
2022-12-17 00:10:01,554:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-17 00:00:01,265:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221216   231000    231959  1671203999  16985.2  16965.2
12236  20221216   232000    232959  1671204599  16964.9  16924.2
12237  20221216   233000    233959  1671205199  16923.2  16962.6
12238  20221216   234000    234959  1671205799  16962.6  16962.3
12239  20221216   235000    235959  1671206399  16962.3  16961.8
2022-12-17 00:00:01,265:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '69.256', 'enterprice': '17334.7', 'countrevence': '0', 'unrealprofit': '25790.20062021392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16962.31059518', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-17 00:00:01,993:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-17 00:00:01,993:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 69.256, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41371F1671206401992I0L2'}
2022-12-17 00:00:02,028:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12170000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221216, closeTime:235959, close:16961.8, total:1199331.4512168001, corrDate:20221108, corrVal:0.8465203645442492, side:buy 
127.0.0.1 - - [17/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-17 00:00:02,163:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41371F1671206401992I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671206402114829, 'quantity': '69.256', 'price': '16961.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671206401546, 'updatetime': 1671206402114, 'tradetype': 'usdt', 'selfid': 41371, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671206402114, 'clientorderid': '41371F1671206401992I0L2', 'price': '16961.8', 'quantity': '69.256', 'commission': '1174.7064208', 'commissionasset': 'USDT', 'tradetime': 1671206402114, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671206402114}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-17 00:00:02,389:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41371F1671206401992I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671206402114829, 'quantity': '69.256', 'price': '16961.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671206401546, 'updatetime': 1671206402114, 'tradetype': 'usdt', 'selfid': 41371, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671206402114, 'clientorderid': '41371F1671206401992I0L2', 'price': '16961.8', 'quantity': '69.256', 'commission': '1174.7064208', 'commissionasset': 'USDT', 'tradetime': 1671206402114, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671206402114}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3081 

self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16961.8', self.close='16860.4'
2022-12-17 00:10:01,525:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16961.8', self.close='16860.4'
2022-12-17 00:10:01,565:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221216   232000    232959  1671204599  16964.9  16924.2
12237  20221216   233000    233959  1671205199  16923.2  16962.6
12238  20221216   234000    234959  1671205799  16962.6  16962.3
12239  20221216   235000    235959  1671206399  16962.3  16961.8
12240  20221217   000000    000959  1671206999  16961.8  16860.4
2022-12-17 00:10:01,571:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [17/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1592
self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16951.9, self.close=16858.1, self.high=16954.4, self.low=16767.6, self.vol=15365.65, self.amt=258946139.1164 
2022-12-17 00:10:01,506:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221216   234500    234959  ...    0.175963   0.301382       0
5758  20221216   235000    235459  ...    0.175708   0.301324       0
5759  20221216   235500    235959  ...    0.175455   0.301267       0
5760  20221217   000000    000459  ...    0.175201   0.301210       0
5761  20221217   000500    000959  ...    0.174948   0.301152       0

[5 rows x 18 columns]
2022-12-17 00:10:01,507:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671206999, self.tradeDate='20221217', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16951.9, self.close=16858.1, self.high=16954.4, self.low=16767.6, self.vol=15365.65, self.amt=258946139.1164, ukdf['pct'].iloc[-1]=-0.005539 , ukdf['amount'].iloc[-1]=258946139.1164, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.17494773132541558, signal=0, value_std=0.3011523724078081 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1593
self.closeSec=1671207299, self.tradeDate='20221217', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16858.2, self.close=16909.9, self.high=16920.0, self.low=16847.1, self.vol=7548.379, self.amt=127382459.7801 
127.0.0.1 - - [17/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-17 00:15:00,564:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221216   235000    235459  ...    0.175708   0.301324       0
5759  20221216   235500    235959  ...    0.175455   0.301267       0
5760  20221217   000000    000459  ...    0.175201   0.301210       0
5761  20221217   000500    000959  ...    0.174948   0.301152       0
5762  20221217   001000    001459  ...    0.174694   0.301095       0

[5 rows x 18 columns]
2022-12-17 00:15:00,565:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671207299, self.tradeDate='20221217', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16858.2, self.close=16909.9, self.high=16920.0, self.low=16847.1, self.vol=7548.379, self.amt=127382459.7801, ukdf['pct'].iloc[-1]=0.003073 , ukdf['amount'].iloc[-1]=127382459.7801, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.17469416149765707, signal=0, value_std=0.30109460064719934 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221216   120000    155959  1671177599  ...    723  0.991257  0.981591     1.0
724  20221216   160000    195959  1671191999  ...    724  0.725008  0.154497     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-39552.47079619008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17016.11602672', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=128
self.closeSec=1671206399, self.tradeDate='20221216', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=17018.7, self.close=16961.8, self.high=17076.9, self.low=16870.6, self.vol=107276.345, self.amt=1821694108.4361 
127.0.0.1 - - [17/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-17 00:00:01,100:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671206399, self.tradeDate='20221216', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=17018.7, self.close=16961.8, self.high=17076.9, self.low=16870.6, self.vol=107276.345, self.amt=1821694108.4361 
2022-12-17 00:00:01,134:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20221216   040000    075959  ...   56639.741  9.830265e+08 -0.004709
722  20221216   080000    115959  ...   35550.559  6.182726e+08  0.003798
723  20221216   120000    155959  ...   41640.940  7.263423e+08  0.004455
724  20221216   160000    195959  ...  188849.287  3.229967e+09 -0.027314
725  20221216   200000    235959  ...  107276.345  1.821694e+09 -0.003338

[5 rows x 11 columns]
2022-12-17 00:00:03,026:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221216   040000    075959  1671148799  ...    721  1.007399  1.067021     1.0
722  20221216   080000    115959  1671163199  ...    722  0.984127  0.976720     1.0
723  20221216   120000    155959  1671177599  ...    723  0.991257  0.981591     1.0
724  20221216   160000    195959  1671191999  ...    724  0.725008  0.154497     NaN
725  20221216   200000    235959  1671206399  ...    725  0.692185  0.053751     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-42422.47279986264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16962.40687926', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


