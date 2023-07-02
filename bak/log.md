# 20230702 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14176
self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30524.7, self.close=30543.1, self.high=30553.9, self.low=30522.0, self.vol=860.75, self.amt=26287241.8636 
127.0.0.1 - - [02/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-02 16:20:07,618:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230702   155500    155959  ...         0.0        0.0       0
5952  20230702   160000    160459  ...         0.0        0.0       0
5953  20230702   160500    160959  ...         0.0        0.0       0
5954  20230702   161000    161459  ...         0.0        0.0       0
5955  20230702   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 16:20:07,648:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30524.7, self.close=30543.1, self.high=30553.9, self.low=30522.0, self.vol=860.75, self.amt=26287241.8636, ukdf['pct'].iloc[-1]=0.000603 , ukdf['amount'].iloc[-1]=26287241.8636, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51255.78728034138', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30545.48216863', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14177
self.closeSec=1688286299, self.tradeDate='20230702', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30543.1, self.close=30528.6, self.high=30543.1, self.low=30516.7, self.vol=467.267, self.amt=14264934.6346 
127.0.0.1 - - [02/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-02 16:25:00,868:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230702   160000    160459  ...         0.0        0.0       0
5953  20230702   160500    160959  ...         0.0        0.0       0
5954  20230702   161000    161459  ...         0.0        0.0       0
5955  20230702   161500    161959  ...         0.0        0.0       0
5956  20230702   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 16:25:00,868:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688286299, self.tradeDate='20230702', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30543.1, self.close=30528.6, self.high=30543.1, self.low=30516.7, self.vol=467.267, self.amt=14264934.6346, ukdf['pct'].iloc[-1]=-0.000475 , ukdf['amount'].iloc[-1]=14264934.6346, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51022.0788', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30528.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30524.7, self.close=30543.1, self.high=30553.9, self.low=30522.0 
127.0.0.1 - - [02/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-02 16:20:05,038:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30524.7, self.close=30543.1, self.high=30553.9, self.low=30522.0   
2023-07-02 16:20:06,588:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230702   155500    155959  1688284799  ...  30504.6  0.000000   1631    5
1632  20230702   160000    160459  1688285099  ...  30495.7 -0.000102   1632    0
1633  20230702   160500    160959  1688285399  ...  30493.6  0.000439   1633    1
1634  20230702   161000    161459  1688285699  ...  30515.0  0.000318   1634    2
1635  20230702   161500    161959  1688285999  ...  30522.0  0.000603   1635    3

[5 rows x 11 columns]
2023-07-02 16:20:06,598:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=94, self.factor=0.41130604919247304, self.count=14179 

self.closeSec=1688286299, self.tradeDate='20230702', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30543.1, self.close=30528.6, self.high=30543.1, self.low=30516.7 
2023-07-02 16:25:00,798:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688286299, self.tradeDate='20230702', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30543.1, self.close=30528.6, self.high=30543.1, self.low=30516.7   
2023-07-02 16:25:00,841:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230702   160000    160459  1688285099  ...  30495.7 -0.000102   1632    0
1633  20230702   160500    160959  1688285399  ...  30493.6  0.000439   1633    1
1634  20230702   161000    161459  1688285699  ...  30515.0  0.000318   1634    2
1635  20230702   161500    161959  1688285999  ...  30522.0  0.000603   1635    3
1636  20230702   162000    162459  1688286299  ...  30516.7 -0.000475   1636    4

[5 rows x 11 columns]
2023-07-02 16:25:00,842:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-02 16:00:18,493:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230702    132959  30525.1  ...  51.666667  0.494197  0.385112
5787  20230702    135959  30492.8  ...  51.250000  0.488998  0.411011
5788  20230702    142959  30473.2  ...  51.666667  0.498834  0.427548
5789  20230702    145959  30509.2  ...  51.250000  0.489929  0.459405
5790  20230702    152959  30475.7  ...  51.250000  0.497309  0.481236

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-07-02 16:00:18,571:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.515422  0.484578       0  ...  1.012236   1.0    0.0  1.073004
538     0  0.516225  0.483775       1  ...  1.013438   1.0    0.0  1.074279
539     0  0.527363  0.472637       0  ...  1.012325   1.0    0.0  1.073099
540     0  0.514675  0.485325       1  ...  1.013222   1.0    0.0  1.074050
541     0  0.525161  0.474839       1  ...  1.013285   1.0    0.0  1.074117

[5 rows x 10 columns]
2023-07-02 16:00:18,582:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515735  0.484265       0  ...  1.012236   1.0    0.0  1.080553
46     0  0.516364  0.483636       1  ...  1.013438   1.0    0.0  1.078056
47     0  0.527654  0.472346       0  ...  1.012325   1.0    0.0  1.077241
48     0  0.514794  0.485206       1  ...  1.013222   1.0    0.0  1.077171
49     0  0.525161  0.474839       1  ...  1.013285   1.0    0.0  1.074117

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '-1419.468', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30504.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230702   155000    155959  1688284799  30511.2  30504.7 -0.000210
2023-07-02 16:00:02,041:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [02/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7088 

self.closeSec=1688285399, self.tradeDate='20230702', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30504.7', self.close='30515.1'
2023-07-02 16:10:01,084:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688285399, self.tradeDate='20230702', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30504.7', self.close='30515.1'
2023-07-02 16:10:01,090:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230702   152000    152959  1688282999  30492.7  30502.8  0.000331
525  20230702   153000    153959  1688283599  30502.9    30500 -0.000092
526  20230702   154000    154959  1688284199    30500  30511.1  0.000364
527  20230702   155000    155959  1688284799  30511.2  30504.7 -0.000210
528  20230702   160000    160959  1688285399  30504.7  30515.1  0.000341
2023-07-02 16:10:01,090:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7089 

self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30515', self.close='30543.1'
127.0.0.1 - - [02/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-02 16:20:07,507:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30515', self.close='30543.1'
2023-07-02 16:20:08,308:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230702   153000    153959  1688283599  30502.9    30500 -0.000092
526  20230702   154000    154959  1688284199    30500  30511.1  0.000364
527  20230702   155000    155959  1688284799  30511.2  30504.7 -0.000210
528  20230702   160000    160959  1688285399  30504.7  30515.1  0.000341
529  20230702   161000    161959  1688285999    30515  30543.1  0.000918
2023-07-02 16:20:08,317:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230702   155000    155959  1688284799  30511.2  30504.7
2023-07-02 16:00:02,046:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7091 

self.closeSec=1688285399, self.tradeDate='20230702', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30504.7', self.close='30515.1'
127.0.0.1 - - [02/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-02 16:10:01,098:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688285399, self.tradeDate='20230702', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30504.7', self.close='30515.1'
2023-07-02 16:10:01,104:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230702   152000    152959  1688282999  30492.7  30502.8
17517  20230702   153000    153959  1688283599  30502.9    30500
17518  20230702   154000    154959  1688284199    30500  30511.1
17519  20230702   155000    155959  1688284799  30511.2  30504.7
17520  20230702   160000    160959  1688285399  30504.7  30515.1
2023-07-02 16:10:01,104:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7092 

self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30515', self.close='30543.1'
127.0.0.1 - - [02/Jul/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-07-02 16:20:09,668:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30515', self.close='30543.1'
2023-07-02 16:20:09,822:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230702   153000    153959  1688283599  30502.9    30500
17518  20230702   154000    154959  1688284199    30500  30511.1
17519  20230702   155000    155959  1688284799  30511.2  30504.7
17520  20230702   160000    160959  1688285399  30504.7  30515.1
17521  20230702   161000    161959  1688285999    30515  30543.1
2023-07-02 16:20:09,822:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230702   155000    155959  1688284799  30511.2  30504.7
2023-07-02 16:00:02,046:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [02/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7091 

self.closeSec=1688285399, self.tradeDate='20230702', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30504.7', self.close='30515.1'
2023-07-02 16:10:01,068:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688285399, self.tradeDate='20230702', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30504.7', self.close='30515.1'
2023-07-02 16:10:01,076:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230702   152000    152959  1688282999  30492.7  30502.8
12189  20230702   153000    153959  1688283599  30502.9    30500
12190  20230702   154000    154959  1688284199    30500  30511.1
12191  20230702   155000    155959  1688284799  30511.2  30504.7
12192  20230702   160000    160959  1688285399  30504.7  30515.1
2023-07-02 16:10:01,076:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7092 

self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30515', self.close='30543.1'
127.0.0.1 - - [02/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-02 16:20:09,189:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30515', self.close='30543.1'
2023-07-02 16:20:09,513:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230702   153000    153959  1688283599  30502.9    30500
12190  20230702   154000    154959  1688284199    30500  30511.1
12191  20230702   155000    155959  1688284799  30511.2  30504.7
12192  20230702   160000    160959  1688285399  30504.7  30515.1
12193  20230702   161000    161959  1688285999    30515  30543.1
2023-07-02 16:20:09,514:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14176
self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30524.7, self.close=30543.1, self.high=30553.9, self.low=30522.0, self.vol=860.75, self.amt=26287241.8636 
127.0.0.1 - - [02/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-02 16:20:07,617:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230702   155500    155959  ...         0.0        0.0       0
5952  20230702   160000    160459  ...         0.0        0.0       0
5953  20230702   160500    160959  ...         0.0        0.0       0
5954  20230702   161000    161459  ...         0.0        0.0       0
5955  20230702   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 16:20:07,639:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688285999, self.tradeDate='20230702', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30524.7, self.close=30543.1, self.high=30553.9, self.low=30522.0, self.vol=860.75, self.amt=26287241.8636, ukdf['pct'].iloc[-1]=0.000603 , ukdf['amount'].iloc[-1]=26287241.8636, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '137476.74922508683', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30545.48216863', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14177
self.closeSec=1688286299, self.tradeDate='20230702', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30543.1, self.close=30528.6, self.high=30543.1, self.low=30516.7, self.vol=467.267, self.amt=14264934.6346 
2023-07-02 16:25:00,866:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230702   160000    160459  ...         0.0        0.0       0
5953  20230702   160500    160959  ...         0.0        0.0       0
5954  20230702   161000    161459  ...         0.0        0.0       0
5955  20230702   161500    161959  ...         0.0        0.0       0
5956  20230702   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 16:25:00,867:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688286299, self.tradeDate='20230702', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30543.1, self.close=30528.6, self.high=30543.1, self.low=30516.7, self.vol=467.267, self.amt=14264934.6346, ukdf['pct'].iloc[-1]=-0.000475 , ukdf['amount'].iloc[-1]=14264934.6346, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136853.4427', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30528.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230702   040000    075959  1688255999  ...    721  0.003916 -1.380020    -1.0
722  20230702   080000    115959  1688270399  ...    722  0.003287 -1.355462    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '10888.24431856476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30502.59502293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [02/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=295
self.closeSec=1688284799, self.tradeDate='20230702', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30505.3, self.close=30504.7, self.high=30553.2, self.low=30462.1, self.vol=16551.148, self.amt=504831974.9637 
2023-07-02 16:00:01,604:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688284799, self.tradeDate='20230702', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30505.3, self.close=30504.7, self.high=30553.2, self.low=30462.1, self.vol=16551.148, self.amt=504831974.9637 
2023-07-02 16:00:01,637:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230701   200000    235959  ...  32888.967  1.005598e+09  0.001737
720  20230702   000000    035959  ...  16091.915  4.920571e+08  0.001276
721  20230702   040000    075959  ...   9534.474  2.915149e+08 -0.000879
722  20230702   080000    115959  ...  27111.402  8.282798e+08 -0.002237
723  20230702   120000    155959  ...  16551.148  5.048320e+08 -0.000016

[5 rows x 11 columns]
2023-07-02 16:00:02,894:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230701   200000    235959  1688227199  ...    719  0.008270 -1.421216    -1.0
720  20230702   000000    035959  1688241599  ...    720  0.005554 -1.402073    -1.0
721  20230702   040000    075959  1688255999  ...    721  0.003916 -1.380020    -1.0
722  20230702   080000    115959  1688270399  ...    722  0.003287 -1.355462    -1.0
723  20230702   120000    155959  1688284799  ...    723  0.002523 -1.329504    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '10781.4432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30504.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


