# 20230803 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23200
self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29305.1, self.close=29262.0, self.high=29307.2, self.low=29254.2, self.vol=2425.024, self.amt=71011431.64 
127.0.0.1 - - [03/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-03 00:20:05,471:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230802   235500    235959  ...         0.0        0.0       0
5760  20230803   000000    000459  ...         0.0        0.0       0
5761  20230803   000500    000959  ...         0.0        0.0       0
5762  20230803   001000    001459  ...         0.0        0.0       0
5763  20230803   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 00:20:05,493:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29305.1, self.close=29262.0, self.high=29307.2, self.low=29254.2, self.vol=2425.024, self.amt=71011431.64, ukdf['pct'].iloc[-1]=-0.001474 , ukdf['amount'].iloc[-1]=71011431.64, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33447.2514316248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29266.6845348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23201
self.closeSec=1690993499, self.tradeDate='20230803', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29262.0, self.close=29252.9, self.high=29270.0, self.low=29239.9, self.vol=1279.219, self.amt=37421725.2345 
127.0.0.1 - - [03/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-03 00:25:00,827:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230803   000000    000459  ...         0.0        0.0       0
5761  20230803   000500    000959  ...         0.0        0.0       0
5762  20230803   001000    001459  ...         0.0        0.0       0
5763  20230803   001500    001959  ...         0.0        0.0       0
5764  20230803   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 00:25:00,827:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690993499, self.tradeDate='20230803', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29262.0, self.close=29252.9, self.high=29270.0, self.low=29239.9, self.vol=1279.219, self.amt=37421725.2345, ukdf['pct'].iloc[-1]=-0.000311 , ukdf['amount'].iloc[-1]=37421725.2345, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33262.251', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29253.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29305.1, self.close=29262.0, self.high=29307.2, self.low=29254.2 
127.0.0.1 - - [03/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-03 00:20:03,660:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29305.1, self.close=29262.0, self.high=29307.2, self.low=29254.2   
2023-08-03 00:20:04,831:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230802   235500    235959  1690991999  ...  29312.0 -0.000488   1727    5
1440  20230803   000000    000459  1690992299  ...  29279.0  0.000051   1440    0
1441  20230803   000500    000959  1690992599  ...  29313.9  0.000283   1441    1
1442  20230803   001000    001459  1690992899  ...  29280.7 -0.000583   1442    2
1443  20230803   001500    001959  1690993199  ...  29254.2 -0.001474   1443    3

[5 rows x 11 columns]
2023-08-03 00:20:04,842:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=38, self.factor=0.47332766251539643, self.count=23203 

self.closeSec=1690993499, self.tradeDate='20230803', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29262.0, self.close=29252.9, self.high=29270.0, self.low=29239.9 
127.0.0.1 - - [03/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-03 00:25:00,806:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690993499, self.tradeDate='20230803', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29262.0, self.close=29252.9, self.high=29270.0, self.low=29239.9   
2023-08-03 00:25:00,833:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230803   000000    000459  1690992299  ...  29279.0  0.000051   1440    0
1441  20230803   000500    000959  1690992599  ...  29313.9  0.000283   1441    1
1442  20230803   001000    001459  1690992899  ...  29280.7 -0.000583   1442    2
1443  20230803   001500    001959  1690993199  ...  29254.2 -0.001474   1443    3
1444  20230803   002000    002459  1690993499  ...  29239.9 -0.000311   1444    4

[5 rows x 11 columns]
2023-08-03 00:25:00,833:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-03 00:00:16,941:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230802    212959  29451.0  ...  44.583333  0.513050  0.361625
5803  20230802    215959  29396.0  ...  45.000000  0.514348  0.376698
5804  20230802    222959  29402.7  ...  44.583333  0.492951  0.403903
5805  20230802    225959  29298.9  ...  44.166667  0.485910  0.436638
5806  20230802    232959  29263.0  ...  44.583333  0.491479  0.464305

[5 rows x 33 columns]
0.5625
acc is : 0.5625
2023-08-03 00:00:16,999:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.483668  0.516332       1  ...  0.974638  -1.0    0.0  0.982280
540     0  0.500240  0.499760       0  ...  0.978076  -1.0    0.0  0.978816
541     1  0.463720  0.536280       0  ...  0.979258  -1.0    0.0  0.977633
542     1  0.482135  0.517865       1  ...  0.978367  -1.0    0.0  0.978522
543     0  0.508154  0.491846       1  ...  0.977619  -1.0    0.0  0.979270

[5 rows x 10 columns]
2023-08-03 00:00:17,010:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483866  0.516134       1  ...  0.974638  -1.0    0.0  0.984560
46     0  0.500310  0.499690       0  ...  0.978076  -1.0    0.0  0.980749
47     1  0.464086  0.535914       0  ...  0.979258  -1.0    0.0  0.979564
48     1  0.482242  0.517758       1  ...  0.978367  -1.0    0.0  0.979347
49     0  0.508154  0.491846       1  ...  0.977619  -1.0    0.0  0.979270

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.243', 'enterprice': '29666', 'countrevence': '0', 'unrealprofit': '8441.8576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29302.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [03/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-03 00:00:04,180:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42789F1690992003556I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690992003976319, 'quantity': '24.809', 'price': '29312.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690992002681, 'updatetime': 1690992003976, 'tradetype': 'usdt', 'selfid': 42789, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690992003976, 'clientorderid': '42789F1690992003556I0L59', 'price': '29312.4', 'quantity': '24.809', 'commission': '727.2113316', 'commissionasset': 'USDT', 'tradetime': 1690992003976, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690992003976}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11600 

self.closeSec=1690992599, self.tradeDate='20230803', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29312.5', self.close='29322.3'
2023-08-03 00:10:01,133:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690992599, self.tradeDate='20230803', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29312.5', self.close='29322.3'
2023-08-03 00:10:01,153:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230802   232000    232959  1690990199  29200.8  29291.7  0.003072
573  20230802   233000    233959  1690990799  29291.6  29330.8  0.001335
574  20230802   234000    234959  1690991399  29330.8    29316 -0.000505
575  20230802   235000    235959  1690991999    29316  29312.6 -0.000116
576  20230803   000000    000959  1690992599  29312.5  29322.3  0.000331
2023-08-03 00:10:01,154:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11601 

self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29322.3', self.close='29262'
127.0.0.1 - - [03/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-03 00:20:06,230:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29322.3', self.close='29262'
2023-08-03 00:20:06,611:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230802   233000    233959  1690990799  29291.6  29330.8  0.001335
574  20230802   234000    234959  1690991399  29330.8    29316 -0.000505
575  20230802   235000    235959  1690991999    29316  29312.6 -0.000116
576  20230803   000000    000959  1690992599  29312.5  29322.3  0.000331
577  20230803   001000    001959  1690993199  29322.3    29262 -0.002056
2023-08-03 00:20:06,611:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-03 00:00:03,983:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42788F1690992003412I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690992003830830, 'quantity': '33.811', 'price': '29312.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690992002565, 'updatetime': 1690992003830, 'tradetype': 'usdt', 'selfid': 42788, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690992003830, 'clientorderid': '42788F1690992003412I0L57', 'price': '29312.4', 'quantity': '33.811', 'commission': '991.0815564', 'commissionasset': 'USDT', 'tradetime': 1690992003830, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690992003830}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Aug/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11603 

self.closeSec=1690992599, self.tradeDate='20230803', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29312.5', self.close='29322.3'
2023-08-03 00:10:01,144:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690992599, self.tradeDate='20230803', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29312.5', self.close='29322.3'
2023-08-03 00:10:01,165:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230802   232000    232959  1690990199  29200.8  29291.7
17421  20230802   233000    233959  1690990799  29291.6  29330.8
17422  20230802   234000    234959  1690991399  29330.8    29316
17423  20230802   235000    235959  1690991999    29316  29312.6
17424  20230803   000000    000959  1690992599  29312.5  29322.3
2023-08-03 00:10:01,165:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11604 

self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29322.3', self.close='29262'
127.0.0.1 - - [03/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-03 00:20:07,463:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29322.3', self.close='29262'
2023-08-03 00:20:07,529:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230802   233000    233959  1690990799  29291.6  29330.8
17422  20230802   234000    234959  1690991399  29330.8    29316
17423  20230802   235000    235959  1690991999    29316  29312.6
17424  20230803   000000    000959  1690992599  29312.5  29322.3
17425  20230803   001000    001959  1690993199  29322.3    29262
2023-08-03 00:20:07,529:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [03/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-03 00:00:04,303:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42790F1690992003602I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690992004040621, 'quantity': '37.25', 'price': '29312.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690992002655, 'updatetime': 1690992004040, 'tradetype': 'usdt', 'selfid': 42790, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690992004040, 'clientorderid': '42790F1690992003602I0L2', 'price': '29312.5', 'quantity': '37.25', 'commission': '1091.890625', 'commissionasset': 'USDT', 'tradetime': 1690992004040, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690992004040}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11603 

self.closeSec=1690992599, self.tradeDate='20230803', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29312.5', self.close='29322.3'
2023-08-03 00:10:01,136:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690992599, self.tradeDate='20230803', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29312.5', self.close='29322.3'
2023-08-03 00:10:01,158:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230802   232000    232959  1690990199  29200.8  29291.7
12237  20230802   233000    233959  1690990799  29291.6  29330.8
12238  20230802   234000    234959  1690991399  29330.8    29316
12239  20230802   235000    235959  1690991999    29316  29312.6
12240  20230803   000000    000959  1690992599  29312.5  29322.3
2023-08-03 00:10:01,158:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11604 

self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29322.3', self.close='29262'
127.0.0.1 - - [03/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-03 00:20:07,314:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29322.3', self.close='29262'
2023-08-03 00:20:07,468:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230802   233000    233959  1690990799  29291.6  29330.8
12238  20230802   234000    234959  1690991399  29330.8    29316
12239  20230802   235000    235959  1690991999    29316  29312.6
12240  20230803   000000    000959  1690992599  29312.5  29322.3
12241  20230803   001000    001959  1690993199  29322.3    29262
2023-08-03 00:20:07,469:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23200
self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29305.1, self.close=29262.0, self.high=29307.2, self.low=29254.2, self.vol=2425.024, self.amt=71011431.64 
127.0.0.1 - - [03/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-03 00:20:05,351:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230802   235500    235959  ...         0.0        0.0       0
5760  20230803   000000    000459  ...         0.0        0.0       0
5761  20230803   000500    000959  ...         0.0        0.0       0
5762  20230803   001000    001459  ...         0.0        0.0       0
5763  20230803   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 00:20:05,362:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690993199, self.tradeDate='20230803', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29305.1, self.close=29262.0, self.high=29307.2, self.low=29254.2, self.vol=2425.024, self.amt=71011431.64, ukdf['pct'].iloc[-1]=-0.001474 , ukdf['amount'].iloc[-1]=71011431.64, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '89980.9263070068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29266.6845348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23201
self.closeSec=1690993499, self.tradeDate='20230803', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29262.0, self.close=29252.9, self.high=29270.0, self.low=29239.9, self.vol=1279.219, self.amt=37421725.2345 
127.0.0.1 - - [03/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-03 00:25:00,843:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230803   000000    000459  ...         0.0        0.0       0
5761  20230803   000500    000959  ...         0.0        0.0       0
5762  20230803   001000    001459  ...         0.0        0.0       0
5763  20230803   001500    001959  ...         0.0        0.0       0
5764  20230803   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 00:25:00,844:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690993499, self.tradeDate='20230803', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29262.0, self.close=29252.9, self.high=29270.0, self.low=29239.9, self.vol=1279.219, self.amt=37421725.2345, ukdf['pct'].iloc[-1]=-0.000311 , ukdf['amount'].iloc[-1]=37421725.2345, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '89487.5254', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29253.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230802   120000    155959  1690963199  ...    723  0.275701  0.170171     NaN
724  20230802   160000    195959  1690977599  ...    724  0.291438  0.247200     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-16471.9176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29552.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [03/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=483
self.closeSec=1690991999, self.tradeDate='20230802', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29552.8, self.close=29312.5, self.high=29599.0, self.low=29156.0, self.vol=97917.578, self.amt=2873898798.03272 
2023-08-03 00:00:01,681:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690991999, self.tradeDate='20230802', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29552.8, self.close=29312.5, self.high=29599.0, self.low=29156.0, self.vol=97917.578, self.amt=2873898798.03272 
2023-08-03 00:00:01,694:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230802   040000    075959  ...   97454.977  2.867119e+09  0.014957
722  20230802   080000    115959  ...  133633.098  3.982644e+09 -0.002650
723  20230802   120000    155959  ...   45298.470  1.341810e+09 -0.001769
724  20230802   160000    195959  ...   75164.964  2.215702e+09 -0.000582
725  20230802   200000    235959  ...   97917.578  2.873899e+09 -0.008135

[5 rows x 11 columns]
2023-08-03 00:00:02,494:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230802   040000    075959  1690934399  ...    721  0.106051 -0.705412    -1.0
722  20230802   080000    115959  1690948799  ...    722  0.232552 -0.054862     NaN
723  20230802   120000    155959  1690963199  ...    723  0.275701  0.170171     NaN
724  20230802   160000    195959  1690977599  ...    724  0.291438  0.247200     NaN
725  20230802   200000    235959  1690991999  ...    725  0.292143  0.241824     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-3479.1456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29312.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


