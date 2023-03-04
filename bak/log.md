# 20230305 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28060
self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22309.8, self.close=22322.8, self.high=22322.8, self.low=22307.3, self.vol=675.803, self.amt=15080895.8468 
127.0.0.1 - - [05/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-05 00:20:04,496:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230304   235500    235959  ...         0.0        0.0       0
5760  20230305   000000    000459  ...         0.0        0.0       0
5761  20230305   000500    000959  ...         0.0        0.0       0
5762  20230305   001000    001459  ...         0.0        0.0       0
5763  20230305   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 00:20:04,501:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22309.8, self.close=22322.8, self.high=22322.8, self.low=22307.3, self.vol=675.803, self.amt=15080895.8468, ukdf['pct'].iloc[-1]=0.000583 , ukdf['amount'].iloc[-1]=15080895.8468, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-348623.6384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22322.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28061
self.closeSec=1677947099, self.tradeDate='20230305', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22322.8, self.close=22315.1, self.high=22322.8, self.low=22315.0, self.vol=288.743, self.amt=6443754.1002 
2023-03-05 00:25:01,595:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230305   000000    000459  ...         0.0        0.0       0
5761  20230305   000500    000959  ...         0.0        0.0       0
5762  20230305   001000    001459  ...         0.0        0.0       0
5763  20230305   001500    001959  ...         0.0        0.0       0
5764  20230305   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 00:25:01,597:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677947099, self.tradeDate='20230305', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22322.8, self.close=22315.1, self.high=22322.8, self.low=22315.0, self.vol=288.743, self.amt=6443754.1002, ukdf['pct'].iloc[-1]=-0.000345 , ukdf['amount'].iloc[-1]=6443754.1002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-348182.9372705848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22315.37646355', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22309.8, self.close=22322.8, self.high=22322.8, self.low=22307.3 
127.0.0.1 - - [05/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 00:20:02,596:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22309.8, self.close=22322.8, self.high=22322.8, self.low=22307.3   
2023-03-05 00:20:03,198:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230304   235500    235959  1677945599  ...  22302.1 -0.000130   1727    5
1440  20230305   000000    000459  1677945899  ...  22280.4 -0.000897   1440    0
1441  20230305   000500    000959  1677946199  ...  22286.3  0.001144   1441    1
1442  20230305   001000    001459  1677946499  ...  22294.9 -0.000090   1442    2
1443  20230305   001500    001959  1677946799  ...  22307.3  0.000583   1443    3

[5 rows x 11 columns]
2023-03-05 00:20:03,206:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.5108841536626465, self.count=28627 

self.closeSec=1677947099, self.tradeDate='20230305', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22322.8, self.close=22315.1, self.high=22322.8, self.low=22315.0 
127.0.0.1 - - [05/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-05 00:25:01,492:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677947099, self.tradeDate='20230305', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22322.8, self.close=22315.1, self.high=22322.8, self.low=22315.0   
2023-03-05 00:25:01,557:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230305   000000    000459  1677945899  ...  22280.4 -0.000897   1440    0
1441  20230305   000500    000959  1677946199  ...  22286.3  0.001144   1441    1
1442  20230305   001000    001459  1677946499  ...  22294.9 -0.000090   1442    2
1443  20230305   001500    001959  1677946799  ...  22307.3  0.000583   1443    3
1444  20230305   002000    002459  1677947099  ...  22315.0 -0.000345   1444    4

[5 rows x 11 columns]
2023-03-05 00:25:01,557:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-05 00:00:36,027:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230304    212959  22376.0  ...  48.333333  0.423011  0.400867
5803  20230304    215959  22362.3  ...  47.916667  0.418156  0.389404
5804  20230304    222959  22344.5  ...  47.500000  0.416797  0.378115
5805  20230304    225959  22339.8  ...  47.083333  0.415195  0.368966
5806  20230304    232959  22334.1  ...  46.666667  0.414255  0.361230

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-03-05 00:00:36,179:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.512280  0.487720       0  ...  0.874533   1.0    0.0  0.893620
540     0  0.505691  0.494309       0  ...  0.874341   1.0    0.0  0.893424
541     0  0.509127  0.490873       0  ...  0.874118   1.0    0.0  0.893196
542     0  0.507977  0.492023       0  ...  0.873989   1.0    0.0  0.893064
543     0  0.501892  0.498108       0  ...  0.873034   1.0    0.0  0.892088

[5 rows x 10 columns]
2023-03-05 00:00:36,201:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512791  0.487209       0  ...  0.857721   1.0    0.0  0.895733
46     0  0.505836  0.494164       0  ...  0.874341   1.0    0.0  0.892214
47     0  0.509268  0.490732       0  ...  0.874118   1.0    0.0  0.891986
48     0  0.508419  0.491581       0  ...  0.857188   1.0    0.0  0.893346
49     0  0.501892  0.498108       0  ...  0.873034   1.0    0.0  0.892088

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.837', 'enterprice': '22365.6', 'countrevence': '0', 'unrealprofit': '-1926.1385', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22305.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-05 00:00:03,644:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41885F1677945602904I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677945603013438, 'quantity': '46.195', 'price': '22306.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677945602289, 'updatetime': 1677945603013, 'tradetype': 'usdt', 'selfid': 41885, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677945603013, 'clientorderid': '41885F1677945602904I0L59', 'price': '22306.3', 'quantity': '46.195', 'commission': '1030.4395285', 'commissionasset': 'USDT', 'tradetime': 1677945603013, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677945603013}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14312 

self.closeSec=1677946199, self.tradeDate='20230305', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22306.2', self.close='22311.8'
2023-03-05 00:10:01,721:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677946199, self.tradeDate='20230305', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22306.2', self.close='22311.8'
2023-03-05 00:10:01,728:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230304   232000    232959  1677943799  22329.8  22330.7  0.000040
573  20230304   233000    233959  1677944399  22330.8  22323.8 -0.000309
574  20230304   234000    234959  1677944999  22323.9  22326.8  0.000134
575  20230304   235000    235959  1677945599  22326.8  22306.3 -0.000918
576  20230305   000000    000959  1677946199  22306.2  22311.8  0.000247
2023-03-05 00:10:01,728:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14313 

self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22311.8', self.close='22322.8'
127.0.0.1 - - [05/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-05 00:20:03,067:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22311.8', self.close='22322.8'
2023-03-05 00:20:03,416:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230304   233000    233959  1677944399  22330.8  22323.8 -0.000309
574  20230304   234000    234959  1677944999  22323.9  22326.8  0.000134
575  20230304   235000    235959  1677945599  22326.8  22306.3 -0.000918
576  20230305   000000    000959  1677946199  22306.2  22311.8  0.000247
577  20230305   001000    001959  1677946799  22311.8  22322.8  0.000493
2023-03-05 00:20:03,416:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-05 00:00:02,109:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-05 00:00:02,305:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3050000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230304, closeTime:235959, close:22306.3, total:982141.1933777, pct_pre:-0.0003356095116210378, thd:0.47605453983042006, side:sell 
127.0.0.1 - - [05/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14313 

self.closeSec=1677946199, self.tradeDate='20230305', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22306.2', self.close='22311.8'
2023-03-05 00:10:01,731:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677946199, self.tradeDate='20230305', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22306.2', self.close='22311.8'
2023-03-05 00:10:01,744:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230304   232000    232959  1677943799  22329.8  22330.7
17421  20230304   233000    233959  1677944399  22330.8  22323.8
17422  20230304   234000    234959  1677944999  22323.9  22326.8
17423  20230304   235000    235959  1677945599  22326.8  22306.3
17424  20230305   000000    000959  1677946199  22306.2  22311.8
2023-03-05 00:10:01,744:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14314 

self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22311.8', self.close='22322.8'
127.0.0.1 - - [05/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-05 00:20:04,427:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22311.8', self.close='22322.8'
2023-03-05 00:20:04,526:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230304   233000    233959  1677944399  22330.8  22323.8
17422  20230304   234000    234959  1677944999  22323.9  22326.8
17423  20230304   235000    235959  1677945599  22326.8  22306.3
17424  20230305   000000    000959  1677946199  22306.2  22311.8
17425  20230305   001000    001959  1677946799  22311.8  22322.8
2023-03-05 00:20:04,526:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [05/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-05 00:00:03,285:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41884F1677945602757I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677945603020751, 'quantity': '52.735', 'price': '22306.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677945602390, 'updatetime': 1677945603020, 'tradetype': 'usdt', 'selfid': 41884, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677945603020, 'clientorderid': '41884F1677945602757I0L2', 'price': '22306.2', 'quantity': '52.735', 'commission': '1176.317457', 'commissionasset': 'USDT', 'tradetime': 1677945603020, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677945603020}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14313 

self.closeSec=1677946199, self.tradeDate='20230305', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22306.2', self.close='22311.8'
2023-03-05 00:10:01,750:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677946199, self.tradeDate='20230305', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22306.2', self.close='22311.8'
2023-03-05 00:10:01,782:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230304   232000    232959  1677943799  22329.8  22330.7
12237  20230304   233000    233959  1677944399  22330.8  22323.8
12238  20230304   234000    234959  1677944999  22323.9  22326.8
12239  20230304   235000    235959  1677945599  22326.8  22306.3
12240  20230305   000000    000959  1677946199  22306.2  22311.8
2023-03-05 00:10:01,782:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14314 

self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22311.8', self.close='22322.8'
127.0.0.1 - - [05/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-05 00:20:04,277:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22311.8', self.close='22322.8'
2023-03-05 00:20:04,466:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230304   233000    233959  1677944399  22330.8  22323.8
12238  20230304   234000    234959  1677944999  22323.9  22326.8
12239  20230304   235000    235959  1677945599  22326.8  22306.3
12240  20230305   000000    000959  1677946199  22306.2  22311.8
12241  20230305   001000    001959  1677946799  22311.8  22322.8
2023-03-05 00:20:04,466:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24058
self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22309.8, self.close=22322.8, self.high=22322.8, self.low=22307.3, self.vol=675.803, self.amt=15080895.8468 
127.0.0.1 - - [05/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 00:20:01,727:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230304   235500    235959  ...         0.0        0.0       0
5760  20230305   000000    000459  ...         0.0        0.0       0
5761  20230305   000500    000959  ...         0.0        0.0       0
5762  20230305   001000    001459  ...         0.0        0.0       0
5763  20230305   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 00:20:01,730:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677946799, self.tradeDate='20230305', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22309.8, self.close=22322.8, self.high=22322.8, self.low=22307.3, self.vol=675.803, self.amt=15080895.8468, ukdf['pct'].iloc[-1]=0.000583 , ukdf['amount'].iloc[-1]=15080895.8468, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24059
self.closeSec=1677947099, self.tradeDate='20230305', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22322.8, self.close=22315.1, self.high=22322.8, self.low=22315.0, self.vol=288.743, self.amt=6443754.1002 
127.0.0.1 - - [05/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-05 00:25:01,572:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230305   000000    000459  ...         0.0        0.0       0
5761  20230305   000500    000959  ...         0.0        0.0       0
5762  20230305   001000    001459  ...         0.0        0.0       0
5763  20230305   001500    001959  ...         0.0        0.0       0
5764  20230305   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 00:25:01,573:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677947099, self.tradeDate='20230305', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22322.8, self.close=22315.1, self.high=22322.8, self.low=22315.0, self.vol=288.743, self.amt=6443754.1002, ukdf['pct'].iloc[-1]=-0.000345 , ukdf['amount'].iloc[-1]=6443754.1002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230304   120000    155959  1677916799  ...    723  0.598689 -0.049109     NaN
724  20230304   160000    195959  1677931199  ...    724  0.645301  0.120369     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '42653.2605', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22338', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [05/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=596
self.closeSec=1677945599, self.tradeDate='20230304', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22338.0, self.close=22306.3, self.high=22390.0, self.low=22292.9, self.vol=22528.758, self.amt=503340308.8971 
2023-03-05 00:00:01,952:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677945599, self.tradeDate='20230304', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22338.0, self.close=22306.3, self.high=22390.0, self.low=22292.9, self.vol=22528.758, self.amt=503340308.8971 
2023-03-05 00:00:02,099:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230304   040000    075959  ...  59046.812  1.314850e+09 -0.000246
722  20230304   080000    115959  ...  24078.215  5.380207e+08 -0.000152
723  20230304   120000    155959  ...  29929.532  6.686327e+08  0.000327
724  20230304   160000    195959  ...  17632.286  3.938497e+08 -0.000385
725  20230304   200000    235959  ...  22528.758  5.033403e+08 -0.001424

[5 rows x 11 columns]
2023-03-05 00:00:05,010:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230304   040000    075959  1677887999  ...    721  0.488592 -0.429537     NaN
722  20230304   080000    115959  1677902399  ...    722  0.545580 -0.235435     NaN
723  20230304   120000    155959  1677916799  ...    723  0.598689 -0.049109     NaN
724  20230304   160000    195959  1677931199  ...    724  0.645301  0.120369     NaN
725  20230304   200000    235959  1677945599  ...    725  0.685684  0.274947     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '43968.6654326661', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22306.78118114', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


