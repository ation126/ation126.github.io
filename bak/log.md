# 20230617 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9664
self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25800.9, self.close=25871.1, self.high=25919.8, self.low=25800.9, self.vol=5245.346, self.amt=135645192.8811 
127.0.0.1 - - [17/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-17 00:20:07,144:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230616   235500    235959  ...         0.0        0.0       0
5760  20230617   000000    000459  ...         0.0        0.0       0
5761  20230617   000500    000959  ...         0.0        0.0       0
5762  20230617   001000    001459  ...         0.0        0.0       0
5763  20230617   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 00:20:07,175:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25800.9, self.close=25871.1, self.high=25919.8, self.low=25800.9, self.vol=5245.346, self.amt=135645192.8811, ukdf['pct'].iloc[-1]=0.002756 , ukdf['amount'].iloc[-1]=135645192.8811, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13848.44806998378', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25870.46885897', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9665
self.closeSec=1686932699, self.tradeDate='20230617', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25868.7, self.close=25833.2, self.high=25874.6, self.low=25820.0, self.vol=3772.145, self.amt=97516334.6637 
2023-06-17 00:25:00,845:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230617   000000    000459  ...         0.0        0.0       0
5761  20230617   000500    000959  ...         0.0        0.0       0
5762  20230617   001000    001459  ...         0.0        0.0       0
5763  20230617   001500    001959  ...         0.0        0.0       0
5764  20230617   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 00:25:00,845:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686932699, self.tradeDate='20230617', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25868.7, self.close=25833.2, self.high=25874.6, self.low=25820.0, self.vol=3772.145, self.amt=97516334.6637, ukdf['pct'].iloc[-1]=-0.001465 , ukdf['amount'].iloc[-1]=97516334.6637, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14331.2466', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25835.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25800.9, self.close=25871.1, self.high=25919.8, self.low=25800.9 
127.0.0.1 - - [17/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-17 00:20:04,564:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25800.9, self.close=25871.1, self.high=25919.8, self.low=25800.9   
2023-06-17 00:20:06,025:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230616   235500    235959  1686931199  ...  25600.0  0.008360   1727    5
1440  20230617   000000    000459  1686931499  ...  25766.6 -0.000751   1440    0
1441  20230617   000500    000959  1686931799  ...  25786.0  0.000066   1441    1
1442  20230617   001000    001459  1686932099  ...  25800.0 -0.000221   1442    2
1443  20230617   001500    001959  1686932399  ...  25800.9  0.002756   1443    3

[5 rows x 11 columns]
2023-06-17 00:20:06,045:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=38, self.factor=0.3458692979223405, self.count=9667 

self.closeSec=1686932699, self.tradeDate='20230617', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25868.7, self.close=25833.2, self.high=25874.6, self.low=25820.0 
127.0.0.1 - - [17/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-17 00:25:00,745:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686932699, self.tradeDate='20230617', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25868.7, self.close=25833.2, self.high=25874.6, self.low=25820.0   
2023-06-17 00:25:00,782:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230617   000000    000459  1686931499  ...  25766.6 -0.000751   1440    0
1441  20230617   000500    000959  1686931799  ...  25786.0  0.000066   1441    1
1442  20230617   001000    001459  1686932099  ...  25800.0 -0.000221   1442    2
1443  20230617   001500    001959  1686932399  ...  25800.9  0.002756   1443    3
1444  20230617   002000    002459  1686932699  ...  25820.0 -0.001465   1444    4

[5 rows x 11 columns]
2023-06-17 00:25:00,782:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-17 00:00:18,931:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230616    212959  25555.4  ...  50.416667  0.528612  0.267085
5803  20230616    215959  25597.9  ...  50.416667  0.503242  0.275950
5804  20230616    222959  25482.4  ...  50.416667  0.506649  0.285364
5805  20230616    225959  25498.7  ...  50.416667  0.527813  0.282450
5806  20230616    232959  25602.1  ...  50.416667  0.536633  0.274751

[5 rows x 33 columns]
0.5496323529411765
acc is : 0.5496323529411765
2023-06-17 00:00:19,017:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.514071  0.485929       0  ...  1.027639   1.0    0.0  0.950155
540     1  0.481967  0.518033       1  ...  1.028296   1.0    0.0  0.950763
541     0  0.508723  0.491277       1  ...  1.032507   1.0    0.0  0.954656
542     0  0.529468  0.470532       1  ...  1.034337   1.0    0.0  0.956348
543     0  0.517678  0.482322       1  ...  1.041754   1.0    0.0  0.963205

[5 rows x 10 columns]
2023-06-17 00:00:19,028:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514113  0.485887       0  ...  1.027639   1.0    0.0  0.950715
46     1  0.482223  0.517777       1  ...  1.028296   1.0    0.0  0.952920
47     0  0.508973  0.491027       1  ...  1.032507   1.0    0.0  0.956821
48     0  0.529655  0.470345       1  ...  1.047628   1.0    0.0  0.956391
49     0  0.517678  0.482322       1  ...  1.041754   1.0    0.0  0.963205

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '11366.1207', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25828.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [17/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-17 00:00:04,111:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42399F1686931203487I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686931203886860, 'quantity': '28.407', 'price': '25832.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686931202579, 'updatetime': 1686931203886, 'tradetype': 'usdt', 'selfid': 42399, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686931203886, 'clientorderid': '42399F1686931203487I0L59', 'price': '25832.4', 'quantity': '28.407', 'commission': '733.8209868', 'commissionasset': 'USDT', 'tradetime': 1686931203886, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686931203886}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4832 

self.closeSec=1686931799, self.tradeDate='20230617', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25832.4', self.close='25805.7'
2023-06-17 00:10:01,142:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686931799, self.tradeDate='20230617', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25832.4', self.close='25805.7'
2023-06-17 00:10:01,187:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230616   232000    232959  1686929399  25622.7  25648.5  0.001011
573  20230616   233000    233959  1686929999  25648.4  25588.4 -0.002343
574  20230616   234000    234959  1686930599  25588.4  25563.8 -0.000961
575  20230616   235000    235959  1686931199  25564.5  25832.4  0.010507
576  20230617   000000    000959  1686931799  25832.4  25805.7 -0.001034
2023-06-17 00:10:01,187:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4833 

self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25805.6', self.close='25871.1'
127.0.0.1 - - [17/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-17 00:20:07,254:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25805.6', self.close='25871.1'
2023-06-17 00:20:08,056:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230616   233000    233959  1686929999  25648.4  25588.4 -0.002343
574  20230616   234000    234959  1686930599  25588.4  25563.8 -0.000961
575  20230616   235000    235959  1686931199  25564.5  25832.4  0.010507
576  20230617   000000    000959  1686931799  25832.4  25805.7 -0.001034
577  20230617   001000    001959  1686932399  25805.6  25871.1  0.002534
2023-06-17 00:20:08,056:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-17 00:00:02,090:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-17 00:00:02,203:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6170000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230616, closeTime:235959, close:25832.4, total:980576.7580187, pct_pre:0.024846362784138654, thd:-0.014591562422873683, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4835 

self.closeSec=1686931799, self.tradeDate='20230617', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25832.4', self.close='25805.7'
2023-06-17 00:10:01,156:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686931799, self.tradeDate='20230617', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25832.4', self.close='25805.7'
127.0.0.1 - - [17/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-17 00:10:01,194:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230616   232000    232959  1686929399  25622.7  25648.5
17421  20230616   233000    233959  1686929999  25648.4  25588.4
17422  20230616   234000    234959  1686930599  25588.4  25563.8
17423  20230616   235000    235959  1686931199  25564.5  25832.4
17424  20230617   000000    000959  1686931799  25832.4  25805.7
2023-06-17 00:10:01,194:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4836 

self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25805.6', self.close='25871.1'
127.0.0.1 - - [17/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-17 00:20:09,105:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25805.6', self.close='25871.1'
2023-06-17 00:20:09,236:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230616   233000    233959  1686929999  25648.4  25588.4
17422  20230616   234000    234959  1686930599  25588.4  25563.8
17423  20230616   235000    235959  1686931199  25564.5  25832.4
17424  20230617   000000    000959  1686931799  25832.4  25805.7
17425  20230617   001000    001959  1686932399  25805.6  25871.1
2023-06-17 00:20:09,237:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [17/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-17 00:00:04,285:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42400F1686931203570I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686931203979836, 'quantity': '50.706', 'price': '25832.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686931202587, 'updatetime': 1686931203979, 'tradetype': 'usdt', 'selfid': 42400, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686931203979, 'clientorderid': '42400F1686931203570I0L2', 'price': '25832.4', 'quantity': '50.706', 'commission': '1309.8576744', 'commissionasset': 'USDT', 'tradetime': 1686931203979, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686931203979}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4835 

self.closeSec=1686931799, self.tradeDate='20230617', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25832.4', self.close='25805.7'
2023-06-17 00:10:01,130:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686931799, self.tradeDate='20230617', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25832.4', self.close='25805.7'
2023-06-17 00:10:01,188:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230616   232000    232959  1686929399  25622.7  25648.5
12237  20230616   233000    233959  1686929999  25648.4  25588.4
12238  20230616   234000    234959  1686930599  25588.4  25563.8
12239  20230616   235000    235959  1686931199  25564.5  25832.4
12240  20230617   000000    000959  1686931799  25832.4  25805.7
2023-06-17 00:10:01,190:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4836 

self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25805.6', self.close='25871.1'
127.0.0.1 - - [17/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-17 00:20:08,718:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25805.6', self.close='25871.1'
2023-06-17 00:20:08,986:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230616   233000    233959  1686929999  25648.4  25588.4
12238  20230616   234000    234959  1686930599  25588.4  25563.8
12239  20230616   235000    235959  1686931199  25564.5  25832.4
12240  20230617   000000    000959  1686931799  25832.4  25805.7
12241  20230617   001000    001959  1686932399  25805.6  25871.1
2023-06-17 00:20:08,987:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9664
self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25800.9, self.close=25871.1, self.high=25919.8, self.low=25800.9, self.vol=5245.346, self.amt=135645192.8811 
127.0.0.1 - - [17/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-17 00:20:07,035:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230616   235500    235959  ...         0.0        0.0       0
5760  20230617   000000    000459  ...         0.0        0.0       0
5761  20230617   000500    000959  ...         0.0        0.0       0
5762  20230617   001000    001459  ...         0.0        0.0       0
5763  20230617   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 00:20:07,066:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686932399, self.tradeDate='20230617', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25800.9, self.close=25871.1, self.high=25919.8, self.low=25800.9, self.vol=5245.346, self.amt=135645192.8811, ukdf['pct'].iloc[-1]=0.002756 , ukdf['amount'].iloc[-1]=135645192.8811, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36157.92010899523', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25870.46885897', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9665
self.closeSec=1686932699, self.tradeDate='20230617', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25868.7, self.close=25833.2, self.high=25874.6, self.low=25820.0, self.vol=3772.145, self.amt=97516334.6637 
127.0.0.1 - - [17/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-17 00:25:00,843:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230617   000000    000459  ...         0.0        0.0       0
5761  20230617   000500    000959  ...         0.0        0.0       0
5762  20230617   001000    001459  ...         0.0        0.0       0
5763  20230617   001500    001959  ...         0.0        0.0       0
5764  20230617   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-17 00:25:00,844:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686932699, self.tradeDate='20230617', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25868.7, self.close=25833.2, self.high=25874.6, self.low=25820.0, self.vol=3772.145, self.amt=97516334.6637, ukdf['pct'].iloc[-1]=-0.001465 , ukdf['amount'].iloc[-1]=97516334.6637, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37445.5562', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25835.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230616   120000    155959  1686902399  ...    723  0.444552  0.148233     NaN
724  20230616   160000    195959  1686916799  ...    724  0.452034  0.201527     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '89137.2228', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25462.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [17/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=201
self.closeSec=1686931199, self.tradeDate='20230616', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25462.9, self.close=25832.4, self.high=25896.0, self.low=25142.1, self.vol=151837.917, self.amt=3878342745.78784 
2023-06-17 00:00:01,663:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686931199, self.tradeDate='20230616', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25462.9, self.close=25832.4, self.high=25896.0, self.low=25142.1, self.vol=151837.917, self.amt=3878342745.78784 
2023-06-17 00:00:01,689:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230616   040000    075959  ...  113154.066  2.888633e+09  0.005620
722  20230616   080000    115959  ...   43049.905  1.098014e+09 -0.001579
723  20230616   120000    155959  ...   40458.494  1.033506e+09 -0.000767
724  20230616   160000    195959  ...   43200.142  1.103317e+09 -0.002480
725  20230616   200000    235959  ...  151837.917  3.878343e+09  0.014515

[5 rows x 11 columns]
2023-06-17 00:00:02,942:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230616   040000    075959  1686873599  ...    721  0.448839  0.146325     NaN
722  20230616   080000    115959  1686887999  ...    722  0.444398  0.133506     NaN
723  20230616   120000    155959  1686902399  ...    723  0.444552  0.148233     NaN
724  20230616   160000    195959  1686916799  ...    724  0.452034  0.201527     NaN
725  20230616   200000    235959  1686931199  ...    725  0.386754 -0.095560     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '68742.3526', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25832.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


