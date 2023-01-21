# 20230122 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15962
self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23056.1, self.close=23081.2, self.high=23116.6, self.low=23040.2, self.vol=4529.62, self.amt=104544641.55 
127.0.0.1 - - [22/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-22 00:10:01,515:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230121   234500    234959  ...         0.0        0.0       0
5758  20230121   235000    235459  ...         0.0        0.0       0
5759  20230121   235500    235959  ...         0.0        0.0       0
5760  20230122   000000    000459  ...         0.0        0.0       0
5761  20230122   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 00:10:01,516:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23056.1, self.close=23081.2, self.high=23116.6, self.low=23040.2, self.vol=4529.62, self.amt=104544641.55, ukdf['pct'].iloc[-1]=0.000967 , ukdf['amount'].iloc[-1]=104544641.55, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-394273.152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23081.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15963
self.closeSec=1674317699, self.tradeDate='20230122', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23081.3, self.close=23100.0, self.high=23141.1, self.low=23075.1, self.vol=3778.974, self.amt=87339780.3043 
2023-01-22 00:15:00,670:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230121   235000    235459  ...         0.0        0.0       0
5759  20230121   235500    235959  ...         0.0        0.0       0
5760  20230122   000000    000459  ...         0.0        0.0       0
5761  20230122   000500    000959  ...         0.0        0.0       0
5762  20230122   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 00:15:00,670:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674317699, self.tradeDate='20230122', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23081.3, self.close=23100.0, self.high=23141.1, self.low=23075.1, self.vol=3778.974, self.amt=87339780.3043, ukdf['pct'].iloc[-1]=0.000815 , ukdf['amount'].iloc[-1]=87339780.3043, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-395419.85337429408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23100.35579258', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23056.1, self.close=23081.2, self.high=23116.6, self.low=23040.2 
2023-01-22 00:10:01,435:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23056.1, self.close=23081.2, self.high=23116.6, self.low=23040.2   
127.0.0.1 - - [22/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-22 00:10:01,477:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230121   234500    234959  1674316199  ...  23163.0 -0.001339   1725    3
1438  20230121   235000    235459  1674316499  ...  23173.0 -0.000569   1726    4
1439  20230121   235500    235959  1674316799  ...  22932.7 -0.007827   1727    5
1440  20230122   000000    000459  1674317099  ...  22980.0  0.002727   1440    0
1441  20230122   000500    000959  1674317399  ...  23040.2  0.000967   1441    1

[5 rows x 11 columns]
2023-01-22 00:10:01,477:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=45, self.factor=0.18818857395859714, self.count=16529 

self.closeSec=1674317699, self.tradeDate='20230122', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23081.3, self.close=23100.0, self.high=23141.1, self.low=23075.1 
2023-01-22 00:15:00,642:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674317699, self.tradeDate='20230122', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23081.3, self.close=23100.0, self.high=23141.1, self.low=23075.1   
2023-01-22 00:15:00,694:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230121   235000    235459  1674316499  ...  23173.0 -0.000569   1726    4
1439  20230121   235500    235959  1674316799  ...  22932.7 -0.007827   1727    5
1440  20230122   000000    000459  1674317099  ...  22980.0  0.002727   1440    0
1441  20230122   000500    000959  1674317399  ...  23040.2  0.000967   1441    1
1442  20230122   001000    001459  1674317699  ...  23075.1  0.000815   1442    2

[5 rows x 11 columns]
2023-01-22 00:15:00,694:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-22 00:00:17,676:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230121    212959  23036.8  ...  55.000000  0.697574  0.148616
5803  20230121    215959  22964.1  ...  55.000000  0.688422  0.151832
5804  20230121    222959  22927.2  ...  55.000000  0.688750  0.154860
5805  20230121    225959  22930.0  ...  55.416667  0.691375  0.157245
5806  20230121    232959  22953.0  ...  55.416667  0.719626  0.150403

[5 rows x 33 columns]
0.53125
acc is : 0.53125
2023-01-22 00:00:17,754:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.513426  0.486574       0  ...  1.074845   1.0    0.0  1.333388
540     0  0.509255  0.490745       1  ...  1.074981   1.0    0.0  1.333556
541     0  0.507997  0.492003       1  ...  1.076059   1.0    0.0  1.334894
542     0  0.506137  0.493863       1  ...  1.088684   1.0    0.0  1.350556
543     0  0.577854  0.422146       0  ...  1.077883   1.0    0.0  1.337156

[5 rows x 10 columns]
2023-01-22 00:00:17,765:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513148  0.486852       0  ...  1.109206   1.0    0.0  1.332713
46     0  0.509159  0.490841       1  ...  1.147537   1.0    0.0  1.333393
47     0  0.507875  0.492125       1  ...  1.148688   1.0    0.0  1.334731
48     0  0.506312  0.493688       1  ...  1.162165   1.0    0.0  1.350988
49     0  0.577854  0.422146       0  ...  1.077883   1.0    0.0  1.337156

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.709', 'enterprice': '20883.4', 'countrevence': '0', 'unrealprofit': '71534.37404891622', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23005.51498558', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-22 00:00:01,589:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230121   231000    231959  1674314399  22980.1  23086.6  0.004639
572  20230121   232000    232959  1674314999  23086.6  23222.4  0.005882
573  20230121   233000    233959  1674315599    23224    23200 -0.000965
574  20230121   234000    234959  1674316199  23199.9  23186.1 -0.000599
575  20230121   235000    235959  1674316799  23186.1  22996.2 -0.008190
2023-01-22 00:00:01,589:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.443', 'enterprice': '22550.4', 'countrevence': '0', 'unrealprofit': '18424.14876328023', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22994.96600061', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-22 00:00:02,464:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-22 00:00:02,464:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 41.443, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41571F1674316802349I0L59'}
2023-01-22 00:00:02,484:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1220000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230121, closeTime:235959, close:22996.2, total:933621.6709728, mom:0.010868751925330766, thd:0.0, side:sell 
2023-01-22 00:00:02,610:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41571F1674316802349I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674316802572691, 'quantity': '41.443', 'price': '22992.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674316801990, 'updatetime': 1674316802572, 'tradetype': 'usdt', 'selfid': 41571, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674316802572, 'clientorderid': '41571F1674316802349I0L59', 'price': '22992.2', 'quantity': '41.443', 'commission': '952.8657446', 'commissionasset': 'USDT', 'tradetime': 1674316802572, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674316802572}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-22 00:00:02,863:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41571F1674316802349I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674316802572691, 'quantity': '41.443', 'price': '22992.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674316801990, 'updatetime': 1674316802572, 'tradetype': 'usdt', 'selfid': 41571, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674316802572, 'clientorderid': '41571F1674316802349I0L59', 'price': '22992.2', 'quantity': '41.443', 'commission': '952.8657446', 'commissionasset': 'USDT', 'tradetime': 1674316802572, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674316802572}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8264 

self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22996.2', self.close='23081.2'
2023-01-22 00:10:01,540:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22996.2', self.close='23081.2'
2023-01-22 00:10:01,588:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230121   232000    232959  1674314999  23086.6  23222.4  0.005882
573  20230121   233000    233959  1674315599    23224    23200 -0.000965
574  20230121   234000    234959  1674316199  23199.9  23186.1 -0.000599
575  20230121   235000    235959  1674316799  23186.1  22996.2 -0.008190
576  20230122   000000    000959  1674317399  22996.2  23081.2  0.003696
2023-01-22 00:10:01,588:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-21 23:50:00,594:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8264 

self.closeSec=1674316799, self.tradeDate='20230121', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='23186.1', self.close='22996.2'
2023-01-22 00:00:01,554:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674316799, self.tradeDate='20230121', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='23186.1', self.close='22996.2'
127.0.0.1 - - [22/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-22 00:00:01,589:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230121   231000    231959  1674314399  22980.1  23086.6
17420  20230121   232000    232959  1674314999  23086.6  23222.4
17421  20230121   233000    233959  1674315599    23224    23200
17422  20230121   234000    234959  1674316199  23199.9  23186.1
17423  20230121   235000    235959  1674316799  23186.1  22996.2
2023-01-22 00:00:01,590:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-22 00:00:01,681:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1220000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230121, closeTime:235959, close:22996.2, total:948173.1491922, pct_pre:0.08890948730438741, thd:-0.2479170553964964, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8265 

self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22996.2', self.close='23081.2'
2023-01-22 00:10:01,553:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22996.2', self.close='23081.2'
127.0.0.1 - - [22/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-22 00:10:01,596:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230121   232000    232959  1674314999  23086.6  23222.4
17421  20230121   233000    233959  1674315599    23224    23200
17422  20230121   234000    234959  1674316199  23199.9  23186.1
17423  20230121   235000    235959  1674316799  23186.1  22996.2
17424  20230122   000000    000959  1674317399  22996.2  23081.2
2023-01-22 00:10:01,596:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-22 00:00:01,586:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230121   231000    231959  1674314399  22980.1  23086.6
12236  20230121   232000    232959  1674314999  23086.6  23222.4
12237  20230121   233000    233959  1674315599    23224    23200
12238  20230121   234000    234959  1674316199  23199.9  23186.1
12239  20230121   235000    235959  1674316799  23186.1  22996.2
2023-01-22 00:00:01,586:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.148', 'enterprice': '22592.3', 'countrevence': '0', 'unrealprofit': '-20192.89459859028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22994.96600061', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-22 00:00:02,115:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-22 00:00:02,115:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 50.148, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41570F1674316802114I0L2'}
2023-01-22 00:00:02,136:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1220000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230121, closeTime:235959, close:22996.2, total:1131825.7017396, corrDate:20221203, corrVal:0.9478101363137675, side:buy 
127.0.0.1 - - [22/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-22 00:00:02,250:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41570F1674316802114I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674316802223507, 'quantity': '50.148', 'price': '22992.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674316801753, 'updatetime': 1674316802223, 'tradetype': 'usdt', 'selfid': 41570, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674316802223, 'clientorderid': '41570F1674316802114I0L2', 'price': '22992.3', 'quantity': '50.148', 'commission': '1153.0178604', 'commissionasset': 'USDT', 'tradetime': 1674316802223, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674316802223}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-22 00:00:02,466:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41570F1674316802114I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674316802223507, 'quantity': '50.148', 'price': '22992.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674316801753, 'updatetime': 1674316802223, 'tradetype': 'usdt', 'selfid': 41570, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674316802223, 'clientorderid': '41570F1674316802114I0L2', 'price': '22992.3', 'quantity': '50.148', 'commission': '1153.0178604', 'commissionasset': 'USDT', 'tradetime': 1674316802223, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674316802223}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8265 

self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22996.2', self.close='23081.2'
2023-01-22 00:10:01,568:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22996.2', self.close='23081.2'
2023-01-22 00:10:01,592:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230121   232000    232959  1674314999  23086.6  23222.4
12237  20230121   233000    233959  1674315599    23224    23200
12238  20230121   234000    234959  1674316199  23199.9  23186.1
12239  20230121   235000    235959  1674316799  23186.1  22996.2
12240  20230122   000000    000959  1674317399  22996.2  23081.2
2023-01-22 00:10:01,594:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11960
self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23056.1, self.close=23081.2, self.high=23116.6, self.low=23040.2, self.vol=4529.62, self.amt=104544641.55 
127.0.0.1 - - [22/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-22 00:10:01,503:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230121   234500    234959  ...         0.0        0.0       0
5758  20230121   235000    235459  ...         0.0        0.0       0
5759  20230121   235500    235959  ...         0.0        0.0       0
5760  20230122   000000    000459  ...         0.0        0.0       0
5761  20230122   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 00:10:01,509:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674317399, self.tradeDate='20230122', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23056.1, self.close=23081.2, self.high=23116.6, self.low=23040.2, self.vol=4529.62, self.amt=104544641.55, ukdf['pct'].iloc[-1]=0.000967 , ukdf['amount'].iloc[-1]=104544641.55, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11961
self.closeSec=1674317699, self.tradeDate='20230122', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23081.3, self.close=23100.0, self.high=23141.1, self.low=23075.1, self.vol=3778.974, self.amt=87339780.3043 
2023-01-22 00:15:00,702:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230121   235000    235459  ...         0.0        0.0       0
5759  20230121   235500    235959  ...         0.0        0.0       0
5760  20230122   000000    000459  ...         0.0        0.0       0
5761  20230122   000500    000959  ...         0.0        0.0       0
5762  20230122   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 00:15:00,702:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674317699, self.tradeDate='20230122', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23081.3, self.close=23100.0, self.high=23141.1, self.low=23075.1, self.vol=3778.974, self.amt=87339780.3043, ukdf['pct'].iloc[-1]=0.000815 , ukdf['amount'].iloc[-1]=87339780.3043, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230121   120000    155959  1674287999  ...    723  0.778042  0.107792     NaN
724  20230121   160000    195959  1674302399  ...    724  0.980106  0.549824     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-88663.7451', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22903.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=344
self.closeSec=1674316799, self.tradeDate='20230121', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22903.5, self.close=22996.2, self.high=23288.0, self.low=22847.8, self.vol=145710.162, self.amt=3357101896.61522 
127.0.0.1 - - [22/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-22 00:00:01,426:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674316799, self.tradeDate='20230121', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22903.5, self.close=22996.2, self.high=23288.0, self.low=22847.8, self.vol=145710.162, self.amt=3357101896.61522 
2023-01-22 00:00:01,448:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230121   040000    075959  ...  326184.044  7.247155e+09  0.054501
722  20230121   080000    115959  ...   91102.531  2.057612e+09 -0.005414
723  20230121   120000    155959  ...   32823.977  7.419001e+08  0.003984
724  20230121   160000    195959  ...  266330.182  6.102600e+09  0.012019
725  20230121   200000    235959  ...  145710.162  3.357102e+09  0.004047

[5 rows x 11 columns]
2023-01-22 00:00:02,893:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230121   040000    075959  1674259199  ...    721  0.730974  0.021872     NaN
722  20230121   080000    115959  1674273599  ...    722  0.824589  0.221529     NaN
723  20230121   120000    155959  1674287999  ...    723  0.778042  0.107792     NaN
724  20230121   160000    195959  1674302399  ...    724  0.980106  0.549824     NaN
725  20230121   200000    235959  1674316799  ...    725  1.000848  0.581866     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-93351.80942775844', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22995.42740148', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


