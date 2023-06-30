# 20230630 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13600
self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30733.7, self.close=30787.5, self.high=30787.9, self.low=30721.1, self.vol=1149.144, self.amt=35347408.5899 
127.0.0.1 - - [30/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-30 16:20:07,927:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230630   155500    155959  ...         0.0        0.0       0
5952  20230630   160000    160459  ...         0.0        0.0       0
5953  20230630   160500    160959  ...         0.0        0.0       0
5954  20230630   161000    161459  ...         0.0        0.0       0
5955  20230630   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 16:20:07,948:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30733.7, self.close=30787.5, self.high=30787.9, self.low=30721.1, self.vol=1149.144, self.amt=35347408.5899, ukdf['pct'].iloc[-1]=0.001666 , ukdf['amount'].iloc[-1]=35347408.5899, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-54610.809', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30786.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13601
self.closeSec=1688113499, self.tradeDate='20230630', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30787.5, self.close=30791.4, self.high=30796.9, self.low=30762.7, self.vol=1299.729, self.amt=40012712.3364 
2023-06-30 16:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230630   160000    160459  ...         0.0        0.0       0
5953  20230630   160500    160959  ...         0.0        0.0       0
5954  20230630   161000    161459  ...         0.0        0.0       0
5955  20230630   161500    161959  ...         0.0        0.0       0
5956  20230630   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 16:25:00,819:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688113499, self.tradeDate='20230630', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30787.5, self.close=30791.4, self.high=30796.9, self.low=30762.7, self.vol=1299.729, self.amt=40012712.3364, ukdf['pct'].iloc[-1]=0.000127 , ukdf['amount'].iloc[-1]=40012712.3364, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-54680.439', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30791.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30733.7, self.close=30787.5, self.high=30787.9, self.low=30721.1 
127.0.0.1 - - [30/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-30 16:20:05,277:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30733.7, self.close=30787.5, self.high=30787.9, self.low=30721.1   
2023-06-30 16:20:06,929:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230630   155500    155959  1688111999  ...  30752.1 -0.001506   1631    5
1632  20230630   160000    160459  1688112299  ...  30727.4 -0.000696   1632    0
1633  20230630   160500    160959  1688112599  ...  30709.9 -0.000205   1633    1
1634  20230630   161000    161459  1688112899  ...  30720.0  0.000159   1634    2
1635  20230630   161500    161959  1688113199  ...  30721.1  0.001666   1635    3

[5 rows x 11 columns]
2023-06-30 16:20:06,957:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [30/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=47, self.factor=0.4374481019659933, self.count=13603 

self.closeSec=1688113499, self.tradeDate='20230630', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30787.5, self.close=30791.4, self.high=30796.9, self.low=30762.7 
2023-06-30 16:25:00,758:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688113499, self.tradeDate='20230630', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30787.5, self.close=30791.4, self.high=30796.9, self.low=30762.7   
2023-06-30 16:25:00,798:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230630   160000    160459  1688112299  ...  30727.4 -0.000696   1632    0
1633  20230630   160500    160959  1688112599  ...  30709.9 -0.000205   1633    1
1634  20230630   161000    161459  1688112899  ...  30720.0  0.000159   1634    2
1635  20230630   161500    161959  1688113199  ...  30721.1  0.001666   1635    3
1636  20230630   162000    162459  1688113499  ...  30762.7  0.000127   1636    4

[5 rows x 11 columns]
2023-06-30 16:25:00,798:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-30 16:00:18,301:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230630    132959  30868.4  ...  50.416667  0.575232  0.406391
5787  20230630    135959  30887.4  ...  50.416667  0.546282  0.414456
5788  20230630    142959  30731.6  ...  50.000000  0.530274  0.427654
5789  20230630    145959  30639.8  ...  50.416667  0.533816  0.438531
5790  20230630    152959  30663.2  ...  50.833333  0.533924  0.448640

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-06-30 16:00:18,388:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.540909  0.459091       0  ...  1.010575   1.0    0.0  1.166011
538     1  0.490182  0.509818       0  ...  1.007560   1.0    0.0  1.162532
539     1  0.493756  0.506244       1  ...  1.008326   1.0    0.0  1.163416
540     0  0.510888  0.489112       0  ...  1.008349   1.0    0.0  1.163442
541     0  0.500113  0.499887       1  ...  1.011483   1.0    0.0  1.167058

[5 rows x 10 columns]
2023-06-30 16:00:18,400:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.541154  0.458846       0  ...  1.010575   1.0    0.0  1.164500
46     1  0.490465  0.509535       0  ...  1.007560   1.0    0.0  1.162845
47     1  0.493900  0.506100       1  ...  1.008326   1.0    0.0  1.164582
48     0  0.510898  0.489102       0  ...  1.008349   1.0    0.0  1.162357
49     0  0.500113  0.499887       1  ...  1.011483   1.0    0.0  1.167058

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.241', 'enterprice': '30643.5', 'countrevence': '0', 'unrealprofit': '3497.9253', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30776.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230630   155000    155959  1688111999  30756.3  30759.1  0.000091
2023-06-30 16:00:02,122:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [30/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6800 

self.closeSec=1688112599, self.tradeDate='20230630', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30759.2', self.close='30731.4'
2023-06-30 16:10:01,126:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688112599, self.tradeDate='20230630', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30759.2', self.close='30731.4'
2023-06-30 16:10:01,143:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230630   152000    152959  1688110199  30709.9  30663.8 -0.001501
525  20230630   153000    153959  1688110799  30663.7  30720.4  0.001846
526  20230630   154000    154959  1688111399  30720.5  30756.3  0.001169
527  20230630   155000    155959  1688111999  30756.3  30759.1  0.000091
528  20230630   160000    160959  1688112599  30759.2  30731.4 -0.000901
2023-06-30 16:10:01,144:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6801 

self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30731.3', self.close='30787.5'
127.0.0.1 - - [30/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-30 16:20:07,737:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30731.3', self.close='30787.5'
2023-06-30 16:20:08,547:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230630   153000    153959  1688110799  30663.7  30720.4  0.001846
526  20230630   154000    154959  1688111399  30720.5  30756.3  0.001169
527  20230630   155000    155959  1688111999  30756.3  30759.1  0.000091
528  20230630   160000    160959  1688112599  30759.2  30731.4 -0.000901
529  20230630   161000    161959  1688113199  30731.3  30787.5  0.001825
2023-06-30 16:20:08,556:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230630   155000    155959  1688111999  30756.3  30759.1
2023-06-30 16:00:02,071:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6803 

self.closeSec=1688112599, self.tradeDate='20230630', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30759.2', self.close='30731.4'
2023-06-30 16:10:01,130:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688112599, self.tradeDate='20230630', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30759.2', self.close='30731.4'
2023-06-30 16:10:01,153:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230630   152000    152959  1688110199  30709.9  30663.8
17517  20230630   153000    153959  1688110799  30663.7  30720.4
17518  20230630   154000    154959  1688111399  30720.5  30756.3
17519  20230630   155000    155959  1688111999  30756.3  30759.1
17520  20230630   160000    160959  1688112599  30759.2  30731.4
2023-06-30 16:10:01,153:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6804 

self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30731.3', self.close='30787.5'
127.0.0.1 - - [30/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-30 16:20:09,733:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30731.3', self.close='30787.5'
2023-06-30 16:20:09,884:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230630   153000    153959  1688110799  30663.7  30720.4
17518  20230630   154000    154959  1688111399  30720.5  30756.3
17519  20230630   155000    155959  1688111999  30756.3  30759.1
17520  20230630   160000    160959  1688112599  30759.2  30731.4
17521  20230630   161000    161959  1688113199  30731.3  30787.5
2023-06-30 16:20:09,885:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230630   155000    155959  1688111999  30756.3  30759.1
2023-06-30 16:00:02,119:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6803 

self.closeSec=1688112599, self.tradeDate='20230630', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30759.2', self.close='30731.4'
2023-06-30 16:10:01,130:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688112599, self.tradeDate='20230630', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30759.2', self.close='30731.4'
2023-06-30 16:10:01,146:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230630   152000    152959  1688110199  30709.9  30663.8
12189  20230630   153000    153959  1688110799  30663.7  30720.4
12190  20230630   154000    154959  1688111399  30720.5  30756.3
12191  20230630   155000    155959  1688111999  30756.3  30759.1
12192  20230630   160000    160959  1688112599  30759.2  30731.4
2023-06-30 16:10:01,146:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6804 

self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30731.3', self.close='30787.5'
127.0.0.1 - - [30/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-30 16:20:09,289:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30731.3', self.close='30787.5'
2023-06-30 16:20:09,607:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230630   153000    153959  1688110799  30663.7  30720.4
12190  20230630   154000    154959  1688111399  30720.5  30756.3
12191  20230630   155000    155959  1688111999  30756.3  30759.1
12192  20230630   160000    160959  1688112599  30759.2  30731.4
12193  20230630   161000    161959  1688113199  30731.3  30787.5
2023-06-30 16:20:09,608:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13600
self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30733.7, self.close=30787.5, self.high=30787.9, self.low=30721.1, self.vol=1149.144, self.amt=35347408.5899 
127.0.0.1 - - [30/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-30 16:20:07,891:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230630   155500    155959  ...         0.0        0.0       0
5952  20230630   160000    160459  ...         0.0        0.0       0
5953  20230630   160500    160959  ...         0.0        0.0       0
5954  20230630   161000    161459  ...         0.0        0.0       0
5955  20230630   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 16:20:07,918:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688113199, self.tradeDate='20230630', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30733.7, self.close=30787.5, self.high=30787.9, self.low=30721.1, self.vol=1149.144, self.amt=35347408.5899, ukdf['pct'].iloc[-1]=0.001666 , ukdf['amount'].iloc[-1]=35347408.5899, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '146424.6784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30786.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [30/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13601
self.closeSec=1688113499, self.tradeDate='20230630', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30787.5, self.close=30791.4, self.high=30796.9, self.low=30762.7, self.vol=1299.729, self.amt=40012712.3364 
2023-06-30 16:25:00,819:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230630   160000    160459  ...         0.0        0.0       0
5953  20230630   160500    160959  ...         0.0        0.0       0
5954  20230630   161000    161459  ...         0.0        0.0       0
5955  20230630   161500    161959  ...         0.0        0.0       0
5956  20230630   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 16:25:00,820:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688113499, self.tradeDate='20230630', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30787.5, self.close=30791.4, self.high=30796.9, self.low=30762.7, self.vol=1299.729, self.amt=40012712.3364, ukdf['pct'].iloc[-1]=0.000127 , ukdf['amount'].iloc[-1]=40012712.3364, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '146610.3834', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30791.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230630   040000    075959  1688083199  ...    721  0.334840 -0.679149    -1.0
722  20230630   080000    115959  1688097599  ...    722  0.378413 -0.570406     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-1649.50039995924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30737.96606593', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=283
self.closeSec=1688111999, self.tradeDate='20230630', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30734.4, self.close=30759.1, self.high=31300.0, self.low=30604.0, self.vol=144771.236, self.amt=4472121436.63202 
127.0.0.1 - - [30/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-30 16:00:01,631:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688111999, self.tradeDate='20230630', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30734.4, self.close=30759.1, self.high=31300.0, self.low=30604.0, self.vol=144771.236, self.amt=4472121436.63202 
2023-06-30 16:00:01,655:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230629   200000    235959  ...  113767.896  3.482065e+09 -0.006275
720  20230630   000000    035959  ...   54373.148  1.660331e+09  0.003387
721  20230630   040000    075959  ...   43576.159  1.324846e+09 -0.004305
722  20230630   080000    115959  ...   74469.724  2.280098e+09  0.009672
723  20230630   120000    155959  ...  144771.236  4.472121e+09  0.000807

[5 rows x 11 columns]
2023-06-30 16:00:02,930:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230629   200000    235959  1688054399  ...    719  0.355426 -0.588082     NaN
720  20230630   000000    035959  1688068799  ...    720  0.333707 -0.664776    -1.0
721  20230630   040000    075959  1688083199  ...    721  0.334840 -0.679149    -1.0
722  20230630   080000    115959  1688097599  ...    722  0.378413 -0.570406     NaN
723  20230630   120000    155959  1688111999  ...    723  0.725928  0.394365     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-2813.6173207524', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30759.8200293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


