# 20230627 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12736
self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30386.2, self.close=30386.0, self.high=30402.9, self.low=30385.0, self.vol=493.272, self.amt=14991710.1393 
127.0.0.1 - - [27/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-27 16:20:07,851:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230627   155500    155959  ...         0.0        0.0       0
5952  20230627   160000    160459  ...         0.0        0.0       0
5953  20230627   160500    160959  ...         0.0        0.0       0
5954  20230627   161000    161459  ...         0.0        0.0       0
5955  20230627   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 16:20:07,881:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30386.2, self.close=30386.0, self.high=30402.9, self.low=30385.0, self.vol=493.272, self.amt=14991710.1393, ukdf['pct'].iloc[-1]=-3e-06 , ukdf['amount'].iloc[-1]=14991710.1393, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49089.15', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30389.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12737
self.closeSec=1687854299, self.tradeDate='20230627', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30386.1, self.close=30396.7, self.high=30400.1, self.low=30386.0, self.vol=410.847, self.amt=12487782.9179 
2023-06-27 16:25:00,839:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230627   160000    160459  ...         0.0        0.0       0
5953  20230627   160500    160959  ...         0.0        0.0       0
5954  20230627   161000    161459  ...         0.0        0.0       0
5955  20230627   161500    161959  ...         0.0        0.0       0
5956  20230627   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 16:25:00,839:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687854299, self.tradeDate='20230627', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30386.1, self.close=30396.7, self.high=30400.1, self.low=30386.0, self.vol=410.847, self.amt=12487782.9179, ukdf['pct'].iloc[-1]=0.000352 , ukdf['amount'].iloc[-1]=12487782.9179, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49185.2394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30396.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30386.2, self.close=30386.0, self.high=30402.9, self.low=30385.0 
127.0.0.1 - - [27/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-27 16:20:05,221:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30386.2, self.close=30386.0, self.high=30402.9, self.low=30385.0   
2023-06-27 16:20:06,871:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230627   155500    155959  1687852799  ...  30379.6 -0.000431   1631    5
1632  20230627   160000    160459  1687853099  ...  30393.0  0.000809   1632    0
1633  20230627   160500    160959  1687853399  ...  30367.4 -0.001374   1633    1
1634  20230627   161000    161459  1687853699  ...  30382.9 -0.000039   1634    2
1635  20230627   161500    161959  1687853999  ...  30385.0 -0.000003   1635    3

[5 rows x 11 columns]
2023-06-27 16:20:06,901:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [27/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=2, self.factor=0.5925911282405583, self.count=12739 

self.closeSec=1687854299, self.tradeDate='20230627', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30386.1, self.close=30396.7, self.high=30400.1, self.low=30386.0 
2023-06-27 16:25:00,796:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687854299, self.tradeDate='20230627', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30386.1, self.close=30396.7, self.high=30400.1, self.low=30386.0   
2023-06-27 16:25:00,824:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230627   160000    160459  1687853099  ...  30393.0  0.000809   1632    0
1633  20230627   160500    160959  1687853399  ...  30367.4 -0.001374   1633    1
1634  20230627   161000    161459  1687853699  ...  30382.9 -0.000039   1634    2
1635  20230627   161500    161959  1687853999  ...  30385.0 -0.000003   1635    3
1636  20230627   162000    162459  1687854299  ...  30386.0  0.000352   1636    4

[5 rows x 11 columns]
2023-06-27 16:25:00,824:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-27 16:00:18,840:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230627    132959  30335.9  ...  47.500000  0.489026  0.478625
5787  20230627    135959  30299.5  ...  47.916667  0.491536  0.477108
5788  20230627    142959  30313.0  ...  47.916667  0.479000  0.481740
5789  20230627    145959  30242.5  ...  48.333333  0.491501  0.480349
5790  20230627    152959  30309.0  ...  48.750000  0.496480  0.476744

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-06-27 16:00:18,948:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.482273  0.517727       1  ...  1.115641  -1.0    0.0  1.189552
538     1  0.493519  0.506481       0  ...  1.118235  -1.0    0.0  1.186786
539     1  0.478744  0.521256       1  ...  1.115773  -1.0    0.0  1.189399
540     0  0.503648  0.496352       1  ...  1.114782  -1.0    0.0  1.190455
541     0  0.501524  0.498476       1  ...  1.112265  -1.0    0.0  1.193143

[5 rows x 10 columns]
2023-06-27 16:00:18,973:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.482392  0.517608       1  ...  1.115641  -1.0    0.0  1.183385
46     1  0.493447  0.506553       0  ...  1.118235  -1.0    0.0  1.182327
47     1  0.478848  0.521152       1  ...  1.115773  -1.0    0.0  1.184592
48     0  0.503499  0.496501       1  ...  1.114782  -1.0    0.0  1.190740
49     0  0.501524  0.498476       1  ...  1.112265  -1.0    0.0  1.193143

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.381', 'enterprice': '30103.1', 'countrevence': '0', 'unrealprofit': '-8485.3719', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30413', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230627   155000    155959  1687852799  30387.5  30404.5  0.000559
2023-06-27 16:00:02,116:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6368 

self.closeSec=1687853399, self.tradeDate='20230627', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30404.5', self.close='30387.3'
2023-06-27 16:10:01,140:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687853399, self.tradeDate='20230627', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30404.5', self.close='30387.3'
127.0.0.1 - - [27/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-27 16:10:01,148:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230627   152000    152959  1687850999  30361.6    30336 -0.000843
525  20230627   153000    153959  1687851599    30336    30368  0.001055
526  20230627   154000    154959  1687852199  30368.1  30387.5  0.000642
527  20230627   155000    155959  1687852799  30387.5  30404.5  0.000559
528  20230627   160000    160959  1687853399  30404.5  30387.3 -0.000566
2023-06-27 16:10:01,149:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6369 

self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30387.3', self.close='30386'
127.0.0.1 - - [27/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-27 16:20:07,512:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30387.3', self.close='30386'
2023-06-27 16:20:08,362:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230627   153000    153959  1687851599    30336    30368  0.001055
526  20230627   154000    154959  1687852199  30368.1  30387.5  0.000642
527  20230627   155000    155959  1687852799  30387.5  30404.5  0.000559
528  20230627   160000    160959  1687853399  30404.5  30387.3 -0.000566
529  20230627   161000    161959  1687853999  30387.3    30386 -0.000043
2023-06-27 16:20:08,371:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230627   155000    155959  1687852799  30387.5  30404.5
2023-06-27 16:00:02,132:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6371 

self.closeSec=1687853399, self.tradeDate='20230627', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30404.5', self.close='30387.3'
2023-06-27 16:10:01,163:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687853399, self.tradeDate='20230627', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30404.5', self.close='30387.3'
2023-06-27 16:10:01,169:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230627   152000    152959  1687850999  30361.6    30336
17517  20230627   153000    153959  1687851599    30336    30368
17518  20230627   154000    154959  1687852199  30368.1  30387.5
17519  20230627   155000    155959  1687852799  30387.5  30404.5
17520  20230627   160000    160959  1687853399  30404.5  30387.3
2023-06-27 16:10:01,169:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6372 

self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30387.3', self.close='30386'
127.0.0.1 - - [27/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-27 16:20:09,655:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30387.3', self.close='30386'
2023-06-27 16:20:09,784:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230627   153000    153959  1687851599    30336    30368
17518  20230627   154000    154959  1687852199  30368.1  30387.5
17519  20230627   155000    155959  1687852799  30387.5  30404.5
17520  20230627   160000    160959  1687853399  30404.5  30387.3
17521  20230627   161000    161959  1687853999  30387.3    30386
2023-06-27 16:20:09,785:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230627   155000    155959  1687852799  30387.5  30404.5
2023-06-27 16:00:02,127:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6371 

self.closeSec=1687853399, self.tradeDate='20230627', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30404.5', self.close='30387.3'
2023-06-27 16:10:01,158:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687853399, self.tradeDate='20230627', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30404.5', self.close='30387.3'
127.0.0.1 - - [27/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-27 16:10:01,166:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230627   152000    152959  1687850999  30361.6    30336
12189  20230627   153000    153959  1687851599    30336    30368
12190  20230627   154000    154959  1687852199  30368.1  30387.5
12191  20230627   155000    155959  1687852799  30387.5  30404.5
12192  20230627   160000    160959  1687853399  30404.5  30387.3
2023-06-27 16:10:01,166:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6372 

self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30387.3', self.close='30386'
127.0.0.1 - - [27/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-27 16:20:09,151:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30387.3', self.close='30386'
2023-06-27 16:20:09,461:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230627   153000    153959  1687851599    30336    30368
12190  20230627   154000    154959  1687852199  30368.1  30387.5
12191  20230627   155000    155959  1687852799  30387.5  30404.5
12192  20230627   160000    160959  1687853399  30404.5  30387.3
12193  20230627   161000    161959  1687853999  30387.3    30386
2023-06-27 16:20:09,463:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12736
self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30386.2, self.close=30386.0, self.high=30402.9, self.low=30385.0, self.vol=493.272, self.amt=14991710.1393 
127.0.0.1 - - [27/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-27 16:20:07,841:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230627   155500    155959  ...         0.0        0.0       0
5952  20230627   160000    160459  ...         0.0        0.0       0
5953  20230627   160500    160959  ...         0.0        0.0       0
5954  20230627   161000    161459  ...         0.0        0.0       0
5955  20230627   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 16:20:07,882:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687853999, self.tradeDate='20230627', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30386.2, self.close=30386.0, self.high=30402.9, self.low=30385.0, self.vol=493.272, self.amt=14991710.1393, ukdf['pct'].iloc[-1]=-3e-06 , ukdf['amount'].iloc[-1]=14991710.1393, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '131642.04843694229', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30388.38621569', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [27/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12737
self.closeSec=1687854299, self.tradeDate='20230627', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30386.1, self.close=30396.7, self.high=30400.1, self.low=30386.0, self.vol=410.847, self.amt=12487782.9179 
2023-06-27 16:25:00,837:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230627   160000    160459  ...         0.0        0.0       0
5953  20230627   160500    160959  ...         0.0        0.0       0
5954  20230627   161000    161459  ...         0.0        0.0       0
5955  20230627   161500    161959  ...         0.0        0.0       0
5956  20230627   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 16:25:00,838:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687854299, self.tradeDate='20230627', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30386.1, self.close=30396.7, self.high=30400.1, self.low=30386.0, self.vol=410.847, self.amt=12487782.9179, ukdf['pct'].iloc[-1]=0.000352 , ukdf['amount'].iloc[-1]=12487782.9179, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '131954.5448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30396.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230627   040000    075959  1687823999  ...    721  0.210680 -0.981612    -1.0
722  20230627   080000    115959  1687838399  ...    722  0.180171 -1.049700    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '18446.7084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30360.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=265
self.closeSec=1687852799, self.tradeDate='20230627', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30360.0, self.close=30404.5, self.high=30470.0, self.low=30222.5, self.vol=36501.042, self.amt=1107267998.3076 
127.0.0.1 - - [27/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-27 16:00:01,691:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687852799, self.tradeDate='20230627', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30360.0, self.close=30404.5, self.high=30470.0, self.low=30222.5, self.vol=36501.042, self.amt=1107267998.3076 
2023-06-27 16:00:01,715:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230626   200000    235959  ...   86040.677  2.618050e+09  0.002817
720  20230627   000000    035959  ...  106775.619  3.216007e+09 -0.005480
721  20230627   040000    075959  ...   28608.033  8.638494e+08  0.000867
722  20230627   080000    115959  ...   41157.089  1.249641e+09  0.003301
723  20230627   120000    155959  ...   36501.042  1.107268e+09  0.001466

[5 rows x 11 columns]
2023-06-27 16:00:03,182:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230626   200000    235959  1687795199  ...    719  0.179621 -1.091527    -1.0
720  20230627   000000    035959  1687809599  ...    720  0.227606 -0.948147    -1.0
721  20230627   040000    075959  1687823999  ...    721  0.210680 -0.981612    -1.0
722  20230627   080000    115959  1687838399  ...    722  0.180171 -1.049700    -1.0
723  20230627   120000    155959  1687852799  ...    723  0.108286 -1.222146    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '16113.57', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30404.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


