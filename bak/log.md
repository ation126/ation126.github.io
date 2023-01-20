# 20230121 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15674
self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=21159.0, self.close=21145.0, self.high=21159.1, self.low=21144.8, self.vol=831.296, self.amt=17583356.5258 
127.0.0.1 - - [21/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 00:10:01,531:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230120   234500    234959  ...         0.0        0.0       0
5758  20230120   235000    235459  ...         0.0        0.0       0
5759  20230120   235500    235959  ...         0.0        0.0       0
5760  20230121   000000    000459  ...         0.0        0.0       0
5761  20230121   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 00:10:01,531:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=21159.0, self.close=21145.0, self.high=21159.1, self.low=21144.8, self.vol=831.296, self.amt=17583356.5258, ukdf['pct'].iloc[-1]=-0.000662 , ukdf['amount'].iloc[-1]=17583356.5258, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-277776.13764248896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21145.36184596', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15675
self.closeSec=1674231299, self.tradeDate='20230121', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=21145.0, self.close=21165.9, self.high=21168.4, self.low=21141.0, self.vol=1258.18, self.amt=26613522.3507 
2023-01-21 00:15:00,754:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230120   235000    235459  ...         0.0        0.0       0
5759  20230120   235500    235959  ...         0.0        0.0       0
5760  20230121   000000    000459  ...         0.0        0.0       0
5761  20230121   000500    000959  ...         0.0        0.0       0
5762  20230121   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 00:15:00,755:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674231299, self.tradeDate='20230121', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=21145.0, self.close=21165.9, self.high=21168.4, self.low=21141.0, self.vol=1258.18, self.amt=26613522.3507, ukdf['pct'].iloc[-1]=0.000988 , ukdf['amount'].iloc[-1]=26613522.3507, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-279006.024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21165.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=21159.0, self.close=21145.0, self.high=21159.1, self.low=21144.8 
2023-01-21 00:10:01,421:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=21159.0, self.close=21145.0, self.high=21159.1, self.low=21144.8   
127.0.0.1 - - [21/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 00:10:01,456:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230120   234500    234959  1674229799  ...  21102.7  0.000085   1725    3
1438  20230120   235000    235459  1674230099  ...  21108.1  0.000810   1726    4
1439  20230120   235500    235959  1674230399  ...  21129.0  0.000270   1727    5
1440  20230121   000000    000459  1674230699  ...  21136.1  0.000913   1440    0
1441  20230121   000500    000959  1674230999  ...  21144.8 -0.000662   1441    1

[5 rows x 11 columns]
2023-01-21 00:10:01,458:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [21/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=46, self.factor=0.4197624478900168, self.count=16241 

self.closeSec=1674231299, self.tradeDate='20230121', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=21145.0, self.close=21165.9, self.high=21168.4, self.low=21141.0 
2023-01-21 00:15:00,667:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674231299, self.tradeDate='20230121', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=21145.0, self.close=21165.9, self.high=21168.4, self.low=21141.0   
2023-01-21 00:15:00,708:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230120   235000    235459  1674230099  ...  21108.1  0.000810   1726    4
1439  20230120   235500    235959  1674230399  ...  21129.0  0.000270   1727    5
1440  20230121   000000    000459  1674230699  ...  21136.1  0.000913   1440    0
1441  20230121   000500    000959  1674230999  ...  21144.8 -0.000662   1441    1
1442  20230121   001000    001459  1674231299  ...  21141.0  0.000988   1442    2

[5 rows x 11 columns]
2023-01-21 00:15:00,708:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-21 00:00:34,258:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5802  20230120    212959  21085.2  ...     52.5  0.521784  0.427563
5803  20230120    215959  21064.2  ...     52.5  0.518806  0.427933
5804  20230120    222959  21053.0  ...     52.5  0.524079  0.426449
5805  20230120    225959  21074.7  ...     52.5  0.541626  0.411687
5806  20230120    232959  21148.0  ...     52.5  0.545574  0.398638

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-01-21 00:00:34,424:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.513633  0.486367       0  ...  1.018529   1.0    0.0  1.224739
540     0  0.513162  0.486838       1  ...  1.019569   1.0    0.0  1.225990
541     0  0.521554  0.478446       1  ...  1.023129   1.0    0.0  1.230272
542     0  0.531918  0.468082       1  ...  1.023952   1.0    0.0  1.231261
543     0  0.519238  0.480762       0  ...  1.022728   1.0    0.0  1.229789

[5 rows x 10 columns]
2023-01-21 00:00:34,451:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513638  0.486362       0  ...  1.018529   1.0    0.0  1.223906
46     0  0.513179  0.486821       1  ...  1.019569   1.0    0.0  1.226618
47     0  0.521551  0.478449       1  ...  1.023129   1.0    0.0  1.230902
48     0  0.531842  0.468158       1  ...  1.023952   1.0    0.0  1.230888
49     0  0.519238  0.480762       0  ...  1.022728   1.0    0.0  1.229789

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.709', 'enterprice': '20883.4', 'countrevence': '0', 'unrealprofit': '8681.69395891291', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21140.94824999', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-21 00:00:01,481:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230120   231000    231959  1674227999  21174.2  21160.9 -0.000633
572  20230120   232000    232959  1674228599  21160.8    21165  0.000194
573  20230120   233000    233959  1674229199  21165.1  21130.2 -0.001644
574  20230120   234000    234959  1674229799  21130.1  21116.9 -0.000629
575  20230120   235000    235959  1674230399  21116.9  21139.7  0.001080
2023-01-21 00:00:01,481:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '44.252', 'enterprice': '21097.2', 'countrevence': '0', 'unrealprofit': '1932.86400175648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21140.87856824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-21 00:00:02,210:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-21 00:00:02,210:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 44.252, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41566F1674230402209I0L59'}
2023-01-21 00:00:02,235:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1210000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230120, closeTime:235959, close:21139.7, total:932659.7011056001, mom:0.0005403737950573362, thd:0.0, side:sell 
2023-01-21 00:00:02,733:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41566F1674230402209I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674230402323853, 'quantity': '44.252', 'price': '21139.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674230401886, 'updatetime': 1674230402323, 'tradetype': 'usdt', 'selfid': 41566, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674230402323, 'clientorderid': '41566F1674230402209I0L59', 'price': '21139.7', 'quantity': '44.252', 'commission': '935.4740044', 'commissionasset': 'USDT', 'tradetime': 1674230402323, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674230402323}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-21 00:00:02,866:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41566F1674230402209I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674230402323853, 'quantity': '44.252', 'price': '21139.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674230401886, 'updatetime': 1674230402323, 'tradetype': 'usdt', 'selfid': 41566, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674230402323, 'clientorderid': '41566F1674230402209I0L59', 'price': '21139.7', 'quantity': '44.252', 'commission': '935.4740044', 'commissionasset': 'USDT', 'tradetime': 1674230402323, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674230402323}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8120 

self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21139.7', self.close='21145.1'
2023-01-21 00:10:01,542:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21139.7', self.close='21145.1'
127.0.0.1 - - [21/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 00:10:01,562:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230120   232000    232959  1674228599  21160.8    21165  0.000194
573  20230120   233000    233959  1674229199  21165.1  21130.2 -0.001644
574  20230120   234000    234959  1674229799  21130.1  21116.9 -0.000629
575  20230120   235000    235959  1674230399  21116.9  21139.7  0.001080
576  20230121   000000    000959  1674230999  21139.7  21145.1  0.000255
2023-01-21 00:10:01,562:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-21 00:00:01,526:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230120   231000    231959  1674227999  21174.2  21160.9
17420  20230120   232000    232959  1674228599  21160.8    21165
17421  20230120   233000    233959  1674229199  21165.1  21130.2
17422  20230120   234000    234959  1674229799  21130.1  21116.9
17423  20230120   235000    235959  1674230399  21116.9  21139.7
2023-01-21 00:00:01,526:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '44.851', 'enterprice': '20956.1', 'countrevence': '0', 'unrealprofit': '8287.50356413224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21140.87856824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-21 00:00:02,131:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-21 00:00:02,132:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 44.851, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41564F1674230402128I0L57'}
2023-01-21 00:00:02,188:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1210000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230120, closeTime:235959, close:21139.7, total:938962.1390589, pct_pre:0.003524380958765727, thd:0.429162150347924, side:sell 
2023-01-21 00:00:02,296:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41564F1674230402128I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674230402253490, 'quantity': '44.851', 'price': '21139.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674230401738, 'updatetime': 1674230402253, 'tradetype': 'usdt', 'selfid': 41564, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674230402253, 'clientorderid': '41564F1674230402128I0L57', 'price': '21139.7', 'quantity': '44.851', 'commission': '948.1366847', 'commissionasset': 'USDT', 'tradetime': 1674230402253, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674230402253}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-21 00:00:02,506:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41564F1674230402128I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674230402253490, 'quantity': '44.851', 'price': '21139.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674230401738, 'updatetime': 1674230402253, 'tradetype': 'usdt', 'selfid': 41564, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674230402253, 'clientorderid': '41564F1674230402128I0L57', 'price': '21139.7', 'quantity': '44.851', 'commission': '948.1366847', 'commissionasset': 'USDT', 'tradetime': 1674230402253, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674230402253}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8121 

