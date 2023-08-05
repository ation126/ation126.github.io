# 20230806 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24064
self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29039.9, self.close=29024.0, self.high=29040.0, self.low=29024.0, self.vol=294.108, self.amt=8538468.3671 
127.0.0.1 - - [06/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-06 00:20:06,811:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230805   235500    235959  ...         0.0        0.0       0
5760  20230806   000000    000459  ...         0.0        0.0       0
5761  20230806   000500    000959  ...         0.0        0.0       0
5762  20230806   001000    001459  ...         0.0        0.0       0
5763  20230806   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 00:20:06,832:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29039.9, self.close=29024.0, self.high=29040.0, self.low=29024.0, self.vol=294.108, self.amt=8538468.3671, ukdf['pct'].iloc[-1]=-0.000548 , ukdf['amount'].iloc[-1]=8538468.3671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30094.30912209348', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29025.91602198', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24065
self.closeSec=1691252699, self.tradeDate='20230806', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29024.0, self.close=29018.9, self.high=29024.1, self.low=29015.6, self.vol=233.106, self.amt=6764447.3613 
127.0.0.1 - - [06/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-06 00:25:00,775:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230806   000000    000459  ...         0.0        0.0       0
5761  20230806   000500    000959  ...         0.0        0.0       0
5762  20230806   001000    001459  ...         0.0        0.0       0
5763  20230806   001500    001959  ...         0.0        0.0       0
5764  20230806   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 00:25:00,775:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691252699, self.tradeDate='20230806', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29024.0, self.close=29018.9, self.high=29024.1, self.low=29015.6, self.vol=233.106, self.amt=6764447.3613, ukdf['pct'].iloc[-1]=-0.000176 , ukdf['amount'].iloc[-1]=6764447.3613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-29997.9966', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29019', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29039.9, self.close=29024.0, self.high=29040.0, self.low=29024.0 
127.0.0.1 - - [06/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-06 00:20:04,681:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29039.9, self.close=29024.0, self.high=29040.0, self.low=29024.0   
2023-08-06 00:20:05,871:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230805   235500    235959  1691251199  ...  29026.0  0.000138   1727    5
1440  20230806   000000    000459  1691251499  ...  29032.4  0.000007   1440    0
1441  20230806   000500    000959  1691251799  ...  29030.9 -0.000062   1441    1
1442  20230806   001000    001459  1691252099  ...  29030.9  0.000310   1442    2
1443  20230806   001500    001959  1691252399  ...  29024.0 -0.000548   1443    3

[5 rows x 11 columns]
2023-08-06 00:20:05,872:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=59, self.factor=0.5694599715847611, self.count=24067 

self.closeSec=1691252699, self.tradeDate='20230806', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29024.0, self.close=29018.9, self.high=29024.1, self.low=29015.6 
2023-08-06 00:25:00,764:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691252699, self.tradeDate='20230806', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29024.0, self.close=29018.9, self.high=29024.1, self.low=29015.6   
2023-08-06 00:25:00,781:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230806   000000    000459  1691251499  ...  29032.4  0.000007   1440    0
1441  20230806   000500    000959  1691251799  ...  29030.9 -0.000062   1441    1
1442  20230806   001000    001459  1691252099  ...  29030.9  0.000310   1442    2
1443  20230806   001500    001959  1691252399  ...  29024.0 -0.000548   1443    3
1444  20230806   002000    002459  1691252699  ...  29015.6 -0.000176   1444    4

[5 rows x 11 columns]
2023-08-06 00:25:00,781:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-06 00:00:18,197:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230805    212959  29004.0  ...  45.416667  0.453147  0.489079
5803  20230805    215959  29012.0  ...  45.833333  0.455108  0.484513
5804  20230805    222959  29016.5  ...  46.250000  0.473544  0.468011
5805  20230805    225959  29058.5  ...  46.666667  0.473717  0.452537
5806  20230805    232959  29059.0  ...  46.666667  0.455686  0.446733

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-08-06 00:00:18,257:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.498571  0.501429       1  ...  0.982590   1.0    0.0  0.996022
540     1  0.496426  0.503574       1  ...  0.984016   1.0    0.0  0.997467
541     0  0.510749  0.489251       0  ...  0.984029   1.0    0.0  0.997480
542     0  0.502993  0.497007       0  ...  0.982428   1.0    0.0  0.995857
543     1  0.488019  0.511981       1  ...  0.983132   1.0    0.0  0.996571

[5 rows x 10 columns]
2023-08-06 00:00:18,270:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498382  0.501618       1  ...  0.982590   1.0    0.0  0.995919
46     1  0.496422  0.503578       1  ...  0.984016   1.0    0.0  0.997484
47     0  0.510739  0.489261       1  ...  0.984029   1.0    0.0  0.997498
48     0  0.502847  0.497153       0  ...  0.982428   1.0    0.0  0.995317
49     1  0.488019  0.511981       1  ...  0.983132   1.0    0.0  0.996571

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-2381.94', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29032.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [06/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-06 00:00:04,300:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42808F1691251203747I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691251204157443, 'quantity': '24.948', 'price': '29032.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691251202884, 'updatetime': 1691251204157, 'tradetype': 'usdt', 'selfid': 42808, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691251204157, 'clientorderid': '42808F1691251203747I0L59', 'price': '29032.5', 'quantity': '24.948', 'commission': '724.30281', 'commissionasset': 'USDT', 'tradetime': 1691251204157, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691251204157}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12032 

self.closeSec=1691251799, self.tradeDate='20230806', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29032.5', self.close='29031'
2023-08-06 00:10:01,159:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691251799, self.tradeDate='20230806', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29032.5', self.close='29031'
2023-08-06 00:10:01,178:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230805   232000    232959  1691249399  29025.9  29011.6 -0.000493
573  20230805   233000    233959  1691249999  29011.6  29021.2  0.000331
574  20230805   234000    234959  1691250599  29021.3    29024  0.000096
575  20230805   235000    235959  1691251199    29024  29032.4  0.000289
576  20230806   000000    000959  1691251799  29032.5    29031 -0.000048
2023-08-06 00:10:01,178:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12033 

self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29031', self.close='29024'
127.0.0.1 - - [06/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-06 00:20:07,312:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29031', self.close='29024'
2023-08-06 00:20:07,880:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230805   233000    233959  1691249999  29011.6  29021.2  0.000331
574  20230805   234000    234959  1691250599  29021.3    29024  0.000096
575  20230805   235000    235959  1691251199    29024  29032.4  0.000289
576  20230806   000000    000959  1691251799  29032.5    29031 -0.000048
577  20230806   001000    001959  1691252399    29031    29024 -0.000241
2023-08-06 00:20:07,880:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-06 00:00:02,356:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-06 00:00:02,420:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8060000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230805, closeTime:235959, close:29032.4, total:991132.0255179, pct_pre:-0.0065529365090222225, thd:0.2917440943687657, side:sell 
127.0.0.1 - - [06/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12035 

self.closeSec=1691251799, self.tradeDate='20230806', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29032.5', self.close='29031'
2023-08-06 00:10:01,162:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691251799, self.tradeDate='20230806', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29032.5', self.close='29031'
2023-08-06 00:10:01,169:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230805   232000    232959  1691249399  29025.9  29011.6
17421  20230805   233000    233959  1691249999  29011.6  29021.2
17422  20230805   234000    234959  1691250599  29021.3    29024
17423  20230805   235000    235959  1691251199    29024  29032.4
17424  20230806   000000    000959  1691251799  29032.5    29031
2023-08-06 00:10:01,169:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12036 

self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29031', self.close='29024'
127.0.0.1 - - [06/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-06 00:20:09,091:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29031', self.close='29024'
2023-08-06 00:20:09,166:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230805   233000    233959  1691249999  29011.6  29021.2
17422  20230805   234000    234959  1691250599  29021.3    29024
17423  20230805   235000    235959  1691251199    29024  29032.4
17424  20230806   000000    000959  1691251799  29032.5    29031
17425  20230806   001000    001959  1691252399    29031    29024
2023-08-06 00:20:09,166:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [06/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-06 00:00:04,446:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42809F1691251203796I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691251204238099, 'quantity': '37.441', 'price': '29032.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691251202922, 'updatetime': 1691251204238, 'tradetype': 'usdt', 'selfid': 42809, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691251204238, 'clientorderid': '42809F1691251203796I0L2', 'price': '29032.4', 'quantity': '37.441', 'commission': '1087.0020884', 'commissionasset': 'USDT', 'tradetime': 1691251204238, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691251204238}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12035 

self.closeSec=1691251799, self.tradeDate='20230806', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29032.5', self.close='29031'
127.0.0.1 - - [06/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-06 00:10:01,170:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691251799, self.tradeDate='20230806', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29032.5', self.close='29031'
2023-08-06 00:10:01,182:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230805   232000    232959  1691249399  29025.9  29011.6
12237  20230805   233000    233959  1691249999  29011.6  29021.2
12238  20230805   234000    234959  1691250599  29021.3    29024
12239  20230805   235000    235959  1691251199    29024  29032.4
12240  20230806   000000    000959  1691251799  29032.5    29031
2023-08-06 00:10:01,182:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12036 

self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29031', self.close='29024'
127.0.0.1 - - [06/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-06 00:20:08,923:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29031', self.close='29024'
2023-08-06 00:20:09,081:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230805   233000    233959  1691249999  29011.6  29021.2
12238  20230805   234000    234959  1691250599  29021.3    29024
12239  20230805   235000    235959  1691251199    29024  29032.4
12240  20230806   000000    000959  1691251799  29032.5    29031
12241  20230806   001000    001959  1691252399    29031    29024
2023-08-06 00:20:09,081:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24064
self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29039.9, self.close=29024.0, self.high=29040.0, self.low=29024.0, self.vol=294.108, self.amt=8538468.3671 
127.0.0.1 - - [06/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-06 00:20:06,832:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230805   235500    235959  ...         0.0        0.0       0
5760  20230806   000000    000459  ...         0.0        0.0       0
5761  20230806   000500    000959  ...         0.0        0.0       0
5762  20230806   001000    001459  ...         0.0        0.0       0
5763  20230806   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 00:20:06,862:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691252399, self.tradeDate='20230806', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29039.9, self.close=29024.0, self.high=29040.0, self.low=29024.0, self.vol=294.108, self.amt=8538468.3671, ukdf['pct'].iloc[-1]=-0.000548 , ukdf['amount'].iloc[-1]=8538468.3671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '81038.54297235918', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29025.91602198', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24065
self.closeSec=1691252699, self.tradeDate='20230806', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29024.0, self.close=29018.9, self.high=29024.1, self.low=29015.6, self.vol=233.106, self.amt=6764447.3613 
2023-08-06 00:25:00,764:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230806   000000    000459  ...         0.0        0.0       0
5761  20230806   000500    000959  ...         0.0        0.0       0
5762  20230806   001000    001459  ...         0.0        0.0       0
5763  20230806   001500    001959  ...         0.0        0.0       0
5764  20230806   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-06 00:25:00,764:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691252699, self.tradeDate='20230806', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29024.0, self.close=29018.9, self.high=29024.1, self.low=29015.6, self.vol=233.106, self.amt=6764447.3613, ukdf['pct'].iloc[-1]=-0.000176 , ukdf['amount'].iloc[-1]=6764447.3613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '80781.675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29019', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230805   120000    155959  1691222399  ...    723  0.636616  1.699703     1.0
724  20230805   160000    195959  1691236799  ...    724  0.581010  1.392646     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '312.2175', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29040.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [06/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1588790.78883, self.flagDict['side']='buy', self.tradeCount=17, self.count=501
self.closeSec=1691251199, self.tradeDate='20230805', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29040.6, self.close=29032.4, self.high=29072.9, self.low=28960.0, self.vol=25947.755, self.amt=752970051.4332 
2023-08-06 00:00:01,910:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691251199, self.tradeDate='20230805', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29040.6, self.close=29032.4, self.high=29072.9, self.low=28960.0, self.vol=25947.755, self.amt=752970051.4332 
2023-08-06 00:00:01,924:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230805   040000    075959  ...  48349.502  1.401817e+09  0.002760
722  20230805   080000    115959  ...  15877.382  4.618873e+08 -0.000636
723  20230805   120000    155959  ...  11796.275  3.427467e+08 -0.001537
724  20230805   160000    195959  ...  10686.415  3.104955e+08  0.000093
725  20230805   200000    235959  ...  25947.755  7.529701e+08 -0.000282

[5 rows x 11 columns]
2023-08-06 00:00:02,696:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230805   040000    075959  1691193599  ...    721  0.470379  0.946624     1.0
722  20230805   080000    115959  1691207999  ...    722  0.466129  0.905948     1.0
723  20230805   120000    155959  1691222399  ...    723  0.636616  1.699703     1.0
724  20230805   160000    195959  1691236799  ...    724  0.581010  1.392646     1.0
725  20230805   200000    235959  1691251199  ...    725  0.554096  1.233047     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '-131.46', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29032.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


