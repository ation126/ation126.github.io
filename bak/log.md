# 20221212 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4154
self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17148.9, self.close=17146.7, self.high=17149.5, self.low=17146.6, self.vol=218.141, self.amt=3740769.1746 
127.0.0.1 - - [12/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 00:10:01,443:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221211   234500    234959  ...         0.0        0.0       0
5758  20221211   235000    235459  ...         0.0        0.0       0
5759  20221211   235500    235959  ...         0.0        0.0       0
5760  20221212   000000    000459  ...         0.0        0.0       0
5761  20221212   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-12 00:10:01,444:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17148.9, self.close=17146.7, self.high=17149.5, self.low=17146.6, self.vol=218.141, self.amt=3740769.1746, ukdf['pct'].iloc[-1]=-0.000128 , ukdf['amount'].iloc[-1]=3740769.1746, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-37146.6448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17146.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4155
self.closeSec=1670775299, self.tradeDate='20221212', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17146.6, self.close=17138.1, self.high=17146.7, self.low=17138.0, self.vol=403.142, self.amt=6910564.808 
127.0.0.1 - - [12/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-12 00:15:00,615:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221211   235000    235459  ...         0.0        0.0       0
5759  20221211   235500    235959  ...         0.0        0.0       0
5760  20221212   000000    000459  ...         0.0        0.0       0
5761  20221212   000500    000959  ...         0.0        0.0       0
5762  20221212   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-12 00:15:00,615:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670775299, self.tradeDate='20221212', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17146.6, self.close=17138.1, self.high=17146.7, self.low=17138.0, self.vol=403.142, self.amt=6910564.808, ukdf['pct'].iloc[-1]=-0.000502 , ukdf['amount'].iloc[-1]=6910564.808, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-36660.9346161704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17138.52850665', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=95, self.factor=0.5243575093195233, self.count=4720 

self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17148.9, self.close=17146.7, self.high=17149.5, self.low=17146.6 
2022-12-12 00:10:01,446:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17148.9, self.close=17146.7, self.high=17149.5, self.low=17146.6   
2022-12-12 00:10:01,503:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221211   234500    234959  1670773799  ...  17136.6  0.000560   1725    3
1438  20221211   235000    235459  1670774099  ...  17146.1  0.000152   1726    4
1439  20221211   235500    235959  1670774399  ...  17145.4 -0.000192   1727    5
1440  20221212   000000    000459  1670774699  ...  17145.4  0.000198   1440    0
1441  20221212   000500    000959  1670774999  ...  17146.6 -0.000128   1441    1

[5 rows x 11 columns]
2022-12-12 00:10:01,504:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=95, self.factor=0.5243575093195233, self.count=4721 

self.closeSec=1670775299, self.tradeDate='20221212', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17146.6, self.close=17138.1, self.high=17146.7, self.low=17138.0 
2022-12-12 00:15:00,550:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670775299, self.tradeDate='20221212', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17146.6, self.close=17138.1, self.high=17146.7, self.low=17138.0   
127.0.0.1 - - [12/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-12 00:15:00,575:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221211   235000    235459  1670774099  ...  17146.1  0.000152   1726    4
1439  20221211   235500    235959  1670774399  ...  17145.4 -0.000192   1727    5
1440  20221212   000000    000459  1670774699  ...  17145.4  0.000198   1440    0
1441  20221212   000500    000959  1670774999  ...  17146.6 -0.000128   1441    1
1442  20221212   001000    001459  1670775299  ...  17138.0 -0.000502   1442    2

[5 rows x 11 columns]
2022-12-12 00:15:00,575:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-12 00:00:19,830:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221211    212959  17153.7  ...  54.166667  0.513763  0.468230
5803  20221211    215959  17152.6  ...  54.166667  0.509024  0.462632
5804  20221211    222959  17147.4  ...  53.750000  0.495399  0.466604
5805  20221211    225959  17132.7  ...  54.166667  0.509777  0.460436
5806  20221211    232959  17148.5  ...  53.750000  0.507288  0.456345

[5 rows x 33 columns]
0.5753676470588235
acc is : 0.5753676470588235
2022-12-12 00:00:19,936:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494365  0.505635       0  ...  0.962378   1.0    0.0  1.016202
540     1  0.494344  0.505656       0  ...  0.961542   1.0    0.0  1.015319
541     1  0.489200  0.510800       1  ...  0.962440   1.0    0.0  1.016268
542     1  0.497628  0.502372       0  ...  0.962288   1.0    0.0  1.016108
543     1  0.493354  0.506646       0  ...  0.962266   1.0    0.0  1.016084

[5 rows x 10 columns]
2022-12-12 00:00:19,957:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495501  0.504499       0  ...  0.962378   1.0    0.0  1.017541
46     1  0.493909  0.506091       0  ...  0.961542   1.0    0.0  1.016524
47     1  0.489974  0.510026       1  ...  0.962440   1.0    0.0  1.017473
48     1  0.498013  0.501987       0  ...  0.962288   1.0    0.0  1.016306
49     1  0.493354  0.506646       0  ...  0.962266   1.0    0.0  1.016084

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-2451.50304314382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17147.92654362', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-12 00:00:01,449:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221211   231000    231959  1670771999  17135.3  17145.5  0.000595
572  20221211   232000    232959  1670772599  17145.4  17145.8  0.000017
573  20221211   233000    233959  1670773199  17145.9  17140.9 -0.000286
574  20221211   234000    234959  1670773799  17140.9  17146.2  0.000309
575  20221211   235000    235959  1670774399  17146.1  17145.5 -0.000041
2022-12-12 00:00:01,449:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.53', 'enterprice': '17157.7', 'countrevence': '0', 'unrealprofit': '-613.2510915254', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17146.24378682', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-12 00:00:02,422:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-12 00:00:02,422:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.53, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41340F1670774402421I0L59'}
2022-12-12 00:00:02,447:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12120000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221211, closeTime:235959, close:17145.5, total:917533.2293190002, mom:4.961090478428076e-06, thd:0.0, side:sell 
127.0.0.1 - - [12/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-12 00:00:02,603:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41340F1670774402421I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670774402529487, 'quantity': '53.53', 'price': '17145.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670774401892, 'updatetime': 1670774402529, 'tradetype': 'usdt', 'selfid': 41340, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670774402529, 'clientorderid': '41340F1670774402421I0L59', 'price': '17145.4', 'quantity': '53.53', 'commission': '917.793262', 'commissionasset': 'USDT', 'tradetime': 1670774402529, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670774402529}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-12 00:00:02,947:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41340F1670774402421I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670774402529487, 'quantity': '53.53', 'price': '17145.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670774401892, 'updatetime': 1670774402529, 'tradetype': 'usdt', 'selfid': 41340, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670774402529, 'clientorderid': '41340F1670774402421I0L59', 'price': '17145.4', 'quantity': '53.53', 'commission': '917.793262', 'commissionasset': 'USDT', 'tradetime': 1670774402529, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670774402529}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2360 

self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17145.5', self.close='17146.7'
2022-12-12 00:10:01,530:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17145.5', self.close='17146.7'
2022-12-12 00:10:01,599:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221211   232000    232959  1670772599  17145.4  17145.8  0.000017
573  20221211   233000    233959  1670773199  17145.9  17140.9 -0.000286
574  20221211   234000    234959  1670773799  17140.9  17146.2  0.000309
575  20221211   235000    235959  1670774399  17146.1  17145.5 -0.000041
576  20221212   000000    000959  1670774999  17145.5  17146.7  0.000070
2022-12-12 00:10:01,599:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-11 23:50:00,792:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2360 

self.closeSec=1670774399, self.tradeDate='20221211', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='17146.1', self.close='17145.5'
2022-12-12 00:00:01,499:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670774399, self.tradeDate='20221211', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='17146.1', self.close='17145.5'
2022-12-12 00:00:01,546:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221211   231000    231959  1670771999  17135.3  17145.5
17420  20221211   232000    232959  1670772599  17145.4  17145.8
17421  20221211   233000    233959  1670773199  17145.9  17140.9
17422  20221211   234000    234959  1670773799  17140.9  17146.2
17423  20221211   235000    235959  1670774399  17146.1  17145.5
2022-12-12 00:00:01,546:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-12 00:00:01,678:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12120000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221211, closeTime:235959, close:17145.5, total:935796.4056934, pct_pre:-0.002215528470413064, thd:-0.3318295908525826, side:sell 
127.0.0.1 - - [12/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2361 

self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17145.5', self.close='17146.7'
2022-12-12 00:10:01,516:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17145.5', self.close='17146.7'
2022-12-12 00:10:01,532:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221211   232000    232959  1670772599  17145.4  17145.8
17421  20221211   233000    233959  1670773199  17145.9  17140.9
17422  20221211   234000    234959  1670773799  17140.9  17146.2
17423  20221211   235000    235959  1670774399  17146.1  17145.5
17424  20221212   000000    000959  1670774999  17145.5  17146.7
2022-12-12 00:10:01,532:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-12 00:00:01,544:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221211   231000    231959  1670771999  17135.3  17145.5
12236  20221211   232000    232959  1670772599  17145.4  17145.8
12237  20221211   233000    233959  1670773199  17145.9  17140.9
12238  20221211   234000    234959  1670773799  17140.9  17146.2
12239  20221211   235000    235959  1670774399  17146.1  17145.5
2022-12-12 00:00:01,544:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '76.397', 'enterprice': '17126', 'countrevence': '0', 'unrealprofit': '-1546.56458168754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17146.24378682', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-12 00:00:02,905:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-12 00:00:02,905:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 76.397, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41341F1670774402781I0L2'}
2022-12-12 00:00:02,960:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12120000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221211, closeTime:235959, close:17145.5, total:1307066.6469780002, corrDate:20221121, corrVal:0.9250540415469103, side:buy 
127.0.0.1 - - [12/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-12 00:00:03,062:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41341F1670774402781I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670774403001328, 'quantity': '76.397', 'price': '17145.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670774401907, 'updatetime': 1670774403001, 'tradetype': 'usdt', 'selfid': 41341, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670774403001, 'clientorderid': '41341F1670774402781I0L2', 'price': '17145.5', 'quantity': '76.397', 'commission': '1309.8647635', 'commissionasset': 'USDT', 'tradetime': 1670774403001, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670774403001}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-12 00:00:03,314:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41341F1670774402781I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670774403001328, 'quantity': '76.397', 'price': '17145.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670774401907, 'updatetime': 1670774403001, 'tradetype': 'usdt', 'selfid': 41341, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670774403001, 'clientorderid': '41341F1670774402781I0L2', 'price': '17145.5', 'quantity': '76.397', 'commission': '1309.8647635', 'commissionasset': 'USDT', 'tradetime': 1670774403001, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670774403001}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2361 

self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17145.5', self.close='17146.7'
127.0.0.1 - - [12/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 00:10:01,554:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17145.5', self.close='17146.7'
2022-12-12 00:10:01,606:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221211   232000    232959  1670772599  17145.4  17145.8
12237  20221211   233000    233959  1670773199  17145.9  17140.9
12238  20221211   234000    234959  1670773799  17140.9  17146.2
12239  20221211   235000    235959  1670774399  17146.1  17145.5
12240  20221212   000000    000959  1670774999  17145.5  17146.7
2022-12-12 00:10:01,606:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [12/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=152
self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17148.9, self.close=17146.7, self.high=17149.5, self.low=17146.6, self.vol=218.141, self.amt=3740769.1746 
2022-12-12 00:10:01,565:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221211   234500    234959  ...    0.561497   0.138106       0
5758  20221211   235000    235459  ...    0.561736   0.138347       0
5759  20221211   235500    235959  ...    0.561939   0.138525       0
5760  20221212   000000    000459  ...    0.562147   0.138707       0
5761  20221212   000500    000959  ...    0.562356   0.138890       0

[5 rows x 18 columns]
2022-12-12 00:10:01,567:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670774999, self.tradeDate='20221212', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17148.9, self.close=17146.7, self.high=17149.5, self.low=17146.6, self.vol=218.141, self.amt=3740769.1746, ukdf['pct'].iloc[-1]=-0.000128 , ukdf['amount'].iloc[-1]=3740769.1746, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.8846665647411104, value_mean=0.562356218840672, signal=0, value_std=0.1388904909803832 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=153
self.closeSec=1670775299, self.tradeDate='20221212', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17146.6, self.close=17138.1, self.high=17146.7, self.low=17138.0, self.vol=403.142, self.amt=6910564.808 
127.0.0.1 - - [12/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-12 00:15:00,594:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221211   235000    235459  ...    0.561736   0.138347       0
5759  20221211   235500    235959  ...    0.561939   0.138525       0
5760  20221212   000000    000459  ...    0.562147   0.138707       0
5761  20221212   000500    000959  ...    0.562356   0.138890       0
5762  20221212   001000    001459  ...    0.562561   0.139063       0

[5 rows x 18 columns]
2022-12-12 00:15:00,595:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670775299, self.tradeDate='20221212', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17146.6, self.close=17138.1, self.high=17146.7, self.low=17138.0, self.vol=403.142, self.amt=6910564.808, ukdf['pct'].iloc[-1]=-0.000502 , ukdf['amount'].iloc[-1]=6910564.808, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.8758620895050504, value_mean=0.5625610573196356, signal=0, value_std=0.1390625821586254 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221211   120000    155959  1670745599  ...    723  0.516006  0.036525     NaN
724  20221211   160000    195959  1670759999  ...    724  0.597746  0.319120     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-8242.2532', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17160.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [12/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=98
self.closeSec=1670774399, self.tradeDate='20221211', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=17160.8, self.close=17145.5, self.high=17161.1, self.low=17121.0, self.vol=19880.891, self.amt=340805775.1584 
2022-12-12 00:00:01,309:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670774399, self.tradeDate='20221211', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=17160.8, self.close=17145.5, self.high=17161.1, self.low=17121.0, self.vol=19880.891, self.amt=340805775.1584 
2022-12-12 00:00:01,398:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221211   040000    075959  ...  26181.427  4.484955e+08 -0.002697
722  20221211   080000    115959  ...  16510.061  2.829950e+08  0.001618
723  20221211   120000    155959  ...  18948.471  3.252470e+08  0.001499
724  20221211   160000    195959  ...  16708.791  2.866225e+08 -0.000734
725  20221211   200000    235959  ...  19880.891  3.408058e+08 -0.000892

[5 rows x 11 columns]
2022-12-12 00:00:03,183:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221211   040000    075959  1670716799  ...    721  0.540221  0.120987     NaN
722  20221211   080000    115959  1670731199  ...    722  0.528735  0.081942     NaN
723  20221211   120000    155959  1670745599  ...    723  0.516006  0.036525     NaN
724  20221211   160000    195959  1670759999  ...    724  0.597746  0.319120     NaN
725  20221211   200000    235959  1670774399  ...    725  0.578351  0.236847     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-9085.2865064389', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17146.51916505', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


