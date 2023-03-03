# 20230304 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27772
self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22312.7, self.close=22336.0, self.high=22350.0, self.low=22310.9, self.vol=1278.975, self.amt=28555833.8407 
127.0.0.1 - - [04/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 00:20:02,808:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230303   235500    235959  ...         0.0        0.0       0
5760  20230304   000000    000459  ...         0.0        0.0       0
5761  20230304   000500    000959  ...         0.0        0.0       0
5762  20230304   001000    001459  ...         0.0        0.0       0
5763  20230304   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 00:20:02,817:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22312.7, self.close=22336.0, self.high=22350.0, self.low=22310.9, self.vol=1278.975, self.amt=28555833.8407, ukdf['pct'].iloc[-1]=0.001044 , ukdf['amount'].iloc[-1]=28555833.8407, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-349417.9616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22335.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27773
self.closeSec=1677860699, self.tradeDate='20230304', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22335.9, self.close=22342.3, self.high=22354.4, self.low=22325.3, self.vol=807.683, self.amt=18044289.0502 
127.0.0.1 - - [04/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-04 00:25:01,591:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230304   000000    000459  ...         0.0        0.0       0
5761  20230304   000500    000959  ...         0.0        0.0       0
5762  20230304   001000    001459  ...         0.0        0.0       0
5763  20230304   001500    001959  ...         0.0        0.0       0
5764  20230304   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 00:25:01,591:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677860699, self.tradeDate='20230304', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22335.9, self.close=22342.3, self.high=22354.4, self.low=22325.3, self.vol=807.683, self.amt=18044289.0502, ukdf['pct'].iloc[-1]=0.000282 , ukdf['amount'].iloc[-1]=18044289.0502, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-349827.1584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22342.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22312.7, self.close=22336.0, self.high=22350.0, self.low=22310.9 
127.0.0.1 - - [04/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 00:20:01,812:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22312.7, self.close=22336.0, self.high=22350.0, self.low=22310.9   
2023-03-04 00:20:01,844:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230303   235500    235959  1677859199  ...  22305.7  0.000816   1727    5
1440  20230304   000000    000459  1677859499  ...  22311.7  0.000403   1440    0
1441  20230304   000500    000959  1677859799  ...  22332.9  0.000649   1441    1
1442  20230304   001000    001459  1677860099  ...  22310.0 -0.001553   1442    2
1443  20230304   001500    001959  1677860399  ...  22310.9  0.001044   1443    3

[5 rows x 11 columns]
2023-03-04 00:20:01,844:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6634351189289961, self.count=28339 

self.closeSec=1677860699, self.tradeDate='20230304', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22335.9, self.close=22342.3, self.high=22354.4, self.low=22325.3 
2023-03-04 00:25:01,499:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677860699, self.tradeDate='20230304', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22335.9, self.close=22342.3, self.high=22354.4, self.low=22325.3   
2023-03-04 00:25:01,552:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230304   000000    000459  1677859499  ...  22311.7  0.000403   1440    0
1441  20230304   000500    000959  1677859799  ...  22332.9  0.000649   1441    1
1442  20230304   001000    001459  1677860099  ...  22310.0 -0.001553   1442    2
1443  20230304   001500    001959  1677860399  ...  22310.9  0.001044   1443    3
1444  20230304   002000    002459  1677860699  ...  22325.3  0.000282   1444    4

[5 rows x 11 columns]
2023-03-04 00:25:01,553:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-04 00:00:34,231:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230303    212959  22341.6  ...  50.833333  0.372478  0.691508
5803  20230303    215959  22368.0  ...  50.833333  0.378188  0.691869
5804  20230303    222959  22391.4  ...  50.416667  0.375688  0.692870
5805  20230303    225959  22374.7  ...  50.416667  0.373966  0.694258
5806  20230303    232959  22363.3  ...  50.000000  0.373859  0.695580

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-03-04 00:00:34,397:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.533887  0.466113       1  ...  0.849248   1.0    0.0  0.913931
540     0  0.537127  0.462873       0  ...  0.848615   1.0    0.0  0.913249
541     0  0.526135  0.473865       0  ...  0.848182   1.0    0.0  0.912784
542     0  0.525039  0.474961       0  ...  0.848156   1.0    0.0  0.912755
543     0  0.527091  0.472909       0  ...  0.846688   1.0    0.0  0.911176

[5 rows x 10 columns]
2023-03-04 00:00:34,417:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.534710  0.465290       1  ...  0.849248   1.0    0.0  0.915336
46     0  0.537269  0.462731       0  ...  0.848615   1.0    0.0  0.913249
47     0  0.526339  0.473661       0  ...  0.848182   1.0    0.0  0.912784
48     0  0.525969  0.474031       0  ...  0.848156   1.0    0.0  0.913994
49     0  0.527091  0.472909       0  ...  0.846688   1.0    0.0  0.911176

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.837', 'enterprice': '22365.6', 'countrevence': '0', 'unrealprofit': '-1504.32877563397', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22318.34904119', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [04/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-04 00:00:03,083:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41880F1677859202706I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677859202814919, 'quantity': '46.2', 'price': '22324', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677859202339, 'updatetime': 1677859202814, 'tradetype': 'usdt', 'selfid': 41880, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677859202814, 'clientorderid': '41880F1677859202706I0L59', 'price': '22324', 'quantity': '46.2', 'commission': '1031.3688', 'commissionasset': 'USDT', 'tradetime': 1677859202814, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677859202814}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14168 

self.closeSec=1677859799, self.tradeDate='20230304', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22324', self.close='22347.4'
2023-03-04 00:10:01,737:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677859799, self.tradeDate='20230304', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22324', self.close='22347.4'
2023-03-04 00:10:01,797:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230303   232000    232959  1677857399  22355.9    22360  0.000188
573  20230303   233000    233959  1677857999  22362.6  22329.2 -0.001377
574  20230303   234000    234959  1677858599  22329.2  22323.8 -0.000242
575  20230303   235000    235959  1677859199  22323.8  22323.9  0.000004
576  20230304   000000    000959  1677859799    22324  22347.4  0.001053
2023-03-04 00:10:01,798:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14169 

self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22347.4', self.close='22336'
2023-03-04 00:20:01,852:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22347.4', self.close='22336'
2023-03-04 00:20:01,882:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230303   233000    233959  1677857999  22362.6  22329.2 -0.001377
574  20230303   234000    234959  1677858599  22329.2  22323.8 -0.000242
575  20230303   235000    235959  1677859199  22323.8  22323.9  0.000004
576  20230304   000000    000959  1677859799    22324  22347.4  0.001053
577  20230304   001000    001959  1677860399  22347.4    22336 -0.000510
2023-03-04 00:20:01,882:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-04 00:00:02,112:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-04 00:00:02,250:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3040000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230303, closeTime:235959, close:22323.9, total:982141.1933777, pct_pre:-0.042914504888614924, thd:-0.5550662142705083, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14169 

self.closeSec=1677859799, self.tradeDate='20230304', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22324', self.close='22347.4'
2023-03-04 00:10:01,758:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677859799, self.tradeDate='20230304', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22324', self.close='22347.4'
127.0.0.1 - - [04/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-04 00:10:01,771:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230303   232000    232959  1677857399  22355.9    22360
17421  20230303   233000    233959  1677857999  22362.6  22329.2
17422  20230303   234000    234959  1677858599  22329.2  22323.8
17423  20230303   235000    235959  1677859199  22323.8  22323.9
17424  20230304   000000    000959  1677859799    22324  22347.4
2023-03-04 00:10:01,771:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14170 

self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22347.4', self.close='22336'
127.0.0.1 - - [04/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 00:20:02,204:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22347.4', self.close='22336'
2023-03-04 00:20:02,490:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230303   233000    233959  1677857999  22362.6  22329.2
17422  20230303   234000    234959  1677858599  22329.2  22323.8
17423  20230303   235000    235959  1677859199  22323.8  22323.9
17424  20230304   000000    000959  1677859799    22324  22347.4
17425  20230304   001000    001959  1677860399  22347.4    22336
2023-03-04 00:20:02,491:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [04/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-04 00:00:03,318:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41881F1677859202790I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677859202910174, 'quantity': '47.916', 'price': '22324', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677859202498, 'updatetime': 1677859202910, 'tradetype': 'usdt', 'selfid': 41881, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677859202910, 'clientorderid': '41881F1677859202790I0L2', 'price': '22324', 'quantity': '47.916', 'commission': '1069.676784', 'commissionasset': 'USDT', 'tradetime': 1677859202910, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677859202910}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14169 

self.closeSec=1677859799, self.tradeDate='20230304', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22324', self.close='22347.4'
2023-03-04 00:10:01,755:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677859799, self.tradeDate='20230304', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22324', self.close='22347.4'
2023-03-04 00:10:01,804:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230303   232000    232959  1677857399  22355.9    22360
12237  20230303   233000    233959  1677857999  22362.6  22329.2
12238  20230303   234000    234959  1677858599  22329.2  22323.8
12239  20230303   235000    235959  1677859199  22323.8  22323.9
12240  20230304   000000    000959  1677859799    22324  22347.4
2023-03-04 00:10:01,804:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14170 

self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22347.4', self.close='22336'
127.0.0.1 - - [04/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 00:20:02,071:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22347.4', self.close='22336'
2023-03-04 00:20:02,421:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230303   233000    233959  1677857999  22362.6  22329.2
12238  20230303   234000    234959  1677858599  22329.2  22323.8
12239  20230303   235000    235959  1677859199  22323.8  22323.9
12240  20230304   000000    000959  1677859799    22324  22347.4
12241  20230304   001000    001959  1677860399  22347.4    22336
2023-03-04 00:20:02,421:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23770
self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22312.7, self.close=22336.0, self.high=22350.0, self.low=22310.9, self.vol=1278.975, self.amt=28555833.8407 
127.0.0.1 - - [04/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 00:20:01,712:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230303   235500    235959  ...         0.0        0.0       0
5760  20230304   000000    000459  ...         0.0        0.0       0
5761  20230304   000500    000959  ...         0.0        0.0       0
5762  20230304   001000    001459  ...         0.0        0.0       0
5763  20230304   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 00:20:01,714:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677860399, self.tradeDate='20230304', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22312.7, self.close=22336.0, self.high=22350.0, self.low=22310.9, self.vol=1278.975, self.amt=28555833.8407, ukdf['pct'].iloc[-1]=0.001044 , ukdf['amount'].iloc[-1]=28555833.8407, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23771
self.closeSec=1677860699, self.tradeDate='20230304', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22335.9, self.close=22342.3, self.high=22354.4, self.low=22325.3, self.vol=807.683, self.amt=18044289.0502 
127.0.0.1 - - [04/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-04 00:25:01,550:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230304   000000    000459  ...         0.0        0.0       0
5761  20230304   000500    000959  ...         0.0        0.0       0
5762  20230304   001000    001459  ...         0.0        0.0       0
5763  20230304   001500    001959  ...         0.0        0.0       0
5764  20230304   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 00:25:01,550:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677860699, self.tradeDate='20230304', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22335.9, self.close=22342.3, self.high=22354.4, self.low=22325.3, self.vol=807.683, self.amt=18044289.0502, ukdf['pct'].iloc[-1]=0.000282 , ukdf['amount'].iloc[-1]=18044289.0502, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230303   120000    155959  1677830399  ...    723  0.128108 -1.587200    -1.0
724  20230303   160000    195959  1677844799  ...    724  0.242193 -1.221520    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '42878.4730744422', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22332.65497628', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=590
self.closeSec=1677859199, self.tradeDate='20230303', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22333.9, self.close=22323.9, self.high=22495.2, self.low=22120.1, self.vol=111464.429, self.amt=2489668739.3042 
2023-03-04 00:00:01,945:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677859199, self.tradeDate='20230303', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22333.9, self.close=22323.9, self.high=22495.2, self.low=22120.1, self.vol=111464.429, self.amt=2489668739.3042 
127.0.0.1 - - [04/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-04 00:00:02,006:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230303   040000    075959  ...   52550.701  1.233292e+09  0.000021
722  20230303   080000    115959  ...  265795.593  5.977734e+09 -0.049056
723  20230303   120000    155959  ...   58370.469  1.304177e+09  0.001856
724  20230303   160000    195959  ...   48913.566  1.094198e+09 -0.000622
725  20230303   200000    235959  ...  111464.429  2.489669e+09 -0.000448

[5 rows x 11 columns]
2023-03-04 00:00:04,369:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230303   040000    075959  1677801599  ...    721  0.409550 -0.830516    -1.0
722  20230303   080000    115959  1677815999  ...    722  0.016977 -1.952277    -1.0
723  20230303   120000    155959  1677830399  ...    723  0.128108 -1.587200    -1.0
724  20230303   160000    195959  1677844799  ...    724  0.242193 -1.221520    -1.0
725  20230303   200000    235959  1677859199  ...    725  0.347434 -0.889416    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '43114.25199915525', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22327.05917885', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


