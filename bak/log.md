# 20221226 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [26/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8186
self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16773.1, self.close=16784.4, self.high=16784.4, self.low=16763.7, self.vol=1589.418, self.amt=26658778.7033 
2022-12-26 00:10:01,486:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221225   234500    234959  ...         0.0        0.0       0
5758  20221225   235000    235459  ...         0.0        0.0       0
5759  20221225   235500    235959  ...         0.0        0.0       0
5760  20221226   000000    000459  ...         0.0        0.0       0
5761  20221226   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 00:10:01,486:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16773.1, self.close=16784.4, self.high=16784.4, self.low=16763.7, self.vol=1589.418, self.amt=26658778.7033, ukdf['pct'].iloc[-1]=0.000626 , ukdf['amount'].iloc[-1]=26658778.7033, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15362.9328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16784.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8187
self.closeSec=1671984899, self.tradeDate='20221226', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16784.4, self.close=16794.6, self.high=16797.0, self.low=16782.3, self.vol=807.768, self.amt=13562625.6622 
127.0.0.1 - - [26/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-26 00:15:00,594:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221225   235000    235459  ...         0.0        0.0       0
5759  20221225   235500    235959  ...         0.0        0.0       0
5760  20221226   000000    000459  ...         0.0        0.0       0
5761  20221226   000500    000959  ...         0.0        0.0       0
5762  20221226   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 00:15:00,594:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671984899, self.tradeDate='20221226', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16784.4, self.close=16794.6, self.high=16797.0, self.low=16782.3, self.vol=807.768, self.amt=13562625.6622, ukdf['pct'].iloc[-1]=0.000608 , ukdf['amount'].iloc[-1]=13562625.6622, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15988.79613613008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16795.00054733', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=214, self.factor=0.5446749783742577, self.count=8752 

self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16773.1, self.close=16784.4, self.high=16784.4, self.low=16763.7 
2022-12-26 00:10:01,429:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16773.1, self.close=16784.4, self.high=16784.4, self.low=16763.7   
2022-12-26 00:10:01,466:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221225   234500    234959  1671983399  ...  16788.6 -0.000006   1725    3
1438  20221225   235000    235459  1671983699  ...  16784.6 -0.000042   1726    4
1439  20221225   235500    235959  1671983999  ...  16784.1 -0.000232   1727    5
1440  20221226   000000    000459  1671984299  ...  16771.5 -0.000608   1440    0
1441  20221226   000500    000959  1671984599  ...  16763.7  0.000626   1441    1

[5 rows x 11 columns]
2022-12-26 00:10:01,466:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [26/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=214, self.factor=0.5446749783742577, self.count=8753 

self.closeSec=1671984899, self.tradeDate='20221226', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16784.4, self.close=16794.6, self.high=16797.0, self.low=16782.3 
2022-12-26 00:15:00,535:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671984899, self.tradeDate='20221226', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16784.4, self.close=16794.6, self.high=16797.0, self.low=16782.3   
2022-12-26 00:15:00,573:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221225   235000    235459  1671983699  ...  16784.6 -0.000042   1726    4
1439  20221225   235500    235959  1671983999  ...  16784.1 -0.000232   1727    5
1440  20221226   000000    000459  1671984299  ...  16771.5 -0.000608   1440    0
1441  20221226   000500    000959  1671984599  ...  16763.7  0.000626   1441    1
1442  20221226   001000    001459  1671984899  ...  16782.3  0.000608   1442    2

[5 rows x 11 columns]
2022-12-26 00:15:00,574:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-26 00:00:17,379:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221225    212959  16810.4  ...  49.583333  0.488839  0.577848
5803  20221225    215959  16809.3  ...  49.583333  0.482377  0.590970
5804  20221225    222959  16804.3  ...  49.166667  0.478504  0.606000
5805  20221225    225959  16801.2  ...  49.166667  0.508567  0.580734
5806  20221225    232959  16823.5  ...  48.750000  0.503019  0.555619

[5 rows x 33 columns]
0.5202205882352942
acc is : 0.5202205882352942
2022-12-26 00:00:17,486:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494372  0.505628       0  ...  1.071489   1.0    0.0  0.943680
540     1  0.493388  0.506612       0  ...  1.071298   1.0    0.0  0.943511
541     1  0.493288  0.506712       1  ...  1.072726   1.0    0.0  0.944769
542     0  0.501590  0.498410       0  ...  1.072458   1.0    0.0  0.944533
543     1  0.495620  0.504380       0  ...  1.070207   1.0    0.0  0.942551

[5 rows x 10 columns]
2022-12-26 00:00:17,501:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494579  0.505421       0  ...  1.071489   1.0    0.0  0.945145
46     1  0.493305  0.506695       0  ...  1.071298   1.0    0.0  0.944572
47     1  0.493290  0.506710       1  ...  1.072726   1.0    0.0  0.945832
48     0  0.501337  0.498663       0  ...  1.072458   1.0    0.0  0.944438
49     1  0.495620  0.504380       0  ...  1.070207   1.0    0.0  0.942551

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '3544.52771832768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16784.84574206', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-26 00:00:01,163:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221225   231000    231959  1671981599  16839.4  16826.1 -0.000790
572  20221225   232000    232959  1671982199  16826.2  16819.5 -0.000392
573  20221225   233000    233959  1671982799  16819.5  16800.5 -0.001130
574  20221225   234000    234959  1671983399  16800.5  16788.8 -0.000696
575  20221225   235000    235959  1671983999  16788.6  16784.1 -0.000280
2022-12-26 00:00:01,163:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.381', 'enterprice': '16823.6', 'countrevence': '0', 'unrealprofit': '-2072.99648059317', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16786.16845343', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-26 00:00:01,915:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-26 00:00:01,915:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.381, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41418F1671984001911I0L59'}
2022-12-26 00:00:01,950:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12260000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221225, closeTime:235959, close:16784.1, total:930776.0838083999, mom:0.0008077655453515575, thd:0.0, side:sell 
2022-12-26 00:00:02,316:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41418F1671984001911I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671984002040010, 'quantity': '55.381', 'price': '16784.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671984001318, 'updatetime': 1671984002040, 'tradetype': 'usdt', 'selfid': 41418, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671984002040, 'clientorderid': '41418F1671984001911I0L59', 'price': '16784.1', 'quantity': '55.381', 'commission': '929.5202421', 'commissionasset': 'USDT', 'tradetime': 1671984002040, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671984002040}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-26 00:00:02,485:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41418F1671984001911I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671984002040010, 'quantity': '55.381', 'price': '16784.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671984001318, 'updatetime': 1671984002040, 'tradetype': 'usdt', 'selfid': 41418, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671984002040, 'clientorderid': '41418F1671984001911I0L59', 'price': '16784.1', 'quantity': '55.381', 'commission': '929.5202421', 'commissionasset': 'USDT', 'tradetime': 1671984002040, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671984002040}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4376 

self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16784.2', self.close='16784.4'
2022-12-26 00:10:01,513:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16784.2', self.close='16784.4'
2022-12-26 00:10:01,528:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221225   232000    232959  1671982199  16826.2  16819.5 -0.000392
573  20221225   233000    233959  1671982799  16819.5  16800.5 -0.001130
574  20221225   234000    234959  1671983399  16800.5  16788.8 -0.000696
575  20221225   235000    235959  1671983999  16788.6  16784.1 -0.000280
576  20221226   000000    000959  1671984599  16784.2  16784.4  0.000018
2022-12-26 00:10:01,528:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-26 00:00:01,169:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221225   231000    231959  1671981599  16839.4  16826.1
17420  20221225   232000    232959  1671982199  16826.2  16819.5
17421  20221225   233000    233959  1671982799  16819.5  16800.5
17422  20221225   234000    234959  1671983399  16800.5  16788.8
17423  20221225   235000    235959  1671983999  16788.6  16784.1
2022-12-26 00:00:01,169:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '56.21', 'enterprice': '16824.1', 'countrevence': '0', 'unrealprofit': '-2132.1322326997', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16786.16845343', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-26 00:00:02,468:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-26 00:00:02,468:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 56.21, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41419F1671984002171I0L57'}
2022-12-26 00:00:02,488:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12260000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221225, closeTime:235959, close:16784.1, total:944736.9783389999, pct_pre:0.0005173859520795077, thd:0.18727748984957865, side:sell 
2022-12-26 00:00:02,609:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41419F1671984002171I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671984002561692, 'quantity': '56.21', 'price': '16784.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671984001443, 'updatetime': 1671984002561, 'tradetype': 'usdt', 'selfid': 41419, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671984002561, 'clientorderid': '41419F1671984002171I0L57', 'price': '16784.1', 'quantity': '56.21', 'commission': '943.434261', 'commissionasset': 'USDT', 'tradetime': 1671984002561, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671984002561}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-26 00:00:02,793:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41419F1671984002171I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671984002561692, 'quantity': '56.21', 'price': '16784.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671984001443, 'updatetime': 1671984002561, 'tradetype': 'usdt', 'selfid': 41419, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671984002561, 'clientorderid': '41419F1671984002171I0L57', 'price': '16784.1', 'quantity': '56.21', 'commission': '943.434261', 'commissionasset': 'USDT', 'tradetime': 1671984002561, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671984002561}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4377 

