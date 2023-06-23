# 20230623 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11584
self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29949.7, self.close=29975.0, self.high=29986.7, self.low=29949.7, self.vol=872.337, self.amt=26143828.9571 
127.0.0.1 - - [23/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-23 16:20:07,815:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230623   155500    155959  ...         0.0        0.0       0
5952  20230623   160000    160459  ...         0.0        0.0       0
5953  20230623   160500    160959  ...         0.0        0.0       0
5954  20230623   161000    161459  ...         0.0        0.0       0
5955  20230623   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 16:20:07,854:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29949.7, self.close=29975.0, self.high=29986.7, self.low=29949.7, self.vol=872.337, self.amt=26143828.9571, ukdf['pct'].iloc[-1]=0.000845 , ukdf['amount'].iloc[-1]=26143828.9571, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43408.7346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29982', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11585
self.closeSec=1687508699, self.tradeDate='20230623', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29975.0, self.close=29988.0, self.high=29988.0, self.low=29968.9, self.vol=594.822, self.amt=17832662.7799 
127.0.0.1 - - [23/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-23 16:25:00,803:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230623   160000    160459  ...         0.0        0.0       0
5953  20230623   160500    160959  ...         0.0        0.0       0
5954  20230623   161000    161459  ...         0.0        0.0       0
5955  20230623   161500    161959  ...         0.0        0.0       0
5956  20230623   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 16:25:00,803:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687508699, self.tradeDate='20230623', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29975.0, self.close=29988.0, self.high=29988.0, self.low=29968.9, self.vol=594.822, self.amt=17832662.7799, ukdf['pct'].iloc[-1]=0.000434 , ukdf['amount'].iloc[-1]=17832662.7799, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43492.2906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29988', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29949.7, self.close=29975.0, self.high=29986.7, self.low=29949.7 
127.0.0.1 - - [23/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-23 16:20:05,165:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29949.7, self.close=29975.0, self.high=29986.7, self.low=29949.7   
2023-06-23 16:20:06,764:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230623   155500    155959  1687507199  ...  29910.0 -0.000010   1631    5
1632  20230623   160000    160459  1687507499  ...  29899.9 -0.000368   1632    0
1633  20230623   160500    160959  1687507799  ...  29910.8  0.000334   1633    1
1634  20230623   161000    161459  1687508099  ...  29926.0  0.000792   1634    2
1635  20230623   161500    161959  1687508399  ...  29949.7  0.000845   1635    3

[5 rows x 11 columns]
2023-06-23 16:20:06,774:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=309, self.factor=0.435493810242743, self.count=11587 

self.closeSec=1687508699, self.tradeDate='20230623', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29975.0, self.close=29988.0, self.high=29988.0, self.low=29968.9 
127.0.0.1 - - [23/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-23 16:25:00,767:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687508699, self.tradeDate='20230623', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29975.0, self.close=29988.0, self.high=29988.0, self.low=29968.9   
2023-06-23 16:25:00,790:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230623   160000    160459  1687507499  ...  29899.9 -0.000368   1632    0
1633  20230623   160500    160959  1687507799  ...  29910.8  0.000334   1633    1
1634  20230623   161000    161459  1687508099  ...  29926.0  0.000792   1634    2
1635  20230623   161500    161959  1687508399  ...  29949.7  0.000845   1635    3
1636  20230623   162000    162459  1687508699  ...  29968.9  0.000434   1636    4

[5 rows x 11 columns]
2023-06-23 16:25:00,790:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-23 16:00:18,925:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230623    132959  29993.9  ...  55.416667  0.552809  0.440754
5787  20230623    135959  30039.1  ...  55.416667  0.552299  0.436248
5788  20230623    142959  30035.3  ...  55.416667  0.552331  0.432018
5789  20230623    145959  30036.8  ...  55.416667  0.548371  0.430358
5790  20230623    152959  30006.3  ...  55.000000  0.544753  0.430886

[5 rows x 33 columns]
0.5701107011070111
acc is : 0.5701107011070111
2023-06-23 16:00:19,007:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502750  0.497250       0  ...  1.135082   1.0    0.0  1.157193
538     1  0.489408  0.510592       1  ...  1.135093   1.0    0.0  1.157205
539     1  0.488361  0.511639       0  ...  1.133986   1.0    0.0  1.156076
540     1  0.484156  0.515844       0  ...  1.132981   1.0    0.0  1.155051
541     1  0.486613  0.513387       0  ...  1.130989   1.0    0.0  1.153021

[5 rows x 10 columns]
2023-06-23 16:00:19,018:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502890  0.497110       0  ...  1.135082   1.0    0.0  1.160390
46     1  0.489379  0.510621       1  ...  1.135093   1.0    0.0  1.162323
47     1  0.488119  0.511881       0  ...  1.133986   1.0    0.0  1.158102
48     1  0.484215  0.515785       0  ...  1.132981   1.0    0.0  1.158152
49     1  0.486613  0.513387       0  ...  1.130989   1.0    0.0  1.153021

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.727', 'enterprice': '30025.4', 'countrevence': '0', 'unrealprofit': '-2480.2656', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29932.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230623   155000    155959  1687507199  29930.2    29927 -0.000053
2023-06-23 16:00:02,152:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5792 

self.closeSec=1687507799, self.tradeDate='20230623', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29926.9', self.close='29926'
2023-06-23 16:10:01,114:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687507799, self.tradeDate='20230623', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29926.9', self.close='29926'
2023-06-23 16:10:01,131:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230623   152000    152959  1687505399    29934  29979.7  0.001527
525  20230623   153000    153959  1687505999  29979.7  29974.7 -0.000167
526  20230623   154000    154959  1687506599  29974.9  29928.6 -0.001538
527  20230623   155000    155959  1687507199  29930.2    29927 -0.000053
528  20230623   160000    160959  1687507799  29926.9    29926 -0.000033
2023-06-23 16:10:01,131:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5793 

self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29926', self.close='29975'
127.0.0.1 - - [23/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-23 16:20:07,774:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29926', self.close='29975'
2023-06-23 16:20:08,614:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230623   153000    153959  1687505999  29979.7  29974.7 -0.000167
526  20230623   154000    154959  1687506599  29974.9  29928.6 -0.001538
527  20230623   155000    155959  1687507199  29930.2    29927 -0.000053
528  20230623   160000    160959  1687507799  29926.9    29926 -0.000033
529  20230623   161000    161959  1687508399    29926    29975  0.001637
2023-06-23 16:20:08,614:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230623   155000    155959  1687507199  29930.2    29927
2023-06-23 16:00:02,156:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5795 

self.closeSec=1687507799, self.tradeDate='20230623', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29926.9', self.close='29926'
2023-06-23 16:10:01,115:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687507799, self.tradeDate='20230623', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29926.9', self.close='29926'
127.0.0.1 - - [23/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-23 16:10:01,137:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230623   152000    152959  1687505399    29934  29979.7
17517  20230623   153000    153959  1687505999  29979.7  29974.7
17518  20230623   154000    154959  1687506599  29974.9  29928.6
17519  20230623   155000    155959  1687507199  29930.2    29927
17520  20230623   160000    160959  1687507799  29926.9    29926
2023-06-23 16:10:01,137:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5796 

self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29926', self.close='29975'
127.0.0.1 - - [23/Jun/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-06-23 16:20:09,923:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29926', self.close='29975'
2023-06-23 16:20:10,058:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230623   153000    153959  1687505999  29979.7  29974.7
17518  20230623   154000    154959  1687506599  29974.9  29928.6
17519  20230623   155000    155959  1687507199  29930.2    29927
17520  20230623   160000    160959  1687507799  29926.9    29926
17521  20230623   161000    161959  1687508399    29926    29975
2023-06-23 16:20:10,059:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230623   155000    155959  1687507199  29930.2    29927
2023-06-23 16:00:02,167:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [23/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5795 

self.closeSec=1687507799, self.tradeDate='20230623', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29926.9', self.close='29926'
2023-06-23 16:10:01,120:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687507799, self.tradeDate='20230623', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29926.9', self.close='29926'
2023-06-23 16:10:01,134:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230623   152000    152959  1687505399    29934  29979.7
12189  20230623   153000    153959  1687505999  29979.7  29974.7
12190  20230623   154000    154959  1687506599  29974.9  29928.6
12191  20230623   155000    155959  1687507199  29930.2    29927
12192  20230623   160000    160959  1687507799  29926.9    29926
2023-06-23 16:10:01,134:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5796 

self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29926', self.close='29975'
127.0.0.1 - - [23/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-23 16:20:09,437:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29926', self.close='29975'
2023-06-23 16:20:09,753:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230623   153000    153959  1687505999  29979.7  29974.7
12190  20230623   154000    154959  1687506599  29974.9  29928.6
12191  20230623   155000    155959  1687507199  29930.2    29927
12192  20230623   160000    160959  1687507799  29926.9    29926
12193  20230623   161000    161959  1687508399    29926    29975
2023-06-23 16:20:09,754:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11584
self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29949.7, self.close=29975.0, self.high=29986.7, self.low=29949.7, self.vol=872.337, self.amt=26143828.9571 
127.0.0.1 - - [23/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-23 16:20:07,805:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230623   155500    155959  ...         0.0        0.0       0
5952  20230623   160000    160459  ...         0.0        0.0       0
5953  20230623   160500    160959  ...         0.0        0.0       0
5954  20230623   161000    161459  ...         0.0        0.0       0
5955  20230623   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 16:20:07,834:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687508399, self.tradeDate='20230623', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29949.7, self.close=29975.0, self.high=29986.7, self.low=29949.7, self.vol=872.337, self.amt=26143828.9571, ukdf['pct'].iloc[-1]=0.000845 , ukdf['amount'].iloc[-1]=26143828.9571, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '116548.458', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29982', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [23/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11585
self.closeSec=1687508699, self.tradeDate='20230623', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29975.0, self.close=29988.0, self.high=29988.0, self.low=29968.9, self.vol=594.822, self.amt=17832662.7799 
2023-06-23 16:25:00,801:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230623   160000    160459  ...         0.0        0.0       0
5953  20230623   160500    160959  ...         0.0        0.0       0
5954  20230623   161000    161459  ...         0.0        0.0       0
5955  20230623   161500    161959  ...         0.0        0.0       0
5956  20230623   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-23 16:25:00,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687508699, self.tradeDate='20230623', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29975.0, self.close=29988.0, self.high=29988.0, self.low=29968.9, self.vol=594.822, self.amt=17832662.7799, ukdf['pct'].iloc[-1]=0.000434 , ukdf['amount'].iloc[-1]=17832662.7799, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '116771.304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29988', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230623   040000    075959  1687478399  ...    721  1.101090  1.690718     1.0
722  20230623   080000    115959  1687492799  ...    722  1.081274  1.587372     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '108010.9312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30002.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=241
self.closeSec=1687507199, self.tradeDate='20230623', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30002.4, self.close=29927.0, self.high=30079.9, self.low=29910.0, self.vol=29527.682, self.amt=885812889.2415 127.0.0.1 - - [23/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -

2023-06-23 16:00:01,757:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687507199, self.tradeDate='20230623', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30002.4, self.close=29927.0, self.high=30079.9, self.low=29910.0, self.vol=29527.682, self.amt=885812889.2415 
2023-06-23 16:00:01,781:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230622   200000    235959  ...  177543.354  5.315799e+09 -0.002741
720  20230623   000000    035959  ...  101073.409  3.035134e+09  0.012451
721  20230623   040000    075959  ...   45457.791  1.365426e+09 -0.011050
722  20230623   080000    115959  ...   46051.180  1.379366e+09  0.004264
723  20230623   120000    155959  ...   29527.682  8.858129e+08 -0.002513

[5 rows x 11 columns]
2023-06-23 16:00:03,024:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230622   200000    235959  1687449599  ...    719  1.165810  2.001616     1.0
720  20230623   000000    035959  1687463999  ...    720  1.132999  1.838901     1.0
721  20230623   040000    075959  1687478399  ...    721  1.101090  1.690718     1.0
722  20230623   080000    115959  1687492799  ...    722  1.081274  1.587372     1.0
723  20230623   120000    155959  1687507199  ...    723  1.037418  1.420951     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '103983.4592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29927', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


