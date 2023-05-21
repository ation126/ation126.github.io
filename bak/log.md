# 20230521 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2080
self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27061.0, self.close=27046.1, self.high=27064.0, self.low=27046.1, self.vol=465.957, self.amt=12606500.0381 
127.0.0.1 - - [21/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-21 16:20:04,516:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230521   155500    155959  ...    0.275880   0.325439       0
5952  20230521   160000    160459  ...    0.275743   0.325451       0
5953  20230521   160500    160959  ...    0.275602   0.325460       0
5954  20230521   161000    161459  ...    0.275461   0.325470       0
5955  20230521   161500    161959  ...    0.275321   0.325480       0

[5 rows x 18 columns]
2023-05-21 16:20:04,520:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27061.0, self.close=27046.1, self.high=27064.0, self.low=27046.1, self.vol=465.957, self.amt=12606500.0381, ukdf['pct'].iloc[-1]=-0.000554 , ukdf['amount'].iloc[-1]=12606500.0381, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.2753214135015135, signal=0, value_std=0.325479802925849 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2575.7849013699', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27049.86229365', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2081
self.closeSec=1684657499, self.tradeDate='20230521', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27046.2, self.close=27039.0, self.high=27050.3, self.low=27039.0, self.vol=366.72, self.amt=9917980.2154 
127.0.0.1 - - [21/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-21 16:25:00,448:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230521   160000    160459  ...    0.275743   0.325451       0
5953  20230521   160500    160959  ...    0.275602   0.325460       0
5954  20230521   161000    161459  ...    0.275461   0.325470       0
5955  20230521   161500    161959  ...    0.275321   0.325480       0
5956  20230521   162000    162459  ...    0.275182   0.325490       0

[5 rows x 18 columns]
2023-05-21 16:25:00,449:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684657499, self.tradeDate='20230521', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27046.2, self.close=27039.0, self.high=27050.3, self.low=27039.0, self.vol=366.72, self.amt=9917980.2154, ukdf['pct'].iloc[-1]=-0.000263 , ukdf['amount'].iloc[-1]=9917980.2154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.27518155851250486, signal=0, value_std=0.3254899058267822 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2467.45206060408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27042.08311508', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27061.0, self.close=27046.1, self.high=27064.0, self.low=27046.1 
127.0.0.1 - - [21/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-21 16:20:03,678:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27061.0, self.close=27046.1, self.high=27064.0, self.low=27046.1   
2023-05-21 16:20:04,249:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230521   155500    155959  1684655999  ...  27041.4  0.000015   1631    5
1632  20230521   160000    160459  1684656299  ...  27032.0 -0.000355   1632    0
1633  20230521   160500    160959  1684656599  ...  27015.0 -0.000584   1633    1
1634  20230521   161000    161459  1684656899  ...  27013.4  0.001554   1634    2
1635  20230521   161500    161959  1684657199  ...  27046.1 -0.000554   1635    3

[5 rows x 11 columns]
2023-05-21 16:20:04,258:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [21/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=40, self.factor=0.4147067344691168, self.count=2083 

self.closeSec=1684657499, self.tradeDate='20230521', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27046.2, self.close=27039.0, self.high=27050.3, self.low=27039.0 
2023-05-21 16:25:00,372:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684657499, self.tradeDate='20230521', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27046.2, self.close=27039.0, self.high=27050.3, self.low=27039.0   
2023-05-21 16:25:00,410:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230521   160000    160459  1684656299  ...  27032.0 -0.000355   1632    0
1633  20230521   160500    160959  1684656599  ...  27015.0 -0.000584   1633    1
1634  20230521   161000    161459  1684656899  ...  27013.4  0.001554   1634    2
1635  20230521   161500    161959  1684657199  ...  27046.1 -0.000554   1635    3
1636  20230521   162000    162459  1684657499  ...  27039.0 -0.000263   1636    4

[5 rows x 11 columns]
2023-05-21 16:25:00,410:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-21 16:00:34,302:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230521    132959  27115.4  ...  48.750000  0.541940  0.320547
5787  20230521    135959  27097.8  ...  48.750000  0.537743  0.330305
5788  20230521    142959  27086.7  ...  48.750000  0.534326  0.340791
5789  20230521    145959  27077.9  ...  48.333333  0.531924  0.351536
5790  20230521    152959  27071.8  ...  47.916667  0.523479  0.364938

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-05-21 16:00:34,446:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.484038  0.515962       0  ...  0.890474  -1.0    0.0  0.976594
538     1  0.483710  0.516290       0  ...  0.890766  -1.0    0.0  0.976273
539     1  0.483532  0.516468       0  ...  0.890970  -1.0    0.0  0.976049
540     1  0.484779  0.515221       0  ...  0.891688  -1.0    0.0  0.975263
541     1  0.483829  0.516171       0  ...  0.891866  -1.0    0.0  0.975069

[5 rows x 10 columns]
2023-05-21 16:00:34,470:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483933  0.516067       0  ...  0.890474  -1.0    0.0  0.982688
46     1  0.483565  0.516435       0  ...  0.890766  -1.0    0.0  0.981927
47     1  0.483273  0.516727       0  ...  0.890970  -1.0    0.0  0.980496
48     1  0.484677  0.515323       0  ...  0.891688  -1.0    0.0  0.974624
49     1  0.483829  0.516171       0  ...  0.891866  -1.0    0.0  0.975069

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.758', 'enterprice': '26580.2', 'countrevence': '0', 'unrealprofit': '-12889.83849285542', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27044.56481349', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230521   155000    155959  1684655999  27051.8  27044.5 -0.000266
2023-05-21 16:00:00,482:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1040 

self.closeSec=1684656599, self.tradeDate='20230521', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27044.6', self.close='27019.1'
2023-05-21 16:10:00,370:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684656599, self.tradeDate='20230521', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27044.6', self.close='27019.1'
127.0.0.1 - - [21/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-21 16:10:00,398:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230521   152000    152959  1684654199  27063.9  27049.9 -0.000517
525  20230521   153000    153959  1684654799  27049.8  27058.3  0.000311
526  20230521   154000    154959  1684655399  27058.4  27051.7 -0.000244
527  20230521   155000    155959  1684655999  27051.8  27044.5 -0.000266
528  20230521   160000    160959  1684656599  27044.6  27019.1 -0.000939
2023-05-21 16:10:00,398:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1041 

self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27019', self.close='27046.1'
127.0.0.1 - - [21/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-21 16:20:03,158:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27019', self.close='27046.1'
2023-05-21 16:20:03,537:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230521   153000    153959  1684654799  27049.8  27058.3  0.000311
526  20230521   154000    154959  1684655399  27058.4  27051.7 -0.000244
527  20230521   155000    155959  1684655999  27051.8  27044.5 -0.000266
528  20230521   160000    160959  1684656599  27044.6  27019.1 -0.000939
529  20230521   161000    161959  1684657199    27019  27046.1  0.000999
2023-05-21 16:20:03,538:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230521   155000    155959  1684655999  27051.8  27044.5
2023-05-21 16:00:00,512:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1043 

self.closeSec=1684656599, self.tradeDate='20230521', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27044.6', self.close='27019.1'
2023-05-21 16:10:00,340:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684656599, self.tradeDate='20230521', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27044.6', self.close='27019.1'
127.0.0.1 - - [21/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-21 16:10:00,359:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230521   152000    152959  1684654199  27063.9  27049.9
17517  20230521   153000    153959  1684654799  27049.8  27058.3
17518  20230521   154000    154959  1684655399  27058.4  27051.7
17519  20230521   155000    155959  1684655999  27051.8  27044.5
17520  20230521   160000    160959  1684656599  27044.6  27019.1
2023-05-21 16:10:00,360:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1044 

self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27019', self.close='27046.1'
127.0.0.1 - - [21/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-21 16:20:04,278:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27019', self.close='27046.1'
2023-05-21 16:20:04,400:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230521   153000    153959  1684654799  27049.8  27058.3
17518  20230521   154000    154959  1684655399  27058.4  27051.7
17519  20230521   155000    155959  1684655999  27051.8  27044.5
17520  20230521   160000    160959  1684656599  27044.6  27019.1
17521  20230521   161000    161959  1684657199    27019  27046.1
2023-05-21 16:20:04,400:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230521   155000    155959  1684655999  27051.8  27044.5
2023-05-21 16:00:00,491:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1043 

self.closeSec=1684656599, self.tradeDate='20230521', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27044.6', self.close='27019.1'
2023-05-21 16:10:00,378:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684656599, self.tradeDate='20230521', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27044.6', self.close='27019.1'
127.0.0.1 - - [21/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-21 16:10:00,420:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230521   152000    152959  1684654199  27063.9  27049.9
12189  20230521   153000    153959  1684654799  27049.8  27058.3
12190  20230521   154000    154959  1684655399  27058.4  27051.7
12191  20230521   155000    155959  1684655999  27051.8  27044.5
12192  20230521   160000    160959  1684656599  27044.6  27019.1
2023-05-21 16:10:00,420:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1044 

self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27019', self.close='27046.1'
127.0.0.1 - - [21/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-21 16:20:04,119:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27019', self.close='27046.1'
2023-05-21 16:20:04,288:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230521   153000    153959  1684654799  27049.8  27058.3
12190  20230521   154000    154959  1684655399  27058.4  27051.7
12191  20230521   155000    155959  1684655999  27051.8  27044.5
12192  20230521   160000    160959  1684656599  27044.6  27019.1
12193  20230521   161000    161959  1684657199    27019  27046.1
2023-05-21 16:20:04,288:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2080
self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27061.0, self.close=27046.1, self.high=27064.0, self.low=27046.1, self.vol=465.957, self.amt=12606500.0381 
127.0.0.1 - - [21/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-21 16:20:03,787:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230521   155500    155959  ...    0.012092   0.105412       0
5952  20230521   160000    160459  ...    0.011464   0.101829       0
5953  20230521   160500    160959  ...    0.010837   0.098131       0
5954  20230521   161000    161459  ...    0.010206   0.094223       0
5955  20230521   161500    161959  ...    0.009561   0.089953       0

[5 rows x 18 columns]
2023-05-21 16:20:03,798:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684657199, self.tradeDate='20230521', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27061.0, self.close=27046.1, self.high=27064.0, self.low=27046.1, self.vol=465.957, self.amt=12606500.0381, ukdf['pct'].iloc[-1]=-0.000554 , ukdf['amount'].iloc[-1]=12606500.0381, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.009561043941964109, signal=0, value_std=0.0899532617507425 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '7645.93144845465', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27049.86229365', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [21/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2081
self.closeSec=1684657499, self.tradeDate='20230521', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27046.2, self.close=27039.0, self.high=27050.3, self.low=27039.0, self.vol=366.72, self.amt=9917980.2154 
2023-05-21 16:25:00,443:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230521   160000    160459  ...    0.011464   0.101829       0
5953  20230521   160500    160959  ...    0.010837   0.098131       0
5954  20230521   161000    161459  ...    0.010206   0.094223       0
5955  20230521   161500    161959  ...    0.009561   0.089953       0
5956  20230521   162000    162459  ...    0.008881   0.084949       0

[5 rows x 18 columns]
2023-05-21 16:25:00,450:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684657499, self.tradeDate='20230521', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27046.2, self.close=27039.0, self.high=27050.3, self.low=27039.0, self.vol=366.72, self.amt=9917980.2154, ukdf['pct'].iloc[-1]=-0.000263 , ukdf['amount'].iloc[-1]=9917980.2154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.00888107518906409, signal=0, value_std=0.08494941409389925 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '7357.00497718628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27042.08311508', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230521   040000    075959  1684627199  ...    721  0.171653 -1.446670    -1.0
722  20230521   080000    115959  1684641599  ...    722  0.183294 -1.352832    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '-4943.5491', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27166.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=43
self.closeSec=1684655999, self.tradeDate='20230521', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27166.4, self.close=27044.5, self.high=27166.5, self.low=27031.0, self.vol=23955.74, self.amt=649005543.0958 
2023-05-21 16:00:00,347:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684655999, self.tradeDate='20230521', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27166.4, self.close=27044.5, self.high=27166.5, self.low=27031.0, self.vol=23955.74, self.amt=649005543.0958 
127.0.0.1 - - [21/May/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-05-21 16:00:00,440:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230520   200000    235959  ...  25544.438  6.872793e+08  0.002509
720  20230521   000000    035959  ...  52033.700  1.406918e+09  0.004392
721  20230521   040000    075959  ...  21251.159  5.744749e+08  0.001301
722  20230521   080000    115959  ...  38117.636  1.035943e+09  0.002842
723  20230521   120000    155959  ...  23955.740  6.490055e+08 -0.004491

[5 rows x 11 columns]
2023-05-21 16:00:02,707:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230520   200000    235959  1684598399  ...    719  0.175194 -1.504185    -1.0
720  20230521   000000    035959  1684612799  ...    720  0.175379 -1.464862    -1.0
721  20230521   040000    075959  1684627199  ...    721  0.171653 -1.446670    -1.0
722  20230521   080000    115959  1684641599  ...    722  0.183294 -1.352832    -1.0
723  20230521   120000    155959  1684655999  ...    723  0.173010 -1.372253    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '1325.64192563388', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27044.78384788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


