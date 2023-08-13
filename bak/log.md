# 20230813 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26272
self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29384.3, self.close=29382.1, self.high=29384.3, self.low=29382.0, self.vol=112.095, self.amt=3293796.1793 
127.0.0.1 - - [13/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-13 16:20:06,634:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230813   155500    155959  ...         0.0        0.0       0
5952  20230813   160000    160459  ...         0.0        0.0       0
5953  20230813   160500    160959  ...         0.0        0.0       0
5954  20230813   161000    161459  ...         0.0        0.0       0
5955  20230813   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 16:20:06,664:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29384.3, self.close=29382.1, self.high=29384.3, self.low=29382.0, self.vol=112.095, self.amt=3293796.1793, ukdf['pct'].iloc[-1]=-7.5e-05 , ukdf['amount'].iloc[-1]=3293796.1793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35078.24505007218', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29383.80313443', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26273
self.closeSec=1691915099, self.tradeDate='20230813', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29382.1, self.close=29384.3, self.high=29384.3, self.low=29380.5, self.vol=216.831, self.amt=6370824.6295 
2023-08-13 16:25:00,807:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230813   160000    160459  ...         0.0        0.0       0
5953  20230813   160500    160959  ...         0.0        0.0       0
5954  20230813   161000    161459  ...         0.0        0.0       0
5955  20230813   161500    161959  ...         0.0        0.0       0
5956  20230813   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 16:25:00,807:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691915099, self.tradeDate='20230813', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29382.1, self.close=29384.3, self.high=29384.3, self.low=29380.5, self.vol=216.831, self.amt=6370824.6295, ukdf['pct'].iloc[-1]=7.5e-05 , ukdf['amount'].iloc[-1]=6370824.6295, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35083.7718', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29384.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29384.3, self.close=29382.1, self.high=29384.3, self.low=29382.0 
127.0.0.1 - - [13/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-13 16:20:04,544:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29384.3, self.close=29382.1, self.high=29384.3, self.low=29382.0   
2023-08-13 16:20:05,704:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230813   155500    155959  1691913599  ...  29385.5 -0.000003   1631    5
1632  20230813   160000    160459  1691913899  ...  29384.2 -0.000041   1632    0
1633  20230813   160500    160959  1691914199  ...  29384.2  0.000000   1633    1
1634  20230813   161000    161459  1691914499  ...  29384.2  0.000000   1634    2
1635  20230813   161500    161959  1691914799  ...  29382.0 -0.000075   1635    3

[5 rows x 11 columns]
2023-08-13 16:20:05,705:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=38, self.factor=0.5863645339649545, self.count=26275 

self.closeSec=1691915099, self.tradeDate='20230813', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29382.1, self.close=29384.3, self.high=29384.3, self.low=29380.5 
127.0.0.1 - - [13/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-13 16:25:00,790:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691915099, self.tradeDate='20230813', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29382.1, self.close=29384.3, self.high=29384.3, self.low=29380.5   
2023-08-13 16:25:00,814:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230813   160000    160459  1691913899  ...  29384.2 -0.000041   1632    0
1633  20230813   160500    160959  1691914199  ...  29384.2  0.000000   1633    1
1634  20230813   161000    161459  1691914499  ...  29384.2  0.000000   1634    2
1635  20230813   161500    161959  1691914799  ...  29382.0 -0.000075   1635    3
1636  20230813   162000    162459  1691915099  ...  29380.5  0.000075   1636    4

[5 rows x 11 columns]
2023-08-13 16:25:00,814:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-13 16:00:16,418:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230813    132959  29377.8  ...  48.750000  0.464746  0.521887
5787  20230813    135959  29370.7  ...  49.166667  0.467134  0.537702
5788  20230813    142959  29374.1  ...  49.166667  0.472919  0.548131
5789  20230813    145959  29382.4  ...  49.583333  0.478416  0.553745
5790  20230813    152959  29390.3  ...  49.583333  0.478155  0.559195

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2023-08-13 16:00:16,478:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.497242  0.502758       1  ...  0.976217  -1.0    0.0  0.985156
538     0  0.502147  0.497853       1  ...  0.975944  -1.0    0.0  0.985431
539     0  0.503769  0.496231       1  ...  0.975685  -1.0    0.0  0.985693
540     0  0.504721  0.495279       0  ...  0.975698  -1.0    0.0  0.985679
541     0  0.504686  0.495314       0  ...  0.975841  -1.0    0.0  0.985535

[5 rows x 10 columns]
2023-08-13 16:00:16,490:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497175  0.502825       1  ...  0.989734  -1.0    0.0  1.004490
46     0  0.502127  0.497873       1  ...  0.989458  -1.0    0.0  0.999068
47     0  0.503667  0.496333       1  ...  0.979480  -1.0    0.0  0.989529
48     0  0.504860  0.495140       0  ...  0.976126  -1.0    0.0  0.986119
49     0  0.504686  0.495314       0  ...  0.975841  -1.0    0.0  0.985535

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '2265.4158', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29385.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230813   155000    155959  1691913599  29386.2  29385.5 -0.000020
2023-08-13 16:00:02,104:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13136 

self.closeSec=1691914199, self.tradeDate='20230813', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29385.6', self.close='29384.3'
2023-08-13 16:10:01,172:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691914199, self.tradeDate='20230813', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29385.6', self.close='29384.3'
2023-08-13 16:10:01,199:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230813   152000    152959  1691911799    29388  29389.8  0.000061
525  20230813   153000    153959  1691912399  29389.8  29386.2 -0.000122
526  20230813   154000    154959  1691912999  29386.2  29386.1 -0.000003
527  20230813   155000    155959  1691913599  29386.2  29385.5 -0.000020
528  20230813   160000    160959  1691914199  29385.6  29384.3 -0.000041
2023-08-13 16:10:01,199:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13137 

self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29384.3', self.close='29382.1'
127.0.0.1 - - [13/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-13 16:20:06,595:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29384.3', self.close='29382.1'
2023-08-13 16:20:07,195:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230813   153000    153959  1691912399  29389.8  29386.2 -0.000122
526  20230813   154000    154959  1691912999  29386.2  29386.1 -0.000003
527  20230813   155000    155959  1691913599  29386.2  29385.5 -0.000020
528  20230813   160000    160959  1691914199  29385.6  29384.3 -0.000041
529  20230813   161000    161959  1691914799  29384.3  29382.1 -0.000075
2023-08-13 16:20:07,204:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230813   155000    155959  1691913599  29386.2  29385.5
2023-08-13 16:00:02,104:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13139 

self.closeSec=1691914199, self.tradeDate='20230813', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29385.6', self.close='29384.3'
2023-08-13 16:10:01,179:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691914199, self.tradeDate='20230813', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29385.6', self.close='29384.3'
127.0.0.1 - - [13/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-13 16:10:01,186:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230813   152000    152959  1691911799    29388  29389.8
17517  20230813   153000    153959  1691912399  29389.8  29386.2
17518  20230813   154000    154959  1691912999  29386.2  29386.1
17519  20230813   155000    155959  1691913599  29386.2  29385.5
17520  20230813   160000    160959  1691914199  29385.6  29384.3
2023-08-13 16:10:01,186:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13140 

self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29384.3', self.close='29382.1'
127.0.0.1 - - [13/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-13 16:20:08,338:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29384.3', self.close='29382.1'
2023-08-13 16:20:08,422:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230813   153000    153959  1691912399  29389.8  29386.2
17518  20230813   154000    154959  1691912999  29386.2  29386.1
17519  20230813   155000    155959  1691913599  29386.2  29385.5
17520  20230813   160000    160959  1691914199  29385.6  29384.3
17521  20230813   161000    161959  1691914799  29384.3  29382.1
2023-08-13 16:20:08,422:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230813   155000    155959  1691913599  29386.2  29385.5
2023-08-13 16:00:02,109:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [13/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13139 

self.closeSec=1691914199, self.tradeDate='20230813', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29385.6', self.close='29384.3'
2023-08-13 16:10:01,179:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691914199, self.tradeDate='20230813', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29385.6', self.close='29384.3'
2023-08-13 16:10:01,196:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230813   152000    152959  1691911799    29388  29389.8
12189  20230813   153000    153959  1691912399  29389.8  29386.2
12190  20230813   154000    154959  1691912999  29386.2  29386.1
12191  20230813   155000    155959  1691913599  29386.2  29385.5
12192  20230813   160000    160959  1691914199  29385.6  29384.3
2023-08-13 16:10:01,196:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13140 

self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29384.3', self.close='29382.1'
127.0.0.1 - - [13/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-13 16:20:08,148:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29384.3', self.close='29382.1'
2023-08-13 16:20:08,327:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230813   153000    153959  1691912399  29389.8  29386.2
12190  20230813   154000    154959  1691912999  29386.2  29386.1
12191  20230813   155000    155959  1691913599  29386.2  29385.5
12192  20230813   160000    160959  1691914199  29385.6  29384.3
12193  20230813   161000    161959  1691914799  29384.3  29382.1
2023-08-13 16:20:08,328:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26272
self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29384.3, self.close=29382.1, self.high=29384.3, self.low=29382.0, self.vol=112.095, self.amt=3293796.1793 
127.0.0.1 - - [13/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-13 16:20:06,543:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230813   155500    155959  ...         0.0        0.0       0
5952  20230813   160000    160459  ...         0.0        0.0       0
5953  20230813   160500    160959  ...         0.0        0.0       0
5954  20230813   161000    161459  ...         0.0        0.0       0
5955  20230813   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 16:20:06,564:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691914799, self.tradeDate='20230813', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29384.3, self.close=29382.1, self.high=29384.3, self.low=29382.0, self.vol=112.095, self.amt=3293796.1793, ukdf['pct'].iloc[-1]=-7.5e-05 , ukdf['amount'].iloc[-1]=3293796.1793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '94330.82821586463', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29383.80313443', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [13/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26273
self.closeSec=1691915099, self.tradeDate='20230813', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29382.1, self.close=29384.3, self.high=29384.3, self.low=29380.5, self.vol=216.831, self.amt=6370824.6295 
2023-08-13 16:25:00,823:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230813   160000    160459  ...         0.0        0.0       0
5953  20230813   160500    160959  ...         0.0        0.0       0
5954  20230813   161000    161459  ...         0.0        0.0       0
5955  20230813   161500    161959  ...         0.0        0.0       0
5956  20230813   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 16:25:00,824:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691915099, self.tradeDate='20230813', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29382.1, self.close=29384.3, self.high=29384.3, self.low=29380.5, self.vol=216.831, self.amt=6370824.6295, ukdf['pct'].iloc[-1]=7.5e-05 , ukdf['amount'].iloc[-1]=6370824.6295, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '94345.5682', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29384.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230813   040000    075959  1691884799  ...    721  1.431491  2.280324     1.0
722  20230813   080000    115959  1691899199  ...    722  1.023916  1.279311     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-24725.69414065688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29403.88823016', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [13/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=547
self.closeSec=1691913599, self.tradeDate='20230813', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29401.8, self.close=29385.5, self.high=29401.9, self.low=29343.8, self.vol=11731.661, self.amt=344641030.9277 
2023-08-13 16:00:01,683:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691913599, self.tradeDate='20230813', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29401.8, self.close=29385.5, self.high=29401.9, self.low=29343.8, self.vol=11731.661, self.amt=344641030.9277 
2023-08-13 16:00:01,697:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230812   200000    235959  ...  10838.163  3.188723e+08  0.000316
720  20230813   000000    035959  ...  10798.789  3.178413e+08 -0.000629
721  20230813   040000    075959  ...   5810.372  1.708853e+08  0.000449
722  20230813   080000    115959  ...   9679.096  2.847198e+08 -0.000642
723  20230813   120000    155959  ...  11731.661  3.446410e+08 -0.000554

[5 rows x 11 columns]
2023-08-13 16:00:02,370:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230812   200000    235959  1691855999  ...    719  1.313265  2.176949     1.0
720  20230813   000000    035959  1691870399  ...    720  1.461579  2.449267     1.0
721  20230813   040000    075959  1691884799  ...    721  1.431491  2.280324     1.0
722  20230813   080000    115959  1691899199  ...    722  1.023916  1.279311     1.0
723  20230813   120000    155959  1691913599  ...    723  0.960580  1.105825     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-25671.8973', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29385.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


