# 20230116 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [16/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14234
self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20956.3, self.close=20942.5, self.high=20976.1, self.low=20925.5, self.vol=2518.104, self.amt=52757358.5362 
2023-01-16 00:10:01,700:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230115   234500    234959  ...         0.0        0.0       0
5758  20230115   235000    235459  ...         0.0        0.0       0
5759  20230115   235500    235959  ...         0.0        0.0       0
5760  20230116   000000    000459  ...         0.0        0.0       0
5761  20230116   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 00:10:01,700:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20956.3, self.close=20942.5, self.high=20976.1, self.low=20925.5, self.vol=2518.104, self.amt=52757358.5362, ukdf['pct'].iloc[-1]=-0.000721 , ukdf['amount'].iloc[-1]=52757358.5362, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-265442.3536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20940.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14235
self.closeSec=1673799299, self.tradeDate='20230116', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20940.4, self.close=20951.3, self.high=20966.2, self.low=20933.2, self.vol=1575.512, self.amt=33007104.1079 
2023-01-16 00:15:00,787:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230115   235000    235459  ...         0.0        0.0       0
5759  20230115   235500    235959  ...         0.0        0.0       0
5760  20230116   000000    000459  ...         0.0        0.0       0
5761  20230116   000500    000959  ...         0.0        0.0       0
5762  20230116   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 00:15:00,788:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673799299, self.tradeDate='20230116', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20940.4, self.close=20951.3, self.high=20966.2, self.low=20933.2, self.vol=1575.512, self.amt=33007104.1079, ukdf['pct'].iloc[-1]=0.00042 , ukdf['amount'].iloc[-1]=33007104.1079, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-266175.46988161728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20952.58286828', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20956.3, self.close=20942.5, self.high=20976.1, self.low=20925.5 
2023-01-16 00:10:01,489:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20956.3, self.close=20942.5, self.high=20976.1, self.low=20925.5   
127.0.0.1 - - [16/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-16 00:10:01,556:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230115   234500    234959  1673797799  ...  20896.0  0.000832   1725    3
1438  20230115   235000    235459  1673798099  ...  20932.2 -0.000062   1726    4
1439  20230115   235500    235959  1673798399  ...  20922.5 -0.000430   1727    5
1440  20230116   000000    000459  1673798699  ...  20890.4  0.001390   1440    0
1441  20230116   000500    000959  1673798999  ...  20925.5 -0.000721   1441    1

[5 rows x 11 columns]
2023-01-16 00:10:01,558:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=383, self.factor=0.4116699865249083, self.count=14801 

self.closeSec=1673799299, self.tradeDate='20230116', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20940.4, self.close=20951.3, self.high=20966.2, self.low=20933.2 
2023-01-16 00:15:00,638:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673799299, self.tradeDate='20230116', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20940.4, self.close=20951.3, self.high=20966.2, self.low=20933.2   
127.0.0.1 - - [16/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-16 00:15:00,749:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230115   235000    235459  1673798099  ...  20932.2 -0.000062   1726    4
1439  20230115   235500    235959  1673798399  ...  20922.5 -0.000430   1727    5
1440  20230116   000000    000459  1673798699  ...  20890.4  0.001390   1440    0
1441  20230116   000500    000959  1673798999  ...  20925.5 -0.000721   1441    1
1442  20230116   001000    001459  1673799299  ...  20933.2  0.000420   1442    2

[5 rows x 11 columns]
2023-01-16 00:15:00,755:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-16 00:00:45,953:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230115    212959  20707.9  ...  55.000000  0.572003  0.605891
5803  20230115    215959  20748.4  ...  54.583333  0.566335  0.611829
5804  20230115    222959  20719.4  ...  54.583333  0.567092  0.616750
5805  20230115    225959  20724.4  ...  54.583333  0.579063  0.611417
5806  20230115    232959  20805.4  ...  54.583333  0.590092  0.596974

[5 rows x 33 columns]
0.5238970588235294
acc is : 0.5238970588235294
2023-01-16 00:00:46,232:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510887  0.489113       0  ...  1.079466   1.0    0.0  1.228732
540     1  0.495138  0.504862       1  ...  1.079726   1.0    0.0  1.229029
541     0  0.501765  0.498235       1  ...  1.083884   1.0    0.0  1.233761
542     0  0.528711  0.471289       1  ...  1.087848   1.0    0.0  1.238274
543     0  0.535683  0.464317       1  ...  1.090318   1.0    0.0  1.241085

[5 rows x 10 columns]
2023-01-16 00:00:46,281:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510825  0.489175       0  ...  1.079466   1.0    0.0  1.229323
46     1  0.494787  0.505213       1  ...  1.079726   1.0    0.0  1.228271
47     0  0.502051  0.497949       1  ...  1.083884   1.0    0.0  1.233001
48     0  0.528606  0.471394       1  ...  1.087848   1.0    0.0  1.239347
49     0  0.535683  0.464317       1  ...  1.090318   1.0    0.0  1.241085

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-16 00:00:01,423:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230115   231000    231959  1673795999  20817.1    20896  0.003785
572  20230115   232000    232959  1673796599    20896  20880.4 -0.000747
573  20230115   233000    233959  1673797199  20880.8  20868.2 -0.000584
574  20230115   234000    234959  1673797799  20868.2  20939.5  0.003417
575  20230115   235000    235959  1673798399  20938.8  20927.8 -0.000559
2023-01-16 00:00:01,423:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '44.518', 'enterprice': '20721.7', 'countrevence': '0', 'unrealprofit': '9050.5094', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20925', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-16 00:00:02,147:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-16 00:00:02,147:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 44.518, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41531F1673798402146I0L59'}
2023-01-16 00:00:02,174:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1160000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230115, closeTime:235959, close:20927.8, total:921566.1519594, mom:0.021338072492454785, thd:0.0, side:sell 
2023-01-16 00:00:02,314:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41531F1673798402146I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673798402256702, 'quantity': '44.518', 'price': '20925', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673798401625, 'updatetime': 1673798402256, 'tradetype': 'usdt', 'selfid': 41531, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673798402256, 'clientorderid': '41531F1673798402146I0L59', 'price': '20925', 'quantity': '44.518', 'commission': '931.53915', 'commissionasset': 'USDT', 'tradetime': 1673798402256, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673798402256}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-16 00:00:02,720:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41531F1673798402146I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673798402256702, 'quantity': '44.518', 'price': '20925', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673798401625, 'updatetime': 1673798402256, 'tradetype': 'usdt', 'selfid': 41531, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673798402256, 'clientorderid': '41531F1673798402146I0L59', 'price': '20925', 'quantity': '44.518', 'commission': '931.53915', 'commissionasset': 'USDT', 'tradetime': 1673798402256, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673798402256}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7400 

