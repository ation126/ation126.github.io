# 20230227 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26332
self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23244.3, self.close=23234.8, self.high=23246.4, self.low=23220.6, self.vol=648.485, self.amt=15067292.2132 
127.0.0.1 - - [27/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-27 00:20:02,477:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230226   235500    235959  ...         0.0        0.0       0
5760  20230227   000000    000459  ...         0.0        0.0       0
5761  20230227   000500    000959  ...         0.0        0.0       0
5762  20230227   001000    001459  ...         0.0        0.0       0
5763  20230227   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 00:20:02,478:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23244.3, self.close=23234.8, self.high=23246.4, self.low=23220.6, self.vol=648.485, self.amt=15067292.2132, ukdf['pct'].iloc[-1]=-0.000404 , ukdf['amount'].iloc[-1]=15067292.2132, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-403510.168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23234.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26333
self.closeSec=1677428699, self.tradeDate='20230227', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23234.8, self.close=23236.0, self.high=23238.7, self.low=23230.1, self.vol=452.284, self.amt=10508363.8561 
2023-02-27 00:25:01,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230227   000000    000459  ...         0.0        0.0       0
5761  20230227   000500    000959  ...         0.0        0.0       0
5762  20230227   001000    001459  ...         0.0        0.0       0
5763  20230227   001500    001959  ...         0.0        0.0       0
5764  20230227   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 00:25:01,578:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677428699, self.tradeDate='20230227', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23234.8, self.close=23236.0, self.high=23238.7, self.low=23230.1, self.vol=452.284, self.amt=10508363.8561, ukdf['pct'].iloc[-1]=5.2e-05 , ukdf['amount'].iloc[-1]=10508363.8561, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-403588.3968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23236.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.4301490353935396, self.count=26898 

self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23244.3, self.close=23234.8, self.high=23246.4, self.low=23220.6 
2023-02-27 00:20:01,703:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23244.3, self.close=23234.8, self.high=23246.4, self.low=23220.6   
2023-02-27 00:20:01,778:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230226   235500    235959  1677427199  ...  23210.0  0.001047   1727    5
1440  20230227   000000    000459  1677427499  ...  23228.2 -0.000495   1440    0
1441  20230227   000500    000959  1677427799  ...  23209.0 -0.000090   1441    1
1442  20230227   001000    001459  1677428099  ...  23226.1  0.000779   1442    2
1443  20230227   001500    001959  1677428399  ...  23220.6 -0.000404   1443    3

[5 rows x 11 columns]
2023-02-27 00:20:01,778:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [27/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.4301490353935396, self.count=26899 

self.closeSec=1677428699, self.tradeDate='20230227', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23234.8, self.close=23236.0, self.high=23238.7, self.low=23230.1 
2023-02-27 00:25:01,530:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677428699, self.tradeDate='20230227', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23234.8, self.close=23236.0, self.high=23238.7, self.low=23230.1   
2023-02-27 00:25:01,569:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230227   000000    000459  1677427499  ...  23228.2 -0.000495   1440    0
1441  20230227   000500    000959  1677427799  ...  23209.0 -0.000090   1441    1
1442  20230227   001000    001459  1677428099  ...  23226.1  0.000779   1442    2
1443  20230227   001500    001959  1677428399  ...  23220.6 -0.000404   1443    3
1444  20230227   002000    002459  1677428699  ...  23230.1  0.000052   1444    4

[5 rows x 11 columns]
2023-02-27 00:25:01,569:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-27 00:00:35,440:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230226    212959  23152.0  ...  47.083333  0.479491  0.198546
5803  20230226    215959  23171.9  ...  47.500000  0.488323  0.194733
5804  20230226    222959  23203.6  ...  47.500000  0.491268  0.194180
5805  20230226    225959  23214.6  ...  47.083333  0.483018  0.197005
5806  20230226    232959  23182.9  ...  47.500000  0.484077  0.199241

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-02-27 00:00:35,591:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.513284  0.486716       1  ...  0.961113   1.0    0.0  1.050055
540     0  0.519554  0.480446       1  ...  0.961564   1.0    0.0  1.050549
541     0  0.513248  0.486752       0  ...  0.960251   1.0    0.0  1.049114
542     0  0.503919  0.496081       1  ...  0.960408   1.0    0.0  1.049286
543     0  0.517187  0.482813       1  ...  0.962608   1.0    0.0  1.051689

[5 rows x 10 columns]
2023-02-27 00:00:35,622:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512945  0.487055       1  ...  0.961113   1.0    0.0  1.048622
46     0  0.519536  0.480464       1  ...  0.961564   1.0    0.0  1.050093
47     0  0.513243  0.486757       0  ...  0.960251   1.0    0.0  1.048659
48     0  0.503658  0.496342       1  ...  0.960408   1.0    0.0  1.046988
49     0  0.517187  0.482813       1  ...  0.962608   1.0    0.0  1.051689

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.793', 'enterprice': '23035.2', 'countrevence': '0', 'unrealprofit': '6732.4029', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23240.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-27 00:00:03,136:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41841F1677427202770I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677427202871164, 'quantity': '43.753', 'price': '23239.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677427202408, 'updatetime': 1677427202871, 'tradetype': 'usdt', 'selfid': 41841, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677427202871, 'clientorderid': '41841F1677427202770I0L59', 'price': '23239.7', 'quantity': '43.753', 'commission': '1016.8065941', 'commissionasset': 'USDT', 'tradetime': 1677427202871, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677427202871}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13448 

self.closeSec=1677427799, self.tradeDate='20230227', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23239.8', self.close='23226.1'
2023-02-27 00:10:01,631:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677427799, self.tradeDate='20230227', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23239.8', self.close='23226.1'
2023-02-27 00:10:01,665:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230226   232000    232959  1677425399  23192.2  23186.6 -0.000237
573  20230226   233000    233959  1677425999  23186.7    23206  0.000837
574  20230226   234000    234959  1677426599    23206    23199 -0.000302
575  20230226   235000    235959  1677427199  23198.9  23239.7  0.001754
576  20230227   000000    000959  1677427799  23239.8  23226.1 -0.000585
2023-02-27 00:10:01,677:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13449 

self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23226.1', self.close='23234.8'
2023-02-27 00:20:01,915:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23226.1', self.close='23234.8'
2023-02-27 00:20:01,979:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230226   233000    233959  1677425999  23186.7    23206  0.000837
574  20230226   234000    234959  1677426599    23206    23199 -0.000302
575  20230226   235000    235959  1677427199  23198.9  23239.7  0.001754
576  20230227   000000    000959  1677427799  23239.8  23226.1 -0.000585
577  20230227   001000    001959  1677428399  23226.1  23234.8  0.000375
2023-02-27 00:20:01,980:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-02-27 00:00:02,245:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-27 00:00:02,513:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2270000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230226, closeTime:235959, close:23239.7, total:979069.1011917, pct_pre:0.011045402601014276, thd:-0.00732217103492977, side:sell 
127.0.0.1 - - [27/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13449 

self.closeSec=1677427799, self.tradeDate='20230227', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23239.8', self.close='23226.1'
2023-02-27 00:10:01,642:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677427799, self.tradeDate='20230227', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23239.8', self.close='23226.1'
2023-02-27 00:10:01,683:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230226   232000    232959  1677425399  23192.2  23186.6
17421  20230226   233000    233959  1677425999  23186.7    23206
17422  20230226   234000    234959  1677426599    23206    23199
17423  20230226   235000    235959  1677427199  23198.9  23239.7
17424  20230227   000000    000959  1677427799  23239.8  23226.1
2023-02-27 00:10:01,683:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13450 

self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23226.1', self.close='23234.8'
2023-02-27 00:20:02,165:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23226.1', self.close='23234.8'
2023-02-27 00:20:02,373:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230226   233000    233959  1677425999  23186.7    23206
17422  20230226   234000    234959  1677426599    23206    23199
17423  20230226   235000    235959  1677427199  23198.9  23239.7
17424  20230227   000000    000959  1677427799  23239.8  23226.1
17425  20230227   001000    001959  1677428399  23226.1  23234.8
2023-02-27 00:20:02,374:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [27/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-27 00:00:03,653:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41842F1677427202938I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677427203220332, 'quantity': '50.837', 'price': '23239.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677427202626, 'updatetime': 1677427203220, 'tradetype': 'usdt', 'selfid': 41842, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677427203220, 'clientorderid': '41842F1677427202938I0L2', 'price': '23239.8', 'quantity': '50.837', 'commission': '1181.4417126', 'commissionasset': 'USDT', 'tradetime': 1677427203220, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677427203220}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13449 

self.closeSec=1677427799, self.tradeDate='20230227', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23239.8', self.close='23226.1'
2023-02-27 00:10:01,636:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677427799, self.tradeDate='20230227', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23239.8', self.close='23226.1'
2023-02-27 00:10:01,674:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230226   232000    232959  1677425399  23192.2  23186.6
12237  20230226   233000    233959  1677425999  23186.7    23206
12238  20230226   234000    234959  1677426599    23206    23199
12239  20230226   235000    235959  1677427199  23198.9  23239.7
12240  20230227   000000    000959  1677427799  23239.8  23226.1
2023-02-27 00:10:01,674:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--: 127.0.0.1 - - [27/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13450 

self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23226.1', self.close='23234.8'
2023-02-27 00:20:02,115:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23226.1', self.close='23234.8'
2023-02-27 00:20:02,298:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230226   233000    233959  1677425999  23186.7    23206
12238  20230226   234000    234959  1677426599    23206    23199
12239  20230226   235000    235959  1677427199  23198.9  23239.7
12240  20230227   000000    000959  1677427799  23239.8  23226.1
12241  20230227   001000    001959  1677428399  23226.1  23234.8
2023-02-27 00:20:02,298:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [27/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22330
self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23244.3, self.close=23234.8, self.high=23246.4, self.low=23220.6, self.vol=648.485, self.amt=15067292.2132 
2023-02-27 00:20:01,898:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230226   235500    235959  ...         0.0        0.0       0
5760  20230227   000000    000459  ...         0.0        0.0       0
5761  20230227   000500    000959  ...         0.0        0.0       0
5762  20230227   001000    001459  ...         0.0        0.0       0
5763  20230227   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 00:20:01,904:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677428399, self.tradeDate='20230227', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23244.3, self.close=23234.8, self.high=23246.4, self.low=23220.6, self.vol=648.485, self.amt=15067292.2132, ukdf['pct'].iloc[-1]=-0.000404 , ukdf['amount'].iloc[-1]=15067292.2132, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [27/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22331
self.closeSec=1677428699, self.tradeDate='20230227', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23234.8, self.close=23236.0, self.high=23238.7, self.low=23230.1, self.vol=452.284, self.amt=10508363.8561 
2023-02-27 00:25:01,587:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230227   000000    000459  ...         0.0        0.0       0
5761  20230227   000500    000959  ...         0.0        0.0       0
5762  20230227   001000    001459  ...         0.0        0.0       0
5763  20230227   001500    001959  ...         0.0        0.0       0
5764  20230227   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 00:25:01,587:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677428699, self.tradeDate='20230227', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23234.8, self.close=23236.0, self.high=23238.7, self.low=23230.1, self.vol=452.284, self.amt=10508363.8561, ukdf['pct'].iloc[-1]=5.2e-05 , ukdf['amount'].iloc[-1]=10508363.8561, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230226   120000    155959  1677398399  ...    723  0.973914  0.797723     1.0
724  20230226   160000    195959  1677412799  ...    724  1.008950  0.878677     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '5668.29366930074', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23243.18663006', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  127.0.0.1 - - [27/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=560
self.closeSec=1677427199, self.tradeDate='20230226', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23244.2, self.close=23239.7, self.high=23332.4, self.low=23115.4, self.vol=63502.842, self.amt=1473862605.935 
2023-02-27 00:00:02,077:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677427199, self.tradeDate='20230226', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23244.2, self.close=23239.7, self.high=23332.4, self.low=23115.4, self.vol=63502.842, self.amt=1473862605.935 
2023-02-27 00:00:02,145:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230226   040000    075959  ...  83386.846  1.914106e+09  0.007421
722  20230226   080000    115959  ...  38352.322  8.878205e+08  0.002402
723  20230226   120000    155959  ...  31491.179  7.292206e+08 -0.002547
724  20230226   160000    195959  ...  42192.201  9.793469e+08  0.004386
725  20230226   200000    235959  ...  63502.842  1.473863e+09 -0.000194

[5 rows x 11 columns]
2023-02-27 00:00:04,999:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230226   040000    075959  1677369599  ...    721  0.976690  0.818508     1.0
722  20230226   080000    115959  1677383999  ...    722  0.978998  0.816343     1.0
723  20230226   120000    155959  1677398399  ...    723  0.973914  0.797723     1.0
724  20230226   160000    195959  1677412799  ...    724  1.008950  0.878677     1.0
725  20230226   200000    235959  1677427199  ...    725  1.023122  0.908203     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '5521.2311', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23239.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


