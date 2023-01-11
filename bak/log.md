# 20230112 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13082
self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17328.6, self.close=17337.8, self.high=17339.4, self.low=17320.3, self.vol=1366.911, self.amt=23684469.3499 
127.0.0.1 - - [12/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-12 00:10:01,531:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230111   234500    234959  ...         0.0        0.0       0
5758  20230111   235000    235459  ...         0.0        0.0       0
5759  20230111   235500    235959  ...         0.0        0.0       0
5760  20230112   000000    000459  ...         0.0        0.0       0
5761  20230112   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 00:10:01,531:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17328.6, self.close=17337.8, self.high=17339.4, self.low=17320.3, self.vol=1366.911, self.amt=23684469.3499, ukdf['pct'].iloc[-1]=0.000612 , ukdf['amount'].iloc[-1]=23684469.3499, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-48646.2784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17337.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13083
self.closeSec=1673453699, self.tradeDate='20230112', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17337.8, self.close=17344.1, self.high=17345.6, self.low=17333.8, self.vol=1128.653, self.amt=19571446.3907 
2023-01-12 00:15:00,628:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230111   235000    235459  ...         0.0        0.0       0
5759  20230111   235500    235959  ...         0.0        0.0       0
5760  20230112   000000    000459  ...         0.0        0.0       0
5761  20230112   000500    000959  ...         0.0        0.0       0
5762  20230112   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 00:15:00,631:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673453699, self.tradeDate='20230112', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17337.8, self.close=17344.1, self.high=17345.6, self.low=17333.8, self.vol=1128.653, self.amt=19571446.3907, ukdf['pct'].iloc[-1]=0.000363 , ukdf['amount'].iloc[-1]=19571446.3907, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-49031.4048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17344.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17328.6, self.close=17337.8, self.high=17339.4, self.low=17320.3 
2023-01-12 00:10:01,429:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17328.6, self.close=17337.8, self.high=17339.4, self.low=17320.3   
127.0.0.1 - - [12/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-12 00:10:01,475:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230111   234500    234959  1673452199  ...  17337.1  0.000432   1725    3
1438  20230111   235000    235459  1673452499  ...  17306.4 -0.001412   1726    4
1439  20230111   235500    235959  1673452799  ...  17311.0 -0.000190   1727    5
1440  20230112   000000    000459  1673453099  ...  17320.6  0.000110   1440    0
1441  20230112   000500    000959  1673453399  ...  17320.3  0.000612   1441    1

[5 rows x 11 columns]
2023-01-12 00:10:01,483:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=191, self.factor=0.37786684727796604, self.count=13649 

self.closeSec=1673453699, self.tradeDate='20230112', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17337.8, self.close=17344.1, self.high=17345.6, self.low=17333.8 
2023-01-12 00:15:00,532:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673453699, self.tradeDate='20230112', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17337.8, self.close=17344.1, self.high=17345.6, self.low=17333.8   
127.0.0.1 - - [12/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-12 00:15:00,593:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230111   235000    235459  1673452499  ...  17306.4 -0.001412   1726    4
1439  20230111   235500    235959  1673452799  ...  17311.0 -0.000190   1727    5
1440  20230112   000000    000459  1673453099  ...  17320.6  0.000110   1440    0
1441  20230112   000500    000959  1673453399  ...  17320.3  0.000612   1441    1
1442  20230112   001000    001459  1673453699  ...  17333.8  0.000363   1442    2

[5 rows x 11 columns]
2023-01-12 00:15:00,594:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-12 00:00:18,528:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230111    212959  17408.6  ...  55.000000  0.567100  0.291125
5803  20230111    215959  17413.9  ...  54.583333  0.560251  0.306455
5804  20230111    222959  17404.7  ...  54.583333  0.547642  0.339453
5805  20230111    225959  17387.9  ...  55.000000  0.558497  0.361585
5806  20230111    232959  17406.0  ...  54.583333  0.546728  0.389860

[5 rows x 33 columns]
0.5588235294117647
acc is : 0.5588235294117647
2023-01-12 00:00:18,633:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     1  0.498482  0.501518       0  ...  NaN   NaN -0.0016  1.050735
540     1  0.494103  0.505897       0  ...  NaN   NaN -0.0016  1.049709
541     1  0.490700  0.509300       1  ...  NaN   NaN -0.0016  1.050808
542     0  0.503502  0.496498       0  ...  NaN   NaN -0.0016  1.049842
543     1  0.493291  0.506709       0  ...  NaN   NaN -0.0016  1.045936

[5 rows x 10 columns]
2023-01-12 00:00:18,655:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.498629  0.501371       0  ...  NaN   NaN -0.0016  1.051929
46     1  0.494391  0.505609       0  ...  NaN   NaN -0.0016  1.051143
47     1  0.490995  0.509005       1  ...  NaN   NaN -0.0016  1.052243
48     0  0.503658  0.496342       0  ...  NaN   NaN -0.0016  1.051111
49     1  0.493291  0.506709       0  ...  NaN   NaN -0.0016  1.045936

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '26486.35355196192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17324.29800489', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-12 00:00:01,277:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230111   231000    231959  1673450399  17425.1    17408 -0.000976
572  20230111   232000    232959  1673450999  17407.7    17390 -0.001034
573  20230111   233000    233959  1673451599    17390  17347.8 -0.002427
574  20230111   234000    234959  1673452199  17347.8  17353.1  0.000306
575  20230111   235000    235959  1673452799  17353.2  17325.3 -0.001602
2023-01-12 00:00:01,286:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.681', 'enterprice': '17406.8', 'countrevence': '0', 'unrealprofit': '4312.30814129057', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17324.94300903', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-12 00:00:01,963:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-12 00:00:01,963:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 52.681, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41510F1673452801956I0L59'}
2023-01-12 00:00:02,000:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1120000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230111, closeTime:235959, close:17325.3, total:916090.6231691999, mom:-7.677072607592539e-05, thd:0.0, side:buy 
2023-01-12 00:00:02,295:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41510F1673452801956I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673452802082233, 'quantity': '52.681', 'price': '17324.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673452801571, 'updatetime': 1673452802082, 'tradetype': 'usdt', 'selfid': 41510, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673452802082, 'clientorderid': '41510F1673452801956I0L59', 'price': '17324.3', 'quantity': '52.681', 'commission': '912.6614483', 'commissionasset': 'USDT', 'tradetime': 1673452802082, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673452802082}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-12 00:00:02,491:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41510F1673452801956I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673452802082233, 'quantity': '52.681', 'price': '17324.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673452801571, 'updatetime': 1673452802082, 'tradetype': 'usdt', 'selfid': 41510, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673452802082, 'clientorderid': '41510F1673452801956I0L59', 'price': '17324.3', 'quantity': '52.681', 'commission': '912.6614483', 'commissionasset': 'USDT', 'tradetime': 1673452802082, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673452802082}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6824 

self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17325.2', self.close='17337.8'
2023-01-12 00:10:01,521:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17325.2', self.close='17337.8'
2023-01-12 00:10:01,574:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230111   232000    232959  1673450999  17407.7    17390 -0.001034
573  20230111   233000    233959  1673451599    17390  17347.8 -0.002427
574  20230111   234000    234959  1673452199  17347.8  17353.1  0.000306
575  20230111   235000    235959  1673452799  17353.2  17325.3 -0.001602
576  20230112   000000    000959  1673453399  17325.2  17337.8  0.000721
2023-01-12 00:10:01,574:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-12 00:00:01,292:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230111   231000    231959  1673450399  17425.1    17408
17420  20230111   232000    232959  1673450999  17407.7    17390
17421  20230111   233000    233959  1673451599    17390  17347.8
17422  20230111   234000    234959  1673452199  17347.8  17353.1
17423  20230111   235000    235959  1673452799  17353.2  17325.3
2023-01-12 00:00:01,292:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.979', 'enterprice': '17437', 'countrevence': '0', 'unrealprofit': '-6048.72431556963', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17324.94300903', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-12 00:00:01,993:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-12 00:00:01,993:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.979, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41511F1673452801990I0L57'}
2023-01-12 00:00:02,029:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1120000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230111, closeTime:235959, close:17325.3, total:940290.591177, pct_pre:0.00691797750213663, thd:0.3521008591053399, side:sell 
2023-01-12 00:00:02,467:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41511F1673452801990I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673452802320934, 'quantity': '53.979', 'price': '17324.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673452801522, 'updatetime': 1673452802320, 'tradetype': 'usdt', 'selfid': 41511, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673452802320, 'clientorderid': '41511F1673452801990I0L57', 'price': '17324.2', 'quantity': '53.979', 'commission': '935.1429918', 'commissionasset': 'USDT', 'tradetime': 1673452802320, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673452802320}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-12 00:00:02,741:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41511F1673452801990I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673452802320934, 'quantity': '53.979', 'price': '17324.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673452801522, 'updatetime': 1673452802320, 'tradetype': 'usdt', 'selfid': 41511, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673452802320, 'clientorderid': '41511F1673452801990I0L57', 'price': '17324.2', 'quantity': '53.979', 'commission': '935.1429918', 'commissionasset': 'USDT', 'tradetime': 1673452802320, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673452802320}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6825 

self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17325.2', self.close='17337.8'
2023-01-12 00:10:01,563:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17325.2', self.close='17337.8'
2023-01-12 00:10:01,578:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230111   232000    232959  1673450999  17407.7    17390
17421  20230111   233000    233959  1673451599    17390  17347.8
17422  20230111   234000    234959  1673452199  17347.8  17353.1
17423  20230111   235000    235959  1673452799  17353.2  17325.3
17424  20230112   000000    000959  1673453399  17325.2  17337.8
2023-01-12 00:10:01,578:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-12 00:00:01,249:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230111   231000    231959  1673450399  17425.1    17408
12236  20230111   232000    232959  1673450999  17407.7    17390
12237  20230111   233000    233959  1673451599    17390  17347.8
12238  20230111   234000    234959  1673452199  17347.8  17353.1
12239  20230111   235000    235959  1673452799  17353.2  17325.3
2023-01-12 00:00:01,249:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '71.886', 'enterprice': '17421', 'countrevence': '0', 'unrealprofit': '6905.15285286942', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17324.94300903', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-12 00:00:01,923:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-12 00:00:01,923:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 71.886, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41509F1673452801918I0L2'}
2023-01-12 00:00:01,958:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1120000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230111, closeTime:235959, close:17325.3, total:1251073.679994, corrDate:20221209, corrVal:0.9289843888063768, side:buy 
127.0.0.1 - - [12/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-12 00:00:02,079:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41509F1673452801918I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673452802029969, 'quantity': '71.886', 'price': '17324.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673452801530, 'updatetime': 1673452802029, 'tradetype': 'usdt', 'selfid': 41509, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673452802029, 'clientorderid': '41509F1673452801918I0L2', 'price': '17324.3', 'quantity': '71.886', 'commission': '1245.3746298', 'commissionasset': 'USDT', 'tradetime': 1673452802029, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673452802029}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-12 00:00:02,279:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41509F1673452801918I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673452802029969, 'quantity': '71.886', 'price': '17324.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673452801530, 'updatetime': 1673452802029, 'tradetype': 'usdt', 'selfid': 41509, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673452802029, 'clientorderid': '41509F1673452801918I0L2', 'price': '17324.3', 'quantity': '71.886', 'commission': '1245.3746298', 'commissionasset': 'USDT', 'tradetime': 1673452802029, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673452802029}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6825 

