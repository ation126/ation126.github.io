# 20230109 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12218
self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16969.4, self.close=16969.4, self.high=16974.6, self.low=16957.5, self.vol=1743.527, self.amt=29582174.1338 
127.0.0.1 - - [09/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-09 00:10:01,478:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230108   234500    234959  ...         0.0        0.0       0
5758  20230108   235000    235459  ...         0.0        0.0       0
5759  20230108   235500    235959  ...         0.0        0.0       0
5760  20230109   000000    000459  ...         0.0        0.0       0
5761  20230109   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 00:10:01,482:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16969.4, self.close=16969.4, self.high=16974.6, self.low=16957.5, self.vol=1743.527, self.amt=29582174.1338, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=29582174.1338, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-26483.4576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16969.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12219
self.closeSec=1673194499, self.tradeDate='20230109', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16969.4, self.close=16958.5, self.high=16969.4, self.low=16943.7, self.vol=2177.295, self.amt=36911758.2135 
2023-01-09 00:15:00,870:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230108   235000    235459  ...         0.0        0.0       0
5759  20230108   235500    235959  ...         0.0        0.0       0
5760  20230109   000000    000459  ...         0.0        0.0       0
5761  20230109   000500    000959  ...         0.0        0.0       0
5762  20230109   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 00:15:00,871:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673194499, self.tradeDate='20230109', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16969.4, self.close=16958.5, self.high=16969.4, self.low=16943.7, self.vol=2177.295, self.amt=36911758.2135, ukdf['pct'].iloc[-1]=-0.000642 , ukdf['amount'].iloc[-1]=36911758.2135, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-25827.5392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16958.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16969.4, self.close=16969.4, self.high=16974.6, self.low=16957.5 
2023-01-09 00:10:01,442:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16969.4, self.close=16969.4, self.high=16974.6, self.low=16957.5   
127.0.0.1 - - [09/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-09 00:10:01,468:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230108   234500    234959  1673192999  ...  16951.0  0.001557   1725    3
1438  20230108   235000    235459  1673193299  ...  16972.9  0.000919   1726    4
1439  20230108   235500    235959  1673193599  ...  16973.6 -0.000165   1727    5
1440  20230109   000000    000459  1673193899  ...  16966.1 -0.001230   1440    0
1441  20230109   000500    000959  1673194199  ...  16957.5  0.000000   1441    1

[5 rows x 11 columns]
2023-01-09 00:10:01,468:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=47, self.factor=0.38447297957478865, self.count=12785 

self.closeSec=1673194499, self.tradeDate='20230109', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16969.4, self.close=16958.5, self.high=16969.4, self.low=16943.7 
2023-01-09 00:15:00,775:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673194499, self.tradeDate='20230109', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16969.4, self.close=16958.5, self.high=16969.4, self.low=16943.7   
2023-01-09 00:15:00,867:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230108   235000    235459  1673193299  ...  16972.9  0.000919   1726    4
1439  20230108   235500    235959  1673193599  ...  16973.6 -0.000165   1727    5
1440  20230109   000000    000459  1673193899  ...  16966.1 -0.001230   1440    0
1441  20230109   000500    000959  1673194199  ...  16957.5  0.000000   1441    1
1442  20230109   001000    001459  1673194499  ...  16943.7 -0.000642   1442    2

[5 rows x 11 columns]
2023-01-09 00:15:00,868:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-09 00:00:17,821:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230108    212959  16915.4  ...  52.083333  0.525585  0.457214
5803  20230108    215959  16926.2  ...  51.666667  0.522959  0.470249
5804  20230108    222959  16924.1  ...  51.666667  0.534819  0.470293
5805  20230108    225959  16934.1  ...  52.083333  0.548006  0.456394
5806  20230108    232959  16945.7  ...  52.083333  0.546768  0.444513

[5 rows x 33 columns]
0.5625
acc is : 0.5625
2023-01-09 00:00:17,927:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     0  0.501520  0.498480       0  ...  NaN   NaN -0.0016  1.017134
540     1  0.498767  0.501233       1  ...  NaN   NaN -0.0016  1.017735
541     0  0.503710  0.496290       1  ...  NaN   NaN -0.0016  1.018427
542     0  0.505572  0.494428       0  ...  NaN   NaN -0.0016  1.018372
543     0  0.503250  0.496750       1  ...  NaN   NaN -0.0016  1.021113

[5 rows x 10 columns]
2023-01-09 00:00:17,948:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.501296  0.498704       0  ...  NaN   NaN -0.0016  1.019002
46     1  0.498767  0.501233       1  ...  NaN   NaN -0.0016  1.019838
47     0  0.503703  0.496297       1  ...  NaN   NaN -0.0016  1.020530
48     0  0.505363  0.494637       0  ...  NaN   NaN -0.0016  1.018262
49     0  0.503250  0.496750       1  ...  NaN   NaN -0.0016  1.021113

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '12622.70899410528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16998.30937251', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-09 00:00:01,240:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230108   231000    231959  1673191199  16937.2    16936 -0.000077
572  20230108   232000    232959  1673191799    16936  16944.7  0.000514
573  20230108   233000    233959  1673192399  16944.8  16941.1 -0.000212
574  20230108   234000    234959  1673192999  16941.1  16977.5  0.002149
575  20230108   235000    235959  1673193599  16980.5  16990.3  0.000754
2023-01-09 00:00:01,242:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.3', 'enterprice': '16936.9', 'countrevence': '0', 'unrealprofit': '3247.14', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16996.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-09 00:00:01,925:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-09 00:00:01,925:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.3, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41494F1673193601924I0L59'}
2023-01-09 00:00:01,946:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1090000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230108, closeTime:235959, close:16990.3, total:918753.99633, mom:0.0007523043799231299, thd:0.0, side:sell 
127.0.0.1 - - [09/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-09 00:00:02,323:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41494F1673193601924I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673193602030930, 'quantity': '54.3', 'price': '16995.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673193601391, 'updatetime': 1673193602030, 'tradetype': 'usdt', 'selfid': 41494, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673193602030, 'clientorderid': '41494F1673193601924I0L59', 'price': '16995.3', 'quantity': '54.3', 'commission': '922.84479', 'commissionasset': 'USDT', 'tradetime': 1673193602030, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673193602030}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-09 00:00:02,531:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41494F1673193601924I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673193602030930, 'quantity': '54.3', 'price': '16995.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673193601391, 'updatetime': 1673193602030, 'tradetype': 'usdt', 'selfid': 41494, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673193602030, 'clientorderid': '41494F1673193601924I0L59', 'price': '16995.3', 'quantity': '54.3', 'commission': '922.84479', 'commissionasset': 'USDT', 'tradetime': 1673193602030, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673193602030}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6392 

self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16990.9', self.close='16969.4'
2023-01-09 00:10:01,518:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16990.9', self.close='16969.4'
127.0.0.1 - - [09/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-09 00:10:01,525:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230108   232000    232959  1673191799    16936  16944.7  0.000514
573  20230108   233000    233959  1673192399  16944.8  16941.1 -0.000212
574  20230108   234000    234959  1673192999  16941.1  16977.5  0.002149
575  20230108   235000    235959  1673193599  16980.5  16990.3  0.000754
576  20230109   000000    000959  1673194199  16990.9  16969.4 -0.001230
2023-01-09 00:10:01,525:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-09 00:00:01,277:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230108   231000    231959  1673191199  16937.2    16936
17420  20230108   232000    232959  1673191799    16936  16944.7
17421  20230108   233000    233959  1673192399  16944.8  16941.1
17422  20230108   234000    234959  1673192999  16941.1  16977.5
17423  20230108   235000    235959  1673193599  16980.5  16990.3
2023-01-09 00:00:01,277:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.438', 'enterprice': '16927.4', 'countrevence': '0', 'unrealprofit': '3841.8534', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16996.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-09 00:00:01,939:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-09 00:00:01,939:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.438, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41495F1673193601938I0L57'}
2023-01-09 00:00:01,962:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1090000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230108, closeTime:235959, close:16990.3, total:937482.7799988001, pct_pre:0.00014771223293630342, thd:0.3319973513387705, side:sell 
2023-01-09 00:00:02,542:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41495F1673193601938I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673193602055557, 'quantity': '55.438', 'price': '16995.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673193601454, 'updatetime': 1673193602055, 'tradetype': 'usdt', 'selfid': 41495, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673193602055, 'clientorderid': '41495F1673193601938I0L57', 'price': '16995.3', 'quantity': '55.438', 'commission': '942.1854414', 'commissionasset': 'USDT', 'tradetime': 1673193602055, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673193602055}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-09 00:00:02,787:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41495F1673193601938I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673193602055557, 'quantity': '55.438', 'price': '16995.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673193601454, 'updatetime': 1673193602055, 'tradetype': 'usdt', 'selfid': 41495, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673193602055, 'clientorderid': '41495F1673193601938I0L57', 'price': '16995.3', 'quantity': '55.438', 'commission': '942.1854414', 'commissionasset': 'USDT', 'tradetime': 1673193602055, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673193602055}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6393 

