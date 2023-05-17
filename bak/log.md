# 20230518 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1024
self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26753.2, self.close=26754.1, self.high=26762.5, self.low=26730.0, self.vol=1232.813, self.amt=32971728.8883 
2023-05-18 00:20:02,283:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230517   235500    235959  ...    0.424798   0.287973       0
5760  20230518   000000    000459  ...    0.424696   0.288058       0
5761  20230518   000500    000959  ...    0.424594   0.288143       0
5762  20230518   001000    001459  ...    0.424491   0.288229       0
5763  20230518   001500    001959  ...    0.424388   0.288314       0

[5 rows x 18 columns]
2023-05-18 00:20:02,293:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26753.2, self.close=26754.1, self.high=26762.5, self.low=26730.0, self.vol=1232.813, self.amt=32971728.8883, ukdf['pct'].iloc[-1]=3.4e-05 , ukdf['amount'].iloc[-1]=32971728.8883, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.4243883047199884, signal=0, value_std=0.2883142265508613 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1525.98014185914', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26755.32222161', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1025
self.closeSec=1684340699, self.tradeDate='20230518', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26754.1, self.close=26778.6, self.high=26783.8, self.low=26754.0, self.vol=655.084, self.amt=17539530.5794 
2023-05-18 00:25:00,401:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230518   000000    000459  ...    0.424696   0.288058       0
5761  20230518   000500    000959  ...    0.424594   0.288143       0
5762  20230518   001000    001459  ...    0.424491   0.288229       0
5763  20230518   001500    001959  ...    0.424388   0.288314       0
5764  20230518   002000    002459  ...    0.424285   0.288400       0

