# 20230712 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16864
self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30548.1, self.close=30495.9, self.high=30569.6, self.low=30489.7, self.vol=1904.418, self.amt=58121416.3554 
127.0.0.1 - - [12/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-12 00:20:06,318:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230711   235500    235959  ...         0.0        0.0       0
5760  20230712   000000    000459  ...         0.0        0.0       0
5761  20230712   000500    000959  ...         0.0        0.0       0
5762  20230712   001000    001459  ...         0.0        0.0       0
5763  20230712   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 00:20:06,349:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30548.1, self.close=30495.9, self.high=30569.6, self.low=30489.7, self.vol=1904.418, self.amt=58121416.3554, ukdf['pct'].iloc[-1]=-0.001712 , ukdf['amount'].iloc[-1]=58121416.3554, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50632.16286924642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30500.70086667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16865
self.closeSec=1689092699, self.tradeDate='20230712', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30495.9, self.close=30502.3, self.high=30521.0, self.low=30489.7, self.vol=1071.602, self.amt=32686176.7869 
127.0.0.1 - - [12/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-12 00:25:00,833:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230712   000000    000459  ...         0.0        0.0       0
5761  20230712   000500    000959  ...         0.0        0.0       0
5762  20230712   001000    001459  ...         0.0        0.0       0
5763  20230712   001500    001959  ...         0.0        0.0       0
5764  20230712   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 00:25:00,834:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689092699, self.tradeDate='20230712', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30495.9, self.close=30502.3, self.high=30521.0, self.low=30489.7, self.vol=1071.602, self.amt=32686176.7869, ukdf['pct'].iloc[-1]=0.00021 , ukdf['amount'].iloc[-1]=32686176.7869, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50672.3000860626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30503.5830451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30548.1, self.close=30495.9, self.high=30569.6, self.low=30489.7 
127.0.0.1 - - [12/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-12 00:20:04,283:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30548.1, self.close=30495.9, self.high=30569.6, self.low=30489.7   
2023-07-12 00:20:05,558:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230711   235500    235959  1689091199  ...  30556.6  0.000943   1727    5
1440  20230712   000000    000459  1689091499  ...  30571.9 -0.000445   1440    0
1441  20230712   000500    000959  1689091799  ...  30519.3 -0.000854   1441    1
1442  20230712   001000    001459  1689092099  ...  30533.0  0.000079   1442    2
1443  20230712   001500    001959  1689092399  ...  30489.7 -0.001712   1443    3

[5 rows x 11 columns]
2023-07-12 00:20:05,578:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=143, self.factor=0.490599624533712, self.count=16867 

self.closeSec=1689092699, self.tradeDate='20230712', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30495.9, self.close=30502.3, self.high=30521.0, self.low=30489.7 
2023-07-12 00:25:00,745:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689092699, self.tradeDate='20230712', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30495.9, self.close=30502.3, self.high=30521.0, self.low=30489.7   
2023-07-12 00:25:00,762:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230712   000000    000459  1689091499  ...  30571.9 -0.000445   1440    0
1441  20230712   000500    000959  1689091799  ...  30519.3 -0.000854   1441    1
1442  20230712   001000    001459  1689092099  ...  30533.0  0.000079   1442    2
1443  20230712   001500    001959  1689092399  ...  30489.7 -0.001712   1443    3
1444  20230712   002000    002459  1689092699  ...  30489.7  0.000210   1444    4

[5 rows x 11 columns]
2023-07-12 00:25:00,762:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-12 00:00:22,787:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230711    212959  30421.0  ...  47.916667  0.509258  0.584945
5803  20230711    215959  30392.7  ...  48.333333  0.518737  0.588835
5804  20230711    222959  30435.3  ...  48.750000  0.531285  0.588353
5805  20230711    225959  30493.3  ...  48.750000  0.535905  0.586363
5806  20230711    232959  30514.9  ...  48.750000  0.540463  0.582989

[5 rows x 33 columns]
0.5753676470588235
acc is : 0.5753676470588235
2023-07-12 00:00:22,934:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.504891  0.495109       1  ...  0.980579   1.0    0.0  0.989473
540     0  0.521195  0.478805       1  ...  0.982448   1.0    0.0  0.991359
541     0  0.535765  0.464235       1  ...  0.983147   1.0    0.0  0.992064
542     0  0.531463  0.468537       1  ...  0.983836   1.0    0.0  0.992760
543     0  0.528828  0.471172       1  ...  0.985418   1.0    0.0  0.994356

[5 rows x 10 columns]
2023-07-12 00:00:22,968:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505278  0.494722       1  ...  0.981179   1.0    0.0  0.993326
46     0  0.521177  0.478823       1  ...  0.982448   1.0    0.0  0.994462
47     0  0.535579  0.464421       1  ...  0.983147   1.0    0.0  0.995170
48     0  0.531955  0.468045       1  ...  0.984438   1.0    0.0  0.995845
49     0  0.528828  0.471172       1  ...  0.985418   1.0    0.0  0.994356

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.383', 'enterprice': '30486.7', 'countrevence': '0', 'unrealprofit': '2591.9129', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30593', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [12/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-12 00:00:04,397:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42596F1689091203585I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689091203981023, 'quantity': '24.875', 'price': '30589.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689091202703, 'updatetime': 1689091203981, 'tradetype': 'usdt', 'selfid': 42596, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689091203981, 'clientorderid': '42596F1689091203585I0L59', 'price': '30589.2', 'quantity': '24.875', 'commission': '760.90635', 'commissionasset': 'USDT', 'tradetime': 1689091203981, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689091203981}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8432 

self.closeSec=1689091799, self.tradeDate='20230712', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30585.5', self.close='30545.8'
2023-07-12 00:10:01,153:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689091799, self.tradeDate='20230712', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30585.5', self.close='30545.8'
2023-07-12 00:10:01,176:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230711   232000    232959  1689089399    30725  30536.4 -0.006142
573  20230711   233000    233959  1689089999  30536.5  30585.7  0.001614
574  20230711   234000    234959  1689090599  30585.7  30545.5 -0.001314
575  20230711   235000    235959  1689091199  30545.5  30585.5  0.001310
576  20230712   000000    000959  1689091799  30585.5  30545.8 -0.001298
2023-07-12 00:10:01,176:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8433 

self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30545.8', self.close='30495.9'
127.0.0.1 - - [12/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-12 00:20:06,548:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30545.8', self.close='30495.9'
2023-07-12 00:20:07,188:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230711   233000    233959  1689089999  30536.5  30585.7  0.001614
574  20230711   234000    234959  1689090599  30585.7  30545.5 -0.001314
575  20230711   235000    235959  1689091199  30545.5  30585.5  0.001310
576  20230712   000000    000959  1689091799  30585.5  30545.8 -0.001298
577  20230712   001000    001959  1689092399  30545.8  30495.9 -0.001634
2023-07-12 00:20:07,188:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [12/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-12 00:00:04,222:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42595F1689091203534I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689091203951541, 'quantity': '32.652', 'price': '30589.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689091202613, 'updatetime': 1689091203951, 'tradetype': 'usdt', 'selfid': 42595, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689091203951, 'clientorderid': '42595F1689091203534I0L57', 'price': '30589.2', 'quantity': '32.652', 'commission': '998.7985584', 'commissionasset': 'USDT', 'tradetime': 1689091203951, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689091203951}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8435 

self.closeSec=1689091799, self.tradeDate='20230712', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30585.5', self.close='30545.8'
127.0.0.1 - - [12/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-12 00:10:01,144:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689091799, self.tradeDate='20230712', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30585.5', self.close='30545.8'
2023-07-12 00:10:01,153:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230711   232000    232959  1689089399    30725  30536.4
17421  20230711   233000    233959  1689089999  30536.5  30585.7
17422  20230711   234000    234959  1689090599  30585.7  30545.5
17423  20230711   235000    235959  1689091199  30545.5  30585.5
17424  20230712   000000    000959  1689091799  30585.5  30545.8
2023-07-12 00:10:01,153:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8436 

self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30545.8', self.close='30495.9'
127.0.0.1 - - [12/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-12 00:20:07,842:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30545.8', self.close='30495.9'
2023-07-12 00:20:08,050:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230711   233000    233959  1689089999  30536.5  30585.7
17422  20230711   234000    234959  1689090599  30585.7  30545.5
17423  20230711   235000    235959  1689091199  30545.5  30585.5
17424  20230712   000000    000959  1689091799  30585.5  30545.8
17425  20230712   001000    001959  1689092399  30545.8  30495.9
2023-07-12 00:20:08,050:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [12/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-12 00:00:04,586:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42597F1689091203690I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689091204087509, 'quantity': '37.158', 'price': '30589.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689091202755, 'updatetime': 1689091204087, 'tradetype': 'usdt', 'selfid': 42597, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689091204087, 'clientorderid': '42597F1689091203690I0L2', 'price': '30589.5', 'quantity': '37.158', 'commission': '1136.644641', 'commissionasset': 'USDT', 'tradetime': 1689091204087, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689091204087}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8435 

self.closeSec=1689091799, self.tradeDate='20230712', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30585.5', self.close='30545.8'
2023-07-12 00:10:01,155:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689091799, self.tradeDate='20230712', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30585.5', self.close='30545.8'
2023-07-12 00:10:01,180:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230711   232000    232959  1689089399    30725  30536.4
12237  20230711   233000    233959  1689089999  30536.5  30585.7
12238  20230711   234000    234959  1689090599  30585.7  30545.5
12239  20230711   235000    235959  1689091199  30545.5  30585.5
12240  20230712   000000    000959  1689091799  30585.5  30545.8
2023-07-12 00:10:01,180:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8436 

self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30545.8', self.close='30495.9'
127.0.0.1 - - [12/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-12 00:20:07,682:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30545.8', self.close='30495.9'
2023-07-12 00:20:07,939:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230711   233000    233959  1689089999  30536.5  30585.7
12238  20230711   234000    234959  1689090599  30585.7  30545.5
12239  20230711   235000    235959  1689091199  30545.5  30585.5
12240  20230712   000000    000959  1689091799  30585.5  30545.8
12241  20230712   001000    001959  1689092399  30545.8  30495.9
2023-07-12 00:20:07,940:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16864
self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30548.1, self.close=30495.9, self.high=30569.6, self.low=30489.7, self.vol=1904.418, self.amt=58121416.3554 
127.0.0.1 - - [12/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-12 00:20:06,308:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230711   235500    235959  ...         0.0        0.0       0
5760  20230712   000000    000459  ...         0.0        0.0       0
5761  20230712   000500    000959  ...         0.0        0.0       0
5762  20230712   001000    001459  ...         0.0        0.0       0
5763  20230712   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 00:20:06,330:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689092399, self.tradeDate='20230712', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30548.1, self.close=30495.9, self.high=30569.6, self.low=30489.7, self.vol=1904.418, self.amt=58121416.3554, ukdf['pct'].iloc[-1]=-0.001712 , ukdf['amount'].iloc[-1]=58121416.3554, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '135813.52688899047', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30500.70086667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16865
self.closeSec=1689092699, self.tradeDate='20230712', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30495.9, self.close=30502.3, self.high=30521.0, self.low=30489.7, self.vol=1071.602, self.amt=32686176.7869 
127.0.0.1 - - [12/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-12 00:25:00,836:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230712   000000    000459  ...         0.0        0.0       0
5761  20230712   000500    000959  ...         0.0        0.0       0
5762  20230712   001000    001459  ...         0.0        0.0       0
5763  20230712   001500    001959  ...         0.0        0.0       0
5764  20230712   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 00:25:00,836:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689092699, self.tradeDate='20230712', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30495.9, self.close=30502.3, self.high=30521.0, self.low=30489.7, self.vol=1071.602, self.amt=32686176.7869, ukdf['pct'].iloc[-1]=0.00021 , ukdf['amount'].iloc[-1]=32686176.7869, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '135920.5738780591', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30503.5830451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230711   120000    155959  1689062399  ...    723  0.112018 -0.687766    -1.0
724  20230711   160000    195959  1689076799  ...    724  0.144841 -0.538874     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-4678.1447748863', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30391.74190842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1604933.5124475, self.flagDict['side']='sell', self.tradeCount=10, self.count=351
self.closeSec=1689091199, self.tradeDate='20230711', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30391.4, self.close=30585.5, self.high=30804.9, self.low=30261.4, self.vol=98194.832, self.amt=2997190036.6765 
127.0.0.1 - - [12/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-12 00:00:01,685:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689091199, self.tradeDate='20230711', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30391.4, self.close=30585.5, self.high=30804.9, self.low=30261.4, self.vol=98194.832, self.amt=2997190036.6765 
2023-07-12 00:00:01,707:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230711   040000    075959  ...  157092.883  4.807923e+09 -0.013875
722  20230711   080000    115959  ...   45182.060  1.376224e+09  0.002112
723  20230711   120000    155959  ...   37038.603  1.130975e+09  0.002216
724  20230711   160000    195959  ...   38953.602  1.185001e+09 -0.004494
725  20230711   200000    235959  ...   98194.832  2.997190e+09  0.006390

[5 rows x 11 columns]
2023-07-12 00:00:03,471:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230711   040000    075959  1689033599  ...    721  0.028964 -1.074251    -1.0
722  20230711   080000    115959  1689047999  ...    722  0.067099 -0.893681    -1.0
723  20230711   120000    155959  1689062399  ...    723  0.112018 -0.687766    -1.0
724  20230711   160000    195959  1689076799  ...    724  0.144841 -0.538874     NaN
725  20230711   200000    235959  1689091199  ...    725  0.168446 -0.433802     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-15130.481', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30588.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


