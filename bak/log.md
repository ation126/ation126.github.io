# 20230604 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6112
self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27136.6, self.close=27130.3, self.high=27142.6, self.low=27130.3, self.vol=495.998, self.amt=13458748.9398 
127.0.0.1 - - [04/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-04 16:20:07,144:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230604   155500    155959  ...         0.0        0.0       0
5952  20230604   160000    160459  ...         0.0        0.0       0
5953  20230604   160500    160959  ...         0.0        0.0       0
5954  20230604   161000    161459  ...         0.0        0.0       0
5955  20230604   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 16:20:07,171:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27136.6, self.close=27130.3, self.high=27142.6, self.low=27130.3, self.vol=495.998, self.amt=13458748.9398, ukdf['pct'].iloc[-1]=-0.000236 , ukdf['amount'].iloc[-1]=13458748.9398, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3707.63234794524', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27131.13814074', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6113
self.closeSec=1685867099, self.tradeDate='20230604', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27130.3, self.close=27119.2, self.high=27130.3, self.low=27119.2, self.vol=550.83, self.amt=14940660.9875 
127.0.0.1 - - [04/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-04 16:25:00,858:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230604   160000    160459  ...         0.0        0.0       0
5953  20230604   160500    160959  ...         0.0        0.0       0
5954  20230604   161000    161459  ...         0.0        0.0       0
5955  20230604   161500    161959  ...         0.0        0.0       0
5956  20230604   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 16:25:00,862:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685867099, self.tradeDate='20230604', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27130.3, self.close=27119.2, self.high=27130.3, self.low=27119.2, self.vol=550.83, self.amt=14940660.9875, ukdf['pct'].iloc[-1]=-0.000409 , ukdf['amount'].iloc[-1]=14940660.9875, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3544.87913441904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27119.45113704', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27136.6, self.close=27130.3, self.high=27142.6, self.low=27130.3 
127.0.0.1 - - [04/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-04 16:20:04,432:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27136.6, self.close=27130.3, self.high=27142.6, self.low=27130.3   
2023-06-04 16:20:05,942:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230604   155500    155959  1685865599  ...  27132.2  0.000321   1631    5
1632  20230604   160000    160459  1685865899  ...  27140.9  0.000221   1632    0
1633  20230604   160500    160959  1685866199  ...  27135.9 -0.000214   1633    1
1634  20230604   161000    161459  1685866499  ...  27130.3 -0.000162   1634    2
1635  20230604   161500    161959  1685866799  ...  27130.3 -0.000236   1635    3

[5 rows x 11 columns]
2023-06-04 16:20:05,951:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=51, self.factor=0.5824509165441868, self.count=6115 

self.closeSec=1685867099, self.tradeDate='20230604', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27130.3, self.close=27119.2, self.high=27130.3, self.low=27119.2 
2023-06-04 16:25:00,803:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685867099, self.tradeDate='20230604', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27130.3, self.close=27119.2, self.high=27130.3, self.low=27119.2   
2023-06-04 16:25:00,864:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230604   160000    160459  1685865899  ...  27140.9  0.000221   1632    0
1633  20230604   160500    160959  1685866199  ...  27135.9 -0.000214   1633    1
1634  20230604   161000    161459  1685866499  ...  27130.3 -0.000162   1634    2
1635  20230604   161500    161959  1685866799  ...  27130.3 -0.000236   1635    3
1636  20230604   162000    162459  1685867099  ...  27119.2 -0.000409   1636    4

[5 rows x 11 columns]
2023-06-04 16:25:00,864:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-04 16:00:34,103:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230604    132959  27045.8  ...  47.083333  0.477505  0.628821
5787  20230604    135959  27029.9  ...  47.083333  0.478484  0.633470
5788  20230604    142959  27032.6  ...  47.083333  0.489395  0.633068
5789  20230604    145959  27064.0  ...  47.083333  0.507889  0.624348
5790  20230604    152959  27119.1  ...  47.500000  0.511103  0.614726

[5 rows x 33 columns]
0.518450184501845
acc is : 0.518450184501845
2023-06-04 16:00:34,270:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493768  0.506232       1  ...  1.033188   1.0    0.0  0.995834
538     0  0.500903  0.499097       1  ...  1.034384   1.0    0.0  0.996987
539     0  0.508562  0.491438       1  ...  1.036490   1.0    0.0  0.999016
540     0  0.517309  0.482691       1  ...  1.036864   1.0    0.0  0.999377
541     0  0.511042  0.488958       1  ...  1.037327   1.0    0.0  0.999823

[5 rows x 10 columns]
2023-06-04 16:00:34,306:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493752  0.506248       1  ...  1.033188   1.0    0.0  0.994248
46     0  0.500754  0.499246       1  ...  1.034384   1.0    0.0  0.993601
47     0  0.508503  0.491497       1  ...  1.036490   1.0    0.0  0.996663
48     0  0.517372  0.482628       1  ...  1.036864   1.0    0.0  0.997063
49     0  0.511042  0.488958       1  ...  1.037327   1.0    0.0  0.999823

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '4339.13869822541', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27145.68426667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230604   155000    155959  1685865599  27119.3    27141  0.000804
2023-06-04 16:00:02,257:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3056 

self.closeSec=1685866199, self.tradeDate='20230604', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27141', self.close='27141.1'
2023-06-04 16:10:01,165:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685866199, self.tradeDate='20230604', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27141', self.close='27141.1'
127.0.0.1 - - [04/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-04 16:10:01,173:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230604   152000    152959  1685863799  27137.4  27128.9 -0.000313
525  20230604   153000    153959  1685864399  27128.9  27149.9  0.000774
526  20230604   154000    154959  1685864999    27150  27119.2 -0.001131
527  20230604   155000    155959  1685865599  27119.3    27141  0.000804
528  20230604   160000    160959  1685866199    27141  27141.1  0.000004
2023-06-04 16:10:01,179:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3057 

self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27141.2', self.close='27130.3'
127.0.0.1 - - [04/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-04 16:20:07,222:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27141.2', self.close='27130.3'
2023-06-04 16:20:08,072:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230604   153000    153959  1685864399  27128.9  27149.9  0.000774
526  20230604   154000    154959  1685864999    27150  27119.2 -0.001131
527  20230604   155000    155959  1685865599  27119.3    27141  0.000804
528  20230604   160000    160959  1685866199    27141  27141.1  0.000004
529  20230604   161000    161959  1685866799  27141.2  27130.3 -0.000398
2023-06-04 16:20:08,073:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230604   155000    155959  1685865599  27119.3    27141
2023-06-04 16:00:02,233:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3059 

self.closeSec=1685866199, self.tradeDate='20230604', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27141', self.close='27141.1'
127.0.0.1 - - [04/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-04 16:10:01,177:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685866199, self.tradeDate='20230604', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27141', self.close='27141.1'
2023-06-04 16:10:01,194:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230604   152000    152959  1685863799  27137.4  27128.9
17517  20230604   153000    153959  1685864399  27128.9  27149.9
17518  20230604   154000    154959  1685864999    27150  27119.2
17519  20230604   155000    155959  1685865599  27119.3    27141
17520  20230604   160000    160959  1685866199    27141  27141.1
2023-06-04 16:10:01,195:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3060 

self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27141.2', self.close='27130.3'
127.0.0.1 - - [04/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-04 16:20:09,066:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27141.2', self.close='27130.3'
2023-06-04 16:20:09,222:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230604   153000    153959  1685864399  27128.9  27149.9
17518  20230604   154000    154959  1685864999    27150  27119.2
17519  20230604   155000    155959  1685865599  27119.3    27141
17520  20230604   160000    160959  1685866199    27141  27141.1
17521  20230604   161000    161959  1685866799  27141.2  27130.3
2023-06-04 16:20:09,223:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230604   155000    155959  1685865599  27119.3    27141
2023-06-04 16:00:02,247:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3059 

self.closeSec=1685866199, self.tradeDate='20230604', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27141', self.close='27141.1'
2023-06-04 16:10:01,176:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685866199, self.tradeDate='20230604', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27141', self.close='27141.1'
2023-06-04 16:10:01,210:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230604   152000    152959  1685863799  27137.4  27128.9
12189  20230604   153000    153959  1685864399  27128.9  27149.9
12190  20230604   154000    154959  1685864999    27150  27119.2
12191  20230604   155000    155959  1685865599  27119.3    27141
12192  20230604   160000    160959  1685866199    27141  27141.1
2023-06-04 16:10:01,211:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3060 

self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27141.2', self.close='27130.3'
127.0.0.1 - - [04/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-04 16:20:08,733:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27141.2', self.close='27130.3'
2023-06-04 16:20:09,041:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230604   153000    153959  1685864399  27128.9  27149.9
12190  20230604   154000    154959  1685864999    27150  27119.2
12191  20230604   155000    155959  1685865599  27119.3    27141
12192  20230604   160000    160959  1685866199    27141  27141.1
12193  20230604   161000    161959  1685866799  27141.2  27130.3
2023-06-04 16:20:09,042:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6112
self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27136.6, self.close=27130.3, self.high=27142.6, self.low=27130.3, self.vol=495.998, self.amt=13458748.9398 
127.0.0.1 - - [04/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-04 16:20:07,084:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230604   155500    155959  ...         0.0        0.0       0
5952  20230604   160000    160459  ...         0.0        0.0       0
5953  20230604   160500    160959  ...         0.0        0.0       0
5954  20230604   161000    161459  ...         0.0        0.0       0
5955  20230604   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 16:20:07,112:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685866799, self.tradeDate='20230604', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27136.6, self.close=27130.3, self.high=27142.6, self.low=27130.3, self.vol=495.998, self.amt=13458748.9398, ukdf['pct'].iloc[-1]=-0.000236 , ukdf['amount'].iloc[-1]=13458748.9398, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10664.59768522434', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27131.13814074', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [04/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6113
self.closeSec=1685867099, self.tradeDate='20230604', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27130.3, self.close=27119.2, self.high=27130.3, self.low=27119.2, self.vol=550.83, self.amt=14940660.9875 
2023-06-04 16:25:00,904:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230604   160000    160459  ...         0.0        0.0       0
5953  20230604   160500    160959  ...         0.0        0.0       0
5954  20230604   161000    161459  ...         0.0        0.0       0
5955  20230604   161500    161959  ...         0.0        0.0       0
5956  20230604   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 16:25:00,906:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685867099, self.tradeDate='20230604', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27130.3, self.close=27119.2, self.high=27130.3, self.low=27119.2, self.vol=550.83, self.amt=14940660.9875, ukdf['pct'].iloc[-1]=-0.000409 , ukdf['amount'].iloc[-1]=14940660.9875, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10230.53068080264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27119.45113704', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230604   040000    075959  1685836799  ...    721  0.276780 -0.862749    -1.0
722  20230604   080000    115959  1685851199  ...    722  0.160352 -1.213449    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '1544.648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27050.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [04/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=127
self.closeSec=1685865599, self.tradeDate='20230604', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27048.3, self.close=27141.0, self.high=27154.0, self.low=27015.0, self.vol=23617.719, self.amt=639956605.1945 
2023-06-04 16:00:01,771:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685865599, self.tradeDate='20230604', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27048.3, self.close=27141.0, self.high=27154.0, self.low=27015.0, self.vol=23617.719, self.amt=639956605.1945 
2023-06-04 16:00:01,833:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230603   200000    235959  ...  35777.121  9.731898e+08  0.006331
720  20230604   000000    035959  ...  50814.584  1.380421e+09 -0.007614
721  20230604   040000    075959  ...  36463.540  9.851884e+08 -0.001108
722  20230604   080000    115959  ...  25275.090  6.832596e+08 -0.000240
723  20230604   120000    155959  ...  23617.719  6.399566e+08  0.003423

[5 rows x 11 columns]
2023-06-04 16:00:03,912:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230603   200000    235959  1685807999  ...    719  0.472565 -0.261938     NaN
720  20230604   000000    035959  1685822399  ...    720  0.361375 -0.602675    -1.0
721  20230604   040000    075959  1685836799  ...    721  0.276780 -0.862749    -1.0
722  20230604   080000    115959  1685851199  ...    722  0.160352 -1.213449    -1.0
723  20230604   120000    155959  1685865599  ...    723  0.029091 -1.593836    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '-3613.373', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27144.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


