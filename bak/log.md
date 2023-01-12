# 20230113 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13370
self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=18063.1, self.close=18069.2, self.high=18080.1, self.low=18055.3, self.vol=1433.262, self.amt=25895457.704 
127.0.0.1 - - [13/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 00:10:01,599:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230112   234500    234959  ...         0.0        0.0       0
5758  20230112   235000    235459  ...         0.0        0.0       0
5759  20230112   235500    235959  ...         0.0        0.0       0
5760  20230113   000000    000459  ...         0.0        0.0       0
5761  20230113   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 00:10:01,600:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=18063.1, self.close=18069.2, self.high=18080.1, self.low=18055.3, self.vol=1433.262, self.amt=25895457.704, ukdf['pct'].iloc[-1]=0.000332 , ukdf['amount'].iloc[-1]=25895457.704, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-92713.1632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18070', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13371
self.closeSec=1673540099, self.tradeDate='20230113', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=18069.4, self.close=18092.1, self.high=18092.7, self.low=18053.4, self.vol=1576.727, self.amt=28492740.5702 
127.0.0.1 - - [13/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-13 00:15:00,675:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230112   235000    235459  ...         0.0        0.0       0
5759  20230112   235500    235959  ...         0.0        0.0       0
5760  20230113   000000    000459  ...         0.0        0.0       0
5761  20230113   000500    000959  ...         0.0        0.0       0
5762  20230113   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 00:15:00,678:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673540099, self.tradeDate='20230113', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=18069.4, self.close=18092.1, self.high=18092.7, self.low=18053.4, self.vol=1576.727, self.amt=28492740.5702, ukdf['pct'].iloc[-1]=0.001267 , ukdf['amount'].iloc[-1]=28492740.5702, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-94043.0528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18092.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=239, self.factor=0.22754939246608602, self.count=13936 

self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=18063.1, self.close=18069.2, self.high=18080.1, self.low=18055.3 
2023-01-13 00:10:01,414:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=18063.1, self.close=18069.2, self.high=18080.1, self.low=18055.3   
2023-01-13 00:10:01,493:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230112   234500    234959  1673538599  ...  18067.3  0.000697   1725    3
1438  20230112   235000    235459  1673538899  ...  18082.2  0.000188   1726    4
1439  20230112   235500    235959  1673539199  ...  18077.6 -0.001078   1727    5
1440  20230113   000000    000459  1673539499  ...  18045.7 -0.000797   1440    0
1441  20230113   000500    000959  1673539799  ...  18055.3  0.000332   1441    1

[5 rows x 11 columns]
2023-01-13 00:10:01,494:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=239, self.factor=0.22754939246608602, self.count=13937 

self.closeSec=1673540099, self.tradeDate='20230113', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=18069.4, self.close=18092.1, self.high=18092.7, self.low=18053.4 
2023-01-13 00:15:00,547:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673540099, self.tradeDate='20230113', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=18069.4, self.close=18092.1, self.high=18092.7, self.low=18053.4   
2023-01-13 00:15:00,625:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230112   235000    235459  1673538899  ...  18082.2  0.000188   1726    4
1439  20230112   235500    235959  1673539199  ...  18077.6 -0.001078   1727    5
1440  20230113   000000    000459  1673539499  ...  18045.7 -0.000797   1440    0
1441  20230113   000500    000959  1673539799  ...  18055.3  0.000332   1441    1
1442  20230113   001000    001459  1673540099  ...  18053.4  0.001267   1442    2

[5 rows x 11 columns]
2023-01-13 00:15:00,625:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-13 00:00:32,962:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230112    212959  18263.3  ...  56.666667  0.687439  0.210751
5803  20230112    215959  18178.9  ...  57.083333  0.698274  0.204649
5804  20230112    222959  18277.7  ...  56.666667  0.635437  0.209259
5805  20230112    225959  18142.7  ...  56.250000  0.577844  0.224415
5806  20230112    232959  17989.7  ...  56.250000  0.599303  0.233462

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-01-13 00:00:33,121:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.510210  0.489790       1  ...  1.017433   1.0  0.0000  1.106419
540     0  0.534240  0.465760       0  ...  1.009746   1.0  0.0000  1.098059
541     1  0.474262  0.525738       0  ...  1.001402   1.0  0.0000  1.088985
542     1  0.447326  0.552674       1  ...  0.994968  -1.0 -0.0016  1.094240
543     0  0.501632  0.498368       1  ...  0.994901  -1.0  0.0000  1.094312

[5 rows x 10 columns]
2023-01-13 00:00:33,156:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.509508  0.490492       1  ...  1.017433   1.0  0.0000  1.105034
46     0  0.533961  0.466039       0  ...  1.009746   1.0  0.0000  1.097017
47     1  0.474112  0.525888       0  ...  1.001402   1.0  0.0000  1.087951
48     1  0.447529  0.552471       1  ...  0.994968  -1.0 -0.0016  1.094591
49     0  0.501632  0.498368       1  ...  0.994901  -1.0  0.0000  1.094312

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.438', 'enterprice': '18059.5', 'countrevence': '0', 'unrealprofit': '-514.842920262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18071.631649', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-13 00:00:01,160:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230112   231000    231959  1673536799  18038.2  18108.5  0.003897
572  20230112   232000    232959  1673537399  18108.5  18076.4 -0.001773
573  20230112   233000    233959  1673537999  18072.5  18119.7  0.002395
574  20230112   234000    234959  1673538599  18119.8  18093.7 -0.001435
575  20230112   235000    235959  1673539199  18093.7  18077.6 -0.000890
2023-01-13 00:00:01,160:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.518', 'enterprice': '18220', 'countrevence': '0', 'unrealprofit': '-6948.26981152902', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18082.45952311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-13 00:00:01,739:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-13 00:00:01,740:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 50.518, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41516F1673539201739I0L59'}
2023-01-13 00:00:01,778:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1130000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230112, closeTime:235959, close:18077.6, total:919517.52204, mom:0.01498087909997059, thd:0.0, side:sell 
127.0.0.1 - - [13/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-13 00:00:01,898:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41516F1673539201739I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673539201859399, 'quantity': '50.518', 'price': '18077.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673539201353, 'updatetime': 1673539201859, 'tradetype': 'usdt', 'selfid': 41516, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673539201859, 'clientorderid': '41516F1673539201739I0L59', 'price': '18077.6', 'quantity': '50.518', 'commission': '913.2441968', 'commissionasset': 'USDT', 'tradetime': 1673539201859, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673539201859}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-13 00:00:02,147:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41516F1673539201739I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673539201859399, 'quantity': '50.518', 'price': '18077.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673539201353, 'updatetime': 1673539201859, 'tradetype': 'usdt', 'selfid': 41516, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673539201859, 'clientorderid': '41516F1673539201739I0L59', 'price': '18077.6', 'quantity': '50.518', 'commission': '913.2441968', 'commissionasset': 'USDT', 'tradetime': 1673539201859, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673539201859}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6968 

self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='18077.6', self.close='18069.2'
2023-01-13 00:10:01,549:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='18077.6', self.close='18069.2'
127.0.0.1 - - [13/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 00:10:01,577:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230112   232000    232959  1673537399  18108.5  18076.4 -0.001773
573  20230112   233000    233959  1673537999  18072.5  18119.7  0.002395
574  20230112   234000    234959  1673538599  18119.8  18093.7 -0.001435
575  20230112   235000    235959  1673539199  18093.7  18077.6 -0.000890
576  20230113   000000    000959  1673539799  18077.6  18069.2 -0.000465
2023-01-13 00:10:01,581:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-12 23:50:00,559:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6968 

self.closeSec=1673539199, self.tradeDate='20230112', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='18093.7', self.close='18077.6'
2023-01-13 00:00:01,111:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673539199, self.tradeDate='20230112', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='18093.7', self.close='18077.6'
2023-01-13 00:00:01,157:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230112   231000    231959  1673536799  18038.2  18108.5
17420  20230112   232000    232959  1673537399  18108.5  18076.4
17421  20230112   233000    233959  1673537999  18072.5  18119.7
17422  20230112   234000    234959  1673538599  18119.8  18093.7
17423  20230112   235000    235959  1673539199  18093.7  18077.6
2023-01-13 00:00:01,157:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-13 00:00:01,340:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1130000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230112, closeTime:235959, close:18077.6, total:935155.1559053, pct_pre:0.04739932402034852, thd:-1.1351982635005717, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6969 

self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='18077.6', self.close='18069.2'
2023-01-13 00:10:01,529:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='18077.6', self.close='18069.2'
127.0.0.1 - - [13/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 00:10:01,591:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230112   232000    232959  1673537399  18108.5  18076.4
17421  20230112   233000    233959  1673537999  18072.5  18119.7
17422  20230112   234000    234959  1673538599  18119.8  18093.7
17423  20230112   235000    235959  1673539199  18093.7  18077.6
17424  20230113   000000    000959  1673539799  18077.6  18069.2
2023-01-13 00:10:01,591:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-13 00:00:01,203:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230112   231000    231959  1673536799  18038.2  18108.5
12236  20230112   232000    232959  1673537399  18108.5  18076.4
12237  20230112   233000    233959  1673537999  18072.5  18119.7
12238  20230112   234000    234959  1673538599  18119.8  18093.7
12239  20230112   235000    235959  1673539199  18093.7  18077.6
2023-01-13 00:00:01,208:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '71.692', 'enterprice': '17548', 'countrevence': '0', 'unrealprofit': '-38316.47213080212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18082.45952311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-13 00:00:02,131:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-13 00:00:02,131:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 71.692, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41517F1673539201986I0L2'}
2023-01-13 00:00:02,150:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1130000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230112, closeTime:235959, close:18077.6, total:1256793.1647839998, corrDate:20230111, corrVal:0.9338460636604162, side:buy 
127.0.0.1 - - [13/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-13 00:00:02,293:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41517F1673539201986I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673539202249826, 'quantity': '71.692', 'price': '18077.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673539201658, 'updatetime': 1673539202249, 'tradetype': 'usdt', 'selfid': 41517, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673539202249, 'clientorderid': '41517F1673539201986I0L2', 'price': '18077.7', 'quantity': '71.692', 'commission': '1296.0264684', 'commissionasset': 'USDT', 'tradetime': 1673539202249, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673539202249}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-13 00:00:02,483:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41517F1673539201986I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673539202249826, 'quantity': '71.692', 'price': '18077.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673539201658, 'updatetime': 1673539202249, 'tradetype': 'usdt', 'selfid': 41517, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673539202249, 'clientorderid': '41517F1673539201986I0L2', 'price': '18077.7', 'quantity': '71.692', 'commission': '1296.0264684', 'commissionasset': 'USDT', 'tradetime': 1673539202249, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673539202249}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6969 

self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='18077.6', self.close='18069.2'
2023-01-13 00:10:01,527:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='18077.6', self.close='18069.2'
127.0.0.1 - - [13/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 00:10:01,587:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230112   232000    232959  1673537399  18108.5  18076.4
12237  20230112   233000    233959  1673537999  18072.5  18119.7
12238  20230112   234000    234959  1673538599  18119.8  18093.7
12239  20230112   235000    235959  1673539199  18093.7  18077.6
12240  20230113   000000    000959  1673539799  18077.6  18069.2
2023-01-13 00:10:01,587:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9368
self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=18063.1, self.close=18069.2, self.high=18080.1, self.low=18055.3, self.vol=1433.262, self.amt=25895457.704 
2023-01-13 00:10:01,472:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230112   234500    234959  ...         0.0        0.0       0
5758  20230112   235000    235459  ...         0.0        0.0       0
5759  20230112   235500    235959  ...         0.0        0.0       0
5760  20230113   000000    000459  ...         0.0        0.0       0
5761  20230113   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 00:10:01,472:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673539799, self.tradeDate='20230113', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=18063.1, self.close=18069.2, self.high=18080.1, self.low=18055.3, self.vol=1433.262, self.amt=25895457.704, ukdf['pct'].iloc[-1]=0.000332 , ukdf['amount'].iloc[-1]=25895457.704, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9369
self.closeSec=1673540099, self.tradeDate='20230113', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=18069.4, self.close=18092.1, self.high=18092.7, self.low=18053.4, self.vol=1576.727, self.amt=28492740.5702 
127.0.0.1 - - [13/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-13 00:15:00,674:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230112   235000    235459  ...         0.0        0.0       0
5759  20230112   235500    235959  ...         0.0        0.0       0
5760  20230113   000000    000459  ...         0.0        0.0       0
5761  20230113   000500    000959  ...         0.0        0.0       0
5762  20230113   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 00:15:00,678:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673540099, self.tradeDate='20230113', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=18069.4, self.close=18092.1, self.high=18092.7, self.low=18053.4, self.vol=1576.727, self.amt=28492740.5702, ukdf['pct'].iloc[-1]=0.001267 , ukdf['amount'].iloc[-1]=28492740.5702, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230112   120000    155959  1673510399  ...    723  1.335643  2.179508     1.0
724  20230112   160000    195959  1673524799  ...    724  1.209428  1.770281     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '51432.5888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18194', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=290
self.closeSec=1673539199, self.tradeDate='20230112', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=18194.4, self.close=18077.6, self.high=18377.4, self.low=17907.3, self.vol=322077.456, self.amt=5844743995.60805 
127.0.0.1 - - [13/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
2023-01-13 00:00:00,985:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673539199, self.tradeDate='20230112', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=18194.4, self.close=18077.6, self.high=18377.4, self.low=17907.3, self.vol=322077.456, self.amt=5844743995.60805 
2023-01-13 00:00:01,051:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230112   040000    075959  ...  144426.875  2.562553e+09  0.022519
722  20230112   080000    115959  ...  167796.454  3.045955e+09  0.015701
723  20230112   120000    155959  ...   51547.124  9.355653e+08 -0.004825
724  20230112   160000    195959  ...   45869.521  8.326695e+08  0.003596
725  20230112   200000    235959  ...  322077.456  5.844744e+09 -0.006425

[5 rows x 11 columns]
2023-01-13 00:00:03,549:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230112   040000    075959  1673481599  ...    721  1.297732  2.310525     1.0
722  20230112   080000    115959  1673495999  ...    722  1.606024  3.041440     1.0
723  20230112   120000    155959  1673510399  ...    723  1.335643  2.179508     1.0
724  20230112   160000    195959  1673524799  ...    724  1.209428  1.770281     1.0
725  20230112   200000    235959  1673539199  ...    725  1.297220  1.946828     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '45711.73902433088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18082.12480883', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


