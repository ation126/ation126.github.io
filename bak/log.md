# 20221215 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5018
self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=18096.0, self.close=18086.1, self.high=18114.0, self.low=18086.1, self.vol=2884.297, self.amt=52213673.3449 
2022-12-15 00:10:01,617:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221214   234500    234959  ...         0.0        0.0       0
5758  20221214   235000    235459  ...         0.0        0.0       0
5759  20221214   235500    235959  ...         0.0        0.0       0
5760  20221215   000000    000459  ...         0.0        0.0       0
5761  20221215   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-15 00:10:01,617:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=18096.0, self.close=18086.1, self.high=18114.0, self.low=18086.1, self.vol=2884.297, self.amt=52213673.3449, ukdf['pct'].iloc[-1]=-0.000553 , ukdf['amount'].iloc[-1]=52213673.3449, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-93881.78287232512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18089.42002912', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5019
self.closeSec=1671034499, self.tradeDate='20221215', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=18080.8, self.close=18076.1, self.high=18090.5, self.low=18065.1, self.vol=2636.306, self.amt=47651481.9958 
127.0.0.1 - - [15/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-15 00:15:00,653:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221214   235000    235459  ...         0.0        0.0       0
5759  20221214   235500    235959  ...         0.0        0.0       0
5760  20221215   000000    000459  ...         0.0        0.0       0
5761  20221215   000500    000959  ...         0.0        0.0       0
5762  20221215   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-15 00:15:00,653:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671034499, self.tradeDate='20221215', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=18080.8, self.close=18076.1, self.high=18090.5, self.low=18065.1, self.vol=2636.306, self.amt=47651481.9958, ukdf['pct'].iloc[-1]=-0.000553 , ukdf['amount'].iloc[-1]=47651481.9958, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-93080.2368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18076.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=18096.0, self.close=18086.1, self.high=18114.0, self.low=18086.1 
127.0.0.1 - - [15/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-15 00:10:01,570:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=18096.0, self.close=18086.1, self.high=18114.0, self.low=18086.1   
2022-12-15 00:10:01,588:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221214   234500    234959  1671032999  ...  18057.8  0.000498   1725    3
1438  20221214   235000    235459  1671033299  ...  18067.1  0.000531   1726    4
1439  20221214   235500    235959  1671033599  ...  18050.2 -0.001328   1727    5
1440  20221215   000000    000459  1671033899  ...  18053.1  0.002349   1440    0
1441  20221215   000500    000959  1671034199  ...  18086.1 -0.000553   1441    1

[5 rows x 11 columns]
2022-12-15 00:10:01,588:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=38, self.factor=0.2218340786758041, self.count=5585 

self.closeSec=1671034499, self.tradeDate='20221215', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=18080.8, self.close=18076.1, self.high=18090.5, self.low=18065.1 
2022-12-15 00:15:00,557:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671034499, self.tradeDate='20221215', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=18080.8, self.close=18076.1, self.high=18090.5, self.low=18065.1   
127.0.0.1 - - [15/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-15 00:15:00,638:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221214   235000    235459  1671033299  ...  18067.1  0.000531   1726    4
1439  20221214   235500    235959  1671033599  ...  18050.2 -0.001328   1727    5
1440  20221215   000000    000459  1671033899  ...  18053.1  0.002349   1440    0
1441  20221215   000500    000959  1671034199  ...  18086.1 -0.000553   1441    1
1442  20221215   001000    001459  1671034499  ...  18065.1 -0.000553   1442    2

[5 rows x 11 columns]
2022-12-15 00:15:00,638:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-15 00:00:19,359:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221214    212959  17910.1  ...  50.833333  0.657358  0.300435
5803  20221214    215959  17903.2  ...  50.833333  0.649681  0.295243
5804  20221214    222959  17889.9  ...  51.250000  0.665734  0.280520
5805  20221214    225959  17943.4  ...  51.250000  0.695558  0.267080
5806  20221214    232959  18055.8  ...  50.833333  0.681308  0.262592

[5 rows x 33 columns]
0.5863970588235294
acc is : 0.5863970588235294
2022-12-15 00:00:19,475:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.498607  0.501393       0  ...  1.022000   1.0    0.0  1.055159
540     1  0.495803  0.504197       1  ...  1.025062   1.0    0.0  1.058320
541     0  0.514466  0.485534       1  ...  1.031478   1.0    0.0  1.064944
542     0  0.532516  0.467484       0  ...  1.030004   1.0    0.0  1.063422
543     0  0.500101  0.499899       1  ...  1.031421   1.0    0.0  1.064885

[5 rows x 10 columns]
2022-12-15 00:00:19,499:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499297  0.500703       0  ...  1.022000   1.0    0.0  1.053841
46     1  0.496241  0.503759       1  ...  1.025062   1.0    0.0  1.057291
47     0  0.514854  0.485146       1  ...  1.031478   1.0    0.0  1.063908
48     0  0.532575  0.467425       0  ...  1.030004   1.0    0.0  1.065017
49     0  0.500101  0.499899       1  ...  1.031421   1.0    0.0  1.064885

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '32086.6399', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18061.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-15 00:00:01,386:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221214   231000    231959  1671031199  18046.3  18065.6  0.001075
572  20221214   232000    232959  1671031799  18065.6  18029.9 -0.001976
573  20221214   233000    233959  1671032399  18029.9  18042.2  0.000682
574  20221214   234000    234959  1671032999  18042.3  18068.3  0.001447
575  20221214   235000    235959  1671033599    18068  18054.8 -0.000747
2022-12-15 00:00:01,386:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.894', 'enterprice': '17800.2', 'countrevence': '0', 'unrealprofit': '13466.8124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18054.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-15 00:00:02,962:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-15 00:00:02,962:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 52.894, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41360F1671033602960I0L59'}
2022-12-15 00:00:02,982:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12150000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221214, closeTime:235959, close:18054.8, total:940582.2550211999, mom:0.008097764933379104, thd:0.0, side:sell 
2022-12-15 00:00:03,115:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41360F1671033602960I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671033603070597, 'quantity': '52.894', 'price': '18054.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671033602095, 'updatetime': 1671033603070, 'tradetype': 'usdt', 'selfid': 41360, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671033603070, 'clientorderid': '41360F1671033602960I0L59', 'price': '18054.7', 'quantity': '52.894', 'commission': '954.9853018', 'commissionasset': 'USDT', 'tradetime': 1671033603070, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671033603070}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-15 00:00:03,389:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41360F1671033602960I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671033603070597, 'quantity': '52.894', 'price': '18054.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671033602095, 'updatetime': 1671033603070, 'tradetype': 'usdt', 'selfid': 41360, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671033603070, 'clientorderid': '41360F1671033602960I0L59', 'price': '18054.7', 'quantity': '52.894', 'commission': '954.9853018', 'commissionasset': 'USDT', 'tradetime': 1671033603070, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671033603070}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2792 

self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='18054.8', self.close='18080.8'
2022-12-15 00:10:01,888:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='18054.8', self.close='18080.8'
2022-12-15 00:10:01,901:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221214   232000    232959  1671031799  18065.6  18029.9 -0.001976
573  20221214   233000    233959  1671032399  18029.9  18042.2  0.000682
574  20221214   234000    234959  1671032999  18042.3  18068.3  0.001447
575  20221214   235000    235959  1671033599    18068  18054.8 -0.000747
576  20221215   000000    000959  1671034199  18054.8  18080.8  0.001440
2022-12-15 00:10:01,901:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-15 00:00:01,411:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221214   231000    231959  1671031199  18046.3  18065.6
17420  20221214   232000    232959  1671031799  18065.6  18029.9
17421  20221214   233000    233959  1671032399  18029.9  18042.2
17422  20221214   234000    234959  1671032999  18042.3  18068.3
17423  20221214   235000    235959  1671033599    18068  18054.8
2022-12-15 00:00:01,413:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.475', 'enterprice': '17815.3', 'countrevence': '0', 'unrealprofit': '12567.7625', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18054.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-15 00:00:03,541:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-15 00:00:03,542:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 52.475, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41361F1671033603540I0L57'}
2022-12-15 00:00:03,561:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12150000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221214, closeTime:235959, close:18054.8, total:933923.0096324999, pct_pre:0.0018895831107261785, thd:0.09753207810551429, side:sell 
2022-12-15 00:00:03,691:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41361F1671033603540I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671033603634755, 'quantity': '52.475', 'price': '18054.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671033602336, 'updatetime': 1671033603634, 'tradetype': 'usdt', 'selfid': 41361, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671033603634, 'clientorderid': '41361F1671033603540I0L57', 'price': '18054.7', 'quantity': '52.475', 'commission': '947.4203825', 'commissionasset': 'USDT', 'tradetime': 1671033603634, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671033603634}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-15 00:00:03,941:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41361F1671033603540I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671033603634755, 'quantity': '52.475', 'price': '18054.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671033602336, 'updatetime': 1671033603634, 'tradetype': 'usdt', 'selfid': 41361, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671033603634, 'clientorderid': '41361F1671033603540I0L57', 'price': '18054.7', 'quantity': '52.475', 'commission': '947.4203825', 'commissionasset': 'USDT', 'tradetime': 1671033603634, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671033603634}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2793 