self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20925', self.close='20942.5'
2023-01-16 00:10:01,575:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20925', self.close='20942.5'
2023-01-16 00:10:01,640:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230115   232000    232959  1673796599    20896  20880.4 -0.000747
573  20230115   233000    233959  1673797199  20880.8  20868.2 -0.000584
574  20230115   234000    234959  1673797799  20868.2  20939.5  0.003417
575  20230115   235000    235959  1673798399  20938.8  20927.8 -0.000559
576  20230116   000000    000959  1673798999    20925  20942.5  0.000702
2023-01-16 00:10:01,641:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-15 23:50:00,573:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7400 

self.closeSec=1673798399, self.tradeDate='20230115', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='20938.8', self.close='20927.8'
127.0.0.1 - - [16/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-16 00:00:01,385:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673798399, self.tradeDate='20230115', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='20938.8', self.close='20927.8'
2023-01-16 00:00:01,446:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230115   231000    231959  1673795999  20817.1    20896
17420  20230115   232000    232959  1673796599    20896  20880.4
17421  20230115   233000    233959  1673797199  20880.8  20868.2
17422  20230115   234000    234959  1673797799  20868.2  20939.5
17423  20230115   235000    235959  1673798399  20938.8  20927.8
2023-01-16 00:00:01,446:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-16 00:00:01,560:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1160000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230115, closeTime:235959, close:20927.8, total:951537.2948681, pct_pre:-0.00220134099156466, thd:0.33987838604567094, side:sell 
127.0.0.1 - - [16/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7401 

self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20925', self.close='20942.5'
2023-01-16 00:10:01,594:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20925', self.close='20942.5'
2023-01-16 00:10:01,654:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230115   232000    232959  1673796599    20896  20880.4
17421  20230115   233000    233959  1673797199  20880.8  20868.2
17422  20230115   234000    234959  1673797799  20868.2  20939.5
17423  20230115   235000    235959  1673798399  20938.8  20927.8
17424  20230116   000000    000959  1673798999    20925  20942.5
2023-01-16 00:10:01,654:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-16 00:00:01,402:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230115   231000    231959  1673795999  20817.1    20896
12236  20230115   232000    232959  1673796599    20896  20880.4
12237  20230115   233000    233959  1673797199  20880.8  20868.2
12238  20230115   234000    234959  1673797799  20868.2  20939.5
12239  20230115   235000    235959  1673798399  20938.8  20927.8
2023-01-16 00:00:01,402:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.117', 'enterprice': '21002.2', 'countrevence': '0', 'unrealprofit': '-4177.8324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20925', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-16 00:00:02,678:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-16 00:00:02,679:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.117, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41532F1673798402348I0L2'}
2023-01-16 00:00:02,709:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1160000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230115, closeTime:235959, close:20927.8, total:1135439.4813426, corrDate:20221223, corrVal:0.772186770896512, side:sell 
2023-01-16 00:00:02,883:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41532F1673798402348I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673798402818626, 'quantity': '54.117', 'price': '20925', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673798401624, 'updatetime': 1673798402818, 'tradetype': 'usdt', 'selfid': 41532, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673798402818, 'clientorderid': '41532F1673798402348I0L2', 'price': '20925', 'quantity': '54.117', 'commission': '1132.398225', 'commissionasset': 'USDT', 'tradetime': 1673798402818, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673798402818}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-16 00:00:03,174:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41532F1673798402348I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673798402818626, 'quantity': '54.117', 'price': '20925', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673798401624, 'updatetime': 1673798402818, 'tradetype': 'usdt', 'selfid': 41532, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673798402818, 'clientorderid': '41532F1673798402348I0L2', 'price': '20925', 'quantity': '54.117', 'commission': '1132.398225', 'commissionasset': 'USDT', 'tradetime': 1673798402818, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673798402818}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7401 

