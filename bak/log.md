# 20221224 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [24/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7610
self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16819.8, self.close=16829.8, self.high=16831.0, self.low=16814.0, self.vol=879.621, self.amt=14798119.3415 
2022-12-24 00:10:01,452:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221223   234500    234959  ...         0.0        0.0       0
5758  20221223   235000    235459  ...         0.0        0.0       0
5759  20221223   235500    235959  ...         0.0        0.0       0
5760  20221224   000000    000459  ...         0.0        0.0       0
5761  20221224   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 00:10:01,452:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16819.8, self.close=16829.8, self.high=16831.0, self.low=16814.0, self.vol=879.621, self.amt=14798119.3415, ukdf['pct'].iloc[-1]=0.000523 , ukdf['amount'].iloc[-1]=14798119.3415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-18082.888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16829.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--: 127.0.0.1 - - [24/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7611
self.closeSec=1671812099, self.tradeDate='20221224', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16829.8, self.close=16828.4, self.high=16837.2, self.low=16828.4, self.vol=828.179, self.amt=13941076.7556 
2022-12-24 00:15:00,582:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221223   235000    235459  ...         0.0        0.0       0
5759  20221223   235500    235959  ...         0.0        0.0       0
5760  20221224   000000    000459  ...         0.0        0.0       0
5761  20221224   000500    000959  ...         0.0        0.0       0
5762  20221224   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 00:15:00,583:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671812099, self.tradeDate='20221224', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16829.8, self.close=16828.4, self.high=16837.2, self.low=16828.4, self.vol=828.179, self.amt=13941076.7556, ukdf['pct'].iloc[-1]=-8.3e-05 , ukdf['amount'].iloc[-1]=13941076.7556, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17998.6416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16828.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=118, self.factor=0.3059004008743723, self.count=8176 

self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16819.8, self.close=16829.8, self.high=16831.0, self.low=16814.0 
2022-12-24 00:10:01,449:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16819.8, self.close=16829.8, self.high=16831.0, self.low=16814.0   
2022-12-24 00:10:01,487:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221223   234500    234959  1671810599  ...  16849.9 -0.000759   1725    3
1438  20221223   235000    235459  1671810899  ...  16830.1 -0.001032   1726    4
1439  20221223   235500    235959  1671811199  ...  16820.0 -0.000677   1727    5
1440  20221224   000000    000459  1671811499  ...  16812.0 -0.000291   1440    0
1441  20221224   000500    000959  1671811799  ...  16814.0  0.000523   1441    1

[5 rows x 11 columns]
2022-12-24 00:10:01,487:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=118, self.factor=0.3059004008743723, self.count=8177 

self.closeSec=1671812099, self.tradeDate='20221224', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16829.8, self.close=16828.4, self.high=16837.2, self.low=16828.4 
2022-12-24 00:15:00,533:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671812099, self.tradeDate='20221224', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16829.8, self.close=16828.4, self.high=16837.2, self.low=16828.4   
2022-12-24 00:15:00,582:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221223   235000    235459  1671810899  ...  16830.1 -0.001032   1726    4
1439  20221223   235500    235959  1671811199  ...  16820.0 -0.000677   1727    5
1440  20221224   000000    000459  1671811499  ...  16812.0 -0.000291   1440    0
1441  20221224   000500    000959  1671811799  ...  16814.0  0.000523   1441    1
1442  20221224   001000    001459  1671812099  ...  16828.4 -0.000083   1442    2

[5 rows x 11 columns]
2022-12-24 00:15:00,582:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-24 00:00:20,603:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5802  20221223    212959  16864.7  ...    48.75  0.522183  0.215239
5803  20221223    215959  16830.0  ...    48.75  0.521201  0.221703
5804  20221223    222959  16833.5  ...    48.75  0.496373  0.235987
5805  20221223    225959  16794.4  ...    48.75  0.489526  0.253859
5806  20221223    232959  16781.1  ...    48.75  0.518394  0.263093

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2022-12-24 00:00:20,725:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.489749  0.510251       0  ...  1.100137   1.0    0.0  0.995135
540     1  0.496462  0.503538       0  ...  1.097412   1.0    0.0  0.992670
541     1  0.483532  0.516468       0  ...  1.096628   1.0    0.0  0.991960
542     1  0.486730  0.513270       1  ...  1.099967   1.0    0.0  0.994981
543     0  0.505992  0.494008       0  ...  1.099614   1.0    0.0  0.994662

[5 rows x 10 columns]
2022-12-24 00:00:20,749:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489636  0.510364       0  ...  1.100137   1.0    0.0  0.994365
46     1  0.495914  0.504086       0  ...  1.097412   1.0    0.0  0.991802
47     1  0.483157  0.516843       0  ...  1.096628   1.0    0.0  0.991093
48     1  0.486424  0.513576       1  ...  1.099967   1.0    0.0  0.994946
49     0  0.505992  0.494008       0  ...  1.099614   1.0    0.0  0.994662

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5252.208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16825', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-24 00:00:01,195:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221223   231000    231959  1671808799  16801.6  16838.3  0.002184
572  20221223   232000    232959  1671809399  16838.3  16831.3 -0.000416
573  20221223   233000    233959  1671809999  16831.3  16880.1  0.002899
574  20221223   234000    234959  1671810599    16880  16854.7 -0.001505
575  20221223   235000    235959  1671811199  16854.6  16825.9 -0.001709
2022-12-24 00:00:01,200:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.473', 'enterprice': '16827.8', 'countrevence': '0', 'unrealprofit': '-105.3987', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16825.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-24 00:00:01,977:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-24 00:00:01,978:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.473, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41408F1671811201976I0L59'}
2022-12-24 00:00:02,016:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12240000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221223, closeTime:235959, close:16825.9, total:932555.0608505999, mom:0.004898149294097154, thd:0.0, side:sell 
2022-12-24 00:00:02,111:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41408F1671811201976I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671811202079385, 'quantity': '55.473', 'price': '16825.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671811201512, 'updatetime': 1671811202079, 'tradetype': 'usdt', 'selfid': 41408, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671811202079, 'clientorderid': '41408F1671811201976I0L59', 'price': '16825.9', 'quantity': '55.473', 'commission': '933.3831507', 'commissionasset': 'USDT', 'tradetime': 1671811202079, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671811202079}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-24 00:00:02,392:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41408F1671811201976I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671811202079385, 'quantity': '55.473', 'price': '16825.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671811201512, 'updatetime': 1671811202079, 'tradetype': 'usdt', 'selfid': 41408, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671811202079, 'clientorderid': '41408F1671811201976I0L59', 'price': '16825.9', 'quantity': '55.473', 'commission': '933.3831507', 'commissionasset': 'USDT', 'tradetime': 1671811202079, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671811202079}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4088 

