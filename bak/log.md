# 20230517 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=736
self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27036.2, self.close=27010.2, self.high=27048.4, self.low=27010.1, self.vol=771.387, self.amt=20846347.9262 
2023-05-17 00:20:00,435:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230516   235500    235959  ...    0.462614   0.260933       0
5760  20230517   000000    000459  ...    0.462511   0.261042       0
5761  20230517   000500    000959  ...    0.462408   0.261152       0
5762  20230517   001000    001459  ...    0.462305   0.261261       0
5763  20230517   001500    001959  ...    0.462202   0.261370       0

[5 rows x 18 columns]
2023-05-17 00:20:00,437:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27036.2, self.close=27010.2, self.high=27048.4, self.low=27010.1, self.vol=771.387, self.amt=20846347.9262, ukdf['pct'].iloc[-1]=-0.000965 , ukdf['amount'].iloc[-1]=20846347.9262, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.46220171316659614, signal=0, value_std=0.2613701032773071 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2044.17517164102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27011.68839377', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=737
self.closeSec=1684254299, self.tradeDate='20230517', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27010.1, self.close=27026.6, self.high=27039.3, self.low=27009.6, self.vol=506.101, self.amt=13678147.6868 
2023-05-17 00:25:00,400:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230517   000000    000459  ...    0.462511   0.261042       0
5761  20230517   000500    000959  ...    0.462408   0.261152       0
5762  20230517   001000    001459  ...    0.462305   0.261261       0
5763  20230517   001500    001959  ...    0.462202   0.261370       0
5764  20230517   002000    002459  ...    0.462105   0.261477       0

[5 rows x 18 columns]
2023-05-17 00:25:00,401:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684254299, self.tradeDate='20230517', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27010.1, self.close=27026.6, self.high=27039.3, self.low=27009.6, self.vol=506.101, self.amt=13678147.6868, ukdf['pct'].iloc[-1]=0.000607 , ukdf['amount'].iloc[-1]=13678147.6868, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.46210473450863915, signal=0, value_std=0.26147678938993774 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2263.42915081272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27027.43261172', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=122, self.factor=0.524849174522125, self.count=738 

self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27036.2, self.close=27010.2, self.high=27048.4, self.low=27010.1 
2023-05-17 00:20:00,402:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27036.2, self.close=27010.2, self.high=27048.4, self.low=27010.1   
2023-05-17 00:20:00,468:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230516   235500    235959  1684252799  ...  27023.8 -0.000695   1726    4
1439  20230517   000000    000459  1684253099  ...  27018.7  0.000770   1439    5
1440  20230517   000500    000959  1684253399  ...  27040.2  0.000048   1440    0
1441  20230517   001000    001459  1684253699  ...  27030.9 -0.000506   1441    1
1442  20230517   001500    001959  1684253999  ...  27010.1 -0.000965   1442    2

[5 rows x 11 columns]
2023-05-17 00:20:00,469:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=122, self.factor=0.524849174522125, self.count=739 

self.closeSec=1684254299, self.tradeDate='20230517', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27010.1, self.close=27026.6, self.high=27039.3, self.low=27009.6 
2023-05-17 00:25:00,355:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684254299, self.tradeDate='20230517', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27010.1, self.close=27026.6, self.high=27039.3, self.low=27009.6   
2023-05-17 00:25:00,370:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230517   000000    000459  1684253099  ...  27018.7  0.000770   1439    5
1440  20230517   000500    000959  1684253399  ...  27040.2  0.000048   1440    0
1441  20230517   001000    001459  1684253699  ...  27030.9 -0.000506   1441    1
1442  20230517   001500    001959  1684253999  ...  27010.1 -0.000965   1442    2
1443  20230517   002000    002459  1684254299  ...  27009.6  0.000607   1443    3

[5 rows x 11 columns]
2023-05-17 00:25:00,370:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-17 00:00:17,369:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230516    212959  27047.3  ...  50.416667  0.488204  0.647236
5803  20230516    215959  27072.3  ...  50.416667  0.466372  0.657215
5804  20230516    222959  26969.6  ...  50.416667  0.470162  0.663178
5805  20230516    225959  26985.7  ...  50.416667  0.467678  0.669838
5806  20230516    232959  26974.0  ...  50.416667  0.489197  0.665005

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-05-17 00:00:17,473:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.511432  0.488568       0  ...  1.025245  -1.0    0.0  0.928098
540     1  0.476368  0.523632       1  ...  1.024633  -1.0    0.0  0.928652
541     1  0.497032  0.502968       0  ...  1.025081  -1.0    0.0  0.928246
542     1  0.493483  0.506517       1  ...  1.021577  -1.0    0.0  0.931419
543     0  0.517620  0.482380       0  ...  1.023019  -1.0    0.0  0.930104

