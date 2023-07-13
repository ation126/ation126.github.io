# 20230713 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17344
self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30352.1, self.close=30363.7, self.high=30378.9, self.low=30352.0, self.vol=594.51, self.amt=18054314.3169 
127.0.0.1 - - [13/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-13 16:20:06,962:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230713   155500    155959  ...         0.0        0.0       0
5952  20230713   160000    160459  ...         0.0        0.0       0
5953  20230713   160500    160959  ...         0.0        0.0       0
5954  20230713   161000    161459  ...         0.0        0.0       0
5955  20230713   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 16:20:06,992:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30352.1, self.close=30363.7, self.high=30378.9, self.low=30352.0, self.vol=594.51, self.amt=18054314.3169, ukdf['pct'].iloc[-1]=0.000382 , ukdf['amount'].iloc[-1]=18054314.3169, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48773.75124868488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30367.25180588', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17345
self.closeSec=1689236699, self.tradeDate='20230713', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30363.8, self.close=30380.2, self.high=30382.0, self.low=30363.7, self.vol=340.979, self.amt=10358086.3348 
127.0.0.1 - - [13/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-13 16:25:00,755:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230713   160000    160459  ...         0.0        0.0       0
5953  20230713   160500    160959  ...         0.0        0.0       0
5954  20230713   161000    161459  ...         0.0        0.0       0
5955  20230713   161500    161959  ...         0.0        0.0       0
5956  20230713   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 16:25:00,755:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689236699, self.tradeDate='20230713', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30363.8, self.close=30380.2, self.high=30382.0, self.low=30363.7, self.vol=340.979, self.amt=10358086.3348, ukdf['pct'].iloc[-1]=0.000543 , ukdf['amount'].iloc[-1]=10358086.3348, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48985.18975807182', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30382.43480957', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30352.1, self.close=30363.7, self.high=30378.9, self.low=30352.0 
127.0.0.1 - - [13/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-13 16:20:04,461:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30352.1, self.close=30363.7, self.high=30378.9, self.low=30352.0   
2023-07-13 16:20:05,951:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230713   155500    155959  1689235199  ...  30355.0 -0.000053   1631    5
1632  20230713   160000    160459  1689235499  ...  30341.9 -0.000432   1632    0
1633  20230713   160500    160959  1689235799  ...  30337.6 -0.000138   1633    1
1634  20230713   161000    161459  1689236099  ...  30328.2  0.000475   1634    2
1635  20230713   161500    161959  1689236399  ...  30352.0  0.000382   1635    3

[5 rows x 11 columns]
2023-07-13 16:20:05,961:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6441799526072165, self.count=17347 

self.closeSec=1689236699, self.tradeDate='20230713', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30363.8, self.close=30380.2, self.high=30382.0, self.low=30363.7 
2023-07-13 16:25:00,748:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689236699, self.tradeDate='20230713', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30363.8, self.close=30380.2, self.high=30382.0, self.low=30363.7   
2023-07-13 16:25:00,776:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230713   160000    160459  1689235499  ...  30341.9 -0.000432   1632    0
1633  20230713   160500    160959  1689235799  ...  30337.6 -0.000138   1633    1
1634  20230713   161000    161459  1689236099  ...  30328.2  0.000475   1634    2
1635  20230713   161500    161959  1689236399  ...  30352.0  0.000382   1635    3
1636  20230713   162000    162459  1689236699  ...  30363.7  0.000543   1636    4

[5 rows x 11 columns]
2023-07-13 16:25:00,777:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-13 16:00:18,532:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230713    132959  30284.5  ...  51.666667  0.456535  0.772097
5787  20230713    135959  30303.0  ...  51.666667  0.458061  0.777045
5788  20230713    142959  30308.0  ...  52.083333  0.470888  0.778114
5789  20230713    145959  30350.3  ...  52.500000  0.478275  0.777031
5790  20230713    152959  30375.3  ...  52.500000  0.484670  0.774207

[5 rows x 33 columns]
0.5645756457564576
acc is : 0.5645756457564576
2023-07-13 16:00:18,639:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.511531  0.488469       1  ...  1.002751   1.0    0.0  0.991468
538     0  0.516157  0.483843       1  ...  1.004151   1.0    0.0  0.992852
539     0  0.528761  0.471239       1  ...  1.004971   1.0    0.0  0.993663
540     0  0.525838  0.474162       1  ...  1.005686   1.0    0.0  0.994370
541     0  0.525471  0.474529       0  ...  1.004303   1.0    0.0  0.993003

[5 rows x 10 columns]
2023-07-13 16:00:18,660:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511558  0.488442       1  ...  1.002751   1.0    0.0  0.991459
46     0  0.516487  0.483513       1  ...  1.004151   1.0    0.0  0.992862
47     0  0.528665  0.471335       1  ...  1.001033   1.0    0.0  0.993511
48     0  0.525386  0.474614       1  ...  1.001745   1.0    0.0  0.991855
49     0  0.525471  0.474529       0  ...  1.004303   1.0    0.0  0.993003

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.383', 'enterprice': '30486.7', 'countrevence': '0', 'unrealprofit': '-3208.8028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30355.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230713   155000    155959  1689235199  30361.8  30355.1 -0.000221
2023-07-13 16:00:02,363:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8672 

self.closeSec=1689235799, self.tradeDate='20230713', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30355.1', self.close='30337.7'
2023-07-13 16:10:01,127:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689235799, self.tradeDate='20230713', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30355.1', self.close='30337.7'
2023-07-13 16:10:01,143:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230713   152000    152959  1689233399    30394  30396.8  0.000092
525  20230713   153000    153959  1689233999  30396.9  30371.6 -0.000829
526  20230713   154000    154959  1689234599  30371.7  30361.8 -0.000323
527  20230713   155000    155959  1689235199  30361.8  30355.1 -0.000221
528  20230713   160000    160959  1689235799  30355.1  30337.7 -0.000573
2023-07-13 16:10:01,144:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8673 

self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30337.6', self.close='30363.7'
127.0.0.1 - - [13/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-13 16:20:06,940:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30337.6', self.close='30363.7'
2023-07-13 16:20:07,672:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230713   153000    153959  1689233999  30396.9  30371.6 -0.000829
526  20230713   154000    154959  1689234599  30371.7  30361.8 -0.000323
527  20230713   155000    155959  1689235199  30361.8  30355.1 -0.000221
528  20230713   160000    160959  1689235799  30355.1  30337.7 -0.000573
529  20230713   161000    161959  1689236399  30337.6  30363.7  0.000857
2023-07-13 16:20:07,680:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230713   155000    155959  1689235199  30361.8  30355.1
2023-07-13 16:00:02,393:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8675 

self.closeSec=1689235799, self.tradeDate='20230713', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30355.1', self.close='30337.7'
2023-07-13 16:10:01,136:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689235799, self.tradeDate='20230713', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30355.1', self.close='30337.7'
2023-07-13 16:10:01,153:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230713   152000    152959  1689233399    30394  30396.8
17517  20230713   153000    153959  1689233999  30396.9  30371.6
17518  20230713   154000    154959  1689234599  30371.7  30361.8
17519  20230713   155000    155959  1689235199  30361.8  30355.1
17520  20230713   160000    160959  1689235799  30355.1  30337.7
2023-07-13 16:10:01,158:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8676 

self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30337.6', self.close='30363.7'
127.0.0.1 - - [13/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-13 16:20:08,712:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30337.6', self.close='30363.7'
2023-07-13 16:20:08,930:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230713   153000    153959  1689233999  30396.9  30371.6
17518  20230713   154000    154959  1689234599  30371.7  30361.8
17519  20230713   155000    155959  1689235199  30361.8  30355.1
17520  20230713   160000    160959  1689235799  30355.1  30337.7
17521  20230713   161000    161959  1689236399  30337.6  30363.7
2023-07-13 16:20:08,931:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230713   155000    155959  1689235199  30361.8  30355.1
2023-07-13 16:00:02,413:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [13/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8675 

self.closeSec=1689235799, self.tradeDate='20230713', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30355.1', self.close='30337.7'
2023-07-13 16:10:01,131:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689235799, self.tradeDate='20230713', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30355.1', self.close='30337.7'
2023-07-13 16:10:01,147:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230713   152000    152959  1689233399    30394  30396.8
12189  20230713   153000    153959  1689233999  30396.9  30371.6
12190  20230713   154000    154959  1689234599  30371.7  30361.8
12191  20230713   155000    155959  1689235199  30361.8  30355.1
12192  20230713   160000    160959  1689235799  30355.1  30337.7
2023-07-13 16:10:01,147:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8676 

self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30337.6', self.close='30363.7'
127.0.0.1 - - [13/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-13 16:20:08,425:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30337.6', self.close='30363.7'
2023-07-13 16:20:08,794:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230713   153000    153959  1689233999  30396.9  30371.6
12190  20230713   154000    154959  1689234599  30371.7  30361.8
12191  20230713   155000    155959  1689235199  30361.8  30355.1
12192  20230713   160000    160959  1689235799  30355.1  30337.7
12193  20230713   161000    161959  1689236399  30337.6  30363.7
2023-07-13 16:20:08,795:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17344
self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30352.1, self.close=30363.7, self.high=30378.9, self.low=30352.0, self.vol=594.51, self.amt=18054314.3169 
127.0.0.1 - - [13/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-13 16:20:07,000:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230713   155500    155959  ...         0.0        0.0       0
5952  20230713   160000    160459  ...         0.0        0.0       0
5953  20230713   160500    160959  ...         0.0        0.0       0
5954  20230713   161000    161459  ...         0.0        0.0       0
5955  20230713   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 16:20:07,021:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689236399, self.tradeDate='20230713', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30352.1, self.close=30363.7, self.high=30378.9, self.low=30352.0, self.vol=594.51, self.amt=18054314.3169, ukdf['pct'].iloc[-1]=0.000382 , ukdf['amount'].iloc[-1]=18054314.3169, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '130857.18271273362', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30367.25415882', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17345
self.closeSec=1689236699, self.tradeDate='20230713', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30363.8, self.close=30380.2, self.high=30382.0, self.low=30363.7, self.vol=340.979, self.amt=10358086.3348 
127.0.0.1 - - [13/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-13 16:25:00,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230713   160000    160459  ...         0.0        0.0       0
5953  20230713   160500    160959  ...         0.0        0.0       0
5954  20230713   161000    161459  ...         0.0        0.0       0
5955  20230713   161500    161959  ...         0.0        0.0       0
5956  20230713   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 16:25:00,791:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689236699, self.tradeDate='20230713', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30363.8, self.close=30380.2, self.high=30382.0, self.low=30363.7, self.vol=340.979, self.amt=10358086.3348, ukdf['pct'].iloc[-1]=0.000543 , ukdf['amount'].iloc[-1]=10358086.3348, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '131421.00726223937', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30382.43480957', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230713   040000    075959  1689206399  ...    721  0.367737  0.396680     NaN
722  20230713   080000    115959  1689220799  ...    722  0.333764  0.239931     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-11846.37310468472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30284.33609608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [13/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=361
self.closeSec=1689235199, self.tradeDate='20230713', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30283.6, self.close=30355.0, self.high=30414.0, self.low=30233.0, self.vol=29140.81, self.amt=883681133.6227 
2023-07-13 16:00:01,939:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689235199, self.tradeDate='20230713', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30283.6, self.close=30355.0, self.high=30414.0, self.low=30233.0, self.vol=29140.81, self.amt=883681133.6227 
2023-07-13 16:00:01,976:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230712   200000    235959  ...  198941.331  6.108353e+09 -0.008295
720  20230713   000000    035959  ...   84461.464  2.566969e+09 -0.007932
721  20230713   040000    075959  ...   29246.963  8.867321e+08  0.003330
722  20230713   080000    115959  ...   25819.244  7.831939e+08 -0.002806
723  20230713   120000    155959  ...   29140.810  8.836811e+08  0.002354

[5 rows x 11 columns]
2023-07-13 16:00:03,303:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230712   200000    235959  1689177599  ...    719  0.413594  0.605172     1.0
720  20230713   000000    035959  1689191999  ...    720  0.383637  0.473527     NaN
721  20230713   040000    075959  1689206399  ...    721  0.367737  0.396680     NaN
722  20230713   080000    115959  1689220799  ...    722  0.333764  0.239931     NaN
723  20230713   120000    155959  1689235199  ...    723  0.333767  0.235954     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-8154.8201', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30355', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


