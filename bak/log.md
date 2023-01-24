# 20230125 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16826
self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22921.3, self.close=22889.4, self.high=22921.3, self.low=22881.8, self.vol=1414.701, self.amt=32397572.5413 
127.0.0.1 - - [25/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-25 00:10:01,500:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230124   234500    234959  ...         0.0        0.0       0
5758  20230124   235000    235459  ...         0.0        0.0       0
5759  20230124   235500    235959  ...         0.0        0.0       0
5760  20230125   000000    000459  ...         0.0        0.0       0
5761  20230125   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 00:10:01,500:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22921.3, self.close=22889.4, self.high=22921.3, self.low=22881.8, self.vol=1414.701, self.amt=32397572.5413, ukdf['pct'].iloc[-1]=-0.001392 , ukdf['amount'].iloc[-1]=32397572.5413, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-382734.82246209872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22889.55695397', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16827
self.closeSec=1674576899, self.tradeDate='20230125', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22889.5, self.close=22886.7, self.high=22925.7, self.low=22869.2, self.vol=1893.12, self.amt=43349402.6656 
2023-01-25 00:15:00,998:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230124   235000    235459  ...         0.0        0.0       0
5759  20230124   235500    235959  ...         0.0        0.0       0
5760  20230125   000000    000459  ...         0.0        0.0       0
5761  20230125   000500    000959  ...         0.0        0.0       0
5762  20230125   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 00:15:00,999:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674576899, self.tradeDate='20230125', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22889.5, self.close=22886.7, self.high=22925.7, self.low=22869.2, self.vol=1893.12, self.amt=43349402.6656, ukdf['pct'].iloc[-1]=-0.000118 , ukdf['amount'].iloc[-1]=43349402.6656, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-382514.73828601232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22885.89961257', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=189, self.factor=0.3737607431665501, self.count=17392 

self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22921.3, self.close=22889.4, self.high=22921.3, self.low=22881.8 
2023-01-25 00:10:01,434:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22921.3, self.close=22889.4, self.high=22921.3, self.low=22881.8   
2023-01-25 00:10:01,478:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230124   234500    234959  1674575399  ...  22890.1  0.001218   1725    3
1438  20230124   235000    235459  1674575699  ...  22897.0  0.000118   1726    4
1439  20230124   235500    235959  1674575999  ...  22915.6 -0.000283   1727    5
1440  20230125   000000    000459  1674576299  ...  22919.7 -0.000118   1440    0
1441  20230125   000500    000959  1674576599  ...  22881.8 -0.001392   1441    1

[5 rows x 11 columns]
2023-01-25 00:10:01,481:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=189, self.factor=0.3737607431665501, self.count=17393 

self.closeSec=1674576899, self.tradeDate='20230125', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22889.5, self.close=22886.7, self.high=22925.7, self.low=22869.2 
2023-01-25 00:15:00,930:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674576899, self.tradeDate='20230125', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22889.5, self.close=22886.7, self.high=22925.7, self.low=22869.2   
2023-01-25 00:15:00,964:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230124   235000    235459  1674575699  ...  22897.0  0.000118   1726    4
1439  20230124   235500    235959  1674575999  ...  22915.6 -0.000283   1727    5
1440  20230125   000000    000459  1674576299  ...  22919.7 -0.000118   1440    0
1441  20230125   000500    000959  1674576599  ...  22881.8 -0.001392   1441    1
1442  20230125   001000    001459  1674576899  ...  22869.2 -0.000118   1442    2

[5 rows x 11 columns]
2023-01-25 00:15:00,965:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-25 00:00:18,266:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5802  20230124    212959  22958.6  ...    53.75  0.517602  0.335833
5803  20230124    215959  22949.9  ...    53.75  0.499278  0.355042
5804  20230124    222959  22856.0  ...    53.75  0.497590  0.372385
5805  20230124    225959  22847.5  ...    53.75  0.498892  0.387728
5806  20230124    232959  22854.0  ...    53.75  0.509053  0.395443

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-01-25 00:00:18,355:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.511717  0.488283       0  ...  1.054685   1.0    0.0  1.214606
540     1  0.486547  0.513453       0  ...  1.054293   1.0    0.0  1.214155
541     0  0.501286  0.498714       1  ...  1.054588   1.0    0.0  1.214495
542     1  0.499200  0.500800       1  ...  1.056900   1.0    0.0  1.217157
543     0  0.515376  0.484624       1  ...  1.057818   1.0    0.0  1.218215

[5 rows x 10 columns]
2023-01-25 00:00:18,376:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512009  0.487991       0  ...  1.054685   1.0    0.0  1.214606
46     1  0.486668  0.513332       0  ...  1.054293   1.0    0.0  1.212460
47     0  0.500986  0.499014       1  ...  1.054588   1.0    0.0  1.212800
48     1  0.499450  0.500550       1  ...  1.056900   1.0    0.0  1.219399
49     0  0.515376  0.484624       1  ...  1.057818   1.0    0.0  1.218215

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.288', 'enterprice': '22918.2', 'countrevence': '0', 'unrealprofit': '325.22498509632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22928.27262714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-25 00:00:01,635:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230124   231000    231959  1674573599  22825.9  22855.6  0.001301
572  20230124   232000    232959  1674574199  22859.4  22904.1  0.002122
573  20230124   233000    233959  1674574799  22904.2  22856.1 -0.002096
574  20230124   234000    234959  1674575399  22856.2  22927.8  0.003137
575  20230124   235000    235959  1674575999  22927.7    22924 -0.000166
2023-01-25 00:00:01,636:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.6', 'enterprice': '23062.1', 'countrevence': '0', 'unrealprofit': '-5684.745379872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22925.44746683', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-25 00:00:02,261:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-25 00:00:02,261:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 41.6, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41594F1674576002259I0L59'}
2023-01-25 00:00:02,291:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1250000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230124, closeTime:235959, close:22924, total:958423.97664, mom:0.005774230831343319, thd:0.0, side:sell 
2023-01-25 00:00:02,699:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41594F1674576002259I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674576002642417, 'quantity': '41.6', 'price': '22924.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674576001866, 'updatetime': 1674576002642, 'tradetype': 'usdt', 'selfid': 41594, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674576002642, 'clientorderid': '41594F1674576002259I0L59', 'price': '22924.5', 'quantity': '41.6', 'commission': '953.6592', 'commissionasset': 'USDT', 'tradetime': 1674576002642, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674576002642}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-25 00:00:02,952:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41594F1674576002259I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674576002642417, 'quantity': '41.6', 'price': '22924.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674576001866, 'updatetime': 1674576002642, 'tradetype': 'usdt', 'selfid': 41594, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674576002642, 'clientorderid': '41594F1674576002259I0L59', 'price': '22924.5', 'quantity': '41.6', 'commission': '953.6592', 'commissionasset': 'USDT', 'tradetime': 1674576002642, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674576002642}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8696 

