# 20230801 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22816
self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28905.4, self.close=28913.5, self.high=28916.7, self.low=28896.9, self.vol=653.525, self.amt=18891752.3438 
127.0.0.1 - - [01/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-01 16:20:05,855:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230801   155500    155959  ...         0.0        0.0       0
5952  20230801   160000    160459  ...         0.0        0.0       0
5953  20230801   160500    160959  ...         0.0        0.0       0
5954  20230801   161000    161459  ...         0.0        0.0       0
5955  20230801   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 16:20:05,884:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28905.4, self.close=28913.5, self.high=28916.7, self.low=28896.9, self.vol=653.525, self.amt=18891752.3438, ukdf['pct'].iloc[-1]=0.00028 , ukdf['amount'].iloc[-1]=18891752.3438, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-28528.8036', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28913.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22817
self.closeSec=1690878299, self.tradeDate='20230801', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28913.5, self.close=28915.7, self.high=28921.9, self.low=28912.0, self.vol=433.728, self.amt=12542105.1143 
127.0.0.1 - - [01/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-01 16:25:00,801:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230801   160000    160459  ...         0.0        0.0       0
5953  20230801   160500    160959  ...         0.0        0.0       0
5954  20230801   161000    161459  ...         0.0        0.0       0
5955  20230801   161500    161959  ...         0.0        0.0       0
5956  20230801   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 16:25:00,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690878299, self.tradeDate='20230801', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28913.5, self.close=28915.7, self.high=28921.9, self.low=28912.0, self.vol=433.728, self.amt=12542105.1143, ukdf['pct'].iloc[-1]=7.6e-05 , ukdf['amount'].iloc[-1]=12542105.1143, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-28594.27252986084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28918.20120134', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28905.4, self.close=28913.5, self.high=28916.7, self.low=28896.9 
127.0.0.1 - - [01/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-01 16:20:03,824:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28905.4, self.close=28913.5, self.high=28916.7, self.low=28896.9   
2023-08-01 16:20:04,985:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230801   155500    155959  1690876799  ...  28917.6  0.000124   1631    5
1632  20230801   160000    160459  1690877099  ...  28915.8  0.000152   1632    0
1633  20230801   160500    160959  1690877399  ...  28909.3 -0.000411   1633    1
1634  20230801   161000    161459  1690877699  ...  28905.3 -0.000287   1634    2
1635  20230801   161500    161959  1690877999  ...  28896.9  0.000280   1635    3

[5 rows x 11 columns]
2023-08-01 16:20:04,995:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6176487252355592, self.count=22819 

self.closeSec=1690878299, self.tradeDate='20230801', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28913.5, self.close=28915.7, self.high=28921.9, self.low=28912.0 
127.0.0.1 - - [01/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-01 16:25:00,771:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690878299, self.tradeDate='20230801', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28913.5, self.close=28915.7, self.high=28921.9, self.low=28912.0   
2023-08-01 16:25:00,788:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230801   160000    160459  1690877099  ...  28915.8  0.000152   1632    0
1633  20230801   160500    160959  1690877399  ...  28909.3 -0.000411   1633    1
1634  20230801   161000    161459  1690877699  ...  28905.3 -0.000287   1634    2
1635  20230801   161500    161959  1690877999  ...  28896.9  0.000280   1635    3
1636  20230801   162000    162459  1690878299  ...  28912.0  0.000076   1636    4

[5 rows x 11 columns]
2023-08-01 16:25:00,789:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-01 16:00:18,707:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230801    132959  28852.2  ...  43.750000  0.388433  0.668407
5787  20230801    135959  28884.7  ...  44.166667  0.398305  0.671124
5788  20230801    142959  28910.5  ...  44.583333  0.408349  0.671359
5789  20230801    145959  28937.4  ...  44.583333  0.398892  0.674780
5790  20230801    152959  28900.1  ...  44.583333  0.401546  0.677372

[5 rows x 33 columns]
0.5756457564575646
acc is : 0.5756457564575646
2023-08-01 16:00:18,777:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.508445  0.491555       1  ...  0.931191  -1.0    0.0  0.971060
538     0  0.510825  0.489175       1  ...  0.930328  -1.0    0.0  0.971960
539     0  0.518983  0.481017       0  ...  0.931527  -1.0    0.0  0.970708
540     1  0.492891  0.507109       1  ...  0.931302  -1.0    0.0  0.970943
541     0  0.505005  0.494995       1  ...  0.930847  -1.0    0.0  0.971416

[5 rows x 10 columns]
2023-08-01 16:00:18,791:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508300  0.491700       1  ...  0.931191  -1.0    0.0  0.970246
46     0  0.510843  0.489157       1  ...  0.930328  -1.0    0.0  0.971132
47     0  0.519003  0.480997       0  ...  0.931527  -1.0    0.0  0.970095
48     1  0.493145  0.506855       1  ...  0.931302  -1.0    0.0  0.971386
49     0  0.505005  0.494995       1  ...  0.930847  -1.0    0.0  0.971416

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.804', 'enterprice': '28908.8', 'countrevence': '0', 'unrealprofit': '-360.11266685504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28923.92824176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230801   155000    155959  1690876799  28910.9  28921.2  0.000353
2023-08-01 16:00:02,369:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11408 

self.closeSec=1690877399, self.tradeDate='20230801', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28921.2', self.close='28913.7'
2023-08-01 16:10:01,136:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690877399, self.tradeDate='20230801', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28921.2', self.close='28913.7'
127.0.0.1 - - [01/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-01 16:10:01,143:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230801   152000    152959  1690874999  28894.7  28907.1  0.000429
525  20230801   153000    153959  1690875599  28907.1    28927  0.000688
526  20230801   154000    154959  1690876199  28926.9    28911 -0.000553
527  20230801   155000    155959  1690876799  28910.9  28921.2  0.000353
528  20230801   160000    160959  1690877399  28921.2  28913.7 -0.000259
2023-08-01 16:10:01,144:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11409 

self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28913.7', self.close='28913.5'
127.0.0.1 - - [01/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-01 16:20:06,515:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28913.7', self.close='28913.5'
2023-08-01 16:20:07,016:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230801   153000    153959  1690875599  28907.1    28927  0.000688
526  20230801   154000    154959  1690876199  28926.9    28911 -0.000553
527  20230801   155000    155959  1690876799  28910.9  28921.2  0.000353
528  20230801   160000    160959  1690877399  28921.2  28913.7 -0.000259
529  20230801   161000    161959  1690877999  28913.7  28913.5 -0.000007
2023-08-01 16:20:07,017:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230801   155000    155959  1690876799  28910.9  28921.2
2023-08-01 16:00:02,385:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11411 

self.closeSec=1690877399, self.tradeDate='20230801', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28921.2', self.close='28913.7'
2023-08-01 16:10:01,151:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690877399, self.tradeDate='20230801', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28921.2', self.close='28913.7'
2023-08-01 16:10:01,157:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230801   152000    152959  1690874999  28894.7  28907.1
17517  20230801   153000    153959  1690875599  28907.1    28927
17518  20230801   154000    154959  1690876199  28926.9    28911
17519  20230801   155000    155959  1690876799  28910.9  28921.2
17520  20230801   160000    160959  1690877399  28921.2  28913.7
2023-08-01 16:10:01,158:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11412 

self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28913.7', self.close='28913.5'
127.0.0.1 - - [01/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-01 16:20:07,966:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28913.7', self.close='28913.5'
2023-08-01 16:20:08,098:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230801   153000    153959  1690875599  28907.1    28927
17518  20230801   154000    154959  1690876199  28926.9    28911
17519  20230801   155000    155959  1690876799  28910.9  28921.2
17520  20230801   160000    160959  1690877399  28921.2  28913.7
17521  20230801   161000    161959  1690877999  28913.7  28913.5
2023-08-01 16:20:08,098:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230801   155000    155959  1690876799  28910.9  28921.2
2023-08-01 16:00:02,376:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11411 

self.closeSec=1690877399, self.tradeDate='20230801', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28921.2', self.close='28913.7'
2023-08-01 16:10:01,139:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690877399, self.tradeDate='20230801', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28921.2', self.close='28913.7'
127.0.0.1 - - [01/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-01 16:10:01,147:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230801   152000    152959  1690874999  28894.7  28907.1
12189  20230801   153000    153959  1690875599  28907.1    28927
12190  20230801   154000    154959  1690876199  28926.9    28911
12191  20230801   155000    155959  1690876799  28910.9  28921.2
12192  20230801   160000    160959  1690877399  28921.2  28913.7
2023-08-01 16:10:01,147:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11412 

self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28913.7', self.close='28913.5'
127.0.0.1 - - [01/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-01 16:20:07,785:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28913.7', self.close='28913.5'
2023-08-01 16:20:07,991:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230801   153000    153959  1690875599  28907.1    28927
12190  20230801   154000    154959  1690876199  28926.9    28911
12191  20230801   155000    155959  1690876799  28910.9  28921.2
12192  20230801   160000    160959  1690877399  28921.2  28913.7
12193  20230801   161000    161959  1690877999  28913.7  28913.5
2023-08-01 16:20:07,992:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22816
self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28905.4, self.close=28913.5, self.high=28916.7, self.low=28896.9, self.vol=653.525, self.amt=18891752.3438 
127.0.0.1 - - [01/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-01 16:20:05,874:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230801   155500    155959  ...         0.0        0.0       0
5952  20230801   160000    160459  ...         0.0        0.0       0
5953  20230801   160500    160959  ...         0.0        0.0       0
5954  20230801   161000    161459  ...         0.0        0.0       0
5955  20230801   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 16:20:05,894:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690877999, self.tradeDate='20230801', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28905.4, self.close=28913.5, self.high=28916.7, self.low=28896.9, self.vol=653.525, self.amt=18891752.3438, ukdf['pct'].iloc[-1]=0.00028 , ukdf['amount'].iloc[-1]=18891752.3438, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '76863.2995', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28913.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22817
self.closeSec=1690878299, self.tradeDate='20230801', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28913.5, self.close=28915.7, self.high=28921.9, self.low=28912.0, self.vol=433.728, self.amt=12542105.1143 
2023-08-01 16:25:00,769:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230801   160000    160459  ...         0.0        0.0       0
5953  20230801   160500    160959  ...         0.0        0.0       0
5954  20230801   161000    161459  ...         0.0        0.0       0
5955  20230801   161500    161959  ...         0.0        0.0       0
5956  20230801   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 16:25:00,770:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690878299, self.tradeDate='20230801', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28913.5, self.close=28915.7, self.high=28921.9, self.low=28912.0, self.vol=433.728, self.amt=12542105.1143, ukdf['pct'].iloc[-1]=7.6e-05 , ukdf['amount'].iloc[-1]=12542105.1143, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '77037.90681896894', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28918.20120134', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230801   040000    075959  1690847999  ...    721  0.062756 -0.996077    -1.0
722  20230801   080000    115959  1690862399  ...    722  0.004820 -1.235378    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '23512.39058367096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28812.77879121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=475
self.closeSec=1690876799, self.tradeDate='20230801', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28820.1, self.close=28921.2, self.high=28959.0, self.low=28785.3, self.vol=38804.577, self.amt=1120812210.5053 127.0.0.1 - - [01/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

2023-08-01 16:00:01,911:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690876799, self.tradeDate='20230801', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28820.1, self.close=28921.2, self.high=28959.0, self.low=28785.3, self.vol=38804.577, self.amt=1120812210.5053 
2023-08-01 16:00:01,927:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230731   200000    235959  ...  58214.878  1.707882e+09 -0.005599
720  20230801   000000    035959  ...  50437.485  1.472438e+09 -0.002942
721  20230801   040000    075959  ...  32949.344  9.621005e+08  0.002590
722  20230801   080000    115959  ...  88466.386  2.563316e+09 -0.013716
723  20230801   120000    155959  ...  38804.577  1.120812e+09  0.003511

[5 rows x 11 columns]
2023-08-01 16:00:02,647:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230731   200000    235959  1690819199  ...    719  0.033872 -1.156911    -1.0
720  20230801   000000    035959  1690833599  ...    720  0.048282 -1.075937    -1.0
721  20230801   040000    075959  1690847999  ...    721  0.062756 -0.996077    -1.0
722  20230801   080000    115959  1690862399  ...    722  0.004820 -1.235378    -1.0
723  20230801   120000    155959  1690876799  ...    723  0.056256 -0.989586    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '17503.87913775864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28923.99809089', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