self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21139.7', self.close='21145.1'
2023-01-21 00:10:01,553:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21139.7', self.close='21145.1'
127.0.0.1 - - [21/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 00:10:01,567:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230120   232000    232959  1674228599  21160.8    21165
17421  20230120   233000    233959  1674229199  21165.1  21130.2
17422  20230120   234000    234959  1674229799  21130.1  21116.9
17423  20230120   235000    235959  1674230399  21116.9  21139.7
17424  20230121   000000    000959  1674230999  21139.7  21145.1
2023-01-21 00:10:01,567:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-21 00:00:01,563:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230120   231000    231959  1674227999  21174.2  21160.9
12236  20230120   232000    232959  1674228599  21160.8    21165
12237  20230120   233000    233959  1674229199  21165.1  21130.2
12238  20230120   234000    234959  1674229799  21130.1  21116.9
12239  20230120   235000    235959  1674230399  21116.9  21139.7
2023-01-21 00:00:01,563:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.032', 'enterprice': '21061.6', 'countrevence': '0', 'unrealprofit': '-4283.57959914368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21140.87856824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-21 00:00:02,144:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-21 00:00:02,144:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.032, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41565F1674230402142I0L2'}
2023-01-21 00:00:02,188:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1210000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230120, closeTime:235959, close:21139.7, total:1136862.3708288, corrDate:20221209, corrVal:0.8542687303819795, side:buy 
2023-01-21 00:00:02,505:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41565F1674230402142I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674230402265740, 'quantity': '54.032', 'price': '21139.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674230401779, 'updatetime': 1674230402265, 'tradetype': 'usdt', 'selfid': 41565, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674230402265, 'clientorderid': '41565F1674230402142I0L2', 'price': '21139.8', 'quantity': '54.032', 'commission': '1142.2256736', 'commissionasset': 'USDT', 'tradetime': 1674230402265, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674230402265}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-21 00:00:02,720:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41565F1674230402142I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674230402265740, 'quantity': '54.032', 'price': '21139.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674230401779, 'updatetime': 1674230402265, 'tradetype': 'usdt', 'selfid': 41565, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674230402265, 'clientorderid': '41565F1674230402142I0L2', 'price': '21139.8', 'quantity': '54.032', 'commission': '1142.2256736', 'commissionasset': 'USDT', 'tradetime': 1674230402265, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674230402265}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8121 