self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22924', self.close='22889.4'
2023-01-25 00:10:01,573:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22924', self.close='22889.4'
2023-01-25 00:10:01,594:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230124   232000    232959  1674574199  22859.4  22904.1  0.002122
573  20230124   233000    233959  1674574799  22904.2  22856.1 -0.002096
574  20230124   234000    234959  1674575399  22856.2  22927.8  0.003137
575  20230124   235000    235959  1674575999  22927.7    22924 -0.000166
576  20230125   000000    000959  1674576599    22924  22889.4 -0.001509
2023-01-25 00:10:01,595:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-24 23:50:00,600:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8696 

self.closeSec=1674575999, self.tradeDate='20230124', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='22927.7', self.close='22924'
2023-01-25 00:00:01,651:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674575999, self.tradeDate='20230124', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='22927.7', self.close='22924'
2023-01-25 00:00:01,722:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230124   231000    231959  1674573599  22825.9  22855.6
17420  20230124   232000    232959  1674574199  22859.4  22904.1
17421  20230124   233000    233959  1674574799  22904.2  22856.1
17422  20230124   234000    234959  1674575399  22856.2  22927.8
17423  20230124   235000    235959  1674575999  22927.7    22924
2023-01-25 00:00:01,723:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-25 00:00:01,901:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1250000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230124, closeTime:235959, close:22924, total:950078.9425875, pct_pre:-0.002292806701109762, thd:0.13143642506523, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8697 

