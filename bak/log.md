# 20230120 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [20/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15386
self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20852.4, self.close=20883.1, self.high=20886.5, self.low=20825.0, self.vol=2118.907, self.amt=44187653.8342 
2023-01-20 00:10:01,537:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230119   234500    234959  ...         0.0        0.0       0
5758  20230119   235000    235459  ...         0.0        0.0       0
5759  20230119   235500    235959  ...         0.0        0.0       0
5760  20230120   000000    000459  ...         0.0        0.0       0
5761  20230120   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-20 00:10:01,572:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20852.4, self.close=20883.1, self.high=20886.5, self.low=20825.0, self.vol=2118.907, self.amt=44187653.8342, ukdf['pct'].iloc[-1]=0.001472 , ukdf['amount'].iloc[-1]=44187653.8342, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-261988.2512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20883', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15387
self.closeSec=1674144899, self.tradeDate='20230120', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20883.1, self.close=20916.5, self.high=20926.5, self.low=20881.9, self.vol=2849.928, self.amt=59586763.6474 
2023-01-20 00:15:00,782:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230119   235000    235459  ...         0.0        0.0       0
5759  20230119   235500    235959  ...         0.0        0.0       0
5760  20230120   000000    000459  ...         0.0        0.0       0
5761  20230120   000500    000959  ...         0.0        0.0       0
5762  20230120   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-20 00:15:00,782:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674144899, self.tradeDate='20230120', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20883.1, self.close=20916.5, self.high=20926.5, self.low=20881.9, self.vol=2849.928, self.amt=59586763.6474, ukdf['pct'].iloc[-1]=0.001599 , ukdf['amount'].iloc[-1]=59586763.6474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-264082.86242186432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20917.80808332', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6359173888788783, self.count=15952 

self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20852.4, self.close=20883.1, self.high=20886.5, self.low=20825.0 
2023-01-20 00:10:01,430:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20852.4, self.close=20883.1, self.high=20886.5, self.low=20825.0   
2023-01-20 00:10:01,524:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230119   234500    234959  1674143399  ...  20856.4 -0.001177   1725    3
1438  20230119   235000    235459  1674143699  ...  20864.1  0.000565   1726    4
1439  20230119   235500    235959  1674143999  ...  20860.1 -0.000488   1727    5
1440  20230120   000000    000459  1674144299  ...  20844.2 -0.000882   1440    0
1441  20230120   000500    000959  1674144599  ...  20825.0  0.001472   1441    1

[5 rows x 11 columns]
2023-01-20 00:10:01,524:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6359173888788783, self.count=15953 

self.closeSec=1674144899, self.tradeDate='20230120', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20883.1, self.close=20916.5, self.high=20926.5, self.low=20881.9 
2023-01-20 00:15:00,657:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674144899, self.tradeDate='20230120', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20883.1, self.close=20916.5, self.high=20926.5, self.low=20881.9   
127.0.0.1 - - [20/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-20 00:15:00,729:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230119   235000    235459  1674143699  ...  20864.1  0.000565   1726    4
1439  20230119   235500    235959  1674143999  ...  20860.1 -0.000488   1727    5
1440  20230120   000000    000459  1674144299  ...  20844.2 -0.000882   1440    0
1441  20230120   000500    000959  1674144599  ...  20825.0  0.001472   1441    1
1442  20230120   001000    001459  1674144899  ...  20881.9  0.001599   1442    2

[5 rows x 11 columns]
2023-01-20 00:15:00,730:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-20 00:00:35,601:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230119    212959  20728.1  ...  50.000000  0.460803  0.658693
5803  20230119    215959  20776.5  ...  49.583333  0.460782  0.658070
5804  20230119    222959  20776.2  ...  49.583333  0.459244  0.658572
5805  20230119    225959  20769.8  ...  50.000000  0.467258  0.647824
5806  20230119    232959  20800.8  ...  50.416667  0.491928  0.618763

[5 rows x 33 columns]
0.5569852941176471
acc is : 0.5569852941176471
2023-01-20 00:00:35,796:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510754  0.489246       1  ...  1.100626  -1.0    0.0  1.226066
540     0  0.507456  0.492544       0  ...  1.101007  -1.0    0.0  1.225641
541     0  0.504429  0.495571       1  ...  1.099321  -1.0    0.0  1.227518
542     0  0.514538  0.485462       1  ...  1.093925  -1.0    0.0  1.233543
543     0  0.544324  0.455676       0  ...  1.095616  -1.0    0.0  1.231637

[5 rows x 10 columns]
2023-01-20 00:00:35,834:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510773  0.489227       1  ...  1.100626  -1.0    0.0  1.227188
46     0  0.506851  0.493149       0  ...  1.101007  -1.0    0.0  1.225619
47     0  0.504485  0.495515       1  ...  1.099321  -1.0    0.0  1.227496
48     0  0.514585  0.485415       1  ...  1.093925  -1.0    0.0  1.233514
49     0  0.544324  0.455676       0  ...  1.095616  -1.0    0.0  1.231637

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.395', 'enterprice': '20707.9', 'countrevence': '0', 'unrealprofit': '-5812.755', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20876.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-20 00:00:01,628:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230119   231000    231959  1674141599    20882  20911.4  0.001408
572  20230119   232000    232959  1674142199  20909.1    20903 -0.000402
573  20230119   233000    233959  1674142799    20903  20896.8 -0.000297
574  20230119   234000    234959  1674143399  20896.9  20869.2 -0.001321
575  20230119   235000    235959  1674143999  20869.3  20870.7  0.000072
2023-01-20 00:00:01,628:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '45.16', 'enterprice': '20782.3', 'countrevence': '0', 'unrealprofit': '-4021.193761596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20871.3432631', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-20 00:00:02,246:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-20 00:00:02,246:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 45.16, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41558F1674144002242I0L59'}
2023-01-20 00:00:02,288:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1200000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230119, closeTime:235959, close:20870.7, total:937590.1393319999, mom:-0.010545099552569992, thd:0.0, side:buy 
127.0.0.1 - - [20/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-20 00:00:02,647:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41558F1674144002242I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674144002361804, 'quantity': '45.16', 'price': '20871', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674144001802, 'updatetime': 1674144002361, 'tradetype': 'usdt', 'selfid': 41558, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674144002361, 'clientorderid': '41558F1674144002242I0L59', 'price': '20871', 'quantity': '45.16', 'commission': '942.53436', 'commissionasset': 'USDT', 'tradetime': 1674144002361, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674144002361}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-20 00:00:02,838:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41558F1674144002242I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674144002361804, 'quantity': '45.16', 'price': '20871', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674144001802, 'updatetime': 1674144002361, 'tradetype': 'usdt', 'selfid': 41558, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674144002361, 'clientorderid': '41558F1674144002242I0L59', 'price': '20871', 'quantity': '45.16', 'commission': '942.53436', 'commissionasset': 'USDT', 'tradetime': 1674144002361, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674144002361}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7976 