self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21139.7', self.close='21145.1'
2023-01-21 00:10:01,577:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21139.7', self.close='21145.1'
2023-01-21 00:10:01,630:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230120   232000    232959  1674228599  21160.8    21165
12237  20230120   233000    233959  1674229199  21165.1  21130.2
12238  20230120   234000    234959  1674229799  21130.1  21116.9
12239  20230120   235000    235959  1674230399  21116.9  21139.7
12240  20230121   000000    000959  1674230999  21139.7  21145.1
2023-01-21 00:10:01,630:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11672
self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=21159.0, self.close=21145.0, self.high=21159.1, self.low=21144.8, self.vol=831.296, self.amt=17583356.5258 
127.0.0.1 - - [21/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 00:10:01,482:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230120   234500    234959  ...         0.0        0.0       0
5758  20230120   235000    235459  ...         0.0        0.0       0
5759  20230120   235500    235959  ...         0.0        0.0       0
5760  20230121   000000    000459  ...         0.0        0.0       0
5761  20230121   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 00:10:01,483:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674230999, self.tradeDate='20230121', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=21159.0, self.close=21145.0, self.high=21159.1, self.low=21144.8, self.vol=831.296, self.amt=17583356.5258, ukdf['pct'].iloc[-1]=-0.000662 , ukdf['amount'].iloc[-1]=17583356.5258, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [21/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11673
self.closeSec=1674231299, self.tradeDate='20230121', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=21145.0, self.close=21165.9, self.high=21168.4, self.low=21141.0, self.vol=1258.18, self.amt=26613522.3507 
2023-01-21 00:15:00,751:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230120   235000    235459  ...         0.0        0.0       0
5759  20230120   235500    235959  ...         0.0        0.0       0
5760  20230121   000000    000459  ...         0.0        0.0       0
5761  20230121   000500    000959  ...         0.0        0.0       0
5762  20230121   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 00:15:00,752:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674231299, self.tradeDate='20230121', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=21145.0, self.close=21165.9, self.high=21168.4, self.low=21141.0, self.vol=1258.18, self.amt=26613522.3507, ukdf['pct'].iloc[-1]=0.000988 , ukdf['amount'].iloc[-1]=26613522.3507, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230120   120000    155959  1674201599  ...    723  0.154954 -1.334303    -1.0
724  20230120   160000    195959  1674215999  ...    724  0.149571 -1.317577    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '10704.09924300378', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20957.23358974', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=338
self.closeSec=1674230399, self.tradeDate='20230120', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=20957.5, self.close=21139.7, self.high=21250.0, self.low=20952.2, self.vol=103649.39, self.amt=2187744948.9115 
127.0.0.1 - - [21/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-21 00:00:01,373:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674230399, self.tradeDate='20230120', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=20957.5, self.close=21139.7, self.high=21250.0, self.low=20952.2, self.vol=103649.39, self.amt=2187744948.9115 
2023-01-21 00:00:01,399:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230120   040000    075959  ...   66652.701  1.403445e+09 -0.001034
722  20230120   080000    115959  ...   49417.658  1.042931e+09  0.000850
723  20230120   120000    155959  ...   54029.169  1.133558e+09 -0.006260
724  20230120   160000    195959  ...   33135.271  6.940604e+08  0.000162
725  20230120   200000    235959  ...  103649.390  2.187745e+09  0.008689

[5 rows x 11 columns]
2023-01-21 00:00:03,475:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230120   040000    075959  1674172799  ...    721  0.148034 -1.417982    -1.0
722  20230120   080000    115959  1674187199  ...    722  0.127783 -1.428838    -1.0
723  20230120   120000    155959  1674201599  ...    723  0.154954 -1.334303    -1.0
724  20230120   160000    195959  1674215999  ...    724  0.149571 -1.317577    -1.0
725  20230120   200000    235959  1674230399  ...    725  0.158853 -1.270892    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '1282.49271905636', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21141.77918988', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


