# 20230718 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18784
self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29920.0, self.close=29895.0, self.high=29939.8, self.low=29871.8, self.vol=1625.987, self.amt=48630808.1901 
127.0.0.1 - - [18/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-18 16:20:05,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230718   155500    155959  ...         0.0        0.0       0
5952  20230718   160000    160459  ...         0.0        0.0       0
5953  20230718   160500    160959  ...         0.0        0.0       0
5954  20230718   161000    161459  ...         0.0        0.0       0
5955  20230718   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 16:20:05,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29920.0, self.close=29895.0, self.high=29939.8, self.low=29871.8, self.vol=1625.987, self.amt=48630808.1901, ukdf['pct'].iloc[-1]=-0.000839 , ukdf['amount'].iloc[-1]=48630808.1901, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42185.48215985862', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29894.16053137', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18785
self.closeSec=1689668699, self.tradeDate='20230718', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29895.0, self.close=29969.5, self.high=29969.5, self.low=29889.1, self.vol=1578.186, self.amt=47253347.4786 
2023-07-18 16:25:00,788:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230718   160000    160459  ...         0.0        0.0       0
5953  20230718   160500    160959  ...         0.0        0.0       0
5954  20230718   161000    161459  ...         0.0        0.0       0
5955  20230718   161500    161959  ...         0.0        0.0       0
5956  20230718   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 16:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689668699, self.tradeDate='20230718', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29895.0, self.close=29969.5, self.high=29969.5, self.low=29889.1, self.vol=1578.186, self.amt=47253347.4786, ukdf['pct'].iloc[-1]=0.002492 , ukdf['amount'].iloc[-1]=47253347.4786, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43269.4746', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29972', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29920.0, self.close=29895.0, self.high=29939.8, self.low=29871.8 
127.0.0.1 - - [18/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-18 16:20:03,876:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29920.0, self.close=29895.0, self.high=29939.8, self.low=29871.8   
2023-07-18 16:20:04,936:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230718   155500    155959  1689667199  ...  29950.9 -0.000764   1631    5
1632  20230718   160000    160459  1689667499  ...  29902.6 -0.001606   1632    0
1633  20230718   160500    160959  1689667799  ...  29900.0  0.000592   1633    1
1634  20230718   161000    161459  1689668099  ...  29864.6 -0.000047   1634    2
1635  20230718   161500    161959  1689668399  ...  29871.8 -0.000839   1635    3

[5 rows x 11 columns]
2023-07-18 16:20:04,937:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=52, self.factor=0.48665740617946307, self.count=18787 

self.closeSec=1689668699, self.tradeDate='20230718', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29895.0, self.close=29969.5, self.high=29969.5, self.low=29889.1 
127.0.0.1 - - [18/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-18 16:25:00,764:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689668699, self.tradeDate='20230718', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29895.0, self.close=29969.5, self.high=29969.5, self.low=29889.1   
2023-07-18 16:25:00,789:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230718   160000    160459  1689667499  ...  29902.6 -0.001606   1632    0
1633  20230718   160500    160959  1689667799  ...  29900.0  0.000592   1633    1
1634  20230718   161000    161459  1689668099  ...  29864.6 -0.000047   1634    2
1635  20230718   161500    161959  1689668399  ...  29871.8 -0.000839   1635    3
1636  20230718   162000    162459  1689668699  ...  29889.1  0.002492   1636    4

[5 rows x 11 columns]
2023-07-18 16:25:00,789:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-18 16:00:20,539:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230718    132959  30110.4  ...  51.250000  0.464215  0.360312
5787  20230718    135959  30058.8  ...  50.833333  0.460038  0.362122
5788  20230718    142959  30040.5  ...  50.416667  0.458574  0.364448
5789  20230718    145959  30034.0  ...  50.000000  0.445658  0.372301
5790  20230718    152959  29976.8  ...  50.000000  0.454229  0.376525

[5 rows x 33 columns]
0.5166051660516605
acc is : 0.5166051660516605
2023-07-18 16:00:20,614:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.492764  0.507236       0  ...  0.963513   1.0    0.0  1.000017
538     1  0.499380  0.500620       0  ...  0.963308   1.0    0.0  0.999804
539     0  0.502132  0.497868       0  ...  0.961476   1.0    0.0  0.997903
540     1  0.484817  0.515183       1  ...  0.962477   1.0    0.0  0.998941
541     0  0.504989  0.495011       0  ...  0.960674   1.0    0.0  0.997071

[5 rows x 10 columns]
2023-07-18 16:00:20,628:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492816  0.507184       0  ...  0.963513   1.0    0.0  0.996447
46     1  0.499981  0.500019       0  ...  0.957642   1.0    0.0  0.999970
47     0  0.502868  0.497132       0  ...  0.968516   1.0    0.0  1.003196
48     1  0.485177  0.514823       1  ...  0.962477   1.0    0.0  1.001773
49     0  0.504989  0.495011       0  ...  0.960674   1.0    0.0  0.997071

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.036', 'enterprice': '30219.4', 'countrevence': '0', 'unrealprofit': '-6501.32318094336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29948.91725824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230718   155000    155959  1689667199  29927.3  29951.9  0.000822
2023-07-18 16:00:02,453:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9392 

self.closeSec=1689667799, self.tradeDate='20230718', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29952', self.close='29921.5'
2023-07-18 16:10:01,118:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689667799, self.tradeDate='20230718', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29952', self.close='29921.5'
127.0.0.1 - - [18/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-18 16:10:01,137:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230718   152000    152959  1689665399  30026.6  30008.1 -0.000616
525  20230718   153000    153959  1689665999    30008  29978.8 -0.000976
526  20230718   154000    154959  1689666599  29978.8  29927.3 -0.001718
527  20230718   155000    155959  1689667199  29927.3  29951.9  0.000822
528  20230718   160000    160959  1689667799    29952  29921.5 -0.001015
2023-07-18 16:10:01,138:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9393 

self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29921.4', self.close='29895'
127.0.0.1 - - [18/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-18 16:20:06,407:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29921.4', self.close='29895'
2023-07-18 16:20:06,998:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230718   153000    153959  1689665999    30008  29978.8 -0.000976
526  20230718   154000    154959  1689666599  29978.8  29927.3 -0.001718
527  20230718   155000    155959  1689667199  29927.3  29951.9  0.000822
528  20230718   160000    160959  1689667799    29952  29921.5 -0.001015
529  20230718   161000    161959  1689668399  29921.4    29895 -0.000886
2023-07-18 16:20:06,998:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230718   155000    155959  1689667199  29927.3  29951.9
2023-07-18 16:00:02,467:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9395 

self.closeSec=1689667799, self.tradeDate='20230718', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29952', self.close='29921.5'
2023-07-18 16:10:01,129:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689667799, self.tradeDate='20230718', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29952', self.close='29921.5'
2023-07-18 16:10:01,137:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230718   152000    152959  1689665399  30026.6  30008.1
17517  20230718   153000    153959  1689665999    30008  29978.8
17518  20230718   154000    154959  1689666599  29978.8  29927.3
17519  20230718   155000    155959  1689667199  29927.3  29951.9
17520  20230718   160000    160959  1689667799    29952  29921.5
2023-07-18 16:10:01,138:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9396 

self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29921.4', self.close='29895'
127.0.0.1 - - [18/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-18 16:20:07,759:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29921.4', self.close='29895'
2023-07-18 16:20:07,954:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230718   153000    153959  1689665999    30008  29978.8
17518  20230718   154000    154959  1689666599  29978.8  29927.3
17519  20230718   155000    155959  1689667199  29927.3  29951.9
17520  20230718   160000    160959  1689667799    29952  29921.5
17521  20230718   161000    161959  1689668399  29921.4    29895
2023-07-18 16:20:07,955:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230718   155000    155959  1689667199  29927.3  29951.9
2023-07-18 16:00:02,448:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--: 127.0.0.1 - - [18/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9395 

self.closeSec=1689667799, self.tradeDate='20230718', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29952', self.close='29921.5'
2023-07-18 16:10:01,120:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689667799, self.tradeDate='20230718', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29952', self.close='29921.5'
2023-07-18 16:10:01,128:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230718   152000    152959  1689665399  30026.6  30008.1
12189  20230718   153000    153959  1689665999    30008  29978.8
12190  20230718   154000    154959  1689666599  29978.8  29927.3
12191  20230718   155000    155959  1689667199  29927.3  29951.9
12192  20230718   160000    160959  1689667799    29952  29921.5
2023-07-18 16:10:01,128:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9396 

self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29921.4', self.close='29895'
127.0.0.1 - - [18/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-18 16:20:07,609:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29921.4', self.close='29895'
2023-07-18 16:20:07,836:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230718   153000    153959  1689665999    30008  29978.8
12190  20230718   154000    154959  1689666599  29978.8  29927.3
12191  20230718   155000    155959  1689667199  29927.3  29951.9
12192  20230718   160000    160959  1689667799    29952  29921.5
12193  20230718   161000    161959  1689668399  29921.4    29895
2023-07-18 16:20:07,837:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18784
self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29920.0, self.close=29895.0, self.high=29939.8, self.low=29871.8, self.vol=1625.987, self.amt=48630808.1901 
127.0.0.1 - - [18/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-18 16:20:05,766:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230718   155500    155959  ...         0.0        0.0       0
5952  20230718   160000    160459  ...         0.0        0.0       0
5953  20230718   160500    160959  ...         0.0        0.0       0
5954  20230718   161000    161459  ...         0.0        0.0       0
5955  20230718   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 16:20:05,787:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689668399, self.tradeDate='20230718', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29920.0, self.close=29895.0, self.high=29939.8, self.low=29871.8, self.vol=1625.987, self.amt=48630808.1901, ukdf['pct'].iloc[-1]=-0.000839 , ukdf['amount'].iloc[-1]=48630808.1901, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '113286.01229561317', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29894.16053137', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18785
self.closeSec=1689668699, self.tradeDate='20230718', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29895.0, self.close=29969.5, self.high=29969.5, self.low=29889.1, self.vol=1578.186, self.amt=47253347.4786 
127.0.0.1 - - [18/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-18 16:25:00,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230718   160000    160459  ...         0.0        0.0       0
5953  20230718   160500    160959  ...         0.0        0.0       0
5954  20230718   161000    161459  ...         0.0        0.0       0
5955  20230718   161500    161959  ...         0.0        0.0       0
5956  20230718   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 16:25:00,802:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689668699, self.tradeDate='20230718', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29895.0, self.close=29969.5, self.high=29969.5, self.low=29889.1, self.vol=1578.186, self.amt=47253347.4786, ukdf['pct'].iloc[-1]=0.002492 , ukdf['amount'].iloc[-1]=47253347.4786, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '116177.048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29972', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230718   040000    075959  1689638399  ...    721  0.608408  0.713520     1.0
722  20230718   080000    115959  1689652799  ...    722  0.497627  0.265788     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-23367.3993', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30063.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=391
self.closeSec=1689667199, self.tradeDate='20230718', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30063.8, self.close=29951.9, self.high=30110.9, self.low=29908.1, self.vol=38504.713, self.amt=1155474666.27174 
127.0.0.1 - - [18/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-18 16:00:01,997:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689667199, self.tradeDate='20230718', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30063.8, self.close=29951.9, self.high=30110.9, self.low=29908.1, self.vol=38504.713, self.amt=1155474666.27174 
2023-07-18 16:00:02,013:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230717   200000    235959  ...   66486.808  2.006394e+09  0.000610
720  20230718   000000    035959  ...  122153.882  3.654921e+09 -0.009727
721  20230718   040000    075959  ...   51790.057  1.558369e+09  0.008574
722  20230718   080000    115959  ...   23756.585  7.160705e+08 -0.002068
723  20230718   120000    155959  ...   38504.713  1.155475e+09 -0.003722

[5 rows x 11 columns]
2023-07-18 16:00:02,765:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230717   200000    235959  1689609599  ...    719  0.746221  1.277956     1.0
720  20230718   000000    035959  1689623999  ...    720  0.675919  0.990122     1.0
721  20230718   040000    075959  1689638399  ...    721  0.608408  0.713520     1.0
722  20230718   080000    115959  1689652799  ...    722  0.497627  0.265788     NaN
723  20230718   120000    155959  1689667199  ...    723  0.375309 -0.236925     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-29177.4796123783', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29952.5831337', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


