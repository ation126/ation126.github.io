# 20230603 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5632
self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27029.4, self.close=27026.0, self.high=27044.3, self.low=27017.7, self.vol=829.923, self.amt=22432743.1157 
127.0.0.1 - - [03/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-03 00:20:06,269:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230602   235500    235959  ...         0.0        0.0       0
5760  20230603   000000    000459  ...         0.0        0.0       0
5761  20230603   000500    000959  ...         0.0        0.0       0
5762  20230603   001000    001459  ...         0.0        0.0       0
5763  20230603   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 00:20:06,299:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27029.4, self.close=27026.0, self.high=27044.3, self.low=27017.7, self.vol=829.923, self.amt=22432743.1157, ukdf['pct'].iloc[-1]=-3.3e-05 , ukdf['amount'].iloc[-1]=22432743.1157, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2321.4642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27031.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5633
self.closeSec=1685723099, self.tradeDate='20230603', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27025.9, self.close=27021.2, self.high=27055.1, self.low=27021.2, self.vol=704.064, self.amt=19039183.6009 
127.0.0.1 - - [03/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-03 00:25:00,831:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230603   000000    000459  ...         0.0        0.0       0
5761  20230603   000500    000959  ...         0.0        0.0       0
5762  20230603   001000    001459  ...         0.0        0.0       0
5763  20230603   001500    001959  ...         0.0        0.0       0
5764  20230603   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 00:25:00,834:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685723099, self.tradeDate='20230603', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27025.9, self.close=27021.2, self.high=27055.1, self.low=27021.2, self.vol=704.064, self.amt=19039183.6009, ukdf['pct'].iloc[-1]=-0.000178 , ukdf['amount'].iloc[-1]=19039183.6009, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2236.41167081904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27025.49253704', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27029.4, self.close=27026.0, self.high=27044.3, self.low=27017.7 
127.0.0.1 - - [03/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-03 00:20:04,183:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27029.4, self.close=27026.0, self.high=27044.3, self.low=27017.7   
2023-06-03 00:20:05,358:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230602   235500    235959  1685721599  ...  27045.1  0.000425   1727    5
1440  20230603   000000    000459  1685721899  ...  27042.6 -0.001071   1440    0
1441  20230603   000500    000959  1685722199  ...  27048.9  0.000344   1441    1
1442  20230603   001000    001459  1685722499  ...  27026.9 -0.001282   1442    2
1443  20230603   001500    001959  1685722799  ...  27017.7 -0.000033   1443    3

[5 rows x 11 columns]
2023-06-03 00:20:05,369:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.46195328909965827, self.count=5635 

self.closeSec=1685723099, self.tradeDate='20230603', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27025.9, self.close=27021.2, self.high=27055.1, self.low=27021.2 
2023-06-03 00:25:00,732:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685723099, self.tradeDate='20230603', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27025.9, self.close=27021.2, self.high=27055.1, self.low=27021.2   
2023-06-03 00:25:00,810:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230603   000000    000459  1685721899  ...  27042.6 -0.001071   1440    0
1441  20230603   000500    000959  1685722199  ...  27048.9  0.000344   1441    1
1442  20230603   001000    001459  1685722499  ...  27026.9 -0.001282   1442    2
1443  20230603   001500    001959  1685722799  ...  27017.7 -0.000033   1443    3
1444  20230603   002000    002459  1685723099  ...  27021.2 -0.000178   1444    4

[5 rows x 11 columns]
2023-06-03 00:25:00,811:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-03 00:00:33,707:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5802  20230602    212959  27084.6  ...    48.75  0.503446  0.260646
5803  20230602    215959  27066.1  ...    48.75  0.467637  0.273765
5804  20230602    222959  26896.4  ...    48.75  0.471657  0.284472
5805  20230602    225959  26914.2  ...    48.75  0.480185  0.291191
5806  20230602    232959  26952.0  ...    48.75  0.488957  0.294049

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-06-03 00:00:33,868:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.490036  0.509964       0  ...  1.023387   1.0    0.0  1.002445
540     1  0.452523  0.547477       1  ...  1.024064   1.0    0.0  1.003108
541     1  0.481033  0.518967       1  ...  1.025506   1.0    0.0  1.004521
542     1  0.487624  0.512376       1  ...  1.027009   1.0    0.0  1.005993
543     1  0.492771  0.507229       1  ...  1.030426   1.0    0.0  1.009340

[5 rows x 10 columns]
2023-06-03 00:00:33,896:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489975  0.510025       0  ...  1.023387   1.0    0.0  1.000491
46     1  0.452612  0.547388       1  ...  1.024064   1.0    0.0  1.003894
47     1  0.480995  0.519005       1  ...  1.025506   1.0    0.0  1.005308
48     1  0.487520  0.512480       1  ...  1.027009   1.0    0.0  1.005866
49     1  0.492771  0.507229       1  ...  1.030426   1.0    0.0  1.009340

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '2999.8578', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27097.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [03/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-03 00:00:04,387:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42307F1685721603635I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685721603993508, 'quantity': '25.162', 'price': '27081.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685721602745, 'updatetime': 1685721603993, 'tradetype': 'usdt', 'selfid': 42307, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685721603993, 'clientorderid': '42307F1685721603635I0L59', 'price': '27081.2', 'quantity': '25.162', 'commission': '681.4171544', 'commissionasset': 'USDT', 'tradetime': 1685721603993, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685721603993}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2816 

self.closeSec=1685722199, self.tradeDate='20230603', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27081.3', self.close='27061.6'
127.0.0.1 - - [03/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-03 00:10:01,069:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685722199, self.tradeDate='20230603', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27081.3', self.close='27061.6'
2023-06-03 00:10:01,091:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230602   232000    232959  1685719799  26995.3  26991.5 -0.000144
573  20230602   233000    233959  1685720399  26990.4  26990.1 -0.000052
574  20230602   234000    234959  1685720999    26990  27004.7  0.000541
575  20230602   235000    235959  1685721599  27004.8  27081.3  0.002837
576  20230603   000000    000959  1685722199  27081.3  27061.6 -0.000727
2023-06-03 00:10:01,091:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2817 

self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27061.6', self.close='27026'
127.0.0.1 - - [03/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-03 00:20:06,588:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27061.6', self.close='27026'
2023-06-03 00:20:07,239:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230602   233000    233959  1685720399  26990.4  26990.1 -0.000052
574  20230602   234000    234959  1685720999    26990  27004.7  0.000541
575  20230602   235000    235959  1685721599  27004.8  27081.3  0.002837
576  20230603   000000    000959  1685722199  27081.3  27061.6 -0.000727
577  20230603   001000    001959  1685722799  27061.6    27026 -0.001316
2023-06-03 00:20:07,249:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-03 00:00:04,157:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42306F1685721603466I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685721603885024, 'quantity': '35.862', 'price': '27081.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685721602667, 'updatetime': 1685721603885, 'tradetype': 'usdt', 'selfid': 42306, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685721603885, 'clientorderid': '42306F1685721603466I0L57', 'price': '27081.2', 'quantity': '35.862', 'commission': '971.1859944', 'commissionasset': 'USDT', 'tradetime': 1685721603885, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685721603885}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2819 

self.closeSec=1685722199, self.tradeDate='20230603', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27081.3', self.close='27061.6'
2023-06-03 00:10:01,090:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685722199, self.tradeDate='20230603', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27081.3', self.close='27061.6'
127.0.0.1 - - [03/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-03 00:10:01,104:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230602   232000    232959  1685719799  26995.3  26991.5
17421  20230602   233000    233959  1685720399  26990.4  26990.1
17422  20230602   234000    234959  1685720999    26990  27004.7
17423  20230602   235000    235959  1685721599  27004.8  27081.3
17424  20230603   000000    000959  1685722199  27081.3  27061.6
2023-06-03 00:10:01,105:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2820 

self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27061.6', self.close='27026'
127.0.0.1 - - [03/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-03 00:20:08,329:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27061.6', self.close='27026'
2023-06-03 00:20:08,444:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230602   233000    233959  1685720399  26990.4  26990.1
17422  20230602   234000    234959  1685720999    26990  27004.7
17423  20230602   235000    235959  1685721599  27004.8  27081.3
17424  20230603   000000    000959  1685722199  27081.3  27061.6
17425  20230603   001000    001959  1685722799  27061.6    27026
2023-06-03 00:20:08,444:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [03/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-03 00:00:04,667:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42308F1685721603668I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685721604030528, 'quantity': '44.14', 'price': '27081.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685721602782, 'updatetime': 1685721604030, 'tradetype': 'usdt', 'selfid': 42308, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685721604030, 'clientorderid': '42308F1685721603668I0L2', 'price': '27081.2', 'quantity': '44.14', 'commission': '1195.364168', 'commissionasset': 'USDT', 'tradetime': 1685721604030, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685721604030}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2819 

self.closeSec=1685722199, self.tradeDate='20230603', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27081.3', self.close='27061.6'
127.0.0.1 - - [03/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-03 00:10:01,087:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685722199, self.tradeDate='20230603', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27081.3', self.close='27061.6'
2023-06-03 00:10:01,102:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230602   232000    232959  1685719799  26995.3  26991.5
12237  20230602   233000    233959  1685720399  26990.4  26990.1
12238  20230602   234000    234959  1685720999    26990  27004.7
12239  20230602   235000    235959  1685721599  27004.8  27081.3
12240  20230603   000000    000959  1685722199  27081.3  27061.6
2023-06-03 00:10:01,103:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2820 

self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27061.6', self.close='27026'
127.0.0.1 - - [03/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-03 00:20:08,001:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27061.6', self.close='27026'
2023-06-03 00:20:08,284:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230602   233000    233959  1685720399  26990.4  26990.1
12238  20230602   234000    234959  1685720999    26990  27004.7
12239  20230602   235000    235959  1685721599  27004.8  27081.3
12240  20230603   000000    000959  1685722199  27081.3  27061.6
12241  20230603   001000    001959  1685722799  27061.6    27026
2023-06-03 00:20:08,287:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5632
self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27029.4, self.close=27026.0, self.high=27044.3, self.low=27017.7, self.vol=829.923, self.amt=22432743.1157 
127.0.0.1 - - [03/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-03 00:20:06,259:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230602   235500    235959  ...         0.0        0.0       0
5760  20230603   000000    000459  ...         0.0        0.0       0
5761  20230603   000500    000959  ...         0.0        0.0       0
5762  20230603   001000    001459  ...         0.0        0.0       0
5763  20230603   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 00:20:06,288:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685722799, self.tradeDate='20230603', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27029.4, self.close=27026.0, self.high=27044.3, self.low=27017.7, self.vol=829.923, self.amt=22432743.1157, ukdf['pct'].iloc[-1]=-3.3e-05 , ukdf['amount'].iloc[-1]=22432743.1157, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '6967.6516', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27031.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5633
self.closeSec=1685723099, self.tradeDate='20230603', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27025.9, self.close=27021.2, self.high=27055.1, self.low=27021.2, self.vol=704.064, self.amt=19039183.6009 
2023-06-03 00:25:00,836:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230603   000000    000459  ...         0.0        0.0       0
5761  20230603   000500    000959  ...         0.0        0.0       0
5762  20230603   001000    001459  ...         0.0        0.0       0
5763  20230603   001500    001959  ...         0.0        0.0       0
5764  20230603   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-03 00:25:00,837:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685723099, self.tradeDate='20230603', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27025.9, self.close=27021.2, self.high=27055.1, self.low=27021.2, self.vol=704.064, self.amt=19039183.6009, ukdf['pct'].iloc[-1]=-0.000178 , ukdf['amount'].iloc[-1]=19039183.6009, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '6740.81431820264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27025.49253704', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230602   120000    155959  1685692799  ...    723  0.670010  0.405017     NaN
724  20230602   160000    195959  1685707199  ...    724  0.673301  0.405992     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '54748.18234327704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27119.13526296', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=117
self.closeSec=1685721599, self.tradeDate='20230602', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27118.5, self.close=27081.3, self.high=27249.3, self.low=26840.5, self.vol=120542.039, self.amt=3257225807.09148 
127.0.0.1 - - [03/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-03 00:00:01,812:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685721599, self.tradeDate='20230602', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27118.5, self.close=27081.3, self.high=27249.3, self.low=26840.5, self.vol=120542.039, self.amt=3257225807.09148 
2023-06-03 00:00:01,829:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230602   040000    075959  ...   37327.512  1.001886e+09 -0.001724
722  20230602   080000    115959  ...   85456.975  2.287551e+09  0.006708
723  20230602   120000    155959  ...   61632.613  1.669195e+09  0.001971
724  20230602   160000    195959  ...   36192.899  9.809580e+08  0.002966
725  20230602   200000    235959  ...  120542.039  3.257226e+09 -0.001372

[5 rows x 11 columns]
2023-06-03 00:00:03,859:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230602   040000    075959  1685663999  ...    721  0.777972  0.742572     1.0
722  20230602   080000    115959  1685678399  ...    722  0.727542  0.583283     NaN
723  20230602   120000    155959  1685692799  ...    723  0.670010  0.405017     NaN
724  20230602   160000    195959  1685707199  ...    724  0.673301  0.405992     NaN
725  20230602   200000    235959  1685721599  ...    725  0.666727  0.377153     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '52839.62876108852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27084.59068148', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


