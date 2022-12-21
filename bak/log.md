# 20221222 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [22/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7034
self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16852.6, self.close=16846.2, self.high=16852.6, self.low=16844.7, self.vol=442.55, self.amt=7456095.6261 
2022-12-22 00:10:01,697:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221221   234500    234959  ...         0.0        0.0       0
5758  20221221   235000    235459  ...         0.0        0.0       0
5759  20221221   235500    235959  ...         0.0        0.0       0
5760  20221222   000000    000459  ...         0.0        0.0       0
5761  20221222   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 00:10:01,698:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16852.6, self.close=16846.2, self.high=16852.6, self.low=16844.7, self.vol=442.55, self.amt=7456095.6261, ukdf['pct'].iloc[-1]=-0.000374 , ukdf['amount'].iloc[-1]=7456095.6261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-19077.12845119104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16846.32220904', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7035
self.closeSec=1671639299, self.tradeDate='20221222', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16845.4, self.close=16841.3, self.high=16852.1, self.low=16833.6, self.vol=874.166, self.amt=14723066.2374 
2022-12-22 00:15:00,601:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221221   235000    235459  ...         0.0        0.0       0
5759  20221221   235500    235959  ...         0.0        0.0       0
5760  20221222   000000    000459  ...         0.0        0.0       0
5761  20221222   000500    000959  ...         0.0        0.0       0
5762  20221222   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 00:15:00,603:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671639299, self.tradeDate='20221222', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16845.4, self.close=16841.3, self.high=16852.1, self.low=16833.6, self.vol=874.166, self.amt=14723066.2374, ukdf['pct'].iloc[-1]=-0.000291 , ukdf['amount'].iloc[-1]=14723066.2374, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-18786.9472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16841.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.4797524615305172, self.count=7600 

self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16852.6, self.close=16846.2, self.high=16852.6, self.low=16844.7 
2022-12-22 00:10:01,646:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16852.6, self.close=16846.2, self.high=16852.6, self.low=16844.7   
2022-12-22 00:10:01,673:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221221   234500    234959  1671637799  ...  16833.1 -0.000445   1725    3
1438  20221221   235000    235459  1671638099  ...  16830.0 -0.000445   1726    4
1439  20221221   235500    235959  1671638399  ...  16831.5  0.001366   1727    5
1440  20221222   000000    000459  1671638699  ...  16851.1 -0.000125   1440    0
1441  20221222   000500    000959  1671638999  ...  16844.7 -0.000374   1441    1

[5 rows x 11 columns]
2022-12-22 00:10:01,673:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.4797524615305172, self.count=7601 

self.closeSec=1671639299, self.tradeDate='20221222', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16845.4, self.close=16841.3, self.high=16852.1, self.low=16833.6 
127.0.0.1 - - [22/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-22 00:15:00,548:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671639299, self.tradeDate='20221222', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16845.4, self.close=16841.3, self.high=16852.1, self.low=16833.6   
2022-12-22 00:15:00,600:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221221   235000    235459  1671638099  ...  16830.0 -0.000445   1726    4
1439  20221221   235500    235959  1671638399  ...  16831.5  0.001366   1727    5
1440  20221222   000000    000459  1671638699  ...  16851.1 -0.000125   1440    0
1441  20221222   000500    000959  1671638999  ...  16844.7 -0.000374   1441    1
1442  20221222   001000    001459  1671639299  ...  16833.6 -0.000291   1442    2

[5 rows x 11 columns]
2022-12-22 00:15:00,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-22 00:00:18,333:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221221    212959  16827.2  ...  48.750000  0.511854  0.532016
5803  20221221    215959  16822.7  ...  49.166667  0.518436  0.530792
5804  20221221    222959  16837.8  ...  49.166667  0.526757  0.521480
5805  20221221    225959  16857.2  ...  49.166667  0.495903  0.525903
5806  20221221    232959  16789.0  ...  49.583333  0.509213  0.521075

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2022-12-22 00:00:18,410:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.489887  0.510113       1  ...  1.100392   1.0    0.0  0.982105
540     1  0.496947  0.503053       1  ...  1.101653   1.0    0.0  0.983231
541     1  0.497313  0.502687       0  ...  1.097203   1.0    0.0  0.979259
542     1  0.474146  0.525854       1  ...  1.099222   1.0    0.0  0.981061
543     0  0.500488  0.499512       1  ...  1.101490   1.0    0.0  0.983085

[5 rows x 10 columns]
2022-12-22 00:00:18,421:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489609  0.510391       1  ...  1.100392   1.0    0.0  0.981905
46     1  0.496977  0.503023       1  ...  1.101653   1.0    0.0  0.983472
47     1  0.497351  0.502649       0  ...  1.097203   1.0    0.0  0.979499
48     1  0.473877  0.526123       1  ...  1.099222   1.0    0.0  0.980352
49     0  0.500488  0.499512       1  ...  1.101490   1.0    0.0  0.983085

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '6621.6096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16857.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-22 00:00:01,686:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221221   231000    231959  1671635999  16833.6  16816.5 -0.001022
572  20221221   232000    232959  1671636599  16816.6  16819.9  0.000202
573  20221221   233000    233959  1671637199    16820  16860.6  0.002420
574  20221221   234000    234959  1671637799  16860.5  16839.1 -0.001275
575  20221221   235000    235959  1671638399    16839  16854.6  0.000920
2022-12-22 00:00:01,687:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '56.171', 'enterprice': '16833.5', 'countrevence': '0', 'unrealprofit': '1190.8252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16854.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-22 00:00:02,231:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-22 00:00:02,231:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 56.171, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41400F1671638402230I0L59'}
2022-12-22 00:00:02,262:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12220000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221221, closeTime:235959, close:16854.6, total:944608.9739715001, mom:0.004242355748700577, thd:0.0, side:sell 
127.0.0.1 - - [22/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-22 00:00:02,416:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41400F1671638402230I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671638402347271, 'quantity': '56.171', 'price': '16854.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671638401854, 'updatetime': 1671638402347, 'tradetype': 'usdt', 'selfid': 41400, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671638402347, 'clientorderid': '41400F1671638402230I0L59', 'price': '16854.6', 'quantity': '56.171', 'commission': '946.7397366', 'commissionasset': 'USDT', 'tradetime': 1671638402347, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671638402347}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-22 00:00:02,654:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41400F1671638402230I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671638402347271, 'quantity': '56.171', 'price': '16854.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671638401854, 'updatetime': 1671638402347, 'tradetype': 'usdt', 'selfid': 41400, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671638402347, 'clientorderid': '41400F1671638402230I0L59', 'price': '16854.6', 'quantity': '56.171', 'commission': '946.7397366', 'commissionasset': 'USDT', 'tradetime': 1671638402347, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671638402347}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3800 

