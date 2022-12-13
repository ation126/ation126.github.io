# 20221214 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4730
self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17778.8, self.close=17781.7, self.high=17785.9, self.low=17770.0, self.vol=1130.853, self.amt=20107567.4976 
127.0.0.1 - - [14/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-14 00:10:01,522:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221213   234500    234959  ...         0.0        0.0       0
5758  20221213   235000    235459  ...         0.0        0.0       0
5759  20221213   235500    235959  ...         0.0        0.0       0
5760  20221214   000000    000459  ...         0.0        0.0       0
5761  20221214   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-14 00:10:01,524:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17778.8, self.close=17781.7, self.high=17785.9, self.low=17770.0, self.vol=1130.853, self.amt=20107567.4976, ukdf['pct'].iloc[-1]=0.000163 , ukdf['amount'].iloc[-1]=20107567.4976, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-75368.58142572736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17781.76911436', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4731
self.closeSec=1670948099, self.tradeDate='20221214', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17781.6, self.close=17808.5, self.high=17818.0, self.low=17779.1, self.vol=2511.058, self.amt=44690982.7713 
2022-12-14 00:15:00,641:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221213   235000    235459  ...         0.0        0.0       0
5759  20221213   235500    235959  ...         0.0        0.0       0
5760  20221214   000000    000459  ...         0.0        0.0       0
5761  20221214   000500    000959  ...         0.0        0.0       0
5762  20221214   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-14 00:15:00,641:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670948099, self.tradeDate='20221214', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17781.6, self.close=17808.5, self.high=17818.0, self.low=17779.1, self.vol=2511.058, self.amt=44690982.7713, ukdf['pct'].iloc[-1]=0.001507 , ukdf['amount'].iloc[-1]=44690982.7713, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-76977.1392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17808.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.31501838368318813, self.count=5296 

self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17778.8, self.close=17781.7, self.high=17785.9, self.low=17770.0 
2022-12-14 00:10:01,418:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17778.8, self.close=17781.7, self.high=17785.9, self.low=17770.0   
2022-12-14 00:10:01,470:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221213   234500    234959  1670946599  ...  17754.6 -0.000698   1725    3
1438  20221213   235000    235459  1670946899  ...  17745.0 -0.000242   1726    4
1439  20221213   235500    235959  1670947199  ...  17741.3 -0.000203   1727    5
1440  20221214   000000    000459  1670947499  ...  17749.5  0.001645   1440    0
1441  20221214   000500    000959  1670947799  ...  17770.0  0.000163   1441    1

[5 rows x 11 columns]
2022-12-14 00:10:01,471:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.31501838368318813, self.count=5297 

self.closeSec=1670948099, self.tradeDate='20221214', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17781.6, self.close=17808.5, self.high=17818.0, self.low=17779.1 
2022-12-14 00:15:00,534:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670948099, self.tradeDate='20221214', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17781.6, self.close=17808.5, self.high=17818.0, self.low=17779.1   
127.0.0.1 - - [14/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-14 00:15:00,623:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221213   235000    235459  1670946899  ...  17745.0 -0.000242   1726    4
1439  20221213   235500    235959  1670947199  ...  17741.3 -0.000203   1727    5
1440  20221214   000000    000459  1670947499  ...  17749.5  0.001645   1440    0
1441  20221214   000500    000959  1670947799  ...  17770.0  0.000163   1441    1
1442  20221214   001000    001459  1670948099  ...  17779.1  0.001507   1442    2

[5 rows x 11 columns]
2022-12-14 00:15:00,623:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-14 00:00:19,571:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221213    212959  17416.8  ...  54.166667  0.685015  0.243189
5803  20221213    215959  17601.2  ...  54.166667  0.760276  0.239297
5804  20221213    222959  17895.9  ...  54.583333  0.760528  0.235579
5805  20221213    225959  17897.5  ...  54.166667  0.745294  0.233831
5806  20221213    232959  17869.0  ...  53.750000  0.691898  0.239001

[5 rows x 33 columns]
0.5698529411764706
acc is : 0.5698529411764706
2022-12-14 00:00:19,674:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.538347  0.461653       1  ...  1.022349   1.0    0.0  1.056110
540     0  0.611373  0.388627       1  ...  1.022435   1.0    0.0  1.056199
541     0  0.545103  0.454897       0  ...  1.020806   1.0    0.0  1.054517
542     0  0.538246  0.461754       0  ...  1.014660   1.0    0.0  1.048167
543     0  0.511137  0.488863       0  ...  1.013980   1.0    0.0  1.047465

[5 rows x 10 columns]
2022-12-14 00:00:19,699:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.538572  0.461428       1  ...  1.022349   1.0    0.0  1.056753
46     0  0.611733  0.388267       1  ...  1.022435   1.0    0.0  1.058967
47     0  0.545506  0.454494       0  ...  1.020806   1.0    0.0  1.057281
48     0  0.538454  0.461546       0  ...  1.014660   1.0    0.0  1.049660
49     0  0.511137  0.488863       0  ...  1.013980   1.0    0.0  1.047465

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '20663.0252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17759.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-14 00:00:01,290:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221213   231000    231959  1670944799  17854.9  17790.2 -0.003624
572  20221213   232000    232959  1670945399  17792.2  17761.4 -0.001619
573  20221213   233000    233959  1670945999  17761.3  17738.1 -0.001312
574  20221213   234000    234959  1670946599    17738  17757.1  0.001071
575  20221213   235000    235959  1670947199  17757.4  17749.6 -0.000422
2022-12-14 00:00:01,290:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.1', 'enterprice': '17153.5', 'countrevence': '0', 'unrealprofit': '31647.6', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17749.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-14 00:00:02,179:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-14 00:00:02,179:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.1, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41352F1670947202174I0L59'}
2022-12-14 00:00:02,218:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12140000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221213, closeTime:235959, close:17749.6, total:909939.9991499999, mom:0.001402209146162292, thd:0.0, side:sell 
127.0.0.1 - - [14/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-14 00:00:02,506:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41352F1670947202174I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670947202295384, 'quantity': '53.1', 'price': '17749.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670947201458, 'updatetime': 1670947202295, 'tradetype': 'usdt', 'selfid': 41352, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670947202295, 'clientorderid': '41352F1670947202174I0L59', 'price': '17749.5', 'quantity': '53.1', 'commission': '942.49845', 'commissionasset': 'USDT', 'tradetime': 1670947202295, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670947202295}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-14 00:00:02,758:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41352F1670947202174I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670947202295384, 'quantity': '53.1', 'price': '17749.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670947201458, 'updatetime': 1670947202295, 'tradetype': 'usdt', 'selfid': 41352, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670947202295, 'clientorderid': '41352F1670947202174I0L59', 'price': '17749.5', 'quantity': '53.1', 'commission': '942.49845', 'commissionasset': 'USDT', 'tradetime': 1670947202295, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670947202295}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2648 

self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17749.5', self.close='17781.7'
2022-12-14 00:10:01,557:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17749.5', self.close='17781.7'
2022-12-14 00:10:01,604:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221213   232000    232959  1670945399  17792.2  17761.4 -0.001619
573  20221213   233000    233959  1670945999  17761.3  17738.1 -0.001312
574  20221213   234000    234959  1670946599    17738  17757.1  0.001071
575  20221213   235000    235959  1670947199  17757.4  17749.6 -0.000422
576  20221214   000000    000959  1670947799  17749.5  17781.7  0.001808
2022-12-14 00:10:01,604:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-13 23:50:00,573:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2648 

self.closeSec=1670947199, self.tradeDate='20221213', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='17757.4', self.close='17749.6'
2022-12-14 00:00:01,242:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670947199, self.tradeDate='20221213', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='17757.4', self.close='17749.6'
2022-12-14 00:00:01,283:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221213   231000    231959  1670944799  17854.9  17790.2
17420  20221213   232000    232959  1670945399  17792.2  17761.4
17421  20221213   233000    233959  1670945999  17761.3  17738.1
17422  20221213   234000    234959  1670946599    17738  17757.1
17423  20221213   235000    235959  1670947199  17757.4  17749.6
2022-12-14 00:00:01,284:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-14 00:00:01,395:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12140000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221213, closeTime:235959, close:17749.6, total:935796.4056934, pct_pre:0.024726631393297893, thd:-0.3140665471544874, side:sell 
127.0.0.1 - - [14/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2649 

self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17749.5', self.close='17781.7'
2022-12-14 00:10:01,584:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17749.5', self.close='17781.7'
2022-12-14 00:10:01,612:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221213   232000    232959  1670945399  17792.2  17761.4
17421  20221213   233000    233959  1670945999  17761.3  17738.1
17422  20221213   234000    234959  1670946599    17738  17757.1
17423  20221213   235000    235959  1670947199  17757.4  17749.6
17424  20221214   000000    000959  1670947799  17749.5  17781.7
2022-12-14 00:10:01,612:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-14 00:00:01,297:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221213   231000    231959  1670944799  17854.9  17790.2
12236  20221213   232000    232959  1670945399  17792.2  17761.4
12237  20221213   233000    233959  1670945999  17761.3  17738.1
12238  20221213   234000    234959  1670946599    17738  17757.1
12239  20221213   235000    235959  1670947199  17757.4  17749.6
2022-12-14 00:00:01,302:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.652', 'enterprice': '17148.1', 'countrevence': '0', 'unrealprofit': '-45497.1128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17749.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-14 00:00:02,142:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-14 00:00:02,142:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.652, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41351F1670947202141I0L2'}
2022-12-14 00:00:02,178:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12140000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221213, closeTime:235959, close:17749.6, total:1295990.7731388, corrDate:20221203, corrVal:0.8778594337092437, side:buy 
127.0.0.1 - - [14/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-14 00:00:02,278:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41351F1670947202141I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670947202243392, 'quantity': '75.652', 'price': '17749.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670947201514, 'updatetime': 1670947202243, 'tradetype': 'usdt', 'selfid': 41351, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670947202243, 'clientorderid': '41351F1670947202141I0L2', 'price': '17749.6', 'quantity': '75.652', 'commission': '1342.7927392', 'commissionasset': 'USDT', 'tradetime': 1670947202243, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670947202243}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-14 00:00:02,499:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41351F1670947202141I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670947202243392, 'quantity': '75.652', 'price': '17749.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670947201514, 'updatetime': 1670947202243, 'tradetype': 'usdt', 'selfid': 41351, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670947202243, 'clientorderid': '41351F1670947202141I0L2', 'price': '17749.6', 'quantity': '75.652', 'commission': '1342.7927392', 'commissionasset': 'USDT', 'tradetime': 1670947202243, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670947202243}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2649 

self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17749.5', self.close='17781.7'
2022-12-14 00:10:01,578:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17749.5', self.close='17781.7'
2022-12-14 00:10:01,609:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221213   232000    232959  1670945399  17792.2  17761.4
12237  20221213   233000    233959  1670945999  17761.3  17738.1
12238  20221213   234000    234959  1670946599    17738  17757.1
12239  20221213   235000    235959  1670947199  17757.4  17749.6
12240  20221214   000000    000959  1670947799  17749.5  17781.7
2022-12-14 00:10:01,609:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=728
self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17778.8, self.close=17781.7, self.high=17785.9, self.low=17770.0, self.vol=1130.853, self.amt=20107567.4976 
127.0.0.1 - - [14/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-14 00:10:01,512:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221213   234500    234959  ...    0.409698   0.285107       0
5758  20221213   235000    235459  ...    0.409302   0.285148       0
5759  20221213   235500    235959  ...    0.408909   0.285191       0
5760  20221214   000000    000459  ...    0.408515   0.285234       0
5761  20221214   000500    000959  ...    0.408120   0.285274       0

[5 rows x 18 columns]
2022-12-14 00:10:01,518:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670947799, self.tradeDate='20221214', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17778.8, self.close=17781.7, self.high=17785.9, self.low=17770.0, self.vol=1130.853, self.amt=20107567.4976, ukdf['pct'].iloc[-1]=0.000163 , ukdf['amount'].iloc[-1]=20107567.4976, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.40812010072176824, signal=0, value_std=0.28527421638305683 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=729
self.closeSec=1670948099, self.tradeDate='20221214', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17781.6, self.close=17808.5, self.high=17818.0, self.low=17779.1, self.vol=2511.058, self.amt=44690982.7713 
127.0.0.1 - - [14/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-14 00:15:00,644:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221213   235000    235459  ...    0.409302   0.285148       0
5759  20221213   235500    235959  ...    0.408909   0.285191       0
5760  20221214   000000    000459  ...    0.408515   0.285234       0
5761  20221214   000500    000959  ...    0.408120   0.285274       0
5762  20221214   001000    001459  ...    0.407724   0.285313       0

[5 rows x 18 columns]
2022-12-14 00:15:00,645:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670948099, self.tradeDate='20221214', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17781.6, self.close=17808.5, self.high=17818.0, self.low=17779.1, self.vol=2511.058, self.amt=44690982.7713, ukdf['pct'].iloc[-1]=0.001507 , ukdf['amount'].iloc[-1]=44690982.7713, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.40772420430970097, signal=0, value_std=0.2853128793894278 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

722  20221213   080000    115959  ...   36929.287  6.334437e+08 -0.003302
723  20221213   120000    155959  ...   55625.343  9.536149e+08  0.000805
724  20221213   160000    195959  ...  122406.120  2.125053e+09  0.016308
725  20221213   200000    235959  ...  263218.863  4.674095e+09  0.017933

[5 rows x 11 columns]
2022-12-14 00:00:02,848:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221213   040000    075959  1670889599  ...    721  0.362269 -0.663837    -1.0
722  20221213   080000    115959  1670903999  ...    722  0.345440 -0.749277    -1.0
723  20221213   120000    155959  1670918399  ...    723  0.315132 -0.874432    -1.0
724  20221213   160000    195959  1670932799  ...    724  0.365657 -0.678358    -1.0
725  20221213   200000    235959  1670947199  ...    725  1.615970  3.841313     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.578', 'enterprice': '16978.7', 'countrevence': '0', 'unrealprofit': '-45151.9224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17749.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.578', 'enterprice': '16978.7', 'countrevence': '0', 'unrealprofit': '-45151.9224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17749.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-14 00:00:08,661:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '951324.6448793', 'total': '951324.6448793', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2022-12-14 00:00:08,877:DEBUG:s_rsrs:main.py:253:openBuy:185271: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2022-12-14 00:00:08,878:INFO:s_rsrs:main.py:254:openBuy:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 53.436, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41354F1670947208877I0L65'}
2022-12-14 00:00:08,895:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:12140000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20221213, closeTime:235959, close:17749.5, sign:1, total:951324.6448793, side:buy  
127.0.0.1 - - [14/Dec/2022 00:00:08] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Dec/2022 00:00:08] "POST / HTTP/1.1" 200 -
2022-12-14 00:00:08,898:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41353F1670947203571I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670947203669687, 'quantity': '58.578', 'price': '17749.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670947203108, 'updatetime': 1670947203669, 'tradetype': 'usdt', 'selfid': 41353, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670947203669, 'clientorderid': '41353F1670947203571I0L65', 'price': '17749.6', 'quantity': '58.578', 'commission': '1039.7360688', 'commissionasset': 'USDT', 'tradetime': 1670947203669, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670947203669}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-14 00:00:08,899:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41353F1670947203571I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670947203669687, 'quantity': '58.578', 'price': '17749.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670947203108, 'updatetime': 1670947203669, 'tradetype': 'usdt', 'selfid': 41353, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670947203669, 'clientorderid': '41353F1670947203571I0L65', 'price': '17749.6', 'quantity': '58.578', 'commission': '1039.7360688', 'commissionasset': 'USDT', 'tradetime': 1670947203669, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670947203669}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Dec/2022 00:00:08] "POST / HTTP/1.1" 200 -
2022-12-14 00:00:08,990:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41354F1670947208877I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670947208975509, 'quantity': '53.436', 'price': '17756.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670947208672, 'updatetime': 1670947208975, 'tradetype': 'usdt', 'selfid': 41354, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670947208975, 'clientorderid': '41354F1670947208877I0L65', 'price': '17756.3', 'quantity': '53.436', 'commission': '948.8256468', 'commissionasset': 'USDT', 'tradetime': 1670947208975, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670947208975}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-14 00:00:09,183:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41354F1670947208877I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670947208975509, 'quantity': '53.436', 'price': '17756.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670947208672, 'updatetime': 1670947208975, 'tradetype': 'usdt', 'selfid': 41354, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670947208975, 'clientorderid': '41354F1670947208877I0L65', 'price': '17756.3', 'quantity': '53.436', 'commission': '948.8256468', 'commissionasset': 'USDT', 'tradetime': 1670947208975, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670947208975}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Dec/2022 00:00:09] "POST / HTTP/1.1" 200 -


