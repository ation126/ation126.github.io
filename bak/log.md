# 20230628 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12832
self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30509.4, self.close=30458.6, self.high=30519.0, self.low=30438.7, self.vol=2313.065, self.amt=70466249.5789 
127.0.0.1 - - [28/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-28 00:20:08,022:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230627   235500    235959  ...         0.0        0.0       0
5760  20230628   000000    000459  ...         0.0        0.0       0
5761  20230628   000500    000959  ...         0.0        0.0       0
5762  20230628   001000    001459  ...         0.0        0.0       0
5763  20230628   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 00:20:08,072:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30509.4, self.close=30458.6, self.high=30519.0, self.low=30438.7, self.vol=2313.065, self.amt=70466249.5789, ukdf['pct'].iloc[-1]=-0.001616 , ukdf['amount'].iloc[-1]=70466249.5789, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50112.711', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30463.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12833
self.closeSec=1687883099, self.tradeDate='20230628', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30458.7, self.close=30537.5, self.high=30547.9, self.low=30456.7, self.vol=1566.789, self.amt=47792632.8495 
2023-06-28 00:25:00,801:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230628   000000    000459  ...         0.0        0.0       0
5761  20230628   000500    000959  ...         0.0        0.0       0
5762  20230628   001000    001459  ...         0.0        0.0       0
5763  20230628   001500    001959  ...         0.0        0.0       0
5764  20230628   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 00:25:00,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687883099, self.tradeDate='20230628', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30458.7, self.close=30537.5, self.high=30547.9, self.low=30456.7, self.vol=1566.789, self.amt=47792632.8495, ukdf['pct'].iloc[-1]=0.00259 , ukdf['amount'].iloc[-1]=47792632.8495, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51112.5978', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30535.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30509.4, self.close=30458.6, self.high=30519.0, self.low=30438.7 
127.0.0.1 - - [28/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-28 00:20:05,243:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30509.4, self.close=30458.6, self.high=30519.0, self.low=30438.7   
2023-06-28 00:20:06,922:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230627   235500    235959  1687881599  ...  30480.0 -0.001592   1727    5
1440  20230628   000000    000459  1687881899  ...  30435.9  0.001374   1440    0
1441  20230628   000500    000959  1687882199  ...  30510.6  0.000812   1441    1
1442  20230628   001000    001459  1687882499  ...  30496.0 -0.001509   1442    2
1443  20230628   001500    001959  1687882799  ...  30438.7 -0.001616   1443    3

[5 rows x 11 columns]
2023-06-28 00:20:06,943:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=18, self.factor=0.47243132861274423, self.count=12835 

self.closeSec=1687883099, self.tradeDate='20230628', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30458.7, self.close=30537.5, self.high=30547.9, self.low=30456.7 
127.0.0.1 - - [28/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-28 00:25:00,735:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687883099, self.tradeDate='20230628', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30458.7, self.close=30537.5, self.high=30547.9, self.low=30456.7   
2023-06-28 00:25:00,753:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230628   000000    000459  1687881899  ...  30435.9  0.001374   1440    0
1441  20230628   000500    000959  1687882199  ...  30510.6  0.000812   1441    1
1442  20230628   001000    001459  1687882499  ...  30496.0 -0.001509   1442    2
1443  20230628   001500    001959  1687882799  ...  30438.7 -0.001616   1443    3
1444  20230628   002000    002459  1687883099  ...  30456.7  0.002590   1444    4

[5 rows x 11 columns]
2023-06-28 00:25:00,753:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-28 00:00:23,586:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230627    212959  30703.2  ...  48.750000  0.533774  0.335101
5803  20230627    215959  30590.7  ...  49.166667  0.535158  0.330017
5804  20230627    222959  30599.9  ...  49.583333  0.570632  0.319414
5805  20230627    225959  30839.0  ...  49.583333  0.563020  0.312421
5806  20230627    232959  30795.5  ...  49.583333  0.522921  0.323385

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-06-28 00:00:23,716:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.470724  0.529276       1  ...  1.105065  -1.0    0.0  1.198750
540     1  0.496036  0.503964       1  ...  1.096496  -1.0    0.0  1.208046
541     0  0.531957  0.468043       0  ...  1.097961  -1.0    0.0  1.206432
542     1  0.496704  0.503296       0  ...  1.106236  -1.0    0.0  1.197339
543     1  0.451007  0.548993       0  ...  1.108990  -1.0    0.0  1.194358

[5 rows x 10 columns]
2023-06-28 00:00:23,748:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.470704  0.529296       1  ...  1.105065  -1.0    0.0  1.196724
46     1  0.495937  0.504063       1  ...  1.096496  -1.0    0.0  1.206236
47     0  0.531773  0.468227       0  ...  1.097961  -1.0    0.0  1.204624
48     1  0.496704  0.503296       0  ...  1.106236  -1.0    0.0  1.195330
49     1  0.451007  0.548993       0  ...  1.108990  -1.0    0.0  1.194358

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.381', 'enterprice': '30103.1', 'countrevence': '0', 'unrealprofit': '-10725.1377', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30494.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-28 00:00:04,472:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42477F1687881603619I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687881604026477, 'quantity': '26.557', 'price': '30487.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687881602656, 'updatetime': 1687881604026, 'tradetype': 'usdt', 'selfid': 42477, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687881604026, 'clientorderid': '42477F1687881603619I0L59', 'price': '30487.3', 'quantity': '26.557', 'commission': '809.6512261', 'commissionasset': 'USDT', 'tradetime': 1687881604026, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687881604026}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6416 

self.closeSec=1687882199, self.tradeDate='20230628', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30487.4', self.close='30554'
2023-06-28 00:10:01,075:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687882199, self.tradeDate='20230628', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30487.4', self.close='30554'
2023-06-28 00:10:01,107:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230627   232000    232959  1687879799  30604.5  30558.1 -0.001516
573  20230627   233000    233959  1687880399    30558    30597  0.001273
574  20230627   234000    234959  1687880999  30599.4    30520 -0.002517
575  20230627   235000    235959  1687881599  30520.1  30487.4 -0.001068
576  20230628   000000    000959  1687882199  30487.4    30554  0.002185
2023-06-28 00:10:01,107:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6417 

self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30554', self.close='30458.8'
127.0.0.1 - - [28/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-28 00:20:07,722:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30554', self.close='30458.8'
2023-06-28 00:20:08,623:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230627   233000    233959  1687880399    30558    30597  0.001273
574  20230627   234000    234959  1687880999  30599.4    30520 -0.002517
575  20230627   235000    235959  1687881599  30520.1  30487.4 -0.001068
576  20230628   000000    000959  1687882199  30487.4    30554  0.002185
577  20230628   001000    001959  1687882799    30554  30458.8 -0.003116
2023-06-28 00:20:08,623:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-28 00:00:02,140:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-28 00:00:02,237:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6280000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230627, closeTime:235959, close:30487.4, total:992420.1027844, pct_pre:-0.0004673389326241839, thd:0.09346561407688803, side:sell 
127.0.0.1 - - [28/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6419 

self.closeSec=1687882199, self.tradeDate='20230628', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30487.4', self.close='30554'
2023-06-28 00:10:01,089:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687882199, self.tradeDate='20230628', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30487.4', self.close='30554'
2023-06-28 00:10:01,113:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230627   232000    232959  1687879799  30604.5  30558.1
17421  20230627   233000    233959  1687880399    30558    30597
17422  20230627   234000    234959  1687880999  30599.4    30520
17423  20230627   235000    235959  1687881599  30520.1  30487.4
17424  20230628   000000    000959  1687882199  30487.4    30554
2023-06-28 00:10:01,113:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6420 

self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30554', self.close='30458.8'
127.0.0.1 - - [28/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-28 00:20:10,067:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30554', self.close='30458.8'
2023-06-28 00:20:10,210:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230627   233000    233959  1687880399    30558    30597
17422  20230627   234000    234959  1687880999  30599.4    30520
17423  20230627   235000    235959  1687881599  30520.1  30487.4
17424  20230628   000000    000959  1687882199  30487.4    30554
17425  20230628   001000    001959  1687882799    30554  30458.8
2023-06-28 00:20:10,211:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [28/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-28 00:00:04,281:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42478F1687881603664I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687881604028745, 'quantity': '38.441', 'price': '30487.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687881602765, 'updatetime': 1687881604028, 'tradetype': 'usdt', 'selfid': 42478, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687881604028, 'clientorderid': '42478F1687881603664I0L2', 'price': '30487.4', 'quantity': '38.441', 'commission': '1171.9661434', 'commissionasset': 'USDT', 'tradetime': 1687881604028, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687881604028}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6419 

self.closeSec=1687882199, self.tradeDate='20230628', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30487.4', self.close='30554'
2023-06-28 00:10:01,082:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687882199, self.tradeDate='20230628', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30487.4', self.close='30554'
2023-06-28 00:10:01,109:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230627   232000    232959  1687879799  30604.5  30558.1
12237  20230627   233000    233959  1687880399    30558    30597
12238  20230627   234000    234959  1687880999  30599.4    30520
12239  20230627   235000    235959  1687881599  30520.1  30487.4
12240  20230628   000000    000959  1687882199  30487.4    30554
2023-06-28 00:10:01,110:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6420 

self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30554', self.close='30458.8'
127.0.0.1 - - [28/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-28 00:20:09,565:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30554', self.close='30458.8'
2023-06-28 00:20:09,913:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230627   233000    233959  1687880399    30558    30597
12238  20230627   234000    234959  1687880999  30599.4    30520
12239  20230627   235000    235959  1687881599  30520.1  30487.4
12240  20230628   000000    000959  1687882199  30487.4    30554
12241  20230628   001000    001959  1687882799    30554  30458.8
2023-06-28 00:20:09,914:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12832
self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30509.4, self.close=30458.6, self.high=30519.0, self.low=30438.7, self.vol=2313.065, self.amt=70466249.5789 
127.0.0.1 - - [28/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-28 00:20:08,012:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230627   235500    235959  ...         0.0        0.0       0
5760  20230628   000000    000459  ...         0.0        0.0       0
5761  20230628   000500    000959  ...         0.0        0.0       0
5762  20230628   001000    001459  ...         0.0        0.0       0
5763  20230628   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 00:20:08,043:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687882799, self.tradeDate='20230628', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30509.4, self.close=30458.6, self.high=30519.0, self.low=30438.7, self.vol=2313.065, self.amt=70466249.5789, ukdf['pct'].iloc[-1]=-0.001616 , ukdf['amount'].iloc[-1]=70466249.5789, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '134428.1354', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30463.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12833
self.closeSec=1687883099, self.tradeDate='20230628', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30458.7, self.close=30537.5, self.high=30547.9, self.low=30456.7, self.vol=1566.789, self.amt=47792632.8495 
127.0.0.1 - - [28/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-28 00:25:00,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230628   000000    000459  ...         0.0        0.0       0
5761  20230628   000500    000959  ...         0.0        0.0       0
5762  20230628   001000    001459  ...         0.0        0.0       0
5763  20230628   001500    001959  ...         0.0        0.0       0
5764  20230628   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 00:25:00,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687883099, self.tradeDate='20230628', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30458.7, self.close=30537.5, self.high=30547.9, self.low=30456.7, self.vol=1566.789, self.amt=47792632.8495, ukdf['pct'].iloc[-1]=0.00259 , ukdf['amount'].iloc[-1]=47792632.8495, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '137094.8592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30535.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230627   120000    155959  1687852799  ...    723  0.108286 -1.222146    -1.0
724  20230627   160000    195959  1687867199  ...    724  0.057545 -1.332153    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-1129.2816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30728.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--: 127.0.0.1 - - [28/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=267
self.closeSec=1687881599, self.tradeDate='20230627', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30720.1, self.close=30487.4, self.high=30998.5, self.low=30351.0, self.vol=147090.862, self.amt=4514833805.9311 
2023-06-28 00:00:01,697:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687881599, self.tradeDate='20230627', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30720.1, self.close=30487.4, self.high=30998.5, self.low=30351.0, self.vol=147090.862, self.amt=4514833805.9311 
2023-06-28 00:00:01,724:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230627   040000    075959  ...   28608.033  8.638494e+08  0.000867
722  20230627   080000    115959  ...   41157.089  1.249641e+09  0.003301
723  20230627   120000    155959  ...   36501.042  1.107268e+09  0.001466
724  20230627   160000    195959  ...   81853.383  2.502512e+09  0.010380
725  20230627   200000    235959  ...  147090.862  4.514834e+09 -0.007575

[5 rows x 11 columns]
2023-06-28 00:00:03,202:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230627   040000    075959  1687823999  ...    721  0.210680 -0.981612    -1.0
722  20230627   080000    115959  1687838399  ...    722  0.180171 -1.049700    -1.0
723  20230627   120000    155959  1687852799  ...    723  0.108286 -1.222146    -1.0
724  20230627   160000    195959  1687867199  ...    724  0.057545 -1.332153    -1.0
725  20230627   200000    235959  1687881599  ...    725  0.026213 -1.386319    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '11697.6528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30487.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