self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16854.6', self.close='16846.2'
2022-12-22 00:10:01,989:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16854.6', self.close='16846.2'
127.0.0.1 - - [22/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 00:10:02,041:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221221   232000    232959  1671636599  16816.6  16819.9  0.000202
573  20221221   233000    233959  1671637199    16820  16860.6  0.002420
574  20221221   234000    234959  1671637799  16860.5  16839.1 -0.001275
575  20221221   235000    235959  1671638399    16839  16854.6  0.000920
576  20221222   000000    000959  1671638999  16854.6  16846.2 -0.000498
2022-12-22 00:10:02,041:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-21 23:50:00,802:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3800 

self.closeSec=1671638399, self.tradeDate='20221221', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16839', self.close='16854.6'
2022-12-22 00:00:01,639:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671638399, self.tradeDate='20221221', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16839', self.close='16854.6'
2022-12-22 00:00:01,697:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221221   231000    231959  1671635999  16833.6  16816.5
17420  20221221   232000    232959  1671636599  16816.6  16819.9
17421  20221221   233000    233959  1671637199    16820  16860.6
17422  20221221   234000    234959  1671637799  16860.5  16839.1
17423  20221221   235000    235959  1671638399    16839  16854.6
2022-12-22 00:00:01,697:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-22 00:00:01,864:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12220000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221221, closeTime:235959, close:16854.6, total:946635.6384771, pct_pre:-0.0012734854408036345, thd:0.3890139201742758, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3801 

self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16854.6', self.close='16846.2'
127.0.0.1 - - [22/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 00:10:01,984:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16854.6', self.close='16846.2'
2022-12-22 00:10:02,052:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221221   232000    232959  1671636599  16816.6  16819.9
17421  20221221   233000    233959  1671637199    16820  16860.6
17422  20221221   234000    234959  1671637799  16860.5  16839.1
17423  20221221   235000    235959  1671638399    16839  16854.6
17424  20221222   000000    000959  1671638999  16854.6  16846.2
2022-12-22 00:10:02,052:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-22 00:00:01,666:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221221   231000    231959  1671635999  16833.6  16816.5
12236  20221221   232000    232959  1671636599  16816.6  16819.9
12237  20221221   233000    233959  1671637199    16820  16860.6
12238  20221221   234000    234959  1671637799  16860.5  16839.1
12239  20221221   235000    235959  1671638399    16839  16854.6
2022-12-22 00:00:01,666:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.371', 'enterprice': '16862.2', 'countrevence': '0', 'unrealprofit': '565.2825', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16854.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-22 00:00:02,595:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-22 00:00:02,595:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.371, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41401F1671638402378I0L2'}
2022-12-22 00:00:02,613:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12220000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221221, closeTime:235959, close:16854.6, total:1269649.9553238, corrDate:20221201, corrVal:0.8291581175854301, side:buy 
127.0.0.1 - - [22/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-22 00:00:02,741:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41401F1671638402378I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671638402705629, 'quantity': '75.371', 'price': '16854.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671638401902, 'updatetime': 1671638402705, 'tradetype': 'usdt', 'selfid': 41401, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671638402705, 'clientorderid': '41401F1671638402378I0L2', 'price': '16854.7', 'quantity': '75.371', 'commission': '1270.3555937', 'commissionasset': 'USDT', 'tradetime': 1671638402705, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671638402705}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-22 00:00:02,930:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41401F1671638402378I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671638402705629, 'quantity': '75.371', 'price': '16854.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671638401902, 'updatetime': 1671638402705, 'tradetype': 'usdt', 'selfid': 41401, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671638402705, 'clientorderid': '41401F1671638402378I0L2', 'price': '16854.7', 'quantity': '75.371', 'commission': '1270.3555937', 'commissionasset': 'USDT', 'tradetime': 1671638402705, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671638402705}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3801 

self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16854.6', self.close='16846.2'
2022-12-22 00:10:01,973:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16854.6', self.close='16846.2'
127.0.0.1 - - [22/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 00:10:02,045:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221221   232000    232959  1671636599  16816.6  16819.9
12237  20221221   233000    233959  1671637199    16820  16860.6
12238  20221221   234000    234959  1671637799  16860.5  16839.1
12239  20221221   235000    235959  1671638399    16839  16854.6
12240  20221222   000000    000959  1671638999  16854.6  16846.2
2022-12-22 00:10:02,045:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3032
self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16852.6, self.close=16846.2, self.high=16852.6, self.low=16844.7, self.vol=442.55, self.amt=7456095.6261 
127.0.0.1 - - [22/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 00:10:01,694:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221221   234500    234959  ...         0.0        0.0       0
5758  20221221   235000    235459  ...         0.0        0.0       0
5759  20221221   235500    235959  ...         0.0        0.0       0
5760  20221222   000000    000459  ...         0.0        0.0       0
5761  20221222   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 00:10:01,696:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671638999, self.tradeDate='20221222', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16852.6, self.close=16846.2, self.high=16852.6, self.low=16844.7, self.vol=442.55, self.amt=7456095.6261, ukdf['pct'].iloc[-1]=-0.000374 , ukdf['amount'].iloc[-1]=7456095.6261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3033
self.closeSec=1671639299, self.tradeDate='20221222', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16845.4, self.close=16841.3, self.high=16852.1, self.low=16833.6, self.vol=874.166, self.amt=14723066.2374 
2022-12-22 00:15:00,621:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221221   235000    235459  ...         0.0        0.0       0
5759  20221221   235500    235959  ...         0.0        0.0       0
5760  20221222   000000    000459  ...         0.0        0.0       0
5761  20221222   000500    000959  ...         0.0        0.0       0
5762  20221222   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 00:15:00,622:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671639299, self.tradeDate='20221222', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16845.4, self.close=16841.3, self.high=16852.1, self.low=16833.6, self.vol=874.166, self.amt=14723066.2374, ukdf['pct'].iloc[-1]=-0.000291 , ukdf['amount'].iloc[-1]=14723066.2374, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221221   120000    155959  1671609599  ...    723  0.031652 -2.167219    -1.0
724  20221221   160000    195959  1671623999  ...    724  0.036194 -2.077497    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-8097.12592546088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16874.81112054', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [22/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=158
self.closeSec=1671638399, self.tradeDate='20221221', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16872.4, self.close=16854.6, self.high=16924.2, self.low=16694.2, self.vol=72649.874, self.amt=1222429104.77814 
2022-12-22 00:00:01,471:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671638399, self.tradeDate='20221221', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16872.4, self.close=16854.6, self.high=16924.2, self.low=16694.2, self.vol=72649.874, self.amt=1222429104.77814 
2022-12-22 00:00:01,495:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221221   040000    075959  ...  35569.835  6.002760e+08 -0.000444
722  20221221   080000    115959  ...  33529.575  5.648337e+08 -0.003399
723  20221221   120000    155959  ...  27534.062  4.629347e+08 -0.001224
724  20221221   160000    195959  ...  31332.466  5.279092e+08  0.003754
725  20221221   200000    235959  ...  72649.874  1.222429e+09 -0.001049

[5 rows x 11 columns]
2022-12-22 00:00:03,189:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221221   040000    075959  1671580799  ...    721  0.011155 -2.410683    -1.0
722  20221221   080000    115959  1671595199  ...    722  0.033927 -2.244878    -1.0
723  20221221   120000    155959  1671609599  ...    723  0.031652 -2.167219    -1.0
724  20221221   160000    195959  1671623999  ...    724  0.036194 -2.077497    -1.0
725  20221221   200000    235959  1671638399  ...    725  0.037568 -2.003620    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-7023.7552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16854.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


