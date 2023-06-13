# 20230613 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8608
self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25928.9, self.close=25988.7, self.high=26026.0, self.low=25928.9, self.vol=4907.332, self.amt=127506206.2097 
127.0.0.1 - - [13/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-13 08:20:03,185:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230613   075500    075959  ...         0.0        0.0       0
5856  20230613   080000    080459  ...         0.0        0.0       0
5857  20230613   080500    080959  ...         0.0        0.0       0
5858  20230613   081000    081459  ...         0.0        0.0       0
5859  20230613   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 08:20:03,215:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25928.9, self.close=25988.7, self.high=26026.0, self.low=25928.9, self.vol=4907.332, self.amt=127506206.2097, ukdf['pct'].iloc[-1]=0.002306 , ukdf['amount'].iloc[-1]=127506206.2097, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12050.1678', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25999.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8609
self.closeSec=1686615899, self.tradeDate='20230613', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25988.8, self.close=25970.5, self.high=26006.7, self.low=25942.8, self.vol=1380.282, self.amt=35843335.2695 
127.0.0.1 - - [13/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-13 08:25:04,350:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230613   080000    080459  ...         0.0        0.0       0
5857  20230613   080500    080959  ...         0.0        0.0       0
5858  20230613   081000    081459  ...         0.0        0.0       0
5859  20230613   081500    081959  ...         0.0        0.0       0
5860  20230613   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 08:25:04,361:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686615899, self.tradeDate='20230613', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25988.8, self.close=25970.5, self.high=26006.7, self.low=25942.8, self.vol=1380.282, self.amt=35843335.2695, ukdf['pct'].iloc[-1]=-0.0007 , ukdf['amount'].iloc[-1]=35843335.2695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12502.5506547975', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25967.11523375', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25928.9, self.close=25988.7, self.high=26026.0, self.low=25928.9 
127.0.0.1 - - [13/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-13 08:20:01,944:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25928.9, self.close=25988.7, self.high=26026.0, self.low=25928.9   
2023-06-13 08:20:02,824:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230613   075500    075959  1686614399  ...  25880.9  0.000529   1535    5
1536  20230613   080000    080459  1686614699  ...  25877.7  0.000405   1536    0
1537  20230613   080500    080959  1686614999  ...  25880.0 -0.000490   1537    1
1538  20230613   081000    081459  1686615299  ...  25897.0  0.001406   1538    2
1539  20230613   081500    081959  1686615599  ...  25928.9  0.002306   1539    3

[5 rows x 11 columns]
2023-06-13 08:20:02,834:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=26, self.factor=0.47143509722644644, self.count=8611 

self.closeSec=1686615899, self.tradeDate='20230613', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25988.8, self.close=25970.5, self.high=26006.7, self.low=25942.8 
127.0.0.1 - - [13/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-13 08:25:03,107:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686615899, self.tradeDate='20230613', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25988.8, self.close=25970.5, self.high=26006.7, self.low=25942.8   
2023-06-13 08:25:03,968:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230613   080000    080459  1686614699  ...  25877.7  0.000405   1536    0
1537  20230613   080500    080959  1686614999  ...  25880.0 -0.000490   1537    1
1538  20230613   081000    081459  1686615299  ...  25897.0  0.001406   1538    2
1539  20230613   081500    081959  1686615599  ...  25928.9  0.002306   1539    3
1540  20230613   082000    082459  1686615899  ...  25942.8 -0.000700   1540    4

[5 rows x 11 columns]
2023-06-13 08:25:03,970:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-13 08:00:39,683:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230613    052959  25886.0  ...  49.583333  0.498974  0.538281
5771  20230613    055959  25877.2  ...  50.000000  0.508236  0.526386
5772  20230613    062959  25918.7  ...  49.583333  0.501992  0.520783
5773  20230613    065959  25891.3  ...  49.583333  0.508781  0.511743
5774  20230613    072959  25921.4  ...  49.166667  0.504931  0.505710

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2023-06-13 08:00:39,880:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.503941  0.496059       1  ...  1.005475  -1.0    0.0  0.960115
537     0  0.521810  0.478190       0  ...  1.006534  -1.0    0.0  0.959104
538     0  0.503351  0.496649       1  ...  1.005364  -1.0    0.0  0.960219
539     0  0.511441  0.488559       0  ...  1.006004  -1.0    0.0  0.959608
540     0  0.500900  0.499100       0  ...  1.006400  -1.0    0.0  0.959230

[5 rows x 10 columns]
2023-06-13 08:00:39,913:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504043  0.495957       1  ...  0.981450  -1.0    0.0  0.964083
46     0  0.521726  0.478274       0  ...  0.982483  -1.0    0.0  0.962817
47     0  0.503203  0.496797       1  ...  0.981341  -1.0    0.0  0.957184
48     0  0.511570  0.488430       0  ...  1.006004  -1.0    0.0  0.959608
49     0  0.500900  0.499100       0  ...  1.006400  -1.0    0.0  0.959230

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-9613.6508', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25900', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230613   075000    075959  1686614399  25886.7  25894.7  0.000305
2023-06-13 08:00:02,413:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4304 

self.closeSec=1686614999, self.tradeDate='20230613', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25894.8', self.close='25897'
2023-06-13 08:10:01,113:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686614999, self.tradeDate='20230613', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25894.8', self.close='25897'
127.0.0.1 - - [13/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-13 08:10:01,144:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230613   072000    072959  1686612599  25904.8  25904.9  0.000004
621  20230613   073000    073959  1686613199  25904.9  25902.2 -0.000104
622  20230613   074000    074959  1686613799  25902.2  25886.8 -0.000595
623  20230613   075000    075959  1686614399  25886.7  25894.7  0.000305
624  20230613   080000    080959  1686614999  25894.8    25897  0.000089
2023-06-13 08:10:01,144:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4305 

self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25897.1', self.close='25988.7'
127.0.0.1 - - [13/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-13 08:20:05,004:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25897.1', self.close='25988.7'
2023-06-13 08:20:05,653:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230613   073000    073959  1686613199  25904.9  25902.2 -0.000104
622  20230613   074000    074959  1686613799  25902.2  25886.8 -0.000595
623  20230613   075000    075959  1686614399  25886.7  25894.7  0.000305
624  20230613   080000    080959  1686614999  25894.8    25897  0.000089
625  20230613   081000    081959  1686615599  25897.1  25988.7  0.003541
2023-06-13 08:20:05,654:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230613   075000    075959  1686614399  25886.7  25894.7
2023-06-13 08:00:02,436:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4307 

self.closeSec=1686614999, self.tradeDate='20230613', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25894.8', self.close='25897'
2023-06-13 08:10:01,174:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686614999, self.tradeDate='20230613', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25894.8', self.close='25897'
2023-06-13 08:10:01,234:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230613   072000    072959  1686612599  25904.8  25904.9
17469  20230613   073000    073959  1686613199  25904.9  25902.2
17470  20230613   074000    074959  1686613799  25902.2  25886.8
17471  20230613   075000    075959  1686614399  25886.7  25894.7
17472  20230613   080000    080959  1686614999  25894.8    25897
2023-06-13 08:10:01,235:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4308 

self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25897.1', self.close='25988.7'
127.0.0.1 - - [13/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-13 08:20:06,438:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25897.1', self.close='25988.7'
2023-06-13 08:20:06,529:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230613   073000    073959  1686613199  25904.9  25902.2
17470  20230613   074000    074959  1686613799  25902.2  25886.8
17471  20230613   075000    075959  1686614399  25886.7  25894.7
17472  20230613   080000    080959  1686614999  25894.8    25897
17473  20230613   081000    081959  1686615599  25897.1  25988.7
2023-06-13 08:20:06,529:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230613   075000    075959  1686614399  25886.7  25894.7
2023-06-13 08:00:02,423:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4307 

self.closeSec=1686614999, self.tradeDate='20230613', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25894.8', self.close='25897'
2023-06-13 08:10:01,126:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686614999, self.tradeDate='20230613', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25894.8', self.close='25897'
127.0.0.1 - - [13/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-13 08:10:01,157:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230613   072000    072959  1686612599  25904.8  25904.9
12141  20230613   073000    073959  1686613199  25904.9  25902.2
12142  20230613   074000    074959  1686613799  25902.2  25886.8
12143  20230613   075000    075959  1686614399  25886.7  25894.7
12144  20230613   080000    080959  1686614999  25894.8    25897
2023-06-13 08:10:01,157:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4308 

self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25897.1', self.close='25988.7'
127.0.0.1 - - [13/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-13 08:20:06,181:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25897.1', self.close='25988.7'
2023-06-13 08:20:06,348:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230613   073000    073959  1686613199  25904.9  25902.2
12142  20230613   074000    074959  1686613799  25902.2  25886.8
12143  20230613   075000    075959  1686614399  25886.7  25894.7
12144  20230613   080000    080959  1686614999  25894.8    25897
12145  20230613   081000    081959  1686615599  25897.1  25988.7
2023-06-13 08:20:06,351:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8608
self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25928.9, self.close=25988.7, self.high=26026.0, self.low=25928.9, self.vol=4907.332, self.amt=127506206.2097 
127.0.0.1 - - [13/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-13 08:20:03,063:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230613   075500    075959  ...         0.0        0.0       0
5856  20230613   080000    080459  ...         0.0        0.0       0
5857  20230613   080500    080959  ...         0.0        0.0       0
5858  20230613   081000    081459  ...         0.0        0.0       0
5859  20230613   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 08:20:03,085:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686615599, self.tradeDate='20230613', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25928.9, self.close=25988.7, self.high=26026.0, self.low=25928.9, self.vol=4907.332, self.amt=127506206.2097, ukdf['pct'].iloc[-1]=0.002306 , ukdf['amount'].iloc[-1]=127506206.2097, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31250.4374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26002.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8609
self.closeSec=1686615899, self.tradeDate='20230613', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25988.8, self.close=25970.5, self.high=26006.7, self.low=25942.8, self.vol=1380.282, self.amt=35843335.2695 
127.0.0.1 - - [13/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-13 08:25:04,295:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230613   080000    080459  ...         0.0        0.0       0
5857  20230613   080500    080959  ...         0.0        0.0       0
5858  20230613   081000    081459  ...         0.0        0.0       0
5859  20230613   081500    081959  ...         0.0        0.0       0
5860  20230613   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 08:25:04,301:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686615899, self.tradeDate='20230613', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25988.8, self.close=25970.5, self.high=26006.7, self.low=25942.8, self.vol=1380.282, self.amt=35843335.2695, ukdf['pct'].iloc[-1]=-0.0007 , ukdf['amount'].iloc[-1]=35843335.2695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-32568.37710329125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25967.11523375', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230612   200000    235959  1686585599  ...    719  0.487058 -0.369591     NaN
720  20230613   000000    035959  1686599999  ...    720  0.456457 -0.460266     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '69829.82755613154', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25812.78722481', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=179
self.closeSec=1686614399, self.tradeDate='20230613', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25816.7, self.close=25894.7, self.high=25961.0, self.low=25795.1, self.vol=25186.398, self.amt=652104389.1797 
127.0.0.1 - - [13/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-13 08:00:01,940:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686614399, self.tradeDate='20230613', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25816.7, self.close=25894.7, self.high=25961.0, self.low=25795.1, self.vol=25186.398, self.amt=652104389.1797 
2023-06-13 08:00:01,983:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230612   120000    155959  ...  30360.911  7.834327e+08  0.000528
718  20230612   160000    195959  ...  60565.670  1.572473e+09  0.007076
719  20230612   200000    235959  ...  55282.739  1.428066e+09 -0.006406
720  20230613   000000    035959  ...  60408.792  1.559081e+09  0.000291
721  20230613   040000    075959  ...  25186.398  6.521044e+08  0.003017

[5 rows x 11 columns]
2023-06-13 08:00:04,620:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230612   120000    155959  1686556799  ...    717  0.472319 -0.417763     NaN
718  20230612   160000    195959  1686571199  ...    718  0.470036 -0.426078     NaN
719  20230612   200000    235959  1686585599  ...    719  0.487058 -0.369591     NaN
720  20230613   000000    035959  1686599999  ...    720  0.456457 -0.460266     NaN
721  20230613   040000    075959  1686614399  ...    721  0.422349 -0.556833     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '65210.9205091239', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25896.51464835', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