self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='20925', self.close='20942.5'
2023-01-16 00:10:01,587:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='20925', self.close='20942.5'
2023-01-16 00:10:01,647:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230115   232000    232959  1673796599    20896  20880.4
12237  20230115   233000    233959  1673797199  20880.8  20868.2
12238  20230115   234000    234959  1673797799  20868.2  20939.5
12239  20230115   235000    235959  1673798399  20938.8  20927.8
12240  20230116   000000    000959  1673798999    20925  20942.5
2023-01-16 00:10:01,648:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [16/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10232
self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20956.3, self.close=20942.5, self.high=20976.1, self.low=20925.5, self.vol=2518.104, self.amt=52757358.5362 
2023-01-16 00:10:01,620:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230115   234500    234959  ...         0.0        0.0       0
5758  20230115   235000    235459  ...         0.0        0.0       0
5759  20230115   235500    235959  ...         0.0        0.0       0
5760  20230116   000000    000459  ...         0.0        0.0       0
5761  20230116   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 00:10:01,626:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673798999, self.tradeDate='20230116', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20956.3, self.close=20942.5, self.high=20976.1, self.low=20925.5, self.vol=2518.104, self.amt=52757358.5362, ukdf['pct'].iloc[-1]=-0.000721 , ukdf['amount'].iloc[-1]=52757358.5362, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10233
self.closeSec=1673799299, self.tradeDate='20230116', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20940.4, self.close=20951.3, self.high=20966.2, self.low=20933.2, self.vol=1575.512, self.amt=33007104.1079 
2023-01-16 00:15:00,783:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230115   235000    235459  ...         0.0        0.0       0
5759  20230115   235500    235959  ...         0.0        0.0       0
5760  20230116   000000    000459  ...         0.0        0.0       0
5761  20230116   000500    000959  ...         0.0        0.0       0
5762  20230116   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 00:15:00,795:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673799299, self.tradeDate='20230116', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20940.4, self.close=20951.3, self.high=20966.2, self.low=20933.2, self.vol=1575.512, self.amt=33007104.1079, ukdf['pct'].iloc[-1]=0.00042 , ukdf['amount'].iloc[-1]=33007104.1079, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230115   120000    155959  1673769599  ...    723  1.073325  0.800655     1.0
724  20230115   160000    195959  1673783999  ...    724  1.022775  0.672264     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '181489.51903624384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20737.35361069', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=308
self.closeSec=1673798399, self.tradeDate='20230115', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=20737.4, self.close=20927.8, self.high=21028.0, self.low=20661.1, self.vol=82799.747, self.amt=1724175209.68679 
127.0.0.1 - - [16/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-16 00:00:01,240:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673798399, self.tradeDate='20230115', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=20737.4, self.close=20927.8, self.high=21028.0, self.low=20661.1, self.vol=82799.747, self.amt=1724175209.68679 
2023-01-16 00:00:01,274:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230115   040000    075959  ...  59647.002  1.249465e+09  0.007890
722  20230115   080000    115959  ...  96643.658  2.005612e+09 -0.010795
723  20230115   120000    155959  ...  34775.593  7.212492e+08  0.000651
724  20230115   160000    195959  ...  63521.557  1.314180e+09 -0.000607
725  20230115   200000    235959  ...  82799.747  1.724175e+09  0.009181

[5 rows x 11 columns]
2023-01-16 00:00:04,178:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230115   040000    075959  1673740799  ...    721  1.161411  1.034070     1.0
722  20230115   080000    115959  1673755199  ...    722  1.134716  0.954694     1.0
723  20230115   120000    155959  1673769599  ...    723  1.073325  0.800655     1.0
724  20230115   160000    195959  1673783999  ...    724  1.022775  0.672264     1.0
725  20230115   200000    235959  1673798399  ...    725  0.985609  0.573577     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '191085.0048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20925', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


