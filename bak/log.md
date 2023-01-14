# 20230115 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13946
self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20792.0, self.close=20805.5, self.high=20840.0, self.low=20790.6, self.vol=1559.726, self.amt=32468769.1511 
2023-01-15 00:10:01,514:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230114   234500    234959  ...         0.0        0.0       0
5758  20230114   235000    235459  ...         0.0        0.0       0
5759  20230114   235500    235959  ...         0.0        0.0       0
5760  20230115   000000    000459  ...         0.0        0.0       0
5761  20230115   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 00:10:01,514:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20792.0, self.close=20805.5, self.high=20840.0, self.low=20790.6, self.vol=1559.726, self.amt=32468769.1511, ukdf['pct'].iloc[-1]=0.000726 , ukdf['amount'].iloc[-1]=32468769.1511, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-257330.6288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20805.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13947
self.closeSec=1673712899, self.tradeDate='20230115', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20805.5, self.close=20817.9, self.high=20827.3, self.low=20794.0, self.vol=798.68, self.amt=16621861.8932 
127.0.0.1 - - [15/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-15 00:15:00,648:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230114   235000    235459  ...         0.0        0.0       0
5759  20230114   235500    235959  ...         0.0        0.0       0
5760  20230115   000000    000459  ...         0.0        0.0       0
5761  20230115   000500    000959  ...         0.0        0.0       0
5762  20230115   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 00:15:00,648:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673712899, self.tradeDate='20230115', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20805.5, self.close=20817.9, self.high=20827.3, self.low=20794.0, self.vol=798.68, self.amt=16621861.8932, ukdf['pct'].iloc[-1]=0.000596 , ukdf['amount'].iloc[-1]=16621861.8932, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-258070.7936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20817.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=335, self.factor=0.13540273770897873, self.count=14512 

self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20792.0, self.close=20805.5, self.high=20840.0, self.low=20790.6 
2023-01-15 00:10:01,449:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20792.0, self.close=20805.5, self.high=20840.0, self.low=20790.6   
2023-01-15 00:10:01,498:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230114   234500    234959  1673711399  ...  20687.8  0.000478   1725    3
1438  20230114   235000    235459  1673711699  ...  20723.9  0.001331   1726    4
1439  20230114   235500    235959  1673711999  ...  20756.3  0.001507   1727    5
1440  20230115   000000    000459  1673712299  ...  20772.5 -0.000317   1440    0
1441  20230115   000500    000959  1673712599  ...  20790.6  0.000726   1441    1

[5 rows x 11 columns]
2023-01-15 00:10:01,498:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=335, self.factor=0.13540273770897873, self.count=14513 

self.closeSec=1673712899, self.tradeDate='20230115', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20805.5, self.close=20817.9, self.high=20827.3, self.low=20794.0 
2023-01-15 00:15:00,562:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673712899, self.tradeDate='20230115', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20805.5, self.close=20817.9, self.high=20827.3, self.low=20794.0   
127.0.0.1 - - [15/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-15 00:15:00,616:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230114   235000    235459  1673711699  ...  20723.9  0.001331   1726    4
1439  20230114   235500    235959  1673711999  ...  20756.3  0.001507   1727    5
1440  20230115   000000    000459  1673712299  ...  20772.5 -0.000317   1440    0
1441  20230115   000500    000959  1673712599  ...  20790.6  0.000726   1441    1
1442  20230115   001000    001459  1673712899  ...  20794.0  0.000596   1442    2

[5 rows x 11 columns]
2023-01-15 00:15:00,619:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-15 00:00:35,443:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230114    212959  20920.9  ...  57.083333  0.654372  0.263184
5803  20230114    215959  20879.9  ...  57.500000  0.659821  0.262934
5804  20230114    222959  20945.9  ...  57.083333  0.657565  0.263109
5805  20230114    225959  20933.1  ...  56.666667  0.642830  0.265950
5806  20230114    232959  20841.9  ...  56.666667  0.639592  0.269500

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-01-15 00:00:35,604:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.536606  0.463394       1  ...  1.091266   1.0    0.0  1.252526
540     0  0.544253  0.455747       0  ...  1.090531   1.0    0.0  1.251683
541     0  0.527020  0.472980       0  ...  1.085707   1.0    0.0  1.246146
542     1  0.499173  0.500827       0  ...  1.084639   1.0    0.0  1.244920
543     1  0.488814  0.511186       0  ...  1.083503   1.0    0.0  1.243617

[5 rows x 10 columns]
2023-01-15 00:00:35,638:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.537278  0.462722       1  ...  1.091266   1.0    0.0  1.250209
46     0  0.544918  0.455082       0  ...  1.090531   1.0    0.0  1.251930
47     0  0.527593  0.472407       0  ...  1.085707   1.0    0.0  1.246392
48     1  0.499372  0.500628       0  ...  1.084639   1.0    0.0  1.246045
49     1  0.488814  0.511186       0  ...  1.083503   1.0    0.0  1.243617

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-15 00:00:01,171:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230114   231000    231959  1673709599    20785  20786.5  0.000072
572  20230114   232000    232959  1673710199  20788.4  20818.8  0.001554
573  20230114   233000    233959  1673710799  20818.9  20797.3 -0.001033
574  20230114   234000    234959  1673711399  20797.4  20738.1 -0.002847
575  20230114   235000    235959  1673711999  20738.1    20797  0.002840
2023-01-15 00:00:01,180:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '44.412', 'enterprice': '20960.1', 'countrevence': '0', 'unrealprofit': '-7252.4796', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20796.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-15 00:00:01,902:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-15 00:00:01,902:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 44.412, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41527F1673712001899I0L59'}
2023-01-15 00:00:01,948:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1150000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230114, closeTime:235959, close:20797, total:929949.0812388, mom:0.05028117520975428, thd:0.0, side:sell 
127.0.0.1 - - [15/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-15 00:00:02,093:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41527F1673712001899I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673712002028668, 'quantity': '44.412', 'price': '20796.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673712001505, 'updatetime': 1673712002028, 'tradetype': 'usdt', 'selfid': 41527, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673712002028, 'clientorderid': '41527F1673712001899I0L59', 'price': '20796.8', 'quantity': '44.412', 'commission': '923.6274816', 'commissionasset': 'USDT', 'tradetime': 1673712002028, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673712002028}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-15 00:00:02,311:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41527F1673712001899I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673712002028668, 'quantity': '44.412', 'price': '20796.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673712001505, 'updatetime': 1673712002028, 'tradetype': 'usdt', 'selfid': 41527, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673712002028, 'clientorderid': '41527F1673712001899I0L59', 'price': '20796.8', 'quantity': '44.412', 'commission': '923.6274816', 'commissionasset': 'USDT', 'tradetime': 1673712002028, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673712002028}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7256 

self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20796.9', self.close='20805.5'
2023-01-15 00:10:01,524:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20796.9', self.close='20805.5'
127.0.0.1 - - [15/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-15 00:10:01,537:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230114   232000    232959  1673710199  20788.4  20818.8  0.001554
573  20230114   233000    233959  1673710799  20818.9  20797.3 -0.001033
574  20230114   234000    234959  1673711399  20797.4  20738.1 -0.002847
575  20230114   235000    235959  1673711999  20738.1    20797  0.002840
576  20230115   000000    000959  1673712599  20796.9  20805.5  0.000409
2023-01-15 00:10:01,544:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-14 23:50:00,573:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7256 

self.closeSec=1673711999, self.tradeDate='20230114', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='20738.1', self.close='20797'
127.0.0.1 - - [15/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-15 00:00:01,128:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673711999, self.tradeDate='20230114', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='20738.1', self.close='20797'
2023-01-15 00:00:01,185:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230114   231000    231959  1673709599    20785  20786.5
17420  20230114   232000    232959  1673710199  20788.4  20818.8
17421  20230114   233000    233959  1673710799  20818.9  20797.3
17422  20230114   234000    234959  1673711399  20797.4  20738.1
17423  20230114   235000    235959  1673711999  20738.1    20797
2023-01-15 00:00:01,185:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-15 00:00:01,304:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1150000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230114, closeTime:235959, close:20797, total:951537.2948681, pct_pre:0.07313569283009014, thd:-0.9092155874584362, side:sell 
127.0.0.1 - - [15/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7257 

self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20796.9', self.close='20805.5'
2023-01-15 00:10:01,552:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20796.9', self.close='20805.5'
2023-01-15 00:10:01,579:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230114   232000    232959  1673710199  20788.4  20818.8
17421  20230114   233000    233959  1673710799  20818.9  20797.3
17422  20230114   234000    234959  1673711399  20797.4  20738.1
17423  20230114   235000    235959  1673711999  20738.1    20797
17424  20230115   000000    000959  1673712599  20796.9  20805.5
2023-01-15 00:10:01,579:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-15 00:00:01,173:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230114   231000    231959  1673709599    20785  20786.5
12236  20230114   232000    232959  1673710199  20788.4  20818.8
12237  20230114   233000    233959  1673710799  20818.9  20797.3
12238  20230114   234000    234959  1673711399  20797.4  20738.1
12239  20230114   235000    235959  1673711999  20738.1    20797
2023-01-15 00:00:01,173:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.24', 'enterprice': '19843.9', 'countrevence': '0', 'unrealprofit': '-57402.696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20796.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-15 00:00:01,916:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-15 00:00:01,916:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 60.24, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41528F1673712001914I0L2'}
2023-01-15 00:00:01,982:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1150000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230114, closeTime:235959, close:20797, total:1194201.139464, corrDate:20221203, corrVal:0.8681918903397253, side:buy 
2023-01-15 00:00:02,324:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41528F1673712001914I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673712002074094, 'quantity': '60.24', 'price': '20796.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673712001425, 'updatetime': 1673712002074, 'tradetype': 'usdt', 'selfid': 41528, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673712002074, 'clientorderid': '41528F1673712001914I0L2', 'price': '20796.9', 'quantity': '60.24', 'commission': '1252.805256', 'commissionasset': 'USDT', 'tradetime': 1673712002074, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673712002074}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-15 00:00:02,585:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41528F1673712001914I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673712002074094, 'quantity': '60.24', 'price': '20796.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673712001425, 'updatetime': 1673712002074, 'tradetype': 'usdt', 'selfid': 41528, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673712002074, 'clientorderid': '41528F1673712001914I0L2', 'price': '20796.9', 'quantity': '60.24', 'commission': '1252.805256', 'commissionasset': 'USDT', 'tradetime': 1673712002074, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673712002074}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7257 

self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20796.9', self.close='20805.5'
127.0.0.1 - - [15/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-15 00:10:01,541:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20796.9', self.close='20805.5'
2023-01-15 00:10:01,560:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230114   232000    232959  1673710199  20788.4  20818.8
12237  20230114   233000    233959  1673710799  20818.9  20797.3
12238  20230114   234000    234959  1673711399  20797.4  20738.1
12239  20230114   235000    235959  1673711999  20738.1    20797
12240  20230115   000000    000959  1673712599  20796.9  20805.5
2023-01-15 00:10:01,560:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9944
self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20792.0, self.close=20805.5, self.high=20840.0, self.low=20790.6, self.vol=1559.726, self.amt=32468769.1511 
127.0.0.1 - - [15/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-15 00:10:01,481:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230114   234500    234959  ...         0.0        0.0       0
5758  20230114   235000    235459  ...         0.0        0.0       0
5759  20230114   235500    235959  ...         0.0        0.0       0
5760  20230115   000000    000459  ...         0.0        0.0       0
5761  20230115   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 00:10:01,481:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673712599, self.tradeDate='20230115', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20792.0, self.close=20805.5, self.high=20840.0, self.low=20790.6, self.vol=1559.726, self.amt=32468769.1511, ukdf['pct'].iloc[-1]=0.000726 , ukdf['amount'].iloc[-1]=32468769.1511, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9945
self.closeSec=1673712899, self.tradeDate='20230115', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20805.5, self.close=20817.9, self.high=20827.3, self.low=20794.0, self.vol=798.68, self.amt=16621861.8932 
127.0.0.1 - - [15/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-15 00:15:00,651:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230114   235000    235459  ...         0.0        0.0       0
5759  20230114   235500    235959  ...         0.0        0.0       0
5760  20230115   000000    000459  ...         0.0        0.0       0
5761  20230115   000500    000959  ...         0.0        0.0       0
5762  20230115   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 00:15:00,651:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673712899, self.tradeDate='20230115', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20805.5, self.close=20817.9, self.high=20827.3, self.low=20794.0, self.vol=798.68, self.amt=16621861.8932, ukdf['pct'].iloc[-1]=0.000596 , ukdf['amount'].iloc[-1]=16621861.8932, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230114   120000    155959  1673683199  ...    723  1.289315  1.435970     1.0
724  20230114   160000    195959  1673697599  ...    724  1.303569  1.434301     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '181190.1888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20731.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [15/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=302
self.closeSec=1673711999, self.tradeDate='20230114', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=20733.3, self.close=20797.0, self.high=21240.0, self.low=20544.0, self.vol=186884.918, self.amt=3898285012.14338 
2023-01-15 00:00:01,003:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673711999, self.tradeDate='20230114', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=20733.3, self.close=20797.0, self.high=21240.0, self.low=20544.0, self.vol=186884.918, self.amt=3898285012.14338 
2023-01-15 00:00:01,063:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230114   040000    075959  ...  253648.534  4.995445e+09  0.029520
722  20230114   080000    115959  ...  400665.223  8.322359e+09  0.053985
723  20230114   120000    155959  ...   75863.507  1.587466e+09 -0.003967
724  20230114   160000    195959  ...  208916.807  4.304202e+09 -0.008759
725  20230114   200000    235959  ...  186884.918  3.898285e+09  0.003072

[5 rows x 11 columns]
2023-01-15 00:00:03,289:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230114   040000    075959  1673654399  ...    721  1.235840  1.402725     1.0
722  20230114   080000    115959  1673668799  ...    722  1.534216  2.042994     1.0
723  20230114   120000    155959  1673683199  ...    723  1.289315  1.435970     1.0
724  20230114   160000    195959  1673697599  ...    724  1.303569  1.434301     1.0
725  20230114   200000    235959  1673711999  ...    725  1.292952  1.376640     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '184529.3696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20796.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