self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='18054.8', self.close='18080.8'
2022-12-15 00:10:01,893:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='18054.8', self.close='18080.8'
127.0.0.1 - - [15/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-15 00:10:01,910:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221214   232000    232959  1671031799  18065.6  18029.9
17421  20221214   233000    233959  1671032399  18029.9  18042.2
17422  20221214   234000    234959  1671032999  18042.3  18068.3
17423  20221214   235000    235959  1671033599    18068  18054.8
17424  20221215   000000    000959  1671034199  18054.8  18080.8
2022-12-15 00:10:01,911:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-15 00:00:01,392:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221214   231000    231959  1671031199  18046.3  18065.6
12236  20221214   232000    232959  1671031799  18065.6  18029.9
12237  20221214   233000    233959  1671032399  18029.9  18042.2
12238  20221214   234000    234959  1671032999  18042.3  18068.3
12239  20221214   235000    235959  1671033599    18068  18054.8
2022-12-15 00:00:01,392:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '70.356', 'enterprice': '17774.9', 'countrevence': '0', 'unrealprofit': '-19692.6444', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18054.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-15 00:00:02,494:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-15 00:00:02,494:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 70.356, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41359F1671033602492I0L2'}
2022-12-15 00:00:02,603:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12150000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221214, closeTime:235959, close:18054.8, total:1249320.2935356002, corrDate:20221119, corrVal:0.6829065131253725, side:buy 
2022-12-15 00:00:02,664:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41359F1671033602492I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671033602613328, 'quantity': '70.356', 'price': '18054.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671033601744, 'updatetime': 1671033602613, 'tradetype': 'usdt', 'selfid': 41359, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671033602613, 'clientorderid': '41359F1671033602492I0L2', 'price': '18054.8', 'quantity': '70.356', 'commission': '1270.2635088', 'commissionasset': 'USDT', 'tradetime': 1671033602613, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671033602613}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-15 00:00:03,008:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41359F1671033602492I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671033602613328, 'quantity': '70.356', 'price': '18054.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671033601744, 'updatetime': 1671033602613, 'tradetype': 'usdt', 'selfid': 41359, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671033602613, 'clientorderid': '41359F1671033602492I0L2', 'price': '18054.8', 'quantity': '70.356', 'commission': '1270.2635088', 'commissionasset': 'USDT', 'tradetime': 1671033602613, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671033602613}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2793 

