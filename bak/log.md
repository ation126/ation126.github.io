# 20230311 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29788
self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=19953.5, self.close=19962.1, self.high=19971.8, self.low=19917.0, self.vol=3487.618, self.amt=69537754.4785 
127.0.0.1 - - [11/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-11 00:20:04,992:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230310   235500    235959  ...         0.0        0.0       0
5760  20230311   000000    000459  ...         0.0        0.0       0
5761  20230311   000500    000959  ...         0.0        0.0       0
5762  20230311   001000    001459  ...         0.0        0.0       0
5763  20230311   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 00:20:05,005:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=19953.5, self.close=19962.1, self.high=19971.8, self.low=19917.0, self.vol=3487.618, self.amt=69537754.4785, ukdf['pct'].iloc[-1]=0.000436 , ukdf['amount'].iloc[-1]=69537754.4785, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-206596.2432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19962.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29789
self.closeSec=1678465499, self.tradeDate='20230311', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=19962.1, self.close=20036.9, self.high=20094.0, self.low=19959.9, self.vol=7629.341, self.amt=152931420.1567 
2023-03-11 00:25:01,597:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230311   000000    000459  ...         0.0        0.0       0
5761  20230311   000500    000959  ...         0.0        0.0       0
5762  20230311   001000    001459  ...         0.0        0.0       0
5763  20230311   001500    001959  ...         0.0        0.0       0
5764  20230311   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 00:25:01,598:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678465499, self.tradeDate='20230311', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=19962.1, self.close=20036.9, self.high=20094.0, self.low=19959.9, self.vol=7629.341, self.amt=152931420.1567, ukdf['pct'].iloc[-1]=0.003747 , ukdf['amount'].iloc[-1]=152931420.1567, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-211277.72683484336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20040.29652411', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=19953.5, self.close=19962.1, self.high=19971.8, self.low=19917.0 
127.0.0.1 - - [11/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-11 00:20:03,813:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=19953.5, self.close=19962.1, self.high=19971.8, self.low=19917.0   
2023-03-11 00:20:04,322:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230310   235500    235959  1678463999  ...  19976.2  0.000831   1727    5
1440  20230311   000000    000459  1678464299  ...  19960.4 -0.000995   1440    0
1441  20230311   000500    000959  1678464599  ...  19960.0  0.000516   1441    1
1442  20230311   001000    001459  1678464899  ...  19951.9 -0.001601   1442    2
1443  20230311   001500    001959  1678465199  ...  19917.0  0.000436   1443    3

[5 rows x 11 columns]
2023-03-11 00:20:04,323:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [11/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8484936026685285, self.count=30355 

self.closeSec=1678465499, self.tradeDate='20230311', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=19962.1, self.close=20036.9, self.high=20094.0, self.low=19959.9 
2023-03-11 00:25:01,529:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678465499, self.tradeDate='20230311', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=19962.1, self.close=20036.9, self.high=20094.0, self.low=19959.9   
2023-03-11 00:25:01,578:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230311   000000    000459  1678464299  ...  19960.4 -0.000995   1440    0
1441  20230311   000500    000959  1678464599  ...  19960.0  0.000516   1441    1
1442  20230311   001000    001459  1678464899  ...  19951.9 -0.001601   1442    2
1443  20230311   001500    001959  1678465199  ...  19917.0  0.000436   1443    3
1444  20230311   002000    002459  1678465499  ...  19959.9  0.003747   1444    4

[5 rows x 11 columns]
2023-03-11 00:25:01,578:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-11 00:00:35,327:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230310    212959  19920.6  ...  42.916667  0.346073  0.883440
5803  20230310    215959  19924.5  ...  42.916667  0.392499  0.869223
5804  20230310    222959  20173.0  ...  42.916667  0.375523  0.859405
5805  20230310    225959  20019.9  ...  42.916667  0.353156  0.856008
5806  20230310    232959  19806.7  ...  42.916667  0.360928  0.849844

[5 rows x 33 columns]
0.5496323529411765
acc is : 0.5496323529411765
2023-03-11 00:00:35,487:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.597823  0.402177       1  ...  0.926094   1.0  0.0000  0.861502
540     0  0.725650  0.274350       0  ...  0.919266   1.0  0.0000  0.855150
541     0  0.511704  0.488296       0  ...  0.909467   1.0  0.0000  0.846035
542     1  0.426694  0.573306       1  ...  0.906051  -1.0 -0.0016  0.847858
543     0  0.546006  0.453994       1  ...  0.899401  -1.0  0.0000  0.854082

[5 rows x 10 columns]
2023-03-11 00:00:35,522:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.597433  0.402567       1  ...  0.926094   1.0  0.0000  0.862862
46     0  0.725422  0.274578       0  ...  0.919266   1.0  0.0000  0.855808
47     0  0.511647  0.488353       0  ...  0.909467   1.0  0.0000  0.846686
48     1  0.426851  0.573149       1  ...  0.906051  -1.0 -0.0016  0.846712
49     0  0.546006  0.453994       1  ...  0.899401  -1.0  0.0000  0.854082

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.174', 'enterprice': '19859.3', 'countrevence': '0', 'unrealprofit': '-4235.11057691624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19983.22785676', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-11 00:00:03,319:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41943F1678464002906I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678464003019054, 'quantity': '50.717', 'price': '19993.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678464002546, 'updatetime': 1678464003019, 'tradetype': 'usdt', 'selfid': 41943, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678464003019, 'clientorderid': '41943F1678464002906I0L59', 'price': '19993.5', 'quantity': '50.717', 'commission': '1014.0103395', 'commissionasset': 'USDT', 'tradetime': 1678464003019, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678464003019}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15176 

self.closeSec=1678464599, self.tradeDate='20230311', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='19995', self.close='19985.4'
2023-03-11 00:10:01,826:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678464599, self.tradeDate='20230311', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='19995', self.close='19985.4'
2023-03-11 00:10:01,865:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230310   232000    232959  1678462199  19820.9  19849.3  0.001428
573  20230310   233000    233959  1678462799    19850  19920.3  0.003577
574  20230310   234000    234959  1678463399  19922.2    19907 -0.000668
575  20230310   235000    235959  1678463999  19907.1    19995  0.004421
576  20230311   000000    000959  1678464599    19995  19985.4 -0.000480
2023-03-11 00:10:01,873:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15177 

self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='19985.4', self.close='19962.1'
127.0.0.1 - - [11/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-11 00:20:03,933:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='19985.4', self.close='19962.1'
2023-03-11 00:20:04,413:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230310   233000    233959  1678462799    19850  19920.3  0.003577
574  20230310   234000    234959  1678463399  19922.2    19907 -0.000668
575  20230310   235000    235959  1678463999  19907.1    19995  0.004421
576  20230311   000000    000959  1678464599    19995  19985.4 -0.000480
577  20230311   001000    001959  1678465199  19985.4  19962.1 -0.001166
2023-03-11 00:20:04,413:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-11 00:00:02,254:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-11 00:00:02,451:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3110000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230310, closeTime:235959, close:19995, total:984062.1980325, pct_pre:-0.08199944485566246, thd:-1.3106555116570389, side:sell 
127.0.0.1 - - [11/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15177 

self.closeSec=1678464599, self.tradeDate='20230311', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='19995', self.close='19985.4'
2023-03-11 00:10:01,809:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678464599, self.tradeDate='20230311', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='19995', self.close='19985.4'
2023-03-11 00:10:01,884:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230310   232000    232959  1678462199  19820.9  19849.3
17421  20230310   233000    233959  1678462799    19850  19920.3
17422  20230310   234000    234959  1678463399  19922.2    19907
17423  20230310   235000    235959  1678463999  19907.1    19995
17424  20230311   000000    000959  1678464599    19995  19985.4
2023-03-11 00:10:01,884:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15178 

self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='19985.4', self.close='19962.1'
127.0.0.1 - - [11/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-11 00:20:05,925:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='19985.4', self.close='19962.1'
2023-03-11 00:20:06,063:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230310   233000    233959  1678462799    19850  19920.3
17422  20230310   234000    234959  1678463399  19922.2    19907
17423  20230310   235000    235959  1678463999  19907.1    19995
17424  20230311   000000    000959  1678464599    19995  19985.4
17425  20230311   001000    001959  1678465199  19985.4  19962.1
2023-03-11 00:20:06,064:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [11/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-11 00:00:03,657:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41942F1678464002894I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678464003035962, 'quantity': '56.928', 'price': '19993.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678464002497, 'updatetime': 1678464003035, 'tradetype': 'usdt', 'selfid': 41942, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678464003035, 'clientorderid': '41942F1678464002894I0L2', 'price': '19993.4', 'quantity': '56.928', 'commission': '1138.1842752', 'commissionasset': 'USDT', 'tradetime': 1678464003035, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678464003035}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15177 

self.closeSec=1678464599, self.tradeDate='20230311', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='19995', self.close='19985.4'
2023-03-11 00:10:01,843:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678464599, self.tradeDate='20230311', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='19995', self.close='19985.4'
2023-03-11 00:10:01,881:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230310   232000    232959  1678462199  19820.9  19849.3
12237  20230310   233000    233959  1678462799    19850  19920.3
12238  20230310   234000    234959  1678463399  19922.2    19907
12239  20230310   235000    235959  1678463999  19907.1    19995
12240  20230311   000000    000959  1678464599    19995  19985.4
2023-03-11 00:10:01,881:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15178 

self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='19985.4', self.close='19962.1'
127.0.0.1 - - [11/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-11 00:20:05,263:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='19985.4', self.close='19962.1'
2023-03-11 00:20:05,626:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230310   233000    233959  1678462799    19850  19920.3
12238  20230310   234000    234959  1678463399  19922.2    19907
12239  20230310   235000    235959  1678463999  19907.1    19995
12240  20230311   000000    000959  1678464599    19995  19985.4
12241  20230311   001000    001959  1678465199  19985.4  19962.1
2023-03-11 00:20:05,627:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25786
self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=19953.5, self.close=19962.1, self.high=19971.8, self.low=19917.0, self.vol=3487.618, self.amt=69537754.4785 
127.0.0.1 - - [11/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-11 00:20:01,836:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230310   235500    235959  ...         0.0        0.0       0
5760  20230311   000000    000459  ...         0.0        0.0       0
5761  20230311   000500    000959  ...         0.0        0.0       0
5762  20230311   001000    001459  ...         0.0        0.0       0
5763  20230311   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 00:20:01,837:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678465199, self.tradeDate='20230311', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=19953.5, self.close=19962.1, self.high=19971.8, self.low=19917.0, self.vol=3487.618, self.amt=69537754.4785, ukdf['pct'].iloc[-1]=0.000436 , ukdf['amount'].iloc[-1]=69537754.4785, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [11/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25787
self.closeSec=1678465499, self.tradeDate='20230311', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=19962.1, self.close=20036.9, self.high=20094.0, self.low=19959.9, self.vol=7629.341, self.amt=152931420.1567 
2023-03-11 00:25:01,585:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230311   000000    000459  ...         0.0        0.0       0
5761  20230311   000500    000959  ...         0.0        0.0       0
5762  20230311   001000    001459  ...         0.0        0.0       0
5763  20230311   001500    001959  ...         0.0        0.0       0
5764  20230311   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 00:25:01,597:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678465499, self.tradeDate='20230311', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=19962.1, self.close=20036.9, self.high=20094.0, self.low=19959.9, self.vol=7629.341, self.amt=152931420.1567, ukdf['pct'].iloc[-1]=0.003747 , ukdf['amount'].iloc[-1]=152931420.1567, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230310   120000    155959  1678435199  ...    723  0.617270  0.229363     NaN
724  20230310   160000    195959  1678449599  ...    724  0.676288  0.426810     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '151112.964', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19763.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=632
self.closeSec=1678463999, self.tradeDate='20230310', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=19749.9, self.close=19995.0, self.high=20293.0, self.low=19650.0, self.vol=377610.37, self.amt=7536281551.49717 
127.0.0.1 - - [11/Mar/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-03-11 00:00:02,081:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678463999, self.tradeDate='20230310', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=19749.9, self.close=19995.0, self.high=20293.0, self.low=19650.0, self.vol=377610.37, self.amt=7536281551.49717 
2023-03-11 00:00:02,111:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230310   040000    075959  ...  336530.824  6.868830e+09 -0.023852
722  20230310   080000    115959  ...  228402.264  4.576687e+09 -0.015048
723  20230310   120000    155959  ...  144189.872  2.872943e+09 -0.004950
724  20230310   160000    195959  ...  189712.340  3.747278e+09 -0.009673
725  20230310   200000    235959  ...  377610.370  7.536282e+09  0.012405

[5 rows x 11 columns]
2023-03-11 00:00:04,901:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230310   040000    075959  1678406399  ...    721  0.418595 -0.460593     NaN
722  20230310   080000    115959  1678420799  ...    722  0.518297 -0.112976     NaN
723  20230310   120000    155959  1678435199  ...    723  0.617270  0.229363     NaN
724  20230310   160000    195959  1678449599  ...    724  0.676288  0.426810     NaN
725  20230310   200000    235959  1678463999  ...    725  0.685910  0.452372     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '141438.768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19993.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


