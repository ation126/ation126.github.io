# 20230306 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [06/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28540
self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22373.7, self.close=22357.1, self.high=22378.1, self.low=22345.3, self.vol=863.074, self.amt=19297460.7678 
2023-03-06 16:20:01,745:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230306   155500    155959  ...         0.0        0.0       0
5952  20230306   160000    160459  ...         0.0        0.0       0
5953  20230306   160500    160959  ...         0.0        0.0       0
5954  20230306   161000    161459  ...         0.0        0.0       0
5955  20230306   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 16:20:01,748:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22373.7, self.close=22357.1, self.high=22378.1, self.low=22345.3, self.vol=863.074, self.amt=19297460.7678, ukdf['pct'].iloc[-1]=-0.000737 , ukdf['amount'].iloc[-1]=19297460.7678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-350687.6752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22357', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28541
self.closeSec=1678091099, self.tradeDate='20230306', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22357.1, self.close=22374.0, self.high=22374.1, self.low=22349.9, self.vol=762.197, self.amt=17043244.9215 
2023-03-06 16:25:01,608:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230306   160000    160459  ...         0.0        0.0       0
5953  20230306   160500    160959  ...         0.0        0.0       0
5954  20230306   161000    161459  ...         0.0        0.0       0
5955  20230306   161500    161959  ...         0.0        0.0       0
5956  20230306   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 16:25:01,609:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678091099, self.tradeDate='20230306', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22357.1, self.close=22374.0, self.high=22374.1, self.low=22349.9, self.vol=762.197, self.amt=17043244.9215, ukdf['pct'].iloc[-1]=0.000756 , ukdf['amount'].iloc[-1]=17043244.9215, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-351710.6672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22374', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=52, self.factor=0.5608379278139617, self.count=29106 

self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22373.7, self.close=22357.1, self.high=22378.1, self.low=22345.3 
2023-03-06 16:20:01,552:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22373.7, self.close=22357.1, self.high=22378.1, self.low=22345.3   
2023-03-06 16:20:01,710:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230306   155500    155959  1678089599  ...  22380.0 -0.000246   1631    5
1632  20230306   160000    160459  1678089899  ...  22380.0 -0.000036   1632    0
1633  20230306   160500    160959  1678090199  ...  22368.0 -0.000241   1633    1
1634  20230306   161000    161459  1678090499  ...  22369.5 -0.000049   1634    2
1635  20230306   161500    161959  1678090799  ...  22345.3 -0.000737   1635    3

[5 rows x 11 columns]
2023-03-06 16:20:01,710:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=52, self.factor=0.5608379278139617, self.count=29107 