self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='18054.8', self.close='18080.8'
2022-12-15 00:10:01,883:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='18054.8', self.close='18080.8'
2022-12-15 00:10:01,905:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221214   232000    232959  1671031799  18065.6  18029.9
12237  20221214   233000    233959  1671032399  18029.9  18042.2
12238  20221214   234000    234959  1671032999  18042.3  18068.3
12239  20221214   235000    235959  1671033599    18068  18054.8
12240  20221215   000000    000959  1671034199  18054.8  18080.8
2022-12-15 00:10:01,905:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1016
self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=18096.0, self.close=18086.1, self.high=18114.0, self.low=18086.1, self.vol=2884.297, self.amt=52213673.3449 
2022-12-15 00:10:01,613:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221214   234500    234959  ...    0.331022   0.310254       0
5758  20221214   235000    235459  ...    0.330791   0.310336       0
5759  20221214   235500    235959  ...    0.330560   0.310416       0
5760  20221215   000000    000459  ...    0.330325   0.310496       0
5761  20221215   000500    000959  ...    0.330076   0.310569       0

[5 rows x 18 columns]
2022-12-15 00:10:01,614:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671034199, self.tradeDate='20221215', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=18096.0, self.close=18086.1, self.high=18114.0, self.low=18086.1, self.vol=2884.297, self.amt=52213673.3449, ukdf['pct'].iloc[-1]=-0.000553 , ukdf['amount'].iloc[-1]=52213673.3449, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.33007587978247066, signal=0, value_std=0.3105689821604896 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1017
self.closeSec=1671034499, self.tradeDate='20221215', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=18080.8, self.close=18076.1, self.high=18090.5, self.low=18065.1, self.vol=2636.306, self.amt=47651481.9958 
2022-12-15 00:15:00,652:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221214   235000    235459  ...    0.330791   0.310336       0
5759  20221214   235500    235959  ...    0.330560   0.310416       0
5760  20221215   000000    000459  ...    0.330325   0.310496       0
5761  20221215   000500    000959  ...    0.330076   0.310569       0
5762  20221215   001000    001459  ...    0.329825   0.310641       0

