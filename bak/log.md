# 20230223 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [23/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25372
self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24417.9, self.close=24446.0, self.high=24457.9, self.low=24417.8, self.vol=3345.195, self.amt=81764428.5984 
2023-02-23 16:20:03,354:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230223   155500    155959  ...         0.0        0.0       0
5952  20230223   160000    160459  ...         0.0        0.0       0
5953  20230223   160500    160959  ...         0.0        0.0       0
5954  20230223   161000    161459  ...         0.0        0.0       0
5955  20230223   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 16:20:03,374:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24417.9, self.close=24446.0, self.high=24457.9, self.low=24417.8, self.vol=3345.195, self.amt=81764428.5984, ukdf['pct'].iloc[-1]=0.001221 , ukdf['amount'].iloc[-1]=81764428.5984, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-476569.93506917632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24448.90142032', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25373
self.closeSec=1677140699, self.tradeDate='20230223', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24446.0, self.close=24415.0, self.high=24483.0, self.low=24412.0, self.vol=2664.119, self.amt=65162369.7765 
2023-02-23 16:25:01,544:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230223   160000    160459  ...         0.0        0.0       0
5953  20230223   160500    160959  ...         0.0        0.0       0
5954  20230223   161000    161459  ...         0.0        0.0       0
5955  20230223   161500    161959  ...         0.0        0.0       0
5956  20230223   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 16:25:01,544:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677140699, self.tradeDate='20230223', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24446.0, self.close=24415.0, self.high=24483.0, self.low=24412.0, self.vol=2664.119, self.amt=65162369.7765, ukdf['pct'].iloc[-1]=-0.001268 , ukdf['amount'].iloc[-1]=65162369.7765, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-474697.55008560352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24417.78627502', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=10, self.factor=0.5091741155025021, self.count=25938 

self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24417.9, self.close=24446.0, self.high=24457.9, self.low=24417.8 
2023-02-23 16:20:01,533:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24417.9, self.close=24446.0, self.high=24457.9, self.low=24417.8   
2023-02-23 16:20:01,623:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230223   155500    155959  1677139199  ...  24352.4 -0.000763   1631    5
1632  20230223   160000    160459  1677139499  ...  24360.0 -0.000218   1632    0
1633  20230223   160500    160959  1677139799  ...  24356.2  0.000525   1633    1
1634  20230223   161000    161459  1677140099  ...  24372.8  0.001781   1634    2
1635  20230223   161500    161959  1677140399  ...  24417.8  0.001221   1635    3

[5 rows x 11 columns]
2023-02-23 16:20:01,624:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=10, self.factor=0.5091741155025021, self.count=25939 

self.closeSec=1677140699, self.tradeDate='20230223', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24446.0, self.close=24415.0, self.high=24483.0, self.low=24412.0 
2023-02-23 16:25:01,544:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677140699, self.tradeDate='20230223', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24446.0, self.close=24415.0, self.high=24483.0, self.low=24412.0   
2023-02-23 16:25:01,642:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230223   160000    160459  1677139499  ...  24360.0 -0.000218   1632    0
1633  20230223   160500    160959  1677139799  ...  24356.2  0.000525   1633    1
1634  20230223   161000    161459  1677140099  ...  24372.8  0.001781   1634    2
1635  20230223   161500    161959  1677140399  ...  24417.8  0.001221   1635    3
1636  20230223   162000    162459  1677140699  ...  24412.0 -0.001268   1636    4

[5 rows x 11 columns]
2023-02-23 16:25:01,643:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-23 16:00:33,334:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230223    132959  24510.2  ...  49.166667  0.529875  0.357683
5787  20230223    135959  24449.9  ...  48.750000  0.520082  0.347282
5788  20230223    142959  24383.1  ...  48.333333  0.516056  0.339229
5789  20230223    145959  24357.9  ...  48.750000  0.519011  0.330426
5790  20230223    152959  24377.5  ...  49.166667  0.523376  0.320320

