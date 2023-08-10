# 20230811 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25504
self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29405.6, self.close=29393.1, self.high=29413.8, self.low=29390.0, self.vol=2092.034, self.amt=61505745.234 
127.0.0.1 - - [11/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-11 00:20:06,679:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230810   235500    235959  ...         0.0        0.0       0
5760  20230811   000000    000459  ...         0.0        0.0       0
5761  20230811   000500    000959  ...         0.0        0.0       0
5762  20230811   001000    001459  ...         0.0        0.0       0
5763  20230811   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 00:20:06,700:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29405.6, self.close=29393.1, self.high=29413.8, self.low=29390.0, self.vol=2092.034, self.amt=61505745.234, ukdf['pct'].iloc[-1]=-0.000428 , ukdf['amount'].iloc[-1]=61505745.234, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35191.74920899968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29391.95365568', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25505
self.closeSec=1691684699, self.tradeDate='20230811', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29393.0, self.close=29418.1, self.high=29436.6, self.low=29366.4, self.vol=2537.847, self.amt=74605942.7521 
127.0.0.1 - - [11/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-11 00:25:00,811:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230811   000000    000459  ...         0.0        0.0       0
5761  20230811   000500    000959  ...         0.0        0.0       0
5762  20230811   001000    001459  ...         0.0        0.0       0
5763  20230811   001500    001959  ...         0.0        0.0       0
5764  20230811   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 00:25:00,811:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691684699, self.tradeDate='20230811', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29393.0, self.close=29418.1, self.high=29436.6, self.low=29366.4, self.vol=2537.847, self.amt=74605942.7521, ukdf['pct'].iloc[-1]=0.000851 , ukdf['amount'].iloc[-1]=74605942.7521, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35633.7726150318', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29423.6945293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29405.6, self.close=29393.1, self.high=29413.8, self.low=29390.0 
127.0.0.1 - - [11/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-11 00:20:04,650:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29405.6, self.close=29393.1, self.high=29413.8, self.low=29390.0   
2023-08-11 00:20:05,949:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230810   235500    235959  1691683199  ...  29437.8  0.000268   1727    5
1440  20230811   000000    000459  1691683499  ...  29438.5  0.000160   1440    0
1441  20230811   000500    000959  1691683799  ...  29431.7 -0.000879   1441    1
1442  20230811   001000    001459  1691684099  ...  29405.6 -0.000883   1442    2
1443  20230811   001500    001959  1691684399  ...  29390.0 -0.000428   1443    3

[5 rows x 11 columns]
2023-08-11 00:20:05,950:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [11/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5799820215627224, self.count=25507 

self.closeSec=1691684699, self.tradeDate='20230811', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29393.0, self.close=29418.1, self.high=29436.6, self.low=29366.4 
2023-08-11 00:25:00,785:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691684699, self.tradeDate='20230811', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29393.0, self.close=29418.1, self.high=29436.6, self.low=29366.4   
2023-08-11 00:25:00,805:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230811   000000    000459  1691683499  ...  29438.5  0.000160   1440    0
1441  20230811   000500    000959  1691683799  ...  29431.7 -0.000879   1441    1
1442  20230811   001000    001459  1691684099  ...  29405.6 -0.000883   1442    2
1443  20230811   001500    001959  1691684399  ...  29390.0 -0.000428   1443    3
1444  20230811   002000    002459  1691684699  ...  29366.4  0.000851   1444    4

[5 rows x 11 columns]
2023-08-11 00:25:00,805:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-11 00:00:17,024:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230810    212959  29552.2  ...  51.250000  0.506525  0.664933
5803  20230810    215959  29575.9  ...  51.250000  0.530207  0.623722
5804  20230810    222959  29669.8  ...  50.833333  0.509631  0.607064
5805  20230810    225959  29592.3  ...  50.416667  0.482816  0.611218
5806  20230810    232959  29483.7  ...  50.416667  0.481224  0.616311

[5 rows x 33 columns]
0.5220588235294118
acc is : 0.5220588235294118
2023-08-11 00:00:17,083:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.507629  0.492371       1  ...  0.955219  -1.0    0.0  1.013313
540     0  0.535619  0.464381       0  ...  0.957715  -1.0    0.0  1.010666
541     1  0.487906  0.512094       0  ...  0.961232  -1.0    0.0  1.006954
542     1  0.464473  0.535527       0  ...  0.961451  -1.0    0.0  1.006725
543     1  0.490569  0.509431       0  ...  0.962234  -1.0    0.0  1.005905

[5 rows x 10 columns]
2023-08-11 00:00:17,094:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508023  0.491977       1  ...  0.955219  -1.0    0.0  1.014005
46     0  0.535628  0.464372       0  ...  0.957715  -1.0    0.0  1.010911
47     1  0.488142  0.511858       0  ...  0.961232  -1.0    0.0  1.007198
48     1  0.464642  0.535358       0  ...  0.961451  -1.0    0.0  1.007285
49     1  0.490569  0.509431       0  ...  0.962234  -1.0    0.0  1.005905

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '646.9181', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29452.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-11 00:00:04,390:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42841F1691683203677I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691683204117463, 'quantity': '24.549', 'price': '29452.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691683202781, 'updatetime': 1691683204117, 'tradetype': 'usdt', 'selfid': 42841, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691683204117, 'clientorderid': '42841F1691683203677I0L59', 'price': '29452.8', 'quantity': '24.549', 'commission': '723.0367872', 'commissionasset': 'USDT', 'tradetime': 1691683204117, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691683204117}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12752 

self.closeSec=1691683799, self.tradeDate='20230811', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29452.9', self.close='29431.7'
127.0.0.1 - - [11/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-11 00:10:01,133:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691683799, self.tradeDate='20230811', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29452.9', self.close='29431.7'
2023-08-11 00:10:01,147:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230810   232000    232959  1691681399  29463.5  29476.9  0.000438
573  20230810   233000    233959  1691681999  29476.9    29510  0.001123
574  20230810   234000    234959  1691682599  29509.9  29455.1 -0.001860
575  20230810   235000    235959  1691683199    29455  29452.8 -0.000078
576  20230811   000000    000959  1691683799  29452.9  29431.7 -0.000716
2023-08-11 00:10:01,148:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12753 

self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29431.6', self.close='29393.1'
127.0.0.1 - - [11/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-11 00:20:07,269:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29431.6', self.close='29393.1'
2023-08-11 00:20:07,779:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230810   233000    233959  1691681999  29476.9    29510  0.001123
574  20230810   234000    234959  1691682599  29509.9  29455.1 -0.001860
575  20230810   235000    235959  1691683199    29455  29452.8 -0.000078
576  20230811   000000    000959  1691683799  29452.9  29431.7 -0.000716
577  20230811   001000    001959  1691684399  29431.6  29393.1 -0.001312
2023-08-11 00:20:07,780:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-11 00:00:02,255:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-11 00:00:02,326:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8110000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230810, closeTime:235959, close:29452.8, total:977345.2184116, pct_pre:-0.006440237689859241, thd:0.3712887248823299, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12755 

self.closeSec=1691683799, self.tradeDate='20230811', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29452.9', self.close='29431.7'
2023-08-11 00:10:01,126:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691683799, self.tradeDate='20230811', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29452.9', self.close='29431.7'
127.0.0.1 - - [11/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-11 00:10:01,133:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230810   232000    232959  1691681399  29463.5  29476.9
17421  20230810   233000    233959  1691681999  29476.9    29510
17422  20230810   234000    234959  1691682599  29509.9  29455.1
17423  20230810   235000    235959  1691683199    29455  29452.8
17424  20230811   000000    000959  1691683799  29452.9  29431.7
2023-08-11 00:10:01,133:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12756 

self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29431.6', self.close='29393.1'
127.0.0.1 - - [11/Aug/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-08-11 00:20:08,782:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29431.6', self.close='29393.1'
2023-08-11 00:20:08,884:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230810   233000    233959  1691681999  29476.9    29510
17422  20230810   234000    234959  1691682599  29509.9  29455.1
17423  20230810   235000    235959  1691683199    29455  29452.8
17424  20230811   000000    000959  1691683799  29452.9  29431.7
17425  20230811   001000    001959  1691684399  29431.6  29393.1
2023-08-11 00:20:08,884:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [11/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-11 00:00:04,276:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42842F1691683203704I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691683204106249, 'quantity': '36.59', 'price': '29452.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691683202808, 'updatetime': 1691683204106, 'tradetype': 'usdt', 'selfid': 42842, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691683204106, 'clientorderid': '42842F1691683203704I0L2', 'price': '29452.8', 'quantity': '36.59', 'commission': '1077.677952', 'commissionasset': 'USDT', 'tradetime': 1691683204106, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691683204106}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12755 

self.closeSec=1691683799, self.tradeDate='20230811', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29452.9', self.close='29431.7'
2023-08-11 00:10:01,115:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691683799, self.tradeDate='20230811', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29452.9', self.close='29431.7'
2023-08-11 00:10:01,125:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230810   232000    232959  1691681399  29463.5  29476.9
12237  20230810   233000    233959  1691681999  29476.9    29510
12238  20230810   234000    234959  1691682599  29509.9  29455.1
12239  20230810   235000    235959  1691683199    29455  29452.8
12240  20230811   000000    000959  1691683799  29452.9  29431.7
2023-08-11 00:10:01,125:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12756 

self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29431.6', self.close='29393.1'
127.0.0.1 - - [11/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-11 00:20:08,620:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29431.6', self.close='29393.1'
2023-08-11 00:20:08,772:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230810   233000    233959  1691681999  29476.9    29510
12238  20230810   234000    234959  1691682599  29509.9  29455.1
12239  20230810   235000    235959  1691683199    29455  29452.8
12240  20230811   000000    000959  1691683799  29452.9  29431.7
12241  20230811   001000    001959  1691684399  29431.6  29393.1
2023-08-11 00:20:08,779:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25504
self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29405.6, self.close=29393.1, self.high=29413.8, self.low=29390.0, self.vol=2092.034, self.amt=61505745.234 
127.0.0.1 - - [11/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-11 00:20:06,689:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230810   235500    235959  ...         0.0        0.0       0
5760  20230811   000000    000459  ...         0.0        0.0       0
5761  20230811   000500    000959  ...         0.0        0.0       0
5762  20230811   001000    001459  ...         0.0        0.0       0
5763  20230811   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 00:20:06,711:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691684399, self.tradeDate='20230811', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29405.6, self.close=29393.1, self.high=29413.8, self.low=29390.0, self.vol=2092.034, self.amt=61505745.234, ukdf['pct'].iloc[-1]=-0.000428 , ukdf['amount'].iloc[-1]=61505745.234, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '94633.54672561088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29391.95365568', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [11/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25505
self.closeSec=1691684699, self.tradeDate='20230811', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29393.0, self.close=29418.1, self.high=29436.6, self.low=29366.4, self.vol=2537.847, self.amt=74605942.7521 
2023-08-11 00:25:00,816:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230811   000000    000459  ...         0.0        0.0       0
5761  20230811   000500    000959  ...         0.0        0.0       0
5762  20230811   001000    001459  ...         0.0        0.0       0
5763  20230811   001500    001959  ...         0.0        0.0       0
5764  20230811   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 00:25:00,816:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691684699, self.tradeDate='20230811', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29393.0, self.close=29418.1, self.high=29436.6, self.low=29366.4, self.vol=2537.847, self.amt=74605942.7521, ukdf['pct'].iloc[-1]=0.000851 , ukdf['amount'].iloc[-1]=74605942.7521, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '95812.4345127313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29423.6945293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230810   120000    155959  1691654399  ...    723  1.035430  1.920660     1.0
724  20230810   160000    195959  1691668799  ...    724  0.966686  1.680627     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-20195.64629667081', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29491.92382967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [11/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=531
self.closeSec=1691683199, self.tradeDate='20230810', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29490.0, self.close=29452.8, self.high=29729.8, self.low=29380.0, self.vol=101443.007, self.amt=2997257912.2473 
2023-08-11 00:00:01,834:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691683199, self.tradeDate='20230810', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29490.0, self.close=29452.8, self.high=29729.8, self.low=29380.0, self.vol=101443.007, self.amt=2997257912.2473 
2023-08-11 00:00:01,857:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230810   040000    075959  ...   37603.980  1.109496e+09  0.005734
722  20230810   080000    115959  ...   26398.656  7.812642e+08 -0.000128
723  20230810   120000    155959  ...   26122.949  7.715556e+08 -0.002198
724  20230810   160000    195959  ...   21083.327  6.221257e+08 -0.000475
725  20230810   200000    235959  ...  101443.007  2.997258e+09 -0.001261

[5 rows x 11 columns]
2023-08-11 00:00:02,583:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230810   040000    075959  1691625599  ...    721  1.191976  2.528315     1.0
722  20230810   080000    115959  1691639999  ...    722  1.098015  2.162763     1.0
723  20230810   120000    155959  1691654399  ...    723  1.035430  1.920660     1.0
724  20230810   160000    195959  1691668799  ...    724  0.966686  1.680627     1.0
725  20230810   200000    235959  1691683199  ...    725  0.947260  1.593051     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-22208.8412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29452.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