self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16990.9', self.close='16969.4'
2023-01-09 00:10:01,527:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16990.9', self.close='16969.4'
127.0.0.1 - - [09/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-09 00:10:01,567:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230108   232000    232959  1673191799    16936  16944.7
17421  20230108   233000    233959  1673192399  16944.8  16941.1
17422  20230108   234000    234959  1673192999  16941.1  16977.5
17423  20230108   235000    235959  1673193599  16980.5  16990.3
17424  20230109   000000    000959  1673194199  16990.9  16969.4
2023-01-09 00:10:01,567:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-09 00:00:01,294:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230108   231000    231959  1673191199  16937.2    16936
12236  20230108   232000    232959  1673191799    16936  16944.7
12237  20230108   233000    233959  1673192399  16944.8  16941.1
12238  20230108   234000    234959  1673192999  16941.1  16977.5
12239  20230108   235000    235959  1673193599  16980.5  16990.3
2023-01-09 00:00:01,294:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '72.677', 'enterprice': '16930.1', 'countrevence': '0', 'unrealprofit': '-4840.2882', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16996.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-09 00:00:01,913:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-09 00:00:01,913:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 72.677, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41493F1673193601911I0L2'}
2023-01-09 00:00:01,936:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1090000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230108, closeTime:235959, close:16990.3, total:1229198.4488223002, corrDate:20221209, corrVal:0.7997198828796507, side:buy 
2023-01-09 00:00:02,043:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41493F1673193601911I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673193602016819, 'quantity': '72.677', 'price': '16996.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673193601462, 'updatetime': 1673193602016, 'tradetype': 'usdt', 'selfid': 41493, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673193602016, 'clientorderid': '41493F1673193601911I0L2', 'price': '16996.7', 'quantity': '72.677', 'commission': '1235.2691659', 'commissionasset': 'USDT', 'tradetime': 1673193602016, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673193602016}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-09 00:00:02,295:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41493F1673193601911I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673193602016819, 'quantity': '72.677', 'price': '16996.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673193601462, 'updatetime': 1673193602016, 'tradetype': 'usdt', 'selfid': 41493, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673193602016, 'clientorderid': '41493F1673193601911I0L2', 'price': '16996.7', 'quantity': '72.677', 'commission': '1235.2691659', 'commissionasset': 'USDT', 'tradetime': 1673193602016, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673193602016}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6393 

