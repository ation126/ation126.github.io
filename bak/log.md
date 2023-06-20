# 20230620 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10720
self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26772.7, self.close=26760.1, self.high=26779.3, self.low=26756.4, self.vol=950.956, self.amt=25455132.3501 
127.0.0.1 - - [20/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-20 16:20:07,683:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230620   155500    155959  ...         0.0        0.0       0
5952  20230620   160000    160459  ...         0.0        0.0       0
5953  20230620   160500    160959  ...         0.0        0.0       0
5954  20230620   161000    161459  ...         0.0        0.0       0
5955  20230620   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 16:20:07,711:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26772.7, self.close=26760.1, self.high=26779.3, self.low=26756.4, self.vol=950.956, self.amt=25455132.3501, ukdf['pct'].iloc[-1]=-0.000471 , ukdf['amount'].iloc[-1]=25455132.3501, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1519.3266', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26755.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10721
self.closeSec=1687249499, self.tradeDate='20230620', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26760.2, self.close=26759.8, self.high=26780.9, self.low=26752.0, self.vol=1127.603, self.amt=30178647.5611 
2023-06-20 16:25:00,779:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230620   160000    160459  ...         0.0        0.0       0
5953  20230620   160500    160959  ...         0.0        0.0       0
5954  20230620   161000    161459  ...         0.0        0.0       0
5955  20230620   161500    161959  ...         0.0        0.0       0
5956  20230620   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 16:25:00,779:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687249499, self.tradeDate='20230620', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26760.2, self.close=26759.8, self.high=26780.9, self.low=26752.0, self.vol=1127.603, self.amt=30178647.5611, ukdf['pct'].iloc[-1]=-1.1e-05 , ukdf['amount'].iloc[-1]=30178647.5611, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1414.84198999968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26763.30284432', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26772.7, self.close=26760.1, self.high=26779.3, self.low=26756.4 
127.0.0.1 - - [20/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-20 16:20:04,891:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26772.7, self.close=26760.1, self.high=26779.3, self.low=26756.4   
2023-06-20 16:20:06,461:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230620   155500    155959  1687247999  ...  26813.1 -0.000101   1631    5
1632  20230620   160000    160459  1687248299  ...  26807.2 -0.000459   1632    0
1633  20230620   160500    160959  1687248599  ...  26766.2 -0.001007   1633    1
1634  20230620   161000    161459  1687248899  ...  26771.0 -0.000314   1634    2
1635  20230620   161500    161959  1687249199  ...  26756.4 -0.000471   1635    3

[5 rows x 11 columns]
2023-06-20 16:20:06,462:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=165, self.factor=0.36380436563261837, self.count=10723 

self.closeSec=1687249499, self.tradeDate='20230620', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26760.2, self.close=26759.8, self.high=26780.9, self.low=26752.0 
127.0.0.1 - - [20/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-20 16:25:00,716:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687249499, self.tradeDate='20230620', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26760.2, self.close=26759.8, self.high=26780.9, self.low=26752.0   
2023-06-20 16:25:00,731:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230620   160000    160459  1687248299  ...  26807.2 -0.000459   1632    0
1633  20230620   160500    160959  1687248599  ...  26766.2 -0.001007   1633    1
1634  20230620   161000    161459  1687248899  ...  26771.0 -0.000314   1634    2
1635  20230620   161500    161959  1687249199  ...  26756.4 -0.000471   1635    3
1636  20230620   162000    162459  1687249499  ...  26752.0 -0.000011   1636    4

[5 rows x 11 columns]
2023-06-20 16:25:00,732:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-20 16:00:19,174:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230620    132959  26951.4  ...  54.583333  0.576723  0.357044
5787  20230620    135959  26921.2  ...  54.583333  0.548950  0.361185
5788  20230620    142959  26805.5  ...  54.583333  0.547810  0.365419
5789  20230620    145959  26800.6  ...  54.583333  0.541071  0.371535
5790  20230620    152959  26771.7  ...  54.583333  0.547986  0.374605

[5 rows x 33 columns]
0.5627306273062731
acc is : 0.5627306273062731
2023-06-20 16:00:19,281:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494914  0.505086       0  ...  1.021669  -1.0    0.0  1.013601
538     1  0.469902  0.530098       0  ...  1.021856  -1.0    0.0  1.013416
539     1  0.489208  0.510792       0  ...  1.022954  -1.0    0.0  1.012327
540     1  0.479747  0.520253       1  ...  1.021613  -1.0    0.0  1.013654
541     1  0.490656  0.509344       1  ...  1.021098  -1.0    0.0  1.014165

[5 rows x 10 columns]
2023-06-20 16:00:19,306:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494497  0.505503       0  ...  1.021669  -1.0    0.0  1.010217
46     1  0.469488  0.530512       0  ...  1.021856  -1.0    0.0  1.010310
47     1  0.489035  0.510965       0  ...  1.022954  -1.0    0.0  1.010794
48     1  0.479698  0.520302       1  ...  1.021613  -1.0    0.0  1.013582
49     1  0.490656  0.509344       1  ...  1.021098  -1.0    0.0  1.014165

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.089', 'enterprice': '26626.6', 'countrevence': '0', 'unrealprofit': '-5508.2529', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26822.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230620   155000    155959  1687247999  26823.1  26820.4 -0.000097
2023-06-20 16:00:02,041:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5360 

self.closeSec=1687248599, self.tradeDate='20230620', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26820.5', self.close='26781.1'
2023-06-20 16:10:01,083:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687248599, self.tradeDate='20230620', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26820.5', self.close='26781.1'
127.0.0.1 - - [20/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-20 16:10:01,093:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230620   152000    152959  1687246199  26804.4  26806.8  0.000090
525  20230620   153000    153959  1687246799  26806.9  26805.1 -0.000063
526  20230620   154000    154959  1687247399    26805    26823  0.000668
527  20230620   155000    155959  1687247999  26823.1  26820.4 -0.000097
528  20230620   160000    160959  1687248599  26820.5  26781.1 -0.001465
2023-06-20 16:10:01,093:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5361 

self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26781.1', self.close='26760.1'
127.0.0.1 - - [20/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-20 16:20:07,351:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26781.1', self.close='26760.1'
2023-06-20 16:20:08,101:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230620   153000    153959  1687246799  26806.9  26805.1 -0.000063
526  20230620   154000    154959  1687247399    26805    26823  0.000668
527  20230620   155000    155959  1687247999  26823.1  26820.4 -0.000097
528  20230620   160000    160959  1687248599  26820.5  26781.1 -0.001465
529  20230620   161000    161959  1687249199  26781.1  26760.1 -0.000784
2023-06-20 16:20:08,111:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230620   155000    155959  1687247999  26823.1  26820.4
2023-06-20 16:00:02,052:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5363 

self.closeSec=1687248599, self.tradeDate='20230620', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26820.5', self.close='26781.1'
2023-06-20 16:10:01,104:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687248599, self.tradeDate='20230620', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26820.5', self.close='26781.1'
2023-06-20 16:10:01,114:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230620   152000    152959  1687246199  26804.4  26806.8
17517  20230620   153000    153959  1687246799  26806.9  26805.1
17518  20230620   154000    154959  1687247399    26805    26823
17519  20230620   155000    155959  1687247999  26823.1  26820.4
17520  20230620   160000    160959  1687248599  26820.5  26781.1
2023-06-20 16:10:01,114:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5364 

self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26781.1', self.close='26760.1'
127.0.0.1 - - [20/Jun/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-06-20 16:20:09,324:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26781.1', self.close='26760.1'
2023-06-20 16:20:09,465:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230620   153000    153959  1687246799  26806.9  26805.1
17518  20230620   154000    154959  1687247399    26805    26823
17519  20230620   155000    155959  1687247999  26823.1  26820.4
17520  20230620   160000    160959  1687248599  26820.5  26781.1
17521  20230620   161000    161959  1687249199  26781.1  26760.1
2023-06-20 16:20:09,466:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230620   155000    155959  1687247999  26823.1  26820.4
2023-06-20 16:00:02,031:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5363 

self.closeSec=1687248599, self.tradeDate='20230620', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26820.5', self.close='26781.1'
127.0.0.1 - - [20/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-20 16:10:01,100:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687248599, self.tradeDate='20230620', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26820.5', self.close='26781.1'
2023-06-20 16:10:01,127:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230620   152000    152959  1687246199  26804.4  26806.8
12189  20230620   153000    153959  1687246799  26806.9  26805.1
12190  20230620   154000    154959  1687247399    26805    26823
12191  20230620   155000    155959  1687247999  26823.1  26820.4
12192  20230620   160000    160959  1687248599  26820.5  26781.1
2023-06-20 16:10:01,128:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5364 

self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26781.1', self.close='26760.1'
127.0.0.1 - - [20/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-20 16:20:08,894:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26781.1', self.close='26760.1'
2023-06-20 16:20:09,201:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230620   153000    153959  1687246799  26806.9  26805.1
12190  20230620   154000    154959  1687247399    26805    26823
12191  20230620   155000    155959  1687247999  26823.1  26820.4
12192  20230620   160000    160959  1687248599  26820.5  26781.1
12193  20230620   161000    161959  1687249199  26781.1  26760.1
2023-06-20 16:20:09,203:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10720
self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26772.7, self.close=26760.1, self.high=26779.3, self.low=26756.4, self.vol=950.956, self.amt=25455132.3501 
127.0.0.1 - - [20/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-20 16:20:07,693:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230620   155500    155959  ...         0.0        0.0       0
5952  20230620   160000    160459  ...         0.0        0.0       0
5953  20230620   160500    160959  ...         0.0        0.0       0
5954  20230620   161000    161459  ...         0.0        0.0       0
5955  20230620   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 16:20:07,722:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687249199, self.tradeDate='20230620', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26772.7, self.close=26760.1, self.high=26779.3, self.low=26756.4, self.vol=950.956, self.amt=25455132.3501, ukdf['pct'].iloc[-1]=-0.000471 , ukdf['amount'].iloc[-1]=25455132.3501, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-3275.8362', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26755.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [20/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10721
self.closeSec=1687249499, self.tradeDate='20230620', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26760.2, self.close=26759.8, self.high=26780.9, self.low=26752.0, self.vol=1127.603, self.amt=30178647.5611 
2023-06-20 16:25:00,776:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230620   160000    160459  ...         0.0        0.0       0
5953  20230620   160500    160959  ...         0.0        0.0       0
5954  20230620   161000    161459  ...         0.0        0.0       0
5955  20230620   161500    161959  ...         0.0        0.0       0
5956  20230620   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 16:25:00,776:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687249499, self.tradeDate='20230620', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26760.2, self.close=26759.8, self.high=26780.9, self.low=26752.0, self.vol=1127.603, self.amt=30178647.5611, ukdf['pct'].iloc[-1]=-1.1e-05 , ukdf['amount'].iloc[-1]=30178647.5611, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2997.17305911088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26763.30284432', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230620   040000    075959  1687219199  ...    721  0.469583  0.213430     NaN
722  20230620   080000    115959  1687233599  ...    722  0.522307  0.501207     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '16782.27082716725', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26883.52463187', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1518762.96675, self.flagDict['side']='buy', self.tradeCount=5, self.count=223
self.closeSec=1687247999, self.tradeDate='20230620', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26880.7, self.close=26820.4, self.high=27024.2, self.low=26733.6, self.vol=58296.884, self.amt=1565392273.85182 
127.0.0.1 - - [20/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-20 16:00:01,624:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687247999, self.tradeDate='20230620', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26880.7, self.close=26820.4, self.high=27024.2, self.low=26733.6, self.vol=58296.884, self.amt=1565392273.85182 
2023-06-20 16:00:01,652:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230619   200000    235959  ...   65548.161  1.734847e+09 -0.000284
720  20230620   000000    035959  ...  200219.917  5.338475e+09  0.009145
721  20230620   040000    075959  ...   57994.516  1.551427e+09  0.005841
722  20230620   080000    115959  ...   79486.167  2.142766e+09  0.001942
723  20230620   120000    155959  ...   58296.884  1.565392e+09 -0.002243

[5 rows x 11 columns]
2023-06-20 16:00:03,018:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230619   200000    235959  1687190399  ...    719  0.568553  0.797705     1.0
720  20230620   000000    035959  1687204799  ...    720  0.473511  0.256385     NaN
721  20230620   040000    075959  1687219199  ...    721  0.469583  0.213430     NaN
722  20230620   080000    115959  1687233599  ...    722  0.522307  0.501207     NaN
723  20230620   120000    155959  1687247999  ...    723  0.454998  0.083055     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '13173.12', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26820.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


