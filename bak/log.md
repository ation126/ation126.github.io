# 20221227 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [27/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8474
self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16799.5, self.close=16807.9, self.high=16807.9, self.low=16795.1, self.vol=529.765, self.amt=8900613.4782 
2022-12-27 00:10:01,508:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221226   234500    234959  ...         0.0        0.0       0
5758  20221226   235000    235459  ...         0.0        0.0       0
5759  20221226   235500    235959  ...         0.0        0.0       0
5760  20221227   000000    000459  ...         0.0        0.0       0
5761  20221227   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-27 00:10:01,508:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16799.5, self.close=16807.9, self.high=16807.9, self.low=16795.1, self.vol=529.765, self.amt=8900613.4782, ukdf['pct'].iloc[-1]=0.000494 , ukdf['amount'].iloc[-1]=8900613.4782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16765.0336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16807.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8475
self.closeSec=1672071299, self.tradeDate='20221227', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16807.8, self.close=16817.3, self.high=16821.0, self.low=16807.8, self.vol=1273.102, self.amt=21405036.1324 
127.0.0.1 - - [27/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-27 00:15:00,662:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221226   235000    235459  ...         0.0        0.0       0
5759  20221226   235500    235959  ...         0.0        0.0       0
5760  20221227   000000    000459  ...         0.0        0.0       0
5761  20221227   000500    000959  ...         0.0        0.0       0
5762  20221227   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-27 00:15:00,666:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672071299, self.tradeDate='20221227', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16807.8, self.close=16817.3, self.high=16821.0, self.low=16807.8, self.vol=1273.102, self.amt=21405036.1324, ukdf['pct'].iloc[-1]=0.000559 , ukdf['amount'].iloc[-1]=21405036.1324, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17324.6704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16817.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16799.5, self.close=16807.9, self.high=16807.9, self.low=16795.1 
2022-12-27 00:10:01,419:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16799.5, self.close=16807.9, self.high=16807.9, self.low=16795.1   
127.0.0.1 - - [27/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-27 00:10:01,475:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221226   234500    234959  1672069799  ...  16792.7 -0.000119   1725    3
1438  20221226   235000    235459  1672070099  ...  16781.1  0.000405   1726    4
1439  20221226   235500    235959  1672070399  ...  16801.1 -0.000042   1727    5
1440  20221227   000000    000459  1672070699  ...  16792.0 -0.000095   1440    0
1441  20221227   000500    000959  1672070999  ...  16795.1  0.000494   1441    1

[5 rows x 11 columns]
2022-12-27 00:10:01,475:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=262, self.factor=0.3837566723925768, self.count=9041 

self.closeSec=1672071299, self.tradeDate='20221227', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16807.8, self.close=16817.3, self.high=16821.0, self.low=16807.8 
2022-12-27 00:15:00,565:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672071299, self.tradeDate='20221227', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16807.8, self.close=16817.3, self.high=16821.0, self.low=16807.8   
127.0.0.1 - - [27/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-27 00:15:00,602:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221226   235000    235459  1672070099  ...  16781.1  0.000405   1726    4
1439  20221226   235500    235959  1672070399  ...  16801.1 -0.000042   1727    5
1440  20221227   000000    000459  1672070699  ...  16792.0 -0.000095   1440    0
1441  20221227   000500    000959  1672070999  ...  16795.1  0.000494   1441    1
1442  20221227   001000    001459  1672071299  ...  16807.8  0.000559   1442    2

[5 rows x 11 columns]
2022-12-27 00:15:00,602:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-27 00:00:20,597:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221226    212959  16849.9  ...  48.750000  0.517589  0.339521
5803  20221226    215959  16842.8  ...  48.333333  0.503888  0.347433
5804  20221226    222959  16830.0  ...  48.333333  0.508989  0.353119
5805  20221226    225959  16835.2  ...  48.333333  0.497199  0.362266
5806  20221226    232959  16823.6  ...  47.916667  0.483546  0.376953

[5 rows x 33 columns]
0.5147058823529411
acc is : 0.5147058823529411
2022-12-27 00:00:20,717:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494823  0.505177       0  ...  1.033342   1.0    0.0  0.951600
540     1  0.490287  0.509713       1  ...  1.033649   1.0    0.0  0.951883
541     1  0.495025  0.504975       0  ...  1.032955   1.0    0.0  0.951244
542     1  0.490637  0.509363       0  ...  1.032126   1.0    0.0  0.950480
543     1  0.488767  0.511233       0  ...  1.031580   1.0    0.0  0.949977

[5 rows x 10 columns]
2022-12-27 00:00:20,742:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494653  0.505347       0  ...  1.033342   1.0    0.0  0.949544
46     1  0.490278  0.509722       1  ...  1.033649   1.0    0.0  0.950314
47     1  0.495019  0.504981       0  ...  1.032955   1.0    0.0  0.949676
48     1  0.490430  0.509570       0  ...  1.032126   1.0    0.0  0.948421
49     1  0.488767  0.511233       0  ...  1.031580   1.0    0.0  0.949977

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '4098.25986620736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16797.86615562', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-27 00:00:01,261:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221226   231000    231959  1672067999  16827.9  16823.8 -0.000244
572  20221226   232000    232959  1672068599  16823.8  16810.1 -0.000814
573  20221226   233000    233959  1672069199    16810    16800 -0.000601
574  20221226   234000    234959  1672069799    16800  16795.1 -0.000292
575  20221226   235000    235959  1672070399  16795.1  16801.2  0.000363
2022-12-27 00:00:01,261:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.023', 'enterprice': '16876.3', 'countrevence': '0', 'unrealprofit': '-4132.2273', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16801.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-27 00:00:02,123:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-27 00:00:02,123:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.023, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41422F1672070402122I0L59'}
2022-12-27 00:00:02,157:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12270000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221226, closeTime:235959, close:16801.2, total:927656.0702451, mom:0.0014856565100906938, thd:0.0, side:sell 
2022-12-27 00:00:02,291:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41422F1672070402122I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672070402236374, 'quantity': '55.023', 'price': '16801.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672070401427, 'updatetime': 1672070402236, 'tradetype': 'usdt', 'selfid': 41422, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672070402236, 'clientorderid': '41422F1672070402122I0L59', 'price': '16801.1', 'quantity': '55.023', 'commission': '924.4469253', 'commissionasset': 'USDT', 'tradetime': 1672070402236, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672070402236}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-27 00:00:02,572:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41422F1672070402122I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672070402236374, 'quantity': '55.023', 'price': '16801.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672070401427, 'updatetime': 1672070402236, 'tradetype': 'usdt', 'selfid': 41422, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672070402236, 'clientorderid': '41422F1672070402122I0L59', 'price': '16801.1', 'quantity': '55.023', 'commission': '924.4469253', 'commissionasset': 'USDT', 'tradetime': 1672070402236, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672070402236}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4520 

self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16801.1', self.close='16807.9'
2022-12-27 00:10:01,771:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16801.1', self.close='16807.9'
2022-12-27 00:10:01,791:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221226   232000    232959  1672068599  16823.8  16810.1 -0.000814
573  20221226   233000    233959  1672069199    16810    16800 -0.000601
574  20221226   234000    234959  1672069799    16800  16795.1 -0.000292
575  20221226   235000    235959  1672070399  16795.1  16801.2  0.000363
576  20221227   000000    000959  1672070999  16801.1  16807.9  0.000399
2022-12-27 00:10:01,791:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-26 23:50:00,550:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4520 

self.closeSec=1672070399, self.tradeDate='20221226', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16795.1', self.close='16801.2'
2022-12-27 00:00:01,255:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672070399, self.tradeDate='20221226', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16795.1', self.close='16801.2'
2022-12-27 00:00:01,303:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221226   231000    231959  1672067999  16827.9  16823.8
17420  20221226   232000    232959  1672068599  16823.8  16810.1
17421  20221226   233000    233959  1672069199    16810    16800
17422  20221226   234000    234959  1672069799    16800  16795.1
17423  20221226   235000    235959  1672070399  16795.1  16801.2
2022-12-27 00:00:01,307:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-27 00:00:01,454:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12270000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221226, closeTime:235959, close:16801.2, total:943443.8042161, pct_pre:0.0024189127999807436, thd:-0.47832208315299124, side:sell 
127.0.0.1 - - [27/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4521 

self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16801.1', self.close='16807.9'
2022-12-27 00:10:01,756:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16801.1', self.close='16807.9'
2022-12-27 00:10:01,772:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221226   232000    232959  1672068599  16823.8  16810.1
17421  20221226   233000    233959  1672069199    16810    16800
17422  20221226   234000    234959  1672069799    16800  16795.1
17423  20221226   235000    235959  1672070399  16795.1  16801.2
17424  20221227   000000    000959  1672070999  16801.1  16807.9
2022-12-27 00:10:01,772:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-27 00:00:01,309:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221226   231000    231959  1672067999  16827.9  16823.8
12236  20221226   232000    232959  1672068599  16823.8  16810.1
12237  20221226   233000    233959  1672069199    16810    16800
12238  20221226   234000    234959  1672069799    16800  16795.1
12239  20221226   235000    235959  1672070399  16795.1  16801.2
2022-12-27 00:00:01,309:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.171', 'enterprice': '16813.9', 'countrevence': '0', 'unrealprofit': '954.6717', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16801.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-27 00:00:02,529:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-27 00:00:02,530:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.171, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41423F1672070402387I0L2'}
2022-12-27 00:00:02,562:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12270000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221226, closeTime:235959, close:16801.2, total:1262653.7592231003, corrDate:20221120, corrVal:0.5514580179044423, side:buy 
127.0.0.1 - - [27/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-27 00:00:02,700:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41423F1672070402387I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672070402629566, 'quantity': '75.171', 'price': '16801.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672070401774, 'updatetime': 1672070402629, 'tradetype': 'usdt', 'selfid': 41423, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672070402629, 'clientorderid': '41423F1672070402387I0L2', 'price': '16801.2', 'quantity': '75.171', 'commission': '1262.9630052', 'commissionasset': 'USDT', 'tradetime': 1672070402629, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672070402629}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-27 00:00:02,930:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41423F1672070402387I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672070402629566, 'quantity': '75.171', 'price': '16801.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672070401774, 'updatetime': 1672070402629, 'tradetype': 'usdt', 'selfid': 41423, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672070402629, 'clientorderid': '41423F1672070402387I0L2', 'price': '16801.2', 'quantity': '75.171', 'commission': '1262.9630052', 'commissionasset': 'USDT', 'tradetime': 1672070402629, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672070402629}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4521 

self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16801.1', self.close='16807.9'
2022-12-27 00:10:01,760:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16801.1', self.close='16807.9'
2022-12-27 00:10:01,775:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221226   232000    232959  1672068599  16823.8  16810.1
12237  20221226   233000    233959  1672069199    16810    16800
12238  20221226   234000    234959  1672069799    16800  16795.1
12239  20221226   235000    235959  1672070399  16795.1  16801.2
12240  20221227   000000    000959  1672070999  16801.1  16807.9
2022-12-27 00:10:01,775:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [27/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4472
self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16799.5, self.close=16807.9, self.high=16807.9, self.low=16795.1, self.vol=529.765, self.amt=8900613.4782 
2022-12-27 00:10:01,490:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221226   234500    234959  ...         0.0        0.0       0
5758  20221226   235000    235459  ...         0.0        0.0       0
5759  20221226   235500    235959  ...         0.0        0.0       0
5760  20221227   000000    000459  ...         0.0        0.0       0
5761  20221227   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-27 00:10:01,491:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672070999, self.tradeDate='20221227', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16799.5, self.close=16807.9, self.high=16807.9, self.low=16795.1, self.vol=529.765, self.amt=8900613.4782, ukdf['pct'].iloc[-1]=0.000494 , ukdf['amount'].iloc[-1]=8900613.4782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [27/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4473
self.closeSec=1672071299, self.tradeDate='20221227', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16807.8, self.close=16817.3, self.high=16821.0, self.low=16807.8, self.vol=1273.102, self.amt=21405036.1324 
2022-12-27 00:15:00,661:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221226   235000    235459  ...         0.0        0.0       0
5759  20221226   235500    235959  ...         0.0        0.0       0
5760  20221227   000000    000459  ...         0.0        0.0       0
5761  20221227   000500    000959  ...         0.0        0.0       0
5762  20221227   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-27 00:15:00,663:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672071299, self.tradeDate='20221227', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16807.8, self.close=16817.3, self.high=16821.0, self.low=16807.8, self.vol=1273.102, self.amt=21405036.1324, ukdf['pct'].iloc[-1]=0.000559 , ukdf['amount'].iloc[-1]=21405036.1324, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221226   120000    155959  1672041599  ...    723  0.023063 -1.041725    -1.0
724  20221226   160000    195959  1672055999  ...    724  0.023302 -1.021403    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-7028.01997985868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16854.77990669', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=188
self.closeSec=1672070399, self.tradeDate='20221226', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16854.1, self.close=16801.2, self.high=16858.9, self.low=16781.1, self.vol=26504.163, self.amt=445860549.2697 
2022-12-27 00:00:01,119:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672070399, self.tradeDate='20221226', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16854.1, self.close=16801.2, self.high=16858.9, self.low=16781.1, self.vol=26504.163, self.amt=445860549.2697 
2022-12-27 00:00:01,182:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221226   040000    075959  ...  24820.079  4.170106e+08  0.002252
722  20221226   080000    115959  ...  28620.905  4.824813e+08  0.003727
723  20221226   120000    155959  ...  24738.987  4.172029e+08 -0.002990
724  20221226   160000    195959  ...  20279.232  3.414780e+08  0.001033
725  20221226   200000    235959  ...  26504.163  4.458605e+08 -0.003133

[5 rows x 11 columns]
2022-12-27 00:00:02,939:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221226   040000    075959  1672012799  ...    721  0.014034 -1.099894    -1.0
722  20221226   080000    115959  1672027199  ...    722  0.016435 -1.074848    -1.0
723  20221226   120000    155959  1672041599  ...    723  0.023063 -1.041725    -1.0
724  20221226   160000    195959  1672055999  ...    724  0.023302 -1.021403    -1.0
725  20221226   200000    235959  1672070399  ...    725  0.023196 -1.002639    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-4168.3532', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16801.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


