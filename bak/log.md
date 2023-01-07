# 20230108 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11930
self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16931.4, self.close=16924.8, self.high=16931.5, self.low=16924.1, self.vol=435.227, self.amt=7367075.5608 
127.0.0.1 - - [08/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-08 00:10:01,495:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230107   234500    234959  ...         0.0        0.0       0
5758  20230107   235000    235459  ...         0.0        0.0       0
5759  20230107   235500    235959  ...         0.0        0.0       0
5760  20230108   000000    000459  ...         0.0        0.0       0
5761  20230108   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 00:10:01,496:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16931.4, self.close=16924.8, self.high=16931.5, self.low=16924.1, self.vol=435.227, self.amt=7367075.5608, ukdf['pct'].iloc[-1]=-0.00039 , ukdf['amount'].iloc[-1]=7367075.5608, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-23834.71861451216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16925.38346541', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11931
self.closeSec=1673108099, self.tradeDate='20230108', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16924.8, self.close=16921.8, self.high=16926.6, self.low=16921.8, self.vol=285.621, self.amt=4834111.1273 
127.0.0.1 - - [08/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-08 00:15:00,618:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230107   235000    235459  ...         0.0        0.0       0
5759  20230107   235500    235959  ...         0.0        0.0       0
5760  20230108   000000    000459  ...         0.0        0.0       0
5761  20230108   000500    000959  ...         0.0        0.0       0
5762  20230108   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 00:15:00,618:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673108099, self.tradeDate='20230108', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16924.8, self.close=16921.8, self.high=16926.6, self.low=16921.8, self.vol=285.621, self.amt=4834111.1273, ukdf['pct'].iloc[-1]=-0.000177 , ukdf['amount'].iloc[-1]=4834111.1273, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-23648.0009436472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16922.28060595', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16931.4, self.close=16924.8, self.high=16931.5, self.low=16924.1 
2023-01-08 00:10:01,431:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16931.4, self.close=16924.8, self.high=16931.5, self.low=16924.1   
127.0.0.1 - - [08/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-08 00:10:01,462:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230107   234500    234959  1673106599  ...  16930.4 -0.000024   1725    3
1438  20230107   235000    235459  1673106899  ...  16930.3  0.000089   1726    4
1439  20230107   235500    235959  1673107199  ...  16931.8  0.000148   1727    5
1440  20230108   000000    000459  1673107499  ...  16931.4 -0.000177   1440    0
1441  20230108   000500    000959  1673107799  ...  16924.1 -0.000390   1441    1

[5 rows x 11 columns]
2023-01-08 00:10:01,462:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=48, self.factor=0.32570765895549725, self.count=12497 

self.closeSec=1673108099, self.tradeDate='20230108', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16924.8, self.close=16921.8, self.high=16926.6, self.low=16921.8 
2023-01-08 00:15:00,543:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673108099, self.tradeDate='20230108', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16924.8, self.close=16921.8, self.high=16926.6, self.low=16921.8   
2023-01-08 00:15:00,562:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230107   235000    235459  1673106899  ...  16930.3  0.000089   1726    4
1439  20230107   235500    235959  1673107199  ...  16931.8  0.000148   1727    5
1440  20230108   000000    000459  1673107499  ...  16931.4 -0.000177   1440    0
1441  20230108   000500    000959  1673107799  ...  16924.1 -0.000390   1441    1
1442  20230108   001000    001459  1673108099  ...  16921.8 -0.000177   1442    2

[5 rows x 11 columns]
2023-01-08 00:15:00,562:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-08 00:00:18,366:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230107    212959  16912.5  ...  50.000000  0.549547  0.356826
5803  20230107    215959  16925.0  ...  50.000000  0.537856  0.369640
5804  20230107    222959  16911.9  ...  50.416667  0.544349  0.382205
5805  20230107    225959  16920.6  ...  50.416667  0.552701  0.390803
5806  20230107    232959  16931.8  ...  50.416667  0.555005  0.400265

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-01-08 00:00:18,465:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     0  0.503135  0.496865       0  ...  NaN   NaN -0.0016  1.003102
540     1  0.495870  0.504130       1  ...  NaN   NaN -0.0016  1.003612
541     0  0.502007  0.497993       1  ...  NaN   NaN -0.0016  1.004276
542     0  0.504429  0.495571       1  ...  NaN   NaN -0.0016  1.004460
543     0  0.503108  0.496892       0  ...  NaN   NaN -0.0016  1.004437

[5 rows x 10 columns]
2023-01-08 00:00:18,488:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.503383  0.496617       0  ...  NaN   NaN -0.0016  1.003007
46     1  0.495469  0.504531       1  ...  NaN   NaN -0.0016  1.002257
47     0  0.502062  0.497938       1  ...  NaN   NaN -0.0016  1.002920
48     0  0.504214  0.495786       1  ...  NaN   NaN -0.0016  1.003651
49     0  0.503108  0.496892       0  ...  NaN   NaN -0.0016  1.004437

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '9900.5184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16934.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-08 00:00:00,925:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230107   231000    231959  1673104799  16938.5  16938.2 -0.000024
572  20230107   232000    232959  1673105399  16938.1  16934.8 -0.000201
573  20230107   233000    233959  1673105999  16934.8  16931.8 -0.000177
574  20230107   234000    234959  1673106599  16931.8  16930.4 -0.000083
575  20230107   235000    235959  1673107199  16930.5  16934.4  0.000236
2023-01-08 00:00:00,925:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.362', 'enterprice': '16934.9', 'countrevence': '0', 'unrealprofit': '-21.7448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16934.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-08 00:00:01,559:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-08 00:00:01,559:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.362, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41485F1673107201557I0L59'}
2023-01-08 00:00:01,588:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1080000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230107, closeTime:235959, close:16934.4, total:919694.4187662001, mom:0.0009358833783754683, thd:0.0, side:sell 
2023-01-08 00:00:01,740:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41485F1673107201557I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673107201678718, 'quantity': '54.362', 'price': '16934.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673107201222, 'updatetime': 1673107201678, 'tradetype': 'usdt', 'selfid': 41485, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673107201678, 'clientorderid': '41485F1673107201557I0L59', 'price': '16934.4', 'quantity': '54.362', 'commission': '920.5878528', 'commissionasset': 'USDT', 'tradetime': 1673107201678, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673107201678}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-08 00:00:02,127:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41485F1673107201557I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673107201678718, 'quantity': '54.362', 'price': '16934.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673107201222, 'updatetime': 1673107201678, 'tradetype': 'usdt', 'selfid': 41485, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673107201678, 'clientorderid': '41485F1673107201557I0L59', 'price': '16934.4', 'quantity': '54.362', 'commission': '920.5878528', 'commissionasset': 'USDT', 'tradetime': 1673107201678, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673107201678}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6248 

self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16934.5', self.close='16924.8'
2023-01-08 00:10:01,531:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16934.5', self.close='16924.8'
2023-01-08 00:10:01,567:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230107   232000    232959  1673105399  16938.1  16934.8 -0.000201
573  20230107   233000    233959  1673105999  16934.8  16931.8 -0.000177
574  20230107   234000    234959  1673106599  16931.8  16930.4 -0.000083
575  20230107   235000    235959  1673107199  16930.5  16934.4  0.000236
576  20230108   000000    000959  1673107799  16934.5  16924.8 -0.000567
2023-01-08 00:10:01,568:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-07 23:50:00,584:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6248 

self.closeSec=1673107199, self.tradeDate='20230107', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16930.5', self.close='16934.4'
127.0.0.1 - - [08/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
2023-01-08 00:00:00,927:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673107199, self.tradeDate='20230107', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16930.5', self.close='16934.4'
2023-01-08 00:00:00,985:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230107   231000    231959  1673104799  16938.5  16938.2
17420  20230107   232000    232959  1673105399  16938.1  16934.8
17421  20230107   233000    233959  1673105999  16934.8  16931.8
17422  20230107   234000    234959  1673106599  16931.8  16930.4
17423  20230107   235000    235959  1673107199  16930.5  16934.4
2023-01-08 00:00:00,985:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-08 00:00:01,140:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1080000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230107, closeTime:235959, close:16934.4, total:939357.0753385, pct_pre:0.006057471674334902, thd:-0.2232101726654332, side:sell 
127.0.0.1 - - [08/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6249 

self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16934.5', self.close='16924.8'
2023-01-08 00:10:01,547:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16934.5', self.close='16924.8'
2023-01-08 00:10:01,574:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230107   232000    232959  1673105399  16938.1  16934.8
17421  20230107   233000    233959  1673105999  16934.8  16931.8
17422  20230107   234000    234959  1673106599  16931.8  16930.4
17423  20230107   235000    235959  1673107199  16930.5  16934.4
17424  20230108   000000    000959  1673107799  16934.5  16924.8
2023-01-08 00:10:01,574:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-08 00:00:00,944:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230107   231000    231959  1673104799  16938.5  16938.2
12236  20230107   232000    232959  1673105399  16938.1  16934.8
12237  20230107   233000    233959  1673105999  16934.8  16931.8
12238  20230107   234000    234959  1673106599  16931.8  16930.4
12239  20230107   235000    235959  1673107199  16930.5  16934.4
2023-01-08 00:00:00,944:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '72.735', 'enterprice': '16949.3', 'countrevence': '0', 'unrealprofit': '-1076.478', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16934.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-08 00:00:01,584:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-08 00:00:01,584:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 72.735, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41486F1673107201583I0L2'}
2023-01-08 00:00:01,610:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1080000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230107, closeTime:235959, close:16934.4, total:1231574.5281645001, corrDate:20221105, corrVal:0.8758665316181097, side:sell 
127.0.0.1 - - [08/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-08 00:00:02,107:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41486F1673107201583I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673107201691278, 'quantity': '72.735', 'price': '16934.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673107201209, 'updatetime': 1673107201691, 'tradetype': 'usdt', 'selfid': 41486, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673107201691, 'clientorderid': '41486F1673107201583I0L2', 'price': '16934.4', 'quantity': '72.735', 'commission': '1231.723584', 'commissionasset': 'USDT', 'tradetime': 1673107201691, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673107201691}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-08 00:00:02,367:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41486F1673107201583I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673107201691278, 'quantity': '72.735', 'price': '16934.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673107201209, 'updatetime': 1673107201691, 'tradetype': 'usdt', 'selfid': 41486, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673107201691, 'clientorderid': '41486F1673107201583I0L2', 'price': '16934.4', 'quantity': '72.735', 'commission': '1231.723584', 'commissionasset': 'USDT', 'tradetime': 1673107201691, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673107201691}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6249 

self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16934.5', self.close='16924.8'
2023-01-08 00:10:01,542:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16934.5', self.close='16924.8'
2023-01-08 00:10:01,569:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230107   232000    232959  1673105399  16938.1  16934.8
12237  20230107   233000    233959  1673105999  16934.8  16931.8
12238  20230107   234000    234959  1673106599  16931.8  16930.4
12239  20230107   235000    235959  1673107199  16930.5  16934.4
12240  20230108   000000    000959  1673107799  16934.5  16924.8
2023-01-08 00:10:01,569:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7928
self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16931.4, self.close=16924.8, self.high=16931.5, self.low=16924.1, self.vol=435.227, self.amt=7367075.5608 
127.0.0.1 - - [08/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-08 00:10:01,490:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230107   234500    234959  ...         0.0        0.0       0
5758  20230107   235000    235459  ...         0.0        0.0       0
5759  20230107   235500    235959  ...         0.0        0.0       0
5760  20230108   000000    000459  ...         0.0        0.0       0
5761  20230108   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 00:10:01,497:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673107799, self.tradeDate='20230108', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16931.4, self.close=16924.8, self.high=16931.5, self.low=16924.1, self.vol=435.227, self.amt=7367075.5608, ukdf['pct'].iloc[-1]=-0.00039 , ukdf['amount'].iloc[-1]=7367075.5608, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7929
self.closeSec=1673108099, self.tradeDate='20230108', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16924.8, self.close=16921.8, self.high=16926.6, self.low=16921.8, self.vol=285.621, self.amt=4834111.1273 
2023-01-08 00:15:00,640:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230107   235000    235459  ...         0.0        0.0       0
5759  20230107   235500    235959  ...         0.0        0.0       0
5760  20230108   000000    000459  ...         0.0        0.0       0
5761  20230108   000500    000959  ...         0.0        0.0       0
5762  20230108   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 00:15:00,641:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673108099, self.tradeDate='20230108', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16924.8, self.close=16921.8, self.high=16926.6, self.low=16921.8, self.vol=285.621, self.amt=4834111.1273, ukdf['pct'].iloc[-1]=-0.000177 , ukdf['amount'].iloc[-1]=4834111.1273, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230107   120000    155959  1673078399  ...    723  0.415503  0.335738     NaN
724  20230107   160000    195959  1673092799  ...    724  0.388516  0.234297     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '10043.700902223', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16913.4297499', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [08/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=260
self.closeSec=1673107199, self.tradeDate='20230107', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16912.3, self.close=16934.4, self.high=16944.0, self.low=16900.1, self.vol=16729.28, self.amt=283069730.0378 
2023-01-08 00:00:00,796:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673107199, self.tradeDate='20230107', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16912.3, self.close=16934.4, self.high=16944.0, self.low=16900.1, self.vol=16729.28, self.amt=283069730.0378 
2023-01-08 00:00:00,822:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230107   040000    075959  ...  68235.521  1.156656e+09  0.000661
722  20230107   080000    115959  ...  18044.046  3.057485e+08  0.000030
723  20230107   120000    155959  ...  10555.757  1.787108e+08 -0.000260
724  20230107   160000    195959  ...  13458.246  2.277289e+08 -0.001623
725  20230107   200000    235959  ...  16729.280  2.830697e+08  0.001301

[5 rows x 11 columns]
2023-01-08 00:00:02,540:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230107   040000    075959  1673049599  ...    721  0.505149  0.661141     1.0
722  20230107   080000    115959  1673063999  ...    722  0.510513  0.662980     1.0
723  20230107   120000    155959  1673078399  ...    723  0.415503  0.335738     NaN
724  20230107   160000    195959  1673092799  ...    724  0.388516  0.234297     NaN
725  20230107   200000    235959  1673107199  ...    725  0.354376  0.109310     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '11155.578', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16934.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