[5 rows x 10 columns]
2023-05-17 00:00:17,497:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511328  0.488672       0  ...  1.025245  -1.0    0.0  0.924345
46     1  0.476065  0.523935       1  ...  1.024633  -1.0    0.0  0.925670
47     1  0.496834  0.503166       0  ...  1.025081  -1.0    0.0  0.925266
48     1  0.493227  0.506773       1  ...  1.021577  -1.0    0.0  0.930231
49     0  0.517620  0.482380       0  ...  1.023019  -1.0    0.0  0.930104

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.151', 'enterprice': '26995.7', 'countrevence': '0', 'unrealprofit': '-934.6132', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27028.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-05-17 00:00:02,941:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42174F1684252802318I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684252802734402, 'quantity': '26.042', 'price': '27027.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684252801007, 'updatetime': 1684252802734, 'tradetype': 'usdt', 'selfid': 42174, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684252802734, 'clientorderid': '42174F1684252802318I0L59', 'price': '27027.8', 'quantity': '26.042', 'commission': '703.8579676', 'commissionasset': 'USDT', 'tradetime': 1684252802734, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684252802734}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=368 

self.closeSec=1684253399, self.tradeDate='20230517', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27027.9', self.close='27050'
2023-05-17 00:10:00,372:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684253399, self.tradeDate='20230517', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27027.9', self.close='27050'
2023-05-17 00:10:00,404:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230516   232000    232959  1684250999  27025.4  27066.1  0.001510
573  20230516   233000    233959  1684251599  27066.1  27023.1 -0.001589
574  20230516   234000    234959  1684252199  27023.2  27012.1 -0.000407
575  20230516   235000    235959  1684252799  27012.2  27027.9  0.000585
576  20230517   000000    000959  1684253399  27027.9    27050  0.000818
2023-05-17 00:10:00,406:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=369 

