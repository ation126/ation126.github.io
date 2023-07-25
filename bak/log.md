# 20230725 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20800
self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29113.9, self.close=29113.8, self.high=29126.0, self.low=29113.7, self.vol=306.915, self.amt=8937320.0426 
127.0.0.1 - - [25/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-25 16:20:05,298:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230725   155500    155959  ...         0.0        0.0       0
5952  20230725   160000    160459  ...         0.0        0.0       0
5953  20230725   160500    160959  ...         0.0        0.0       0
5954  20230725   161000    161459  ...         0.0        0.0       0
5955  20230725   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 16:20:05,309:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29113.9, self.close=29113.8, self.high=29126.0, self.low=29113.7, self.vol=306.915, self.amt=8937320.0426, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=8937320.0426, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31333.83595834404', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29114.92412454', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20801
self.closeSec=1690273499, self.tradeDate='20230725', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29113.8, self.close=29129.7, self.high=29129.8, self.low=29113.7, self.vol=272.332, self.amt=7931228.2791 
2023-07-25 16:25:00,730:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230725   160000    160459  ...         0.0        0.0       0
5953  20230725   160500    160959  ...         0.0        0.0       0
5954  20230725   161000    161459  ...         0.0        0.0       0
5955  20230725   161500    161959  ...         0.0        0.0       0
5956  20230725   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 16:25:00,731:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690273499, self.tradeDate='20230725', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29113.8, self.close=29129.7, self.high=29129.8, self.low=29113.7, self.vol=272.332, self.amt=7931228.2791, ukdf['pct'].iloc[-1]=0.000546 , ukdf['amount'].iloc[-1]=7931228.2791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31540.9974', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29129.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29113.9, self.close=29113.8, self.high=29126.0, self.low=29113.7 
127.0.0.1 - - [25/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-25 16:20:03,768:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29113.9, self.close=29113.8, self.high=29126.0, self.low=29113.7   
2023-07-25 16:20:04,789:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230725   155500    155959  1690271999  ...  29126.3 -0.000196   1631    5
1632  20230725   160000    160459  1690272299  ...  29132.2  0.000474   1632    0
1633  20230725   160500    160959  1690272599  ...  29121.3 -0.000714   1633    1
1634  20230725   161000    161459  1690272899  ...  29111.7 -0.000395   1634    2
1635  20230725   161500    161959  1690273199  ...  29113.7  0.000000   1635    3

[5 rows x 11 columns]
2023-07-25 16:20:04,798:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--: 127.0.0.1 - - [25/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7375690801313779, self.count=20803 

self.closeSec=1690273499, self.tradeDate='20230725', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29113.8, self.close=29129.7, self.high=29129.8, self.low=29113.7 
2023-07-25 16:25:00,726:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690273499, self.tradeDate='20230725', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29113.8, self.close=29129.7, self.high=29129.8, self.low=29113.7   
2023-07-25 16:25:00,740:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230725   160000    160459  1690272299  ...  29132.2  0.000474   1632    0
1633  20230725   160500    160959  1690272599  ...  29121.3 -0.000714   1633    1
1634  20230725   161000    161459  1690272899  ...  29111.7 -0.000395   1634    2
1635  20230725   161500    161959  1690273199  ...  29113.7  0.000000   1635    3
1636  20230725   162000    162459  1690273499  ...  29113.7  0.000546   1636    4

[5 rows x 11 columns]
2023-07-25 16:25:00,740:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-25 16:00:17,784:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230725    132959  29080.0  ...  50.833333  0.396163  0.739595
5787  20230725    135959  29097.3  ...  50.833333  0.400633  0.722549
5788  20230725    142959  29110.7  ...  50.833333  0.408954  0.702505
5789  20230725    145959  29135.3  ...  50.833333  0.408132  0.681519
5790  20230725    152959  29131.8  ...  50.833333  0.413736  0.657630

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-07-25 16:00:17,847:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.487533  0.512467       1  ...  0.961700  -1.0    0.0  0.926146
538     1  0.490785  0.509215       1  ...  0.960888  -1.0    0.0  0.926928
539     1  0.495728  0.504272       0  ...  0.961003  -1.0    0.0  0.926817
540     1  0.493070  0.506930       1  ...  0.960465  -1.0    0.0  0.927335
541     0  0.500350  0.499650       0  ...  0.960986  -1.0    0.0  0.926833

[5 rows x 10 columns]
2023-07-25 16:00:17,859:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487823  0.512177       1  ...  0.949599  -1.0    0.0  0.930301
46     1  0.490974  0.509026       1  ...  0.948797  -1.0    0.0  0.929104
47     1  0.495582  0.504418       0  ...  0.961003  -1.0    0.0  0.926534
48     1  0.493498  0.506502       1  ...  0.960465  -1.0    0.0  0.928523
49     0  0.500350  0.499650       0  ...  0.960986  -1.0    0.0  0.926833

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.403', 'enterprice': '29752', 'countrevence': '0', 'unrealprofit': '14353.0599', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29138.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230725   155000    155959  1690271999  29117.9  29132.3  0.000498
2023-07-25 16:00:02,117:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10400 

self.closeSec=1690272599, self.tradeDate='20230725', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29132.3', self.close='29125.3'
2023-07-25 16:10:01,100:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690272599, self.tradeDate='20230725', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29132.3', self.close='29125.3'
127.0.0.1 - - [25/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-25 16:10:01,113:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230725   152000    152959  1690270199    29125  29148.1  0.000793
525  20230725   153000    153959  1690270799  29148.2  29139.2 -0.000305
526  20230725   154000    154959  1690271399  29139.2  29117.8 -0.000734
527  20230725   155000    155959  1690271999  29117.9  29132.3  0.000498
528  20230725   160000    160959  1690272599  29132.3  29125.3 -0.000240
2023-07-25 16:10:01,117:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10401 

self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29125.3', self.close='29113.8'
127.0.0.1 - - [25/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-25 16:20:05,828:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29125.3', self.close='29113.8'
2023-07-25 16:20:06,258:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230725   153000    153959  1690270799  29148.2  29139.2 -0.000305
526  20230725   154000    154959  1690271399  29139.2  29117.8 -0.000734
527  20230725   155000    155959  1690271999  29117.9  29132.3  0.000498
528  20230725   160000    160959  1690272599  29132.3  29125.3 -0.000240
529  20230725   161000    161959  1690273199  29125.3  29113.8 -0.000395
2023-07-25 16:20:06,259:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230725   155000    155959  1690271999  29117.9  29132.3
2023-07-25 16:00:02,127:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10403 

self.closeSec=1690272599, self.tradeDate='20230725', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29132.3', self.close='29125.3'
2023-07-25 16:10:01,102:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690272599, self.tradeDate='20230725', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29132.3', self.close='29125.3'
2023-07-25 16:10:01,109:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230725   152000    152959  1690270199    29125  29148.1
17517  20230725   153000    153959  1690270799  29148.2  29139.2
17518  20230725   154000    154959  1690271399  29139.2  29117.8
17519  20230725   155000    155959  1690271999  29117.9  29132.3
17520  20230725   160000    160959  1690272599  29132.3  29125.3
2023-07-25 16:10:01,109:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10404 

self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29125.3', self.close='29113.8'
127.0.0.1 - - [25/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-25 16:20:06,930:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29125.3', self.close='29113.8'
2023-07-25 16:20:07,025:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230725   153000    153959  1690270799  29148.2  29139.2
17518  20230725   154000    154959  1690271399  29139.2  29117.8
17519  20230725   155000    155959  1690271999  29117.9  29132.3
17520  20230725   160000    160959  1690272599  29132.3  29125.3
17521  20230725   161000    161959  1690273199  29125.3  29113.8
2023-07-25 16:20:07,027:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230725   155000    155959  1690271999  29117.9  29132.3
2023-07-25 16:00:02,109:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10403 

self.closeSec=1690272599, self.tradeDate='20230725', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29132.3', self.close='29125.3'
2023-07-25 16:10:01,109:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690272599, self.tradeDate='20230725', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29132.3', self.close='29125.3'
2023-07-25 16:10:01,119:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230725   152000    152959  1690270199    29125  29148.1
12189  20230725   153000    153959  1690270799  29148.2  29139.2
12190  20230725   154000    154959  1690271399  29139.2  29117.8
12191  20230725   155000    155959  1690271999  29117.9  29132.3
12192  20230725   160000    160959  1690272599  29132.3  29125.3
2023-07-25 16:10:01,119:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10404 

self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29125.3', self.close='29113.8'
127.0.0.1 - - [25/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-25 16:20:06,780:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29125.3', self.close='29113.8'
2023-07-25 16:20:06,948:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230725   153000    153959  1690270799  29148.2  29139.2
12190  20230725   154000    154959  1690271399  29139.2  29117.8
12191  20230725   155000    155959  1690271999  29117.9  29132.3
12192  20230725   160000    160959  1690272599  29132.3  29125.3
12193  20230725   161000    161959  1690273199  29125.3  29113.8
2023-07-25 16:20:06,950:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20800
self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29113.9, self.close=29113.8, self.high=29126.0, self.low=29113.7, self.vol=306.915, self.amt=8937320.0426 
127.0.0.1 - - [25/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-25 16:20:05,348:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230725   155500    155959  ...         0.0        0.0       0
5952  20230725   160000    160459  ...         0.0        0.0       0
5953  20230725   160500    160959  ...         0.0        0.0       0
5954  20230725   161000    161459  ...         0.0        0.0       0
5955  20230725   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 16:20:05,358:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690273199, self.tradeDate='20230725', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29113.9, self.close=29113.8, self.high=29126.0, self.low=29113.7, self.vol=306.915, self.amt=8937320.0426, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=8937320.0426, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '84344.39290954014', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29114.92412454', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20801
self.closeSec=1690273499, self.tradeDate='20230725', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29113.8, self.close=29129.7, self.high=29129.8, self.low=29113.7, self.vol=272.332, self.amt=7931228.2791 
2023-07-25 16:25:00,751:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230725   160000    160459  ...         0.0        0.0       0
5953  20230725   160500    160959  ...         0.0        0.0       0
5954  20230725   161000    161459  ...         0.0        0.0       0
5955  20230725   161500    161959  ...         0.0        0.0       0
5956  20230725   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 16:25:00,752:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690273499, self.tradeDate='20230725', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29113.8, self.close=29129.7, self.high=29129.8, self.low=29113.7, self.vol=272.332, self.amt=7931228.2791, ukdf['pct'].iloc[-1]=0.000546 , ukdf['amount'].iloc[-1]=7931228.2791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '84896.8978', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29129.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230725   040000    075959  1690243199  ...    721  0.339939  0.031975     NaN
722  20230725   080000    115959  1690257599  ...    722  0.416269  0.327084     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '40107.6912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29101.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [25/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=433
self.closeSec=1690271999, self.tradeDate='20230725', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29099.6, self.close=29132.3, self.high=29155.4, self.low=29060.0, self.vol=17709.951, self.amt=515599793.3398 
2023-07-25 16:00:01,695:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690271999, self.tradeDate='20230725', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29099.6, self.close=29132.3, self.high=29155.4, self.low=29060.0, self.vol=17709.951, self.amt=515599793.3398 
2023-07-25 16:00:01,710:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230724   200000    235959  ...  124594.368  3.623508e+09 -0.005967
720  20230725   000000    035959  ...   41486.808  1.206293e+09  0.000753
721  20230725   040000    075959  ...   18811.829  5.482895e+08  0.001955
722  20230725   080000    115959  ...   27479.779  7.997241e+08 -0.002201
723  20230725   120000    155959  ...   17709.951  5.155998e+08  0.001124

[5 rows x 11 columns]
2023-07-25 16:00:02,618:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230724   200000    235959  1690214399  ...    719  0.093340 -0.933171    -1.0
720  20230725   000000    035959  1690228799  ...    720  0.246148 -0.333214     NaN
721  20230725   040000    075959  1690243199  ...    721  0.339939  0.031975     NaN
722  20230725   080000    115959  1690257599  ...    722  0.416269  0.327084     NaN
723  20230725   120000    155959  1690271999  ...    723  0.479340  0.567308     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '38521.5408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29132.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


