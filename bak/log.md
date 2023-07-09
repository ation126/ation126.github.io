# 20230709 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16096
self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30246.1, self.close=30258.2, self.high=30263.3, self.low=30246.0, self.vol=273.143, self.amt=8264613.3341 
127.0.0.1 - - [09/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-09 08:20:07,985:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230709   075500    075959  ...         0.0        0.0       0
5856  20230709   080000    080459  ...         0.0        0.0       0
5857  20230709   080500    080959  ...         0.0        0.0       0
5858  20230709   081000    081459  ...         0.0        0.0       0
5859  20230709   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 08:20:08,025:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30246.1, self.close=30258.2, self.high=30263.3, self.low=30246.0, self.vol=273.143, self.amt=8264613.3341, ukdf['pct'].iloc[-1]=0.000403 , ukdf['amount'].iloc[-1]=8264613.3341, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47301.9582438744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30261.5651044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16097
self.closeSec=1688862299, self.tradeDate='20230709', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30258.3, self.close=30247.6, self.high=30258.3, self.low=30244.2, self.vol=260.714, self.amt=7887083.7468 
127.0.0.1 - - [09/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-09 08:25:00,790:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230709   080000    080459  ...         0.0        0.0       0
5857  20230709   080500    080959  ...         0.0        0.0       0
5858  20230709   081000    081459  ...         0.0        0.0       0
5859  20230709   081500    081959  ...         0.0        0.0       0
5860  20230709   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 08:25:00,790:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688862299, self.tradeDate='20230709', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30258.3, self.close=30247.6, self.high=30258.3, self.low=30244.2, self.vol=260.714, self.amt=7887083.7468, ukdf['pct'].iloc[-1]=-0.00035 , ukdf['amount'].iloc[-1]=7887083.7468, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47164.0141742814', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30251.6595989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30246.1, self.close=30258.2, self.high=30263.3, self.low=30246.0 
127.0.0.1 - - [09/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-09 08:20:05,347:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30246.1, self.close=30258.2, self.high=30263.3, self.low=30246.0   
2023-07-09 08:20:07,044:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230709   075500    075959  1688860799  ...  30238.7  0.000631   1535    5
1536  20230709   080000    080459  1688861099  ...  30257.7 -0.000380   1536    0
1537  20230709   080500    080959  1688861399  ...  30254.2  0.000083   1537    1
1538  20230709   081000    081459  1688861699  ...  30244.2 -0.000469   1538    2
1539  20230709   081500    081959  1688861999  ...  30246.0  0.000403   1539    3

[5 rows x 11 columns]
2023-07-09 08:20:07,055:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=15, self.factor=0.5642333965322235, self.count=16099 

self.closeSec=1688862299, self.tradeDate='20230709', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30258.3, self.close=30247.6, self.high=30258.3, self.low=30244.2 
2023-07-09 08:25:00,761:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688862299, self.tradeDate='20230709', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30258.3, self.close=30247.6, self.high=30258.3, self.low=30244.2   
2023-07-09 08:25:00,780:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230709   080000    080459  1688861099  ...  30257.7 -0.000380   1536    0
1537  20230709   080500    080959  1688861399  ...  30254.2  0.000083   1537    1
1538  20230709   081000    081459  1688861699  ...  30244.2 -0.000469   1538    2
1539  20230709   081500    081959  1688861999  ...  30246.0  0.000403   1539    3
1540  20230709   082000    082459  1688862299  ...  30244.2 -0.000350   1540    4

[5 rows x 11 columns]
2023-07-09 08:25:00,781:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-09 08:00:20,615:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230709    052959  30140.0  ...  46.250000  0.476485  0.636033
5771  20230709    055959  30180.1  ...  45.833333  0.475373  0.632702
5772  20230709    062959  30173.1  ...  45.416667  0.470634  0.632783
5773  20230709    065959  30156.2  ...  45.833333  0.487835  0.619084
5774  20230709    072959  30212.0  ...  46.250000  0.498299  0.593541

[5 rows x 33 columns]
0.5767097966728281
acc is : 0.5767097966728281
2023-07-09 08:00:20,705:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.511686  0.488314       0  ...  0.940143   1.0    0.0  0.983180
537     0  0.510159  0.489841       0  ...  0.939616   1.0    0.0  0.982629
538     0  0.507497  0.492503       1  ...  0.941355   1.0    0.0  0.984447
539     0  0.526973  0.473027       1  ...  0.942449   1.0    0.0  0.985591
540     0  0.526914  0.473086       1  ...  0.943144   1.0    0.0  0.986318

[5 rows x 10 columns]
2023-07-09 08:00:20,717:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512198  0.487802       0  ...  0.949958   1.0    0.0  0.989691
46     0  0.510272  0.489728       0  ...  0.939616   1.0    0.0  0.986567
47     0  0.507151  0.492849       1  ...  0.941355   1.0    0.0  0.984245
48     0  0.526760  0.473240       1  ...  0.942449   1.0    0.0  0.985591
49     0  0.526914  0.473086       1  ...  0.943144   1.0    0.0  0.986318

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.764', 'enterprice': '30087.2', 'countrevence': '0', 'unrealprofit': '4729.924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30278.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230709   075000    075959  1688860799  30231.7  30269.3  0.001244
2023-07-09 08:00:02,124:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8048 

self.closeSec=1688861399, self.tradeDate='20230709', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30269.2', self.close='30260.2'
2023-07-09 08:10:01,163:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688861399, self.tradeDate='20230709', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30269.2', self.close='30260.2'
127.0.0.1 - - [09/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-09 08:10:01,169:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230709   072000    072959  1688858999  30234.6    30247  0.000407
621  20230709   073000    073959  1688859599    30247  30226.6 -0.000674
622  20230709   074000    074959  1688860199  30226.6  30231.7  0.000169
623  20230709   075000    075959  1688860799  30231.7  30269.3  0.001244
624  20230709   080000    080959  1688861399  30269.2  30260.2 -0.000301
2023-07-09 08:10:01,170:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8049 

self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30260.3', self.close='30258.2'
127.0.0.1 - - [09/Jul/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-07-09 08:20:07,834:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30260.3', self.close='30258.2'
2023-07-09 08:20:08,674:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230709   073000    073959  1688859599    30247  30226.6 -0.000674
622  20230709   074000    074959  1688860199  30226.6  30231.7  0.000169
623  20230709   075000    075959  1688860799  30231.7  30269.3  0.001244
624  20230709   080000    080959  1688861399  30269.2  30260.2 -0.000301
625  20230709   081000    081959  1688861999  30260.3  30258.2 -0.000066
2023-07-09 08:20:08,684:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230709   075000    075959  1688860799  30231.7  30269.3
2023-07-09 08:00:02,126:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8051 

self.closeSec=1688861399, self.tradeDate='20230709', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30269.2', self.close='30260.2'
2023-07-09 08:10:01,184:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688861399, self.tradeDate='20230709', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30269.2', self.close='30260.2'
127.0.0.1 - - [09/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-09 08:10:01,194:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230709   072000    072959  1688858999  30234.6    30247
17469  20230709   073000    073959  1688859599    30247  30226.6
17470  20230709   074000    074959  1688860199  30226.6  30231.7
17471  20230709   075000    075959  1688860799  30231.7  30269.3
17472  20230709   080000    080959  1688861399  30269.2  30260.2
2023-07-09 08:10:01,194:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8052 

self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30260.3', self.close='30258.2'
127.0.0.1 - - [09/Jul/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-07-09 08:20:10,148:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30260.3', self.close='30258.2'
2023-07-09 08:20:10,363:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230709   073000    073959  1688859599    30247  30226.6
17470  20230709   074000    074959  1688860199  30226.6  30231.7
17471  20230709   075000    075959  1688860799  30231.7  30269.3
17472  20230709   080000    080959  1688861399  30269.2  30260.2
17473  20230709   081000    081959  1688861999  30260.3  30258.2
2023-07-09 08:20:10,364:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230709   075000    075959  1688860799  30231.7  30269.3
2023-07-09 08:00:02,125:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8051 

self.closeSec=1688861399, self.tradeDate='20230709', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30269.2', self.close='30260.2'
2023-07-09 08:10:01,170:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688861399, self.tradeDate='20230709', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30269.2', self.close='30260.2'
2023-07-09 08:10:01,177:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230709   072000    072959  1688858999  30234.6    30247
12141  20230709   073000    073959  1688859599    30247  30226.6
12142  20230709   074000    074959  1688860199  30226.6  30231.7
12143  20230709   075000    075959  1688860799  30231.7  30269.3
12144  20230709   080000    080959  1688861399  30269.2  30260.2
2023-07-09 08:10:01,177:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8052 

self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30260.3', self.close='30258.2'
127.0.0.1 - - [09/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-09 08:20:09,824:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30260.3', self.close='30258.2'
2023-07-09 08:20:10,177:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230709   073000    073959  1688859599    30247  30226.6
12142  20230709   074000    074959  1688860199  30226.6  30231.7
12143  20230709   075000    075959  1688860799  30231.7  30269.3
12144  20230709   080000    080959  1688861399  30269.2  30260.2
12145  20230709   081000    081959  1688861999  30260.3  30258.2
2023-07-09 08:20:10,183:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16096
self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30246.1, self.close=30258.2, self.high=30263.3, self.low=30246.0, self.vol=273.143, self.amt=8264613.3341 
127.0.0.1 - - [09/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-09 08:20:07,985:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230709   075500    075959  ...         0.0        0.0       0
5856  20230709   080000    080459  ...         0.0        0.0       0
5857  20230709   080500    080959  ...         0.0        0.0       0
5858  20230709   081000    081459  ...         0.0        0.0       0
5859  20230709   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 08:20:08,014:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688861999, self.tradeDate='20230709', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30246.1, self.close=30258.2, self.high=30263.3, self.low=30246.0, self.vol=273.143, self.amt=8264613.3341, ukdf['pct'].iloc[-1]=0.000403 , ukdf['amount'].iloc[-1]=8264613.3341, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126931.7855425204', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30261.5651044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16097
self.closeSec=1688862299, self.tradeDate='20230709', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30258.3, self.close=30247.6, self.high=30258.3, self.low=30244.2, self.vol=260.714, self.amt=7887083.7468 
2023-07-09 08:25:00,805:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230709   080000    080459  ...         0.0        0.0       0
5857  20230709   080500    080959  ...         0.0        0.0       0
5858  20230709   081000    081459  ...         0.0        0.0       0
5859  20230709   081500    081959  ...         0.0        0.0       0
5860  20230709   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 08:25:00,806:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688862299, self.tradeDate='20230709', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30258.3, self.close=30247.6, self.high=30258.3, self.low=30244.2, self.vol=260.714, self.amt=7887083.7468, ukdf['pct'].iloc[-1]=-0.00035 , ukdf['amount'].iloc[-1]=7887083.7468, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126563.8851627449', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30251.6595989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230708   200000    235959  1688831999  ...    719  0.422333  0.360380     NaN
720  20230709   000000    035959  1688846399  ...    720  0.417043  0.377134     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-34291.52', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30104.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [09/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=335
self.closeSec=1688860799, self.tradeDate='20230709', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30100.0, self.close=30269.3, self.high=30280.0, self.low=30037.5, self.vol=19275.386, self.amt=581540692.5554 
2023-07-09 08:00:01,668:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688860799, self.tradeDate='20230709', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30100.0, self.close=30269.3, self.high=30280.0, self.low=30037.5, self.vol=19275.386, self.amt=581540692.5554 
2023-07-09 08:00:01,697:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230708   120000    155959  ...  26594.583  8.031862e+08 -0.002816
718  20230708   160000    195959  ...  25385.741  7.672975e+08  0.000348
719  20230708   200000    235959  ...  15361.803  4.637049e+08  0.000378
720  20230709   000000    035959  ...  31842.636  9.610810e+08 -0.003202
721  20230709   040000    075959  ...  19275.386  5.815407e+08  0.005625

[5 rows x 11 columns]
2023-07-09 08:00:02,991:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230708   120000    155959  1688803199  ...    717  0.458979  0.419851     NaN
718  20230708   160000    195959  1688817599  ...    718  0.426726  0.341712     NaN
719  20230708   200000    235959  1688831999  ...    719  0.422333  0.360380     NaN
720  20230709   000000    035959  1688846399  ...    720  0.417043  0.377134     NaN
721  20230709   040000    075959  1688860799  ...    721  0.358795  0.194950     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-25431.522226609', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30271.51221062', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