self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27050', self.close='27010.2'
2023-05-17 00:20:00,397:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27050', self.close='27010.2'
127.0.0.1 - - [17/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-17 00:20:00,419:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230516   233000    233959  1684251599  27066.1  27023.1 -0.001589
574  20230516   234000    234959  1684252199  27023.2  27012.1 -0.000407
575  20230516   235000    235959  1684252799  27012.2  27027.9  0.000585
576  20230517   000000    000959  1684253399  27027.9    27050  0.000818
577  20230517   001000    001959  1684253999    27050  27010.2 -0.001471
2023-05-17 00:20:00,419:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-17 00:00:00,407:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-17 00:00:00,521:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5170000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230516, closeTime:235959, close:27027.9, total:986122.7200962, pct_pre:-0.01180840893001811, thd:-0.034636922905616985, side:sell 
127.0.0.1 - - [17/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=371 

self.closeSec=1684253399, self.tradeDate='20230517', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27027.9', self.close='27050'
2023-05-17 00:10:00,390:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684253399, self.tradeDate='20230517', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27027.9', self.close='27050'
2023-05-17 00:10:00,419:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230516   232000    232959  1684250999  27025.4  27066.1
17421  20230516   233000    233959  1684251599  27066.1  27023.1
17422  20230516   234000    234959  1684252199  27023.2  27012.1
17423  20230516   235000    235959  1684252799  27012.2  27027.9
17424  20230517   000000    000959  1684253399  27027.9    27050
2023-05-17 00:10:00,419:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/May/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=372 

self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27050', self.close='27010.2'
2023-05-17 00:20:00,490:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27050', self.close='27010.2'
2023-05-17 00:20:00,500:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230516   233000    233959  1684251599  27066.1  27023.1
17422  20230516   234000    234959  1684252199  27023.2  27012.1
17423  20230516   235000    235959  1684252799  27012.2  27027.9
17424  20230517   000000    000959  1684253399  27027.9    27050
17425  20230517   001000    001959  1684253999    27050  27010.2
2023-05-17 00:20:00,500:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [17/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-17 00:00:03,125:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42175F1684252802429I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684252802836988, 'quantity': '45.991', 'price': '27027.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684252801332, 'updatetime': 1684252802836, 'tradetype': 'usdt', 'selfid': 42175, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684252802836, 'clientorderid': '42175F1684252802429I0L2', 'price': '27027.9', 'quantity': '45.991', 'commission': '1243.0401489', 'commissionasset': 'USDT', 'tradetime': 1684252802836, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684252802836}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=371 

self.closeSec=1684253399, self.tradeDate='20230517', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27027.9', self.close='27050'
127.0.0.1 - - [17/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-17 00:10:00,354:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684253399, self.tradeDate='20230517', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27027.9', self.close='27050'
2023-05-17 00:10:00,361:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230516   232000    232959  1684250999  27025.4  27066.1
12237  20230516   233000    233959  1684251599  27066.1  27023.1
12238  20230516   234000    234959  1684252199  27023.2  27012.1
12239  20230516   235000    235959  1684252799  27012.2  27027.9
12240  20230517   000000    000959  1684253399  27027.9    27050
2023-05-17 00:10:00,362:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [17/May/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=372 

self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27050', self.close='27010.2'
2023-05-17 00:20:00,436:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27050', self.close='27010.2'
2023-05-17 00:20:00,489:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230516   233000    233959  1684251599  27066.1  27023.1
12238  20230516   234000    234959  1684252199  27023.2  27012.1
12239  20230516   235000    235959  1684252799  27012.2  27027.9
12240  20230517   000000    000959  1684253399  27027.9    27050
12241  20230517   001000    001959  1684253999    27050  27010.2
2023-05-17 00:20:00,489:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [17/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=736
self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27036.2, self.close=27010.2, self.high=27048.4, self.low=27010.1, self.vol=771.387, self.amt=20846347.9262 
2023-05-17 00:20:00,480:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230516   235500    235959  ...    0.365529   0.268360       0
5760  20230517   000000    000459  ...    0.365281   0.268477       0
5761  20230517   000500    000959  ...    0.365032   0.268595       0
5762  20230517   001000    001459  ...    0.364793   0.268715       0
5763  20230517   001500    001959  ...    0.364554   0.268835       0

[5 rows x 18 columns]
2023-05-17 00:20:00,481:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684253999, self.tradeDate='20230517', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27036.2, self.close=27010.2, self.high=27048.4, self.low=27010.1, self.vol=771.387, self.amt=20846347.9262, ukdf['pct'].iloc[-1]=-0.000965 , ukdf['amount'].iloc[-1]=20846347.9262, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.36455429707329995, signal=0, value_std=0.2688352995202855 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '6228.11463301157', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27011.68839377', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [17/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=737
self.closeSec=1684254299, self.tradeDate='20230517', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27010.1, self.close=27026.6, self.high=27039.3, self.low=27009.6, self.vol=506.101, self.amt=13678147.6868 
2023-05-17 00:25:00,411:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230517   000000    000459  ...    0.365281   0.268477       0
5761  20230517   000500    000959  ...    0.365032   0.268595       0
5762  20230517   001000    001459  ...    0.364793   0.268715       0
5763  20230517   001500    001959  ...    0.364554   0.268835       0
5764  20230517   002000    002459  ...    0.364317   0.268956       0

[5 rows x 18 columns]
2023-05-17 00:25:00,412:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684254299, self.tradeDate='20230517', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27010.1, self.close=27026.6, self.high=27039.3, self.low=27009.6, self.vol=506.101, self.amt=13678147.6868, ukdf['pct'].iloc[-1]=0.000607 , ukdf['amount'].iloc[-1]=13678147.6868, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.36431705570726874, signal=0, value_std=0.2689558931299035 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '6812.87063189252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27027.43261172', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230516   120000    155959  1684223999  ...    723  0.502828  0.089948     NaN
724  20230516   160000    195959  1684238399  ...    724  0.552624  0.358453     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-12096.9852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27049.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [17/May/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=6897.9369698, self.flagDict['side']='', self.tradeCount=0, self.count=15
self.closeSec=1684252799, self.tradeDate='20230516', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27049.3, self.close=27027.9, self.high=27127.4, self.low=26880.1, self.vol=89162.317, self.amt=2408573520.6957 
2023-05-17 00:00:00,404:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684252799, self.tradeDate='20230516', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27049.3, self.close=27027.9, self.high=27127.4, self.low=26880.1, self.vol=89162.317, self.amt=2408573520.6957 
2023-05-17 00:00:00,465:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230516   040000    075959  ...  38932.072  1.061731e+09 -0.009398
722  20230516   080000    115959  ...  90185.098  2.439151e+09 -0.001245
723  20230516   120000    155959  ...  49329.282  1.337491e+09  0.004495
724  20230516   160000    195959  ...  62608.697  1.697098e+09 -0.007023
725  20230516   200000    235959  ...  89162.317  2.408574e+09 -0.000791

[5 rows x 11 columns]
2023-05-17 00:00:01,757:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230516   040000    075959  1684195199  ...    721  0.467538 -0.050923     NaN
722  20230516   080000    115959  1684209599  ...    722  0.474729 -0.042116     NaN
723  20230516   120000    155959  1684223999  ...    723  0.502828  0.089948     NaN
724  20230516   160000    195959  1684238399  ...    724  0.552624  0.358453     NaN
725  20230516   200000    235959  1684252799  ...    725  0.485815 -0.056272     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-10969.6112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27027.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