self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16990.9', self.close='16969.4'
2023-01-09 00:10:01,538:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16990.9', self.close='16969.4'
2023-01-09 00:10:01,563:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230108   232000    232959  1673191799    16936  16944.7
12237  20230108   233000    233959  1673192399  16944.8  16941.1
12238  20230108   234000    234959  1673192999  16941.1  16977.5
12239  20230108   235000    235959  1673193599  16980.5  16990.3
12240  20230109   000000    000959  1673194199  16990.9  16969.4
2023-01-09 00:10:01,563:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [09/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8216
self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16969.4, self.close=16969.4, self.high=16974.6, self.low=16957.5, self.vol=1743.527, self.amt=29582174.1338 
2023-01-09 00:10:01,476:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230108   234500    234959  ...         0.0        0.0       0
5758  20230108   235000    235459  ...         0.0        0.0       0
5759  20230108   235500    235959  ...         0.0        0.0       0
5760  20230109   000000    000459  ...         0.0        0.0       0
5761  20230109   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 00:10:01,476:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673194199, self.tradeDate='20230109', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16969.4, self.close=16969.4, self.high=16974.6, self.low=16957.5, self.vol=1743.527, self.amt=29582174.1338, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=29582174.1338, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8217
self.closeSec=1673194499, self.tradeDate='20230109', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16969.4, self.close=16958.5, self.high=16969.4, self.low=16943.7, self.vol=2177.295, self.amt=36911758.2135 
127.0.0.1 - - [09/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-09 00:15:00,901:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230108   235000    235459  ...         0.0        0.0       0
5759  20230108   235500    235959  ...         0.0        0.0       0
5760  20230109   000000    000459  ...         0.0        0.0       0
5761  20230109   000500    000959  ...         0.0        0.0       0
5762  20230109   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 00:15:00,903:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673194499, self.tradeDate='20230109', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16969.4, self.close=16958.5, self.high=16969.4, self.low=16943.7, self.vol=2177.295, self.amt=36911758.2135, ukdf['pct'].iloc[-1]=-0.000642 , ukdf['amount'].iloc[-1]=36911758.2135, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230108   120000    155959  1673164799  ...    723  0.186551 -0.494174     NaN
724  20230108   160000    195959  1673179199  ...    724  0.192833 -0.482656     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.715', 'enterprice': '16938.9', 'countrevence': '0', 'unrealprofit': '1075.386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16918.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [09/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=892041.1793865, self.flagDict['side']='sell', self.tradeCount=11, self.count=266
self.closeSec=1673193599, self.tradeDate='20230108', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16918.5, self.close=16990.3, self.high=17015.6, self.low=16912.7, self.vol=27048.995, self.amt=458583609.297 
2023-01-09 00:00:01,140:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673193599, self.tradeDate='20230108', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16918.5, self.close=16990.3, self.high=17015.6, self.low=16912.7, self.vol=27048.995, self.amt=458583609.297 
2023-01-09 00:00:01,189:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230108   040000    075959  ...   9824.894  1.663814e+08 -0.000047
722  20230108   080000    115959  ...  15067.264  2.550033e+08  0.000148
723  20230108   120000    155959  ...   7997.895  1.354707e+08  0.000384
724  20230108   160000    195959  ...  15529.917  2.630195e+08 -0.001593
725  20230108   200000    235959  ...  27048.995  4.585836e+08  0.004244

[5 rows x 11 columns]
2023-01-09 00:00:02,770:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230108   040000    075959  1673135999  ...    721  0.226620 -0.341427     NaN
722  20230108   080000    115959  1673150399  ...    722  0.135794 -0.657472    -1.0
723  20230108   120000    155959  1673164799  ...    723  0.186551 -0.494174     NaN
724  20230108   160000    195959  1673179199  ...    724  0.192833 -0.482656     NaN
725  20230108   200000    235959  1673193599  ...    725  0.221401 -0.395178     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.715', 'enterprice': '16938.9', 'countrevence': '0', 'unrealprofit': '-3046.927', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16996.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


