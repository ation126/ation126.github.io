# 20230129 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17978
self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23003.3, self.close=23021.0, self.high=23021.0, self.low=23003.1, self.vol=433.194, self.amt=9969299.8884 
127.0.0.1 - - [29/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-29 00:10:01,477:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230128   234500    234959  ...         0.0        0.0       0
5758  20230128   235000    235459  ...         0.0        0.0       0
5759  20230128   235500    235959  ...         0.0        0.0       0
5760  20230129   000000    000459  ...         0.0        0.0       0
5761  20230129   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-29 00:10:01,478:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23003.3, self.close=23021.0, self.high=23021.0, self.low=23003.1, self.vol=433.194, self.amt=9969299.8884, ukdf['pct'].iloc[-1]=0.000804 , ukdf['amount'].iloc[-1]=9969299.8884, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-390743.22896589296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23022.64001871', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17979
self.closeSec=1674922499, self.tradeDate='20230129', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23021.0, self.close=23023.7, self.high=23029.2, self.low=23014.7, self.vol=530.991, self.amt=12224542.6067 
127.0.0.1 - - [29/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-29 00:15:00,788:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230128   235000    235459  ...         0.0        0.0       0
5759  20230128   235500    235959  ...         0.0        0.0       0
5760  20230129   000000    000459  ...         0.0        0.0       0
5761  20230129   000500    000959  ...         0.0        0.0       0
5762  20230129   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-29 00:15:00,788:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674922499, self.tradeDate='20230129', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23021.0, self.close=23023.7, self.high=23029.2, self.low=23014.7, self.vol=530.991, self.amt=12224542.6067, ukdf['pct'].iloc[-1]=0.000117 , ukdf['amount'].iloc[-1]=12224542.6067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-390807.0144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23023.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23003.3, self.close=23021.0, self.high=23021.0, self.low=23003.1 
2023-01-29 00:10:01,414:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23003.3, self.close=23021.0, self.high=23021.0, self.low=23003.1   
127.0.0.1 - - [29/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-29 00:10:01,457:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230128   234500    234959  1674920999  ...  23017.1 -0.000465   1725    3
1438  20230128   235000    235459  1674921299  ...  23007.3 -0.000043   1726    4
1439  20230128   235500    235959  1674921599  ...  23001.0 -0.000478   1727    5
1440  20230129   000000    000459  1674921899  ...  23000.0 -0.000130   1440    0
1441  20230129   000500    000959  1674922199  ...  23003.1  0.000804   1441    1

[5 rows x 11 columns]
2023-01-29 00:10:01,458:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=381, self.factor=0.5803691005455943, self.count=18545 

self.closeSec=1674922499, self.tradeDate='20230129', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23021.0, self.close=23023.7, self.high=23029.2, self.low=23014.7 
2023-01-29 00:15:00,728:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674922499, self.tradeDate='20230129', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23021.0, self.close=23023.7, self.high=23029.2, self.low=23014.7   
127.0.0.1 - - [29/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-29 00:15:00,766:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230128   235000    235459  1674921299  ...  23007.3 -0.000043   1726    4
1439  20230128   235500    235959  1674921599  ...  23001.0 -0.000478   1727    5
1440  20230129   000000    000459  1674921899  ...  23000.0 -0.000130   1440    0
1441  20230129   000500    000959  1674922199  ...  23003.1  0.000804   1441    1
1442  20230129   001000    001459  1674922499  ...  23014.7  0.000117   1442    2

[5 rows x 11 columns]
2023-01-29 00:15:00,770:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-29 00:00:19,188:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230128    212959  22950.4  ...  51.250000  0.480314  0.714222
5803  20230128    215959  22920.6  ...  51.666667  0.491135  0.723409
5804  20230128    222959  22963.8  ...  52.083333  0.492728  0.731306
5805  20230128    225959  22970.2  ...  52.083333  0.485745  0.741728
5806  20230128    232959  22941.5  ...  52.083333  0.497380  0.746571

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-01-29 00:00:19,278:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.503000  0.497000       1  ...  0.986789   1.0    0.0  1.086550
540     0  0.521428  0.478572       1  ...  0.987064   1.0    0.0  1.086852
541     0  0.514047  0.485953       0  ...  0.985827   1.0    0.0  1.085490
542     0  0.507172  0.492828       1  ...  0.987807   1.0    0.0  1.087671
543     0  0.523567  0.476433       1  ...  0.988542   1.0    0.0  1.088480

[5 rows x 10 columns]
2023-01-29 00:00:19,297:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503571  0.496429       1  ...  0.986789   1.0    0.0  1.087177
46     0  0.522942  0.477058       1  ...  0.959656   1.0    0.0  1.089792
47     0  0.515526  0.484474       0  ...  0.958453   1.0    0.0  1.088425
48     0  0.507935  0.492065       1  ...  0.987807   1.0    0.0  1.089336
49     0  0.523567  0.476433       1  ...  0.988542   1.0    0.0  1.088480

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.8', 'enterprice': '23035.8', 'countrevence': '0', 'unrealprofit': '-880.88', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23007.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-29 00:00:02,165:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230128   231000    231959  1674919199  22986.8  23030.4  0.001897
572  20230128   232000    232959  1674919799  23030.4  22987.6 -0.001858
573  20230128   233000    233959  1674920399  22987.6  23021.4  0.001470
574  20230128   234000    234959  1674920999  23021.4  23017.5 -0.000169
575  20230128   235000    235959  1674921599  23017.5  23004.7 -0.000556
2023-01-29 00:00:02,165:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.077', 'enterprice': '23116.5', 'countrevence': '0', 'unrealprofit': '-4564.20138598837', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23005.38669119', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-29 00:00:02,735:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-29 00:00:02,735:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 41.077, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41625F1674921602734I0L59'}
2023-01-29 00:00:02,772:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1290000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230128, closeTime:235959, close:23004.7, total:948606.9140295, mom:0.008765414729198229, thd:0.0, side:sell 
2023-01-29 00:00:02,894:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41625F1674921602734I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674921602855905, 'quantity': '41.077', 'price': '23004.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674921602344, 'updatetime': 1674921602855, 'tradetype': 'usdt', 'selfid': 41625, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674921602855, 'clientorderid': '41625F1674921602734I0L59', 'price': '23004.6', 'quantity': '41.077', 'commission': '944.9599542', 'commissionasset': 'USDT', 'tradetime': 1674921602855, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674921602855}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-29 00:00:03,151:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41625F1674921602734I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674921602855905, 'quantity': '41.077', 'price': '23004.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674921602344, 'updatetime': 1674921602855, 'tradetype': 'usdt', 'selfid': 41625, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674921602855, 'clientorderid': '41625F1674921602734I0L59', 'price': '23004.6', 'quantity': '41.077', 'commission': '944.9599542', 'commissionasset': 'USDT', 'tradetime': 1674921602855, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674921602855}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9272 

self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23004.6', self.close='23021'
2023-01-29 00:10:01,536:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23004.6', self.close='23021'
2023-01-29 00:10:01,583:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230128   232000    232959  1674919799  23030.4  22987.6 -0.001858
573  20230128   233000    233959  1674920399  22987.6  23021.4  0.001470
574  20230128   234000    234959  1674920999  23021.4  23017.5 -0.000169
575  20230128   235000    235959  1674921599  23017.5  23004.7 -0.000556
576  20230129   000000    000959  1674922199  23004.6    23021  0.000709
2023-01-29 00:10:01,583:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-29 00:00:02,169:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230128   231000    231959  1674919199  22986.8  23030.4
17420  20230128   232000    232959  1674919799  23030.4  22987.6
17421  20230128   233000    233959  1674920399  22987.6  23021.4
17422  20230128   234000    234959  1674920999  23021.4  23017.5
17423  20230128   235000    235959  1674921599  23017.5  23004.7
2023-01-29 00:00:02,174:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.279', 'enterprice': '22992.5', 'countrevence': '0', 'unrealprofit': '531.94972563201', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23005.38669119', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-29 00:00:02,785:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-29 00:00:02,785:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 41.279, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41627F1674921602784I0L57'}
2023-01-29 00:00:02,818:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1290000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230128, closeTime:235959, close:23004.7, total:948158.3000925, pct_pre:7.394101246993579e-05, thd:0.11549650870509354, side:sell 
127.0.0.1 - - [29/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-29 00:00:03,146:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41627F1674921602784I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674921602935375, 'quantity': '41.279', 'price': '23004.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674921602376, 'updatetime': 1674921602935, 'tradetype': 'usdt', 'selfid': 41627, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674921602935, 'clientorderid': '41627F1674921602784I0L57', 'price': '23004.6', 'quantity': '41.279', 'commission': '949.6068834', 'commissionasset': 'USDT', 'tradetime': 1674921602935, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674921602935}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-29 00:00:03,342:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41627F1674921602784I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674921602935375, 'quantity': '41.279', 'price': '23004.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674921602376, 'updatetime': 1674921602935, 'tradetype': 'usdt', 'selfid': 41627, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674921602935, 'clientorderid': '41627F1674921602784I0L57', 'price': '23004.6', 'quantity': '41.279', 'commission': '949.6068834', 'commissionasset': 'USDT', 'tradetime': 1674921602935, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674921602935}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9273 

self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23004.6', self.close='23021'
2023-01-29 00:10:01,550:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23004.6', self.close='23021'
2023-01-29 00:10:01,586:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230128   232000    232959  1674919799  23030.4  22987.6
17421  20230128   233000    233959  1674920399  22987.6  23021.4
17422  20230128   234000    234959  1674920999  23021.4  23017.5
17423  20230128   235000    235959  1674921599  23017.5  23004.7
17424  20230129   000000    000959  1674922199  23004.6    23021
2023-01-29 00:10:01,587:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-29 00:00:02,118:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230128   231000    231959  1674919199  22986.8  23030.4
12236  20230128   232000    232959  1674919799  23030.4  22987.6
12237  20230128   233000    233959  1674920399  22987.6  23021.4
12238  20230128   234000    234959  1674920999  23021.4  23017.5
12239  20230128   235000    235959  1674921599  23017.5  23004.7
2023-01-29 00:00:02,118:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '49.102', 'enterprice': '23000.7', 'countrevence': '0', 'unrealprofit': '-230.12591081138', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23005.38669119', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-29 00:00:02,763:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-29 00:00:02,763:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 49.102, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41626F1674921602762I0L2'}
2023-01-29 00:00:02,803:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1290000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230128, closeTime:235959, close:23004.7, total:1128250.9910286001, corrDate:20221108, corrVal:0.6330907976791581, side:buy 
127.0.0.1 - - [29/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-29 00:00:03,343:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41626F1674921602762I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674921602865729, 'quantity': '49.102', 'price': '23004.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674921602289, 'updatetime': 1674921602865, 'tradetype': 'usdt', 'selfid': 41626, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674921602865, 'clientorderid': '41626F1674921602762I0L2', 'price': '23004.7', 'quantity': '49.102', 'commission': '1129.5767794', 'commissionasset': 'USDT', 'tradetime': 1674921602865, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674921602865}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-29 00:00:03,527:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41626F1674921602762I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674921602865729, 'quantity': '49.102', 'price': '23004.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674921602289, 'updatetime': 1674921602865, 'tradetype': 'usdt', 'selfid': 41626, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674921602865, 'clientorderid': '41626F1674921602762I0L2', 'price': '23004.7', 'quantity': '49.102', 'commission': '1129.5767794', 'commissionasset': 'USDT', 'tradetime': 1674921602865, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674921602865}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9273 

self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23004.6', self.close='23021'
2023-01-29 00:10:01,547:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23004.6', self.close='23021'
2023-01-29 00:10:01,584:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230128   232000    232959  1674919799  23030.4  22987.6
12237  20230128   233000    233959  1674920399  22987.6  23021.4
12238  20230128   234000    234959  1674920999  23021.4  23017.5
12239  20230128   235000    235959  1674921599  23017.5  23004.7
12240  20230129   000000    000959  1674922199  23004.6    23021
2023-01-29 00:10:01,586:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [29/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13976
self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23003.3, self.close=23021.0, self.high=23021.0, self.low=23003.1, self.vol=433.194, self.amt=9969299.8884 
2023-01-29 00:10:01,477:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230128   234500    234959  ...         0.0        0.0       0
5758  20230128   235000    235459  ...         0.0        0.0       0
5759  20230128   235500    235959  ...         0.0        0.0       0
5760  20230129   000000    000459  ...         0.0        0.0       0
5761  20230129   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-29 00:10:01,477:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674922199, self.tradeDate='20230129', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23003.3, self.close=23021.0, self.high=23021.0, self.low=23003.1, self.vol=433.194, self.amt=9969299.8884, ukdf['pct'].iloc[-1]=0.000804 , ukdf['amount'].iloc[-1]=9969299.8884, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [29/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13977
self.closeSec=1674922499, self.tradeDate='20230129', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23021.0, self.close=23023.7, self.high=23029.2, self.low=23014.7, self.vol=530.991, self.amt=12224542.6067 
2023-01-29 00:15:00,785:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230128   235000    235459  ...         0.0        0.0       0
5759  20230128   235500    235959  ...         0.0        0.0       0
5760  20230129   000000    000459  ...         0.0        0.0       0
5761  20230129   000500    000959  ...         0.0        0.0       0
5762  20230129   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-29 00:15:00,786:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674922499, self.tradeDate='20230129', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23021.0, self.close=23023.7, self.high=23029.2, self.low=23014.7, self.vol=530.991, self.amt=12224542.6067, ukdf['pct'].iloc[-1]=0.000117 , ukdf['amount'].iloc[-1]=12224542.6067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230128   120000    155959  1674892799  ...    723  0.205949 -0.956298    -1.0
724  20230128   160000    195959  1674907199  ...    724  0.203517 -0.940949    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-1968.81775786908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22974.87086966', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [29/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=386
self.closeSec=1674921599, self.tradeDate='20230128', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22973.4, self.close=23004.7, self.high=23038.0, self.low=22870.8, self.vol=49477.228, self.amt=1135744162.7592 
2023-01-29 00:00:01,828:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674921599, self.tradeDate='20230128', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22973.4, self.close=23004.7, self.high=23038.0, self.low=22870.8, self.vol=49477.228, self.amt=1135744162.7592 
2023-01-29 00:00:01,871:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230128   040000    075959  ...  121012.865  2.806965e+09 -0.007687
722  20230128   080000    115959  ...   30607.076  7.071304e+08  0.001777
723  20230128   120000    155959  ...   29492.397  6.790772e+08 -0.005396
724  20230128   160000    195959  ...   36651.176  8.419766e+08 -0.000474
725  20230128   200000    235959  ...   49477.228  1.135744e+09  0.001362

[5 rows x 11 columns]
2023-01-29 00:00:03,412:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230128   040000    075959  1674863999  ...    721  0.243670 -0.910256    -1.0
722  20230128   080000    115959  1674878399  ...    722  0.219206 -0.946683    -1.0
723  20230128   120000    155959  1674892799  ...    723  0.205949 -0.956298    -1.0
724  20230128   160000    195959  1674907199  ...    724  0.203517 -0.940949    -1.0
725  20230128   200000    235959  1674921599  ...    725  0.189366 -0.953117    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-3261.27728567838', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23005.83688451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