self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16826', self.close='16829.8'
2022-12-24 00:10:01,531:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16826', self.close='16829.8'
127.0.0.1 - - [24/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-24 00:10:01,552:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221223   232000    232959  1671809399  16838.3  16831.3 -0.000416
573  20221223   233000    233959  1671809999  16831.3  16880.1  0.002899
574  20221223   234000    234959  1671810599    16880  16854.7 -0.001505
575  20221223   235000    235959  1671811199  16854.6  16825.9 -0.001709
576  20221224   000000    000959  1671811799    16826  16829.8  0.000232
2022-12-24 00:10:01,552:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-23 23:50:00,597:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4088 

self.closeSec=1671811199, self.tradeDate='20221223', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16854.6', self.close='16825.9'
2022-12-24 00:00:01,120:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671811199, self.tradeDate='20221223', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16854.6', self.close='16825.9'
2022-12-24 00:00:01,151:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221223   231000    231959  1671808799  16801.6  16838.3
17420  20221223   232000    232959  1671809399  16838.3  16831.3
17421  20221223   233000    233959  1671809999  16831.3  16880.1
17422  20221223   234000    234959  1671810599    16880  16854.7
17423  20221223   235000    235959  1671811199  16854.6  16825.9
2022-12-24 00:00:01,151:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-24 00:00:01,288:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12240000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221223, closeTime:235959, close:16825.9, total:946635.6384771, pct_pre:0.012242345527575527, thd:-0.5937646275755248, side:sell 
127.0.0.1 - - [24/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4089 

self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16826', self.close='16829.8'
2022-12-24 00:10:01,562:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16826', self.close='16829.8'
2022-12-24 00:10:01,568:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221223   232000    232959  1671809399  16838.3  16831.3
17421  20221223   233000    233959  1671809999  16831.3  16880.1
17422  20221223   234000    234959  1671810599    16880  16854.7
17423  20221223   235000    235959  1671811199  16854.6  16825.9
17424  20221224   000000    000959  1671811799    16826  16829.8
2022-12-24 00:10:01,568:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-24 00:00:01,208:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221223   231000    231959  1671808799  16801.6  16838.3
12236  20221223   232000    232959  1671809399  16838.3  16831.3
12237  20221223   233000    233959  1671809999  16831.3  16880.1
12238  20221223   234000    234959  1671810599    16880  16854.7
12239  20221223   235000    235959  1671811199  16854.6  16825.9
2022-12-24 00:00:01,213:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '74.972', 'enterprice': '16795.3', 'countrevence': '0', 'unrealprofit': '2294.1432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16825.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-24 00:00:02,367:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-24 00:00:02,368:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 74.972, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41409F1671811202327I0L2'}
2022-12-24 00:00:02,406:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12240000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221223, closeTime:235959, close:16825.9, total:1257918.0543683998, corrDate:20221213, corrVal:0.9197684710902347, side:sell 
127.0.0.1 - - [24/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-24 00:00:02,513:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41409F1671811202327I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671811202467508, 'quantity': '74.972', 'price': '16825.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671811201560, 'updatetime': 1671811202467, 'tradetype': 'usdt', 'selfid': 41409, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671811202467, 'clientorderid': '41409F1671811202327I0L2', 'price': '16825.9', 'quantity': '74.972', 'commission': '1261.4713748', 'commissionasset': 'USDT', 'tradetime': 1671811202467, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671811202467}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-24 00:00:02,766:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41409F1671811202327I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671811202467508, 'quantity': '74.972', 'price': '16825.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671811201560, 'updatetime': 1671811202467, 'tradetype': 'usdt', 'selfid': 41409, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671811202467, 'clientorderid': '41409F1671811202327I0L2', 'price': '16825.9', 'quantity': '74.972', 'commission': '1261.4713748', 'commissionasset': 'USDT', 'tradetime': 1671811202467, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671811202467}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4089 

self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16826', self.close='16829.8'
2022-12-24 00:10:01,525:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16826', self.close='16829.8'
2022-12-24 00:10:01,555:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221223   232000    232959  1671809399  16838.3  16831.3
12237  20221223   233000    233959  1671809999  16831.3  16880.1
12238  20221223   234000    234959  1671810599    16880  16854.7
12239  20221223   235000    235959  1671811199  16854.6  16825.9
12240  20221224   000000    000959  1671811799    16826  16829.8
2022-12-24 00:10:01,555:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3608
self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16819.8, self.close=16829.8, self.high=16831.0, self.low=16814.0, self.vol=879.621, self.amt=14798119.3415 
127.0.0.1 - - [24/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-24 00:10:01,497:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221223   234500    234959  ...         0.0        0.0       0
5758  20221223   235000    235459  ...         0.0        0.0       0
5759  20221223   235500    235959  ...         0.0        0.0       0
5760  20221224   000000    000459  ...         0.0        0.0       0
5761  20221224   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 00:10:01,498:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671811799, self.tradeDate='20221224', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16819.8, self.close=16829.8, self.high=16831.0, self.low=16814.0, self.vol=879.621, self.amt=14798119.3415, ukdf['pct'].iloc[-1]=0.000523 , ukdf['amount'].iloc[-1]=14798119.3415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3609
self.closeSec=1671812099, self.tradeDate='20221224', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16829.8, self.close=16828.4, self.high=16837.2, self.low=16828.4, self.vol=828.179, self.amt=13941076.7556 
2022-12-24 00:15:00,573:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221223   235000    235459  ...         0.0        0.0       0
5759  20221223   235500    235959  ...         0.0        0.0       0
5760  20221224   000000    000459  ...         0.0        0.0       0
5761  20221224   000500    000959  ...         0.0        0.0       0
5762  20221224   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 00:15:00,590:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671812099, self.tradeDate='20221224', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16829.8, self.close=16828.4, self.high=16837.2, self.low=16828.4, self.vol=828.179, self.amt=13941076.7556, ukdf['pct'].iloc[-1]=-8.3e-05 , ukdf['amount'].iloc[-1]=13941076.7556, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221223   120000    155959  1671782399  ...    723  0.044734 -1.484985    -1.0
724  20221223   160000    195959  1671796799  ...    724  0.046008 -1.444387    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-6095.0824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16837.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [24/Dec/2022 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=170
self.closeSec=1671811199, self.tradeDate='20221223', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16837.3, self.close=16826.0, self.high=16960.0, self.low=16690.0, self.vol=123957.356, self.amt=2086381480.8201 
2022-12-24 00:00:00,988:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671811199, self.tradeDate='20221223', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16837.3, self.close=16826.0, self.high=16960.0, self.low=16690.0, self.vol=123957.356, self.amt=2086381480.8201 
2022-12-24 00:00:01,041:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20221223   040000    075959  ...   77053.704  1.293023e+09  0.009431
722  20221223   080000    115959  ...   40208.220  6.764735e+08  0.000482
723  20221223   120000    155959  ...   24891.267  4.188321e+08  0.001100
724  20221223   160000    195959  ...   30513.335  5.139140e+08 -0.000273
725  20221223   200000    235959  ...  123957.356  2.086381e+09 -0.000677

[5 rows x 11 columns]
2022-12-24 00:00:02,739:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221223   040000    075959  1671753599  ...    721  0.047321 -1.558658    -1.0
722  20221223   080000    115959  1671767999  ...    722  0.048847 -1.513796    -1.0
723  20221223   120000    155959  1671782399  ...    723  0.044734 -1.484985    -1.0
724  20221223   160000    195959  1671796799  ...    724  0.046008 -1.444387    -1.0
725  20221223   200000    235959  1671811199  ...    725  0.046037 -1.408536    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5491.9788', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16826', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


