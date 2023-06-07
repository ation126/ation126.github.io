# 20230608 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7072
self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26269.0, self.close=26351.7, self.high=26387.1, self.low=26250.0, self.vol=3734.966, self.amt=98321881.396 
127.0.0.1 - - [08/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-08 00:20:02,321:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230607   235500    235959  ...         0.0        0.0       0
5760  20230608   000000    000459  ...         0.0        0.0       0
5761  20230608   000500    000959  ...         0.0        0.0       0
5762  20230608   001000    001459  ...         0.0        0.0       0
5763  20230608   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 00:20:02,329:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26269.0, self.close=26351.7, self.high=26387.1, self.low=26250.0, self.vol=3734.966, self.amt=98321881.396, ukdf['pct'].iloc[-1]=0.003144 , ukdf['amount'].iloc[-1]=98321881.396, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7110.06928817262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26354.33922963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7073
self.closeSec=1686155099, self.tradeDate='20230608', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26351.8, self.close=26370.0, self.high=26398.0, self.low=26347.8, self.vol=2176.344, self.amt=57410772.0416 
127.0.0.1 - - [08/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-08 00:25:03,987:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230608   000000    000459  ...         0.0        0.0       0
5761  20230608   000500    000959  ...         0.0        0.0       0
5762  20230608   001000    001459  ...         0.0        0.0       0
5763  20230608   001500    001959  ...         0.0        0.0       0
5764  20230608   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 00:25:03,998:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686155099, self.tradeDate='20230608', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26351.8, self.close=26370.0, self.high=26398.0, self.low=26347.8, self.vol=2176.344, self.amt=57410772.0416, ukdf['pct'].iloc[-1]=0.000694 , ukdf['amount'].iloc[-1]=57410772.0416, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7045.06911582738', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26359.00677037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [08/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -

self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26269.0, self.close=26351.7, self.high=26387.1, self.low=26250.0 
2023-06-08 00:20:01,703:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26269.0, self.close=26351.7, self.high=26387.1, self.low=26250.0   
2023-06-08 00:20:02,087:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230607   235500    235959  1686153599  ...  26261.0  0.000768   1727    5
1440  20230608   000000    000459  1686153899  ...  26264.9  0.001827   1440    0
1441  20230608   000500    000959  1686154199  ...  26338.0 -0.000694   1441    1
1442  20230608   001000    001459  1686154499  ...  26220.0 -0.003588   1442    2
1443  20230608   001500    001959  1686154799  ...  26250.0  0.003144   1443    3

[5 rows x 11 columns]
2023-06-08 00:20:02,089:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=44, self.factor=0.45614709798145997, self.count=7075 

self.closeSec=1686155099, self.tradeDate='20230608', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26351.8, self.close=26370.0, self.high=26398.0, self.low=26347.8 
127.0.0.1 - - [08/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-08 00:25:03,045:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686155099, self.tradeDate='20230608', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26351.8, self.close=26370.0, self.high=26398.0, self.low=26347.8   
2023-06-08 00:25:03,625:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230608   000000    000459  1686153899  ...  26264.9  0.001827   1440    0
1441  20230608   000500    000959  1686154199  ...  26338.0 -0.000694   1441    1
1442  20230608   001000    001459  1686154499  ...  26220.0 -0.003588   1442    2
1443  20230608   001500    001959  1686154799  ...  26250.0  0.003144   1443    3
1444  20230608   002000    002459  1686155099  ...  26347.8  0.000694   1444    4

[5 rows x 11 columns]
2023-06-08 00:25:03,626:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-08 00:00:41,571:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230607    212959  26793.0  ...  47.083333  0.526182  0.360138
5803  20230607    215959  26744.9  ...  47.500000  0.535038  0.372997
5804  20230607    222959  26806.3  ...  47.083333  0.509436  0.395141
5805  20230607    225959  26644.4  ...  46.666667  0.478207  0.428763
5806  20230607    232959  26430.0  ...  46.666667  0.488845  0.451387

[5 rows x 33 columns]
0.5055147058823529
acc is : 0.5055147058823529
2023-06-08 00:00:41,801:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.506611  0.493389       1  ...  1.109369  -1.0    0.0  1.003403
540     0  0.519410  0.480590       0  ...  1.116065  -1.0    0.0  0.997346
541     1  0.455535  0.544465       0  ...  1.125129  -1.0    0.0  0.989246
542     1  0.435730  0.564270       1  ...  1.122064  -1.0    0.0  0.991941
543     1  0.493390  0.506610       0  ...  1.129097  -1.0    0.0  0.985724

[5 rows x 10 columns]
2023-06-08 00:00:41,825:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507198  0.492802       1  ...  1.109369  -1.0    0.0  1.003786
46     0  0.519355  0.480645       0  ...  1.116065  -1.0    0.0  0.996566
47     1  0.455903  0.544097       0  ...  1.125129  -1.0    0.0  0.988473
48     1  0.436020  0.563980       1  ...  1.122064  -1.0    0.0  0.992078
49     1  0.493390  0.506610       0  ...  1.129097  -1.0    0.0  0.985724

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.022', 'enterprice': '26938.4', 'countrevence': '0', 'unrealprofit': '17682.50803221628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26307.37765926', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [08/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-08 00:00:04,746:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42340F1686153603838I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686153604287222, 'quantity': '25.442', 'price': '26330.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686153602976, 'updatetime': 1686153604287, 'tradetype': 'usdt', 'selfid': 42340, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686153604287, 'clientorderid': '42340F1686153603838I0L59', 'price': '26330.1', 'quantity': '25.442', 'commission': '669.8904042', 'commissionasset': 'USDT', 'tradetime': 1686153604287, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686153604287}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3536 

self.closeSec=1686154199, self.tradeDate='20230608', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26333.9', self.close='26363.7'
2023-06-08 00:10:01,127:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686154199, self.tradeDate='20230608', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26333.9', self.close='26363.7'
2023-06-08 00:10:01,158:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230607   232000    232959  1686151799  26533.5  26500.1 -0.001263
573  20230607   233000    233959  1686152399  26500.1  26569.7  0.002626
574  20230607   234000    234959  1686152999  26572.9    26414 -0.005860
575  20230607   235000    235959  1686153599  26412.6  26333.9 -0.003032
576  20230608   000000    000959  1686154199  26333.9  26363.7  0.001132
2023-06-08 00:10:01,161:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3537 

self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26358.4', self.close='26351.7'
127.0.0.1 - - [08/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-08 00:20:01,398:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26358.4', self.close='26351.7'
2023-06-08 00:20:01,493:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230607   233000    233959  1686152399  26500.1  26569.7  0.002626
574  20230607   234000    234959  1686152999  26572.9    26414 -0.005860
575  20230607   235000    235959  1686153599  26412.6  26333.9 -0.003032
576  20230608   000000    000959  1686154199  26333.9  26363.7  0.001132
577  20230608   001000    001959  1686154799  26358.4  26351.7 -0.000455
2023-06-08 00:20:01,493:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-06-08 00:00:02,287:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-08 00:00:02,396:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6080000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230607, closeTime:235959, close:26333.9, total:975635.9291773, pct_pre:0.011955495591219778, thd:-0.5197774396094061, side:sell 
127.0.0.1 - - [08/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3539 

self.closeSec=1686154199, self.tradeDate='20230608', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26333.9', self.close='26363.7'
2023-06-08 00:10:01,143:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686154199, self.tradeDate='20230608', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26333.9', self.close='26363.7'
2023-06-08 00:10:01,173:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230607   232000    232959  1686151799  26533.5  26500.1
17421  20230607   233000    233959  1686152399  26500.1  26569.7
17422  20230607   234000    234959  1686152999  26572.9    26414
17423  20230607   235000    235959  1686153599  26412.6  26333.9
17424  20230608   000000    000959  1686154199  26333.9  26363.7
2023-06-08 00:10:01,173:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3540 

self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26358.4', self.close='26351.7'
2023-06-08 00:20:01,468:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26358.4', self.close='26351.7'
2023-06-08 00:20:01,527:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230607   233000    233959  1686152399  26500.1  26569.7
17422  20230607   234000    234959  1686152999  26572.9    26414
17423  20230607   235000    235959  1686153599  26412.6  26333.9
17424  20230608   000000    000959  1686154199  26333.9  26363.7
17425  20230608   001000    001959  1686154799  26358.4  26351.7
2023-06-08 00:20:01,527:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-06-08 00:00:04,423:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42339F1686153603767I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686153604181759, 'quantity': '45.268', 'price': '26330.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686153602845, 'updatetime': 1686153604181, 'tradetype': 'usdt', 'selfid': 42339, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686153604181, 'clientorderid': '42339F1686153603767I0L2', 'price': '26330.1', 'quantity': '45.268', 'commission': '1191.9109668', 'commissionasset': 'USDT', 'tradetime': 1686153604181, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686153604181}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3539 

self.closeSec=1686154199, self.tradeDate='20230608', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26333.9', self.close='26363.7'
127.0.0.1 - - [08/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-08 00:10:01,131:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686154199, self.tradeDate='20230608', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26333.9', self.close='26363.7'
2023-06-08 00:10:01,164:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230607   232000    232959  1686151799  26533.5  26500.1
12237  20230607   233000    233959  1686152399  26500.1  26569.7
12238  20230607   234000    234959  1686152999  26572.9    26414
12239  20230607   235000    235959  1686153599  26412.6  26333.9
12240  20230608   000000    000959  1686154199  26333.9  26363.7
2023-06-08 00:10:01,164:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [08/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3540 

self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26358.4', self.close='26351.7'
2023-06-08 00:20:01,443:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26358.4', self.close='26351.7'
2023-06-08 00:20:01,496:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230607   233000    233959  1686152399  26500.1  26569.7
12238  20230607   234000    234959  1686152999  26572.9    26414
12239  20230607   235000    235959  1686153599  26412.6  26333.9
12240  20230608   000000    000959  1686154199  26333.9  26363.7
12241  20230608   001000    001959  1686154799  26358.4  26351.7
2023-06-08 00:20:01,496:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7072
self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26269.0, self.close=26351.7, self.high=26387.1, self.low=26250.0, self.vol=3734.966, self.amt=98321881.396 
127.0.0.1 - - [08/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-08 00:20:02,340:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230607   235500    235959  ...         0.0        0.0       0
5760  20230608   000000    000459  ...         0.0        0.0       0
5761  20230608   000500    000959  ...         0.0        0.0       0
5762  20230608   001000    001459  ...         0.0        0.0       0
5763  20230608   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 00:20:02,341:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686154799, self.tradeDate='20230608', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26269.0, self.close=26351.7, self.high=26387.1, self.low=26250.0, self.vol=3734.966, self.amt=98321881.396, ukdf['pct'].iloc[-1]=0.003144 , ukdf['amount'].iloc[-1]=98321881.396, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-18186.49067231217', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26354.33922963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7073
self.closeSec=1686155099, self.tradeDate='20230608', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26351.8, self.close=26370.0, self.high=26398.0, self.low=26347.8, self.vol=2176.344, self.amt=57410772.0416 
127.0.0.1 - - [08/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-08 00:25:03,986:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230608   000000    000459  ...         0.0        0.0       0
5761  20230608   000500    000959  ...         0.0        0.0       0
5762  20230608   001000    001459  ...         0.0        0.0       0
5763  20230608   001500    001959  ...         0.0        0.0       0
5764  20230608   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 00:25:03,993:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686155099, self.tradeDate='20230608', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26351.8, self.close=26370.0, self.high=26398.0, self.low=26347.8, self.vol=2176.344, self.amt=57410772.0416, ukdf['pct'].iloc[-1]=0.000694 , ukdf['amount'].iloc[-1]=57410772.0416, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-18013.13354168783', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26359.00677037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230607   120000    155959  1686124799  ...    723  0.503559 -0.291878     NaN
724  20230607   160000    195959  1686139199  ...    724  0.501072 -0.310688     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '10460.67867037704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26888.97815556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [08/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=147
self.closeSec=1686153599, self.tradeDate='20230607', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26888.4, self.close=26333.9, self.high=26900.0, self.low=26230.0, self.vol=202615.316, self.amt=5380169246.09334 
2023-06-08 00:00:01,792:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686153599, self.tradeDate='20230607', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26888.4, self.close=26333.9, self.high=26900.0, self.low=26230.0, self.vol=202615.316, self.amt=5380169246.09334 
2023-06-08 00:00:01,854:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230607   040000    075959  ...  113750.962  3.081163e+09  0.005478
722  20230607   080000    115959  ...  114373.103  3.092580e+09 -0.011921
723  20230607   120000    155959  ...   47010.017  1.263080e+09 -0.004101
724  20230607   160000    195959  ...  151149.929  4.026422e+09  0.003793
725  20230607   200000    235959  ...  202615.316  5.380169e+09 -0.020619

[5 rows x 11 columns]
2023-06-08 00:00:04,722:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230607   040000    075959  1686095999  ...    721  0.501330 -0.266944     NaN
722  20230607   080000    115959  1686110399  ...    722  0.502091 -0.284508     NaN
723  20230607   120000    155959  1686124799  ...    723  0.503559 -0.291878     NaN
724  20230607   160000    195959  1686139199  ...    724  0.501072 -0.310688     NaN
725  20230607   200000    235959  1686153599  ...    725  0.502840 -0.313424     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '41297.2676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26330', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