self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22924', self.close='22889.4'
2023-01-25 00:10:01,557:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22924', self.close='22889.4'
127.0.0.1 - - [25/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-25 00:10:01,567:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230124   232000    232959  1674574199  22859.4  22904.1
17421  20230124   233000    233959  1674574799  22904.2  22856.1
17422  20230124   234000    234959  1674575399  22856.2  22927.8
17423  20230124   235000    235959  1674575999  22927.7    22924
17424  20230125   000000    000959  1674576599    22924  22889.4
2023-01-25 00:10:01,567:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-25 00:00:01,705:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230124   231000    231959  1674573599  22825.9  22855.6
12236  20230124   232000    232959  1674574199  22859.4  22904.1
12237  20230124   233000    233959  1674574799  22904.2  22856.1
12238  20230124   234000    234959  1674575399  22856.2  22927.8
12239  20230124   235000    235959  1674575999  22927.7    22924
2023-01-25 00:00:01,705:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '48.882', 'enterprice': '22929.9', 'countrevence': '0', 'unrealprofit': '217.64872641594', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22925.44746683', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-25 00:00:02,307:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-25 00:00:02,307:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 48.882, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41595F1674576002306I0L2'}
2023-01-25 00:00:02,352:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1250000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230124, closeTime:235959, close:22924, total:1119738.5124282, corrDate:20221118, corrVal:0.5721541616580329, side:buy 
127.0.0.1 - - [25/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-25 00:00:02,480:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41595F1674576002306I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674576002430930, 'quantity': '48.882', 'price': '22924.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674576001921, 'updatetime': 1674576002430, 'tradetype': 'usdt', 'selfid': 41595, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674576002430, 'clientorderid': '41595F1674576002306I0L2', 'price': '22924.6', 'quantity': '48.882', 'commission': '1120.6002972', 'commissionasset': 'USDT', 'tradetime': 1674576002430, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674576002430}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-25 00:00:02,700:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41595F1674576002306I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674576002430930, 'quantity': '48.882', 'price': '22924.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674576001921, 'updatetime': 1674576002430, 'tradetype': 'usdt', 'selfid': 41595, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674576002430, 'clientorderid': '41595F1674576002306I0L2', 'price': '22924.6', 'quantity': '48.882', 'commission': '1120.6002972', 'commissionasset': 'USDT', 'tradetime': 1674576002430, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674576002430}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8697 

