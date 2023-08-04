# 20230804 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23680
self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29220.6, self.close=29235.2, self.high=29248.4, self.low=29212.4, self.vol=750.387, self.amt=21937543.966 
127.0.0.1 - - [04/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-04 16:20:06,213:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230804   155500    155959  ...         0.0        0.0       0
5952  20230804   160000    160459  ...         0.0        0.0       0
5953  20230804   160500    160959  ...         0.0        0.0       0
5954  20230804   161000    161459  ...         0.0        0.0       0
5955  20230804   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 16:20:06,254:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29220.6, self.close=29235.2, self.high=29248.4, self.low=29212.4, self.vol=750.387, self.amt=21937543.966, ukdf['pct'].iloc[-1]=0.000503 , ukdf['amount'].iloc[-1]=21937543.966, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33002.17050335898', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29234.72410623', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23681
self.closeSec=1691137499, self.tradeDate='20230804', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29235.2, self.close=29200.3, self.high=29237.3, self.low=29197.7, self.vol=810.448, self.amt=23677732.8714 
2023-08-04 16:25:00,760:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230804   160000    160459  ...         0.0        0.0       0
5953  20230804   160500    160959  ...         0.0        0.0       0
5954  20230804   161000    161459  ...         0.0        0.0       0
5955  20230804   161500    161959  ...         0.0        0.0       0
5956  20230804   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 16:25:00,760:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691137499, self.tradeDate='20230804', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29235.2, self.close=29200.3, self.high=29237.3, self.low=29197.7, self.vol=810.448, self.amt=23677732.8714, ukdf['pct'].iloc[-1]=-0.001194 , ukdf['amount'].iloc[-1]=23677732.8714, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32533.64303706264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29201.08002564', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29220.6, self.close=29235.2, self.high=29248.4, self.low=29212.4 
127.0.0.1 - - [04/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-04 16:20:04,154:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29220.6, self.close=29235.2, self.high=29248.4, self.low=29212.4   
2023-08-04 16:20:05,373:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230804   155500    155959  1691135999  ...  29194.0  0.000257   1631    5
1632  20230804   160000    160459  1691136299  ...  29191.7  0.000377   1632    0
1633  20230804   160500    160959  1691136599  ...  29212.5  0.000462   1633    1
1634  20230804   161000    161459  1691136899  ...  29209.0 -0.000192   1634    2
1635  20230804   161500    161959  1691137199  ...  29212.4  0.000503   1635    3

[5 rows x 11 columns]
2023-08-04 16:20:05,374:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=44, self.factor=0.5371114852811125, self.count=23683 

self.closeSec=1691137499, self.tradeDate='20230804', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29235.2, self.close=29200.3, self.high=29237.3, self.low=29197.7 
127.0.0.1 - - [04/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-04 16:25:00,763:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691137499, self.tradeDate='20230804', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29235.2, self.close=29200.3, self.high=29237.3, self.low=29197.7   
2023-08-04 16:25:00,786:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230804   160000    160459  1691136299  ...  29191.7  0.000377   1632    0
1633  20230804   160500    160959  1691136599  ...  29212.5  0.000462   1633    1
1634  20230804   161000    161459  1691136899  ...  29209.0 -0.000192   1634    2
1635  20230804   161500    161959  1691137199  ...  29212.4  0.000503   1635    3
1636  20230804   162000    162459  1691137499  ...  29197.7 -0.001194   1636    4

[5 rows x 11 columns]
2023-08-04 16:25:00,788:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-04 16:00:16,463:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230804    132959  29199.4  ...  45.833333  0.496346  0.528396
5787  20230804    135959  29202.8  ...  46.250000  0.502353  0.531683
5788  20230804    142959  29225.0  ...  46.250000  0.501917  0.535036
5789  20230804    145959  29224.5  ...  45.833333  0.491383  0.545102
5790  20230804    152959  29184.7  ...  45.833333  0.486644  0.557651

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-08-04 16:00:16,518:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510026  0.489974       1  ...  0.974472   1.0    0.0  0.974144
538     0  0.519157  0.480843       0  ...  0.974419   1.0    0.0  0.974091
539     0  0.510428  0.489572       0  ...  0.973129   1.0    0.0  0.972801
540     0  0.500027  0.499973       0  ...  0.972542   1.0    0.0  0.972214
541     1  0.498736  0.501264       1  ...  0.973689   1.0    0.0  0.973361

[5 rows x 10 columns]
2023-08-04 16:00:16,529:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509902  0.490098       1  ...  0.974472   1.0    0.0  0.974027
46     0  0.518927  0.481073       0  ...  0.974419   1.0    0.0  0.972357
47     0  0.510112  0.489888       0  ...  0.973129   1.0    0.0  0.970536
48     0  0.500135  0.499865       0  ...  0.972542   1.0    0.0  0.969980
49     1  0.498736  0.501264       1  ...  0.973689   1.0    0.0  0.973361

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '1674.8265589152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29201.11041392', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230804   155000    155959  1691135999  29182.9  29201.6  0.000641
2023-08-04 16:00:02,141:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11840 

self.closeSec=1691136599, self.tradeDate='20230804', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29201.6', self.close='29226.1'
2023-08-04 16:10:01,169:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691136599, self.tradeDate='20230804', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29201.6', self.close='29226.1'
2023-08-04 16:10:01,187:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230804   152000    152959  1691134199  29163.1  29167.2  0.000141
525  20230804   153000    153959  1691134799  29167.1  29163.2 -0.000137
526  20230804   154000    154959  1691135399  29163.3  29182.9  0.000676
527  20230804   155000    155959  1691135999  29182.9  29201.6  0.000641
528  20230804   160000    160959  1691136599  29201.6  29226.1  0.000839
2023-08-04 16:10:01,187:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11841 

self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29226.1', self.close='29235.2'
127.0.0.1 - - [04/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-04 16:20:06,425:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29226.1', self.close='29235.2'
2023-08-04 16:20:07,053:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230804   153000    153959  1691134799  29167.1  29163.2 -0.000137
526  20230804   154000    154959  1691135399  29163.3  29182.9  0.000676
527  20230804   155000    155959  1691135999  29182.9  29201.6  0.000641
528  20230804   160000    160959  1691136599  29201.6  29226.1  0.000839
529  20230804   161000    161959  1691137199  29226.1  29235.2  0.000311
2023-08-04 16:20:07,054:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230804   155000    155959  1691135999  29182.9  29201.6
2023-08-04 16:00:02,139:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11843 

self.closeSec=1691136599, self.tradeDate='20230804', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29201.6', self.close='29226.1'
127.0.0.1 - - [04/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-04 16:10:01,175:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691136599, self.tradeDate='20230804', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29201.6', self.close='29226.1'
2023-08-04 16:10:01,185:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230804   152000    152959  1691134199  29163.1  29167.2
17517  20230804   153000    153959  1691134799  29167.1  29163.2
17518  20230804   154000    154959  1691135399  29163.3  29182.9
17519  20230804   155000    155959  1691135999  29182.9  29201.6
17520  20230804   160000    160959  1691136599  29201.6  29226.1
2023-08-04 16:10:01,185:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11844 

self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29226.1', self.close='29235.2'
127.0.0.1 - - [04/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-04 16:20:08,015:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29226.1', self.close='29235.2'
2023-08-04 16:20:08,075:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230804   153000    153959  1691134799  29167.1  29163.2
17518  20230804   154000    154959  1691135399  29163.3  29182.9
17519  20230804   155000    155959  1691135999  29182.9  29201.6
17520  20230804   160000    160959  1691136599  29201.6  29226.1
17521  20230804   161000    161959  1691137199  29226.1  29235.2
2023-08-04 16:20:08,076:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230804   155000    155959  1691135999  29182.9  29201.6
2023-08-04 16:00:02,144:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11843 

self.closeSec=1691136599, self.tradeDate='20230804', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29201.6', self.close='29226.1'
2023-08-04 16:10:01,177:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691136599, self.tradeDate='20230804', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29201.6', self.close='29226.1'
127.0.0.1 - - [04/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-04 16:10:01,196:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230804   152000    152959  1691134199  29163.1  29167.2
12189  20230804   153000    153959  1691134799  29167.1  29163.2
12190  20230804   154000    154959  1691135399  29163.3  29182.9
12191  20230804   155000    155959  1691135999  29182.9  29201.6
12192  20230804   160000    160959  1691136599  29201.6  29226.1
2023-08-04 16:10:01,196:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11844 

self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29226.1', self.close='29235.2'
127.0.0.1 - - [04/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-04 16:20:07,855:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29226.1', self.close='29235.2'
2023-08-04 16:20:08,009:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230804   153000    153959  1691134799  29167.1  29163.2
12190  20230804   154000    154959  1691135399  29163.3  29182.9
12191  20230804   155000    155959  1691135999  29182.9  29201.6
12192  20230804   160000    160959  1691136599  29201.6  29226.1
12193  20230804   161000    161959  1691137199  29226.1  29235.2
2023-08-04 16:20:08,013:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23680
self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29220.6, self.close=29235.2, self.high=29248.4, self.low=29212.4, self.vol=750.387, self.amt=21937543.966 
127.0.0.1 - - [04/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-04 16:20:06,164:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230804   155500    155959  ...         0.0        0.0       0
5952  20230804   160000    160459  ...         0.0        0.0       0
5953  20230804   160500    160959  ...         0.0        0.0       0
5954  20230804   161000    161459  ...         0.0        0.0       0
5955  20230804   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 16:20:06,194:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691137199, self.tradeDate='20230804', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29220.6, self.close=29235.2, self.high=29248.4, self.low=29212.4, self.vol=750.387, self.amt=21937543.966, ukdf['pct'].iloc[-1]=0.000503 , ukdf['amount'].iloc[-1]=21937543.966, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88793.88402948843', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29234.72410623', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [04/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23681
self.closeSec=1691137499, self.tradeDate='20230804', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29235.2, self.close=29200.3, self.high=29237.3, self.low=29197.7, self.vol=810.448, self.amt=23677732.8714 
2023-08-04 16:25:00,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230804   160000    160459  ...         0.0        0.0       0
5953  20230804   160500    160959  ...         0.0        0.0       0
5954  20230804   161000    161459  ...         0.0        0.0       0
5955  20230804   161500    161959  ...         0.0        0.0       0
5956  20230804   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 16:25:00,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691137499, self.tradeDate='20230804', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29235.2, self.close=29200.3, self.high=29237.3, self.low=29197.7, self.vol=810.448, self.amt=23677732.8714, ukdf['pct'].iloc[-1]=-0.001194 , ukdf['amount'].iloc[-1]=23677732.8714, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '87544.30923229524', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29201.08002564', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230804   040000    075959  1691107199  ...    721  0.429670  0.843415     1.0
722  20230804   080000    115959  1691121599  ...    722  0.424128  0.801254     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '6452.495', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29152.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1588790.78883, self.flagDict['side']='buy', self.tradeCount=17, self.count=493
self.closeSec=1691135999, self.tradeDate='20230804', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29152.6, self.close=29201.6, self.high=29243.9, self.low=29120.3, self.vol=18873.441, self.amt=550909139.1281 
127.0.0.1 - - [04/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-08-04 16:00:01,711:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691135999, self.tradeDate='20230804', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29152.6, self.close=29201.6, self.high=29243.9, self.low=29120.3, self.vol=18873.441, self.amt=550909139.1281 
2023-08-04 16:00:01,727:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230803   200000    235959  ...  78353.291  2.291478e+09  0.003782
720  20230804   000000    035959  ...  49254.329  1.440697e+09  0.000745
721  20230804   040000    075959  ...  32069.536  9.381274e+08 -0.002942
722  20230804   080000    115959  ...  24448.761  7.130760e+08 -0.000942
723  20230804   120000    155959  ...  18873.441  5.509091e+08  0.001681

[5 rows x 11 columns]
2023-08-04 16:00:02,457:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230803   200000    235959  1691078399  ...    719  0.426334  0.858964     1.0
720  20230804   000000    035959  1691092799  ...    720  0.435090  0.886587     1.0
721  20230804   040000    075959  1691107199  ...    721  0.429670  0.843415     1.0
722  20230804   080000    115959  1691121599  ...    722  0.424128  0.801254     1.0
723  20230804   120000    155959  1691135999  ...    723  0.406703  0.700907     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '9241.418247082', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29203.51598808', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


