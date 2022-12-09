# 20221210 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3578
self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17173.3, self.close=17161.0, self.high=17173.3, self.low=17161.0, self.vol=725.231, self.amt=12450848.8663 
127.0.0.1 - - [10/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-10 00:10:01,475:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221209   234500    234959  ...    0.036284   0.171917       0
5758  20221209   235000    235459  ...    0.036112   0.171643       0
5759  20221209   235500    235959  ...    0.035939   0.171365       0
5760  20221210   000000    000459  ...    0.035765   0.171081       0
5761  20221210   000500    000959  ...    0.035589   0.170793       0

[5 rows x 18 columns]
2022-12-10 00:10:01,475:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17173.3, self.close=17161.0, self.high=17173.3, self.low=17161.0, self.vol=725.231, self.amt=12450848.8663, ukdf['pct'].iloc[-1]=-0.00071 , ukdf['amount'].iloc[-1]=12450848.8663, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.03558906309910381, signal=0, value_std=0.17079290773757957 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-38124.754816236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17162.85415475', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3579
self.closeSec=1670602499, self.tradeDate='20221210', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17161.0, self.close=17159.1, self.high=17162.3, self.low=17155.4, self.vol=560.369, self.amt=9615351.753 
2022-12-10 00:15:00,568:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221209   235000    235459  ...    0.036112   0.171643       0
5759  20221209   235500    235959  ...    0.035939   0.171365       0
5760  20221210   000000    000459  ...    0.035765   0.171081       0
5761  20221210   000500    000959  ...    0.035589   0.170793       0
5762  20221210   001000    001459  ...    0.035412   0.170499       0

[5 rows x 18 columns]
2022-12-10 00:15:00,568:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670602499, self.tradeDate='20221210', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17161.0, self.close=17159.1, self.high=17162.3, self.low=17155.4, self.vol=560.369, self.amt=9615351.753, ukdf['pct'].iloc[-1]=-0.000111 , ukdf['amount'].iloc[-1]=9615351.753, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.03541203502323537, signal=0, value_std=0.17049916814611749 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-37904.8624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17159.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17173.3, self.close=17161.0, self.high=17173.3, self.low=17161.0 
2022-12-10 00:10:01,422:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17173.3, self.close=17161.0, self.high=17173.3, self.low=17161.0   
127.0.0.1 - - [10/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-10 00:10:01,453:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221209   234500    234959  1670600999  ...  17156.0 -0.000757   1725    3
1438  20221209   235000    235459  1670601299  ...  17154.0  0.000251   1726    4
1439  20221209   235500    235959  1670601599  ...  17160.3  0.000583   1727    5
1440  20221210   000000    000459  1670601899  ...  17166.3  0.000163   1440    0
1441  20221210   000500    000959  1670602199  ...  17161.0 -0.000710   1441    1

[5 rows x 11 columns]
2022-12-10 00:10:01,453:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [10/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=48, self.factor=0.33751361232715754, self.count=4145 

self.closeSec=1670602499, self.tradeDate='20221210', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17161.0, self.close=17159.1, self.high=17162.3, self.low=17155.4 
2022-12-10 00:15:00,546:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670602499, self.tradeDate='20221210', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17161.0, self.close=17159.1, self.high=17162.3, self.low=17155.4   
2022-12-10 00:15:00,590:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221209   235000    235459  1670601299  ...  17154.0  0.000251   1726    4
1439  20221209   235500    235959  1670601599  ...  17160.3  0.000583   1727    5
1440  20221210   000000    000459  1670601899  ...  17166.3  0.000163   1440    0
1441  20221210   000500    000959  1670602199  ...  17161.0 -0.000710   1441    1
1442  20221210   001000    001459  1670602499  ...  17155.4 -0.000111   1442    2

[5 rows x 11 columns]
2022-12-10 00:15:00,590:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-10 00:00:26,581:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221209    212959  17250.4  ...  55.000000  0.587461  0.193950
5803  20221209    215959  17220.0  ...  54.583333  0.542432  0.216580
5804  20221209    222959  17143.3  ...  54.583333  0.525091  0.248487
5805  20221209    225959  17111.0  ...  54.583333  0.541484  0.279706
5806  20221209    232959  17146.9  ...  54.583333  0.544835  0.307228

[5 rows x 33 columns]
0.5643382352941176
acc is : 0.5643382352941176
2022-12-10 00:00:26,707:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.482983  0.517017       0  ...  1.009352   1.0    0.0  1.057256
540     1  0.464851  0.535149       0  ...  1.007450   1.0    0.0  1.055264
541     1  0.468455  0.531545       1  ...  1.009534   1.0    0.0  1.057447
542     1  0.486372  0.513628       1  ...  1.009970   1.0    0.0  1.057903
543     1  0.479932  0.520068       1  ...  1.010941   1.0    0.0  1.058921

[5 rows x 10 columns]
2022-12-10 00:00:26,737:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483389  0.516611       0  ...  1.009352   1.0    0.0  1.060992
46     1  0.464843  0.535157       0  ...  1.007450   1.0    0.0  1.056130
47     1  0.468632  0.531368       1  ...  1.009534   1.0    0.0  1.058315
48     1  0.486804  0.513196       1  ...  1.009970   1.0    0.0  1.059098
49     1  0.479932  0.520068       1  ...  1.010941   1.0    0.0  1.058921

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-1740.96320523105', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17166.72936555', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-10 00:00:01,113:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221209   231000    231959  1670599199  17155.4  17148.6 -0.000402
572  20221209   232000    232959  1670599799  17148.6  17153.9  0.000309
573  20221209   233000    233959  1670600399    17154    17172  0.001055
574  20221209   234000    234959  1670600999    17172  17156.1 -0.000926
575  20221209   235000    235959  1670601599  17156.1  17170.4  0.000834
2022-12-10 00:00:01,121:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.262', 'enterprice': '17192.9', 'countrevence': '0', 'unrealprofit': '1186.45349928138', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17170.62420301', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-10 00:00:01,760:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-10 00:00:01,760:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.262, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41330F1670601601756I0L59'}
2022-12-10 00:00:01,795:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12100000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221209, closeTime:235959, close:17170.4, total:914812.5115602001, mom:-0.0013639655505240933, thd:0.0, side:buy 
2022-12-10 00:00:02,318:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41330F1670601601756I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670601602105848, 'quantity': '53.262', 'price': '17170.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670601601302, 'updatetime': 1670601602105, 'tradetype': 'usdt', 'selfid': 41330, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670601602105, 'clientorderid': '41330F1670601601756I0L59', 'price': '17170.4', 'quantity': '53.262', 'commission': '914.5298448', 'commissionasset': 'USDT', 'tradetime': 1670601602105, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670601602105}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-10 00:00:02,821:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41330F1670601601756I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670601602105848, 'quantity': '53.262', 'price': '17170.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670601601302, 'updatetime': 1670601602105, 'tradetype': 'usdt', 'selfid': 41330, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670601602105, 'clientorderid': '41330F1670601601756I0L59', 'price': '17170.4', 'quantity': '53.262', 'commission': '914.5298448', 'commissionasset': 'USDT', 'tradetime': 1670601602105, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670601602105}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2072 

self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17170.3', self.close='17161'
2022-12-10 00:10:01,517:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17170.3', self.close='17161'
2022-12-10 00:10:01,532:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221209   232000    232959  1670599799  17148.6  17153.9  0.000309
573  20221209   233000    233959  1670600399    17154    17172  0.001055
574  20221209   234000    234959  1670600999    17172  17156.1 -0.000926
575  20221209   235000    235959  1670601599  17156.1  17170.4  0.000834
576  20221210   000000    000959  1670602199  17170.3    17161 -0.000547
2022-12-10 00:10:01,532:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-10 00:00:01,136:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221209   231000    231959  1670599199  17155.4  17148.6
17420  20221209   232000    232959  1670599799  17148.6  17153.9
17421  20221209   233000    233959  1670600399    17154    17172
17422  20221209   234000    234959  1670600999    17172  17156.1
17423  20221209   235000    235959  1670601599  17156.1  17170.4
2022-12-10 00:00:01,136:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.498', 'enterprice': '17231.3', 'countrevence': '0', 'unrealprofit': '-3306.70958436102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17170.62420301', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-10 00:00:01,818:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-10 00:00:01,818:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.498, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41331F1670601601817I0L57'}
2022-12-10 00:00:01,840:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12100000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221209, closeTime:235959, close:17170.4, total:938132.3160125999, pct_pre:0.01935533484374341, thd:0.22773179248517256, side:sell 
127.0.0.1 - - [10/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-10 00:00:02,008:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41331F1670601601817I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670601601934162, 'quantity': '54.498', 'price': '17170.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670601601329, 'updatetime': 1670601601934, 'tradetype': 'usdt', 'selfid': 41331, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670601601934, 'clientorderid': '41331F1670601601817I0L57', 'price': '17170.3', 'quantity': '54.498', 'commission': '935.7470094', 'commissionasset': 'USDT', 'tradetime': 1670601601934, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670601601934}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-10 00:00:02,313:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41331F1670601601817I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670601601934162, 'quantity': '54.498', 'price': '17170.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670601601329, 'updatetime': 1670601601934, 'tradetype': 'usdt', 'selfid': 41331, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670601601934, 'clientorderid': '41331F1670601601817I0L57', 'price': '17170.3', 'quantity': '54.498', 'commission': '935.7470094', 'commissionasset': 'USDT', 'tradetime': 1670601601934, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670601601934}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2073 

self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17170.3', self.close='17161'
2022-12-10 00:10:01,528:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17170.3', self.close='17161'
2022-12-10 00:10:01,545:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221209   232000    232959  1670599799  17148.6  17153.9
17421  20221209   233000    233959  1670600399    17154    17172
17422  20221209   234000    234959  1670600999    17172  17156.1
17423  20221209   235000    235959  1670601599  17156.1  17170.4
17424  20221210   000000    000959  1670602199  17170.3    17161
2022-12-10 00:10:01,545:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-10 00:00:01,129:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221209   231000    231959  1670599199  17155.4  17148.6
12236  20221209   232000    232959  1670599799  17148.6  17153.9
12237  20221209   233000    233959  1670600399    17154    17172
12238  20221209   234000    234959  1670600999    17172  17156.1
12239  20221209   235000    235959  1670601599  17156.1  17170.4
2022-12-10 00:00:01,129:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '76.477', 'enterprice': '17194.9', 'countrevence': '0', 'unrealprofit': '1856.54012640423', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17170.62420301', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-10 00:00:02,278:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-10 00:00:02,278:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 76.477, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41332F1670601601975I0L2'}
2022-12-10 00:00:02,359:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12100000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221209, closeTime:235959, close:17170.4, total:1313699.3529327002, corrDate:20221014, corrVal:0.9072263976822903, side:buy 
127.0.0.1 - - [10/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-10 00:00:02,799:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41332F1670601601975I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670601602415427, 'quantity': '76.477', 'price': '17170.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670601601449, 'updatetime': 1670601602415, 'tradetype': 'usdt', 'selfid': 41332, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670601602415, 'clientorderid': '41332F1670601601975I0L2', 'price': '17170.4', 'quantity': '76.477', 'commission': '1313.1406808', 'commissionasset': 'USDT', 'tradetime': 1670601602415, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670601602415}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-10 00:00:03,104:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41332F1670601601975I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670601602415427, 'quantity': '76.477', 'price': '17170.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670601601449, 'updatetime': 1670601602415, 'tradetype': 'usdt', 'selfid': 41332, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670601602415, 'clientorderid': '41332F1670601601975I0L2', 'price': '17170.4', 'quantity': '76.477', 'commission': '1313.1406808', 'commissionasset': 'USDT', 'tradetime': 1670601602415, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670601602415}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2073 

