# 20230310 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29692
self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=19899.7, self.close=19908.2, self.high=19916.5, self.low=19875.3, self.vol=2246.94, self.amt=44698794.2147 
127.0.0.1 - - [10/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-10 16:20:01,868:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230310   155500    155959  ...         0.0        0.0       0
5952  20230310   160000    160459  ...         0.0        0.0       0
5953  20230310   160500    160959  ...         0.0        0.0       0
5954  20230310   161000    161459  ...         0.0        0.0       0
5955  20230310   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 16:20:01,870:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=19899.7, self.close=19908.2, self.high=19916.5, self.low=19875.3, self.vol=2246.94, self.amt=44698794.2147, ukdf['pct'].iloc[-1]=0.000427 , ukdf['amount'].iloc[-1]=44698794.2147, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-203328.6864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19908.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29693
self.closeSec=1678436699, self.tradeDate='20230310', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=19908.2, self.close=19904.2, self.high=19920.2, self.low=19893.1, self.vol=1619.984, self.amt=32251709.6436 
127.0.0.1 - - [10/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-10 16:25:01,563:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230310   160000    160459  ...         0.0        0.0       0
5953  20230310   160500    160959  ...         0.0        0.0       0
5954  20230310   161000    161459  ...         0.0        0.0       0
5955  20230310   161500    161959  ...         0.0        0.0       0
5956  20230310   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 16:25:01,564:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678436699, self.tradeDate='20230310', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=19908.2, self.close=19904.2, self.high=19920.2, self.low=19893.1, self.vol=1619.984, self.amt=32251709.6436, ukdf['pct'].iloc[-1]=-0.000201 , ukdf['amount'].iloc[-1]=32251709.6436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-203218.91766203856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19906.37587181', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8435370787482521, self.count=30258 

self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=19899.7, self.close=19908.2, self.high=19916.5, self.low=19875.3 
2023-03-10 16:20:01,658:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=19899.7, self.close=19908.2, self.high=19916.5, self.low=19875.3   
2023-03-10 16:20:01,759:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230310   155500    155959  1678435199  ...  19938.2  0.000130   1631    5
1632  20230310   160000    160459  1678435499  ...  19900.4 -0.001755   1632    0
1633  20230310   160500    160959  1678435799  ...  19900.2  0.000889   1633    1
1634  20230310   161000    161459  1678436099  ...  19891.0 -0.001300   1634    2
1635  20230310   161500    161959  1678436399  ...  19875.3  0.000427   1635    3

[5 rows x 11 columns]
2023-03-10 16:20:01,760:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [10/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8435370787482521, self.count=30259 

self.closeSec=1678436699, self.tradeDate='20230310', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=19908.2, self.close=19904.2, self.high=19920.2, self.low=19893.1 
2023-03-10 16:25:01,482:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678436699, self.tradeDate='20230310', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=19908.2, self.close=19904.2, self.high=19920.2, self.low=19893.1   
2023-03-10 16:25:01,506:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230310   160000    160459  1678435499  ...  19900.4 -0.001755   1632    0
1633  20230310   160500    160959  1678435799  ...  19900.2  0.000889   1633    1
1634  20230310   161000    161459  1678436099  ...  19891.0 -0.001300   1634    2
1635  20230310   161500    161959  1678436399  ...  19875.3  0.000427   1635    3
1636  20230310   162000    162459  1678436699  ...  19893.1 -0.000201   1636    4

[5 rows x 11 columns]
2023-03-10 16:25:01,506:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-10 16:00:35,715:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230310    132959  19865.8  ...  42.083333  0.291117  0.859041
5787  20230310    135959  19942.7  ...  42.500000  0.298891  0.861154
5788  20230310    142959  19978.4  ...  42.500000  0.295427  0.864326
5789  20230310    145959  19941.0  ...  42.083333  0.288682  0.869659
5790  20230310    152959  19867.4  ...  42.500000  0.303262  0.872506

[5 rows x 33 columns]
0.5553505535055351
acc is : 0.5553505535055351
2023-03-10 16:00:35,859:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.560443  0.439557       1  ...  0.924857   1.0    0.0  0.850781
538     0  0.537847  0.462153       0  ...  0.923130   1.0    0.0  0.849193
539     0  0.503006  0.496994       0  ...  0.919718   1.0    0.0  0.846054
540     1  0.490286  0.509714       1  ...  0.922783   1.0    0.0  0.848873
541     0  0.581939  0.418061       1  ...  0.923218   1.0    0.0  0.849274

[5 rows x 10 columns]
2023-03-10 16:00:35,882:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.560311  0.439689       1  ...  0.924857   1.0    0.0  0.851256
46     0  0.537644  0.462356       0  ...  0.923130   1.0    0.0  0.848091
47     0  0.503354  0.496646       0  ...  0.919718   1.0    0.0  0.843790
48     1  0.490851  0.509149       1  ...  0.922783   1.0    0.0  0.849709
49     0  0.581939  0.418061       1  ...  0.923218   1.0    0.0  0.849274

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.939', 'enterprice': '20043.6', 'countrevence': '0', 'unrealprofit': '-3168.9673', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19952.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230310   155000    155959  1678435199    19947  19942.9 -0.000301
2023-03-10 16:00:02,235:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15128 

self.closeSec=1678435799, self.tradeDate='20230310', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='19943', self.close='19925.6'
2023-03-10 16:10:01,613:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678435799, self.tradeDate='20230310', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='19943', self.close='19925.6'
127.0.0.1 - - [10/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-10 16:10:01,680:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230310   152000    152959  1678433399  19848.2  19933.5  0.004303
525  20230310   153000    153959  1678433999  19933.5    20001  0.003386
526  20230310   154000    154959  1678434599    20001  19948.9 -0.002605
527  20230310   155000    155959  1678435199    19947  19942.9 -0.000301
528  20230310   160000    160959  1678435799    19943  19925.6 -0.000867
2023-03-10 16:10:01,680:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--: 127.0.0.1 - - [10/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15129 

self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='19925.5', self.close='19908.2'
2023-03-10 16:20:01,814:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='19925.5', self.close='19908.2'
2023-03-10 16:20:01,845:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230310   153000    153959  1678433999  19933.5    20001  0.003386
526  20230310   154000    154959  1678434599    20001  19948.9 -0.002605
527  20230310   155000    155959  1678435199    19947  19942.9 -0.000301
528  20230310   160000    160959  1678435799    19943  19925.6 -0.000867
529  20230310   161000    161959  1678436399  19925.5  19908.2 -0.000873
2023-03-10 16:20:01,845:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230310   155000    155959  1678435199    19947  19942.9
2023-03-10 16:00:02,303:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15129 

self.closeSec=1678435799, self.tradeDate='20230310', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='19943', self.close='19925.6'
2023-03-10 16:10:01,641:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678435799, self.tradeDate='20230310', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='19943', self.close='19925.6'
2023-03-10 16:10:01,688:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230310   152000    152959  1678433399  19848.2  19933.5
17517  20230310   153000    153959  1678433999  19933.5    20001
17518  20230310   154000    154959  1678434599    20001  19948.9
17519  20230310   155000    155959  1678435199    19947  19942.9
17520  20230310   160000    160959  1678435799    19943  19925.6
2023-03-10 16:10:01,688:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15130 

self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='19925.5', self.close='19908.2'
127.0.0.1 - - [10/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-10 16:20:01,896:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='19925.5', self.close='19908.2'
2023-03-10 16:20:01,917:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230310   153000    153959  1678433999  19933.5    20001
17518  20230310   154000    154959  1678434599    20001  19948.9
17519  20230310   155000    155959  1678435199    19947  19942.9
17520  20230310   160000    160959  1678435799    19943  19925.6
17521  20230310   161000    161959  1678436399  19925.5  19908.2
2023-03-10 16:20:01,917:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230310   155000    155959  1678435199    19947  19942.9
2023-03-10 16:00:02,232:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15129 

self.closeSec=1678435799, self.tradeDate='20230310', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='19943', self.close='19925.6'
2023-03-10 16:10:01,590:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678435799, self.tradeDate='20230310', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='19943', self.close='19925.6'
2023-03-10 16:10:01,614:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230310   152000    152959  1678433399  19848.2  19933.5
12189  20230310   153000    153959  1678433999  19933.5    20001
12190  20230310   154000    154959  1678434599    20001  19948.9
12191  20230310   155000    155959  1678435199    19947  19942.9
12192  20230310   160000    160959  1678435799    19943  19925.6
2023-03-10 16:10:01,614:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15130 

self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='19925.5', self.close='19908.2'
2023-03-10 16:20:01,865:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='19925.5', self.close='19908.2'
2023-03-10 16:20:01,881:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230310   153000    153959  1678433999  19933.5    20001
12190  20230310   154000    154959  1678434599    20001  19948.9
12191  20230310   155000    155959  1678435199    19947  19942.9
12192  20230310   160000    160959  1678435799    19943  19925.6
12193  20230310   161000    161959  1678436399  19925.5  19908.2
2023-03-10 16:20:01,881:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [10/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25690
self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=19899.7, self.close=19908.2, self.high=19916.5, self.low=19875.3, self.vol=2246.94, self.amt=44698794.2147 
2023-03-10 16:20:01,774:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230310   155500    155959  ...         0.0        0.0       0
5952  20230310   160000    160459  ...         0.0        0.0       0
5953  20230310   160500    160959  ...         0.0        0.0       0
5954  20230310   161000    161459  ...         0.0        0.0       0
5955  20230310   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 16:20:01,778:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678436399, self.tradeDate='20230310', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=19899.7, self.close=19908.2, self.high=19916.5, self.low=19875.3, self.vol=2246.94, self.amt=44698794.2147, ukdf['pct'].iloc[-1]=0.000427 , ukdf['amount'].iloc[-1]=44698794.2147, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25691
self.closeSec=1678436699, self.tradeDate='20230310', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=19908.2, self.close=19904.2, self.high=19920.2, self.low=19893.1, self.vol=1619.984, self.amt=32251709.6436 
127.0.0.1 - - [10/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-10 16:25:01,555:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230310   160000    160459  ...         0.0        0.0       0
5953  20230310   160500    160959  ...         0.0        0.0       0
5954  20230310   161000    161459  ...         0.0        0.0       0
5955  20230310   161500    161959  ...         0.0        0.0       0
5956  20230310   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 16:25:01,555:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678436699, self.tradeDate='20230310', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=19908.2, self.close=19904.2, self.high=19920.2, self.low=19893.1, self.vol=1619.984, self.amt=32251709.6436, ukdf['pct'].iloc[-1]=-0.000201 , ukdf['amount'].iloc[-1]=32251709.6436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230310   040000    075959  1678406399  ...    721  0.418595 -0.460593     NaN
722  20230310   080000    115959  1678420799  ...    722  0.518297 -0.112976     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '139472.48493054525', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20040.16626485', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [10/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=630
self.closeSec=1678435199, self.tradeDate='20230310', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=20042.1, self.close=19942.9, self.high=20052.0, self.low=19757.0, self.vol=144189.872, self.amt=2872942659.12235 
2023-03-10 16:00:02,068:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678435199, self.tradeDate='20230310', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=20042.1, self.close=19942.9, self.high=20052.0, self.low=19757.0, self.vol=144189.872, self.amt=2872942659.12235 
2023-03-10 16:00:02,116:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230309   200000    235959  ...  128925.274  2.797151e+09 -0.001246
720  20230310   000000    035959  ...  317671.191  6.733776e+09 -0.036599
721  20230310   040000    075959  ...  336530.824  6.868830e+09 -0.023852
722  20230310   080000    115959  ...  228402.264  4.576687e+09 -0.015048
723  20230310   120000    155959  ...  144189.872  2.872943e+09 -0.004950

[5 rows x 11 columns]
2023-03-10 16:00:04,680:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230309   200000    235959  1678377599  ...    719  0.503191 -0.169857     NaN
720  20230310   000000    035959  1678391999  ...    720  0.347579 -0.711117    -1.0
721  20230310   040000    075959  1678406399  ...    721  0.418595 -0.460593     NaN
722  20230310   080000    115959  1678420799  ...    722  0.518297 -0.112976     NaN
723  20230310   120000    155959  1678435199  ...    723  0.617270  0.229363     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '143441.86619536635', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19945.95999299', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


