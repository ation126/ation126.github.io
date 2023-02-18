# 20230218 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23932
self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24490.6, self.close=24536.7, self.high=24538.0, self.low=24490.6, self.vol=891.173, self.amt=21852480.5615 
2023-02-18 16:20:01,734:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230218   155500    155959  ...         0.0        0.0       0
5952  20230218   160000    160459  ...         0.0        0.0       0
5953  20230218   160500    160959  ...         0.0        0.0       0
5954  20230218   161000    161459  ...         0.0        0.0       0
5955  20230218   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 16:20:01,737:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24490.6, self.close=24536.7, self.high=24538.0, self.low=24490.6, self.vol=891.173, self.amt=21852480.5615, ukdf['pct'].iloc[-1]=0.001886 , ukdf['amount'].iloc[-1]=21852480.5615, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-481799.22004742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24535.80126375', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23933
self.closeSec=1676708699, self.tradeDate='20230218', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24536.7, self.close=24522.3, self.high=24546.1, self.low=24505.0, self.vol=847.871, self.amt=20793829.3578 
127.0.0.1 - - [18/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-18 16:25:01,782:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230218   160000    160459  ...         0.0        0.0       0
5953  20230218   160500    160959  ...         0.0        0.0       0
5954  20230218   161000    161459  ...         0.0        0.0       0
5955  20230218   161500    161959  ...         0.0        0.0       0
5956  20230218   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 16:25:01,782:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676708699, self.tradeDate='20230218', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24536.7, self.close=24522.3, self.high=24546.1, self.low=24505.0, self.vol=847.871, self.amt=20793829.3578, ukdf['pct'].iloc[-1]=-0.000587 , ukdf['amount'].iloc[-1]=20793829.3578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-480824.7225800008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24519.60714205', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24490.6, self.close=24536.7, self.high=24538.0, self.low=24490.6 
127.0.0.1 - - [18/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 16:20:01,539:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24490.6, self.close=24536.7, self.high=24538.0, self.low=24490.6   
2023-02-18 16:20:01,561:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230218   155500    155959  1676707199  ...  24513.6 -0.000322   1631    5
1632  20230218   160000    160459  1676707499  ...  24502.9  0.001044   1632    0
1633  20230218   160500    160959  1676707799  ...  24463.5 -0.002827   1633    1
1634  20230218   161000    161459  1676708099  ...  24474.4  0.000470   1634    2
1635  20230218   161500    161959  1676708399  ...  24490.6  0.001886   1635    3

[5 rows x 11 columns]
2023-02-18 16:20:01,561:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=167, self.factor=0.40625827975353007, self.count=24499 

self.closeSec=1676708699, self.tradeDate='20230218', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24536.7, self.close=24522.3, self.high=24546.1, self.low=24505.0 
2023-02-18 16:25:01,676:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676708699, self.tradeDate='20230218', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24536.7, self.close=24522.3, self.high=24546.1, self.low=24505.0   
2023-02-18 16:25:01,761:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230218   160000    160459  1676707499  ...  24502.9  0.001044   1632    0
1633  20230218   160500    160959  1676707799  ...  24463.5 -0.002827   1633    1
1634  20230218   161000    161459  1676708099  ...  24474.4  0.000470   1634    2
1635  20230218   161500    161959  1676708399  ...  24490.6  0.001886   1635    3
1636  20230218   162000    162459  1676708699  ...  24505.0 -0.000587   1636    4

[5 rows x 11 columns]
2023-02-18 16:25:01,762:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-18 16:00:34,015:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230218    132959  24632.4  ...  51.250000  0.562729  0.335241
5787  20230218    135959  24623.7  ...  51.666667  0.565538  0.332063
5788  20230218    142959  24649.8  ...  51.666667  0.566573  0.328995
5789  20230218    145959  24659.3  ...  51.666667  0.562359  0.327587
5790  20230218    152959  24630.0  ...  51.250000  0.552583  0.329666

[5 rows x 33 columns]
0.511070110701107
acc is : 0.511070110701107
2023-02-18 16:00:34,166:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.516818  0.483182       1  ...  1.048698   1.0    0.0  1.081630
538     0  0.520183  0.479817       1  ...  1.049102   1.0    0.0  1.082047
539     0  0.511767  0.488233       0  ...  1.047855   1.0    0.0  1.080761
540     0  0.500215  0.499785       0  ...  1.044950   1.0    0.0  1.077764
541     1  0.490022  0.509978       0  ...  1.043295   1.0    0.0  1.076057

[5 rows x 10 columns]
2023-02-18 16:00:34,202:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.516763  0.483237       1  ...  1.048698   1.0    0.0  1.077380
46     0  0.520655  0.479345       1  ...  1.049102   1.0    0.0  1.085500
47     0  0.511893  0.488107       0  ...  1.047855   1.0    0.0  1.082271
48     1  0.499645  0.500355       0  ...  1.044950   1.0    0.0  1.076592
49     1  0.490022  0.509978       0  ...  1.043295   1.0    0.0  1.076057

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.459', 'enterprice': '24163.6', 'countrevence': '0', 'unrealprofit': '12229.14774461707', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24508.48134873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230218   155000    155959  1676707199  24528.9  24522.8 -0.000224
2023-02-18 16:00:02,249:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12248 

self.closeSec=1676707799, self.tradeDate='20230218', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24522.7', self.close='24479'
2023-02-18 16:10:01,651:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676707799, self.tradeDate='20230218', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24522.7', self.close='24479'
127.0.0.1 - - [18/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-18 16:10:01,696:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230218   152000    152959  1676705399  24568.8  24561.7 -0.000289
525  20230218   153000    153959  1676705999  24561.8  24548.7 -0.000529
526  20230218   154000    154959  1676706599  24548.7  24528.3 -0.000831
527  20230218   155000    155959  1676707199  24528.9  24522.8 -0.000224
528  20230218   160000    160959  1676707799  24522.7    24479 -0.001786
2023-02-18 16:10:01,702:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12249 

self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24479', self.close='24536.7'
2023-02-18 16:20:01,659:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24479', self.close='24536.7'
2023-02-18 16:20:01,691:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230218   153000    153959  1676705999  24561.8  24548.7 -0.000529
526  20230218   154000    154959  1676706599  24548.7  24528.3 -0.000831
527  20230218   155000    155959  1676707199  24528.9  24522.8 -0.000224
528  20230218   160000    160959  1676707799  24522.7    24479 -0.001786
529  20230218   161000    161959  1676708399    24479  24536.7  0.002357
2023-02-18 16:20:01,691:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [18/Feb/2023 15:00:02] "POST / HTTP/1.1" 200 -
2023-02-18 15:00:03,203:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/18 12:30:00  123000  24632.4  ...     NaN     NaN       0
145  2023/02/18 13:00:00  130000  24623.7  ...     NaN     NaN       0
146  2023/02/18 13:30:00  133000  24649.8  ...     NaN     NaN       0
147  2023/02/18 14:00:00  140000  24659.3  ...     NaN     NaN       0
148  2023/02/18 14:30:00  143000  24630.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [18/Feb/2023 15:30:01] "POST / HTTP/1.1" 200 -
2023-02-18 15:30:02,963:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/18 13:00:00  130000  24623.7  ...     NaN     NaN       0
145  2023/02/18 13:30:00  133000  24649.8  ...     NaN     NaN       0
146  2023/02/18 14:00:00  140000  24659.3  ...     NaN     NaN       0
147  2023/02/18 14:30:00  143000  24630.0  ...     NaN     NaN       0
148  2023/02/18 15:00:00  150000  24561.7  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [18/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-02-18 16:00:03,430:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/18 13:30:00  133000  24649.8  ...     NaN     NaN       0
145  2023/02/18 14:00:00  140000  24659.3  ...     NaN     NaN       0
146  2023/02/18 14:30:00  143000  24630.0  ...     NaN     NaN       0
147  2023/02/18 15:00:00  150000  24561.7  ...     NaN     NaN       0
148  2023/02/18 15:30:00  153000  24522.8  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17519  20230218   155000    155959  1676707199  24528.9  24522.8
2023-02-18 16:00:02,276:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12249 

self.closeSec=1676707799, self.tradeDate='20230218', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24522.7', self.close='24479'
2023-02-18 16:10:01,622:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676707799, self.tradeDate='20230218', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24522.7', self.close='24479'
2023-02-18 16:10:01,648:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230218   152000    152959  1676705399  24568.8  24561.7
17517  20230218   153000    153959  1676705999  24561.8  24548.7
17518  20230218   154000    154959  1676706599  24548.7  24528.3
17519  20230218   155000    155959  1676707199  24528.9  24522.8
17520  20230218   160000    160959  1676707799  24522.7    24479
2023-02-18 16:10:01,648:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12250 

self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24479', self.close='24536.7'
2023-02-18 16:20:01,678:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24479', self.close='24536.7'
2023-02-18 16:20:01,712:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230218   153000    153959  1676705999  24561.8  24548.7
17518  20230218   154000    154959  1676706599  24548.7  24528.3
17519  20230218   155000    155959  1676707199  24528.9  24522.8
17520  20230218   160000    160959  1676707799  24522.7    24479
17521  20230218   161000    161959  1676708399    24479  24536.7
2023-02-18 16:20:01,712:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230218   155000    155959  1676707199  24528.9  24522.8
2023-02-18 16:00:02,268:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12249 

self.closeSec=1676707799, self.tradeDate='20230218', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24522.7', self.close='24479'
2023-02-18 16:10:01,622:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676707799, self.tradeDate='20230218', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24522.7', self.close='24479'
2023-02-18 16:10:01,695:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230218   152000    152959  1676705399  24568.8  24561.7
12189  20230218   153000    153959  1676705999  24561.8  24548.7
12190  20230218   154000    154959  1676706599  24548.7  24528.3
12191  20230218   155000    155959  1676707199  24528.9  24522.8
12192  20230218   160000    160959  1676707799  24522.7    24479
2023-02-18 16:10:01,698:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12250 

self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24479', self.close='24536.7'
2023-02-18 16:20:01,665:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24479', self.close='24536.7'
2023-02-18 16:20:01,706:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230218   153000    153959  1676705999  24561.8  24548.7
12190  20230218   154000    154959  1676706599  24548.7  24528.3
12191  20230218   155000    155959  1676707199  24528.9  24522.8
12192  20230218   160000    160959  1676707799  24522.7    24479
12193  20230218   161000    161959  1676708399    24479  24536.7
2023-02-18 16:20:01,706:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19930
self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24490.6, self.close=24536.7, self.high=24538.0, self.low=24490.6, self.vol=891.173, self.amt=21852480.5615 
2023-02-18 16:20:01,660:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230218   155500    155959  ...         0.0        0.0       0
5952  20230218   160000    160459  ...         0.0        0.0       0
5953  20230218   160500    160959  ...         0.0        0.0       0
5954  20230218   161000    161459  ...         0.0        0.0       0
5955  20230218   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 16:20:01,661:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676708399, self.tradeDate='20230218', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24490.6, self.close=24536.7, self.high=24538.0, self.low=24490.6, self.vol=891.173, self.amt=21852480.5615, ukdf['pct'].iloc[-1]=0.001886 , ukdf['amount'].iloc[-1]=21852480.5615, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [18/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19931
self.closeSec=1676708699, self.tradeDate='20230218', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24536.7, self.close=24522.3, self.high=24546.1, self.low=24505.0, self.vol=847.871, self.amt=20793829.3578 
2023-02-18 16:25:01,787:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230218   160000    160459  ...         0.0        0.0       0
5953  20230218   160500    160959  ...         0.0        0.0       0
5954  20230218   161000    161459  ...         0.0        0.0       0
5955  20230218   161500    161959  ...         0.0        0.0       0
5956  20230218   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 16:25:01,792:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676708699, self.tradeDate='20230218', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24536.7, self.close=24522.3, self.high=24546.1, self.low=24505.0, self.vol=847.871, self.amt=20793829.3578, ukdf['pct'].iloc[-1]=-0.000587 , ukdf['amount'].iloc[-1]=20793829.3578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230218   040000    075959  1676678399  ...    721  1.199144  1.565452     1.0
722  20230218   080000    115959  1676692799  ...    722  1.148250  1.388875     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '47545.304142849', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24620.1690055', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [18/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=510
self.closeSec=1676707199, self.tradeDate='20230218', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24619.9, self.close=24522.8, self.high=24684.8, self.low=24430.6, self.vol=34345.925, self.amt=844718066.2492 
2023-02-18 16:00:02,091:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676707199, self.tradeDate='20230218', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24619.9, self.close=24522.8, self.high=24684.8, self.low=24430.6, self.vol=34345.925, self.amt=844718066.2492 
2023-02-18 16:00:02,140:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230217   200000    235959  ...  225818.466  5.419494e+09  0.014240
720  20230218   000000    035959  ...  205070.186  4.980683e+09  0.016381
721  20230218   040000    075959  ...  225818.499  5.563054e+09  0.002234
722  20230218   080000    115959  ...   50759.107  1.250384e+09  0.001562
723  20230218   120000    155959  ...   34345.925  8.447181e+08 -0.003944

[5 rows x 11 columns]
2023-02-18 16:00:04,590:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230217   200000    235959  1676649599  ...    719  1.179899  1.580532     1.0
720  20230218   000000    035959  1676663999  ...    720  1.168760  1.513700     1.0
721  20230218   040000    075959  1676678399  ...    721  1.199144  1.565452     1.0
722  20230218   080000    115959  1676692799  ...    722  1.148250  1.388875     1.0
723  20230218   120000    155959  1676707199  ...    723  1.082603  1.179174     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '43985.931', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24522.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


