# 20230731 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22336
self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29387.4, self.close=29363.3, self.high=29390.0, self.low=29362.3, self.vol=672.816, self.amt=19763142.4421 
127.0.0.1 - - [31/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-31 00:20:04,913:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230730   235500    235959  ...         0.0        0.0       0
5760  20230731   000000    000459  ...         0.0        0.0       0
5761  20230731   000500    000959  ...         0.0        0.0       0
5762  20230731   001000    001459  ...         0.0        0.0       0
5763  20230731   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 00:20:04,925:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29387.4, self.close=29363.3, self.high=29390.0, self.low=29362.3, self.vol=672.816, self.amt=19763142.4421, ukdf['pct'].iloc[-1]=-0.00082 , ukdf['amount'].iloc[-1]=19763142.4421, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34798.48529432814', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29363.71410989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22337
self.closeSec=1690734299, self.tradeDate='20230731', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29363.3, self.close=29359.9, self.high=29369.7, self.low=29357.7, self.vol=456.089, self.amt=13392525.4149 
127.0.0.1 - - [31/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-31 00:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230731   000000    000459  ...         0.0        0.0       0
5761  20230731   000500    000959  ...         0.0        0.0       0
5762  20230731   001000    001459  ...         0.0        0.0       0
5763  20230731   001500    001959  ...         0.0        0.0       0
5764  20230731   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 00:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690734299, self.tradeDate='20230731', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29363.3, self.close=29359.9, self.high=29369.7, self.low=29357.7, self.vol=456.089, self.amt=13392525.4149, ukdf['pct'].iloc[-1]=-0.000116 , ukdf['amount'].iloc[-1]=13392525.4149, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34745.37', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29359.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29387.4, self.close=29363.3, self.high=29390.0, self.low=29362.3 
127.0.0.1 - - [31/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-31 00:20:03,324:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29387.4, self.close=29363.3, self.high=29390.0, self.low=29362.3   
2023-07-31 00:20:04,275:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230730   235500    235959  1690732799  ...  29293.8  0.000263   1727    5
1440  20230731   000000    000459  1690733099  ...  29316.0 -0.000412   1440    0
1441  20230731   000500    000959  1690733399  ...  29325.0  0.002005   1441    1
1442  20230731   001000    001459  1690733699  ...  29380.5  0.000119   1442    2
1443  20230731   001500    001959  1690733999  ...  29362.3 -0.000820   1443    3

[5 rows x 11 columns]
2023-07-31 00:20:04,284:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [31/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5672213760738143, self.count=22339 

self.closeSec=1690734299, self.tradeDate='20230731', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29363.3, self.close=29359.9, self.high=29369.7, self.low=29357.7 
2023-07-31 00:25:00,763:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690734299, self.tradeDate='20230731', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29363.3, self.close=29359.9, self.high=29369.7, self.low=29357.7   
2023-07-31 00:25:00,777:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230731   000000    000459  1690733099  ...  29316.0 -0.000412   1440    0
1441  20230731   000500    000959  1690733399  ...  29325.0  0.002005   1441    1
1442  20230731   001000    001459  1690733699  ...  29380.5  0.000119   1442    2
1443  20230731   001500    001959  1690733999  ...  29362.3 -0.000820   1443    3
1444  20230731   002000    002459  1690734299  ...  29357.7 -0.000116   1444    4

[5 rows x 11 columns]
2023-07-31 00:25:00,777:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-31 00:00:19,777:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230730    212959  29307.3  ...  46.250000  0.495521  0.576271
5803  20230730    215959  29292.5  ...  45.833333  0.483903  0.578251
5804  20230730    222959  29273.4  ...  46.250000  0.496085  0.571892
5805  20230730    225959  29292.7  ...  46.666667  0.543932  0.549854
5806  20230730    232959  29377.2  ...  46.666667  0.560268  0.522679

[5 rows x 33 columns]
0.5790441176470589
acc is : 0.5790441176470589
2023-07-31 00:00:19,845:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.501654  0.498346       0  ...  0.928993   1.0    0.0  0.976297
540     0  0.501415  0.498585       1  ...  0.929609   1.0    0.0  0.976944
541     0  0.506578  0.493422       1  ...  0.932290   1.0    0.0  0.979763
542     0  0.528081  0.471919       1  ...  0.933319   1.0    0.0  0.980843
543     0  0.520568  0.479432       0  ...  0.931018   1.0    0.0  0.978425

[5 rows x 10 columns]
2023-07-31 00:00:19,861:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501569  0.498431       0  ...  0.928993   1.0    0.0  0.974704
46     0  0.501432  0.498568       1  ...  0.929609   1.0    0.0  0.975513
47     0  0.506582  0.493418       1  ...  0.932290   1.0    0.0  0.978327
48     0  0.527924  0.472076       1  ...  0.933319   1.0    0.0  0.979174
49     0  0.520568  0.479432       0  ...  0.931018   1.0    0.0  0.978425

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-3227.339', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29342.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [31/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-31 00:00:04,392:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42767F1690732803794I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690732804202752, 'quantity': '25.15', 'price': '29337.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690732802878, 'updatetime': 1690732804202, 'tradetype': 'usdt', 'selfid': 42767, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690732804202, 'clientorderid': '42767F1690732803794I0L59', 'price': '29337.2', 'quantity': '25.15', 'commission': '737.83058', 'commissionasset': 'USDT', 'tradetime': 1690732804202, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690732804202}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11168 

self.closeSec=1690733399, self.tradeDate='20230731', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29337.2', self.close='29383.9'
127.0.0.1 - - [31/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-31 00:10:01,169:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690733399, self.tradeDate='20230731', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29337.2', self.close='29383.9'
2023-07-31 00:10:01,177:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230730   232000    232959  1690730999    29400  29409.6  0.000330
573  20230730   233000    233959  1690731599  29409.7  29422.2  0.000428
574  20230730   234000    234959  1690732199  29422.2  29383.8 -0.001305
575  20230730   235000    235959  1690732799  29383.8  29337.1 -0.001589
576  20230731   000000    000959  1690733399  29337.2  29383.9  0.001595
2023-07-31 00:10:01,178:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11169 

self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29383.9', self.close='29363.3'
127.0.0.1 - - [31/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-31 00:20:05,895:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29383.9', self.close='29363.3'
2023-07-31 00:20:06,314:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230730   233000    233959  1690731599  29409.7  29422.2  0.000428
574  20230730   234000    234959  1690732199  29422.2  29383.8 -0.001305
575  20230730   235000    235959  1690732799  29383.8  29337.1 -0.001589
576  20230731   000000    000959  1690733399  29337.2  29383.9  0.001595
577  20230731   001000    001959  1690733999  29383.9  29363.3 -0.000701
2023-07-31 00:20:06,314:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-31 00:00:02,290:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-31 00:00:02,382:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7310000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230730, closeTime:235959, close:29337.1, total:996515.1559743, pct_pre:-0.0002561702883452366, thd:0.3369672023909254, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11171 

self.closeSec=1690733399, self.tradeDate='20230731', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29337.2', self.close='29383.9'
127.0.0.1 - - [31/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-31 00:10:01,183:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690733399, self.tradeDate='20230731', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29337.2', self.close='29383.9'
2023-07-31 00:10:01,190:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230730   232000    232959  1690730999    29400  29409.6
17421  20230730   233000    233959  1690731599  29409.7  29422.2
17422  20230730   234000    234959  1690732199  29422.2  29383.8
17423  20230730   235000    235959  1690732799  29383.8  29337.1
17424  20230731   000000    000959  1690733399  29337.2  29383.9
2023-07-31 00:10:01,190:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11172 

self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29383.9', self.close='29363.3'
127.0.0.1 - - [31/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-31 00:20:07,070:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29383.9', self.close='29363.3'
2023-07-31 00:20:07,152:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230730   233000    233959  1690731599  29409.7  29422.2
17422  20230730   234000    234959  1690732199  29422.2  29383.8
17423  20230730   235000    235959  1690732799  29383.8  29337.1
17424  20230731   000000    000959  1690733399  29337.2  29383.9
17425  20230731   001000    001959  1690733999  29383.9  29363.3
2023-07-31 00:20:07,153:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [31/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-31 00:00:04,491:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42768F1690732803823I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690732804220395, 'quantity': '37.021', 'price': '29337.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690732802933, 'updatetime': 1690732804220, 'tradetype': 'usdt', 'selfid': 42768, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690732804220, 'clientorderid': '42768F1690732803823I0L2', 'price': '29337.2', 'quantity': '37.021', 'commission': '1086.0924812', 'commissionasset': 'USDT', 'tradetime': 1690732804220, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690732804220}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11171 

self.closeSec=1690733399, self.tradeDate='20230731', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29337.2', self.close='29383.9'
2023-07-31 00:10:01,161:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690733399, self.tradeDate='20230731', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29337.2', self.close='29383.9'
2023-07-31 00:10:01,167:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230730   232000    232959  1690730999    29400  29409.6
12237  20230730   233000    233959  1690731599  29409.7  29422.2
12238  20230730   234000    234959  1690732199  29422.2  29383.8
12239  20230730   235000    235959  1690732799  29383.8  29337.1
12240  20230731   000000    000959  1690733399  29337.2  29383.9
2023-07-31 00:10:01,167:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11172 

self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29383.9', self.close='29363.3'
127.0.0.1 - - [31/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-31 00:20:06,935:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29383.9', self.close='29363.3'
2023-07-31 00:20:07,069:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230730   233000    233959  1690731599  29409.7  29422.2
12238  20230730   234000    234959  1690732199  29422.2  29383.8
12239  20230730   235000    235959  1690732799  29383.8  29337.1
12240  20230731   000000    000959  1690733399  29337.2  29383.9
12241  20230731   001000    001959  1690733999  29383.9  29363.3
2023-07-31 00:20:07,070:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22336
self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29387.4, self.close=29363.3, self.high=29390.0, self.low=29362.3, self.vol=672.816, self.amt=19763142.4421 
127.0.0.1 - - [31/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-31 00:20:04,913:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230730   235500    235959  ...         0.0        0.0       0
5760  20230731   000000    000459  ...         0.0        0.0       0
5761  20230731   000500    000959  ...         0.0        0.0       0
5762  20230731   001000    001459  ...         0.0        0.0       0
5763  20230731   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 00:20:04,934:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690733999, self.tradeDate='20230731', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29387.4, self.close=29363.3, self.high=29390.0, self.low=29362.3, self.vol=672.816, self.amt=19763142.4421, ukdf['pct'].iloc[-1]=-0.00082 , ukdf['amount'].iloc[-1]=19763142.4421, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '93584.70175542449', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29363.71410989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [31/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22337
self.closeSec=1690734299, self.tradeDate='20230731', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29363.3, self.close=29359.9, self.high=29369.7, self.low=29357.7, self.vol=456.089, self.amt=13392525.4149 
2023-07-31 00:25:00,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230731   000000    000459  ...         0.0        0.0       0
5761  20230731   000500    000959  ...         0.0        0.0       0
5762  20230731   001000    001459  ...         0.0        0.0       0
5763  20230731   001500    001959  ...         0.0        0.0       0
5764  20230731   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 00:25:00,790:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690734299, self.tradeDate='20230731', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29363.3, self.close=29359.9, self.high=29369.7, self.low=29357.7, self.vol=456.089, self.amt=13392525.4149, ukdf['pct'].iloc[-1]=-0.000116 , ukdf['amount'].iloc[-1]=13392525.4149, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '93443.0419', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29359.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230730   120000    155959  1690703999  ...    723  0.121428 -0.957668    -1.0
724  20230730   160000    195959  1690718399  ...    724  0.123511 -0.928860    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-2922.6984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29302.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=465
self.closeSec=1690732799, self.tradeDate='20230730', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29301.3, self.close=29337.1, self.high=29442.5, self.low=29260.0, self.vol=40656.643, self.amt=1193674542.3662 
127.0.0.1 - - [31/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-31 00:00:01,845:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690732799, self.tradeDate='20230730', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29301.3, self.close=29337.1, self.high=29442.5, self.low=29260.0, self.vol=40656.643, self.amt=1193674542.3662 
2023-07-31 00:00:01,891:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230730   040000    075959  ...   9865.259  2.895167e+08  0.000378
722  20230730   080000    115959  ...   9189.052  2.693709e+08 -0.001326
723  20230730   120000    155959  ...  11221.774  3.286130e+08 -0.000689
724  20230730   160000    195959  ...  20506.002  6.003079e+08  0.000727
725  20230730   200000    235959  ...  40656.643  1.193675e+09  0.001222

[5 rows x 11 columns]
2023-07-31 00:00:03,103:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230730   040000    075959  1690675199  ...    721  0.116313 -1.023235    -1.0
722  20230730   080000    115959  1690689599  ...    722  0.085739 -1.129026    -1.0
723  20230730   120000    155959  1690703999  ...    723  0.121428 -0.957668    -1.0
724  20230730   160000    195959  1690718399  ...    724  0.123511 -0.928860    -1.0
725  20230730   200000    235959  1690732799  ...    725  0.097821 -1.014500    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-4847.11421713608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29337.72149817', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


