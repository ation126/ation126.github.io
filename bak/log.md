# 20230127 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [27/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17402
self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22970.1, self.close=22887.6, self.high=22982.7, self.low=22870.0, self.vol=4932.301, self.amt=112992531.3547 
2023-01-27 00:10:01,721:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230126   234500    234959  ...         0.0        0.0       0
5758  20230126   235000    235459  ...         0.0        0.0       0
5759  20230126   235500    235959  ...         0.0        0.0       0
5760  20230127   000000    000459  ...         0.0        0.0       0
5761  20230127   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 00:10:01,721:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22970.1, self.close=22887.6, self.high=22982.7, self.low=22870.0, self.vol=4932.301, self.amt=112992531.3547, ukdf['pct'].iloc[-1]=-0.003592 , ukdf['amount'].iloc[-1]=112992531.3547, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-383033.79312214896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22894.52522471', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17403
self.closeSec=1674749699, self.tradeDate='20230127', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22890.6, self.close=22949.2, self.high=22961.3, self.low=22850.0, self.vol=6488.319, self.amt=148632469.7409 
127.0.0.1 - - [27/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-27 00:15:00,736:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230126   235000    235459  ...         0.0        0.0       0
5759  20230126   235500    235959  ...         0.0        0.0       0
5760  20230127   000000    000459  ...         0.0        0.0       0
5761  20230127   000500    000959  ...         0.0        0.0       0
5762  20230127   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 00:15:00,736:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674749699, self.tradeDate='20230127', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22890.6, self.close=22949.2, self.high=22961.3, self.low=22850.0, self.vol=6488.319, self.amt=148632469.7409, ukdf['pct'].iloc[-1]=0.002691 , ukdf['amount'].iloc[-1]=148632469.7409, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-386227.6208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22947.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22970.1, self.close=22887.6, self.high=22982.7, self.low=22870.0 
2023-01-27 00:10:01,656:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22970.1, self.close=22887.6, self.high=22982.7, self.low=22870.0   
127.0.0.1 - - [27/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-27 00:10:01,674:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230126   234500    234959  1674748199  ...  22984.5 -0.002095   1725    3
1438  20230126   235000    235459  1674748499  ...  22940.1 -0.002230   1726    4
1439  20230126   235500    235959  1674748799  ...  22890.0 -0.000200   1727    5
1440  20230127   000000    000459  1674749099  ...  22936.3  0.000941   1440    0
1441  20230127   000500    000959  1674749399  ...  22870.0 -0.003592   1441    1

[5 rows x 11 columns]
2023-01-27 00:10:01,674:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=285, self.factor=0.5060452676700756, self.count=17969 

self.closeSec=1674749699, self.tradeDate='20230127', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22890.6, self.close=22949.2, self.high=22961.3, self.low=22850.0 
2023-01-27 00:15:00,693:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674749699, self.tradeDate='20230127', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22890.6, self.close=22949.2, self.high=22961.3, self.low=22850.0   
127.0.0.1 - - [27/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-27 00:15:00,720:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230126   235000    235459  1674748499  ...  22940.1 -0.002230   1726    4
1439  20230126   235500    235959  1674748799  ...  22890.0 -0.000200   1727    5
1440  20230127   000000    000459  1674749099  ...  22936.3  0.000941   1440    0
1441  20230127   000500    000959  1674749399  ...  22870.0 -0.003592   1441    1
1442  20230127   001000    001459  1674749699  ...  22850.0  0.002691   1442    2

[5 rows x 11 columns]
2023-01-27 00:15:00,722:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-27 00:00:21,004:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230126    212959  23115.7  ...  52.083333  0.526509  0.529672
5803  20230126    215959  23064.7  ...  52.500000  0.535157  0.531512
5804  20230126    222959  23121.2  ...  52.500000  0.544002  0.531240
5805  20230126    225959  23180.1  ...  52.083333  0.518127  0.541377
5806  20230126    232959  23028.6  ...  52.083333  0.532577  0.545402

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-01-27 00:00:21,114:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.515787  0.484213       1  ...  0.978749   1.0    0.0  1.114275
540     0  0.540792  0.459208       1  ...  0.981243   1.0    0.0  1.117113
541     0  0.543359  0.456641       0  ...  0.974829   1.0    0.0  1.109812
542     1  0.487653  0.512347       1  ...  0.978914   1.0    0.0  1.114463
543     0  0.534099  0.465901       0  ...  0.971439   1.0    0.0  1.105952

[5 rows x 10 columns]
2023-01-27 00:00:21,141:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514907  0.485093       1  ...  0.978749   1.0    0.0  1.112902
46     0  0.540769  0.459231       1  ...  0.981243   1.0    0.0  1.118434
47     0  0.543334  0.456666       0  ...  0.974829   1.0    0.0  1.111124
48     1  0.488219  0.511781       1  ...  0.978914   1.0    0.0  1.116389
49     0  0.534099  0.465901       0  ...  0.971439   1.0    0.0  1.105952

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.682', 'enterprice': '23079.5', 'countrevence': '0', 'unrealprofit': '-4105.9872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22949.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-27 00:00:02,150:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230126   231000    231959  1674746399  23074.6  23160.4  0.003718
572  20230126   232000    232959  1674746999  23166.8  23121.9 -0.001662
573  20230126   233000    233959  1674747599  23121.8  23032.4 -0.003871
574  20230126   234000    234959  1674748199  23034.3  23004.4 -0.001216
575  20230126   235000    235959  1674748799  23002.6  22948.5 -0.002430
2023-01-27 00:00:02,150:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.22', 'enterprice': '23120.5', 'countrevence': '0', 'unrealprofit': '-7133.2914043044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22947.44586598', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-27 00:00:02,790:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-27 00:00:02,790:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 41.22, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41613F1674748802789I0L59'}
2023-01-27 00:00:02,805:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1270000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230126, closeTime:235959, close:22948.5, total:952073.98299, mom:0.015157363960054848, thd:0.0, side:sell 
2023-01-27 00:00:03,122:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41613F1674748802789I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674748802892483, 'quantity': '41.22', 'price': '22945.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674748802359, 'updatetime': 1674748802892, 'tradetype': 'usdt', 'selfid': 41613, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674748802892, 'clientorderid': '41613F1674748802789I0L59', 'price': '22945.9', 'quantity': '41.22', 'commission': '945.829998', 'commissionasset': 'USDT', 'tradetime': 1674748802892, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674748802892}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-27 00:00:03,276:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41613F1674748802789I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674748802892483, 'quantity': '41.22', 'price': '22945.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674748802359, 'updatetime': 1674748802892, 'tradetype': 'usdt', 'selfid': 41613, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674748802892, 'clientorderid': '41613F1674748802789I0L59', 'price': '22945.9', 'quantity': '41.22', 'commission': '945.829998', 'commissionasset': 'USDT', 'tradetime': 1674748802892, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674748802892}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8984 

self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22947.2', self.close='22887.6'
2023-01-27 00:10:01,905:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22947.2', self.close='22887.6'
2023-01-27 00:10:01,954:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230126   232000    232959  1674746999  23166.8  23121.9 -0.001662
573  20230126   233000    233959  1674747599  23121.8  23032.4 -0.003871
574  20230126   234000    234959  1674748199  23034.3  23004.4 -0.001216
575  20230126   235000    235959  1674748799  23002.6  22948.5 -0.002430
576  20230127   000000    000959  1674749399  22947.2  22887.6 -0.002654
2023-01-27 00:10:01,954:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-26 23:50:00,552:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8984 

self.closeSec=1674748799, self.tradeDate='20230126', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='23002.6', self.close='22948.5'
127.0.0.1 - - [27/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-27 00:00:02,139:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674748799, self.tradeDate='20230126', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='23002.6', self.close='22948.5'
2023-01-27 00:00:02,188:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230126   231000    231959  1674746399  23074.6  23160.4
17420  20230126   232000    232959  1674746999  23166.8  23121.9
17421  20230126   233000    233959  1674747599  23121.8  23032.4
17422  20230126   234000    234959  1674748199  23034.3  23004.4
17423  20230126   235000    235959  1674748799  23002.6  22948.5
2023-01-27 00:00:02,189:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-27 00:00:02,361:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1270000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230126, closeTime:235959, close:22948.5, total:950078.9425875, pct_pre:0.018905764017375093, thd:-0.172291366009923, side:sell 
127.0.0.1 - - [27/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8985 

self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22947.2', self.close='22887.6'
2023-01-27 00:10:01,934:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22947.2', self.close='22887.6'
2023-01-27 00:10:01,959:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230126   232000    232959  1674746999  23166.8  23121.9
17421  20230126   233000    233959  1674747599  23121.8  23032.4
17422  20230126   234000    234959  1674748199  23034.3  23004.4
17423  20230126   235000    235959  1674748799  23002.6  22948.5
17424  20230127   000000    000959  1674749399  22947.2  22887.6
2023-01-27 00:10:01,960:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-27 00:00:02,156:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230126   231000    231959  1674746399  23074.6  23160.4
12236  20230126   232000    232959  1674746999  23166.8  23121.9
12237  20230126   233000    233959  1674747599  23121.8  23032.4
12238  20230126   234000    234959  1674748199  23034.3  23004.4
12239  20230126   235000    235959  1674748799  23002.6  22948.5
2023-01-27 00:00:02,156:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '49.15', 'enterprice': '22925.1', 'countrevence': '0', 'unrealprofit': '1098.299312917', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22947.44586598', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-27 00:00:02,757:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-27 00:00:02,758:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 49.15, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41612F1674748802756I0L2'}
2023-01-27 00:00:02,779:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1270000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230126, closeTime:235959, close:22948.5, total:1125641.8963349997, corrDate:20230114, corrVal:0.9092178881603639, side:sell 
127.0.0.1 - - [27/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-27 00:00:02,888:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41612F1674748802756I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674748802857907, 'quantity': '49.15', 'price': '22945.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674748802381, 'updatetime': 1674748802857, 'tradetype': 'usdt', 'selfid': 41612, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674748802857, 'clientorderid': '41612F1674748802756I0L2', 'price': '22945.9', 'quantity': '49.15', 'commission': '1127.790985', 'commissionasset': 'USDT', 'tradetime': 1674748802857, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674748802857}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-27 00:00:03,079:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41612F1674748802756I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674748802857907, 'quantity': '49.15', 'price': '22945.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674748802381, 'updatetime': 1674748802857, 'tradetype': 'usdt', 'selfid': 41612, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674748802857, 'clientorderid': '41612F1674748802756I0L2', 'price': '22945.9', 'quantity': '49.15', 'commission': '1127.790985', 'commissionasset': 'USDT', 'tradetime': 1674748802857, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674748802857}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8985 

self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22947.2', self.close='22887.6'
2023-01-27 00:10:01,931:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22947.2', self.close='22887.6'
2023-01-27 00:10:01,957:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230126   232000    232959  1674746999  23166.8  23121.9
12237  20230126   233000    233959  1674747599  23121.8  23032.4
12238  20230126   234000    234959  1674748199  23034.3  23004.4
12239  20230126   235000    235959  1674748799  23002.6  22948.5
12240  20230127   000000    000959  1674749399  22947.2  22887.6
2023-01-27 00:10:01,957:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [27/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13400
self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22970.1, self.close=22887.6, self.high=22982.7, self.low=22870.0, self.vol=4932.301, self.amt=112992531.3547 
2023-01-27 00:10:01,723:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230126   234500    234959  ...         0.0        0.0       0
5758  20230126   235000    235459  ...         0.0        0.0       0
5759  20230126   235500    235959  ...         0.0        0.0       0
5760  20230127   000000    000459  ...         0.0        0.0       0
5761  20230127   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 00:10:01,724:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674749399, self.tradeDate='20230127', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22970.1, self.close=22887.6, self.high=22982.7, self.low=22870.0, self.vol=4932.301, self.amt=112992531.3547, ukdf['pct'].iloc[-1]=-0.003592 , ukdf['amount'].iloc[-1]=112992531.3547, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [27/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13401
self.closeSec=1674749699, self.tradeDate='20230127', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22890.6, self.close=22949.2, self.high=22961.3, self.low=22850.0, self.vol=6488.319, self.amt=148632469.7409 
2023-01-27 00:15:00,748:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230126   235000    235459  ...         0.0        0.0       0
5759  20230126   235500    235959  ...         0.0        0.0       0
5760  20230127   000000    000459  ...         0.0        0.0       0
5761  20230127   000500    000959  ...         0.0        0.0       0
5762  20230127   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 00:15:00,749:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674749699, self.tradeDate='20230127', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22890.6, self.close=22949.2, self.high=22961.3, self.low=22850.0, self.vol=6488.319, self.amt=148632469.7409, ukdf['pct'].iloc[-1]=0.002691 , ukdf['amount'].iloc[-1]=148632469.7409, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230126   120000    155959  1674719999  ...    723  0.185886 -1.284585    -1.0
724  20230126   160000    195959  1674734399  ...    724  0.176547 -1.274700    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-2529.43668463728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22988.30272856', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=374
self.closeSec=1674748799, self.tradeDate='20230126', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22985.4, self.close=22948.5, self.high=23241.9, self.low=22856.0, self.vol=155447.749, self.amt=3585152915.28458 
2023-01-27 00:00:01,992:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674748799, self.tradeDate='20230126', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22985.4, self.close=22948.5, self.high=23241.9, self.low=22856.0, self.vol=155447.749, self.amt=3585152915.28458 
2023-01-27 00:00:02,018:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230126   040000    075959  ...  309662.086  7.186402e+09  0.013903
722  20230126   080000    115959  ...   61160.892  1.416929e+09  0.003027
723  20230126   120000    155959  ...   50565.793  1.165545e+09 -0.007268
724  20230126   160000    195959  ...   54116.524  1.242078e+09  0.001050
725  20230126   200000    235959  ...  155447.749  3.585153e+09 -0.001605

[5 rows x 11 columns]
2023-01-27 00:00:03,619:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230126   040000    075959  1674691199  ...    721  0.164732 -1.395258    -1.0
722  20230126   080000    115959  1674705599  ...    722  0.176898 -1.335582    -1.0
723  20230126   120000    155959  1674719999  ...    723  0.185886 -1.284585    -1.0
724  20230126   160000    195959  1674734399  ...    724  0.176547 -1.274700    -1.0
725  20230126   200000    235959  1674748799  ...    725  0.205563 -1.183238    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-839.34558627324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22947.80986598', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