[5 rows x 18 columns]
2022-12-15 00:15:00,652:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671034499, self.tradeDate='20221215', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=18080.8, self.close=18076.1, self.high=18090.5, self.low=18065.1, self.vol=2636.306, self.amt=47651481.9958, ukdf['pct'].iloc[-1]=-0.000553 , ukdf['amount'].iloc[-1]=47651481.9958, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.32982463978103244, signal=0, value_std=0.31064077764212994 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221214   120000    155959  1671004799  ...    723  0.955077  1.230219     1.0
724  20221214   160000    195959  1671019199  ...    724  0.924404  1.102377     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '3606.93', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17823.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--: 127.0.0.1 - - [15/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=116
self.closeSec=1671033599, self.tradeDate='20221214', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=17823.9, self.close=18053.7, self.high=18111.5, self.low=17814.0, self.vol=137064.54, self.amt=2462616425.04247 
2022-12-15 00:00:01,190:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671033599, self.tradeDate='20221214', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=17823.9, self.close=18053.7, self.high=18111.5, self.low=17814.0, self.vol=137064.54, self.amt=2462616425.04247 
2022-12-15 00:00:01,221:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20221214   040000    075959  ...   33535.147  5.955503e+08  0.002057
722  20221214   080000    115959  ...   30721.609  5.467234e+08  0.000298
723  20221214   120000    155959  ...   22263.865  3.958589e+08  0.001389
724  20221214   160000    195959  ...   37760.719  6.730514e+08  0.000938
725  20221214   200000    235959  ...  137064.540  2.462616e+09  0.012898

[5 rows x 11 columns]
2022-12-15 00:00:03,017:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221214   040000    075959  1670975999  ...    721  1.139591  1.922200     1.0
722  20221214   080000    115959  1670990399  ...    722  1.019275  1.475146     1.0
723  20221214   120000    155959  1671004799  ...    723  0.955077  1.230219     1.0
724  20221214   160000    195959  1671019199  ...    724  0.924404  1.102377     1.0
725  20221214   200000    235959  1671033599  ...    725  1.005027  1.339233     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '16013.68542814752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18055.97971832', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


