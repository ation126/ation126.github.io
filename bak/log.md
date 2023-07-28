# 20230729 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21760
self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29331.7, self.close=29363.1, self.high=29363.9, self.low=29322.7, self.vol=1366.808, self.amt=40112412.1816 
127.0.0.1 - - [29/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-29 00:20:04,862:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230728   235500    235959  ...         0.0        0.0       0
5760  20230729   000000    000459  ...         0.0        0.0       0
5761  20230729   000500    000959  ...         0.0        0.0       0
5762  20230729   001000    001459  ...         0.0        0.0       0
5763  20230729   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 00:20:04,891:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29331.7, self.close=29363.1, self.high=29363.9, self.low=29322.7, self.vol=1366.808, self.amt=40112412.1816, ukdf['pct'].iloc[-1]=0.001071 , ukdf['amount'].iloc[-1]=40112412.1816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34788.5406', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29363', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21761
self.closeSec=1690561499, self.tradeDate='20230729', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29363.1, self.close=29349.2, self.high=29365.9, self.low=29349.1, self.vol=547.563, self.amt=16075462.7342 
2023-07-29 00:25:00,769:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230729   000000    000459  ...         0.0        0.0       0
5761  20230729   000500    000959  ...         0.0        0.0       0
5762  20230729   001000    001459  ...         0.0        0.0       0
5763  20230729   001500    001959  ...         0.0        0.0       0
5764  20230729   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 00:25:00,770:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690561499, self.tradeDate='20230729', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29363.1, self.close=29349.2, self.high=29365.9, self.low=29349.1, self.vol=547.563, self.amt=16075462.7342, ukdf['pct'].iloc[-1]=-0.000473 , ukdf['amount'].iloc[-1]=16075462.7342, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34620.46459437456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29350.93077656', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29331.7, self.close=29363.1, self.high=29363.9, self.low=29322.7 
127.0.0.1 - - [29/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-29 00:20:03,053:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29331.7, self.close=29363.1, self.high=29363.9, self.low=29322.7   
2023-07-29 00:20:04,032:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230728   235500    235959  1690559999  ...  29364.6 -0.000242   1727    5
1440  20230729   000000    000459  1690560299  ...  29332.0 -0.001362   1440    0
1441  20230729   000500    000959  1690560599  ...  29329.6 -0.000293   1441    1
1442  20230729   001000    001459  1690560899  ...  29323.0  0.000068   1442    2
1443  20230729   001500    001959  1690561199  ...  29322.7  0.001071   1443    3

[5 rows x 11 columns]
2023-07-29 00:20:04,042:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=2, self.factor=0.5824000467750419, self.count=21763 

self.closeSec=1690561499, self.tradeDate='20230729', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29363.1, self.close=29349.2, self.high=29365.9, self.low=29349.1 
127.0.0.1 - - [29/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-29 00:25:00,745:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690561499, self.tradeDate='20230729', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29363.1, self.close=29349.2, self.high=29365.9, self.low=29349.1   
2023-07-29 00:25:00,773:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230729   000000    000459  1690560299  ...  29332.0 -0.001362   1440    0
1441  20230729   000500    000959  1690560599  ...  29329.6 -0.000293   1441    1
1442  20230729   001000    001459  1690560899  ...  29323.0  0.000068   1442    2
1443  20230729   001500    001959  1690561199  ...  29322.7  0.001071   1443    3
1444  20230729   002000    002459  1690561499  ...  29349.1 -0.000473   1444    4

[5 rows x 11 columns]
2023-07-29 00:25:00,782:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-29 00:00:17,331:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230728    212959  29294.9  ...  49.583333  0.503684  0.579005
5803  20230728    215959  29277.7  ...  49.166667  0.503321  0.551721
5804  20230728    222959  29276.8  ...  49.583333  0.558858  0.516385
5805  20230728    225959  29430.8  ...  49.583333  0.572990  0.489120
5806  20230728    232959  29475.6  ...  49.583333  0.572823  0.465561

[5 rows x 33 columns]
0.5606617647058824
acc is : 0.5606617647058824
2023-07-29 00:00:17,388:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.501261  0.498739       0  ...  0.922370   1.0    0.0  0.967342
540     0  0.506463  0.493537       1  ...  0.927225   1.0    0.0  0.972434
541     0  0.554709  0.445291       1  ...  0.928633   1.0    0.0  0.973911
542     0  0.528210  0.471790       0  ...  0.928620   1.0    0.0  0.973897
543     0  0.515332  0.484668       0  ...  0.925568   1.0    0.0  0.970696

[5 rows x 10 columns]
2023-07-29 00:00:17,400:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501159  0.498841       0  ...  0.922370   1.0    0.0  0.967483
46     0  0.506455  0.493545       1  ...  0.927225   1.0    0.0  0.972604
47     0  0.554672  0.445328       1  ...  0.928633   1.0    0.0  0.974081
48     0  0.528027  0.471973       0  ...  0.928620   1.0    0.0  0.973653
49     0  0.515332  0.484668       0  ...  0.925568   1.0    0.0  0.970696

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-2203.165', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29385.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [29/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-29 00:00:04,284:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42754F1690560003572I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690560003972166, 'quantity': '25.502', 'price': '29380', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690560002670, 'updatetime': 1690560003972, 'tradetype': 'usdt', 'selfid': 42754, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690560003972, 'clientorderid': '42754F1690560003572I0L59', 'price': '29380', 'quantity': '25.502', 'commission': '749.24876', 'commissionasset': 'USDT', 'tradetime': 1690560003972, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690560003972}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10880 

self.closeSec=1690560599, self.tradeDate='20230729', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29379', self.close='29329.7'
127.0.0.1 - - [29/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-29 00:10:01,107:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690560599, self.tradeDate='20230729', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29379', self.close='29329.7'
2023-07-29 00:10:01,116:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230728   232000    232959  1690558199  29478.7  29475.1 -0.000122
573  20230728   233000    233959  1690558799  29475.1  29385.6 -0.003036
574  20230728   234000    234959  1690559399  29385.7  29387.1  0.000051
575  20230728   235000    235959  1690559999  29387.1    29379 -0.000276
576  20230729   000000    000959  1690560599    29379  29329.7 -0.001678
2023-07-29 00:10:01,116:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10881 

self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29329.6', self.close='29363.1'
127.0.0.1 - - [29/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-29 00:20:05,802:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29329.6', self.close='29363.1'
2023-07-29 00:20:06,174:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230728   233000    233959  1690558799  29475.1  29385.6 -0.003036
574  20230728   234000    234959  1690559399  29385.7  29387.1  0.000051
575  20230728   235000    235959  1690559999  29387.1    29379 -0.000276
576  20230729   000000    000959  1690560599    29379  29329.7 -0.001678
577  20230729   001000    001959  1690561199  29329.6  29363.1  0.001139
2023-07-29 00:20:06,181:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-29 00:00:02,129:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-29 00:00:02,186:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7290000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230728, closeTime:235959, close:29379, total:996515.1559743, pct_pre:-0.0022856088636525884, thd:0.34706826792859596, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10883 

self.closeSec=1690560599, self.tradeDate='20230729', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29379', self.close='29329.7'
2023-07-29 00:10:01,126:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690560599, self.tradeDate='20230729', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29379', self.close='29329.7'
127.0.0.1 - - [29/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-29 00:10:01,133:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230728   232000    232959  1690558199  29478.7  29475.1
17421  20230728   233000    233959  1690558799  29475.1  29385.6
17422  20230728   234000    234959  1690559399  29385.7  29387.1
17423  20230728   235000    235959  1690559999  29387.1    29379
17424  20230729   000000    000959  1690560599    29379  29329.7
2023-07-29 00:10:01,133:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10884 

self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29329.6', self.close='29363.1'
127.0.0.1 - - [29/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-29 00:20:07,164:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29329.6', self.close='29363.1'
2023-07-29 00:20:07,268:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230728   233000    233959  1690558799  29475.1  29385.6
17422  20230728   234000    234959  1690559399  29385.7  29387.1
17423  20230728   235000    235959  1690559999  29387.1    29379
17424  20230729   000000    000959  1690560599    29379  29329.7
17425  20230729   001000    001959  1690561199  29329.6  29363.1
2023-07-29 00:20:07,269:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [29/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-29 00:00:04,180:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42753F1690560003549I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690560003952765, 'quantity': '37.547', 'price': '29380', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690560002713, 'updatetime': 1690560003952, 'tradetype': 'usdt', 'selfid': 42753, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690560003952, 'clientorderid': '42753F1690560003549I0L2', 'price': '29380', 'quantity': '37.547', 'commission': '1103.13086', 'commissionasset': 'USDT', 'tradetime': 1690560003952, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690560003952}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10883 

self.closeSec=1690560599, self.tradeDate='20230729', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29379', self.close='29329.7'
2023-07-29 00:10:01,107:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690560599, self.tradeDate='20230729', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29379', self.close='29329.7'
2023-07-29 00:10:01,114:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230728   232000    232959  1690558199  29478.7  29475.1
12237  20230728   233000    233959  1690558799  29475.1  29385.6
12238  20230728   234000    234959  1690559399  29385.7  29387.1
12239  20230728   235000    235959  1690559999  29387.1    29379
12240  20230729   000000    000959  1690560599    29379  29329.7
2023-07-29 00:10:01,115:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10884 

self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29329.6', self.close='29363.1'
127.0.0.1 - - [29/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-29 00:20:07,052:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29329.6', self.close='29363.1'
2023-07-29 00:20:07,191:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230728   233000    233959  1690558799  29475.1  29385.6
12238  20230728   234000    234959  1690559399  29385.7  29387.1
12239  20230728   235000    235959  1690559999  29387.1    29379
12240  20230729   000000    000959  1690560599    29379  29329.7
12241  20230729   001000    001959  1690561199  29329.6  29363.1
2023-07-29 00:20:07,192:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21760
self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29331.7, self.close=29363.1, self.high=29363.9, self.low=29322.7, self.vol=1366.808, self.amt=40112412.1816 
127.0.0.1 - - [29/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-29 00:20:04,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230728   235500    235959  ...         0.0        0.0       0
5760  20230729   000000    000459  ...         0.0        0.0       0
5761  20230729   000500    000959  ...         0.0        0.0       0
5762  20230729   001000    001459  ...         0.0        0.0       0
5763  20230729   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 00:20:04,823:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690561199, self.tradeDate='20230729', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29331.7, self.close=29363.1, self.high=29363.9, self.low=29322.7, self.vol=1366.808, self.amt=40112412.1816, ukdf['pct'].iloc[-1]=0.001071 , ukdf['amount'].iloc[-1]=40112412.1816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '93558.179', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29363', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [29/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21761
self.closeSec=1690561499, self.tradeDate='20230729', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29363.1, self.close=29349.2, self.high=29365.9, self.low=29349.1, self.vol=547.563, self.amt=16075462.7342 
2023-07-29 00:25:00,786:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230729   000000    000459  ...         0.0        0.0       0
5761  20230729   000500    000959  ...         0.0        0.0       0
5762  20230729   001000    001459  ...         0.0        0.0       0
5763  20230729   001500    001959  ...         0.0        0.0       0
5764  20230729   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 00:25:00,786:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690561499, self.tradeDate='20230729', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29363.1, self.close=29349.2, self.high=29365.9, self.low=29349.1, self.vol=547.563, self.amt=16075462.7342, ukdf['pct'].iloc[-1]=-0.000473 , ukdf['amount'].iloc[-1]=16075462.7342, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '93109.91597221496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29350.93077656', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230728   120000    155959  1690531199  ...    723  0.114819 -1.076804    -1.0
724  20230728   160000    195959  1690545599  ...    724  0.014316 -1.429866    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.767', 'enterprice': '29133.6', 'countrevence': '0', 'unrealprofit': '-3386.2216429563', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29195.4295989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [29/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1593964.3113288, self.flagDict['side']='sell', self.tradeCount=14, self.count=453
self.closeSec=1690559999, self.tradeDate='20230728', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29195.4, self.close=29379.0, self.high=29535.7, self.low=29192.5, self.vol=93071.263, self.amt=2735679251.67912 
2023-07-29 00:00:01,723:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690559999, self.tradeDate='20230728', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29195.4, self.close=29379.0, self.high=29535.7, self.low=29192.5, self.vol=93071.263, self.amt=2735679251.67912 
2023-07-29 00:00:01,737:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230728   040000    075959  ...  20489.076  5.978041e+08  0.001959
722  20230728   080000    115959  ...  23272.406  6.803464e+08  0.001030
723  20230728   120000    155959  ...  19221.001  5.608905e+08 -0.003861
724  20230728   160000    195959  ...  25255.902  7.368084e+08  0.002348
725  20230728   200000    235959  ...  93071.263  2.735679e+09  0.006292

[5 rows x 11 columns]
2023-07-29 00:00:02,452:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230728   040000    075959  1690502399  ...    721  0.490120  0.346234     NaN
722  20230728   080000    115959  1690516799  ...    722  0.335138 -0.248092     NaN
723  20230728   120000    155959  1690531199  ...    723  0.114819 -1.076804    -1.0
724  20230728   160000    195959  1690545599  ...    724  0.014316 -1.429866    -1.0
725  20230728   200000    235959  1690559999  ...    725  0.330897 -0.233582     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.767', 'enterprice': '29133.6', 'countrevence': '0', 'unrealprofit': '-13494.5888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29380', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


