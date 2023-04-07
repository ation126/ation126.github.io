# 20230408 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37852
self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27916.9, self.close=27898.3, self.high=27917.0, self.low=27898.3, self.vol=519.562, self.amt=14497840.4727 
127.0.0.1 - - [08/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-08 00:20:09,690:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230407   235500    235959  ...         0.0        0.0       0
5760  20230408   000000    000459  ...         0.0        0.0       0
5761  20230408   000500    000959  ...         0.0        0.0       0
5762  20230408   001000    001459  ...         0.0        0.0       0
5763  20230408   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 00:20:09,711:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27916.9, self.close=27898.3, self.high=27917.0, self.low=27898.3, self.vol=519.562, self.amt=14497840.4727, ukdf['pct'].iloc[-1]=-0.00067 , ukdf['amount'].iloc[-1]=14497840.4727, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-684177.0496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27898.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37853
self.closeSec=1680884699, self.tradeDate='20230408', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27898.3, self.close=27876.9, self.high=27902.1, self.low=27873.5, self.vol=951.572, self.amt=26539070.3826 
127.0.0.1 - - [08/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-08 00:25:01,603:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230408   000000    000459  ...         0.0        0.0       0
5761  20230408   000500    000959  ...         0.0        0.0       0
5762  20230408   001000    001459  ...         0.0        0.0       0
5763  20230408   001500    001959  ...         0.0        0.0       0
5764  20230408   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 00:25:01,608:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680884699, self.tradeDate='20230408', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27898.3, self.close=27876.9, self.high=27902.1, self.low=27873.5, self.vol=951.572, self.amt=26539070.3826, ukdf['pct'].iloc[-1]=-0.000767 , ukdf['amount'].iloc[-1]=26539070.3826, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-682966.00014660064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27878.77487614', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27916.9, self.close=27898.3, self.high=27917.0, self.low=27898.3 
127.0.0.1 - - [08/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-08 00:20:06,761:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27916.9, self.close=27898.3, self.high=27917.0, self.low=27898.3   
2023-04-08 00:20:07,970:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230407   235500    235959  1680883199  ...  27923.5  0.000236   1727    5
1440  20230408   000000    000459  1680883499  ...  27924.6 -0.000007   1440    0
1441  20230408   000500    000959  1680883799  ...  27922.6 -0.000172   1441    1
1442  20230408   001000    001459  1680884099  ...  27913.7 -0.000294   1442    2
1443  20230408   001500    001959  1680884399  ...  27898.3 -0.000670   1443    3

[5 rows x 11 columns]
2023-04-08 00:20:07,980:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=40, self.factor=0.5720217893744579, self.count=38419 

self.closeSec=1680884699, self.tradeDate='20230408', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27898.3, self.close=27876.9, self.high=27902.1, self.low=27873.5 
2023-04-08 00:25:01,520:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680884699, self.tradeDate='20230408', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27898.3, self.close=27876.9, self.high=27902.1, self.low=27873.5   
2023-04-08 00:25:01,599:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230408   000000    000459  1680883499  ...  27924.6 -0.000007   1440    0
1441  20230408   000500    000959  1680883799  ...  27922.6 -0.000172   1441    1
1442  20230408   001000    001459  1680884099  ...  27913.7 -0.000294   1442    2
1443  20230408   001500    001959  1680884399  ...  27898.3 -0.000670   1443    3
1444  20230408   002000    002459  1680884699  ...  27873.5 -0.000767   1444    4

[5 rows x 11 columns]
2023-04-08 00:25:01,599:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-08 00:00:33,744:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230407    212959  27876.1  ...  47.916667  0.461892  0.579253
5803  20230407    215959  27839.2  ...  47.916667  0.472010  0.583344
5804  20230407    222959  27883.3  ...  47.916667  0.485463  0.575939
5805  20230407    225959  27943.4  ...  47.916667  0.476516  0.577132
5806  20230407    232959  27900.0  ...  47.916667  0.475486  0.579180

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-04-08 00:00:33,892:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.503944  0.496056       1  ...  0.956523   1.0    0.0  1.003195
540     0  0.523079  0.476921       1  ...  0.958585   1.0    0.0  1.005357
541     0  0.534450  0.465550       0  ...  0.957096   1.0    0.0  1.003796
542     0  0.506706  0.493294       0  ...  0.956924   1.0    0.0  1.003616
543     0  0.516336  0.483664       1  ...  0.958132   1.0    0.0  1.004882

[5 rows x 10 columns]
2023-04-08 00:00:33,927:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503999  0.496001       1  ...  0.956523   1.0    0.0  1.004228
46     0  0.522645  0.477355       1  ...  0.958585   1.0    0.0  1.006244
47     0  0.534451  0.465549       0  ...  0.957096   1.0    0.0  1.004681
48     0  0.506266  0.493734       0  ...  0.956924   1.0    0.0  1.003605
49     0  0.516336  0.483664       1  ...  0.958132   1.0    0.0  1.004882

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [08/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-08 00:00:03,554:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42130F1680883202867I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680883203242783, 'quantity': '24.41', 'price': '27930.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680883202416, 'updatetime': 1680883203242, 'tradetype': 'usdt', 'selfid': 42130, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680883203242, 'clientorderid': '42130F1680883202867I0L59', 'price': '27930.2', 'quantity': '24.41', 'commission': '681.776182', 'commissionasset': 'USDT', 'tradetime': 1680883203242, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680883203242}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19208 

self.closeSec=1680883799, self.tradeDate='20230408', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27930.2', self.close='27925.2'
127.0.0.1 - - [08/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-08 00:10:01,730:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680883799, self.tradeDate='20230408', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27930.2', self.close='27925.2'
2023-04-08 00:10:01,752:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230407   232000    232959  1680881399  27927.9    27895 -0.001182
573  20230407   233000    233959  1680881999  27894.9    27907  0.000430
574  20230407   234000    234959  1680882599  27907.1  27920.7  0.000491
575  20230407   235000    235959  1680883199  27920.7  27930.2  0.000340
576  20230408   000000    000959  1680883799  27930.2  27925.2 -0.000179
2023-04-08 00:10:01,753:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19209 

self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27925.2', self.close='27898.3'
127.0.0.1 - - [08/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-08 00:20:08,059:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27925.2', self.close='27898.3'
2023-04-08 00:20:08,990:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230407   233000    233959  1680881999  27894.9    27907  0.000430
574  20230407   234000    234959  1680882599  27907.1  27920.7  0.000491
575  20230407   235000    235959  1680883199  27920.7  27930.2  0.000340
576  20230408   000000    000959  1680883799  27930.2  27925.2 -0.000179
577  20230408   001000    001959  1680884399  27925.2  27898.3 -0.000963
2023-04-08 00:20:08,999:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-04-08 00:00:02,089:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-04-08 00:00:02,242:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:4080000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230407, closeTime:235959, close:27930.2, total:978039.764104, pct_pre:-0.00818099289770191, thd:-0.08762831467312687, side:sell 
127.0.0.1 - - [08/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19209 

self.closeSec=1680883799, self.tradeDate='20230408', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27930.2', self.close='27925.2'
2023-04-08 00:10:01,743:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680883799, self.tradeDate='20230408', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27930.2', self.close='27925.2'
2023-04-08 00:10:01,776:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230407   232000    232959  1680881399  27927.9    27895
17421  20230407   233000    233959  1680881999  27894.9    27907
17422  20230407   234000    234959  1680882599  27907.1  27920.7
17423  20230407   235000    235959  1680883199  27920.7  27930.2
17424  20230408   000000    000959  1680883799  27930.2  27925.2
2023-04-08 00:10:01,776:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19210 

self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27925.2', self.close='27898.3'
127.0.0.1 - - [08/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-08 00:20:11,552:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27925.2', self.close='27898.3'
2023-04-08 00:20:11,707:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230407   233000    233959  1680881999  27894.9    27907
17422  20230407   234000    234959  1680882599  27907.1  27920.7
17423  20230407   235000    235959  1680883199  27920.7  27930.2
17424  20230408   000000    000959  1680883799  27930.2  27925.2
17425  20230408   001000    001959  1680884399  27925.2  27898.3
2023-04-08 00:20:11,707:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [08/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-08 00:00:03,177:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42129F1680883202703I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680883202826171, 'quantity': '46.279', 'price': '27930.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680883202368, 'updatetime': 1680883202826, 'tradetype': 'usdt', 'selfid': 42129, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680883202826, 'clientorderid': '42129F1680883202703I0L2', 'price': '27930.3', 'quantity': '46.279', 'commission': '1292.5863537', 'commissionasset': 'USDT', 'tradetime': 1680883202826, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680883202826}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19209 

self.closeSec=1680883799, self.tradeDate='20230408', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27930.2', self.close='27925.2'
2023-04-08 00:10:01,743:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680883799, self.tradeDate='20230408', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27930.2', self.close='27925.2'
2023-04-08 00:10:01,772:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230407   232000    232959  1680881399  27927.9    27895
12237  20230407   233000    233959  1680881999  27894.9    27907
12238  20230407   234000    234959  1680882599  27907.1  27920.7
12239  20230407   235000    235959  1680883199  27920.7  27930.2
12240  20230408   000000    000959  1680883799  27930.2  27925.2
2023-04-08 00:10:01,773:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19210 

self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27925.2', self.close='27898.3'
127.0.0.1 - - [08/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-08 00:20:10,981:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27925.2', self.close='27898.3'
2023-04-08 00:20:11,301:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230407   233000    233959  1680881999  27894.9    27907
12238  20230407   234000    234959  1680882599  27907.1  27920.7
12239  20230407   235000    235959  1680883199  27920.7  27930.2
12240  20230408   000000    000959  1680883799  27930.2  27925.2
12241  20230408   001000    001959  1680884399  27925.2  27898.3
2023-04-08 00:20:11,301:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33850
self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27916.9, self.close=27898.3, self.high=27917.0, self.low=27898.3, self.vol=519.562, self.amt=14497840.4727 
127.0.0.1 - - [08/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-08 00:20:09,370:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230407   235500    235959  ...         0.0        0.0       0
5760  20230408   000000    000459  ...         0.0        0.0       0
5761  20230408   000500    000959  ...         0.0        0.0       0
5762  20230408   001000    001459  ...         0.0        0.0       0
5763  20230408   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 00:20:09,400:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680884399, self.tradeDate='20230408', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27916.9, self.close=27898.3, self.high=27917.0, self.low=27898.3, self.vol=519.562, self.amt=14497840.4727, ukdf['pct'].iloc[-1]=-0.00067 , ukdf['amount'].iloc[-1]=14497840.4727, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33851
self.closeSec=1680884699, self.tradeDate='20230408', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27898.3, self.close=27876.9, self.high=27902.1, self.low=27873.5, self.vol=951.572, self.amt=26539070.3826 
2023-04-08 00:25:01,630:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230408   000000    000459  ...         0.0        0.0       0
5761  20230408   000500    000959  ...         0.0        0.0       0
5762  20230408   001000    001459  ...         0.0        0.0       0
5763  20230408   001500    001959  ...         0.0        0.0       0
5764  20230408   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 00:25:01,630:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680884699, self.tradeDate='20230408', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27898.3, self.close=27876.9, self.high=27902.1, self.low=27873.5, self.vol=951.572, self.amt=26539070.3826, ukdf['pct'].iloc[-1]=-0.000767 , ukdf['amount'].iloc[-1]=26539070.3826, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230407   120000    155959  1680854399  ...    723  0.137208 -0.434237     NaN
724  20230407   160000    195959  1680868799  ...    724  0.120385 -0.514724     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '29674.36754189336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27829.10318803', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=800
self.closeSec=1680883199, self.tradeDate='20230407', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27829.9, self.close=27930.2, self.high=27981.1, self.low=27776.5, self.vol=58901.765, self.amt=1642831389.4064 
127.0.0.1 - - [08/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-08 00:00:01,931:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680883199, self.tradeDate='20230407', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27829.9, self.close=27930.2, self.high=27981.1, self.low=27776.5, self.vol=58901.765, self.amt=1642831389.4064 
2023-04-08 00:00:01,983:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230407   040000    075959  ...  34378.119  9.624497e+08  0.000636
722  20230407   080000    115959  ...  27954.246  7.831085e+08 -0.000021
723  20230407   120000    155959  ...  43961.294  1.226721e+09 -0.007141
724  20230407   160000    195959  ...  47979.773  1.336970e+09  0.000255
725  20230407   200000    235959  ...  58901.765  1.642831e+09  0.003629

[5 rows x 11 columns]
2023-04-08 00:00:04,938:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230407   040000    075959  1680825599  ...    721  0.131946 -0.455118     NaN
722  20230407   080000    115959  1680839999  ...    722  0.122961 -0.495959     NaN
723  20230407   120000    155959  1680854399  ...    723  0.137208 -0.434237     NaN
724  20230407   160000    195959  1680868799  ...    724  0.120385 -0.514724     NaN
725  20230407   200000    235959  1680883199  ...    725  0.126587 -0.494260     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '24223.33541379752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27933.75362821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