self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22924', self.close='22889.4'
2023-01-25 00:10:01,560:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22924', self.close='22889.4'
2023-01-25 00:10:01,598:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230124   232000    232959  1674574199  22859.4  22904.1
12237  20230124   233000    233959  1674574799  22904.2  22856.1
12238  20230124   234000    234959  1674575399  22856.2  22927.8
12239  20230124   235000    235959  1674575999  22927.7    22924
12240  20230125   000000    000959  1674576599    22924  22889.4
2023-01-25 00:10:01,598:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12824
self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22921.3, self.close=22889.4, self.high=22921.3, self.low=22881.8, self.vol=1414.701, self.amt=32397572.5413 
127.0.0.1 - - [25/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-25 00:10:01,503:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230124   234500    234959  ...         0.0        0.0       0
5758  20230124   235000    235459  ...         0.0        0.0       0
5759  20230124   235500    235959  ...         0.0        0.0       0
5760  20230125   000000    000459  ...         0.0        0.0       0
5761  20230125   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 00:10:01,504:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674576599, self.tradeDate='20230125', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22921.3, self.close=22889.4, self.high=22921.3, self.low=22881.8, self.vol=1414.701, self.amt=32397572.5413, ukdf['pct'].iloc[-1]=-0.001392 , ukdf['amount'].iloc[-1]=32397572.5413, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12825
self.closeSec=1674576899, self.tradeDate='20230125', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22889.5, self.close=22886.7, self.high=22925.7, self.low=22869.2, self.vol=1893.12, self.amt=43349402.6656 
127.0.0.1 - - [25/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-25 00:15:00,975:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230124   235000    235459  ...         0.0        0.0       0
5759  20230124   235500    235959  ...         0.0        0.0       0
5760  20230125   000000    000459  ...         0.0        0.0       0
5761  20230125   000500    000959  ...         0.0        0.0       0
5762  20230125   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 00:15:00,976:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674576899, self.tradeDate='20230125', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22889.5, self.close=22886.7, self.high=22925.7, self.low=22869.2, self.vol=1893.12, self.amt=43349402.6656, ukdf['pct'].iloc[-1]=-0.000118 , ukdf['amount'].iloc[-1]=43349402.6656, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230124   040000    075959  ...   53110.170  1.217507e+09  0.005371
722  20230124   080000    115959  ...   51857.971  1.194127e+09  0.007205
723  20230124   120000    155959  ...   37575.800  8.677053e+08 -0.001122
724  20230124   160000    195959  ...   80599.104  1.845843e+09 -0.006086
725  20230124   200000    235959  ...  126440.595  2.891896e+09  0.000524

[5 rows x 11 columns]
2023-01-25 00:00:03,247:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230124   040000    075959  1674518399  ...    721  0.950928  0.242794     NaN
722  20230124   080000    115959  1674532799  ...    722  0.908219  0.128689     NaN
723  20230124   120000    155959  1674547199  ...    723  0.829119 -0.071439     NaN
724  20230124   160000    195959  1674561599  ...    724  0.749789 -0.268334     NaN
725  20230124   200000    235959  1674575999  ...    725  0.566763 -0.712239    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-14997.65895944328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22925.39574728', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-14997.65895944328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22925.39574728', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-25 00:00:08,876:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '959682.9632632', 'total': '959682.9632632', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-01-25 00:00:09,067:INFO:s_rsrs:main.py:269:openSell:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 41.738, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41597F1674576009066I0L65'}
2023-01-25 00:00:09,086:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:1250000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230124, closeTime:235959, close:22924.0, sign:-1, total:959682.9632632, side:sell  
127.0.0.1 - - [25/Jan/2023 00:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Jan/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-01-25 00:00:09,088:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41596F1674576003787I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674576003892882, 'quantity': '41.799', 'price': '22924.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674576003500, 'updatetime': 1674576003892, 'tradetype': 'usdt', 'selfid': 41596, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674576003892, 'clientorderid': '41596F1674576003787I0L65', 'price': '22924.5', 'quantity': '41.799', 'commission': '958.2211755', 'commissionasset': 'USDT', 'tradetime': 1674576003892, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674576003892}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-25 00:00:09,088:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41596F1674576003787I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674576003892882, 'quantity': '41.799', 'price': '22924.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674576003500, 'updatetime': 1674576003892, 'tradetype': 'usdt', 'selfid': 41596, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674576003892, 'clientorderid': '41596F1674576003787I0L65', 'price': '22924.5', 'quantity': '41.799', 'commission': '958.2211755', 'commissionasset': 'USDT', 'tradetime': 1674576003892, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674576003892}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jan/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-01-25 00:00:09,215:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41597F1674576009066I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674576009176867, 'quantity': '41.738', 'price': '22927.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674576008887, 'updatetime': 1674576009176, 'tradetype': 'usdt', 'selfid': 41597, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674576009176, 'clientorderid': '41597F1674576009066I0L65', 'price': '22927.7', 'quantity': '41.738', 'commission': '956.9563426', 'commissionasset': 'USDT', 'tradetime': 1674576009176, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674576009176}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-25 00:00:09,398:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41597F1674576009066I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674576009176867, 'quantity': '41.738', 'price': '22927.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674576008887, 'updatetime': 1674576009176, 'tradetype': 'usdt', 'selfid': 41597, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674576009176, 'clientorderid': '41597F1674576009066I0L65', 'price': '22927.7', 'quantity': '41.738', 'commission': '956.9563426', 'commissionasset': 'USDT', 'tradetime': 1674576009176, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674576009176}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jan/2023 00:00:09] "POST / HTTP/1.1" 200 -


