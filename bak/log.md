# 20230706 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15136
self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30373.6, self.close=30410.5, self.high=30420.0, self.low=30369.6, self.vol=1501.204, self.amt=45634872.7787 
127.0.0.1 - - [06/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-06 00:20:06,739:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230705   235500    235959  ...         0.0        0.0       0
5760  20230706   000000    000459  ...         0.0        0.0       0
5761  20230706   000500    000959  ...         0.0        0.0       0
5762  20230706   001000    001459  ...         0.0        0.0       0
5763  20230706   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 00:20:06,760:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30373.6, self.close=30410.5, self.high=30420.0, self.low=30369.6, self.vol=1501.204, self.amt=45634872.7787, ukdf['pct'].iloc[-1]=0.001212 , ukdf['amount'].iloc[-1]=45634872.7787, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49365.04420939014', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30409.71144689', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15137
self.closeSec=1688574299, self.tradeDate='20230706', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30410.5, self.close=30411.8, self.high=30420.0, self.low=30399.0, self.vol=939.405, self.amt=28566183.4676 
127.0.0.1 - - [06/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-06 00:25:00,804:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230706   000000    000459  ...         0.0        0.0       0
5761  20230706   000500    000959  ...         0.0        0.0       0
5762  20230706   001000    001459  ...         0.0        0.0       0
5763  20230706   001500    001959  ...         0.0        0.0       0
5764  20230706   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 00:25:00,804:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688574299, self.tradeDate='20230706', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30410.5, self.close=30411.8, self.high=30420.0, self.low=30399.0, self.vol=939.405, self.amt=28566183.4676, ukdf['pct'].iloc[-1]=4.3e-05 , ukdf['amount'].iloc[-1]=28566183.4676, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49394.1294', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30411.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30373.6, self.close=30410.5, self.high=30420.0, self.low=30369.6 
127.0.0.1 - - [06/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-06 00:20:04,559:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30373.6, self.close=30410.5, self.high=30420.0, self.low=30369.6   
2023-07-06 00:20:05,890:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230705   235500    235959  1688572799  ...  30333.0  0.000102   1727    5
1440  20230706   000000    000459  1688573099  ...  30321.2  0.000623   1440    0
1441  20230706   000500    000959  1688573399  ...  30352.0  0.000362   1441    1
1442  20230706   001000    001459  1688573699  ...  30372.5 -0.000040   1442    2
1443  20230706   001500    001959  1688573999  ...  30369.6  0.001212   1443    3

[5 rows x 11 columns]
2023-07-06 00:20:05,900:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.699657182883284, self.count=15139 

self.closeSec=1688574299, self.tradeDate='20230706', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30410.5, self.close=30411.8, self.high=30420.0, self.low=30399.0 
127.0.0.1 - - [06/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-06 00:25:00,719:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688574299, self.tradeDate='20230706', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30410.5, self.close=30411.8, self.high=30420.0, self.low=30399.0   
2023-07-06 00:25:00,747:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230706   000000    000459  1688573099  ...  30321.2  0.000623   1440    0
1441  20230706   000500    000959  1688573399  ...  30352.0  0.000362   1441    1
1442  20230706   001000    001459  1688573699  ...  30372.5 -0.000040   1442    2
1443  20230706   001500    001959  1688573999  ...  30369.6  0.001212   1443    3
1444  20230706   002000    002459  1688574299  ...  30399.0  0.000043   1444    4

[5 rows x 11 columns]
2023-07-06 00:25:00,748:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-06 00:00:19,639:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230705    212959  30309.9  ...  47.500000  0.363091  0.762480
5803  20230705    215959  30218.9  ...  47.916667  0.401415  0.762872
5804  20230705    222959  30350.5  ...  47.916667  0.411646  0.759941
5805  20230705    225959  30387.9  ...  48.333333  0.416665  0.755007
5806  20230705    232959  30406.3  ...  48.333333  0.408188  0.753563

[5 rows x 33 columns]
0.5790441176470589
acc is : 0.5790441176470589
2023-07-06 00:00:19,737:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.470260  0.529740       1  ...  0.931019  -1.0    0.0  0.993034
540     0  0.520391  0.479609       1  ...  0.929874  -1.0    0.0  0.994255
541     0  0.510980  0.489020       1  ...  0.929311  -1.0    0.0  0.994857
542     0  0.510908  0.489092       0  ...  0.930653  -1.0    0.0  0.993420
543     0  0.503648  0.496352       0  ...  0.931183  -1.0    0.0  0.992854

[5 rows x 10 columns]
2023-07-06 00:00:19,763:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.469883  0.530117       1  ...  0.931019  -1.0    0.0  0.989892
46     0  0.519126  0.480874       1  ...  0.931556  -1.0    0.0  0.990147
47     0  0.509863  0.490137       1  ...  0.930992  -1.0    0.0  0.990746
48     0  0.510325  0.489675       0  ...  0.930653  -1.0    0.0  0.989516
49     0  0.503648  0.496352       0  ...  0.931183  -1.0    0.0  0.992854

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.486', 'enterprice': '30415.6', 'countrevence': '0', 'unrealprofit': '1926.7416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30340', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [06/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-06 00:00:04,245:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42535F1688572803622I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688572804015295, 'quantity': '25.503', 'price': '30345', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688572802657, 'updatetime': 1688572804015, 'tradetype': 'usdt', 'selfid': 42535, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688572804015, 'clientorderid': '42535F1688572803622I0L59', 'price': '30345', 'quantity': '25.503', 'commission': '773.888535', 'commissionasset': 'USDT', 'tradetime': 1688572804015, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688572804015}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7568 

self.closeSec=1688573399, self.tradeDate='20230706', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30345.1', self.close='30374.9'
2023-07-06 00:10:01,168:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688573399, self.tradeDate='20230706', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30345.1', self.close='30374.9'
2023-07-06 00:10:01,186:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230705   232000    232959  1688570999  30309.4  30361.6  0.001706
573  20230705   233000    233959  1688571599  30361.6  30269.7 -0.003027
574  20230705   234000    234959  1688572199  30269.7  30314.5  0.001480
575  20230705   235000    235959  1688572799  30314.5    30345  0.001006
576  20230706   000000    000959  1688573399  30345.1  30374.9  0.000985
2023-07-06 00:10:01,188:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7569 

self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30375', self.close='30410.5'
127.0.0.1 - - [06/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-06 00:20:06,659:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30375', self.close='30410.5'
2023-07-06 00:20:07,290:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230705   233000    233959  1688571599  30361.6  30269.7 -0.003027
574  20230705   234000    234959  1688572199  30269.7  30314.5  0.001480
575  20230705   235000    235959  1688572799  30314.5    30345  0.001006
576  20230706   000000    000959  1688573399  30345.1  30374.9  0.000985
577  20230706   001000    001959  1688573999    30375  30410.5  0.001172
2023-07-06 00:20:07,290:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-06 00:00:02,103:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-06 00:00:02,175:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7060000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230705, closeTime:235959, close:30345, total:993267.8008712, pct_pre:-0.009284055265002533, thd:0.2952483373924045, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7571 

self.closeSec=1688573399, self.tradeDate='20230706', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30345.1', self.close='30374.9'
127.0.0.1 - - [06/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-06 00:10:01,176:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688573399, self.tradeDate='20230706', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30345.1', self.close='30374.9'
2023-07-06 00:10:01,191:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230705   232000    232959  1688570999  30309.4  30361.6
17421  20230705   233000    233959  1688571599  30361.6  30269.7
17422  20230705   234000    234959  1688572199  30269.7  30314.5
17423  20230705   235000    235959  1688572799  30314.5    30345
17424  20230706   000000    000959  1688573399  30345.1  30374.9
2023-07-06 00:10:01,191:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7572 

self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30375', self.close='30410.5'
127.0.0.1 - - [06/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-06 00:20:08,211:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30375', self.close='30410.5'
2023-07-06 00:20:08,363:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230705   233000    233959  1688571599  30361.6  30269.7
17422  20230705   234000    234959  1688572199  30269.7  30314.5
17423  20230705   235000    235959  1688572799  30314.5    30345
17424  20230706   000000    000959  1688573399  30345.1  30374.9
17425  20230706   001000    001959  1688573999    30375  30410.5
2023-07-06 00:20:08,364:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [06/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-06 00:00:04,463:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42536F1688572803719I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688572804083764, 'quantity': '36.791', 'price': '30345.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688572802754, 'updatetime': 1688572804083, 'tradetype': 'usdt', 'selfid': 42536, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688572804083, 'clientorderid': '42536F1688572803719I0L2', 'price': '30345.1', 'quantity': '36.791', 'commission': '1116.4265741', 'commissionasset': 'USDT', 'tradetime': 1688572804083, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688572804083}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7571 

self.closeSec=1688573399, self.tradeDate='20230706', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30345.1', self.close='30374.9'
2023-07-06 00:10:01,157:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688573399, self.tradeDate='20230706', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30345.1', self.close='30374.9'
2023-07-06 00:10:01,165:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230705   232000    232959  1688570999  30309.4  30361.6
12237  20230705   233000    233959  1688571599  30361.6  30269.7
12238  20230705   234000    234959  1688572199  30269.7  30314.5
12239  20230705   235000    235959  1688572799  30314.5    30345
12240  20230706   000000    000959  1688573399  30345.1  30374.9
2023-07-06 00:10:01,165:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7572 

self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30375', self.close='30410.5'
127.0.0.1 - - [06/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-06 00:20:07,934:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30375', self.close='30410.5'
2023-07-06 00:20:08,220:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230705   233000    233959  1688571599  30361.6  30269.7
12238  20230705   234000    234959  1688572199  30269.7  30314.5
12239  20230705   235000    235959  1688572799  30314.5    30345
12240  20230706   000000    000959  1688573399  30345.1  30374.9
12241  20230706   001000    001959  1688573999    30375  30410.5
2023-07-06 00:20:08,220:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15136
self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30373.6, self.close=30410.5, self.high=30420.0, self.low=30369.6, self.vol=1501.204, self.amt=45634872.7787 
127.0.0.1 - - [06/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-06 00:20:06,729:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230705   235500    235959  ...         0.0        0.0       0
5760  20230706   000000    000459  ...         0.0        0.0       0
5761  20230706   000500    000959  ...         0.0        0.0       0
5762  20230706   001000    001459  ...         0.0        0.0       0
5763  20230706   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 00:20:06,769:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688573999, self.tradeDate='20230706', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30373.6, self.close=30410.5, self.high=30420.0, self.low=30369.6, self.vol=1501.204, self.amt=45634872.7787, ukdf['pct'].iloc[-1]=0.001212 , ukdf['amount'].iloc[-1]=45634872.7787, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '132434.08884894149', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30409.71144689', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15137
self.closeSec=1688574299, self.tradeDate='20230706', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30410.5, self.close=30411.8, self.high=30420.0, self.low=30399.0, self.vol=939.405, self.amt=28566183.4676 
2023-07-06 00:25:00,811:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230706   000000    000459  ...         0.0        0.0       0
5761  20230706   000500    000959  ...         0.0        0.0       0
5762  20230706   001000    001459  ...         0.0        0.0       0
5763  20230706   001500    001959  ...         0.0        0.0       0
5764  20230706   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 00:25:00,811:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688574299, self.tradeDate='20230706', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30410.5, self.close=30411.8, self.high=30420.0, self.low=30399.0, self.vol=939.405, self.amt=28566183.4676, ukdf['pct'].iloc[-1]=4.3e-05 , ukdf['amount'].iloc[-1]=28566183.4676, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '132511.6598', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30411.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230705   120000    155959  1688543999  ...    723  0.702982  0.562522     NaN
724  20230705   160000    195959  1688558399  ...    724  0.548848  0.211732     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-19569.2570888875', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30382.01673725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [06/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=315
self.closeSec=1688572799, self.tradeDate='20230705', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30395.0, self.close=30345.0, self.high=30438.1, self.low=30175.8, self.vol=93102.558, self.amt=2823460306.67573 
2023-07-06 00:00:01,659:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688572799, self.tradeDate='20230705', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30395.0, self.close=30345.0, self.high=30438.1, self.low=30175.8, self.vol=93102.558, self.amt=2823460306.67573 
2023-07-06 00:00:01,688:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230705   040000    075959  ...  26150.576  8.044804e+08  0.002311
722  20230705   080000    115959  ...  18762.480  5.781087e+08  0.003284
723  20230705   120000    155959  ...  19242.008  5.926999e+08 -0.002959
724  20230705   160000    195959  ...  90362.983  2.760664e+09 -0.012056
725  20230705   200000    235959  ...  93102.558  2.823460e+09 -0.001645

[5 rows x 11 columns]
2023-07-06 00:00:03,116:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230705   040000    075959  1688515199  ...    721  0.847470  0.903770     1.0
722  20230705   080000    115959  1688529599  ...    722  0.783556  0.750836     1.0
723  20230705   120000    155959  1688543999  ...    723  0.702982  0.562522     NaN
724  20230705   160000    195959  1688558399  ...    724  0.548848  0.211732     NaN
725  20230705   200000    235959  1688572799  ...    725  0.568203  0.246937     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-21532.995', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30345', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


