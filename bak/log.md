# 20230718 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18592
self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30224.4, self.close=30189.1, self.high=30224.4, self.low=30180.4, self.vol=715.282, self.amt=21601011.1794 
127.0.0.1 - - [18/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-18 00:20:05,864:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230717   235500    235959  ...         0.0        0.0       0
5760  20230718   000000    000459  ...         0.0        0.0       0
5761  20230718   000500    000959  ...         0.0        0.0       0
5762  20230718   001000    001459  ...         0.0        0.0       0
5763  20230718   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 00:20:05,883:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30224.4, self.close=30189.1, self.high=30224.4, self.low=30180.4, self.vol=715.282, self.amt=21601011.1794, ukdf['pct'].iloc[-1]=-0.001019 , ukdf['amount'].iloc[-1]=21601011.1794, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-46247.58035767122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30185.85220147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18593
self.closeSec=1689611099, self.tradeDate='20230718', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30189.2, self.close=30199.7, self.high=30209.8, self.low=30183.2, self.vol=611.397, self.amt=18461838.7751 
127.0.0.1 - - [18/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-18 00:25:00,759:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230718   000000    000459  ...         0.0        0.0       0
5761  20230718   000500    000959  ...         0.0        0.0       0
5762  20230718   001000    001459  ...         0.0        0.0       0
5763  20230718   001500    001959  ...         0.0        0.0       0
5764  20230718   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 00:25:00,760:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689611099, self.tradeDate='20230718', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30189.2, self.close=30199.7, self.high=30209.8, self.low=30183.2, self.vol=611.397, self.amt=18461838.7751, ukdf['pct'].iloc[-1]=0.000351 , ukdf['amount'].iloc[-1]=18461838.7751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-46440.4248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30199.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30224.4, self.close=30189.1, self.high=30224.4, self.low=30180.4 
127.0.0.1 - - [18/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-18 00:20:03,864:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30224.4, self.close=30189.1, self.high=30224.4, self.low=30180.4   
2023-07-18 00:20:05,075:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230717   235500    235959  1689609599  ...  30143.5  0.000511   1727    5
1440  20230718   000000    000459  1689609899  ...  30133.4 -0.000862   1440    0
1441  20230718   000500    000959  1689610199  ...  30137.9  0.002273   1441    1
1442  20230718   001000    001459  1689610499  ...  30199.9  0.000460   1442    2
1443  20230718   001500    001959  1689610799  ...  30180.4 -0.001019   1443    3

[5 rows x 11 columns]
2023-07-18 00:20:05,093:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.5051577427923423, self.count=18595 

self.closeSec=1689611099, self.tradeDate='20230718', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30189.2, self.close=30199.7, self.high=30209.8, self.low=30183.2 
2023-07-18 00:25:00,735:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689611099, self.tradeDate='20230718', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30189.2, self.close=30199.7, self.high=30209.8, self.low=30183.2   
2023-07-18 00:25:00,761:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230718   000000    000459  1689609899  ...  30133.4 -0.000862   1440    0
1441  20230718   000500    000959  1689610199  ...  30137.9  0.002273   1441    1
1442  20230718   001000    001459  1689610499  ...  30199.9  0.000460   1442    2
1443  20230718   001500    001959  1689610799  ...  30180.4 -0.001019   1443    3
1444  20230718   002000    002459  1689611099  ...  30183.2  0.000351   1444    4

[5 rows x 11 columns]
2023-07-18 00:25:00,762:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-18 00:00:19,193:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230717    212959  30196.9  ...  52.500000  0.478154  0.510084
5803  20230717    215959  30232.0  ...  52.500000  0.491899  0.490745
5804  20230717    222959  30276.0  ...  52.083333  0.482534  0.474013
5805  20230717    225959  30244.2  ...  52.083333  0.488428  0.455545
5806  20230717    232959  30262.9  ...  52.083333  0.457302  0.455006

[5 rows x 33 columns]
0.5202205882352942
acc is : 0.5202205882352942
2023-07-18 00:00:19,253:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.526936  0.473064       1  ...  0.991153   1.0    0.0  0.983230
540     0  0.528971  0.471029       0  ...  0.990115   1.0    0.0  0.982200
541     0  0.507654  0.492346       1  ...  0.990730   1.0    0.0  0.982811
542     0  0.531016  0.468984       0  ...  0.987126   1.0    0.0  0.979235
543     1  0.473471  0.526529       1  ...  0.987470   1.0    0.0  0.979576

[5 rows x 10 columns]
2023-07-18 00:00:19,265:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.528320  0.471680       1  ...  1.009476   1.0    0.0  0.989531
46     0  0.529988  0.470012       0  ...  1.008419   1.0    0.0  0.985799
47     0  0.508644  0.491356       1  ...  1.009045   1.0    0.0  0.986411
48     0  0.531579  0.468421       0  ...  1.005374   1.0    0.0  0.980362
49     1  0.473471  0.526529       1  ...  0.987470   1.0    0.0  0.979576

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.219', 'enterprice': '30360.8', 'countrevence': '0', 'unrealprofit': '-4531.3749', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30173.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [18/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-18 00:00:04,202:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42669F1689609603531I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689609603925758, 'quantity': '24.384', 'price': '30163.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689609602673, 'updatetime': 1689609603925, 'tradetype': 'usdt', 'selfid': 42669, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689609603925, 'clientorderid': '42669F1689609603531I0L59', 'price': '30163.5', 'quantity': '24.384', 'commission': '735.506784', 'commissionasset': 'USDT', 'tradetime': 1689609603925, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689609603925}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9296 

self.closeSec=1689610199, self.tradeDate='20230718', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30163.4', self.close='30201.9'
2023-07-18 00:10:01,126:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689610199, self.tradeDate='20230718', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30163.4', self.close='30201.9'
2023-07-18 00:10:01,138:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230717   232000    232959  1689607799    30200  30152.9 -0.001563
573  20230717   233000    233959  1689608399    30153    30157  0.000136
574  20230717   234000    234959  1689608999  30157.1  30140.2 -0.000557
575  20230717   235000    235959  1689609599  30140.2  30163.4  0.000770
576  20230718   000000    000959  1689610199  30163.4  30201.9  0.001276
2023-07-18 00:10:01,138:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9297 

self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30202', self.close='30189.1'
127.0.0.1 - - [18/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-18 00:20:06,584:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30202', self.close='30189.1'
2023-07-18 00:20:07,134:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230717   233000    233959  1689608399    30153    30157  0.000136
574  20230717   234000    234959  1689608999  30157.1  30140.2 -0.000557
575  20230717   235000    235959  1689609599  30140.2  30163.4  0.000770
576  20230718   000000    000959  1689610199  30163.4  30201.9  0.001276
577  20230718   001000    001959  1689610799    30202  30189.1 -0.000424
2023-07-18 00:20:07,135:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-18 00:00:02,145:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-18 00:00:02,194:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7180000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230717, closeTime:235959, close:30163.4, total:1011809.3588385, pct_pre:-0.006331574196693945, thd:0.2169023180367733, side:sell 
127.0.0.1 - - [18/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9299 

self.closeSec=1689610199, self.tradeDate='20230718', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30163.4', self.close='30201.9'
2023-07-18 00:10:01,133:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689610199, self.tradeDate='20230718', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30163.4', self.close='30201.9'
2023-07-18 00:10:01,149:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230717   232000    232959  1689607799    30200  30152.9
17421  20230717   233000    233959  1689608399    30153    30157
17422  20230717   234000    234959  1689608999  30157.1  30140.2
17423  20230717   235000    235959  1689609599  30140.2  30163.4
17424  20230718   000000    000959  1689610199  30163.4  30201.9
2023-07-18 00:10:01,149:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9300 

self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30202', self.close='30189.1'
127.0.0.1 - - [18/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-18 00:20:07,776:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30202', self.close='30189.1'
2023-07-18 00:20:07,990:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230717   233000    233959  1689608399    30153    30157
17422  20230717   234000    234959  1689608999  30157.1  30140.2
17423  20230717   235000    235959  1689609599  30140.2  30163.4
17424  20230718   000000    000959  1689610199  30163.4  30201.9
17425  20230718   001000    001959  1689610799    30202  30189.1
2023-07-18 00:20:07,991:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [18/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-18 00:00:04,063:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42668F1689609603493I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689609603870523, 'quantity': '37.368', 'price': '30163.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689609602688, 'updatetime': 1689609603870, 'tradetype': 'usdt', 'selfid': 42668, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689609603870, 'clientorderid': '42668F1689609603493I0L2', 'price': '30163.4', 'quantity': '37.368', 'commission': '1127.1459312', 'commissionasset': 'USDT', 'tradetime': 1689609603870, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689609603870}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9299 

self.closeSec=1689610199, self.tradeDate='20230718', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30163.4', self.close='30201.9'
127.0.0.1 - - [18/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-18 00:10:01,129:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689610199, self.tradeDate='20230718', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30163.4', self.close='30201.9'
2023-07-18 00:10:01,140:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230717   232000    232959  1689607799    30200  30152.9
12237  20230717   233000    233959  1689608399    30153    30157
12238  20230717   234000    234959  1689608999  30157.1  30140.2
12239  20230717   235000    235959  1689609599  30140.2  30163.4
12240  20230718   000000    000959  1689610199  30163.4  30201.9
2023-07-18 00:10:01,140:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9300 

self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30202', self.close='30189.1'
127.0.0.1 - - [18/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-18 00:20:07,616:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30202', self.close='30189.1'
2023-07-18 00:20:07,879:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230717   233000    233959  1689608399    30153    30157
12238  20230717   234000    234959  1689608999  30157.1  30140.2
12239  20230717   235000    235959  1689609599  30140.2  30163.4
12240  20230718   000000    000959  1689610199  30163.4  30201.9
12241  20230718   001000    001959  1689610799    30202  30189.1
2023-07-18 00:20:07,882:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18592
self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30224.4, self.close=30189.1, self.high=30224.4, self.low=30180.4, self.vol=715.282, self.amt=21601011.1794 
127.0.0.1 - - [18/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-18 00:20:05,733:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230717   235500    235959  ...         0.0        0.0       0
5760  20230718   000000    000459  ...         0.0        0.0       0
5761  20230718   000500    000959  ...         0.0        0.0       0
5762  20230718   001000    001459  ...         0.0        0.0       0
5763  20230718   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 00:20:05,753:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689610799, self.tradeDate='20230718', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30224.4, self.close=30189.1, self.high=30224.4, self.low=30180.4, self.vol=715.282, self.amt=21601011.1794, ukdf['pct'].iloc[-1]=-0.001019 , ukdf['amount'].iloc[-1]=21601011.1794, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '124119.73261479727', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30185.85220147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18593
self.closeSec=1689611099, self.tradeDate='20230718', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30189.2, self.close=30199.7, self.high=30209.8, self.low=30183.2, self.vol=611.397, self.amt=18461838.7751 
2023-07-18 00:25:00,767:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230718   000000    000459  ...         0.0        0.0       0
5761  20230718   000500    000959  ...         0.0        0.0       0
5762  20230718   001000    001459  ...         0.0        0.0       0
5763  20230718   001500    001959  ...         0.0        0.0       0
5764  20230718   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 00:25:00,767:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689611099, self.tradeDate='20230718', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30189.2, self.close=30199.7, self.high=30209.8, self.low=30183.2, self.vol=611.397, self.amt=18461838.7751, ukdf['pct'].iloc[-1]=0.000351 , ukdf['amount'].iloc[-1]=18461838.7751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '124634.0537', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30199.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230717   120000    155959  1689580799  ...    723  0.755479  1.365454     1.0
724  20230717   160000    195959  1689595199  ...    724  0.734620  1.260333     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-19401.5918132302', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30139.7136978', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=387
self.closeSec=1689609599, self.tradeDate='20230717', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30145.0, self.close=30163.4, self.high=30300.0, self.low=30015.9, self.vol=66486.808, self.amt=2006393696.0132 
127.0.0.1 - - [18/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-18 00:00:01,760:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689609599, self.tradeDate='20230717', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30145.0, self.close=30163.4, self.high=30300.0, self.low=30015.9, self.vol=66486.808, self.amt=2006393696.0132 
2023-07-18 00:00:01,779:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230717   040000    075959  ...  25379.658  7.674281e+08 -0.000751
722  20230717   080000    115959  ...  22700.198  6.866654e+08  0.002618
723  20230717   120000    155959  ...  13248.606  4.010111e+08 -0.001013
724  20230717   160000    195959  ...  67733.832  2.041188e+09 -0.003972
725  20230717   200000    235959  ...  66486.808  2.006394e+09  0.000610

[5 rows x 11 columns]
2023-07-18 00:00:02,584:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230717   040000    075959  1689551999  ...    721  0.741507  1.372828     1.0
722  20230717   080000    115959  1689566399  ...    722  0.748426  1.368622     1.0
723  20230717   120000    155959  1689580799  ...    723  0.755479  1.365454     1.0
724  20230717   160000    195959  1689595199  ...    724  0.734620  1.260333     1.0
725  20230717   200000    235959  1689609599  ...    725  0.746221  1.277956     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-18164.1957', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30163.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


