# 20230521 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [21/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1888
self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26926.6, self.close=26918.3, self.high=26929.5, self.low=26918.3, self.vol=258.808, self.amt=6968688.0059 
2023-05-21 00:20:01,693:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230520   235500    235959  ...    0.301268   0.321730       0
5760  20230521   000000    000459  ...    0.301150   0.321762       0
5761  20230521   000500    000959  ...    0.301034   0.321796       0
5762  20230521   001000    001459  ...    0.300922   0.321830       0
5763  20230521   001500    001959  ...    0.300809   0.321864       0

[5 rows x 18 columns]
2023-05-21 00:20:01,703:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26926.6, self.close=26918.3, self.high=26929.5, self.low=26918.3, self.vol=258.808, self.amt=6968688.0059, ukdf['pct'].iloc[-1]=-0.000312 , ukdf['amount'].iloc[-1]=6968688.0059, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.30080860325142905, signal=0, value_std=0.3218643202897389 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-834.46249862448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26924.82119048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1889
self.closeSec=1684599899, self.tradeDate='20230521', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26918.4, self.close=26907.3, self.high=26921.0, self.low=26905.9, self.vol=594.096, self.amt=15989898.9832 
127.0.0.1 - - [21/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-21 00:25:00,381:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230521   000000    000459  ...    0.301150   0.321762       0
5761  20230521   000500    000959  ...    0.301034   0.321796       0
5762  20230521   001000    001459  ...    0.300922   0.321830       0
5763  20230521   001500    001959  ...    0.300809   0.321864       0
5764  20230521   002000    002459  ...    0.300701   0.321900       0

[5 rows x 18 columns]
2023-05-21 00:25:00,381:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684599899, self.tradeDate='20230521', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26918.4, self.close=26907.3, self.high=26921.0, self.low=26905.9, self.vol=594.096, self.amt=15989898.9832, ukdf['pct'].iloc[-1]=-0.000409 , ukdf['amount'].iloc[-1]=15989898.9832, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.30070144041018615, signal=0, value_std=0.3219002302772318 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-614.34807508338', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26909.01518563', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.5415302622973877, self.count=1890 

self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26926.6, self.close=26918.3, self.high=26929.5, self.low=26918.3 
2023-05-21 00:20:01,033:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26926.6, self.close=26918.3, self.high=26929.5, self.low=26918.3   
2023-05-21 00:20:01,673:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230520   235500    235959  1684598399  ...  26921.9  0.000271   1727    5
1440  20230521   000000    000459  1684598699  ...  26926.4 -0.000241   1440    0
1441  20230521   000500    000959  1684598999  ...  26929.5  0.000171   1441    1
1442  20230521   001000    001459  1684599299  ...  26915.1 -0.000275   1442    2
1443  20230521   001500    001959  1684599599  ...  26918.3 -0.000312   1443    3

[5 rows x 11 columns]
2023-05-21 00:20:01,673:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.5415302622973877, self.count=1891 

self.closeSec=1684599899, self.tradeDate='20230521', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26918.4, self.close=26907.3, self.high=26921.0, self.low=26905.9 
2023-05-21 00:25:00,342:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684599899, self.tradeDate='20230521', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26918.4, self.close=26907.3, self.high=26921.0, self.low=26905.9   
127.0.0.1 - - [21/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-21 00:25:00,370:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230521   000000    000459  1684598699  ...  26926.4 -0.000241   1440    0
1441  20230521   000500    000959  1684598999  ...  26929.5  0.000171   1441    1
1442  20230521   001000    001459  1684599299  ...  26915.1 -0.000275   1442    2
1443  20230521   001500    001959  1684599599  ...  26918.3 -0.000312   1443    3
1444  20230521   002000    002459  1684599899  ...  26905.9 -0.000409   1444    4

[5 rows x 11 columns]
2023-05-21 00:25:00,371:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-21 00:00:17,765:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230520    212959  26882.9  ...  49.583333  0.489717  0.503352
5803  20230520    215959  26875.3  ...  50.000000  0.491014  0.492561
5804  20230520    222959  26878.9  ...  50.416667  0.493004  0.480479
5805  20230520    225959  26884.1  ...  50.416667  0.501154  0.460968
5806  20230520    232959  26906.0  ...  50.416667  0.505860  0.439433

[5 rows x 33 columns]
0.5496323529411765
acc is : 0.5496323529411765
2023-05-21 00:00:17,833:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495375  0.504625       1  ...  0.953683  -1.0    0.0  0.972137
540     1  0.497217  0.502783       1  ...  0.953495  -1.0    0.0  0.972328
541     1  0.498857  0.501143       1  ...  0.952725  -1.0    0.0  0.973113
542     1  0.498862  0.501138       1  ...  0.952279  -1.0    0.0  0.973569
543     0  0.501385  0.498615       1  ...  0.951660  -1.0    0.0  0.974202

[5 rows x 10 columns]
2023-05-21 00:00:17,844:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495828  0.504172       1  ...  0.953683  -1.0    0.0  0.978414
46     1  0.497420  0.502580       1  ...  0.953495  -1.0    0.0  0.976365
47     1  0.499188  0.500812       1  ...  0.952725  -1.0    0.0  0.977153
48     1  0.499017  0.500983       1  ...  0.952279  -1.0    0.0  0.975909
49     0  0.501385  0.498615       1  ...  0.951660  -1.0    0.0  0.974202

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.758', 'enterprice': '26580.2', 'countrevence': '0', 'unrealprofit': '-9719.9033117734', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26930.3658373', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [21/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-05-21 00:00:02,754:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42203F1684598402117I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684598402551524, 'quantity': '26.629', 'price': '26936', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684598400901, 'updatetime': 1684598402551, 'tradetype': 'usdt', 'selfid': 42203, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684598402551, 'clientorderid': '42203F1684598402117I0L59', 'price': '26936', 'quantity': '26.629', 'commission': '717.278744', 'commissionasset': 'USDT', 'tradetime': 1684598402551, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684598402551}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=944 

self.closeSec=1684598999, self.tradeDate='20230521', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26936', self.close='26934.1'
2023-05-21 00:10:00,363:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684598999, self.tradeDate='20230521', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26936', self.close='26934.1'
127.0.0.1 - - [21/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-21 00:10:00,377:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230520   232000    232959  1684596599  26894.9  26918.5  0.000881
573  20230520   233000    233959  1684597199  26918.5  26957.4  0.001445
574  20230520   234000    234959  1684597799  26957.4  26936.5 -0.000775
575  20230520   235000    235959  1684598399  26936.6    26936 -0.000019
576  20230521   000000    000959  1684598999    26936  26934.1 -0.000071
2023-05-21 00:10:00,377:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=945 

self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26934.2', self.close='26918.3'
127.0.0.1 - - [21/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-21 00:20:02,294:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26934.2', self.close='26918.3'
2023-05-21 00:20:02,653:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230520   233000    233959  1684597199  26918.5  26957.4  0.001445
574  20230520   234000    234959  1684597799  26957.4  26936.5 -0.000775
575  20230520   235000    235959  1684598399  26936.6    26936 -0.000019
576  20230521   000000    000959  1684598999    26936  26934.1 -0.000071
577  20230521   001000    001959  1684599599  26934.2  26918.3 -0.000587
2023-05-21 00:20:02,662:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-21 00:00:00,462:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-21 00:00:00,624:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5210000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230520, closeTime:235959, close:26936, total:973579.8686232, pct_pre:-0.002724047325683321, thd:0.2987405811707046, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=947 

self.closeSec=1684598999, self.tradeDate='20230521', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26936', self.close='26934.1'
127.0.0.1 - - [21/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-21 00:10:00,391:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684598999, self.tradeDate='20230521', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26936', self.close='26934.1'
2023-05-21 00:10:00,407:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230520   232000    232959  1684596599  26894.9  26918.5
17421  20230520   233000    233959  1684597199  26918.5  26957.4
17422  20230520   234000    234959  1684597799  26957.4  26936.5
17423  20230520   235000    235959  1684598399  26936.6    26936
17424  20230521   000000    000959  1684598999    26936  26934.1
2023-05-21 00:10:00,409:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=948 

self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26934.2', self.close='26918.3'
127.0.0.1 - - [21/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-21 00:20:03,528:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26934.2', self.close='26918.3'
2023-05-21 00:20:03,606:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230520   233000    233959  1684597199  26918.5  26957.4
17422  20230520   234000    234959  1684597799  26957.4  26936.5
17423  20230520   235000    235959  1684598399  26936.6    26936
17424  20230521   000000    000959  1684598999    26936  26934.1
17425  20230521   001000    001959  1684599599  26934.2  26918.3
2023-05-21 00:20:03,606:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-05-21 00:00:03,016:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42204F1684598402385I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684598402818047, 'quantity': '47.79', 'price': '26936', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684598401183, 'updatetime': 1684598402818, 'tradetype': 'usdt', 'selfid': 42204, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684598402818, 'clientorderid': '42204F1684598402385I0L2', 'price': '26936', 'quantity': '47.79', 'commission': '1287.27144', 'commissionasset': 'USDT', 'tradetime': 1684598402818, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684598402818}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=947 

self.closeSec=1684598999, self.tradeDate='20230521', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26936', self.close='26934.1'
2023-05-21 00:10:00,355:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684598999, self.tradeDate='20230521', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26936', self.close='26934.1'
2023-05-21 00:10:00,379:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230520   232000    232959  1684596599  26894.9  26918.5
12237  20230520   233000    233959  1684597199  26918.5  26957.4
12238  20230520   234000    234959  1684597799  26957.4  26936.5
12239  20230520   235000    235959  1684598399  26936.6    26936
12240  20230521   000000    000959  1684598999    26936  26934.1
2023-05-21 00:10:00,379:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=948 

self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26934.2', self.close='26918.3'
127.0.0.1 - - [21/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-21 00:20:03,224:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26934.2', self.close='26918.3'
2023-05-21 00:20:03,435:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230520   233000    233959  1684597199  26918.5  26957.4
12238  20230520   234000    234959  1684597799  26957.4  26936.5
12239  20230520   235000    235959  1684598399  26936.6    26936
12240  20230521   000000    000959  1684598999    26936  26934.1
12241  20230521   001000    001959  1684599599  26934.2  26918.3
2023-05-21 00:20:03,435:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1888
self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26926.6, self.close=26918.3, self.high=26929.5, self.low=26918.3, self.vol=258.808, self.amt=6968688.0059 
127.0.0.1 - - [21/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-21 00:20:03,193:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230520   235500    235959  ...    0.081347   0.234128       0
5760  20230521   000000    000459  ...    0.081034   0.233834       0
5761  20230521   000500    000959  ...    0.080722   0.233543       0
5762  20230521   001000    001459  ...    0.080415   0.233260       0
5763  20230521   001500    001959  ...    0.080110   0.232982       0

[5 rows x 18 columns]
2023-05-21 00:20:03,202:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684599599, self.tradeDate='20230521', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26926.6, self.close=26918.3, self.high=26929.5, self.low=26918.3, self.vol=258.808, self.amt=6968688.0059, ukdf['pct'].iloc[-1]=-0.000312 , ukdf['amount'].iloc[-1]=6968688.0059, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.08010961286401987, signal=0, value_std=0.2329815061019865 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2998.73471559558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26924.73920238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1889
self.closeSec=1684599899, self.tradeDate='20230521', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26918.4, self.close=26907.3, self.high=26921.0, self.low=26905.9, self.vol=594.096, self.amt=15989898.9832 
127.0.0.1 - - [21/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-21 00:25:00,397:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230521   000000    000459  ...    0.081034   0.233834       0
5761  20230521   000500    000959  ...    0.080722   0.233543       0
5762  20230521   001000    001459  ...    0.080415   0.233260       0
5763  20230521   001500    001959  ...    0.080110   0.232982       0
5764  20230521   002000    002459  ...    0.079804   0.232701       0

[5 rows x 18 columns]
2023-05-21 00:25:00,397:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684599899, self.tradeDate='20230521', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26918.4, self.close=26907.3, self.high=26921.0, self.low=26905.9, self.vol=594.096, self.amt=15989898.9832, ukdf['pct'].iloc[-1]=-0.000409 , ukdf['amount'].iloc[-1]=15989898.9832, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.07980371735462179, signal=0, value_std=0.2327007533181415 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2414.72900948383', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26909.01518563', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230520   120000    155959  1684569599  ...    723  0.198884 -1.451841    -1.0
724  20230520   160000    195959  1684583999  ...    724  0.187873 -1.475185    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '10389.14489506092', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26868.96078692', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [21/May/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=39
self.closeSec=1684598399, self.tradeDate='20230520', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26868.5, self.close=26936.0, self.high=26969.8, self.low=26857.1, self.vol=25544.438, self.amt=687279317.5301 
2023-05-21 00:00:00,341:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684598399, self.tradeDate='20230520', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26868.5, self.close=26936.0, self.high=26969.8, self.low=26857.1, self.vol=25544.438, self.amt=687279317.5301 
2023-05-21 00:00:00,480:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230520   040000    075959  ...  17666.894  4.744511e+08  0.001629
722  20230520   080000    115959  ...  13932.879  3.740527e+08 -0.000778
723  20230520   120000    155959  ...   9537.697  2.560345e+08 -0.000276
724  20230520   160000    195959  ...  15215.481  4.089376e+08  0.000998
725  20230520   200000    235959  ...  25544.438  6.872793e+08  0.002509

[5 rows x 11 columns]
2023-05-21 00:00:01,926:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230520   040000    075959  1684540799  ...    721  0.224054 -1.382607    -1.0
722  20230520   080000    115959  1684555199  ...    722  0.201823 -1.471486    -1.0
723  20230520   120000    155959  1684569599  ...    723  0.198884 -1.451841    -1.0
724  20230520   160000    195959  1684583999  ...    724  0.187873 -1.475185    -1.0
725  20230520   200000    235959  1684598399  ...    725  0.175194 -1.504185    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '6933.3405', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26936', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


