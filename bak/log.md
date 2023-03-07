# 20230307 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28828
self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22390.1, self.close=22409.2, self.high=22414.3, self.low=22388.6, self.vol=628.08, self.amt=14070628.2882 
127.0.0.1 - - [07/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-07 16:20:01,563:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230307   155500    155959  ...         0.0        0.0       0
5952  20230307   160000    160459  ...         0.0        0.0       0
5953  20230307   160500    160959  ...         0.0        0.0       0
5954  20230307   161000    161459  ...         0.0        0.0       0
5955  20230307   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 16:20:01,563:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22390.1, self.close=22409.2, self.high=22414.3, self.low=22388.6, self.vol=628.08, self.amt=14070628.2882, ukdf['pct'].iloc[-1]=0.000853 , ukdf['amount'].iloc[-1]=14070628.2882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-353822.8448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22409.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28829
self.closeSec=1678177499, self.tradeDate='20230307', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22409.2, self.close=22407.1, self.high=22409.2, self.low=22400.2, self.vol=340.818, self.amt=7636126.2892 
127.0.0.1 - - [07/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-07 16:25:01,551:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230307   160000    160459  ...         0.0        0.0       0
5953  20230307   160500    160959  ...         0.0        0.0       0
5954  20230307   161000    161459  ...         0.0        0.0       0
5955  20230307   161500    161959  ...         0.0        0.0       0
5956  20230307   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 16:25:01,551:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678177499, self.tradeDate='20230307', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22409.2, self.close=22407.1, self.high=22409.2, self.low=22400.2, self.vol=340.818, self.amt=7636126.2892, ukdf['pct'].iloc[-1]=-9.4e-05 , ukdf['amount'].iloc[-1]=7636126.2892, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-353720.5456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22407.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=100, self.factor=0.5481252841056281, self.count=29394 

self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22390.1, self.close=22409.2, self.high=22414.3, self.low=22388.6 
2023-03-07 16:20:01,494:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22390.1, self.close=22409.2, self.high=22414.3, self.low=22388.6   
2023-03-07 16:20:01,529:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230307   155500    155959  1678175999  ...  22403.1 -0.000174   1631    5
1632  20230307   160000    160459  1678176299  ...  22401.6 -0.000308   1632    0
1633  20230307   160500    160959  1678176599  ...  22384.2 -0.000594   1633    1
1634  20230307   161000    161459  1678176899  ...  22384.0  0.000080   1634    2
1635  20230307   161500    161959  1678177199  ...  22388.6  0.000853   1635    3

[5 rows x 11 columns]
2023-03-07 16:20:01,529:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=100, self.factor=0.5481252841056281, self.count=29395 

self.closeSec=1678177499, self.tradeDate='20230307', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22409.2, self.close=22407.1, self.high=22409.2, self.low=22400.2 
2023-03-07 16:25:01,501:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678177499, self.tradeDate='20230307', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22409.2, self.close=22407.1, self.high=22409.2, self.low=22400.2   
127.0.0.1 - - [07/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-07 16:25:01,525:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230307   160000    160459  1678176299  ...  22401.6 -0.000308   1632    0
1633  20230307   160500    160959  1678176599  ...  22384.2 -0.000594   1633    1
1634  20230307   161000    161459  1678176899  ...  22384.0  0.000080   1634    2
1635  20230307   161500    161959  1678177199  ...  22388.6  0.000853   1635    3
1636  20230307   162000    162459  1678177499  ...  22400.2 -0.000094   1636    4

[5 rows x 11 columns]
2023-03-07 16:25:01,531:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-07 16:00:33,403:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230307    132959  22463.5  ...  46.666667  0.510650  0.505476
5787  20230307    135959  22453.6  ...  46.666667  0.508512  0.505715
5788  20230307    142959  22448.5  ...  46.250000  0.499632  0.510777
5789  20230307    145959  22427.9  ...  46.250000  0.498948  0.515874
5790  20230307    152959  22426.1  ...  46.250000  0.493776  0.523423

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-03-07 16:00:33,571:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494105  0.505895       0  ...  0.929540  -1.0    0.0  0.937460
538     0  0.500813  0.499187       0  ...  0.930401  -1.0    0.0  0.936591
539     1  0.492749  0.507251       0  ...  0.930468  -1.0    0.0  0.936524
540     1  0.499386  0.500614       0  ...  0.930965  -1.0    0.0  0.936023
541     1  0.492365  0.507635       0  ...  0.931202  -1.0    0.0  0.935785

[5 rows x 10 columns]
2023-03-07 16:00:33,597:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495185  0.504815       0  ...  0.929540  -1.0    0.0  0.941107
46     0  0.501632  0.498368       0  ...  0.930401  -1.0    0.0  0.939467
47     1  0.493232  0.506768       0  ...  0.930468  -1.0    0.0  0.937209
48     1  0.499734  0.500266       0  ...  0.930965  -1.0    0.0  0.936461
49     1  0.492365  0.507635       0  ...  0.931202  -1.0    0.0  0.935785

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.561', 'enterprice': '22386.6', 'countrevence': '0', 'unrealprofit': '-653.3127', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22407.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230307   155000    155959  1678175999  22408.6  22408.5 -0.000004
2023-03-07 16:00:02,341:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--: 127.0.0.1 - - [07/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14696 

self.closeSec=1678176599, self.tradeDate='20230307', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22408.5', self.close='22388.3'
2023-03-07 16:10:01,720:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678176599, self.tradeDate='20230307', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22408.5', self.close='22388.3'
2023-03-07 16:10:01,742:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230307   152000    152959  1678174199  22434.1  22414.2 -0.000887
525  20230307   153000    153959  1678174799  22414.1  22422.9  0.000388
526  20230307   154000    154959  1678175399    22423  22408.6 -0.000638
527  20230307   155000    155959  1678175999  22408.6  22408.5 -0.000004
528  20230307   160000    160959  1678176599  22408.5  22388.3 -0.000901
2023-03-07 16:10:01,742:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14697 

self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22388.3', self.close='22409.2'
2023-03-07 16:20:01,618:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22388.3', self.close='22409.2'
2023-03-07 16:20:01,651:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230307   153000    153959  1678174799  22414.1  22422.9  0.000388
526  20230307   154000    154959  1678175399    22423  22408.6 -0.000638
527  20230307   155000    155959  1678175999  22408.6  22408.5 -0.000004
528  20230307   160000    160959  1678176599  22408.5  22388.3 -0.000901
529  20230307   161000    161959  1678177199  22388.3  22409.2  0.000934
2023-03-07 16:20:01,651:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230307   155000    155959  1678175999  22408.6  22408.5
2023-03-07 16:00:02,388:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14697 

self.closeSec=1678176599, self.tradeDate='20230307', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22408.5', self.close='22388.3'
2023-03-07 16:10:01,737:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678176599, self.tradeDate='20230307', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22408.5', self.close='22388.3'
127.0.0.1 - - [07/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-07 16:10:01,758:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230307   152000    152959  1678174199  22434.1  22414.2
17517  20230307   153000    153959  1678174799  22414.1  22422.9
17518  20230307   154000    154959  1678175399    22423  22408.6
17519  20230307   155000    155959  1678175999  22408.6  22408.5
17520  20230307   160000    160959  1678176599  22408.5  22388.3
2023-03-07 16:10:01,758:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14698 

self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22388.3', self.close='22409.2'
2023-03-07 16:20:01,632:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22388.3', self.close='22409.2'
2023-03-07 16:20:01,665:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230307   153000    153959  1678174799  22414.1  22422.9
17518  20230307   154000    154959  1678175399    22423  22408.6
17519  20230307   155000    155959  1678175999  22408.6  22408.5
17520  20230307   160000    160959  1678176599  22408.5  22388.3
17521  20230307   161000    161959  1678177199  22388.3  22409.2
2023-03-07 16:20:01,666:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230307   155000    155959  1678175999  22408.6  22408.5
2023-03-07 16:00:02,349:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14697 

self.closeSec=1678176599, self.tradeDate='20230307', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22408.5', self.close='22388.3'
2023-03-07 16:10:01,748:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678176599, self.tradeDate='20230307', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22408.5', self.close='22388.3'
2023-03-07 16:10:01,788:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230307   152000    152959  1678174199  22434.1  22414.2
12189  20230307   153000    153959  1678174799  22414.1  22422.9
12190  20230307   154000    154959  1678175399    22423  22408.6
12191  20230307   155000    155959  1678175999  22408.6  22408.5
12192  20230307   160000    160959  1678176599  22408.5  22388.3
2023-03-07 16:10:01,789:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14698 

self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22388.3', self.close='22409.2'
2023-03-07 16:20:01,627:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22388.3', self.close='22409.2'
2023-03-07 16:20:01,661:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230307   153000    153959  1678174799  22414.1  22422.9
12190  20230307   154000    154959  1678175399    22423  22408.6
12191  20230307   155000    155959  1678175999  22408.6  22408.5
12192  20230307   160000    160959  1678176599  22408.5  22388.3
12193  20230307   161000    161959  1678177199  22388.3  22409.2
2023-03-07 16:20:01,674:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24826
self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22390.1, self.close=22409.2, self.high=22414.3, self.low=22388.6, self.vol=628.08, self.amt=14070628.2882 
127.0.0.1 - - [07/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-07 16:20:01,554:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230307   155500    155959  ...         0.0        0.0       0
5952  20230307   160000    160459  ...         0.0        0.0       0
5953  20230307   160500    160959  ...         0.0        0.0       0
5954  20230307   161000    161459  ...         0.0        0.0       0
5955  20230307   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 16:20:01,557:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678177199, self.tradeDate='20230307', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22390.1, self.close=22409.2, self.high=22414.3, self.low=22388.6, self.vol=628.08, self.amt=14070628.2882, ukdf['pct'].iloc[-1]=0.000853 , ukdf['amount'].iloc[-1]=14070628.2882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [07/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24827
self.closeSec=1678177499, self.tradeDate='20230307', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22409.2, self.close=22407.1, self.high=22409.2, self.low=22400.2, self.vol=340.818, self.amt=7636126.2892 
2023-03-07 16:25:01,554:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230307   160000    160459  ...         0.0        0.0       0
5953  20230307   160500    160959  ...         0.0        0.0       0
5954  20230307   161000    161459  ...         0.0        0.0       0
5955  20230307   161500    161959  ...         0.0        0.0       0
5956  20230307   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 16:25:01,558:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678177499, self.tradeDate='20230307', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22409.2, self.close=22407.1, self.high=22409.2, self.low=22400.2, self.vol=340.818, self.amt=7636126.2892, ukdf['pct'].iloc[-1]=-9.4e-05 , ukdf['amount'].iloc[-1]=7636126.2892, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230307   040000    075959  1678147199  ...    721  0.054042 -1.859668    -1.0
722  20230307   080000    115959  1678161599  ...    722  0.535163 -0.094572     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '37938.354', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22449.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [07/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=612
self.closeSec=1678175999, self.tradeDate='20230307', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22449.1, self.close=22408.5, self.high=22467.8, self.low=22402.5, self.vol=18027.295, self.amt=404441162.5049 
2023-03-07 16:00:02,196:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678175999, self.tradeDate='20230307', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22449.1, self.close=22408.5, self.high=22467.8, self.low=22402.5, self.vol=18027.295, self.amt=404441162.5049 
2023-03-07 16:00:02,256:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230306   200000    235959  ...  69925.596  1.570430e+09  0.007765
720  20230307   000000    035959  ...  72720.927  1.633468e+09 -0.007133
721  20230307   040000    075959  ...  34143.090  7.641526e+08  0.000639
722  20230307   080000    115959  ...  38691.872  8.689790e+08  0.002322
723  20230307   120000    155959  ...  18027.295  4.044412e+08 -0.001809

[5 rows x 11 columns]
2023-03-07 16:00:04,839:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230306   200000    235959  1678118399  ...    719  0.290726 -1.003096    -1.0
720  20230307   000000    035959  1678132799  ...    720  0.192246 -1.361699    -1.0
721  20230307   040000    075959  1678147199  ...    721  0.054042 -1.859668    -1.0
722  20230307   080000    115959  1678161599  ...    722  0.535163 -0.094572     NaN
723  20230307   120000    155959  1678175999  ...    723  0.003245 -2.049317    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '39686.9565', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22408.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