[5 rows x 33 columns]
0.518450184501845
acc is : 0.518450184501845
2023-02-23 16:00:33,455:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.511489  0.488511       0  ...  1.049549   1.0    0.0  1.118229
538     0  0.507878  0.492122       0  ...  1.048465   1.0    0.0  1.117074
539     0  0.519660  0.480340       1  ...  1.049308   1.0    0.0  1.117972
540     0  0.529539  0.470461       1  ...  1.050548   1.0    0.0  1.119293
541     0  0.527278  0.472722       0  ...  1.048783   1.0    0.0  1.117413

[5 rows x 10 columns]
2023-02-23 16:00:33,494:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510678  0.489322       0  ...  1.043287   1.0    0.0  1.117840
46     0  0.507428  0.492572       0  ...  1.042209   1.0    0.0  1.114207
47     0  0.519726  0.480274       1  ...  1.083853   1.0    0.0  1.115614
48     0  0.530064  0.469936       1  ...  1.036679   1.0    0.0  1.117673
49     0  0.527278  0.472722       0  ...  1.048783   1.0    0.0  1.117413

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.835', 'enterprice': '24119', 'countrevence': '0', 'unrealprofit': '8766.6485', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24378.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230223   155000    155959  1677139199  24402.1  24365.3 -0.001512
2023-02-23 16:00:02,219:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12968 

self.closeSec=1677139799, self.tradeDate='20230223', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24365.2', self.close='24372.8'
2023-02-23 16:10:01,622:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677139799, self.tradeDate='20230223', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24365.2', self.close='24372.8'
2023-02-23 16:10:01,663:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230223   152000    152959  1677137399  24403.6  24406.3  0.000111
525  20230223   153000    153959  1677137999  24406.3  24390.6 -0.000643
526  20230223   154000    154959  1677138599  24390.7  24402.2  0.000476
527  20230223   155000    155959  1677139199  24402.1  24365.3 -0.001512
528  20230223   160000    160959  1677139799  24365.2  24372.8  0.000308
2023-02-23 16:10:01,663:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12969 

