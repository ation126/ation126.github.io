# 20230707 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15424
self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30395.0, self.close=30366.4, self.high=30414.0, self.low=30361.9, self.vol=1342.163, self.amt=40779662.1684 
127.0.0.1 - - [07/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-07 00:20:06,955:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230706   235500    235959  ...         0.0        0.0       0
5760  20230707   000000    000459  ...         0.0        0.0       0
5761  20230707   000500    000959  ...         0.0        0.0       0
5762  20230707   001000    001459  ...         0.0        0.0       0
5763  20230707   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 00:20:06,986:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30395.0, self.close=30366.4, self.high=30414.0, self.low=30361.9, self.vol=1342.163, self.amt=40779662.1684, ukdf['pct'].iloc[-1]=-0.000941 , ukdf['amount'].iloc[-1]=40779662.1684, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48864.9414', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30373.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15425
self.closeSec=1688660699, self.tradeDate='20230707', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30366.4, self.close=30334.9, self.high=30377.5, self.low=30266.9, self.vol=4540.191, self.amt=137639586.9058 
127.0.0.1 - - [07/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-07 00:25:00,814:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230707   000000    000459  ...         0.0        0.0       0
5761  20230707   000500    000959  ...         0.0        0.0       0
5762  20230707   001000    001459  ...         0.0        0.0       0
5763  20230707   001500    001959  ...         0.0        0.0       0
5764  20230707   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 00:25:00,816:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688660699, self.tradeDate='20230707', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30366.4, self.close=30334.9, self.high=30377.5, self.low=30266.9, self.vol=4540.191, self.amt=137639586.9058, ukdf['pct'].iloc[-1]=-0.001037 , ukdf['amount'].iloc[-1]=137639586.9058, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48323.22', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30334.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30395.0, self.close=30366.4, self.high=30414.0, self.low=30361.9 
127.0.0.1 - - [07/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-07 00:20:04,605:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30395.0, self.close=30366.4, self.high=30414.0, self.low=30361.9   
2023-07-07 00:20:06,105:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230706   235500    235959  1688659199  ...  30382.3 -0.000454   1727    5
1440  20230707   000000    000459  1688659499  ...  30368.0  0.000138   1440    0
1441  20230707   000500    000959  1688659799  ...  30390.5  0.000839   1441    1
1442  20230707   001000    001459  1688660099  ...  30330.0 -0.000713   1442    2
1443  20230707   001500    001959  1688660399  ...  30361.9 -0.000941   1443    3

[5 rows x 11 columns]
2023-07-07 00:20:06,124:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=18, self.factor=0.5698735259860577, self.count=15427 

self.closeSec=1688660699, self.tradeDate='20230707', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30366.4, self.close=30334.9, self.high=30377.5, self.low=30266.9 
2023-07-07 00:25:00,785:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688660699, self.tradeDate='20230707', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30366.4, self.close=30334.9, self.high=30377.5, self.low=30266.9   
2023-07-07 00:25:00,811:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230707   000000    000459  1688659499  ...  30368.0  0.000138   1440    0
1441  20230707   000500    000959  1688659799  ...  30390.5  0.000839   1441    1
1442  20230707   001000    001459  1688660099  ...  30330.0 -0.000713   1442    2
1443  20230707   001500    001959  1688660399  ...  30361.9 -0.000941   1443    3
1444  20230707   002000    002459  1688660699  ...  30266.9 -0.001037   1444    4

[5 rows x 11 columns]
2023-07-07 00:25:00,812:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-07 00:00:20,189:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230706    212959  30588.6  ...  48.333333  0.481536  0.446727
5803  20230706    215959  30584.2  ...  47.916667  0.449198  0.479837
5804  20230706    222959  30361.6  ...  47.500000  0.407539  0.514157
5805  20230706    225959  30029.2  ...  47.500000  0.434490  0.533566
5806  20230706    232959  30196.5  ...  47.916667  0.440943  0.550052

[5 rows x 33 columns]
0.5680147058823529
acc is : 0.5680147058823529
2023-07-07 00:00:20,293:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.440327  0.559673       0  ...  0.923121  -1.0    0.0  0.988523
540     1  0.383491  0.616509       0  ...  0.933221  -1.0    0.0  0.977707
541     1  0.365369  0.634631       1  ...  0.928022  -1.0    0.0  0.983154
542     1  0.483703  0.516297       1  ...  0.926744  -1.0    0.0  0.984509
543     1  0.477045  0.522955       1  ...  0.922183  -1.0    0.0  0.989353

[5 rows x 10 columns]
2023-07-07 00:00:20,307:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.438423  0.561577       0  ...  0.931506  -1.0    0.0  0.981487
46     1  0.381908  0.618092       0  ...  0.933221  -1.0    0.0  0.972965
47     1  0.363865  0.636135       1  ...  0.928022  -1.0    0.0  0.978386
48     1  0.483060  0.516940       1  ...  0.926744  -1.0    0.0  0.984137
49     1  0.477045  0.522955       1  ...  0.922183  -1.0    0.0  0.989353

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.821', 'enterprice': '30691.5', 'countrevence': '0', 'unrealprofit': '7195.75409753403', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30389.42392857', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [07/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-07 00:00:04,523:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42548F1688659203720I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688659204121521, 'quantity': '25.356', 'price': '30390.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688659202774, 'updatetime': 1688659204121, 'tradetype': 'usdt', 'selfid': 42548, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688659204121, 'clientorderid': '42548F1688659203720I0L59', 'price': '30390.3', 'quantity': '25.356', 'commission': '770.5764468', 'commissionasset': 'USDT', 'tradetime': 1688659204121, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688659204121}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7712 

self.closeSec=1688659799, self.tradeDate='20230707', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30390.3', self.close='30416.7'
2023-07-07 00:10:01,134:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688659799, self.tradeDate='20230707', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30390.3', self.close='30416.7'
2023-07-07 00:10:01,141:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230706   232000    232959  1688657399  30185.4  30238.2  0.001753
573  20230706   233000    233959  1688657999  30238.2    30340  0.003367
574  20230706   234000    234959  1688658599    30340  30406.2  0.002182
575  20230706   235000    235959  1688659199  30406.1  30390.3 -0.000523
576  20230707   000000    000959  1688659799  30390.3  30416.7  0.000869
2023-07-07 00:10:01,141:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7713 

self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30416.7', self.close='30366.4'
127.0.0.1 - - [07/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-07 00:20:07,025:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30416.7', self.close='30366.4'
2023-07-07 00:20:07,804:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230706   233000    233959  1688657999  30238.2    30340  0.003367
574  20230706   234000    234959  1688658599    30340  30406.2  0.002182
575  20230706   235000    235959  1688659199  30406.1  30390.3 -0.000523
576  20230707   000000    000959  1688659799  30390.3  30416.7  0.000869
577  20230707   001000    001959  1688660399  30416.7  30366.4 -0.001654
2023-07-07 00:20:07,805:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-07 00:00:02,183:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-07 00:00:02,306:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7070000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230706, closeTime:235959, close:30390.3, total:993267.8008712, pct_pre:0.022709539784493193, thd:-0.16605473704992418, side:sell 
127.0.0.1 - - [07/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7715 

self.closeSec=1688659799, self.tradeDate='20230707', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30390.3', self.close='30416.7'
2023-07-07 00:10:01,132:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688659799, self.tradeDate='20230707', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30390.3', self.close='30416.7'
2023-07-07 00:10:01,153:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230706   232000    232959  1688657399  30185.4  30238.2
17421  20230706   233000    233959  1688657999  30238.2    30340
17422  20230706   234000    234959  1688658599    30340  30406.2
17423  20230706   235000    235959  1688659199  30406.1  30390.3
17424  20230707   000000    000959  1688659799  30390.3  30416.7
2023-07-07 00:10:01,155:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7716 

self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30416.7', self.close='30366.4'
127.0.0.1 - - [07/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-07 00:20:08,757:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30416.7', self.close='30366.4'
2023-07-07 00:20:08,929:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230706   233000    233959  1688657999  30238.2    30340
17422  20230706   234000    234959  1688658599    30340  30406.2
17423  20230706   235000    235959  1688659199  30406.1  30390.3
17424  20230707   000000    000959  1688659799  30390.3  30416.7
17425  20230707   001000    001959  1688660399  30416.7  30366.4
2023-07-07 00:20:08,930:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [07/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-07 00:00:04,343:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42547F1688659203688I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688659204074365, 'quantity': '37.772', 'price': '30390.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688659202735, 'updatetime': 1688659204074, 'tradetype': 'usdt', 'selfid': 42547, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688659204074, 'clientorderid': '42547F1688659203688I0L2', 'price': '30390.3', 'quantity': '37.772', 'commission': '1147.9024116', 'commissionasset': 'USDT', 'tradetime': 1688659204074, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688659204074}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7715 

self.closeSec=1688659799, self.tradeDate='20230707', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30390.3', self.close='30416.7'
127.0.0.1 - - [07/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-07 00:10:01,137:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688659799, self.tradeDate='20230707', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30390.3', self.close='30416.7'
2023-07-07 00:10:01,159:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230706   232000    232959  1688657399  30185.4  30238.2
12237  20230706   233000    233959  1688657999  30238.2    30340
12238  20230706   234000    234959  1688658599    30340  30406.2
12239  20230706   235000    235959  1688659199  30406.1  30390.3
12240  20230707   000000    000959  1688659799  30390.3  30416.7
2023-07-07 00:10:01,160:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7716 

self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30416.7', self.close='30366.4'
127.0.0.1 - - [07/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-07 00:20:08,447:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30416.7', self.close='30366.4'
2023-07-07 00:20:08,758:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230706   233000    233959  1688657999  30238.2    30340
12238  20230706   234000    234959  1688658599    30340  30406.2
12239  20230706   235000    235959  1688659199  30406.1  30390.3
12240  20230707   000000    000959  1688659799  30390.3  30416.7
12241  20230707   001000    001959  1688660399  30416.7  30366.4
2023-07-07 00:20:08,759:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15424
self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30395.0, self.close=30366.4, self.high=30414.0, self.low=30361.9, self.vol=1342.163, self.amt=40779662.1684 
127.0.0.1 - - [07/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-07 00:20:06,945:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230706   235500    235959  ...         0.0        0.0       0
5760  20230707   000000    000459  ...         0.0        0.0       0
5761  20230707   000500    000959  ...         0.0        0.0       0
5762  20230707   001000    001459  ...         0.0        0.0       0
5763  20230707   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 00:20:06,985:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688660399, self.tradeDate='20230707', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30395.0, self.close=30366.4, self.high=30414.0, self.low=30361.9, self.vol=1342.163, self.amt=40779662.1684, ukdf['pct'].iloc[-1]=-0.000941 , ukdf['amount'].iloc[-1]=40779662.1684, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '131100.3018', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30373.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15425
self.closeSec=1688660699, self.tradeDate='20230707', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30366.4, self.close=30334.9, self.high=30377.5, self.low=30266.9, self.vol=4540.191, self.amt=137639586.9058 
127.0.0.1 - - [07/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-07 00:25:00,820:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230707   000000    000459  ...         0.0        0.0       0
5761  20230707   000500    000959  ...         0.0        0.0       0
5762  20230707   001000    001459  ...         0.0        0.0       0
5763  20230707   001500    001959  ...         0.0        0.0       0
5764  20230707   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 00:25:00,821:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688660699, self.tradeDate='20230707', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30366.4, self.close=30334.9, self.high=30377.5, self.low=30266.9, self.vol=4540.191, self.amt=137639586.9058, ukdf['pct'].iloc[-1]=-0.001037 , ukdf['amount'].iloc[-1]=137639586.9058, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '129655.5169', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30334.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230706   120000    155959  1688630399  ...    723  0.604498  0.401745     NaN
724  20230706   160000    195959  1688644799  ...    724  0.571736  0.346347     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '3957.53', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30825.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=321
self.closeSec=1688659199, self.tradeDate='20230706', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30833.0, self.close=30390.3, self.high=30866.4, self.low=29865.0, self.vol=270998.539, self.amt=8221108723.18529 
127.0.0.1 - - [07/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-07 00:00:01,730:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688659199, self.tradeDate='20230706', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30833.0, self.close=30390.3, self.high=30866.4, self.low=29865.0, self.vol=270998.539, self.amt=8221108723.18529 
2023-07-07 00:00:01,761:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230706   040000    075959  ...   26258.551  7.995880e+08  0.002252
722  20230706   080000    115959  ...   27525.436  8.380867e+08 -0.000354
723  20230706   120000    155959  ...   59326.951  1.819310e+09  0.010322
724  20230706   160000    195959  ...  227986.969  7.104595e+09  0.001257
725  20230706   200000    235959  ...  270998.539  8.221109e+09 -0.014294

[5 rows x 11 columns]
2023-07-07 00:00:03,368:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230706   040000    075959  1688601599  ...    721  0.614850  0.372855     NaN
722  20230706   080000    115959  1688615999  ...    722  0.642712  0.469417     NaN
723  20230706   120000    155959  1688630399  ...    723  0.604498  0.401745     NaN
724  20230706   160000    195959  1688644799  ...    724  0.571736  0.346347     NaN
725  20230706   200000    235959  1688659199  ...    725  0.249758 -0.418730     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-18960.8098825145', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30393.48605311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