self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17170.3', self.close='17161'
2022-12-10 00:10:01,524:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670602199, self.tradeDate='20221210', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17170.3', self.close='17161'
2022-12-10 00:10:01,542:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221209   232000    232959  1670599799  17148.6  17153.9
12237  20221209   233000    233959  1670600399    17154    17172
12238  20221209   234000    234959  1670600999    17172  17156.1
12239  20221209   235000    235959  1670601599  17156.1  17170.4
12240  20221210   000000    000959  1670602199  17170.3    17161
2022-12-10 00:10:01,542:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221209   120000    155959  1670572799  ...    723  0.723998  0.798378     1.0
724  20221209   160000    195959  1670587199  ...    724  0.613072  0.399523     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-3922.18181444314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17234.59368813', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [10/Dec/2022 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=86
self.closeSec=1670601599, self.tradeDate='20221209', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=17231.8, self.close=17170.4, self.high=17365.4, self.low=17060.0, self.vol=130054.486, self.amt=2233481757.6049 
2022-12-10 00:00:00,981:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670601599, self.tradeDate='20221209', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=17231.8, self.close=17170.4, self.high=17365.4, self.low=17060.0, self.vol=130054.486, self.amt=2233481757.6049 
2022-12-10 00:00:01,110:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20221209   040000    075959  ...   58532.020  1.007112e+09 -0.001502
722  20221209   080000    115959  ...   42568.695  7.331506e+08 -0.001278
723  20221209   120000    155959  ...   23221.849  3.995087e+08  0.000564
724  20221209   160000    195959  ...   34061.603  5.864694e+08  0.001633
725  20221209   200000    235959  ...  130054.486  2.233482e+09 -0.003563

[5 rows x 11 columns]
2022-12-10 00:00:02,644:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221209   040000    075959  1670543999  ...    721  0.876128  1.378563     1.0
722  20221209   080000    115959  1670558399  ...    722  0.843817  1.237965     1.0
723  20221209   120000    155959  1670572799  ...    723  0.723998  0.798378     1.0
724  20221209   160000    195959  1670587199  ...    724  0.613072  0.399523     NaN
725  20221209   200000    235959  1670601599  ...    725  0.637512  0.481243     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-7680.31593077832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17170.48577444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