self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24372.8', self.close='24446'
127.0.0.1 - - [23/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-23 16:20:03,473:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24372.8', self.close='24446'
2023-02-23 16:20:04,073:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230223   153000    153959  1677137999  24406.3  24390.6 -0.000643
526  20230223   154000    154959  1677138599  24390.7  24402.2  0.000476
527  20230223   155000    155959  1677139199  24402.1  24365.3 -0.001512
528  20230223   160000    160959  1677139799  24365.2  24372.8  0.000308
529  20230223   161000    161959  1677140399  24372.8    24446  0.003003
2023-02-23 16:20:04,073:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230223   155000    155959  1677139199  24402.1  24365.3
2023-02-23 16:00:02,241:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12969 

self.closeSec=1677139799, self.tradeDate='20230223', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24365.2', self.close='24372.8'
2023-02-23 16:10:01,644:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677139799, self.tradeDate='20230223', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24365.2', self.close='24372.8'
2023-02-23 16:10:01,673:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230223   152000    152959  1677137399  24403.6  24406.3
17517  20230223   153000    153959  1677137999  24406.3  24390.6
17518  20230223   154000    154959  1677138599  24390.7  24402.2
17519  20230223   155000    155959  1677139199  24402.1  24365.3
17520  20230223   160000    160959  1677139799  24365.2  24372.8
2023-02-23 16:10:01,673:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12970 

self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24372.8', self.close='24446'
127.0.0.1 - - [23/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-23 16:20:04,897:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24372.8', self.close='24446'
2023-02-23 16:20:05,162:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230223   153000    153959  1677137999  24406.3  24390.6
17518  20230223   154000    154959  1677138599  24390.7  24402.2
17519  20230223   155000    155959  1677139199  24402.1  24365.3
17520  20230223   160000    160959  1677139799  24365.2  24372.8
17521  20230223   161000    161959  1677140399  24372.8    24446
2023-02-23 16:20:05,163:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230223   155000    155959  1677139199  24402.1  24365.3
2023-02-23 16:00:02,226:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12969 

self.closeSec=1677139799, self.tradeDate='20230223', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24365.2', self.close='24372.8'
2023-02-23 16:10:01,609:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677139799, self.tradeDate='20230223', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24365.2', self.close='24372.8'
127.0.0.1 - - [23/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-23 16:10:01,624:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230223   152000    152959  1677137399  24403.6  24406.3
12189  20230223   153000    153959  1677137999  24406.3  24390.6
12190  20230223   154000    154959  1677138599  24390.7  24402.2
12191  20230223   155000    155959  1677139199  24402.1  24365.3
12192  20230223   160000    160959  1677139799  24365.2  24372.8
2023-02-23 16:10:01,624:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12970 

self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24372.8', self.close='24446'
127.0.0.1 - - [23/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-23 16:20:04,836:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24372.8', self.close='24446'
2023-02-23 16:20:05,114:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230223   153000    153959  1677137999  24406.3  24390.6
12190  20230223   154000    154959  1677138599  24390.7  24402.2
12191  20230223   155000    155959  1677139199  24402.1  24365.3
12192  20230223   160000    160959  1677139799  24365.2  24372.8
12193  20230223   161000    161959  1677140399  24372.8    24446
2023-02-23 16:20:05,114:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [23/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21370
self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24417.9, self.close=24446.0, self.high=24457.9, self.low=24417.8, self.vol=3345.195, self.amt=81764428.5984 
2023-02-23 16:20:01,607:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230223   155500    155959  ...         0.0        0.0       0
5952  20230223   160000    160459  ...         0.0        0.0       0
5953  20230223   160500    160959  ...         0.0        0.0       0
5954  20230223   161000    161459  ...         0.0        0.0       0
5955  20230223   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 16:20:01,609:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677140399, self.tradeDate='20230223', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24417.9, self.close=24446.0, self.high=24457.9, self.low=24417.8, self.vol=3345.195, self.amt=81764428.5984, ukdf['pct'].iloc[-1]=0.001221 , ukdf['amount'].iloc[-1]=81764428.5984, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21371
self.closeSec=1677140699, self.tradeDate='20230223', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24446.0, self.close=24415.0, self.high=24483.0, self.low=24412.0, self.vol=2664.119, self.amt=65162369.7765 
127.0.0.1 - - [23/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-23 16:25:01,669:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230223   160000    160459  ...         0.0        0.0       0
5953  20230223   160500    160959  ...         0.0        0.0       0
5954  20230223   161000    161459  ...         0.0        0.0       0
5955  20230223   161500    161959  ...         0.0        0.0       0
5956  20230223   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 16:25:01,670:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677140699, self.tradeDate='20230223', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24446.0, self.close=24415.0, self.high=24483.0, self.low=24412.0, self.vol=2664.119, self.amt=65162369.7765, ukdf['pct'].iloc[-1]=-0.001268 , ukdf['amount'].iloc[-1]=65162369.7765, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230223   040000    075959  1677110399  ...    721  0.459757 -0.335653     NaN
722  20230223   080000    115959  1677124799  ...    722  0.487210 -0.270709     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '17827.7385', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24445.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [23/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=540
self.closeSec=1677139199, self.tradeDate='20230223', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24444.3, self.close=24365.3, self.high=24516.0, self.low=24301.1, self.vol=53133.37, self.amt=1296761166.5111 
2023-02-23 16:00:02,072:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677139199, self.tradeDate='20230223', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24444.3, self.close=24365.3, self.high=24516.0, self.low=24301.1, self.vol=53133.37, self.amt=1296761166.5111 
2023-02-23 16:00:02,127:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230222   200000    235959  ...  185020.734  4.423616e+09 -0.018475
720  20230223   000000    035959  ...  157258.798  3.734329e+09  0.003020
721  20230223   040000    075959  ...   82007.956  1.966414e+09  0.016382
722  20230223   080000    115959  ...  105146.844  2.561934e+09  0.011294
723  20230223   120000    155959  ...   53133.370  1.296761e+09 -0.003232

[5 rows x 11 columns]
2023-02-23 16:00:04,340:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230222   200000    235959  1677081599  ...    719  0.330927 -0.651380    -1.0
720  20230223   000000    035959  1677095999  ...    720  0.430758 -0.405187     NaN
721  20230223   040000    075959  1677110399  ...    721  0.459757 -0.335653     NaN
722  20230223   080000    115959  1677124799  ...    722  0.487210 -0.270709     NaN
723  20230223   120000    155959  1677139199  ...    723  0.515010 -0.206087     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '20762.4483264198', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24365.41981828', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


