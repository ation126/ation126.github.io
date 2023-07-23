# 20230723 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20224
self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29880.1, self.close=29876.2, self.high=29880.2, self.low=29871.6, self.vol=256.226, self.amt=7654856.1505 
127.0.0.1 - - [23/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-23 16:20:05,486:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230723   155500    155959  ...         0.0        0.0       0
5952  20230723   160000    160459  ...         0.0        0.0       0
5953  20230723   160500    160959  ...         0.0        0.0       0
5954  20230723   161000    161459  ...         0.0        0.0       0
5955  20230723   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 16:20:05,505:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29880.1, self.close=29876.2, self.high=29880.2, self.low=29871.6, self.vol=256.226, self.amt=7654856.1505, ukdf['pct'].iloc[-1]=-0.000131 , ukdf['amount'].iloc[-1]=7654856.1505, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41936.7564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29876.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20225
self.closeSec=1690100699, self.tradeDate='20230723', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29876.2, self.close=29883.6, self.high=29883.6, self.low=29876.2, self.vol=224.545, self.amt=6709227.1308 
2023-07-23 16:25:00,772:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230723   160000    160459  ...         0.0        0.0       0
5953  20230723   160500    160959  ...         0.0        0.0       0
5954  20230723   161000    161459  ...         0.0        0.0       0
5955  20230723   161500    161959  ...         0.0        0.0       0
5956  20230723   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 16:25:00,773:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690100699, self.tradeDate='20230723', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29876.2, self.close=29883.6, self.high=29883.6, self.low=29876.2, self.vol=224.545, self.amt=6709227.1308, ukdf['pct'].iloc[-1]=0.000248 , ukdf['amount'].iloc[-1]=6709227.1308, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42038.4162', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29883.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29880.1, self.close=29876.2, self.high=29880.2, self.low=29871.6 
127.0.0.1 - - [23/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-23 16:20:03,875:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29880.1, self.close=29876.2, self.high=29880.2, self.low=29871.6   
2023-07-23 16:20:04,956:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230723   155500    155959  1690099199  ...  29881.9  0.000632   1631    5
1632  20230723   160000    160459  1690099499  ...  29900.9  0.000020   1632    0
1633  20230723   160500    160959  1690099799  ...  29892.8 -0.000291   1633    1
1634  20230723   161000    161459  1690100099  ...  29880.1 -0.000425   1634    2
1635  20230723   161500    161959  1690100399  ...  29871.6 -0.000131   1635    3

[5 rows x 11 columns]
2023-07-23 16:20:04,965:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=13, self.factor=0.5078938891324838, self.count=20227 

self.closeSec=1690100699, self.tradeDate='20230723', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29876.2, self.close=29883.6, self.high=29883.6, self.low=29876.2 
2023-07-23 16:25:00,743:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690100699, self.tradeDate='20230723', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29876.2, self.close=29883.6, self.high=29883.6, self.low=29876.2   
2023-07-23 16:25:00,754:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230723   160000    160459  1690099499  ...  29900.9  0.000020   1632    0
1633  20230723   160500    160959  1690099799  ...  29892.8 -0.000291   1633    1
1634  20230723   161000    161459  1690100099  ...  29880.1 -0.000425   1634    2
1635  20230723   161500    161959  1690100399  ...  29871.6 -0.000131   1635    3
1636  20230723   162000    162459  1690100699  ...  29876.2  0.000248   1636    4

[5 rows x 11 columns]
2023-07-23 16:25:00,755:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-23 16:00:17,824:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230723    132959  29892.7  ...  50.416667  0.532760  0.499013
5787  20230723    135959  29954.8  ...  50.416667  0.516225  0.477203
5788  20230723    142959  29910.6  ...  50.416667  0.508000  0.460892
5789  20230723    145959  29887.9  ...  50.833333  0.515013  0.442071
5790  20230723    152959  29908.1  ...  50.416667  0.508391  0.427726

[5 rows x 33 columns]
0.5129151291512916
acc is : 0.5129151291512916
2023-07-23 16:00:17,882:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.527690  0.472310       0  ...  0.966319   1.0    0.0  0.980675
538     0  0.502061  0.497939       0  ...  0.965589   1.0    0.0  0.979934
539     0  0.505490  0.494510       1  ...  0.966238   1.0    0.0  0.980593
540     0  0.515337  0.484663       0  ...  0.965657   1.0    0.0  0.980003
541     0  0.500136  0.499864       1  ...  0.966006   1.0    0.0  0.980357

[5 rows x 10 columns]
2023-07-23 16:00:17,893:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.527257  0.472743       0  ...  0.966319   1.0    0.0  0.978369
46     0  0.501256  0.498744       0  ...  0.965589   1.0    0.0  0.975775
47     0  0.504924  0.495076       1  ...  0.966238   1.0    0.0  0.977121
48     0  0.515043  0.484957       0  ...  0.965657   1.0    0.0  0.978547
49     0  0.500136  0.499864       1  ...  0.966006   1.0    0.0  0.980357

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '1593.66244903796', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29907.27741209', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230723   155000    155959  1690099199  29875.9  29900.9  0.000837
2023-07-23 16:00:02,289:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10112 

self.closeSec=1690099799, self.tradeDate='20230723', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29900.9', self.close='29892.8'
2023-07-23 16:10:01,109:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690099799, self.tradeDate='20230723', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29900.9', self.close='29892.8'
127.0.0.1 - - [23/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-23 16:10:01,117:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230723   152000    152959  1690097399  29891.2  29890.1 -0.000037
525  20230723   153000    153959  1690097999  29890.1    29875 -0.000505
526  20230723   154000    154959  1690098599    29875  29875.9  0.000030
527  20230723   155000    155959  1690099199  29875.9  29900.9  0.000837
528  20230723   160000    160959  1690099799  29900.9  29892.8 -0.000271
2023-07-23 16:10:01,124:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10113 

self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29892.8', self.close='29876.2'
127.0.0.1 - - [23/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-23 16:20:05,994:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29892.8', self.close='29876.2'
2023-07-23 16:20:06,345:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230723   153000    153959  1690097999  29890.1    29875 -0.000505
526  20230723   154000    154959  1690098599    29875  29875.9  0.000030
527  20230723   155000    155959  1690099199  29875.9  29900.9  0.000837
528  20230723   160000    160959  1690099799  29900.9  29892.8 -0.000271
529  20230723   161000    161959  1690100399  29892.8  29876.2 -0.000555
2023-07-23 16:20:06,346:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230723   155000    155959  1690099199  29875.9  29900.9
2023-07-23 16:00:02,311:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10115 

self.closeSec=1690099799, self.tradeDate='20230723', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29900.9', self.close='29892.8'
2023-07-23 16:10:01,100:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690099799, self.tradeDate='20230723', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29900.9', self.close='29892.8'
127.0.0.1 - - [23/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-23 16:10:01,115:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230723   152000    152959  1690097399  29891.2  29890.1
17517  20230723   153000    153959  1690097999  29890.1    29875
17518  20230723   154000    154959  1690098599    29875  29875.9
17519  20230723   155000    155959  1690099199  29875.9  29900.9
17520  20230723   160000    160959  1690099799  29900.9  29892.8
2023-07-23 16:10:01,115:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10116 

self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29892.8', self.close='29876.2'
127.0.0.1 - - [23/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-23 16:20:06,986:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29892.8', self.close='29876.2'
2023-07-23 16:20:07,201:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230723   153000    153959  1690097999  29890.1    29875
17518  20230723   154000    154959  1690098599    29875  29875.9
17519  20230723   155000    155959  1690099199  29875.9  29900.9
17520  20230723   160000    160959  1690099799  29900.9  29892.8
17521  20230723   161000    161959  1690100399  29892.8  29876.2
2023-07-23 16:20:07,202:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230723   155000    155959  1690099199  29875.9  29900.9
2023-07-23 16:00:02,304:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10115 

self.closeSec=1690099799, self.tradeDate='20230723', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29900.9', self.close='29892.8'
2023-07-23 16:10:01,100:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690099799, self.tradeDate='20230723', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29900.9', self.close='29892.8'
127.0.0.1 - - [23/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-23 16:10:01,109:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230723   152000    152959  1690097399  29891.2  29890.1
12189  20230723   153000    153959  1690097999  29890.1    29875
12190  20230723   154000    154959  1690098599    29875  29875.9
12191  20230723   155000    155959  1690099199  29875.9  29900.9
12192  20230723   160000    160959  1690099799  29900.9  29892.8
2023-07-23 16:10:01,109:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10116 

self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29892.8', self.close='29876.2'
127.0.0.1 - - [23/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-23 16:20:06,858:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29892.8', self.close='29876.2'
2023-07-23 16:20:07,096:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230723   153000    153959  1690097999  29890.1    29875
12190  20230723   154000    154959  1690098599    29875  29875.9
12191  20230723   155000    155959  1690099199  29875.9  29900.9
12192  20230723   160000    160959  1690099799  29900.9  29892.8
12193  20230723   161000    161959  1690100399  29892.8  29876.2
2023-07-23 16:20:07,097:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20224
self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29880.1, self.close=29876.2, self.high=29880.2, self.low=29871.6, self.vol=256.226, self.amt=7654856.1505 
127.0.0.1 - - [23/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-23 16:20:05,415:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230723   155500    155959  ...         0.0        0.0       0
5952  20230723   160000    160459  ...         0.0        0.0       0
5953  20230723   160500    160959  ...         0.0        0.0       0
5954  20230723   161000    161459  ...         0.0        0.0       0
5955  20230723   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 16:20:05,426:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690100399, self.tradeDate='20230723', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29880.1, self.close=29876.2, self.high=29880.2, self.low=29871.6, self.vol=256.226, self.amt=7654856.1505, ukdf['pct'].iloc[-1]=-0.000131 , ukdf['amount'].iloc[-1]=7654856.1505, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '112622.6543', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29876.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20225
self.closeSec=1690100699, self.tradeDate='20230723', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29876.2, self.close=29883.6, self.high=29883.6, self.low=29876.2, self.vol=224.545, self.amt=6709227.1308 
127.0.0.1 - - [23/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-23 16:25:00,777:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230723   160000    160459  ...         0.0        0.0       0
5953  20230723   160500    160959  ...         0.0        0.0       0
5954  20230723   161000    161459  ...         0.0        0.0       0
5955  20230723   161500    161959  ...         0.0        0.0       0
5956  20230723   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 16:25:00,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690100699, self.tradeDate='20230723', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29876.2, self.close=29883.6, self.high=29883.6, self.low=29876.2, self.vol=224.545, self.amt=6709227.1308, ukdf['pct'].iloc[-1]=0.000248 , ukdf['amount'].iloc[-1]=6709227.1308, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '112893.7836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29883.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230723   040000    075959  1690070399  ...    721  0.164716 -0.808995    -1.0
722  20230723   080000    115959  1690084799  ...    722  0.156991 -0.823997    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '1737.4608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29837.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=421
self.closeSec=1690099199, self.tradeDate='20230723', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29832.5, self.close=29900.9, self.high=29974.6, self.low=29832.5, self.vol=34347.504, self.amt=1027395719.09404 
127.0.0.1 - - [23/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-23 16:00:01,880:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690099199, self.tradeDate='20230723', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29832.5, self.close=29900.9, self.high=29974.6, self.low=29832.5, self.vol=34347.504, self.amt=1027395719.09404 
2023-07-23 16:00:01,894:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230722   200000    235959  ...  24285.778  7.249418e+08  0.000328
720  20230723   000000    035959  ...  17262.524  5.149351e+08 -0.002118
721  20230723   040000    075959  ...  33991.832  1.010297e+09 -0.001244
722  20230723   080000    115959  ...  29826.520  8.891474e+08  0.001645
723  20230723   120000    155959  ...  34347.504  1.027396e+09  0.002293

[5 rows x 11 columns]
2023-07-23 16:00:02,644:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230722   200000    235959  1690041599  ...    719  0.072097 -1.233408    -1.0
720  20230723   000000    035959  1690055999  ...    720  0.074972 -1.193808    -1.0
721  20230723   040000    075959  1690070399  ...    721  0.164716 -0.808995    -1.0
722  20230723   080000    115959  1690084799  ...    722  0.156991 -0.823997    -1.0
723  20230723   120000    155959  1690099199  ...    723  0.148149 -0.843344    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-1712.76148406688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29903.42661538', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


