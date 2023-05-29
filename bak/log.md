# 20230530 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4480
self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27665.9, self.close=27630.3, self.high=27670.0, self.low=27585.7, self.vol=2250.969, self.amt=62200370.1437 
127.0.0.1 - - [30/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-30 00:20:06,600:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230529   235500    235959  ...         0.0        0.0       0
5760  20230530   000000    000459  ...         0.0        0.0       0
5761  20230530   000500    000959  ...         0.0        0.0       0
5762  20230530   001000    001459  ...         0.0        0.0       0
5763  20230530   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 00:20:06,620:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27665.9, self.close=27630.3, self.high=27670.0, self.low=27585.7, self.vol=2250.969, self.amt=62200370.1437, ukdf['pct'].iloc[-1]=-0.001287 , ukdf['amount'].iloc[-1]=62200370.1437, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-10543.3746', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27622', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4481
self.closeSec=1685377499, self.tradeDate='20230530', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27630.3, self.close=27571.7, self.high=27630.4, self.low=27530.0, self.vol=5235.184, self.amt=144317398.95398 
2023-05-30 00:25:00,815:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230530   000000    000459  ...         0.0        0.0       0
5761  20230530   000500    000959  ...         0.0        0.0       0
5762  20230530   001000    001459  ...         0.0        0.0       0
5763  20230530   001500    001959  ...         0.0        0.0       0
5764  20230530   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 00:25:00,815:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685377499, self.tradeDate='20230530', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27630.3, self.close=27571.7, self.high=27630.4, self.low=27530.0, self.vol=5235.184, self.amt=144317398.95398, ukdf['pct'].iloc[-1]=-0.002121 , ukdf['amount'].iloc[-1]=144317398.95398, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-9785.8002', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27567.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27665.9, self.close=27630.3, self.high=27670.0, self.low=27585.7 
127.0.0.1 - - [30/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-30 00:20:04,260:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27665.9, self.close=27630.3, self.high=27670.0, self.low=27585.7   
2023-05-30 00:20:05,581:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230529   235500    235959  1685375999  ...  27593.1 -0.000658   1727    5
1440  20230530   000000    000459  1685376299  ...  27550.0 -0.000257   1440    0
1441  20230530   000500    000959  1685376599  ...  27563.8  0.001032   1441    1
1442  20230530   001000    001459  1685376899  ...  27625.4  0.000814   1442    2
1443  20230530   001500    001959  1685377199  ...  27585.7 -0.001287   1443    3

[5 rows x 11 columns]
2023-05-30 00:20:05,590:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=147, self.factor=0.30329244936365896, self.count=4483 

self.closeSec=1685377499, self.tradeDate='20230530', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27630.3, self.close=27571.7, self.high=27630.4, self.low=27530.0 
2023-05-30 00:25:00,694:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685377499, self.tradeDate='20230530', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27630.3, self.close=27571.7, self.high=27630.4, self.low=27530.0   
2023-05-30 00:25:00,767:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230530   000000    000459  1685376299  ...  27550.0 -0.000257   1440    0
1441  20230530   000500    000959  1685376599  ...  27563.8  0.001032   1441    1
1442  20230530   001000    001459  1685376899  ...  27625.4  0.000814   1442    2
1443  20230530   001500    001959  1685377199  ...  27585.7 -0.001287   1443    3
1444  20230530   002000    002459  1685377499  ...  27530.0 -0.002121   1444    4

[5 rows x 11 columns]
2023-05-30 00:25:00,768:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-30 00:00:33,499:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230529    212959  27870.9  ...  50.416667  0.608943  0.361389
5803  20230529    215959  27927.5  ...  50.416667  0.599051  0.369427
5804  20230529    222959  27892.8  ...  50.416667  0.594941  0.383248
5805  20230529    225959  27878.3  ...  50.416667  0.568512  0.402715
5806  20230529    232959  27781.9  ...  50.000000  0.532893  0.430571

[5 rows x 33 columns]
0.5220588235294118
acc is : 0.5220588235294118
2023-05-30 00:00:33,656:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.508170  0.491830       0  ...  0.972206  -1.0    0.0  1.018911
540     1  0.488988  0.511012       0  ...  0.972712  -1.0    0.0  1.018382
541     1  0.488222  0.511778       0  ...  0.976072  -1.0    0.0  1.014864
542     1  0.468550  0.531450       0  ...  0.981060  -1.0    0.0  1.009677
543     1  0.455158  0.544842       0  ...  0.981699  -1.0    0.0  1.009019

[5 rows x 10 columns]
2023-05-30 00:00:33,689:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508222  0.491778       0  ...  0.972206  -1.0    0.0  1.026917
46     1  0.488837  0.511163       0  ...  0.972712  -1.0    0.0  1.025069
47     1  0.488249  0.511751       0  ...  0.976072  -1.0    0.0  1.021529
48     1  0.468552  0.531448       0  ...  0.981060  -1.0    0.0  1.015504
49     1  0.455158  0.544842       0  ...  0.981699  -1.0    0.0  1.009019

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '8280.1688116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27614.9716', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [30/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-30 00:00:04,504:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42285F1685376003714I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685376004161655, 'quantity': '24.614', 'price': '27621.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685376002836, 'updatetime': 1685376004161, 'tradetype': 'usdt', 'selfid': 42285, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685376004161, 'clientorderid': '42285F1685376003714I0L59', 'price': '27621.5', 'quantity': '24.614', 'commission': '679.875601', 'commissionasset': 'USDT', 'tradetime': 1685376004161, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685376004161}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2240 

self.closeSec=1685376599, self.tradeDate='20230530', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27622', self.close='27643.4'
127.0.0.1 - - [30/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-30 00:10:01,118:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685376599, self.tradeDate='20230530', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27622', self.close='27643.4'
2023-05-30 00:10:01,143:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230529   232000    232959  1685374199  27780.7    27640 -0.005065
573  20230529   233000    233959  1685374799    27640  27696.3  0.002037
574  20230529   234000    234959  1685375399  27696.3    27640 -0.002033
575  20230529   235000    235959  1685375999    27640  27622.1 -0.000648
576  20230530   000000    000959  1685376599    27622  27643.4  0.000771
2023-05-30 00:10:01,143:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2241 

self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27643.4', self.close='27630.3'
127.0.0.1 - - [30/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-30 00:20:06,450:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27643.4', self.close='27630.3'
2023-05-30 00:20:07,170:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230529   233000    233959  1685374799    27640  27696.3  0.002037
574  20230529   234000    234959  1685375399  27696.3    27640 -0.002033
575  20230529   235000    235959  1685375999    27640  27622.1 -0.000648
576  20230530   000000    000959  1685376599    27622  27643.4  0.000771
577  20230530   001000    001959  1685377199  27643.4  27630.3 -0.000474
2023-05-30 00:20:07,170:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-30 00:00:04,946:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42287F1685376003872I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685376004270448, 'quantity': '35.187', 'price': '27621.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685376002820, 'updatetime': 1685376004270, 'tradetype': 'usdt', 'selfid': 42287, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685376004270, 'clientorderid': '42287F1685376003872I0L57', 'price': '27621.4', 'quantity': '35.187', 'commission': '971.9142018', 'commissionasset': 'USDT', 'tradetime': 1685376004270, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685376004270}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/May/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2243 

self.closeSec=1685376599, self.tradeDate='20230530', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27622', self.close='27643.4'
2023-05-30 00:10:01,129:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685376599, self.tradeDate='20230530', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27622', self.close='27643.4'
127.0.0.1 - - [30/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-30 00:10:01,155:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230529   232000    232959  1685374199  27780.7    27640
17421  20230529   233000    233959  1685374799    27640  27696.3
17422  20230529   234000    234959  1685375399  27696.3    27640
17423  20230529   235000    235959  1685375999    27640  27622.1
17424  20230530   000000    000959  1685376599    27622  27643.4
2023-05-30 00:10:01,158:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2244 

self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27643.4', self.close='27630.3'
127.0.0.1 - - [30/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-30 00:20:08,025:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27643.4', self.close='27630.3'
2023-05-30 00:20:08,121:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230529   233000    233959  1685374799    27640  27696.3
17422  20230529   234000    234959  1685375399  27696.3    27640
17423  20230529   235000    235959  1685375999    27640  27622.1
17424  20230530   000000    000959  1685376599    27622  27643.4
17425  20230530   001000    001959  1685377199  27643.4  27630.3
2023-05-30 00:20:08,122:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [30/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-30 00:00:04,740:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42286F1685376003767I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685376004181591, 'quantity': '44.886', 'price': '27621.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685376002914, 'updatetime': 1685376004181, 'tradetype': 'usdt', 'selfid': 42286, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685376004181, 'clientorderid': '42286F1685376003767I0L2', 'price': '27621.4', 'quantity': '44.886', 'commission': '1239.8141604', 'commissionasset': 'USDT', 'tradetime': 1685376004181, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685376004181}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2243 

self.closeSec=1685376599, self.tradeDate='20230530', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27622', self.close='27643.4'
127.0.0.1 - - [30/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-30 00:10:01,136:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685376599, self.tradeDate='20230530', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27622', self.close='27643.4'
2023-05-30 00:10:01,154:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230529   232000    232959  1685374199  27780.7    27640
12237  20230529   233000    233959  1685374799    27640  27696.3
12238  20230529   234000    234959  1685375399  27696.3    27640
12239  20230529   235000    235959  1685375999    27640  27622.1
12240  20230530   000000    000959  1685376599    27622  27643.4
2023-05-30 00:10:01,154:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2244 

self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27643.4', self.close='27630.3'
127.0.0.1 - - [30/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-30 00:20:07,810:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27643.4', self.close='27630.3'
2023-05-30 00:20:08,010:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230529   233000    233959  1685374799    27640  27696.3
12238  20230529   234000    234959  1685375399  27696.3    27640
12239  20230529   235000    235959  1685375999    27640  27622.1
12240  20230530   000000    000959  1685376599    27622  27643.4
12241  20230530   001000    001959  1685377199  27643.4  27630.3
2023-05-30 00:20:08,011:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4480
self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27665.9, self.close=27630.3, self.high=27670.0, self.low=27585.7, self.vol=2250.969, self.amt=62200370.1437 
127.0.0.1 - - [30/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-30 00:20:06,593:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230529   235500    235959  ...         0.0        0.0       0
5760  20230530   000000    000459  ...         0.0        0.0       0
5761  20230530   000500    000959  ...         0.0        0.0       0
5762  20230530   001000    001459  ...         0.0        0.0       0
5763  20230530   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 00:20:06,611:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685377199, self.tradeDate='20230530', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27665.9, self.close=27630.3, self.high=27670.0, self.low=27585.7, self.vol=2250.969, self.amt=62200370.1437, ukdf['pct'].iloc[-1]=-0.001287 , ukdf['amount'].iloc[-1]=62200370.1437, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '28895.698', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27622', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4481
self.closeSec=1685377499, self.tradeDate='20230530', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27630.3, self.close=27571.7, self.high=27630.4, self.low=27530.0, self.vol=5235.184, self.amt=144317398.95398 
127.0.0.1 - - [30/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-30 00:25:00,822:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230530   000000    000459  ...         0.0        0.0       0
5761  20230530   000500    000959  ...         0.0        0.0       0
5762  20230530   001000    001459  ...         0.0        0.0       0
5763  20230530   001500    001959  ...         0.0        0.0       0
5764  20230530   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 00:25:00,826:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685377499, self.tradeDate='20230530', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27630.3, self.close=27571.7, self.high=27630.4, self.low=27530.0, self.vol=5235.184, self.amt=144317398.95398, ukdf['pct'].iloc[-1]=-0.002121 , ukdf['amount'].iloc[-1]=144317398.95398, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '26875.2276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27567.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230529   120000    155959  1685347199  ...    723  1.148239  3.355206     1.0
724  20230529   160000    195959  1685361599  ...    724  1.095699  2.928957     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '98216.1473', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27905.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=93
self.closeSec=1685375999, self.tradeDate='20230529', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27908.1, self.close=27622.0, self.high=27945.4, self.low=27570.6, self.vol=81223.202, self.amt=2254189587.10122 127.0.0.1 - - [30/May/2023 00:00:01] "POST / HTTP/1.1" 200 -

2023-05-30 00:00:01,849:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685375999, self.tradeDate='20230529', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27908.1, self.close=27622.0, self.high=27945.4, self.low=27570.6, self.vol=81223.202, self.amt=2254189587.10122 
2023-05-30 00:00:01,866:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230529   040000    075959  ...  116480.961  3.257902e+09  0.019525
722  20230529   080000    115959  ...  103587.637  2.920579e+09 -0.003842
723  20230529   120000    155959  ...   60707.279  1.695958e+09 -0.001893
724  20230529   160000    195959  ...   48976.302  1.365145e+09  0.000470
725  20230529   200000    235959  ...   81223.202  2.254190e+09 -0.010252

[5 rows x 11 columns]
2023-05-30 00:00:03,982:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230529   040000    075959  1685318399  ...    721  0.981724  3.044001     1.0
722  20230529   080000    115959  1685332799  ...    722  1.102658  3.402473     1.0
723  20230529   120000    155959  1685347199  ...    723  1.148239  3.355206     1.0
724  20230529   160000    195959  1685361599  ...    724  1.095699  2.928957     1.0
725  20230529   200000    235959  1685375999  ...    725  1.106273  2.811384     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '82503.3317', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27621.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


