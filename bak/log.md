# 20230315 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  127.0.0.1 - - [15/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31132
self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24894.1, self.close=24885.1, self.high=24937.7, self.low=24865.0, self.vol=1838.845, self.amt=45793119.3856 
2023-03-15 16:20:02,747:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230315   155500    155959  ...         0.0        0.0       0
5952  20230315   160000    160459  ...         0.0        0.0       0
5953  20230315   160500    160959  ...         0.0        0.0       0
5954  20230315   161000    161459  ...         0.0        0.0       0
5955  20230315   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 16:20:02,767:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24894.1, self.close=24885.1, self.high=24937.7, self.low=24865.0, self.vol=1838.845, self.amt=45793119.3856, ukdf['pct'].iloc[-1]=-0.000358 , ukdf['amount'].iloc[-1]=45793119.3856, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-502812.6032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24885', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31133
self.closeSec=1678868699, self.tradeDate='20230315', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24885.0, self.close=24831.1, self.high=24895.7, self.low=24831.0, self.vol=1452.918, self.amt=36126585.0184 
2023-03-15 16:25:01,611:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230315   160000    160459  ...         0.0        0.0       0
5953  20230315   160500    160959  ...         0.0        0.0       0
5954  20230315   161000    161459  ...         0.0        0.0       0
5955  20230315   161500    161959  ...         0.0        0.0       0
5956  20230315   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 16:25:01,614:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678868699, self.tradeDate='20230315', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24885.0, self.close=24831.1, self.high=24895.7, self.low=24831.0, self.vol=1452.918, self.amt=36126585.0184, ukdf['pct'].iloc[-1]=-0.00217 , ukdf['amount'].iloc[-1]=36126585.0184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-499484.8704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24829.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24894.1, self.close=24885.1, self.high=24937.7, self.low=24865.0 
127.0.0.1 - - [15/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-15 16:20:02,636:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24894.1, self.close=24885.1, self.high=24937.7, self.low=24865.0   
2023-03-15 16:20:03,136:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230315   155500    155959  1678867199  ...  24821.6  0.002255   1631    5
1632  20230315   160000    160459  1678867499  ...  24867.0  0.000040   1632    0
1633  20230315   160500    160959  1678867799  ...  24850.5 -0.001008   1633    1
1634  20230315   161000    161459  1678868099  ...  24852.8  0.001050   1634    2
1635  20230315   161500    161959  1678868399  ...  24865.0 -0.000358   1635    3

[5 rows x 11 columns]
2023-03-15 16:20:03,136:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=119, self.factor=0.41930349477879736, self.count=31699 

self.closeSec=1678868699, self.tradeDate='20230315', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24885.0, self.close=24831.1, self.high=24895.7, self.low=24831.0 
127.0.0.1 - - [15/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-15 16:25:01,545:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678868699, self.tradeDate='20230315', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24885.0, self.close=24831.1, self.high=24895.7, self.low=24831.0   
2023-03-15 16:25:01,576:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230315   160000    160459  1678867499  ...  24867.0  0.000040   1632    0
1633  20230315   160500    160959  1678867799  ...  24850.5 -0.001008   1633    1
1634  20230315   161000    161459  1678868099  ...  24852.8  0.001050   1634    2
1635  20230315   161500    161959  1678868399  ...  24865.0 -0.000358   1635    3
1636  20230315   162000    162459  1678868699  ...  24831.0 -0.002170   1636    4

[5 rows x 11 columns]
2023-03-15 16:25:01,576:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-15 16:00:35,733:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230315    132959  24814.9  ...  55.833333  0.562230  0.584018
5787  20230315    135959  24854.4  ...  55.416667  0.550411  0.591670
5788  20230315    142959  24715.6  ...  55.833333  0.554169  0.597382
5789  20230315    145959  24770.2  ...  56.250000  0.555823  0.602087
5790  20230315    152959  24800.0  ...  55.833333  0.555090  0.606697

[5 rows x 33 columns]
0.566420664206642
acc is : 0.566420664206642
2023-03-15 16:00:35,906:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494250  0.505750       0  ...  1.115210  -1.0    0.0  1.105526
538     1  0.441652  0.558348       1  ...  1.112751  -1.0    0.0  1.107964
539     0  0.504632  0.495368       1  ...  1.111682  -1.0    0.0  1.109029
540     1  0.494329  0.505671       0  ...  1.112054  -1.0    0.0  1.108657
541     1  0.481348  0.518652       1  ...  1.107285  -1.0    0.0  1.113412

[5 rows x 10 columns]
2023-03-15 16:00:35,945:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494366  0.505634       0  ...  1.107106  -1.0    0.0  1.107885
46     1  0.442281  0.557719       1  ...  1.112751  -1.0    0.0  1.108519
47     0  0.504532  0.495468       1  ...  1.111682  -1.0    0.0  1.109709
48     1  0.494840  0.505160       0  ...  1.112054  -1.0    0.0  1.108469
49     1  0.481348  0.518652       1  ...  1.107285  -1.0    0.0  1.113412

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.798', 'enterprice': '24755.5', 'countrevence': '0', 'unrealprofit': '-4046.8572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24886.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230315   155000    155959  1678867199  24837.1    24892  0.002210
2023-03-15 16:00:02,391:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [15/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15848 

self.closeSec=1678867799, self.tradeDate='20230315', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24892', self.close='24867.9'
2023-03-15 16:10:01,685:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678867799, self.tradeDate='20230315', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24892', self.close='24867.9'
2023-03-15 16:10:01,723:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230315   152000    152959  1678865399  24779.9  24785.7  0.000238
525  20230315   153000    153959  1678865999  24785.8    24786  0.000012
526  20230315   154000    154959  1678866599    24786  24837.1  0.002062
527  20230315   155000    155959  1678867199  24837.1    24892  0.002210
528  20230315   160000    160959  1678867799    24892  24867.9 -0.000968
2023-03-15 16:10:01,723:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15849 

self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24867.9', self.close='24885.1'
127.0.0.1 - - [15/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-15 16:20:03,656:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24867.9', self.close='24885.1'
2023-03-15 16:20:03,889:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230315   153000    153959  1678865999  24785.8    24786  0.000012
526  20230315   154000    154959  1678866599    24786  24837.1  0.002062
527  20230315   155000    155959  1678867199  24837.1    24892  0.002210
528  20230315   160000    160959  1678867799    24892  24867.9 -0.000968
529  20230315   161000    161959  1678868399  24867.9  24885.1  0.000692
2023-03-15 16:20:03,889:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230315   155000    155959  1678867199  24837.1    24892
2023-03-15 16:00:02,391:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15849 

self.closeSec=1678867799, self.tradeDate='20230315', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24892', self.close='24867.9'
2023-03-15 16:10:01,710:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678867799, self.tradeDate='20230315', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24892', self.close='24867.9'
2023-03-15 16:10:01,733:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230315   152000    152959  1678865399  24779.9  24785.7
17517  20230315   153000    153959  1678865999  24785.8    24786
17518  20230315   154000    154959  1678866599    24786  24837.1
17519  20230315   155000    155959  1678867199  24837.1    24892
17520  20230315   160000    160959  1678867799    24892  24867.9
2023-03-15 16:10:01,733:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15850 

self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24867.9', self.close='24885.1'
127.0.0.1 - - [15/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-15 16:20:04,609:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24867.9', self.close='24885.1'
2023-03-15 16:20:04,703:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230315   153000    153959  1678865999  24785.8    24786
17518  20230315   154000    154959  1678866599    24786  24837.1
17519  20230315   155000    155959  1678867199  24837.1    24892
17520  20230315   160000    160959  1678867799    24892  24867.9
17521  20230315   161000    161959  1678868399  24867.9  24885.1
2023-03-15 16:20:04,703:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230315   155000    155959  1678867199  24837.1    24892
2023-03-15 16:00:02,398:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15849 

self.closeSec=1678867799, self.tradeDate='20230315', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24892', self.close='24867.9'
2023-03-15 16:10:01,704:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678867799, self.tradeDate='20230315', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24892', self.close='24867.9'
127.0.0.1 - - [15/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 16:10:01,730:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230315   152000    152959  1678865399  24779.9  24785.7
12189  20230315   153000    153959  1678865999  24785.8    24786
12190  20230315   154000    154959  1678866599    24786  24837.1
12191  20230315   155000    155959  1678867199  24837.1    24892
12192  20230315   160000    160959  1678867799    24892  24867.9
2023-03-15 16:10:01,730:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15850 

self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24867.9', self.close='24885.1'
127.0.0.1 - - [15/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-15 16:20:04,308:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24867.9', self.close='24885.1'
2023-03-15 16:20:04,436:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230315   153000    153959  1678865999  24785.8    24786
12190  20230315   154000    154959  1678866599    24786  24837.1
12191  20230315   155000    155959  1678867199  24837.1    24892
12192  20230315   160000    160959  1678867799    24892  24867.9
12193  20230315   161000    161959  1678868399  24867.9  24885.1
2023-03-15 16:20:04,436:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27130
self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24894.1, self.close=24885.1, self.high=24937.7, self.low=24865.0, self.vol=1838.845, self.amt=45793119.3856 
2023-03-15 16:20:01,995:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230315   155500    155959  ...         0.0        0.0       0
5952  20230315   160000    160459  ...         0.0        0.0       0
5953  20230315   160500    160959  ...         0.0        0.0       0
5954  20230315   161000    161459  ...         0.0        0.0       0
5955  20230315   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 16:20:01,999:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678868399, self.tradeDate='20230315', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24894.1, self.close=24885.1, self.high=24937.7, self.low=24865.0, self.vol=1838.845, self.amt=45793119.3856, ukdf['pct'].iloc[-1]=-0.000358 , ukdf['amount'].iloc[-1]=45793119.3856, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27131
self.closeSec=1678868699, self.tradeDate='20230315', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24885.0, self.close=24831.1, self.high=24895.7, self.low=24831.0, self.vol=1452.918, self.amt=36126585.0184 
2023-03-15 16:25:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230315   160000    160459  ...         0.0        0.0       0
5953  20230315   160500    160959  ...         0.0        0.0       0
5954  20230315   161000    161459  ...         0.0        0.0       0
5955  20230315   161500    161959  ...         0.0        0.0       0
5956  20230315   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 16:25:01,615:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678868699, self.tradeDate='20230315', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24885.0, self.close=24831.1, self.high=24895.7, self.low=24831.0, self.vol=1452.918, self.amt=36126585.0184, ukdf['pct'].iloc[-1]=-0.00217 , ukdf['amount'].iloc[-1]=36126585.0184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230315   040000    075959  1678838399  ...    721  1.246479  2.193121     1.0
722  20230315   080000    115959  1678852799  ...    722  1.218211  2.032856     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '260802.40934210925', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24741.78520989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [15/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=660
self.closeSec=1678867199, self.tradeDate='20230315', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24741.6, self.close=24892.0, self.high=24940.0, self.low=24609.4, self.vol=66779.179, self.amt=1654864713.0552 
2023-03-15 16:00:02,084:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678867199, self.tradeDate='20230315', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24741.6, self.close=24892.0, self.high=24940.0, self.low=24609.4, self.vol=66779.179, self.amt=1654864713.0552 
2023-03-15 16:00:02,150:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230314   200000    235959  ...  572682.237  1.469777e+10  0.047035
720  20230315   000000    035959  ...  344588.234  8.672309e+09 -0.032854
721  20230315   040000    075959  ...  240076.010  5.904620e+09 -0.015064
722  20230315   080000    115959  ...  126773.008  3.138394e+09  0.002394
723  20230315   120000    155959  ...   66779.179  1.654865e+09  0.006079

[5 rows x 11 columns]
2023-03-15 16:00:04,397:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230314   200000    235959  1678809599  ...    719  1.158051  2.045910     1.0
720  20230315   000000    035959  1678823999  ...    720  1.232075  2.223976     1.0
721  20230315   040000    075959  1678838399  ...    721  1.246479  2.193121     1.0
722  20230315   080000    115959  1678852799  ...    722  1.218211  2.032856     1.0
723  20230315   120000    155959  1678867199  ...    723  1.161865  1.800504     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '268914.6075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24887.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