self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16784.2', self.close='16784.4'
2022-12-26 00:10:01,540:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16784.2', self.close='16784.4'
2022-12-26 00:10:01,554:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221225   232000    232959  1671982199  16826.2  16819.5
17421  20221225   233000    233959  1671982799  16819.5  16800.5
17422  20221225   234000    234959  1671983399  16800.5  16788.8
17423  20221225   235000    235959  1671983999  16788.6  16784.1
17424  20221226   000000    000959  1671984599  16784.2  16784.4
2022-12-26 00:10:01,554:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-26 00:00:01,167:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221225   231000    231959  1671981599  16839.4  16826.1
12236  20221225   232000    232959  1671982199  16826.2  16819.5
12237  20221225   233000    233959  1671982799  16819.5  16800.5
12238  20221225   234000    234959  1671983399  16800.5  16788.8
12239  20221225   235000    235959  1671983999  16788.6  16784.1
2022-12-26 00:00:01,167:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.065', 'enterprice': '16819.2', 'countrevence': '0', 'unrealprofit': '2479.51304327705', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16786.16845343', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-26 00:00:01,898:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-26 00:00:01,899:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.065, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41417F1671984001896I0L2'}
2022-12-26 00:00:01,936:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12260000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221225, closeTime:235959, close:16784.1, total:1261270.7147519998, corrDate:20221121, corrVal:0.6247552389676212, side:buy 
2022-12-26 00:00:02,075:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41417F1671984001896I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671984002016902, 'quantity': '75.065', 'price': '16784.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671984001390, 'updatetime': 1671984002016, 'tradetype': 'usdt', 'selfid': 41417, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671984002016, 'clientorderid': '41417F1671984001896I0L2', 'price': '16784.2', 'quantity': '75.065', 'commission': '1259.905973', 'commissionasset': 'USDT', 'tradetime': 1671984002016, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671984002016}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-26 00:00:02,294:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41417F1671984001896I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671984002016902, 'quantity': '75.065', 'price': '16784.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671984001390, 'updatetime': 1671984002016, 'tradetype': 'usdt', 'selfid': 41417, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671984002016, 'clientorderid': '41417F1671984001896I0L2', 'price': '16784.2', 'quantity': '75.065', 'commission': '1259.905973', 'commissionasset': 'USDT', 'tradetime': 1671984002016, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671984002016}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4377 

