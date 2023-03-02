# 20230303 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [03/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27484
self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23341.5, self.close=23373.9, self.high=23373.9, self.low=23341.4, self.vol=1057.679, self.amt=24711486.6087 
2023-03-03 00:20:01,695:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230302   235500    235959  ...         0.0        0.0       0
5760  20230303   000000    000459  ...         0.0        0.0       0
5761  20230303   000500    000959  ...         0.0        0.0       0
5762  20230303   001000    001459  ...         0.0        0.0       0
5763  20230303   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 00:20:01,701:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23341.5, self.close=23373.9, self.high=23373.9, self.low=23341.4, self.vol=1057.679, self.amt=24711486.6087, ukdf['pct'].iloc[-1]=0.001401 , ukdf['amount'].iloc[-1]=24711486.6087, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-411874.632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23373.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27485
self.closeSec=1677774299, self.tradeDate='20230303', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23373.9, self.close=23342.4, self.high=23378.2, self.low=23342.3, self.vol=1171.87, self.amt=27380812.1861 
127.0.0.1 - - [03/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-03 00:25:01,583:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230303   000000    000459  ...         0.0        0.0       0
5761  20230303   000500    000959  ...         0.0        0.0       0
5762  20230303   001000    001459  ...         0.0        0.0       0
5763  20230303   001500    001959  ...         0.0        0.0       0
5764  20230303   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 00:25:01,585:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677774299, self.tradeDate='20230303', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23373.9, self.close=23342.4, self.high=23378.2, self.low=23342.3, self.vol=1171.87, self.amt=27380812.1861, ukdf['pct'].iloc[-1]=-0.001348 , ukdf['amount'].iloc[-1]=27380812.1861, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-410269.26575376192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23347.12215092', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6466247171419686, self.count=28050 

self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23341.5, self.close=23373.9, self.high=23373.9, self.low=23341.4 
2023-03-03 00:20:01,505:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23341.5, self.close=23373.9, self.high=23373.9, self.low=23341.4   
2023-03-03 00:20:01,523:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230302   235500    235959  1677772799  ...  23330.6  0.000107   1727    5
1440  20230303   000000    000459  1677773099  ...  23334.5 -0.000484   1440    0
1441  20230303   000500    000959  1677773399  ...  23335.6  0.000917   1441    1
1442  20230303   001000    001459  1677773699  ...  23341.2 -0.000822   1442    2
1443  20230303   001500    001959  1677773999  ...  23341.4  0.001401   1443    3

[5 rows x 11 columns]
2023-03-03 00:20:01,523:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6466247171419686, self.count=28051 

self.closeSec=1677774299, self.tradeDate='20230303', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23373.9, self.close=23342.4, self.high=23378.2, self.low=23342.3 
2023-03-03 00:25:01,485:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677774299, self.tradeDate='20230303', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23373.9, self.close=23342.4, self.high=23378.2, self.low=23342.3   
2023-03-03 00:25:01,521:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230303   000000    000459  1677773099  ...  23334.5 -0.000484   1440    0
1441  20230303   000500    000959  1677773399  ...  23335.6  0.000917   1441    1
1442  20230303   001000    001459  1677773699  ...  23341.2 -0.000822   1442    2
1443  20230303   001500    001959  1677773999  ...  23341.4  0.001401   1443    3
1444  20230303   002000    002459  1677774299  ...  23342.3 -0.001348   1444    4

[5 rows x 11 columns]
2023-03-03 00:25:01,521:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-03 00:00:35,082:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230302    212959  23346.8  ...  50.416667  0.472819  0.725155
5803  20230302    215959  23363.3  ...  50.416667  0.458901  0.733556
5804  20230302    222959  23299.9  ...  50.000000  0.457816  0.739050
5805  20230302    225959  23294.8  ...  50.416667  0.458678  0.743816
5806  20230302    232959  23298.0  ...  50.416667  0.466567  0.744960

[5 rows x 33 columns]
0.5275735294117647
acc is : 0.5275735294117647
2023-03-03 00:00:35,244:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.517189  0.482811       0  ...  0.831963  -1.0    0.0  0.948044
540     1  0.492502  0.507498       0  ...  0.832142  -1.0    0.0  0.947841
541     0  0.501317  0.498683       1  ...  0.832024  -1.0    0.0  0.947975
542     0  0.511687  0.488313       1  ...  0.830949  -1.0    0.0  0.949200
543     0  0.519236  0.480764       1  ...  0.830162  -1.0    0.0  0.950099

[5 rows x 10 columns]
2023-03-03 00:00:35,277:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.516526  0.483474       0  ...  0.835182  -1.0    0.0  0.943766
46     1  0.491524  0.508476       0  ...  0.835361  -1.0    0.0  0.945794
47     0  0.500328  0.499672       1  ...  0.835243  -1.0    0.0  0.945928
48     0  0.511204  0.488796       1  ...  0.834164  -1.0    0.0  0.947534
49     0  0.519236  0.480764       1  ...  0.830162  -1.0    0.0  0.950099

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.484', 'enterprice': '23376.7', 'countrevence': '0', 'unrealprofit': '932.2908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-03-03 00:00:03,168:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41869F1677772802786I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677772802898549, 'quantity': '43.759', 'price': '23350.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677772802392, 'updatetime': 1677772802898, 'tradetype': 'usdt', 'selfid': 41869, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677772802898, 'clientorderid': '41869F1677772802786I0L59', 'price': '23350.3', 'quantity': '43.759', 'commission': '1021.7857777', 'commissionasset': 'USDT', 'tradetime': 1677772802898, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677772802898}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14024 

self.closeSec=1677773399, self.tradeDate='20230303', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23350.3', self.close='23360.4'
2023-03-03 00:10:01,605:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677773399, self.tradeDate='20230303', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23350.3', self.close='23360.4'
2023-03-03 00:10:01,635:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230302   232000    232959  1677770999  23316.4  23328.2  0.000506
573  20230302   233000    233959  1677771599  23328.2  23332.4  0.000180
574  20230302   234000    234959  1677772199  23332.4  23311.1 -0.000913
575  20230302   235000    235959  1677772799    23311  23350.3  0.001682
576  20230303   000000    000959  1677773399  23350.3  23360.4  0.000433
2023-03-03 00:10:01,636:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14025 

self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23360.3', self.close='23373.9'
2023-03-03 00:20:01,603:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23360.3', self.close='23373.9'
2023-03-03 00:20:01,649:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230302   233000    233959  1677771599  23328.2  23332.4  0.000180
574  20230302   234000    234959  1677772199  23332.4  23311.1 -0.000913
575  20230302   235000    235959  1677772799    23311  23350.3  0.001682
576  20230303   000000    000959  1677773399  23350.3  23360.4  0.000433
577  20230303   001000    001959  1677773999  23360.3  23373.9  0.000578
2023-03-03 00:20:01,649:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-03 00:00:02,121:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-03 00:00:02,239:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3030000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230302, closeTime:235959, close:23350.3, total:982141.1933777, pct_pre:-0.009356799457822418, thd:0.17395553752810744, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14025 

self.closeSec=1677773399, self.tradeDate='20230303', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23350.3', self.close='23360.4'
2023-03-03 00:10:01,607:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677773399, self.tradeDate='20230303', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23350.3', self.close='23360.4'
127.0.0.1 - - [03/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-03 00:10:01,622:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230302   232000    232959  1677770999  23316.4  23328.2
17421  20230302   233000    233959  1677771599  23328.2  23332.4
17422  20230302   234000    234959  1677772199  23332.4  23311.1
17423  20230302   235000    235959  1677772799    23311  23350.3
17424  20230303   000000    000959  1677773399  23350.3  23360.4
2023-03-03 00:10:01,622:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14026 

self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23360.3', self.close='23373.9'
127.0.0.1 - - [03/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-03 00:20:01,657:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23360.3', self.close='23373.9'
2023-03-03 00:20:01,729:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230302   233000    233959  1677771599  23328.2  23332.4
17422  20230302   234000    234959  1677772199  23332.4  23311.1
17423  20230302   235000    235959  1677772799    23311  23350.3
17424  20230303   000000    000959  1677773399  23350.3  23360.4
17425  20230303   001000    001959  1677773999  23360.3  23373.9
2023-03-03 00:20:01,733:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [03/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-03 00:00:03,440:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41870F1677772802895I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677772803120685, 'quantity': '48.169', 'price': '23350.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677772802412, 'updatetime': 1677772803120, 'tradetype': 'usdt', 'selfid': 41870, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677772803120, 'clientorderid': '41870F1677772802895I0L2', 'price': '23350.2', 'quantity': '48.169', 'commission': '1124.7557838', 'commissionasset': 'USDT', 'tradetime': 1677772803120, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677772803120}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14025 

self.closeSec=1677773399, self.tradeDate='20230303', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23350.3', self.close='23360.4'
2023-03-03 00:10:01,609:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677773399, self.tradeDate='20230303', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23350.3', self.close='23360.4'
2023-03-03 00:10:01,647:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230302   232000    232959  1677770999  23316.4  23328.2
12237  20230302   233000    233959  1677771599  23328.2  23332.4
12238  20230302   234000    234959  1677772199  23332.4  23311.1
12239  20230302   235000    235959  1677772799    23311  23350.3
12240  20230303   000000    000959  1677773399  23350.3  23360.4
2023-03-03 00:10:01,647:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [03/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14026 

self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23360.3', self.close='23373.9'
2023-03-03 00:20:01,643:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23360.3', self.close='23373.9'
2023-03-03 00:20:01,716:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230302   233000    233959  1677771599  23328.2  23332.4
12238  20230302   234000    234959  1677772199  23332.4  23311.1
12239  20230302   235000    235959  1677772799    23311  23350.3
12240  20230303   000000    000959  1677773399  23350.3  23360.4
12241  20230303   001000    001959  1677773999  23360.3  23373.9
2023-03-03 00:20:01,716:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [03/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23482
self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23341.5, self.close=23373.9, self.high=23373.9, self.low=23341.4, self.vol=1057.679, self.amt=24711486.6087 
2023-03-03 00:20:01,776:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230302   235500    235959  ...         0.0        0.0       0
5760  20230303   000000    000459  ...         0.0        0.0       0
5761  20230303   000500    000959  ...         0.0        0.0       0
5762  20230303   001000    001459  ...         0.0        0.0       0
5763  20230303   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 00:20:01,777:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677773999, self.tradeDate='20230303', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23341.5, self.close=23373.9, self.high=23373.9, self.low=23341.4, self.vol=1057.679, self.amt=24711486.6087, ukdf['pct'].iloc[-1]=0.001401 , ukdf['amount'].iloc[-1]=24711486.6087, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23483
self.closeSec=1677774299, self.tradeDate='20230303', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23373.9, self.close=23342.4, self.high=23378.2, self.low=23342.3, self.vol=1171.87, self.amt=27380812.1861 
2023-03-03 00:25:01,563:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230303   000000    000459  ...         0.0        0.0       0
5761  20230303   000500    000959  ...         0.0        0.0       0
5762  20230303   001000    001459  ...         0.0        0.0       0
5763  20230303   001500    001959  ...         0.0        0.0       0
5764  20230303   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 00:25:01,564:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677774299, self.tradeDate='20230303', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23373.9, self.close=23342.4, self.high=23378.2, self.low=23342.3, self.vol=1171.87, self.amt=27380812.1861, ukdf['pct'].iloc[-1]=-0.001348 , ukdf['amount'].iloc[-1]=27380812.1861, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230302   040000    075959  ...   79548.850  1.867409e+09  0.011862
722  20230302   080000    115959  ...   66503.537  1.567660e+09 -0.005618
723  20230302   120000    155959  ...   49671.496  1.163425e+09 -0.004479
724  20230302   160000    195959  ...   48950.758  1.145241e+09  0.001014
725  20230302   200000    235959  ...  124403.213  2.899906e+09 -0.002363

[5 rows x 11 columns]
2023-03-03 00:00:05,075:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230302   040000    075959  1677715199  ...    721  0.605781 -0.246234     NaN
722  20230302   080000    115959  1677729599  ...    722  0.744600  0.123421     NaN
723  20230302   120000    155959  1677743999  ...    723  0.643526 -0.179710     NaN
724  20230302   160000    195959  1677758399  ...    724  0.511077 -0.571254     NaN
725  20230302   200000    235959  1677772799  ...    725  0.467245 -0.693599    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '10186.2285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23350.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '10186.2285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23350.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-03-03 00:00:10,777:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '986834.0965399', 'total': '986834.0965399', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-03-03 00:00:11,034:INFO:s_rsrs:main.py:269:openSell:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 42.135, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41872F1677772811033I0L65'}
2023-03-03 00:00:11,056:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:3030000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230302, closeTime:235959, close:23350.3, sign:-1, total:986834.0965399, side:sell  
127.0.0.1 - - [03/Mar/2023 00:00:11] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Mar/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-03-03 00:00:11,060:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41871F1677772805612I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677772805721998, 'quantity': '42.179', 'price': '23350.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677772805319, 'updatetime': 1677772805721, 'tradetype': 'usdt', 'selfid': 41871, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677772805721, 'clientorderid': '41871F1677772805612I0L65', 'price': '23350.2', 'quantity': '42.179', 'commission': '984.8880858', 'commissionasset': 'USDT', 'tradetime': 1677772805721, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677772805721}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-03 00:00:11,060:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41871F1677772805612I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677772805721998, 'quantity': '42.179', 'price': '23350.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677772805319, 'updatetime': 1677772805721, 'tradetype': 'usdt', 'selfid': 41871, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677772805721, 'clientorderid': '41871F1677772805612I0L65', 'price': '23350.2', 'quantity': '42.179', 'commission': '984.8880858', 'commissionasset': 'USDT', 'tradetime': 1677772805721, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677772805721}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Mar/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-03-03 00:00:11,158:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41872F1677772811033I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677772811121417, 'quantity': '42.135', 'price': '23350.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677772810800, 'updatetime': 1677772811121, 'tradetype': 'usdt', 'selfid': 41872, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677772811121, 'clientorderid': '41872F1677772811033I0L65', 'price': '23350.3', 'quantity': '42.135', 'commission': '983.8648905', 'commissionasset': 'USDT', 'tradetime': 1677772811121, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677772811121}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-03 00:00:11,390:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41872F1677772811033I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677772811121417, 'quantity': '42.135', 'price': '23350.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677772810800, 'updatetime': 1677772811121, 'tradetype': 'usdt', 'selfid': 41872, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677772811121, 'clientorderid': '41872F1677772811033I0L65', 'price': '23350.3', 'quantity': '42.135', 'commission': '983.8648905', 'commissionasset': 'USDT', 'tradetime': 1677772811121, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677772811121}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Mar/2023 00:00:11] "POST / HTTP/1.1" 200 -


