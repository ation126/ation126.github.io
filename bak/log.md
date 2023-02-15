# 20230215 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23068
self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22106.8, self.close=22112.7, self.high=22114.4, self.low=22097.8, self.vol=507.419, self.amt=11217163.6209 
2023-02-15 16:20:01,779:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230215   155500    155959  ...         0.0        0.0       0
5952  20230215   160000    160459  ...         0.0        0.0       0
5953  20230215   160500    160959  ...         0.0        0.0       0
5954  20230215   161000    161459  ...         0.0        0.0       0
5955  20230215   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 16:20:01,781:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22106.8, self.close=22112.7, self.high=22114.4, self.low=22097.8, self.vol=507.419, self.amt=11217163.6209, ukdf['pct'].iloc[-1]=0.000267 , ukdf['amount'].iloc[-1]=11217163.6209, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-335992.696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22112.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23069
self.closeSec=1676449499, self.tradeDate='20230215', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22112.8, self.close=22100.0, self.high=22116.4, self.low=22100.0, self.vol=378.442, self.amt=8367767.4283 
127.0.0.1 - - [15/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-15 16:25:01,778:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230215   160000    160459  ...         0.0        0.0       0
5953  20230215   160500    160959  ...         0.0        0.0       0
5954  20230215   161000    161459  ...         0.0        0.0       0
5955  20230215   161500    161959  ...         0.0        0.0       0
5956  20230215   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 16:25:01,782:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676449499, self.tradeDate='20230215', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22112.8, self.close=22100.0, self.high=22116.4, self.low=22100.0, self.vol=378.442, self.amt=8367767.4283, ukdf['pct'].iloc[-1]=-0.000574 , ukdf['amount'].iloc[-1]=8367767.4283, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-335290.16738739168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22101.12543518', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22106.8, self.close=22112.7, self.high=22114.4, self.low=22097.8 
127.0.0.1 - - [15/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-15 16:20:01,673:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22106.8, self.close=22112.7, self.high=22114.4, self.low=22097.8   
2023-02-15 16:20:01,724:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230215   155500    155959  1676447999  ...  22085.1 -0.000276   1631    5
1632  20230215   160000    160459  1676448299  ...  22086.0 -0.000430   1632    0
1633  20230215   160500    160959  1676448599  ...  22084.7  0.000086   1633    1
1634  20230215   161000    161459  1676448899  ...  22083.9  0.000765   1634    2
1635  20230215   161500    161959  1676449199  ...  22097.8  0.000267   1635    3

[5 rows x 11 columns]
2023-02-15 16:20:01,724:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.2825799308935839, self.count=23635 

self.closeSec=1676449499, self.tradeDate='20230215', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22112.8, self.close=22100.0, self.high=22116.4, self.low=22100.0 
2023-02-15 16:25:01,683:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676449499, self.tradeDate='20230215', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22112.8, self.close=22100.0, self.high=22116.4, self.low=22100.0   
2023-02-15 16:25:01,737:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230215   160000    160459  1676448299  ...  22086.0 -0.000430   1632    0
1633  20230215   160500    160959  1676448599  ...  22084.7  0.000086   1633    1
1634  20230215   161000    161459  1676448899  ...  22083.9  0.000765   1634    2
1635  20230215   161500    161959  1676449199  ...  22097.8  0.000267   1635    3
1636  20230215   162000    162459  1676449499  ...  22100.0 -0.000574   1636    4

[5 rows x 11 columns]
2023-02-15 16:25:01,737:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-15 16:00:40,584:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230215    132959  22074.3  ...  47.500000  0.547755  0.241095
5787  20230215    135959  22094.0  ...  47.500000  0.555263  0.240523
5788  20230215    142959  22125.9  ...  47.500000  0.555688  0.239845
5789  20230215    145959  22127.6  ...  47.083333  0.549559  0.240857
5790  20230215    152959  22107.1  ...  47.500000  0.558932  0.238696

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-02-15 16:00:40,760:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.509536  0.490464       1  ...  0.992826   1.0    0.0  0.945378
538     0  0.502619  0.497381       1  ...  0.992907   1.0    0.0  0.945454
539     1  0.498847  0.501153       0  ...  0.991982   1.0    0.0  0.944574
540     1  0.492836  0.507164       1  ...  0.993728   1.0    0.0  0.946236
541     0  0.510394  0.489606       0  ...  0.991552   1.0    0.0  0.944164

[5 rows x 10 columns]
2023-02-15 16:00:40,807:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509539  0.490461       1  ...  0.992826   1.0    0.0  0.944857
46     0  0.502289  0.497711       1  ...  0.992907   1.0    0.0  0.943845
47     1  0.498900  0.501100       0  ...  0.991982   1.0    0.0  0.943752
48     1  0.492482  0.507518       1  ...  0.993728   1.0    0.0  0.944819
49     0  0.510394  0.489606       0  ...  0.991552   1.0    0.0  0.944164

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.557', 'enterprice': '21695.5', 'countrevence': '0', 'unrealprofit': '14699.2638', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22108.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230215   155000    155959  1676447999    22111  22097.5 -0.000611
2023-02-15 16:00:02,993:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11816 

self.closeSec=1676448599, self.tradeDate='20230215', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22097.4', self.close='22089.9'
2023-02-15 16:10:02,054:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676448599, self.tradeDate='20230215', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22097.4', self.close='22089.9'
127.0.0.1 - - [15/Feb/2023 16:10:02] "POST / HTTP/1.1" 200 -
2023-02-15 16:10:02,067:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230215   152000    152959  1676446199  22129.9    22146  0.000728
525  20230215   153000    153959  1676446799  22146.1    22108 -0.001716
526  20230215   154000    154959  1676447399    22108    22111  0.000136
527  20230215   155000    155959  1676447999    22111  22097.5 -0.000611
528  20230215   160000    160959  1676448599  22097.4  22089.9 -0.000344
2023-02-15 16:10:02,067:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [15/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11817 

self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22089.9', self.close='22112.7'
2023-02-15 16:20:01,779:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22089.9', self.close='22112.7'
2023-02-15 16:20:01,841:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230215   153000    153959  1676446799  22146.1    22108 -0.001716
526  20230215   154000    154959  1676447399    22108    22111  0.000136
527  20230215   155000    155959  1676447999    22111  22097.5 -0.000611
528  20230215   160000    160959  1676448599  22097.4  22089.9 -0.000344
529  20230215   161000    161959  1676449199  22089.9  22112.7  0.001032
2023-02-15 16:20:01,842:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [15/Feb/2023 15:00:01] "POST / HTTP/1.1" 200 -
2023-02-15 15:00:02,586:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/15 12:30:00  123000  22074.3  ...     NaN     NaN       0
145  2023/02/15 13:00:00  130000  22094.0  ...     NaN     NaN       0
146  2023/02/15 13:30:00  133000  22125.9  ...     NaN     NaN       0
147  2023/02/15 14:00:00  140000  22127.7  ...     NaN     NaN       0
148  2023/02/15 14:30:00  143000  22107.1  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [15/Feb/2023 15:30:02] "POST / HTTP/1.1" 200 -
2023-02-15 15:30:03,150:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/15 13:00:00  130000  22094.0  ...     NaN     NaN       0
145  2023/02/15 13:30:00  133000  22125.9  ...     NaN     NaN       0
146  2023/02/15 14:00:00  140000  22127.7  ...     NaN     NaN       0
147  2023/02/15 14:30:00  143000  22107.1  ...     NaN     NaN       0
148  2023/02/15 15:00:00  150000  22146.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [15/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-02-15 16:00:03,936:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/15 13:30:00  133000  22125.9  ...     NaN     NaN       0
145  2023/02/15 14:00:00  140000  22127.7  ...     NaN     NaN       0
146  2023/02/15 14:30:00  143000  22107.1  ...     NaN     NaN       0
147  2023/02/15 15:00:00  150000  22146.0  ...     NaN     NaN       0
148  2023/02/15 15:30:00  153000  22097.5  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17519  20230215   155000    155959  1676447999    22111  22097.5
2023-02-15 16:00:03,015:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11817 

self.closeSec=1676448599, self.tradeDate='20230215', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22097.4', self.close='22089.9'
2023-02-15 16:10:02,046:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676448599, self.tradeDate='20230215', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22097.4', self.close='22089.9'
127.0.0.1 - - [15/Feb/2023 16:10:02] "POST / HTTP/1.1" 200 -
2023-02-15 16:10:02,070:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230215   152000    152959  1676446199  22129.9    22146
17517  20230215   153000    153959  1676446799  22146.1    22108
17518  20230215   154000    154959  1676447399    22108    22111
17519  20230215   155000    155959  1676447999    22111  22097.5
17520  20230215   160000    160959  1676448599  22097.4  22089.9
2023-02-15 16:10:02,071:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11818 

self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22089.9', self.close='22112.7'
2023-02-15 16:20:01,814:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22089.9', self.close='22112.7'
2023-02-15 16:20:01,834:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230215   153000    153959  1676446799  22146.1    22108
17518  20230215   154000    154959  1676447399    22108    22111
17519  20230215   155000    155959  1676447999    22111  22097.5
17520  20230215   160000    160959  1676448599  22097.4  22089.9
17521  20230215   161000    161959  1676449199  22089.9  22112.7
2023-02-15 16:20:01,834:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230215   155000    155959  1676447999    22111  22097.5
2023-02-15 16:00:02,984:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Feb/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11817 

self.closeSec=1676448599, self.tradeDate='20230215', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22097.4', self.close='22089.9'
2023-02-15 16:10:02,073:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676448599, self.tradeDate='20230215', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22097.4', self.close='22089.9'
2023-02-15 16:10:02,097:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230215   152000    152959  1676446199  22129.9    22146
12189  20230215   153000    153959  1676446799  22146.1    22108
12190  20230215   154000    154959  1676447399    22108    22111
12191  20230215   155000    155959  1676447999    22111  22097.5
12192  20230215   160000    160959  1676448599  22097.4  22089.9
2023-02-15 16:10:02,097:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11818 

self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22089.9', self.close='22112.7'
2023-02-15 16:20:01,830:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22089.9', self.close='22112.7'
2023-02-15 16:20:01,848:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230215   153000    153959  1676446799  22146.1    22108
12190  20230215   154000    154959  1676447399    22108    22111
12191  20230215   155000    155959  1676447999    22111  22097.5
12192  20230215   160000    160959  1676448599  22097.4  22089.9
12193  20230215   161000    161959  1676449199  22089.9  22112.7
2023-02-15 16:20:01,848:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19066
self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22106.8, self.close=22112.7, self.high=22114.4, self.low=22097.8, self.vol=507.419, self.amt=11217163.6209 
2023-02-15 16:20:01,747:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230215   155500    155959  ...         0.0        0.0       0
5952  20230215   160000    160459  ...         0.0        0.0       0
5953  20230215   160500    160959  ...         0.0        0.0       0
5954  20230215   161000    161459  ...         0.0        0.0       0
5955  20230215   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 16:20:01,747:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676449199, self.tradeDate='20230215', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22106.8, self.close=22112.7, self.high=22114.4, self.low=22097.8, self.vol=507.419, self.amt=11217163.6209, ukdf['pct'].iloc[-1]=0.000267 , ukdf['amount'].iloc[-1]=11217163.6209, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19067
self.closeSec=1676449499, self.tradeDate='20230215', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22112.8, self.close=22100.0, self.high=22116.4, self.low=22100.0, self.vol=378.442, self.amt=8367767.4283 
127.0.0.1 - - [15/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-15 16:25:01,772:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230215   160000    160459  ...         0.0        0.0       0
5953  20230215   160500    160959  ...         0.0        0.0       0
5954  20230215   161000    161459  ...         0.0        0.0       0
5955  20230215   161500    161959  ...         0.0        0.0       0
5956  20230215   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 16:25:01,773:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676449499, self.tradeDate='20230215', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22112.8, self.close=22100.0, self.high=22116.4, self.low=22100.0, self.vol=378.442, self.amt=8367767.4283, ukdf['pct'].iloc[-1]=-0.000574 , ukdf['amount'].iloc[-1]=8367767.4283, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230215   040000    075959  1676419199  ...    721  0.097099 -2.015925    -1.0
722  20230215   080000    115959  1676433599  ...    722  0.141782 -1.779834    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-20943.6753', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22088.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [15/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=925514.8695891, self.flagDict['side']='sell', self.tradeCount=19, self.count=492
self.closeSec=1676447999, self.tradeDate='20230215', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22088.9, self.close=22097.5, self.high=22164.4, self.low=22061.2, self.vol=23896.173, self.amt=528431242.1005 
2023-02-15 16:00:02,865:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676447999, self.tradeDate='20230215', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22088.9, self.close=22097.5, self.high=22164.4, self.low=22061.2, self.vol=23896.173, self.amt=528431242.1005 
2023-02-15 16:00:02,929:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230214   200000    235959  ...  325421.325  7.131807e+09  0.010753
720  20230215   000000    035959  ...  121281.491  2.677237e+09  0.007416
721  20230215   040000    075959  ...   49074.627  1.089328e+09 -0.000419
722  20230215   080000    115959  ...   35580.160  7.867157e+08 -0.004439
723  20230215   120000    155959  ...   23896.173  5.284312e+08  0.000389

[5 rows x 11 columns]
2023-02-15 16:00:05,326:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230214   200000    235959  1676390399  ...    719  0.003743 -2.580120    -1.0
720  20230215   000000    035959  1676404799  ...    720  0.032776 -2.354771    -1.0
721  20230215   040000    075959  1676419199  ...    721  0.097099 -2.015925    -1.0
722  20230215   080000    115959  1676433599  ...    722  0.141782 -1.779834    -1.0
723  20230215   120000    155959  1676447999  ...    723  0.154039 -1.681050    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-21342.5616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22097.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


