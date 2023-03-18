# 20230319 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32092
self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27271.6, self.close=27249.6, self.high=27275.0, self.low=27230.5, self.vol=1316.259, self.amt=35869769.5049 
127.0.0.1 - - [19/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 00:20:03,354:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230318   235500    235959  ...         0.0        0.0       0
5760  20230319   000000    000459  ...         0.0        0.0       0
5761  20230319   000500    000959  ...         0.0        0.0       0
5762  20230319   001000    001459  ...         0.0        0.0       0
5763  20230319   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 00:20:03,365:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27271.6, self.close=27249.6, self.high=27275.0, self.low=27230.5, self.vol=1316.259, self.amt=35869769.5049, ukdf['pct'].iloc[-1]=-0.000642 , ukdf['amount'].iloc[-1]=35869769.5049, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-644581.2416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27240.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32093
self.closeSec=1679156699, self.tradeDate='20230319', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27247.0, self.close=27266.3, self.high=27268.7, self.low=27231.2, self.vol=987.855, self.amt=26919923.2161 
127.0.0.1 - - [19/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-19 00:25:01,690:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230319   000000    000459  ...         0.0        0.0       0
5761  20230319   000500    000959  ...         0.0        0.0       0
5762  20230319   001000    001459  ...         0.0        0.0       0
5763  20230319   001500    001959  ...         0.0        0.0       0
5764  20230319   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 00:25:01,692:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679156699, self.tradeDate='20230319', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27247.0, self.close=27266.3, self.high=27268.7, self.low=27231.2, self.vol=987.855, self.amt=26919923.2161, ukdf['pct'].iloc[-1]=0.000613 , ukdf['amount'].iloc[-1]=26919923.2161, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-645669.9456475776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27258.9919976', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27271.6, self.close=27249.6, self.high=27275.0, self.low=27230.5 
127.0.0.1 - - [19/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 00:20:02,230:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27271.6, self.close=27249.6, self.high=27275.0, self.low=27230.5   
2023-03-19 00:20:02,559:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230318   235500    235959  1679155199  ...  27202.3 -0.001691   1727    5
1440  20230319   000000    000459  1679155499  ...  27157.3  0.000772   1440    0
1441  20230319   000500    000959  1679155799  ...  27236.2  0.003025   1441    1
1442  20230319   001000    001459  1679156099  ...  27243.3 -0.001940   1442    2
1443  20230319   001500    001959  1679156399  ...  27230.5 -0.000642   1443    3

[5 rows x 11 columns]
2023-03-19 00:20:02,559:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=60, self.factor=0.2232730536028458, self.count=32659 

self.closeSec=1679156699, self.tradeDate='20230319', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27247.0, self.close=27266.3, self.high=27268.7, self.low=27231.2 
2023-03-19 00:25:01,624:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679156699, self.tradeDate='20230319', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27247.0, self.close=27266.3, self.high=27268.7, self.low=27231.2   
127.0.0.1 - - [19/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-19 00:25:01,672:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230319   000000    000459  1679155499  ...  27157.3  0.000772   1440    0
1441  20230319   000500    000959  1679155799  ...  27236.2  0.003025   1441    1
1442  20230319   001000    001459  1679156099  ...  27243.3 -0.001940   1442    2
1443  20230319   001500    001959  1679156399  ...  27230.5 -0.000642   1443    3
1444  20230319   002000    002459  1679156699  ...  27231.2  0.000613   1444    4

[5 rows x 11 columns]
2023-03-19 00:25:01,672:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-19 00:00:35,211:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230318    212959  27493.1  ...  50.416667  0.603148  0.216297
5803  20230318    215959  27429.9  ...  50.000000  0.600015  0.217687
5804  20230318    222959  27404.5  ...  50.000000  0.610286  0.214185
5805  20230318    225959  27530.8  ...  49.583333  0.609275  0.213173
5806  20230318    232959  27522.8  ...  49.166667  0.581218  0.225188

[5 rows x 33 columns]
0.5698529411764706
acc is : 0.5698529411764706
2023-03-19 00:00:35,374:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.459049  0.540951       0  ...  1.134653  -1.0    0.0  1.222951
540     1  0.474234  0.525766       1  ...  1.129423  -1.0    0.0  1.228587
541     0  0.533031  0.466969       0  ...  1.129752  -1.0    0.0  1.228230
542     1  0.490932  0.509068       0  ...  1.139127  -1.0    0.0  1.218038
543     1  0.395755  0.604245       0  ...  1.142278  -1.0    0.0  1.214669

[5 rows x 10 columns]
2023-03-19 00:00:35,410:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.458919  0.541081       0  ...  1.144567  -1.0    0.0  1.221899
46     1  0.474426  0.525574       1  ...  1.129423  -1.0    0.0  1.227618
47     0  0.532010  0.467990       0  ...  1.129752  -1.0    0.0  1.227261
48     1  0.490706  0.509294       0  ...  1.139127  -1.0    0.0  1.217728
49     1  0.395755  0.604245       0  ...  1.142278  -1.0    0.0  1.214669

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [19/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-19 00:00:03,575:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42018F1679155202838I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679155203091663, 'quantity': '29.326', 'price': '27218.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679155202450, 'updatetime': 1679155203091, 'tradetype': 'usdt', 'selfid': 42018, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679155203091, 'clientorderid': '42018F1679155202838I0L59', 'price': '27218.9', 'quantity': '29.326', 'commission': '798.2214614', 'commissionasset': 'USDT', 'tradetime': 1679155203091, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679155203091}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16328 

self.closeSec=1679155799, self.tradeDate='20230319', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27218.9', self.close='27320.1'
2023-03-19 00:10:01,635:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679155799, self.tradeDate='20230319', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27218.9', self.close='27320.1'
2023-03-19 00:10:01,689:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230318   232000    232959  1679153399  27411.7  27294.4 -0.004276
573  20230318   233000    233959  1679153999  27295.5  27199.9 -0.003462
574  20230318   234000    234959  1679154599    27203  27216.7  0.000618
575  20230318   235000    235959  1679155199    27217  27218.9  0.000081
576  20230319   000000    000959  1679155799  27218.9  27320.1  0.003718
2023-03-19 00:10:01,690:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16329 

self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27320', self.close='27249.6'
127.0.0.1 - - [19/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-19 00:20:03,185:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27320', self.close='27249.6'
2023-03-19 00:20:03,604:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230318   233000    233959  1679153999  27295.5  27199.9 -0.003462
574  20230318   234000    234959  1679154599    27203  27216.7  0.000618
575  20230318   235000    235959  1679155199    27217  27218.9  0.000081
576  20230319   000000    000959  1679155799  27218.9  27320.1  0.003718
577  20230319   001000    001959  1679156399    27320  27249.6 -0.002581
2023-03-19 00:20:03,604:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-19 00:00:02,164:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-19 00:00:02,300:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3190000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230318, closeTime:235959, close:27218.9, total:1054769.6042238, pct_pre:0.0347083711090963, thd:-0.14489217762330053, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16329 

self.closeSec=1679155799, self.tradeDate='20230319', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27218.9', self.close='27320.1'
2023-03-19 00:10:01,611:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679155799, self.tradeDate='20230319', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27218.9', self.close='27320.1'
127.0.0.1 - - [19/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-19 00:10:01,665:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230318   232000    232959  1679153399  27411.7  27294.4
17421  20230318   233000    233959  1679153999  27295.5  27199.9
17422  20230318   234000    234959  1679154599    27203  27216.7
17423  20230318   235000    235959  1679155199    27217  27218.9
17424  20230319   000000    000959  1679155799  27218.9  27320.1
2023-03-19 00:10:01,665:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16330 

self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27320', self.close='27249.6'
127.0.0.1 - - [19/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 00:20:04,282:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27320', self.close='27249.6'
2023-03-19 00:20:04,350:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230318   233000    233959  1679153999  27295.5  27199.9
17422  20230318   234000    234959  1679154599    27203  27216.7
17423  20230318   235000    235959  1679155199    27217  27218.9
17424  20230319   000000    000959  1679155799  27218.9  27320.1
17425  20230319   001000    001959  1679156399    27320  27249.6
2023-03-19 00:20:04,350:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [19/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-19 00:00:03,367:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42019F1679155202873I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679155203004164, 'quantity': '41.025', 'price': '27218.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679155202542, 'updatetime': 1679155203004, 'tradetype': 'usdt', 'selfid': 42019, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679155203004, 'clientorderid': '42019F1679155202873I0L2', 'price': '27218.9', 'quantity': '41.025', 'commission': '1116.6553725', 'commissionasset': 'USDT', 'tradetime': 1679155203004, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679155203004}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16329 

self.closeSec=1679155799, self.tradeDate='20230319', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27218.9', self.close='27320.1'
2023-03-19 00:10:01,652:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679155799, self.tradeDate='20230319', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27218.9', self.close='27320.1'
2023-03-19 00:10:01,693:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230318   232000    232959  1679153399  27411.7  27294.4
12237  20230318   233000    233959  1679153999  27295.5  27199.9
12238  20230318   234000    234959  1679154599    27203  27216.7
12239  20230318   235000    235959  1679155199    27217  27218.9
12240  20230319   000000    000959  1679155799  27218.9  27320.1
2023-03-19 00:10:01,696:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16330 

self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27320', self.close='27249.6'
127.0.0.1 - - [19/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 00:20:04,025:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27320', self.close='27249.6'
2023-03-19 00:20:04,196:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230318   233000    233959  1679153999  27295.5  27199.9
12238  20230318   234000    234959  1679154599    27203  27216.7
12239  20230318   235000    235959  1679155199    27217  27218.9
12240  20230319   000000    000959  1679155799  27218.9  27320.1
12241  20230319   001000    001959  1679156399    27320  27249.6
2023-03-19 00:20:04,197:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [19/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28090
self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27271.6, self.close=27249.6, self.high=27275.0, self.low=27230.5, self.vol=1316.259, self.amt=35869769.5049 
2023-03-19 00:20:01,578:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230318   235500    235959  ...         0.0        0.0       0
5760  20230319   000000    000459  ...         0.0        0.0       0
5761  20230319   000500    000959  ...         0.0        0.0       0
5762  20230319   001000    001459  ...         0.0        0.0       0
5763  20230319   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 00:20:01,579:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679156399, self.tradeDate='20230319', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27271.6, self.close=27249.6, self.high=27275.0, self.low=27230.5, self.vol=1316.259, self.amt=35869769.5049, ukdf['pct'].iloc[-1]=-0.000642 , ukdf['amount'].iloc[-1]=35869769.5049, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28091
self.closeSec=1679156699, self.tradeDate='20230319', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27247.0, self.close=27266.3, self.high=27268.7, self.low=27231.2, self.vol=987.855, self.amt=26919923.2161 
127.0.0.1 - - [19/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-19 00:25:01,744:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230319   000000    000459  ...         0.0        0.0       0
5761  20230319   000500    000959  ...         0.0        0.0       0
5762  20230319   001000    001459  ...         0.0        0.0       0
5763  20230319   001500    001959  ...         0.0        0.0       0
5764  20230319   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 00:25:01,744:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679156699, self.tradeDate='20230319', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27247.0, self.close=27266.3, self.high=27268.7, self.low=27231.2, self.vol=987.855, self.amt=26919923.2161, ukdf['pct'].iloc[-1]=0.000613 , ukdf['amount'].iloc[-1]=26919923.2161, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230318   120000    155959  1679126399  ...    723  0.790757  0.466857     NaN
724  20230318   160000    195959  1679140799  ...    724  0.763908  0.372658     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '2110.3200978398', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27439.22892644', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [19/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=680
self.closeSec=1679155199, self.tradeDate='20230318', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27439.9, self.close=27218.9, self.high=27658.4, self.low=27037.0, self.vol=147089.406, self.amt=4027337065.66546 
2023-03-19 00:00:01,853:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679155199, self.tradeDate='20230318', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27439.9, self.close=27218.9, self.high=27658.4, self.low=27037.0, self.vol=147089.406, self.amt=4027337065.66546 
2023-03-19 00:00:01,896:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230318   040000    075959  ...  271230.892  7.389118e+09  0.021315
722  20230318   080000    115959  ...  145608.554  3.984148e+09 -0.003312
723  20230318   120000    155959  ...   67348.417  1.847161e+09  0.002147
724  20230318   160000    195959  ...   87883.227  2.399320e+09  0.003221
725  20230318   200000    235959  ...  147089.406  4.027337e+09 -0.008058

[5 rows x 11 columns]
2023-03-19 00:00:04,563:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230318   040000    075959  1679097599  ...    721  0.897811  0.812698     1.0
722  20230318   080000    115959  1679111999  ...    722  0.861374  0.690349     1.0
723  20230318   120000    155959  1679126399  ...    723  0.790757  0.466857     NaN
724  20230318   160000    195959  1679140799  ...    724  0.763908  0.372658     NaN
725  20230318   200000    235959  1679155199  ...    725  0.763519  0.358986     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '-9736.895', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27219', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


