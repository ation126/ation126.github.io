# 20230520 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [20/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1600
self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26905.2, self.close=26904.1, self.high=26944.0, self.low=26894.5, self.vol=1364.878, self.amt=36742600.4552 
2023-05-20 00:20:00,718:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230519   235500    235959  ...    0.355783   0.325636       0
5760  20230520   000000    000459  ...    0.355629   0.325673       0
5761  20230520   000500    000959  ...    0.355482   0.325714       0
5762  20230520   001000    001459  ...    0.355334   0.325754       0
5763  20230520   001500    001959  ...    0.355185   0.325794       0

[5 rows x 18 columns]
2023-05-20 00:20:00,733:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26905.2, self.close=26904.1, self.high=26944.0, self.low=26894.5, self.vol=1364.878, self.amt=36742600.4552, ukdf['pct'].iloc[-1]=-4.1e-05 , ukdf['amount'].iloc[-1]=36742600.4552, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.35518527993798077, signal=0, value_std=0.3257942960401202 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-553.5099247194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26904.6465119', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1601
self.closeSec=1684513499, self.tradeDate='20230520', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26904.1, self.close=26911.9, self.high=26921.6, self.low=26890.5, self.vol=979.253, self.amt=26345907.7506 
127.0.0.1 - - [20/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-20 00:25:00,357:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230520   000000    000459  ...    0.355629   0.325673       0
5761  20230520   000500    000959  ...    0.355482   0.325714       0
5762  20230520   001000    001459  ...    0.355334   0.325754       0
5763  20230520   001500    001959  ...    0.355185   0.325794       0
5764  20230520   002000    002459  ...    0.355035   0.325834       0

[5 rows x 18 columns]
2023-05-20 00:25:00,358:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684513499, self.tradeDate='20230520', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26904.1, self.close=26911.9, self.high=26921.6, self.low=26890.5, self.vol=979.253, self.amt=26345907.7506, ukdf['pct'].iloc[-1]=0.00029 , ukdf['amount'].iloc[-1]=26345907.7506, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.3550354102123811, signal=0, value_std=0.32583355344022014 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-654.522', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26911.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26905.2, self.close=26904.1, self.high=26944.0, self.low=26894.5 
127.0.0.1 - - [20/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 00:20:00,514:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26905.2, self.close=26904.1, self.high=26944.0, self.low=26894.5   
2023-05-20 00:20:00,576:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230519   235500    235959  1684511999  ...  26866.5 -0.001119   1727    5
1440  20230520   000000    000459  1684512299  ...  26832.2  0.000856   1440    0
1441  20230520   000500    000959  1684512599  ...  26865.7  0.001945   1441    1
1442  20230520   001000    001459  1684512899  ...  26897.0 -0.001484   1442    2
1443  20230520   001500    001959  1684513199  ...  26894.5 -0.000041   1443    3

[5 rows x 11 columns]
2023-05-20 00:20:00,578:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=40, self.factor=0.4591399041651362, self.count=1603 

self.closeSec=1684513499, self.tradeDate='20230520', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26904.1, self.close=26911.9, self.high=26921.6, self.low=26890.5 
2023-05-20 00:25:00,332:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684513499, self.tradeDate='20230520', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26904.1, self.close=26911.9, self.high=26921.6, self.low=26890.5   
2023-05-20 00:25:00,363:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230520   000000    000459  1684512299  ...  26832.2  0.000856   1440    0
1441  20230520   000500    000959  1684512599  ...  26865.7  0.001945   1441    1
1442  20230520   001000    001459  1684512899  ...  26897.0 -0.001484   1442    2
1443  20230520   001500    001959  1684513199  ...  26894.5 -0.000041   1443    3
1444  20230520   002000    002459  1684513499  ...  26890.5  0.000290   1444    4

[5 rows x 11 columns]
2023-05-20 00:25:00,363:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-20 00:00:18,327:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230519    212959  26897.2  ...  50.000000  0.487964  0.462904
5803  20230519    215959  26922.7  ...  49.583333  0.472108  0.452963
5804  20230519    222959  26852.9  ...  49.583333  0.459768  0.456398
5805  20230519    225959  26796.3  ...  49.583333  0.467238  0.456960
5806  20230519    232959  26826.0  ...  49.583333  0.477781  0.463311

[5 rows x 33 columns]
0.5386029411764706
acc is : 0.5386029411764706
2023-05-20 00:00:18,425:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.514388  0.485612       0  ...  0.911496  -1.0    0.0  0.960480
540     1  0.492443  0.507557       0  ...  0.913414  -1.0    0.0  0.958459
541     1  0.487222  0.512778       1  ...  0.912402  -1.0    0.0  0.959521
542     1  0.498481  0.501519       1  ...  0.910956  -1.0    0.0  0.961041
543     0  0.505348  0.494652       1  ...  0.910912  -1.0    0.0  0.961088

[5 rows x 10 columns]
2023-05-20 00:00:18,453:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514626  0.485374       0  ...  0.911496  -1.0    0.0  0.951434
46     1  0.492353  0.507647       0  ...  0.913414  -1.0    0.0  0.951638
47     1  0.487213  0.512787       1  ...  0.912402  -1.0    0.0  0.952692
48     1  0.498446  0.501554       1  ...  0.910956  -1.0    0.0  0.955770
49     0  0.505348  0.494652       1  ...  0.910912  -1.0    0.0  0.961088

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.758', 'enterprice': '26580.2', 'countrevence': '0', 'unrealprofit': '-8133.094', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26873.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-05-20 00:00:02,902:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42198F1684512002228I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684512002647082, 'quantity': '26.717', 'price': '26870.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684512000981, 'updatetime': 1684512002647, 'tradetype': 'usdt', 'selfid': 42198, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684512002647, 'clientorderid': '42198F1684512002228I0L59', 'price': '26870.1', 'quantity': '26.717', 'commission': '717.8884617', 'commissionasset': 'USDT', 'tradetime': 1684512002647, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684512002647}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=800 

self.closeSec=1684512599, self.tradeDate='20230520', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26870', self.close='26945.2'
2023-05-20 00:10:00,348:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684512599, self.tradeDate='20230520', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26870', self.close='26945.2'
2023-05-20 00:10:00,400:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230519   232000    232959  1684510199  26992.7  26868.6 -0.004598
573  20230519   233000    233959  1684510799  26868.6    26790 -0.002925
574  20230519   234000    234959  1684511399    26790  26886.1  0.003587
575  20230519   235000    235959  1684511999  26886.1  26869.9 -0.000603
576  20230520   000000    000959  1684512599    26870  26945.2  0.002802
2023-05-20 00:10:00,400:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=801 

self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26945.3', self.close='26904.1'
127.0.0.1 - - [20/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 00:20:00,663:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26945.3', self.close='26904.1'
2023-05-20 00:20:00,761:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230519   233000    233959  1684510799  26868.6    26790 -0.002925
574  20230519   234000    234959  1684511399    26790  26886.1  0.003587
575  20230519   235000    235959  1684511999  26886.1  26869.9 -0.000603
576  20230520   000000    000959  1684512599    26870  26945.2  0.002802
577  20230520   001000    001959  1684513199  26945.3  26904.1 -0.001525
2023-05-20 00:20:00,766:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-20 00:00:00,455:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-20 00:00:00,609:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5200000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230519, closeTime:235959, close:26869.9, total:973579.8686232, pct_pre:-0.008858187728565614, thd:0.3591918894647234, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=803 

self.closeSec=1684512599, self.tradeDate='20230520', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26870', self.close='26945.2'
2023-05-20 00:10:00,342:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684512599, self.tradeDate='20230520', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26870', self.close='26945.2'
127.0.0.1 - - [20/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-20 00:10:00,357:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230519   232000    232959  1684510199  26992.7  26868.6
17421  20230519   233000    233959  1684510799  26868.6    26790
17422  20230519   234000    234959  1684511399    26790  26886.1
17423  20230519   235000    235959  1684511999  26886.1  26869.9
17424  20230520   000000    000959  1684512599    26870  26945.2
2023-05-20 00:10:00,357:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=804 

self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26945.3', self.close='26904.1'
127.0.0.1 - - [20/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 00:20:01,041:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26945.3', self.close='26904.1'
2023-05-20 00:20:01,098:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230519   233000    233959  1684510799  26868.6    26790
17422  20230519   234000    234959  1684511399    26790  26886.1
17423  20230519   235000    235959  1684511999  26886.1  26869.9
17424  20230520   000000    000959  1684512599    26870  26945.2
17425  20230520   001000    001959  1684513199  26945.3  26904.1
2023-05-20 00:20:01,099:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-20 00:00:03,097:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42199F1684512002314I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684512002727912, 'quantity': '47.819', 'price': '26870', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684512001115, 'updatetime': 1684512002727, 'tradetype': 'usdt', 'selfid': 42199, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684512002727, 'clientorderid': '42199F1684512002314I0L2', 'price': '26870', 'quantity': '47.819', 'commission': '1284.89653', 'commissionasset': 'USDT', 'tradetime': 1684512002727, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684512002727}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=803 

self.closeSec=1684512599, self.tradeDate='20230520', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26870', self.close='26945.2'
2023-05-20 00:10:00,328:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684512599, self.tradeDate='20230520', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26870', self.close='26945.2'
2023-05-20 00:10:00,352:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230519   232000    232959  1684510199  26992.7  26868.6
12237  20230519   233000    233959  1684510799  26868.6    26790
12238  20230519   234000    234959  1684511399    26790  26886.1
12239  20230519   235000    235959  1684511999  26886.1  26869.9
12240  20230520   000000    000959  1684512599    26870  26945.2
2023-05-20 00:10:00,352:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=804 

self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26945.3', self.close='26904.1'
127.0.0.1 - - [20/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 00:20:00,966:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26945.3', self.close='26904.1'
2023-05-20 00:20:01,046:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230519   233000    233959  1684510799  26868.6    26790
12238  20230519   234000    234959  1684511399    26790  26886.1
12239  20230519   235000    235959  1684511999  26886.1  26869.9
12240  20230520   000000    000959  1684512599    26870  26945.2
12241  20230520   001000    001959  1684513199  26945.3  26904.1
2023-05-20 00:20:01,046:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [20/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1600
self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26905.2, self.close=26904.1, self.high=26944.0, self.low=26894.5, self.vol=1364.878, self.amt=36742600.4552 
2023-05-20 00:20:00,742:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230519   235500    235959  ...    0.163006   0.287022       0
5760  20230520   000000    000459  ...    0.162758   0.286957       0
5761  20230520   000500    000959  ...    0.162510   0.286891       0
5762  20230520   001000    001459  ...    0.162262   0.286826       0
5763  20230520   001500    001959  ...    0.162013   0.286758       0

[5 rows x 18 columns]
2023-05-20 00:20:00,783:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684513199, self.tradeDate='20230520', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26905.2, self.close=26904.1, self.high=26944.0, self.low=26894.5, self.vol=1364.878, self.amt=36742600.4552, ukdf['pct'].iloc[-1]=-4.1e-05 , ukdf['amount'].iloc[-1]=36742600.4552, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.16201268210802272, signal=0, value_std=0.2867583594916293 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2252.4720984779', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26904.6465119', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [20/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1601
self.closeSec=1684513499, self.tradeDate='20230520', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26904.1, self.close=26911.9, self.high=26921.6, self.low=26890.5, self.vol=979.253, self.amt=26345907.7506 
2023-05-20 00:25:00,380:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230520   000000    000459  ...    0.162758   0.286957       0
5761  20230520   000500    000959  ...    0.162510   0.286891       0
5762  20230520   001000    001459  ...    0.162262   0.286826       0
5763  20230520   001500    001959  ...    0.162013   0.286758       0
5764  20230520   002000    002459  ...    0.161763   0.286690       0

[5 rows x 18 columns]
2023-05-20 00:25:00,380:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684513499, self.tradeDate='20230520', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26904.1, self.close=26911.9, self.high=26921.6, self.low=26890.5, self.vol=979.253, self.amt=26345907.7506, ukdf['pct'].iloc[-1]=0.00029 , ukdf['amount'].iloc[-1]=26345907.7506, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.16176263934774357, signal=0, value_std=0.28669020450660493 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2521.8739', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26911.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230519   120000    155959  1684483199  ...    723  0.342365 -0.811255    -1.0
724  20230519   160000    195959  1684497599  ...    724  0.335530 -0.830864    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '11686.1583', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26843.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [20/May/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=33
self.closeSec=1684511999, self.tradeDate='20230519', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26843.8, self.close=26869.9, self.high=27180.0, self.low=26611.2, self.vol=157634.157, self.amt=4238886804.37383 
2023-05-20 00:00:00,401:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684511999, self.tradeDate='20230519', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26843.8, self.close=26869.9, self.high=27180.0, self.low=26611.2, self.vol=157634.157, self.amt=4238886804.37383 
2023-05-20 00:00:00,483:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230519   040000    075959  ...   58949.169  1.583234e+09  0.003368
722  20230519   080000    115959  ...   37542.604  1.006846e+09  0.000586
723  20230519   120000    155959  ...   28781.823  7.734667e+08  0.000630
724  20230519   160000    195959  ...   32361.524  8.685760e+08  0.000071
725  20230519   200000    235959  ...  157634.157  4.238887e+09  0.000972

[5 rows x 11 columns]
2023-05-20 00:00:01,734:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230519   040000    075959  1684454399  ...    721  0.281797 -1.193104    -1.0
722  20230519   080000    115959  1684468799  ...    722  0.298540 -1.075083    -1.0
723  20230519   120000    155959  1684483199  ...    723  0.342365 -0.811255    -1.0
724  20230519   160000    195959  1684497599  ...    724  0.335530 -0.830864    -1.0
725  20230519   200000    235959  1684511999  ...    725  0.299043 -1.013582    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '10229.33896599108', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26872.06086508', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