self.closeSec=1678091099, self.tradeDate='20230306', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22357.1, self.close=22374.0, self.high=22374.1, self.low=22349.9 
2023-03-06 16:25:01,522:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678091099, self.tradeDate='20230306', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22357.1, self.close=22374.0, self.high=22374.1, self.low=22349.9   
127.0.0.1 - - [06/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-06 16:25:01,593:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230306   160000    160459  1678089899  ...  22380.0 -0.000036   1632    0
1633  20230306   160500    160959  1678090199  ...  22368.0 -0.000241   1633    1
1634  20230306   161000    161459  1678090499  ...  22369.5 -0.000049   1634    2
1635  20230306   161500    161959  1678090799  ...  22345.3 -0.000737   1635    3
1636  20230306   162000    162459  1678091099  ...  22349.9  0.000756   1636    4

[5 rows x 11 columns]
2023-03-06 16:25:01,593:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-06 16:00:34,949:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230306    132959  22333.9  ...  46.250000  0.459989  0.548055
5787  20230306    135959  22328.8  ...  46.250000  0.472545  0.553097
5788  20230306    142959  22358.6  ...  46.250000  0.493669  0.546710
5789  20230306    145959  22411.0  ...  45.833333  0.488677  0.543522
5790  20230306    152959  22397.8  ...  46.250000  0.494648  0.537371

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-03-06 16:00:35,100:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495399  0.504601       1  ...  0.893236  -1.0    0.0  0.927050
538     0  0.511614  0.488386       1  ...  0.891143  -1.0    0.0  0.929223
539     0  0.528247  0.471753       0  ...  0.891663  -1.0    0.0  0.928680
540     0  0.504698  0.495302       1  ...  0.891066  -1.0    0.0  0.929302
541     0  0.524526  0.475474       0  ...  0.892339  -1.0    0.0  0.927975

[5 rows x 10 columns]
2023-03-06 16:00:35,124:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495560  0.504440       1  ...  0.909128  -1.0    0.0  0.928066
46     0  0.511438  0.488562       1  ...  0.903950  -1.0    0.0  0.927120
47     0  0.528320  0.471680       0  ...  0.904531  -1.0    0.0  0.926632
48     0  0.504385  0.495615       1  ...  0.918000  -1.0    0.0  0.927187
49     0  0.524526  0.475474       0  ...  0.892339  -1.0    0.0  0.927975

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.887', 'enterprice': '22396.9', 'countrevence': '0', 'unrealprofit': '312.47136612783', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22387.10066591', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230306   155000    155959  1678089599  22395.6  22380.9 -0.000656
2023-03-06 16:00:02,283:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [06/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14552 

self.closeSec=1678090199, self.tradeDate='20230306', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22380.9', self.close='22374.7'
2023-03-06 16:10:01,879:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678090199, self.tradeDate='20230306', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22380.9', self.close='22374.7'
2023-03-06 16:10:01,897:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230306   152000    152959  1678087799  22410.8  22412.9  0.000089
525  20230306   153000    153959  1678088399  22412.8    22400 -0.000576
526  20230306   154000    154959  1678088999  22400.1  22395.6 -0.000196
527  20230306   155000    155959  1678089599  22395.6  22380.9 -0.000656
528  20230306   160000    160959  1678090199  22380.9  22374.7 -0.000277
2023-03-06 16:10:01,897:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14553 

self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22374.6', self.close='22357.1'
127.0.0.1 - - [06/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-06 16:20:01,653:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22374.6', self.close='22357.1'
2023-03-06 16:20:01,714:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230306   153000    153959  1678088399  22412.8    22400 -0.000576
526  20230306   154000    154959  1678088999  22400.1  22395.6 -0.000196
527  20230306   155000    155959  1678089599  22395.6  22380.9 -0.000656
528  20230306   160000    160959  1678090199  22380.9  22374.7 -0.000277
529  20230306   161000    161959  1678090799  22374.6  22357.1 -0.000787
2023-03-06 16:20:01,714:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230306   155000    155959  1678089599  22395.6  22380.9
2023-03-06 16:00:02,323:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14553 

self.closeSec=1678090199, self.tradeDate='20230306', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22380.9', self.close='22374.7'
2023-03-06 16:10:01,919:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678090199, self.tradeDate='20230306', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22380.9', self.close='22374.7'
2023-03-06 16:10:01,959:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230306   152000    152959  1678087799  22410.8  22412.9
17517  20230306   153000    153959  1678088399  22412.8    22400
17518  20230306   154000    154959  1678088999  22400.1  22395.6
17519  20230306   155000    155959  1678089599  22395.6  22380.9
17520  20230306   160000    160959  1678090199  22380.9  22374.7
2023-03-06 16:10:01,960:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14554 

self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22374.6', self.close='22357.1'
127.0.0.1 - - [06/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-06 16:20:01,705:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22374.6', self.close='22357.1'
2023-03-06 16:20:01,755:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230306   153000    153959  1678088399  22412.8    22400
17518  20230306   154000    154959  1678088999  22400.1  22395.6
17519  20230306   155000    155959  1678089599  22395.6  22380.9
17520  20230306   160000    160959  1678090199  22380.9  22374.7
17521  20230306   161000    161959  1678090799  22374.6  22357.1
2023-03-06 16:20:01,755:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230306   155000    155959  1678089599  22395.6  22380.9
2023-03-06 16:00:02,311:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [06/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14553 

self.closeSec=1678090199, self.tradeDate='20230306', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22380.9', self.close='22374.7'
2023-03-06 16:10:01,912:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678090199, self.tradeDate='20230306', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22380.9', self.close='22374.7'
2023-03-06 16:10:01,947:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230306   152000    152959  1678087799  22410.8  22412.9
12189  20230306   153000    153959  1678088399  22412.8    22400
12190  20230306   154000    154959  1678088999  22400.1  22395.6
12191  20230306   155000    155959  1678089599  22395.6  22380.9
12192  20230306   160000    160959  1678090199  22380.9  22374.7
2023-03-06 16:10:01,953:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14554 

self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22374.6', self.close='22357.1'
127.0.0.1 - - [06/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-06 16:20:01,664:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22374.6', self.close='22357.1'
2023-03-06 16:20:01,725:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230306   153000    153959  1678088399  22412.8    22400
12190  20230306   154000    154959  1678088999  22400.1  22395.6
12191  20230306   155000    155959  1678089599  22395.6  22380.9
12192  20230306   160000    160959  1678090199  22380.9  22374.7
12193  20230306   161000    161959  1678090799  22374.6  22357.1
2023-03-06 16:20:01,726:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [06/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24538
self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22373.7, self.close=22357.1, self.high=22378.1, self.low=22345.3, self.vol=863.074, self.amt=19297460.7678 
2023-03-06 16:20:01,705:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230306   155500    155959  ...         0.0        0.0       0
5952  20230306   160000    160459  ...         0.0        0.0       0
5953  20230306   160500    160959  ...         0.0        0.0       0
5954  20230306   161000    161459  ...         0.0        0.0       0
5955  20230306   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 16:20:01,709:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678090799, self.tradeDate='20230306', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22373.7, self.close=22357.1, self.high=22378.1, self.low=22345.3, self.vol=863.074, self.amt=19297460.7678, ukdf['pct'].iloc[-1]=-0.000737 , ukdf['amount'].iloc[-1]=19297460.7678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24539
self.closeSec=1678091099, self.tradeDate='20230306', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22357.1, self.close=22374.0, self.high=22374.1, self.low=22349.9, self.vol=762.197, self.amt=17043244.9215 
127.0.0.1 - - [06/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-06 16:25:01,540:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230306   160000    160459  ...         0.0        0.0       0
5953  20230306   160500    160959  ...         0.0        0.0       0
5954  20230306   161000    161459  ...         0.0        0.0       0
5955  20230306   161500    161959  ...         0.0        0.0       0
5956  20230306   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 16:25:01,541:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678091099, self.tradeDate='20230306', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22357.1, self.close=22374.0, self.high=22374.1, self.low=22349.9, self.vol=762.197, self.amt=17043244.9215, ukdf['pct'].iloc[-1]=0.000756 , ukdf['amount'].iloc[-1]=17043244.9215, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230306   040000    075959  1678060799  ...    721  0.571982  0.009081     NaN
722  20230306   080000    115959  1678075199  ...    722  0.516390 -0.187218     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '41060.5575', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22375.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [06/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=606
self.closeSec=1678089599, self.tradeDate='20230306', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22378.0, self.close=22380.9, self.high=22429.6, self.low=22306.0, self.vol=27604.231, self.amt=617517920.3415 
2023-03-06 16:00:02,042:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678089599, self.tradeDate='20230306', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22378.0, self.close=22380.9, self.high=22429.6, self.low=22306.0, self.vol=27604.231, self.amt=617517920.3415 
2023-03-06 16:00:02,076:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230305   200000    235959  ...  32096.465  7.199611e+08  0.001979
720  20230306   000000    035959  ...  21185.383  4.748226e+08 -0.001356
721  20230306   040000    075959  ...  53766.640  1.205734e+09  0.001134
722  20230306   080000    115959  ...  65552.847  1.466936e+09 -0.001847
723  20230306   120000    155959  ...  27604.231  6.175179e+08  0.000130

[5 rows x 11 columns]
2023-03-06 16:00:04,410:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230305   200000    235959  1678031999  ...    719  0.664683  0.319818     NaN
720  20230306   000000    035959  1678046399  ...    720  0.625788  0.194302     NaN
721  20230306   040000    075959  1678060799  ...    721  0.571982  0.009081     NaN
722  20230306   080000    115959  1678075199  ...    722  0.516390 -0.187218     NaN
723  20230306   120000    155959  1678089599  ...    723  0.425069 -0.518944     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '40785.2876025765', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22382.3330461', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