self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20870.8', self.close='20883.1'
2023-01-20 00:10:01,546:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20870.8', self.close='20883.1'
127.0.0.1 - - [20/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-20 00:10:01,579:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230119   232000    232959  1674142199  20909.1    20903 -0.000402
573  20230119   233000    233959  1674142799    20903  20896.8 -0.000297
574  20230119   234000    234959  1674143399  20896.9  20869.2 -0.001321
575  20230119   235000    235959  1674143999  20869.3  20870.7  0.000072
576  20230120   000000    000959  1674144599  20870.8  20883.1  0.000594
2023-01-20 00:10:01,587:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-19 23:50:00,592:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7976 

self.closeSec=1674143999, self.tradeDate='20230119', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='20869.3', self.close='20870.7'
2023-01-20 00:00:01,605:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674143999, self.tradeDate='20230119', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='20869.3', self.close='20870.7'
2023-01-20 00:00:01,649:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230119   231000    231959  1674141599    20882  20911.4
17420  20230119   232000    232959  1674142199  20909.1    20903
17421  20230119   233000    233959  1674142799    20903  20896.8
17422  20230119   234000    234959  1674143399  20896.9  20869.2
17423  20230119   235000    235959  1674143999  20869.3  20870.7
2023-01-20 00:00:01,649:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-20 00:00:01,756:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1200000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230119, closeTime:235959, close:20870.7, total:940886.6422769, pct_pre:-0.005784436519394642, thd:0.4056958365981201, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7977 

self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20870.8', self.close='20883.1'
2023-01-20 00:10:01,565:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20870.8', self.close='20883.1'
127.0.0.1 - - [20/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-20 00:10:01,594:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230119   232000    232959  1674142199  20909.1    20903
17421  20230119   233000    233959  1674142799    20903  20896.8
17422  20230119   234000    234959  1674143399  20896.9  20869.2
17423  20230119   235000    235959  1674143999  20869.3  20870.7
17424  20230120   000000    000959  1674144599  20870.8  20883.1
2023-01-20 00:10:01,595:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-20 00:00:01,555:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230119   231000    231959  1674141599    20882  20911.4
12236  20230119   232000    232959  1674142199  20909.1    20903
12237  20230119   233000    233959  1674142799    20903  20896.8
12238  20230119   234000    234959  1674143399  20896.9  20869.2
12239  20230119   235000    235959  1674143999  20869.3  20870.7
2023-01-20 00:00:01,555:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.577', 'enterprice': '20809.4', 'countrevence': '0', 'unrealprofit': '3380.6774702087', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20871.3432631', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-20 00:00:02,230:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-20 00:00:02,230:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.577, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41557F1674144002229I0L2'}
2023-01-20 00:00:02,270:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1200000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230119, closeTime:235959, close:20870.7, total:1134578.9091762, corrDate:20221224, corrVal:0.5691794020111212, side:sell 
2023-01-20 00:00:02,410:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41557F1674144002229I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674144002349728, 'quantity': '54.577', 'price': '20870.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674144001802, 'updatetime': 1674144002349, 'tradetype': 'usdt', 'selfid': 41557, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674144002349, 'clientorderid': '41557F1674144002229I0L2', 'price': '20870.9', 'quantity': '54.577', 'commission': '1139.0711093', 'commissionasset': 'USDT', 'tradetime': 1674144002349, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674144002349}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-20 00:00:02,635:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41557F1674144002229I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674144002349728, 'quantity': '54.577', 'price': '20870.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674144001802, 'updatetime': 1674144002349, 'tradetype': 'usdt', 'selfid': 41557, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674144002349, 'clientorderid': '41557F1674144002229I0L2', 'price': '20870.9', 'quantity': '54.577', 'commission': '1139.0711093', 'commissionasset': 'USDT', 'tradetime': 1674144002349, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674144002349}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7977 

self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20870.8', self.close='20883.1'
2023-01-20 00:10:01,545:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20870.8', self.close='20883.1'
2023-01-20 00:10:01,577:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230119   232000    232959  1674142199  20909.1    20903
12237  20230119   233000    233959  1674142799    20903  20896.8
12238  20230119   234000    234959  1674143399  20896.9  20869.2
12239  20230119   235000    235959  1674143999  20869.3  20870.7
12240  20230120   000000    000959  1674144599  20870.8  20883.1
2023-01-20 00:10:01,586:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [20/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11384
self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20852.4, self.close=20883.1, self.high=20886.5, self.low=20825.0, self.vol=2118.907, self.amt=44187653.8342 
2023-01-20 00:10:01,590:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230119   234500    234959  ...         0.0        0.0       0
5758  20230119   235000    235459  ...         0.0        0.0       0
5759  20230119   235500    235959  ...         0.0        0.0       0
5760  20230120   000000    000459  ...         0.0        0.0       0
5761  20230120   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-20 00:10:01,590:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674144599, self.tradeDate='20230120', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20852.4, self.close=20883.1, self.high=20886.5, self.low=20825.0, self.vol=2118.907, self.amt=44187653.8342, ukdf['pct'].iloc[-1]=0.001472 , ukdf['amount'].iloc[-1]=44187653.8342, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11385
self.closeSec=1674144899, self.tradeDate='20230120', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20883.1, self.close=20916.5, self.high=20926.5, self.low=20881.9, self.vol=2849.928, self.amt=59586763.6474 
127.0.0.1 - - [20/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-20 00:15:00,786:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230119   235000    235459  ...         0.0        0.0       0
5759  20230119   235500    235959  ...         0.0        0.0       0
5760  20230120   000000    000459  ...         0.0        0.0       0
5761  20230120   000500    000959  ...         0.0        0.0       0
5762  20230120   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-20 00:15:00,787:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674144899, self.tradeDate='20230120', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20883.1, self.close=20916.5, self.high=20926.5, self.low=20881.9, self.vol=2849.928, self.amt=59586763.6474, ukdf['pct'].iloc[-1]=0.001599 , ukdf['amount'].iloc[-1]=59586763.6474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230119   120000    155959  1674115199  ...    723  0.204434 -1.425282    -1.0
724  20230119   160000    195959  1674129599  ...    724  0.195458 -1.412865    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '21683.3899609953', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20742.1768699', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [20/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=332
self.closeSec=1674143999, self.tradeDate='20230119', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=20741.3, self.close=20870.8, self.high=20962.7, self.low=20661.0, self.vol=108038.719, self.amt=2247318591.179 
2023-01-20 00:00:01,355:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674143999, self.tradeDate='20230119', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=20741.3, self.close=20870.8, self.high=20962.7, self.low=20661.0, self.vol=108038.719, self.amt=2247318591.179 
2023-01-20 00:00:01,394:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230119   040000    075959  ...   93528.513  1.941499e+09 -0.010768
722  20230119   080000    115959  ...   43011.055  8.920198e+08  0.003332
723  20230119   120000    155959  ...   31249.692  6.507700e+08  0.003335
724  20230119   160000    195959  ...   39443.433  8.193602e+08 -0.003684
725  20230119   200000    235959  ...  108038.719  2.247319e+09  0.006239

[5 rows x 11 columns]
2023-01-20 00:00:03,378:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230119   040000    075959  1674086399  ...    721  0.176794 -1.566888    -1.0
722  20230119   080000    115959  1674100799  ...    722  0.200767 -1.469262    -1.0
723  20230119   120000    155959  1674115199  ...    723  0.204434 -1.425282    -1.0
724  20230119   160000    195959  1674129599  ...    724  0.195458 -1.412865    -1.0
725  20230119   200000    235959  1674143999  ...    725  0.166687 -1.446583    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '15084.36741283202', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20871.43514166', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


