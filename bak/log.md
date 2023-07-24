# 20230724 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20512
self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29806.0, self.close=29782.8, self.high=29806.1, self.low=29780.9, self.vol=674.48, self.amt=20092284.3571 
127.0.0.1 - - [24/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-24 16:20:05,610:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230724   155500    155959  ...         0.0        0.0       0
5952  20230724   160000    160459  ...         0.0        0.0       0
5953  20230724   160500    160959  ...         0.0        0.0       0
5954  20230724   161000    161459  ...         0.0        0.0       0
5955  20230724   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 16:20:05,620:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29806.0, self.close=29782.8, self.high=29806.1, self.low=29780.9, self.vol=674.48, self.amt=20092284.3571, ukdf['pct'].iloc[-1]=-0.000778 , ukdf['amount'].iloc[-1]=20092284.3571, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40635.6411158775', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29782.86934625', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20513
self.closeSec=1690187099, self.tradeDate='20230724', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29782.8, self.close=29787.0, self.high=29787.4, self.low=29772.4, self.vol=517.635, self.amt=15415555.9654 
2023-07-24 16:25:00,748:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230724   160000    160459  ...         0.0        0.0       0
5953  20230724   160500    160959  ...         0.0        0.0       0
5954  20230724   161000    161459  ...         0.0        0.0       0
5955  20230724   161500    161959  ...         0.0        0.0       0
5956  20230724   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 16:25:00,748:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690187099, self.tradeDate='20230724', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29782.8, self.close=29787.0, self.high=29787.4, self.low=29772.4, self.vol=517.635, self.amt=15415555.9654, ukdf['pct'].iloc[-1]=0.000141 , ukdf['amount'].iloc[-1]=15415555.9654, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40694.5572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29787.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29806.0, self.close=29782.8, self.high=29806.1, self.low=29780.9 
127.0.0.1 - - [24/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-24 16:20:03,879:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29806.0, self.close=29782.8, self.high=29806.1, self.low=29780.9   
2023-07-24 16:20:04,911:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230724   155500    155959  1690185599  ...  29802.6 -0.000620   1631    5
1632  20230724   160000    160459  1690185899  ...  29796.0 -0.000282   1632    0
1633  20230724   160500    160959  1690186199  ...  29804.1 -0.000013   1633    1
1634  20230724   161000    161459  1690186499  ...  29801.1 -0.000054   1634    2
1635  20230724   161500    161959  1690186799  ...  29780.9 -0.000778   1635    3

[5 rows x 11 columns]
2023-07-24 16:20:04,919:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=13, self.factor=0.5387320465767229, self.count=20515 

self.closeSec=1690187099, self.tradeDate='20230724', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29782.8, self.close=29787.0, self.high=29787.4, self.low=29772.4 
2023-07-24 16:25:00,721:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690187099, self.tradeDate='20230724', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29782.8, self.close=29787.0, self.high=29787.4, self.low=29772.4   
2023-07-24 16:25:00,744:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230724   160000    160459  1690185899  ...  29796.0 -0.000282   1632    0
1633  20230724   160500    160959  1690186199  ...  29804.1 -0.000013   1633    1
1634  20230724   161000    161459  1690186499  ...  29801.1 -0.000054   1634    2
1635  20230724   161500    161959  1690186799  ...  29780.9 -0.000778   1635    3
1636  20230724   162000    162459  1690187099  ...  29772.4  0.000141   1636    4

[5 rows x 11 columns]
2023-07-24 16:25:00,744:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-24 16:00:17,274:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230724    132959  29775.8  ...  52.083333  0.469390  0.630904
5787  20230724    135959  29798.6  ...  51.666667  0.466094  0.642094
5788  20230724    142959  29786.4  ...  51.666667  0.464364  0.653125
5789  20230724    145959  29779.9  ...  51.666667  0.460303  0.664783
5790  20230724    152959  29765.1  ...  51.666667  0.470762  0.672645

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2023-07-24 16:00:17,333:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.515395  0.484605       0  ...  0.960066  -1.0    0.0  0.981621
538     0  0.513255  0.486745       0  ...  0.960272  -1.0    0.0  0.981410
539     0  0.512574  0.487426       0  ...  0.960753  -1.0    0.0  0.980919
540     0  0.503945  0.496055       1  ...  0.959688  -1.0    0.0  0.982006
541     0  0.515317  0.484683       1  ...  0.959095  -1.0    0.0  0.982613

[5 rows x 10 columns]
2023-07-24 16:00:17,344:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515068  0.484932       0  ...  0.927410  -1.0    0.0  0.981423
46     0  0.513118  0.486882       0  ...  0.927609  -1.0    0.0  0.980906
47     0  0.512097  0.487903       0  ...  0.928073  -1.0    0.0  0.980115
48     0  0.503630  0.496370       1  ...  0.927044  -1.0    0.0  0.980872
49     0  0.515317  0.484683       1  ...  0.959095  -1.0    0.0  0.982613

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.403', 'enterprice': '29752', 'countrevence': '0', 'unrealprofit': '-1504.8129', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29816.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230724   155000    155959  1690185599    29848  29816.4 -0.001062
2023-07-24 16:00:02,131:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10256 

self.closeSec=1690186199, self.tradeDate='20230724', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29816.4', self.close='29807.6'
2023-07-24 16:10:01,142:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690186199, self.tradeDate='20230724', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29816.4', self.close='29807.6'
127.0.0.1 - - [24/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-24 16:10:01,157:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230724   152000    152959  1690183799  29756.9  29798.1  0.001385
525  20230724   153000    153959  1690184399  29798.1  29804.9  0.000228
526  20230724   154000    154959  1690184999  29807.8  29848.1  0.001449
527  20230724   155000    155959  1690185599    29848  29816.4 -0.001062
528  20230724   160000    160959  1690186199  29816.4  29807.6 -0.000295
2023-07-24 16:10:01,158:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10257 

self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29807.6', self.close='29782.8'
127.0.0.1 - - [24/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-24 16:20:06,140:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29807.6', self.close='29782.8'
2023-07-24 16:20:06,522:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230724   153000    153959  1690184399  29798.1  29804.9  0.000228
526  20230724   154000    154959  1690184999  29807.8  29848.1  0.001449
527  20230724   155000    155959  1690185599    29848  29816.4 -0.001062
528  20230724   160000    160959  1690186199  29816.4  29807.6 -0.000295
529  20230724   161000    161959  1690186799  29807.6  29782.8 -0.000832
2023-07-24 16:20:06,522:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230724   155000    155959  1690185599    29848  29816.4
2023-07-24 16:00:02,138:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10259 

self.closeSec=1690186199, self.tradeDate='20230724', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29816.4', self.close='29807.6'
2023-07-24 16:10:01,152:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690186199, self.tradeDate='20230724', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29816.4', self.close='29807.6'
127.0.0.1 - - [24/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-24 16:10:01,161:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230724   152000    152959  1690183799  29756.9  29798.1
17517  20230724   153000    153959  1690184399  29798.1  29804.9
17518  20230724   154000    154959  1690184999  29807.8  29848.1
17519  20230724   155000    155959  1690185599    29848  29816.4
17520  20230724   160000    160959  1690186199  29816.4  29807.6
2023-07-24 16:10:01,161:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10260 

self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29807.6', self.close='29782.8'
127.0.0.1 - - [24/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-24 16:20:07,253:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29807.6', self.close='29782.8'
2023-07-24 16:20:07,396:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230724   153000    153959  1690184399  29798.1  29804.9
17518  20230724   154000    154959  1690184999  29807.8  29848.1
17519  20230724   155000    155959  1690185599    29848  29816.4
17520  20230724   160000    160959  1690186199  29816.4  29807.6
17521  20230724   161000    161959  1690186799  29807.6  29782.8
2023-07-24 16:20:07,396:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230724   155000    155959  1690185599    29848  29816.4
2023-07-24 16:00:02,129:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10259 

self.closeSec=1690186199, self.tradeDate='20230724', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29816.4', self.close='29807.6'
2023-07-24 16:10:01,142:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690186199, self.tradeDate='20230724', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29816.4', self.close='29807.6'
127.0.0.1 - - [24/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-24 16:10:01,148:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230724   152000    152959  1690183799  29756.9  29798.1
12189  20230724   153000    153959  1690184399  29798.1  29804.9
12190  20230724   154000    154959  1690184999  29807.8  29848.1
12191  20230724   155000    155959  1690185599    29848  29816.4
12192  20230724   160000    160959  1690186199  29816.4  29807.6
2023-07-24 16:10:01,149:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10260 

self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29807.6', self.close='29782.8'
127.0.0.1 - - [24/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-24 16:20:07,090:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29807.6', self.close='29782.8'
2023-07-24 16:20:07,301:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230724   153000    153959  1690184399  29798.1  29804.9
12190  20230724   154000    154959  1690184999  29807.8  29848.1
12191  20230724   155000    155959  1690185599    29848  29816.4
12192  20230724   160000    160959  1690186199  29816.4  29807.6
12193  20230724   161000    161959  1690186799  29807.6  29782.8
2023-07-24 16:20:07,303:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20512
self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29806.0, self.close=29782.8, self.high=29806.1, self.low=29780.9, self.vol=674.48, self.amt=20092284.3571 
127.0.0.1 - - [24/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-24 16:20:05,670:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230724   155500    155959  ...         0.0        0.0       0
5952  20230724   160000    160459  ...         0.0        0.0       0
5953  20230724   160500    160959  ...         0.0        0.0       0
5954  20230724   161000    161459  ...         0.0        0.0       0
5955  20230724   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 16:20:05,680:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690186799, self.tradeDate='20230724', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29806.0, self.close=29782.8, self.high=29806.1, self.low=29780.9, self.vol=674.48, self.amt=20092284.3571, ukdf['pct'].iloc[-1]=-0.000778 , ukdf['amount'].iloc[-1]=20092284.3571, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '109152.54638907125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29782.86934625', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20513
self.closeSec=1690187099, self.tradeDate='20230724', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29782.8, self.close=29787.0, self.high=29787.4, self.low=29772.4, self.vol=517.635, self.amt=15415555.9654 
2023-07-24 16:25:00,752:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230724   160000    160459  ...         0.0        0.0       0
5953  20230724   160500    160959  ...         0.0        0.0       0
5954  20230724   161000    161459  ...         0.0        0.0       0
5955  20230724   161500    161959  ...         0.0        0.0       0
5956  20230724   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 16:25:00,753:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690187099, self.tradeDate='20230724', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29782.8, self.close=29787.0, self.high=29787.4, self.low=29772.4, self.vol=517.635, self.amt=15415555.9654, ukdf['pct'].iloc[-1]=0.000141 , ukdf['amount'].iloc[-1]=15415555.9654, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '109309.6771', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29787.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230724   040000    075959  1690156799  ...    721  0.150437 -0.769752    -1.0
722  20230724   080000    115959  1690171199  ...    722  0.110284 -0.915170    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '8776.0032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29702.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [24/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=427
self.closeSec=1690185599, self.tradeDate='20230724', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29705.7, self.close=29816.4, self.high=29862.9, self.low=29639.7, self.vol=41872.139, self.amt=1246236297.5257 
2023-07-24 16:00:01,711:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690185599, self.tradeDate='20230724', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29705.7, self.close=29816.4, self.high=29862.9, self.low=29639.7, self.vol=41872.139, self.amt=1246236297.5257 
2023-07-24 16:00:01,723:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230723   200000    235959  ...  14726.508  4.400262e+08  0.000151
720  20230724   000000    035959  ...  92494.175  2.786594e+09  0.006595
721  20230724   040000    075959  ...  37643.416  1.130502e+09 -0.000409
722  20230724   080000    115959  ...  70283.909  2.096249e+09 -0.012141
723  20230724   120000    155959  ...  41872.139  1.246236e+09  0.003727

[5 rows x 11 columns]
2023-07-24 16:00:02,391:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230723   200000    235959  1690127999  ...    719  0.096704 -1.012718    -1.0
720  20230724   000000    035959  1690142399  ...    720  0.142670 -0.812779    -1.0
721  20230724   040000    075959  1690156799  ...    721  0.150437 -0.769752    -1.0
722  20230724   080000    115959  1690171199  ...    722  0.110284 -0.915170    -1.0
723  20230724   120000    155959  1690185599  ...    723  0.125401 -0.842012    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '2833.1568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29816.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