self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17325.2', self.close='17337.8'
2023-01-12 00:10:01,544:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17325.2', self.close='17337.8'
127.0.0.1 - - [12/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-12 00:10:01,564:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230111   232000    232959  1673450999  17407.7    17390
12237  20230111   233000    233959  1673451599    17390  17347.8
12238  20230111   234000    234959  1673452199  17347.8  17353.1
12239  20230111   235000    235959  1673452799  17353.2  17325.3
12240  20230112   000000    000959  1673453399  17325.2  17337.8
2023-01-12 00:10:01,564:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9080
self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17328.6, self.close=17337.8, self.high=17339.4, self.low=17320.3, self.vol=1366.911, self.amt=23684469.3499 
127.0.0.1 - - [12/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-12 00:10:01,530:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230111   234500    234959  ...         0.0        0.0       0
5758  20230111   235000    235459  ...         0.0        0.0       0
5759  20230111   235500    235959  ...         0.0        0.0       0
5760  20230112   000000    000459  ...         0.0        0.0       0
5761  20230112   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 00:10:01,531:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673453399, self.tradeDate='20230112', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17328.6, self.close=17337.8, self.high=17339.4, self.low=17320.3, self.vol=1366.911, self.amt=23684469.3499, ukdf['pct'].iloc[-1]=0.000612 , ukdf['amount'].iloc[-1]=23684469.3499, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [12/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9081
self.closeSec=1673453699, self.tradeDate='20230112', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17337.8, self.close=17344.1, self.high=17345.6, self.low=17333.8, self.vol=1128.653, self.amt=19571446.3907 
2023-01-12 00:15:00,630:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230111   235000    235459  ...         0.0        0.0       0
5759  20230111   235500    235959  ...         0.0        0.0       0
5760  20230112   000000    000459  ...         0.0        0.0       0
5761  20230112   000500    000959  ...         0.0        0.0       0
5762  20230112   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 00:15:00,631:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673453699, self.tradeDate='20230112', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17337.8, self.close=17344.1, self.high=17345.6, self.low=17333.8, self.vol=1128.653, self.amt=19571446.3907, ukdf['pct'].iloc[-1]=0.000363 , ukdf['amount'].iloc[-1]=19571446.3907, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230111   120000    155959  1673423999  ...    723  1.161141  2.127499     1.0
724  20230111   160000    195959  1673438399  ...    724  1.083178  1.833845     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '12298.208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17428.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [12/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=284
self.closeSec=1673452799, self.tradeDate='20230111', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=17428.6, self.close=17325.3, self.high=17429.7, self.low=17306.4, self.vol=62512.096, self.amt=1086441628.1227 
2023-01-12 00:00:01,114:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673452799, self.tradeDate='20230111', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=17428.6, self.close=17325.3, self.high=17429.7, self.low=17306.4, self.vol=62512.096, self.amt=1086441628.1227 
2023-01-12 00:00:01,160:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230111   040000    075959  ...  48167.989  8.401772e+08  0.000264
722  20230111   080000    115959  ...  42391.318  7.389567e+08 -0.001211
723  20230111   120000    155959  ...  25910.727  4.512019e+08  0.001683
724  20230111   160000    195959  ...  24797.868  4.323252e+08 -0.000476
725  20230111   200000    235959  ...  62512.096  1.086442e+09 -0.005933

[5 rows x 11 columns]
2023-01-12 00:00:02,768:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230111   040000    075959  1673395199  ...    721  1.158436  2.281776     1.0
722  20230111   080000    115959  1673409599  ...    722  1.230810  2.418932     1.0
723  20230111   120000    155959  1673423999  ...    723  1.161141  2.127499     1.0
724  20230111   160000    195959  1673438399  ...    724  1.083178  1.833845     1.0
725  20230111   200000    235959  1673452799  ...    725  1.065789  1.736196     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '6975.64980292416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17324.61367731', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


