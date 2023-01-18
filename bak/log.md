# 20230119 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15098
self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20911.9, self.close=20918.2, self.high=20949.5, self.low=20800.0, self.vol=13902.838, self.amt=290358495.3583 
127.0.0.1 - - [19/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 00:10:01,500:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230118   234500    234959  ...         0.0        0.0       0
5758  20230118   235000    235459  ...         0.0        0.0       0
5759  20230118   235500    235959  ...         0.0        0.0       0
5760  20230119   000000    000459  ...         0.0        0.0       0
5761  20230119   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 00:10:01,500:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20911.9, self.close=20918.2, self.high=20949.5, self.low=20800.0, self.vol=13902.838, self.amt=290358495.3583, ukdf['pct'].iloc[-1]=-0.00011 , ukdf['amount'].iloc[-1]=290358495.3583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-264369.97459656144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20922.57929069', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15099
self.closeSec=1674058499, self.tradeDate='20230119', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20920.3, self.close=20872.3, self.high=20924.3, self.low=20800.0, self.vol=10122.14, self.amt=211174603.6272 
127.0.0.1 - - [19/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-19 00:15:00,889:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230118   235000    235459  ...         0.0        0.0       0
5759  20230118   235500    235959  ...         0.0        0.0       0
5760  20230119   000000    000459  ...         0.0        0.0       0
5761  20230119   000500    000959  ...         0.0        0.0       0
5762  20230119   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 00:15:00,892:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674058499, self.tradeDate='20230119', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20920.3, self.close=20872.3, self.high=20924.3, self.low=20800.0, self.vol=10122.14, self.amt=211174603.6272, ukdf['pct'].iloc[-1]=-0.002194 , ukdf['amount'].iloc[-1]=211174603.6272, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-261617.2979840776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20876.83552885', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20911.9, self.close=20918.2, self.high=20949.5, self.low=20800.0 
2023-01-19 00:10:01,433:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20911.9, self.close=20918.2, self.high=20949.5, self.low=20800.0   
127.0.0.1 - - [19/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 00:10:01,477:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230118   234500    234959  1674056999  ...  21196.8 -0.003298   1725    3
1438  20230118   235000    235459  1674057299  ...  20850.0 -0.015726   1726    4
1439  20230118   235500    235959  1674057599  ...  20810.0  0.007486   1727    5
1440  20230119   000000    000459  1674057899  ...  20870.3 -0.005472   1440    0
1441  20230119   000500    000959  1674058199  ...  20800.0 -0.000110   1441    1

[5 rows x 11 columns]
2023-01-19 00:10:01,477:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=527, self.factor=0.5075796717521949, self.count=15665 

self.closeSec=1674058499, self.tradeDate='20230119', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20920.3, self.close=20872.3, self.high=20924.3, self.low=20800.0 
2023-01-19 00:15:00,709:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674058499, self.tradeDate='20230119', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20920.3, self.close=20872.3, self.high=20924.3, self.low=20800.0   
127.0.0.1 - - [19/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-19 00:15:00,799:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230118   235000    235459  1674057299  ...  20850.0 -0.015726   1726    4
1439  20230118   235500    235959  1674057599  ...  20810.0  0.007486   1727    5
1440  20230119   000000    000459  1674057899  ...  20870.3 -0.005472   1440    0
1441  20230119   000500    000959  1674058199  ...  20800.0 -0.000110   1441    1
1442  20230119   001000    001459  1674058499  ...  20800.0 -0.002194   1442    2

[5 rows x 11 columns]
2023-01-19 00:15:00,800:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-19 00:00:34,565:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230118    212959  21257.9  ...  51.666667  0.527381  0.573667
5803  20230118    215959  21256.7  ...  52.083333  0.561199  0.549267
5804  20230118    222959  21401.2  ...  51.666667  0.560391  0.544751
5805  20230118    225959  21399.8  ...  51.666667  0.565170  0.537991
5806  20230118    232959  21419.9  ...  51.666667  0.566742  0.530849

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-01-19 00:00:34,787:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.509645  0.490355       1  ...  1.061598   1.0    0.0  1.263368
540     0  0.552923  0.447077       0  ...  1.061454   1.0    0.0  1.263197
541     0  0.525971  0.474029       1  ...  1.062530   1.0    0.0  1.264478
542     0  0.530966  0.469034       1  ...  1.062882   1.0    0.0  1.264897
543     0  0.525899  0.474101       0  ...  1.043462   1.0    0.0  1.241786

[5 rows x 10 columns]
2023-01-19 00:00:34,825:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
15     0  0.509428  0.490572       1  ...  1.061598   1.0    0.0  1.264659
16     0  0.552984  0.447016       0  ...  1.061454   1.0    0.0  1.264294
17     0  0.525853  0.474147       1  ...  1.062530   1.0    0.0  1.265576
18     0  0.530826  0.469174       1  ...  1.062882   1.0    0.0  1.265084
19     0  0.525899  0.474101       0  ...  1.043462   1.0    0.0  1.241786

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.369', 'enterprice': '21276.8', 'countrevence': '0', 'unrealprofit': '-11383.0128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20945.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-19 00:00:01,882:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230118   231000    231959  1674055199  21500.1  21423.3 -0.003632
572  20230118   232000    232959  1674055799  21427.9  21424.1  0.000037
573  20230118   233000    233959  1674056399  21427.2  21331.9 -0.004304
574  20230118   234000    234959  1674056999  21334.2  21212.9 -0.005578
575  20230118   235000    235959  1674057599  21215.2  21035.6 -0.008358
2023-01-19 00:00:01,882:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.517', 'enterprice': '21307.5', 'countrevence': '0', 'unrealprofit': '12023.7471', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21031.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-19 00:00:02,812:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-19 00:00:02,812:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 43.517, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41550F1674057602810I0L59'}
2023-01-19 00:00:02,850:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1190000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230118, closeTime:235959, close:21035.6, total:926311.2390225, mom:-0.015083755026553791, thd:0.0, side:buy 
127.0.0.1 - - [19/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-19 00:00:02,977:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41550F1674057602810I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674057602936292, 'quantity': '43.517', 'price': '21030.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674057602308, 'updatetime': 1674057602936, 'tradetype': 'usdt', 'selfid': 41550, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674057602936, 'clientorderid': '41550F1674057602810I0L59', 'price': '21030.6', 'quantity': '43.517', 'commission': '915.1886202', 'commissionasset': 'USDT', 'tradetime': 1674057602936, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674057602936}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-19 00:00:03,210:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41550F1674057602810I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674057602936292, 'quantity': '43.517', 'price': '21030.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674057602308, 'updatetime': 1674057602936, 'tradetype': 'usdt', 'selfid': 41550, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674057602936, 'clientorderid': '41550F1674057602810I0L59', 'price': '21030.6', 'quantity': '43.517', 'commission': '915.1886202', 'commissionasset': 'USDT', 'tradetime': 1674057602936, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674057602936}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7832 

self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21035.5', self.close='20918.2'
2023-01-19 00:10:01,571:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21035.5', self.close='20918.2'
127.0.0.1 - - [19/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 00:10:01,609:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230118   232000    232959  1674055799  21427.9  21424.1  0.000037
573  20230118   233000    233959  1674056399  21427.2  21331.9 -0.004304
574  20230118   234000    234959  1674056999  21334.2  21212.9 -0.005578
575  20230118   235000    235959  1674057599  21215.2  21035.6 -0.008358
576  20230119   000000    000959  1674058199  21035.5  20918.2 -0.005581
2023-01-19 00:10:01,609:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-19 00:00:01,878:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230118   231000    231959  1674055199  21500.1  21423.3
17420  20230118   232000    232959  1674055799  21427.9  21424.1
17421  20230118   233000    233959  1674056399  21427.2  21331.9
17422  20230118   234000    234959  1674056999  21334.2  21212.9
17423  20230118   235000    235959  1674057599  21215.2  21035.6
2023-01-19 00:00:01,878:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '44.736', 'enterprice': '21226.6', 'countrevence': '0', 'unrealprofit': '-8497.49658829632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21036.65238313', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-19 00:00:02,788:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-19 00:00:02,788:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 44.736, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41549F1674057602786I0L57'}
2023-01-19 00:00:02,824:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1190000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230118, closeTime:235959, close:21035.6, total:948643.5844223999, pct_pre:0.003906379316052533, thd:0.4287718092276174, side:sell 
2023-01-19 00:00:03,232:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41549F1674057602786I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674057603135425, 'quantity': '44.736', 'price': '21030.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674057602095, 'updatetime': 1674057603135, 'tradetype': 'usdt', 'selfid': 41549, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674057603135, 'clientorderid': '41549F1674057602786I0L57', 'price': '21030.5', 'quantity': '44.736', 'commission': '940.820448', 'commissionasset': 'USDT', 'tradetime': 1674057603135, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674057603135}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-19 00:00:03,516:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41549F1674057602786I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674057603135425, 'quantity': '44.736', 'price': '21030.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674057602095, 'updatetime': 1674057603135, 'tradetype': 'usdt', 'selfid': 41549, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674057603135, 'clientorderid': '41549F1674057602786I0L57', 'price': '21030.5', 'quantity': '44.736', 'commission': '940.820448', 'commissionasset': 'USDT', 'tradetime': 1674057603135, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674057603135}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7833 

self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21035.5', self.close='20918.2'
2023-01-19 00:10:01,561:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21035.5', self.close='20918.2'
127.0.0.1 - - [19/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 00:10:01,616:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230118   232000    232959  1674055799  21427.9  21424.1
17421  20230118   233000    233959  1674056399  21427.2  21331.9
17422  20230118   234000    234959  1674056999  21334.2  21212.9
17423  20230118   235000    235959  1674057599  21215.2  21035.6
17424  20230119   000000    000959  1674058199  21035.5  20918.2
2023-01-19 00:10:01,616:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-19 00:00:01,879:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230118   231000    231959  1674055199  21500.1  21423.3
12236  20230118   232000    232959  1674055799  21427.9  21424.1
12237  20230118   233000    233959  1674056399  21427.2  21331.9
12238  20230118   234000    234959  1674056999  21334.2  21212.9
12239  20230118   235000    235959  1674057599  21215.2  21035.6
2023-01-19 00:00:01,879:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.057', 'enterprice': '21229.9', 'countrevence': '0', 'unrealprofit': '10542.4259', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21031.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-19 00:00:02,837:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-19 00:00:02,838:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.057, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41551F1674057602835I0L2'}
2023-01-19 00:00:02,865:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1190000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230118, closeTime:235959, close:21035.6, total:1125268.4094957002, corrDate:20221209, corrVal:0.8929648372092709, side:buy 
127.0.0.1 - - [19/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-19 00:00:03,517:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41551F1674057602835I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674057603202321, 'quantity': '53.057', 'price': '21030.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674057602462, 'updatetime': 1674057603202, 'tradetype': 'usdt', 'selfid': 41551, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674057603202, 'clientorderid': '41551F1674057602835I0L2', 'price': '21030.6', 'quantity': '53.057', 'commission': '1115.8205442', 'commissionasset': 'USDT', 'tradetime': 1674057603202, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674057603202}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-19 00:00:03,801:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41551F1674057602835I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674057603202321, 'quantity': '53.057', 'price': '21030.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674057602462, 'updatetime': 1674057603202, 'tradetype': 'usdt', 'selfid': 41551, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674057603202, 'clientorderid': '41551F1674057602835I0L2', 'price': '21030.6', 'quantity': '53.057', 'commission': '1115.8205442', 'commissionasset': 'USDT', 'tradetime': 1674057603202, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674057603202}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7833 

self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21035.5', self.close='20918.2'
127.0.0.1 - - [19/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 00:10:01,588:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21035.5', self.close='20918.2'
2023-01-19 00:10:01,595:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230118   232000    232959  1674055799  21427.9  21424.1
12237  20230118   233000    233959  1674056399  21427.2  21331.9
12238  20230118   234000    234959  1674056999  21334.2  21212.9
12239  20230118   235000    235959  1674057599  21215.2  21035.6
12240  20230119   000000    000959  1674058199  21035.5  20918.2
2023-01-19 00:10:01,611:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11096
self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20911.9, self.close=20918.2, self.high=20949.5, self.low=20800.0, self.vol=13902.838, self.amt=290358495.3583 
127.0.0.1 - - [19/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 00:10:01,551:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230118   234500    234959  ...         0.0        0.0       0
5758  20230118   235000    235459  ...         0.0        0.0       0
5759  20230118   235500    235959  ...         0.0        0.0       0
5760  20230119   000000    000459  ...         0.0        0.0       0
5761  20230119   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 00:10:01,556:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674058199, self.tradeDate='20230119', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20911.9, self.close=20918.2, self.high=20949.5, self.low=20800.0, self.vol=13902.838, self.amt=290358495.3583, ukdf['pct'].iloc[-1]=-0.00011 , ukdf['amount'].iloc[-1]=290358495.3583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11097
self.closeSec=1674058499, self.tradeDate='20230119', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20920.3, self.close=20872.3, self.high=20924.3, self.low=20800.0, self.vol=10122.14, self.amt=211174603.6272 
127.0.0.1 - - [19/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-19 00:15:00,908:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230118   235000    235459  ...         0.0        0.0       0
5759  20230118   235500    235959  ...         0.0        0.0       0
5760  20230119   000000    000459  ...         0.0        0.0       0
5761  20230119   000500    000959  ...         0.0        0.0       0
5762  20230119   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 00:15:00,908:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674058499, self.tradeDate='20230119', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20920.3, self.close=20872.3, self.high=20924.3, self.low=20800.0, self.vol=10122.14, self.amt=211174603.6272, ukdf['pct'].iloc[-1]=-0.002194 , ukdf['amount'].iloc[-1]=211174603.6272, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230118   120000    155959  1674028799  ...    723  0.179287 -1.690226    -1.0
724  20230118   160000    195959  1674043199  ...    724  0.172129 -1.682806    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-1794.09959989603', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21202.04190351', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [19/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=326
self.closeSec=1674057599, self.tradeDate='20230118', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=21201.7, self.close=21035.6, self.high=21672.0, self.low=20810.0, self.vol=269413.61, self.amt=5745100498.14781 
2023-01-19 00:00:01,625:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674057599, self.tradeDate='20230118', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=21201.7, self.close=21035.6, self.high=21672.0, self.low=20810.0, self.vol=269413.61, self.amt=5745100498.14781 
2023-01-19 00:00:01,707:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230118   040000    075959  ...   56117.691  1.193678e+09 -0.009795
722  20230118   080000    115959  ...   58477.632  1.242592e+09  0.005959
723  20230118   120000    155959  ...   26297.724  5.595176e+08  0.002522
724  20230118   160000    195959  ...   45098.726  9.571280e+08 -0.004979
725  20230118   200000    235959  ...  269413.610  5.745100e+09 -0.007830

[5 rows x 11 columns]
2023-01-19 00:00:04,009:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230118   040000    075959  1673999999  ...    721  0.123877 -1.893662    -1.0
722  20230118   080000    115959  1674014399  ...    722  0.005990 -2.167398    -1.0
723  20230118   120000    155959  1674028799  ...    723  0.179287 -1.690226    -1.0
724  20230118   160000    195959  1674043199  ...    724  0.172129 -1.682806    -1.0
725  20230118   200000    235959  1674057599  ...    725  0.189080 -1.617061    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '6963.6292', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21030.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