[5 rows x 18 columns]
2023-05-18 00:25:00,401:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684340699, self.tradeDate='20230518', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26754.1, self.close=26778.6, self.high=26783.8, self.low=26754.0, self.vol=655.084, self.amt=17539530.5794, ukdf['pct'].iloc[-1]=0.000916 , ukdf['amount'].iloc[-1]=17539530.5794, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.42428530794523645, signal=0, value_std=0.2883995732804567 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1157.79011774976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26781.76125824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26753.2, self.close=26754.1, self.high=26762.5, self.low=26730.0 
127.0.0.1 - - [18/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 00:20:01,092:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26753.2, self.close=26754.1, self.high=26762.5, self.low=26730.0   
2023-05-18 00:20:01,561:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230517   235500    235959  1684339199  ...  26750.2  0.001241   1726    4
1440  20230518   000000    000459  1684339499  ...  26755.0 -0.001172   1440    0
1441  20230518   000500    000959  1684339799  ...  26754.6  0.001252   1441    1
1442  20230518   001000    001459  1684340099  ...  26750.1 -0.001377   1442    2
1443  20230518   001500    001959  1684340399  ...  26730.0  0.000034   1443    3

[5 rows x 11 columns]
2023-05-18 00:20:01,562:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6658805224980594, self.count=1027 

self.closeSec=1684340699, self.tradeDate='20230518', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26754.1, self.close=26778.6, self.high=26783.8, self.low=26754.0 
127.0.0.1 - - [18/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-18 00:25:00,358:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684340699, self.tradeDate='20230518', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26754.1, self.close=26778.6, self.high=26783.8, self.low=26754.0   
2023-05-18 00:25:00,376:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230518   000000    000459  1684339499  ...  26755.0 -0.001172   1440    0
1441  20230518   000500    000959  1684339799  ...  26754.6  0.001252   1441    1
1442  20230518   001000    001459  1684340099  ...  26750.1 -0.001377   1442    2
1443  20230518   001500    001959  1684340399  ...  26730.0  0.000034   1443    3
1444  20230518   002000    002459  1684340699  ...  26754.0  0.000916   1444    4

[5 rows x 11 columns]
2023-05-18 00:25:00,376:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-18 00:00:18,615:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230517    212959  26659.9  ...  50.000000  0.430303  0.710604
5803  20230517    215959  26695.7  ...  49.583333  0.415877  0.723950
5804  20230517    222959  26618.6  ...  49.583333  0.425976  0.732527
5805  20230517    225959  26658.4  ...  50.000000  0.453235  0.727602
5806  20230517    232959  26770.2  ...  50.000000  0.451884  0.723652

[5 rows x 33 columns]
0.53125
acc is : 0.53125
2023-05-18 00:00:18,760:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.491160  0.508840       0  ...  1.027759  -1.0    0.0  0.906934
540     1  0.478199  0.521801       1  ...  1.026230  -1.0    0.0  0.908283
541     0  0.510555  0.489445       1  ...  1.021922  -1.0    0.0  0.912096
542     0  0.528814  0.471186       0  ...  1.022186  -1.0    0.0  0.911861
543     0  0.508689  0.491311       1  ...  1.021242  -1.0    0.0  0.912702

[5 rows x 10 columns]
2023-05-18 00:00:18,795:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491325  0.508675       0  ...  1.027759  -1.0    0.0  0.907382
46     1  0.478961  0.521039       1  ...  1.026230  -1.0    0.0  0.907483
47     0  0.510544  0.489456       1  ...  1.021922  -1.0    0.0  0.911292
48     0  0.528628  0.471372       0  ...  1.022186  -1.0    0.0  0.910419
49     0  0.508689  0.491311       1  ...  1.021242  -1.0    0.0  0.912702

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.151', 'enterprice': '26995.7', 'countrevence': '0', 'unrealprofit': '5976.29695274853', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26783.40569597', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [18/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-05-18 00:00:02,885:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42181F1684339202233I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684339202659558, 'quantity': '25.954', 'price': '26788.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684339201041, 'updatetime': 1684339202659, 'tradetype': 'usdt', 'selfid': 42181, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684339202659, 'clientorderid': '42181F1684339202233I0L59', 'price': '26788.1', 'quantity': '25.954', 'commission': '695.2583474', 'commissionasset': 'USDT', 'tradetime': 1684339202659, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684339202659}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=512 

self.closeSec=1684339799, self.tradeDate='20230518', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26788.1', self.close='26790.1'
2023-05-18 00:10:00,330:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684339799, self.tradeDate='20230518', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26788.1', self.close='26790.1'
2023-05-18 00:10:00,362:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230517   232000    232959  1684337399  26776.4  26763.3 -0.000489
573  20230517   233000    233959  1684337999  26763.2  26772.9  0.000359
574  20230517   234000    234959  1684338599    26773  26733.7 -0.001464
575  20230517   235000    235959  1684339199  26733.7    26788  0.002031
576  20230518   000000    000959  1684339799  26788.1  26790.1  0.000078
2023-05-18 00:10:00,362:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=513 

self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26790.2', self.close='26754.1'
127.0.0.1 - - [18/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-18 00:20:02,592:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26790.2', self.close='26754.1'
2023-05-18 00:20:02,925:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230517   233000    233959  1684337999  26763.2  26772.9  0.000359
574  20230517   234000    234959  1684338599    26773  26733.7 -0.001464
575  20230517   235000    235959  1684339199  26733.7    26788  0.002031
576  20230518   000000    000959  1684339799  26788.1  26790.1  0.000078
577  20230518   001000    001959  1684340399  26790.2  26754.1 -0.001344
2023-05-18 00:20:02,925:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-18 00:00:00,470:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-18 00:00:00,645:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5180000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230517, closeTime:235959, close:26788, total:986122.7200962, pct_pre:-0.006983364140480619, thd:0.2392297778219809, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=515 

self.closeSec=1684339799, self.tradeDate='20230518', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26788.1', self.close='26790.1'
2023-05-18 00:10:00,356:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684339799, self.tradeDate='20230518', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26788.1', self.close='26790.1'
127.0.0.1 - - [18/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-18 00:10:00,375:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230517   232000    232959  1684337399  26776.4  26763.3
17421  20230517   233000    233959  1684337999  26763.2  26772.9
17422  20230517   234000    234959  1684338599    26773  26733.7
17423  20230517   235000    235959  1684339199  26733.7    26788
17424  20230518   000000    000959  1684339799  26788.1  26790.1
2023-05-18 00:10:00,375:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=516 

self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26790.2', self.close='26754.1'
127.0.0.1 - - [18/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-18 00:20:03,387:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26790.2', self.close='26754.1'
2023-05-18 00:20:03,450:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230517   233000    233959  1684337999  26763.2  26772.9
17422  20230517   234000    234959  1684338599    26773  26733.7
17423  20230517   235000    235959  1684339199  26733.7    26788
17424  20230518   000000    000959  1684339799  26788.1  26790.1
17425  20230518   001000    001959  1684340399  26790.2  26754.1
2023-05-18 00:20:03,451:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [18/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-18 00:00:03,125:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42182F1684339202407I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684339202835730, 'quantity': '46.931', 'price': '26788.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684339201158, 'updatetime': 1684339202835, 'tradetype': 'usdt', 'selfid': 42182, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684339202835, 'clientorderid': '42182F1684339202407I0L2', 'price': '26788.1', 'quantity': '46.931', 'commission': '1257.1923211', 'commissionasset': 'USDT', 'tradetime': 1684339202835, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684339202835}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=515 

self.closeSec=1684339799, self.tradeDate='20230518', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26788.1', self.close='26790.1'
2023-05-18 00:10:00,343:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684339799, self.tradeDate='20230518', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26788.1', self.close='26790.1'
127.0.0.1 - - [18/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-18 00:10:00,371:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230517   232000    232959  1684337399  26776.4  26763.3
12237  20230517   233000    233959  1684337999  26763.2  26772.9
12238  20230517   234000    234959  1684338599    26773  26733.7
12239  20230517   235000    235959  1684339199  26733.7    26788
12240  20230518   000000    000959  1684339799  26788.1  26790.1
2023-05-18 00:10:00,372:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=516 

self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26790.2', self.close='26754.1'
127.0.0.1 - - [18/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 00:20:03,152:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26790.2', self.close='26754.1'
2023-05-18 00:20:03,306:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230517   233000    233959  1684337999  26763.2  26772.9
12238  20230517   234000    234959  1684338599    26773  26733.7
12239  20230517   235000    235959  1684339199  26733.7    26788
12240  20230518   000000    000959  1684339799  26788.1  26790.1
12241  20230518   001000    001959  1684340399  26790.2  26754.1
2023-05-18 00:20:03,306:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1024
self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26753.2, self.close=26754.1, self.high=26762.5, self.low=26730.0, self.vol=1232.813, self.amt=32971728.8883 
127.0.0.1 - - [18/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 00:20:02,282:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230517   235500    235959  ...    0.303197   0.289801       0
5760  20230518   000000    000459  ...    0.303033   0.289884       0
5761  20230518   000500    000959  ...    0.302869   0.289966       0
5762  20230518   001000    001459  ...    0.302703   0.290048       0
5763  20230518   001500    001959  ...    0.302538   0.290130       0

[5 rows x 18 columns]
2023-05-18 00:20:02,302:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684340399, self.tradeDate='20230518', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26753.2, self.close=26754.1, self.high=26762.5, self.low=26730.0, self.vol=1232.813, self.amt=32971728.8883, ukdf['pct'].iloc[-1]=3.4e-05 , ukdf['amount'].iloc[-1]=32971728.8883, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.30253827421711893, signal=0, value_std=0.2901301309023394 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-3293.58136718299', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26755.32222161', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1025
self.closeSec=1684340699, self.tradeDate='20230518', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26754.1, self.close=26778.6, self.high=26783.8, self.low=26754.0, self.vol=655.084, self.amt=17539530.5794 
2023-05-18 00:25:00,428:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230518   000000    000459  ...    0.303033   0.289884       0
5761  20230518   000500    000959  ...    0.302869   0.289966       0
5762  20230518   001000    001459  ...    0.302703   0.290048       0
5763  20230518   001500    001959  ...    0.302538   0.290130       0
5764  20230518   002000    002459  ...    0.302370   0.290212       0

[5 rows x 18 columns]
2023-05-18 00:25:00,428:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684340699, self.tradeDate='20230518', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26754.1, self.close=26778.6, self.high=26783.8, self.low=26754.0, self.vol=655.084, self.amt=17539530.5794, ukdf['pct'].iloc[-1]=0.000916 , ukdf['amount'].iloc[-1]=17539530.5794, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.30236992445753985, signal=0, value_std=0.290211841687148 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2311.60910770816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26781.76125824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230517   120000    155959  1684310399  ...    723  0.786628  1.643496     1.0
724  20230517   160000    195959  1684324799  ...    724  0.722309  1.258142     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '-20544.5145414041', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26626.62763919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1393350.022233, self.flagDict['side']='buy', self.tradeCount=1, self.count=21
self.closeSec=1684339199, self.tradeDate='20230517', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26626.4, self.close=26788.0, self.high=26830.0, self.low=26527.5, self.vol=106131.008, self.amt=2833126103.41978 
127.0.0.1 - - [18/May/2023 00:00:00] "POST / HTTP/1.1" 200 -
2023-05-18 00:00:00,406:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684339199, self.tradeDate='20230517', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26626.4, self.close=26788.0, self.high=26830.0, self.low=26527.5, self.vol=106131.008, self.amt=2833126103.41978 
2023-05-18 00:00:00,485:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230517   040000    075959  ...   28799.999  7.769224e+08  0.003971
722  20230517   080000    115959  ...   48161.970  1.305342e+09  0.001010
723  20230517   120000    155959  ...   53789.861  1.448160e+09 -0.008140
724  20230517   160000    195959  ...   84616.009  2.263006e+09 -0.007655
725  20230517   200000    235959  ...  106131.008  2.833126e+09  0.006065

[5 rows x 11 columns]
2023-05-18 00:00:01,883:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230517   040000    075959  1684281599  ...    721  0.625374  0.766509     1.0
722  20230517   080000    115959  1684295999  ...    722  0.830026  1.936136     1.0
723  20230517   120000    155959  1684310399  ...    723  0.786628  1.643496     1.0
724  20230517   160000    195959  1684324799  ...    724  0.722309  1.258142     1.0
725  20230517   200000    235959  1684339199  ...    725  0.709365  1.165997     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '-12210.926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26788.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


