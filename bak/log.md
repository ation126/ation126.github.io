# 20221216 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5306
self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17431.6, self.close=17415.5, self.high=17433.0, self.low=17408.0, self.vol=1395.454, self.amt=24304756.7716 
127.0.0.1 - - [16/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-16 00:10:01,465:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221215   234500    234959  ...         0.0        0.0       0
5758  20221215   235000    235459  ...         0.0        0.0       0
5759  20221215   235500    235959  ...         0.0        0.0       0
5760  20221216   000000    000459  ...         0.0        0.0       0
5761  20221216   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-16 00:10:01,465:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17431.6, self.close=17415.5, self.high=17433.0, self.low=17408.0, self.vol=1395.454, self.amt=24304756.7716, ukdf['pct'].iloc[-1]=-0.000918 , ukdf['amount'].iloc[-1]=24304756.7716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-53327.9712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17415.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5307
self.closeSec=1671120899, self.tradeDate='20221216', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17415.4, self.close=17437.2, self.high=17437.2, self.low=17415.4, self.vol=1126.201, self.amt=19624979.1275 
127.0.0.1 - - [16/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-16 00:15:00,606:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221215   235000    235459  ...         0.0        0.0       0
5759  20221215   235500    235959  ...         0.0        0.0       0
5760  20221216   000000    000459  ...         0.0        0.0       0
5761  20221216   000500    000959  ...         0.0        0.0       0
5762  20221216   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-16 00:15:00,606:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671120899, self.tradeDate='20221216', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17415.4, self.close=17437.2, self.high=17437.2, self.low=17415.4, self.vol=1126.201, self.amt=19624979.1275, ukdf['pct'].iloc[-1]=0.001246 , ukdf['amount'].iloc[-1]=19624979.1275, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-54627.7728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17437.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.663747920059504, self.count=5872 

self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17431.6, self.close=17415.5, self.high=17433.0, self.low=17408.0 
2022-12-16 00:10:01,404:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17431.6, self.close=17415.5, self.high=17433.0, self.low=17408.0   
2022-12-16 00:10:01,460:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221215   234500    234959  1671119399  ...  17355.0 -0.000919   1725    3
1438  20221215   235000    235459  1671119699  ...  17392.4  0.000741   1726    4
1439  20221215   235500    235959  1671119999  ...  17403.6  0.000333   1727    5
1440  20221216   000000    000459  1671120299  ...  17415.4  0.000723   1440    0
1441  20221216   000500    000959  1671120599  ...  17408.0 -0.000918   1441    1

[5 rows x 11 columns]
2022-12-16 00:10:01,460:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.663747920059504, self.count=5873 

self.closeSec=1671120899, self.tradeDate='20221216', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17415.4, self.close=17437.2, self.high=17437.2, self.low=17415.4 
2022-12-16 00:15:00,549:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671120899, self.tradeDate='20221216', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17415.4, self.close=17437.2, self.high=17437.2, self.low=17415.4   
2022-12-16 00:15:00,596:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221215   235000    235459  1671119699  ...  17392.4  0.000741   1726    4
1439  20221215   235500    235959  1671119999  ...  17403.6  0.000333   1727    5
1440  20221216   000000    000459  1671120299  ...  17415.4  0.000723   1440    0
1441  20221216   000500    000959  1671120599  ...  17408.0 -0.000918   1441    1
1442  20221216   001000    001459  1671120899  ...  17415.4  0.001246   1442    2

[5 rows x 11 columns]
2022-12-16 00:15:00,597:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-16 00:00:19,544:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221215    212959  17674.7  ...  50.416667  0.454178  0.799312
5803  20221215    215959  17538.8  ...  50.000000  0.442973  0.809072
5804  20221215    222959  17497.8  ...  50.000000  0.454561  0.815763
5805  20221215    225959  17532.3  ...  49.583333  0.431805  0.824591
5806  20221215    232959  17448.0  ...  49.166667  0.425106  0.833182

[5 rows x 33 columns]
0.5863970588235294
acc is : 0.5863970588235294
2022-12-16 00:00:19,668:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.458458  0.541542       0  ...  1.043401  -1.0    0.0  1.030015
540     1  0.470990  0.529010       1  ...  1.041337  -1.0    0.0  1.032052
541     1  0.487150  0.512850       0  ...  1.046439  -1.0    0.0  1.026996
542     1  0.455838  0.544162       0  ...  1.048029  -1.0    0.0  1.025436
543     1  0.467331  0.532669       0  ...  1.048029  -1.0    0.0  1.025436

[5 rows x 10 columns]
2022-12-16 00:00:19,692:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.458238  0.541762       0  ...  1.043401  -1.0    0.0  1.028139
46     1  0.470987  0.529013       1  ...  1.041337  -1.0    0.0  1.031700
47     1  0.487114  0.512886       0  ...  1.046439  -1.0    0.0  1.026645
48     1  0.455626  0.544374       0  ...  1.048029  -1.0    0.0  1.024941
49     1  0.467331  0.532669       0  ...  1.048029  -1.0    0.0  1.025436

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '13170.0072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17420.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-16 00:00:01,458:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221215   231000    231959  1671117599  17460.6  17465.4  0.000275
572  20221215   232000    232959  1671118199  17464.7  17420.1 -0.002594
573  20221215   233000    233959  1671118799    17420  17441.7  0.001240
574  20221215   234000    234959  1671119399  17441.8  17400.1 -0.002385
575  20221215   235000    235959  1671119999  17400.1    17424  0.001374
2022-12-16 00:00:01,458:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.786', 'enterprice': '17737.2', 'countrevence': '0', 'unrealprofit': '-16845.7752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17424', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-16 00:00:02,043:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-16 00:00:02,043:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.786, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41368F1671120002042I0L59'}
2022-12-16 00:00:02,059:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12160000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221215, closeTime:235959, close:17424, total:953059.0261608001, mom:0.0005179163898207939, thd:0.0, side:sell 
127.0.0.1 - - [16/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-16 00:00:02,389:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41368F1671120002042I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671120002210408, 'quantity': '53.786', 'price': '17423.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671120001647, 'updatetime': 1671120002210, 'tradetype': 'usdt', 'selfid': 41368, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671120002210, 'clientorderid': '41368F1671120002042I0L59', 'price': '17423.9', 'quantity': '53.786', 'commission': '937.1618854', 'commissionasset': 'USDT', 'tradetime': 1671120002210, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671120002210}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-16 00:00:02,639:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41368F1671120002042I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671120002210408, 'quantity': '53.786', 'price': '17423.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671120001647, 'updatetime': 1671120002210, 'tradetype': 'usdt', 'selfid': 41368, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671120002210, 'clientorderid': '41368F1671120002042I0L59', 'price': '17423.9', 'quantity': '53.786', 'commission': '937.1618854', 'commissionasset': 'USDT', 'tradetime': 1671120002210, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671120002210}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2936 

self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17424', self.close='17415.5'
2022-12-16 00:10:01,525:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17424', self.close='17415.5'
2022-12-16 00:10:01,532:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221215   232000    232959  1671118199  17464.7  17420.1 -0.002594
573  20221215   233000    233959  1671118799    17420  17441.7  0.001240
574  20221215   234000    234959  1671119399  17441.8  17400.1 -0.002385
575  20221215   235000    235959  1671119999  17400.1    17424  0.001374
576  20221216   000000    000959  1671120599    17424  17415.5 -0.000488
2022-12-16 00:10:01,532:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-15 23:50:00,565:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2936 

self.closeSec=1671119999, self.tradeDate='20221215', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='17400.1', self.close='17424'
127.0.0.1 - - [16/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-16 00:00:01,425:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671119999, self.tradeDate='20221215', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='17400.1', self.close='17424'
2022-12-16 00:00:01,455:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221215   231000    231959  1671117599  17460.6  17465.4
17420  20221215   232000    232959  1671118199  17464.7  17420.1
17421  20221215   233000    233959  1671118799    17420  17441.7
17422  20221215   234000    234959  1671119399  17441.8  17400.1
17423  20221215   235000    235959  1671119999  17400.1    17424
2022-12-16 00:00:01,456:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-16 00:00:01,546:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12160000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221215, closeTime:235959, close:17424, total:947411.5003109, pct_pre:-0.02150900402637035, thd:-0.16843909939899077, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2937 

self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17424', self.close='17415.5'
127.0.0.1 - - [16/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-16 00:10:01,529:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17424', self.close='17415.5'
2022-12-16 00:10:01,548:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221215   232000    232959  1671118199  17464.7  17420.1
17421  20221215   233000    233959  1671118799    17420  17441.7
17422  20221215   234000    234959  1671119399  17441.8  17400.1
17423  20221215   235000    235959  1671119999  17400.1    17424
17424  20221216   000000    000959  1671120599    17424  17415.5
2022-12-16 00:10:01,548:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-16 00:00:01,461:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221215   231000    231959  1671117599  17460.6  17465.4
12236  20221215   232000    232959  1671118199  17464.7  17420.1
12237  20221215   233000    233959  1671118799    17420  17441.7
12238  20221215   234000    234959  1671119399  17441.8  17400.1
12239  20221215   235000    235959  1671119999  17400.1    17424
2022-12-16 00:00:01,461:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '68.969', 'enterprice': '17829.8', 'countrevence': '0', 'unrealprofit': '-27987.6202', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17424', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-16 00:00:02,022:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-16 00:00:02,022:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 68.969, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41367F1671120002020I0L2'}
2022-12-16 00:00:02,046:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12160000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221215, closeTime:235959, close:17424, total:1228473.7727237998, corrDate:20221206, corrVal:0.9189289398274029, side:sell 
2022-12-16 00:00:02,159:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41367F1671120002020I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671120002119373, 'quantity': '68.969', 'price': '17423.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671120001627, 'updatetime': 1671120002119, 'tradetype': 'usdt', 'selfid': 41367, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671120002119, 'clientorderid': '41367F1671120002020I0L2', 'price': '17423.9', 'quantity': '68.969', 'commission': '1201.7089591', 'commissionasset': 'USDT', 'tradetime': 1671120002119, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671120002119}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-16 00:00:02,382:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41367F1671120002020I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671120002119373, 'quantity': '68.969', 'price': '17423.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671120001627, 'updatetime': 1671120002119, 'tradetype': 'usdt', 'selfid': 41367, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671120002119, 'clientorderid': '41367F1671120002020I0L2', 'price': '17423.9', 'quantity': '68.969', 'commission': '1201.7089591', 'commissionasset': 'USDT', 'tradetime': 1671120002119, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671120002119}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2937 

self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17424', self.close='17415.5'
2022-12-16 00:10:01,550:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17424', self.close='17415.5'
2022-12-16 00:10:01,556:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221215   232000    232959  1671118199  17464.7  17420.1
12237  20221215   233000    233959  1671118799    17420  17441.7
12238  20221215   234000    234959  1671119399  17441.8  17400.1
12239  20221215   235000    235959  1671119999  17400.1    17424
12240  20221216   000000    000959  1671120599    17424  17415.5
2022-12-16 00:10:01,556:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1304
self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17431.6, self.close=17415.5, self.high=17433.0, self.low=17408.0, self.vol=1395.454, self.amt=24304756.7716 
127.0.0.1 - - [16/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-16 00:10:01,433:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221215   234500    234959  ...    0.253588   0.315769       0
5758  20221215   235000    235459  ...    0.253353   0.315789       0
5759  20221215   235500    235959  ...    0.253120   0.315811       0
5760  20221216   000000    000459  ...    0.252888   0.315833       0
5761  20221216   000500    000959  ...    0.252656   0.315856       0

[5 rows x 18 columns]
2022-12-16 00:10:01,433:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671120599, self.tradeDate='20221216', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17431.6, self.close=17415.5, self.high=17433.0, self.low=17408.0, self.vol=1395.454, self.amt=24304756.7716, ukdf['pct'].iloc[-1]=-0.000918 , ukdf['amount'].iloc[-1]=24304756.7716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.25265594299487865, signal=0, value_std=0.31585552768039316 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1305
self.closeSec=1671120899, self.tradeDate='20221216', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17415.4, self.close=17437.2, self.high=17437.2, self.low=17415.4, self.vol=1126.201, self.amt=19624979.1275 
127.0.0.1 - - [16/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-16 00:15:00,567:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221215   235000    235459  ...    0.253353   0.315789       0
5759  20221215   235500    235959  ...    0.253120   0.315811       0
5760  20221216   000000    000459  ...    0.252888   0.315833       0
5761  20221216   000500    000959  ...    0.252656   0.315856       0
5762  20221216   001000    001459  ...    0.252412   0.315870       0

[5 rows x 18 columns]
2022-12-16 00:15:00,567:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671120899, self.tradeDate='20221216', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17415.4, self.close=17437.2, self.high=17437.2, self.low=17415.4, self.vol=1126.201, self.amt=19624979.1275, ukdf['pct'].iloc[-1]=0.001246 , ukdf['amount'].iloc[-1]=19624979.1275, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.2524123688549635, signal=0, value_std=0.3158699502826706 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221215   120000    155959  1671091199  ...    723  1.103680  1.479993     1.0
724  20221215   160000    195959  1671105599  ...    724  1.062907  1.317741     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-2367.2148', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17712', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [16/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=122
self.closeSec=1671119999, self.tradeDate='20221215', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=17712.1, self.close=17424.0, self.high=17714.6, self.low=17355.0, self.vol=146628.881, self.amt=2567878251.11814 
2022-12-16 00:00:01,321:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671119999, self.tradeDate='20221215', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=17712.1, self.close=17424.0, self.high=17714.6, self.low=17355.0, self.vol=146628.881, self.amt=2567878251.11814 
2022-12-16 00:00:01,342:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20221215   040000    075959  ...   98675.813  1.756578e+09  0.000809
722  20221215   080000    115959  ...   74507.679  1.318699e+09 -0.004437
723  20221215   120000    155959  ...   27803.765  4.924763e+08 -0.002195
724  20221215   160000    195959  ...   52699.528  9.310796e+08  0.001476
725  20221215   200000    235959  ...  146628.881  2.567878e+09 -0.016266

[5 rows x 11 columns]
2022-12-16 00:00:03,089:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221215   040000    075959  1671062399  ...    721  1.168074  1.773576     1.0
722  20221215   080000    115959  1671076799  ...    722  1.174786  1.746192     1.0
723  20221215   120000    155959  1671091199  ...    723  1.103680  1.479993     1.0
724  20221215   160000    195959  1671105599  ...    724  1.062907  1.317741     1.0
725  20221215   200000    235959  1671119999  ...    725  1.039420  1.214469     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-17756.7828', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17424', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


