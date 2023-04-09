# 20230410 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38428
self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27898.0, self.close=27896.0, self.high=27902.0, self.low=27891.3, self.vol=525.466, self.amt=14658589.5294 
127.0.0.1 - - [10/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-10 00:20:07,998:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230409   235500    235959  ...         0.0        0.0       0
5760  20230410   000000    000459  ...         0.0        0.0       0
5761  20230410   000500    000959  ...         0.0        0.0       0
5762  20230410   001000    001459  ...         0.0        0.0       0
5763  20230410   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 00:20:08,028:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27898.0, self.close=27896.0, self.high=27902.0, self.low=27891.3, self.vol=525.466, self.amt=14658589.5294, ukdf['pct'].iloc[-1]=-6.8e-05 , ukdf['amount'].iloc[-1]=14658589.5294, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-684083.84340520384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27897.35110684', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38429
self.closeSec=1681057499, self.tradeDate='20230410', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27896.0, self.close=27897.4, self.high=27910.0, self.low=27893.9, self.vol=537.361, self.amt=14994641.268 
127.0.0.1 - - [10/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-10 00:25:01,583:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230410   000000    000459  ...         0.0        0.0       0
5761  20230410   000500    000959  ...         0.0        0.0       0
5762  20230410   001000    001459  ...         0.0        0.0       0
5763  20230410   001500    001959  ...         0.0        0.0       0
5764  20230410   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 00:25:01,586:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681057499, self.tradeDate='20230410', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27896.0, self.close=27897.4, self.high=27910.0, self.low=27893.9, self.vol=537.361, self.amt=14994641.268, ukdf['pct'].iloc[-1]=5e-05 , ukdf['amount'].iloc[-1]=14994641.268, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-684086.89700804112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27897.40185137', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27898.0, self.close=27896.0, self.high=27902.0, self.low=27891.3 
127.0.0.1 - - [10/Apr/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-04-10 00:20:05,009:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27898.0, self.close=27896.0, self.high=27902.0, self.low=27891.3   
2023-04-10 00:20:06,449:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230409   235500    235959  1681055999  ...  27869.7 -0.000011   1727    5
1440  20230410   000000    000459  1681056299  ...  27871.2  0.000219   1440    0
1441  20230410   000500    000959  1681056599  ...  27874.9  0.000025   1441    1
1442  20230410   001000    001459  1681056899  ...  27875.2  0.000628   1442    2
1443  20230410   001500    001959  1681057199  ...  27891.3 -0.000068   1443    3

[5 rows x 11 columns]
2023-04-10 00:20:06,458:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=88, self.factor=0.5930929093525642, self.count=38995 

self.closeSec=1681057499, self.tradeDate='20230410', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27896.0, self.close=27897.4, self.high=27910.0, self.low=27893.9 
2023-04-10 00:25:01,492:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1681057499, self.tradeDate='20230410', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27896.0, self.close=27897.4, self.high=27910.0, self.low=27893.9   
2023-04-10 00:25:01,510:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230410   000000    000459  1681056299  ...  27871.2  0.000219   1440    0
1441  20230410   000500    000959  1681056599  ...  27874.9  0.000025   1441    1
1442  20230410   001000    001459  1681056899  ...  27875.2  0.000628   1442    2
1443  20230410   001500    001959  1681057199  ...  27891.3 -0.000068   1443    3
1444  20230410   002000    002459  1681057499  ...  27893.9  0.000050   1444    4

[5 rows x 11 columns]
2023-04-10 00:25:01,510:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-10 00:00:35,900:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230409    212959  27915.1  ...  47.083333  0.474956  0.560925
5803  20230409    215959  27889.8  ...  47.500000  0.477433  0.561949
5804  20230409    222959  27896.5  ...  47.083333  0.455850  0.576626
5805  20230409    225959  27831.4  ...  47.500000  0.465201  0.585124
5806  20230409    232959  27856.2  ...  47.916667  0.471306  0.589630

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-04-10 00:00:36,071:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510550  0.489450       1  ...  0.901421   1.0    0.0  0.993543
540     0  0.519326  0.480674       0  ...  0.899324   1.0    0.0  0.991231
541     1  0.496073  0.503927       1  ...  0.900118   1.0    0.0  0.992108
542     0  0.513345  0.486655       1  ...  0.900642   1.0    0.0  0.992685
543     0  0.515105  0.484895       1  ...  0.900684   1.0    0.0  0.992731

[5 rows x 10 columns]
2023-04-10 00:00:36,107:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512318  0.487682       1  ...  0.916515   1.0    0.0  0.996610
46     0  0.520617  0.479383       0  ...  0.912652   1.0    0.0  0.992412
47     1  0.496853  0.503147       1  ...  0.913459   1.0    0.0  0.993289
48     0  0.513695  0.486305       1  ...  0.900642   1.0    0.0  0.993838
49     0  0.515105  0.484895       1  ...  0.900684   1.0    0.0  0.992731

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [10/Apr/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-04-10 00:00:04,784:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42138F1681056004216I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1681056004509248, 'quantity': '24.311', 'price': '27871.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1681056003561, 'updatetime': 1681056004509, 'tradetype': 'usdt', 'selfid': 42138, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1681056004509, 'clientorderid': '42138F1681056004216I0L59', 'price': '27871.3', 'quantity': '24.311', 'commission': '677.5791743', 'commissionasset': 'USDT', 'tradetime': 1681056004509, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1681056004509}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19496 

self.closeSec=1681056599, self.tradeDate='20230410', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27873.6', self.close='27880.4'
127.0.0.1 - - [10/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-10 00:10:01,873:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1681056599, self.tradeDate='20230410', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27873.6', self.close='27880.4'
2023-04-10 00:10:01,882:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230409   232000    232959  1681054199  27860.4  27872.3  0.000424
573  20230409   233000    233959  1681054799  27872.3  27858.6 -0.000492
574  20230409   234000    234959  1681055399  27858.6    27890  0.001127
575  20230409   235000    235959  1681055999    27890  27873.6 -0.000588
576  20230410   000000    000959  1681056599  27873.6  27880.4  0.000244
2023-04-10 00:10:01,882:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19497 

self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27880.4', self.close='27896'
127.0.0.1 - - [10/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-10 00:20:07,399:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27880.4', self.close='27896'
2023-04-10 00:20:08,248:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230409   233000    233959  1681054799  27872.3  27858.6 -0.000492
574  20230409   234000    234959  1681055399  27858.6    27890  0.001127
575  20230409   235000    235959  1681055999    27890  27873.6 -0.000588
576  20230410   000000    000959  1681056599  27873.6  27880.4  0.000244
577  20230410   001000    001959  1681057199  27880.4    27896  0.000560
2023-04-10 00:20:08,248:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-04-10 00:00:03,168:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-04-10 00:00:03,256:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:4100000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230409, closeTime:235959, close:27873.6, total:978039.764104, pct_pre:-0.004135064489866003, thd:0.397557969354711, side:sell 
127.0.0.1 - - [10/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19497 

self.closeSec=1681056599, self.tradeDate='20230410', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27873.6', self.close='27880.4'
2023-04-10 00:10:01,887:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1681056599, self.tradeDate='20230410', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27873.6', self.close='27880.4'
2023-04-10 00:10:01,900:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230409   232000    232959  1681054199  27860.4  27872.3
17421  20230409   233000    233959  1681054799  27872.3  27858.6
17422  20230409   234000    234959  1681055399  27858.6    27890
17423  20230409   235000    235959  1681055999    27890  27873.6
17424  20230410   000000    000959  1681056599  27873.6  27880.4
2023-04-10 00:10:01,900:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19498 

self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27880.4', self.close='27896'
127.0.0.1 - - [10/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-10 00:20:10,524:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27880.4', self.close='27896'
2023-04-10 00:20:10,664:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230409   233000    233959  1681054799  27872.3  27858.6
17422  20230409   234000    234959  1681055399  27858.6    27890
17423  20230409   235000    235959  1681055999    27890  27873.6
17424  20230410   000000    000959  1681056599  27873.6  27880.4
17425  20230410   001000    001959  1681057199  27880.4    27896
2023-04-10 00:20:10,664:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [10/Apr/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-04-10 00:00:04,963:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42139F1681056004233I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1681056004525708, 'quantity': '46.31', 'price': '27871.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1681056003601, 'updatetime': 1681056004525, 'tradetype': 'usdt', 'selfid': 42139, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1681056004525, 'clientorderid': '42139F1681056004233I0L2', 'price': '27871.3', 'quantity': '46.31', 'commission': '1290.719903', 'commissionasset': 'USDT', 'tradetime': 1681056004525, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1681056004525}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19497 

self.closeSec=1681056599, self.tradeDate='20230410', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27873.6', self.close='27880.4'
2023-04-10 00:10:01,879:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1681056599, self.tradeDate='20230410', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27873.6', self.close='27880.4'
2023-04-10 00:10:01,898:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230409   232000    232959  1681054199  27860.4  27872.3
12237  20230409   233000    233959  1681054799  27872.3  27858.6
12238  20230409   234000    234959  1681055399  27858.6    27890
12239  20230409   235000    235959  1681055999    27890  27873.6
12240  20230410   000000    000959  1681056599  27873.6  27880.4
2023-04-10 00:10:01,898:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19498 

self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27880.4', self.close='27896'
127.0.0.1 - - [10/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-10 00:20:09,990:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27880.4', self.close='27896'
2023-04-10 00:20:10,315:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230409   233000    233959  1681054799  27872.3  27858.6
12238  20230409   234000    234959  1681055399  27858.6    27890
12239  20230409   235000    235959  1681055999    27890  27873.6
12240  20230410   000000    000959  1681056599  27873.6  27880.4
12241  20230410   001000    001959  1681057199  27880.4    27896
2023-04-10 00:20:10,316:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34426
self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27898.0, self.close=27896.0, self.high=27902.0, self.low=27891.3, self.vol=525.466, self.amt=14658589.5294 
127.0.0.1 - - [10/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-10 00:20:08,238:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230409   235500    235959  ...         0.0        0.0       0
5760  20230410   000000    000459  ...         0.0        0.0       0
5761  20230410   000500    000959  ...         0.0        0.0       0
5762  20230410   001000    001459  ...         0.0        0.0       0
5763  20230410   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 00:20:08,268:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681057199, self.tradeDate='20230410', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27898.0, self.close=27896.0, self.high=27902.0, self.low=27891.3, self.vol=525.466, self.amt=14658589.5294, ukdf['pct'].iloc[-1]=-6.8e-05 , ukdf['amount'].iloc[-1]=14658589.5294, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [10/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34427
self.closeSec=1681057499, self.tradeDate='20230410', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27896.0, self.close=27897.4, self.high=27910.0, self.low=27893.9, self.vol=537.361, self.amt=14994641.268 
2023-04-10 00:25:01,586:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230410   000000    000459  ...         0.0        0.0       0
5761  20230410   000500    000959  ...         0.0        0.0       0
5762  20230410   001000    001459  ...         0.0        0.0       0
5763  20230410   001500    001959  ...         0.0        0.0       0
5764  20230410   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 00:25:01,587:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681057499, self.tradeDate='20230410', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27896.0, self.close=27897.4, self.high=27910.0, self.low=27893.9, self.vol=537.361, self.amt=14994641.268, ukdf['pct'].iloc[-1]=5e-05 , ukdf['amount'].iloc[-1]=14994641.268, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230409   120000    155959  1681027199  ...    723  0.209839 -0.237609     NaN
724  20230409   160000    195959  1681041599  ...    724  0.118720 -0.686927    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '24960.5696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27919.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=812
self.closeSec=1681055999, self.tradeDate='20230409', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27919.3, self.close=27873.6, self.high=27960.0, self.low=27777.0, self.vol=35449.263, self.amt=988065770.8909 
127.0.0.1 - - [10/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-04-10 00:00:02,823:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681055999, self.tradeDate='20230409', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27919.3, self.close=27873.6, self.high=27960.0, self.low=27777.0, self.vol=35449.263, self.amt=988065770.8909 
2023-04-10 00:00:02,884:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230409   040000    075959  ...  19235.488  5.370948e+08  0.000566
722  20230409   080000    115959  ...  30081.552  8.429432e+08  0.003119
723  20230409   120000    155959  ...  47649.419  1.330187e+09 -0.004420
724  20230409   160000    195959  ...  31551.572  8.794584e+08  0.001115
725  20230409   200000    235959  ...  35449.263  9.880658e+08 -0.001637

[5 rows x 11 columns]
2023-04-10 00:00:05,114:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230409   040000    075959  1680998399  ...    721  0.273751  0.094085     NaN
722  20230409   080000    115959  1681012799  ...    722  0.269967  0.063218     NaN
723  20230409   120000    155959  1681027199  ...    723  0.209839 -0.237609     NaN
724  20230409   160000    195959  1681041599  ...    724  0.118720 -0.686927    -1.0
725  20230409   200000    235959  1681055999  ...    725  0.009779 -1.214057    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '27194.5353261252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27876.71170085', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


