# 20230523 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2464
self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26894.5, self.close=26873.9, self.high=26899.4, self.low=26873.9, self.vol=851.95, self.amt=22903007.863 
127.0.0.1 - - [23/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-23 00:20:05,895:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230522   235500    235959  ...    0.213020   0.314176       0
5760  20230523   000000    000459  ...    0.212839   0.314111       0
5761  20230523   000500    000959  ...    0.212655   0.314041       0
5762  20230523   001000    001459  ...    0.212469   0.313969       0
5763  20230523   001500    001959  ...    0.212281   0.313894       0

[5 rows x 18 columns]
2023-05-23 00:20:05,906:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26894.5, self.close=26873.9, self.high=26899.4, self.low=26873.9, self.vol=851.95, self.amt=22903007.863, ukdf['pct'].iloc[-1]=-0.000766 , ukdf['amount'].iloc[-1]=22903007.863, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.21228117532388896, signal=0, value_std=0.31389358044546506 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-151.31157140154', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26875.76540079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2465
self.closeSec=1684772699, self.tradeDate='20230523', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26873.9, self.close=26827.2, self.high=26886.1, self.low=26822.4, self.vol=1648.674, self.amt=44266273.4528 
127.0.0.1 - - [23/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-23 00:25:00,427:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230523   000000    000459  ...    0.212839   0.314111       0
5761  20230523   000500    000959  ...    0.212655   0.314041       0
5762  20230523   001000    001459  ...    0.212469   0.313969       0
5763  20230523   001500    001959  ...    0.212281   0.313894       0
5764  20230523   002000    002459  ...    0.212089   0.313812       0

[5 rows x 18 columns]
2023-05-23 00:25:00,427:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684772699, self.tradeDate='20230523', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26873.9, self.close=26827.2, self.high=26886.1, self.low=26822.4, self.vol=1648.674, self.amt=44266273.4528, ukdf['pct'].iloc[-1]=-0.001738 , ukdf['amount'].iloc[-1]=44266273.4528, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.21208930493814993, signal=0, value_std=0.31381216147704133 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '525.0102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26827.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26894.5, self.close=26873.9, self.high=26899.4, self.low=26873.9 
127.0.0.1 - - [23/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-23 00:20:04,325:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26894.5, self.close=26873.9, self.high=26899.4, self.low=26873.9   
2023-05-23 00:20:05,305:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230522   235500    235959  1684771199  ...  26862.2  0.000037   1727    5
1440  20230523   000000    000459  1684771499  ...  26860.0  0.000346   1440    0
1441  20230523   000500    000959  1684771799  ...  26859.5  0.000588   1441    1
1442  20230523   001000    001459  1684772099  ...  26883.0  0.000231   1442    2
1443  20230523   001500    001959  1684772399  ...  26873.9 -0.000766   1443    3

[5 rows x 11 columns]
2023-05-23 00:20:05,315:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=11, self.factor=0.5237771022408955, self.count=2467 

self.closeSec=1684772699, self.tradeDate='20230523', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26873.9, self.close=26827.2, self.high=26886.1, self.low=26822.4 
2023-05-23 00:25:00,361:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684772699, self.tradeDate='20230523', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26873.9, self.close=26827.2, self.high=26886.1, self.low=26822.4   
2023-05-23 00:25:00,411:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230523   000000    000459  1684771499  ...  26860.0  0.000346   1440    0
1441  20230523   000500    000959  1684771799  ...  26859.5  0.000588   1441    1
1442  20230523   001000    001459  1684772099  ...  26883.0  0.000231   1442    2
1443  20230523   001500    001959  1684772399  ...  26873.9 -0.000766   1443    3
1444  20230523   002000    002459  1684772699  ...  26822.4 -0.001738   1444    4

[5 rows x 11 columns]
2023-05-23 00:25:00,411:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-23 00:00:33,832:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230522    212959  26718.0  ...  49.166667  0.469980  0.465024
5803  20230522    215959  26762.4  ...  49.583333  0.538092  0.445454
5804  20230522    222959  26995.3  ...  49.166667  0.519271  0.434369
5805  20230522    225959  26931.0  ...  49.166667  0.523208  0.422362
5806  20230522    232959  26945.9  ...  49.166667  0.493796  0.422999

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-05-23 00:00:34,047:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.501926  0.498074       1  ...  0.971341   1.0    0.0  0.983883
540     0  0.556347  0.443653       0  ...  0.969024   1.0    0.0  0.981536
541     1  0.497223  0.502777       1  ...  0.969560   1.0    0.0  0.982079
542     0  0.512229  0.487771       0  ...  0.965739   1.0    0.0  0.978209
543     1  0.490528  0.509472       1  ...  0.966588   1.0    0.0  0.979069

[5 rows x 10 columns]
2023-05-23 00:00:34,075:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502001  0.497999       1  ...  0.971341   1.0    0.0  0.982226
46     0  0.555716  0.444284       0  ...  0.969024   1.0    0.0  0.979690
47     1  0.497294  0.502706       1  ...  0.969560   1.0    0.0  0.980232
48     0  0.512163  0.487837       0  ...  0.965739   1.0    0.0  0.975482
49     1  0.490528  0.509472       1  ...  0.966588   1.0    0.0  0.979069

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.741', 'enterprice': '27035', 'countrevence': '0', 'unrealprofit': '-4575.95515019786', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26863.87868254', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-05-23 00:00:02,887:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42239F1684771202176I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684771202627085, 'quantity': '26.43', 'price': '26863.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684771200942, 'updatetime': 1684771202627, 'tradetype': 'usdt', 'selfid': 42239, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684771202627, 'clientorderid': '42239F1684771202176I0L59', 'price': '26863.3', 'quantity': '26.43', 'commission': '709.997019', 'commissionasset': 'USDT', 'tradetime': 1684771202627, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684771202627}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1232 

self.closeSec=1684771799, self.tradeDate='20230523', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26863.3', self.close='26888.3'
2023-05-23 00:10:00,352:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684771799, self.tradeDate='20230523', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26863.3', self.close='26888.3'
2023-05-23 00:10:00,400:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230522   232000    232959  1684769399  26818.2  26839.6  0.000794
573  20230522   233000    233959  1684769999  26839.6    26859  0.000723
574  20230522   234000    234959  1684770599  26859.1    26863  0.000149
575  20230522   235000    235959  1684771199    26863  26863.2  0.000007
576  20230523   000000    000959  1684771799  26863.3  26888.3  0.000934
2023-05-23 00:10:00,401:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1233 

self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26888.3', self.close='26873.9'
127.0.0.1 - - [23/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 00:20:04,225:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26888.3', self.close='26873.9'
2023-05-23 00:20:04,995:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230522   233000    233959  1684769999  26839.6    26859  0.000723
574  20230522   234000    234959  1684770599  26859.1    26863  0.000149
575  20230522   235000    235959  1684771199    26863  26863.2  0.000007
576  20230523   000000    000959  1684771799  26863.3  26888.3  0.000934
577  20230523   001000    001959  1684772399  26888.3  26873.9 -0.000536
2023-05-23 00:20:04,995:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-23 00:00:00,467:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-23 00:00:00,626:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5230000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230522, closeTime:235959, close:26863.2, total:973579.8686232, pct_pre:-0.002099981416093688, thd:0.36493745083992757, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1235 

self.closeSec=1684771799, self.tradeDate='20230523', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26863.3', self.close='26888.3'
2023-05-23 00:10:00,375:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684771799, self.tradeDate='20230523', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26863.3', self.close='26888.3'
127.0.0.1 - - [23/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-23 00:10:00,404:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230522   232000    232959  1684769399  26818.2  26839.6
17421  20230522   233000    233959  1684769999  26839.6    26859
17422  20230522   234000    234959  1684770599  26859.1    26863
17423  20230522   235000    235959  1684771199    26863  26863.2
17424  20230523   000000    000959  1684771799  26863.3  26888.3
2023-05-23 00:10:00,404:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1236 

self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26888.3', self.close='26873.9'
127.0.0.1 - - [23/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-23 00:20:06,323:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26888.3', self.close='26873.9'
2023-05-23 00:20:06,384:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230522   233000    233959  1684769999  26839.6    26859
17422  20230522   234000    234959  1684770599  26859.1    26863
17423  20230522   235000    235959  1684771199    26863  26863.2
17424  20230523   000000    000959  1684771799  26863.3  26888.3
17425  20230523   001000    001959  1684772399  26888.3  26873.9
2023-05-23 00:20:06,386:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-05-23 00:00:03,057:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42240F1684771202419I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684771202851611, 'quantity': '47.489', 'price': '26863.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684771201322, 'updatetime': 1684771202851, 'tradetype': 'usdt', 'selfid': 42240, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684771202851, 'clientorderid': '42240F1684771202419I0L2', 'price': '26863.2', 'quantity': '47.489', 'commission': '1275.7065048', 'commissionasset': 'USDT', 'tradetime': 1684771202851, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684771202851}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1235 

self.closeSec=1684771799, self.tradeDate='20230523', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26863.3', self.close='26888.3'
2023-05-23 00:10:00,338:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684771799, self.tradeDate='20230523', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26863.3', self.close='26888.3'
2023-05-23 00:10:00,379:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230522   232000    232959  1684769399  26818.2  26839.6
12237  20230522   233000    233959  1684769999  26839.6    26859
12238  20230522   234000    234959  1684770599  26859.1    26863
12239  20230522   235000    235959  1684771199    26863  26863.2
12240  20230523   000000    000959  1684771799  26863.3  26888.3
2023-05-23 00:10:00,380:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1236 

self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26888.3', self.close='26873.9'
127.0.0.1 - - [23/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 00:20:06,015:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26888.3', self.close='26873.9'
2023-05-23 00:20:06,243:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230522   233000    233959  1684769999  26839.6    26859
12238  20230522   234000    234959  1684770599  26859.1    26863
12239  20230522   235000    235959  1684771199    26863  26863.2
12240  20230523   000000    000959  1684771799  26863.3  26888.3
12241  20230523   001000    001959  1684772399  26888.3  26873.9
2023-05-23 00:20:06,243:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2464
self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26894.5, self.close=26873.9, self.high=26899.4, self.low=26873.9, self.vol=851.95, self.amt=22903007.863 
127.0.0.1 - - [23/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-23 00:20:05,915:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230522   235500    235959  ...         0.0        0.0       0
5760  20230523   000000    000459  ...         0.0        0.0       0
5761  20230523   000500    000959  ...         0.0        0.0       0
5762  20230523   001000    001459  ...         0.0        0.0       0
5763  20230523   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-23 00:20:05,925:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684772399, self.tradeDate='20230523', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26894.5, self.close=26873.9, self.high=26899.4, self.low=26873.9, self.vol=851.95, self.amt=22903007.863, ukdf['pct'].iloc[-1]=-0.000766 , ukdf['amount'].iloc[-1]=22903007.863, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '1179.79875074139', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26875.76540079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2465
self.closeSec=1684772699, self.tradeDate='20230523', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26873.9, self.close=26827.2, self.high=26886.1, self.low=26822.4, self.vol=1648.674, self.amt=44266273.4528 
127.0.0.1 - - [23/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-23 00:25:00,415:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230523   000000    000459  ...         0.0        0.0       0
5761  20230523   000500    000959  ...         0.0        0.0       0
5762  20230523   001000    001459  ...         0.0        0.0       0
5763  20230523   001500    001959  ...         0.0        0.0       0
5764  20230523   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-23 00:25:00,416:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684772699, self.tradeDate='20230523', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26873.9, self.close=26827.2, self.high=26886.1, self.low=26822.4, self.vol=1648.674, self.amt=44266273.4528, ukdf['pct'].iloc[-1]=-0.001738 , ukdf['amount'].iloc[-1]=44266273.4528, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-623.9688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26827.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230522   120000    155959  1684742399  ...    723  0.151993 -1.376274    -1.0
724  20230522   160000    195959  1684756799  ...    724  0.099685 -1.608829    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '12923.3343', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26819.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=51
self.closeSec=1684771199, self.tradeDate='20230522', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26819.9, self.close=26863.2, self.high=27097.8, self.low=26690.0, self.vol=129893.083, self.amt=3493351748.06182 
2023-05-23 00:00:00,361:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684771199, self.tradeDate='20230522', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26819.9, self.close=26863.2, self.high=27097.8, self.low=26690.0, self.vol=129893.083, self.amt=3493351748.06182 
127.0.0.1 - - [23/May/2023 00:00:00] "POST / HTTP/1.1" 200 -
2023-05-23 00:00:00,439:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230522   040000    075959  ...   41970.275  1.122797e+09 -0.005816
722  20230522   080000    115959  ...   60333.993  1.606146e+09 -0.003557
723  20230522   120000    155959  ...   46118.467  1.235246e+09  0.007245
724  20230522   160000    195959  ...   31113.301  8.346117e+08 -0.000403
725  20230522   200000    235959  ...  129893.083  3.493352e+09  0.001614

[5 rows x 11 columns]
2023-05-23 00:00:03,061:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230522   040000    075959  1684713599  ...    721  0.231294 -1.012186    -1.0
722  20230522   080000    115959  1684727999  ...    722  0.206858 -1.122289    -1.0
723  20230522   120000    155959  1684742399  ...    723  0.151993 -1.376274    -1.0
724  20230522   160000    195959  1684756799  ...    724  0.099685 -1.608829    -1.0
725  20230522   200000    235959  1684771199  ...    725  0.030624 -1.905052    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '10554.8609922423', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26865.7460573', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