self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16784.2', self.close='16784.4'
2022-12-26 00:10:01,536:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16784.2', self.close='16784.4'
2022-12-26 00:10:01,550:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221225   232000    232959  1671982199  16826.2  16819.5
12237  20221225   233000    233959  1671982799  16819.5  16800.5
12238  20221225   234000    234959  1671983399  16800.5  16788.8
12239  20221225   235000    235959  1671983999  16788.6  16784.1
12240  20221226   000000    000959  1671984599  16784.2  16784.4
2022-12-26 00:10:01,550:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [26/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4184
self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16773.1, self.close=16784.4, self.high=16784.4, self.low=16763.7, self.vol=1589.418, self.amt=26658778.7033 
2022-12-26 00:10:01,496:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221225   234500    234959  ...         0.0        0.0       0
5758  20221225   235000    235459  ...         0.0        0.0       0
5759  20221225   235500    235959  ...         0.0        0.0       0
5760  20221226   000000    000459  ...         0.0        0.0       0
5761  20221226   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 00:10:01,496:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671984599, self.tradeDate='20221226', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16773.1, self.close=16784.4, self.high=16784.4, self.low=16763.7, self.vol=1589.418, self.amt=26658778.7033, ukdf['pct'].iloc[-1]=0.000626 , ukdf['amount'].iloc[-1]=26658778.7033, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4185
self.closeSec=1671984899, self.tradeDate='20221226', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16784.4, self.close=16794.6, self.high=16797.0, self.low=16782.3, self.vol=807.768, self.amt=13562625.6622 
2022-12-26 00:15:00,589:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221225   235000    235459  ...         0.0        0.0       0
5759  20221225   235500    235959  ...         0.0        0.0       0
5760  20221226   000000    000459  ...         0.0        0.0       0
5761  20221226   000500    000959  ...         0.0        0.0       0
5762  20221226   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 00:15:00,591:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671984899, self.tradeDate='20221226', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16784.4, self.close=16794.6, self.high=16797.0, self.low=16782.3, self.vol=807.768, self.amt=13562625.6622, ukdf['pct'].iloc[-1]=0.000608 , ukdf['amount'].iloc[-1]=13562625.6622, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221225   120000    155959  1671955199  ...    723  0.007733 -1.202113    -1.0
724  20221225   160000    195959  1671969599  ...    724  0.006121 -1.182515    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-4919.26023292264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16815.26930662', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Dec/2022 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=182
self.closeSec=1671983999, self.tradeDate='20221225', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16815.0, self.close=16784.1, self.high=16850.0, self.low=16700.0, self.vol=58570.137, self.amt=983461365.538 
2022-12-26 00:00:00,987:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671983999, self.tradeDate='20221225', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16815.0, self.close=16784.1, self.high=16850.0, self.low=16700.0, self.vol=58570.137, self.amt=983461365.538 
2022-12-26 00:00:01,009:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221225   040000    075959  ...  13189.410  2.219239e+08 -0.000339
722  20221225   080000    115959  ...   8339.966  1.403594e+08 -0.000291
723  20221225   120000    155959  ...  13041.653  2.192675e+08 -0.000428
724  20221225   160000    195959  ...  10124.306  1.702797e+08 -0.000113
725  20221225   200000    235959  ...  58570.137  9.834614e+08 -0.001832

[5 rows x 11 columns]
2022-12-26 00:00:02,679:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221225   040000    075959  1671926399  ...    721  0.016321 -1.231471    -1.0
722  20221225   080000    115959  1671940799  ...    722  0.009877 -1.221246    -1.0
723  20221225   120000    155959  1671955199  ...    723  0.007733 -1.202113    -1.0
724  20221225   160000    195959  1671969599  ...    724  0.006121 -1.182515    -1.0
725  20221225   200000    235959  1671983999  ...    725  0.004976 -1.162320    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-3355.84622213896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16785.97653118', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


