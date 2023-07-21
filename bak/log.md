# 20230721 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19648
self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29766.6, self.close=29782.0, self.high=29782.0, self.low=29757.0, self.vol=551.127, self.amt=16407045.4341 
127.0.0.1 - - [21/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-21 16:20:05,688:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230721   155500    155959  ...         0.0        0.0       0
5952  20230721   160000    160459  ...         0.0        0.0       0
5953  20230721   160500    160959  ...         0.0        0.0       0
5954  20230721   161000    161459  ...         0.0        0.0       0
5955  20230721   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 16:20:05,708:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29766.6, self.close=29782.0, self.high=29782.0, self.low=29757.0, self.vol=551.127, self.amt=16407045.4341, ukdf['pct'].iloc[-1]=0.000517 , ukdf['amount'].iloc[-1]=16407045.4341, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40623.5346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29782', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19649
self.closeSec=1689927899, self.tradeDate='20230721', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29782.0, self.close=29797.2, self.high=29797.6, self.low=29778.5, self.vol=609.174, self.amt=18144950.3218 
2023-07-21 16:25:00,788:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230721   160000    160459  ...         0.0        0.0       0
5953  20230721   160500    160959  ...         0.0        0.0       0
5954  20230721   161000    161459  ...         0.0        0.0       0
5955  20230721   161500    161959  ...         0.0        0.0       0
5956  20230721   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 16:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689927899, self.tradeDate='20230721', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29782.0, self.close=29797.2, self.high=29797.6, self.low=29778.5, self.vol=609.174, self.amt=18144950.3218, ukdf['pct'].iloc[-1]=0.00051 , ukdf['amount'].iloc[-1]=18144950.3218, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40835.2098', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29797.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29766.6, self.close=29782.0, self.high=29782.0, self.low=29757.0 
127.0.0.1 - - [21/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-21 16:20:04,137:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29766.6, self.close=29782.0, self.high=29782.0, self.low=29757.0   
2023-07-21 16:20:05,217:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230721   155500    155959  1689926399  ...  29744.8 -0.000037   1631    5
1632  20230721   160000    160459  1689926699  ...  29740.0  0.000575   1632    0
1633  20230721   160500    160959  1689926999  ...  29750.1 -0.000652   1633    1
1634  20230721   161000    161459  1689927299  ...  29755.4  0.000373   1634    2
1635  20230721   161500    161959  1689927599  ...  29757.0  0.000517   1635    3

[5 rows x 11 columns]
2023-07-21 16:20:05,219:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=60, self.factor=0.5521683402876979, self.count=19651 

self.closeSec=1689927899, self.tradeDate='20230721', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29782.0, self.close=29797.2, self.high=29797.6, self.low=29778.5 
2023-07-21 16:25:00,769:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689927899, self.tradeDate='20230721', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29782.0, self.close=29797.2, self.high=29797.6, self.low=29778.5   
2023-07-21 16:25:00,788:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230721   160000    160459  1689926699  ...  29740.0  0.000575   1632    0
1633  20230721   160500    160959  1689926999  ...  29750.1 -0.000652   1633    1
1634  20230721   161000    161459  1689927299  ...  29755.4  0.000373   1634    2
1635  20230721   161500    161959  1689927599  ...  29757.0  0.000517   1635    3
1636  20230721   162000    162459  1689927899  ...  29778.5  0.000510   1636    4

[5 rows x 11 columns]
2023-07-21 16:25:00,788:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-21 16:00:16,783:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230721    132959  29848.1  ...  50.000000  0.469426  0.617004
5787  20230721    135959  29812.9  ...  49.583333  0.467916  0.620341
5788  20230721    142959  29806.3  ...  49.583333  0.474683  0.621320
5789  20230721    145959  29832.1  ...  49.583333  0.476467  0.618543
5790  20230721    152959  29839.0  ...  49.166667  0.464999  0.619952

[5 rows x 33 columns]
0.5018450184501845
acc is : 0.5018450184501845
2023-07-21 16:00:16,839:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.496347  0.503653       0  ...  0.950629   1.0    0.0  0.990980
538     1  0.497323  0.502677       1  ...  0.951455   1.0    0.0  0.991841
539     0  0.508617  0.491383       1  ...  0.951672   1.0    0.0  0.992067
540     0  0.505206  0.494794       0  ...  0.950129   1.0    0.0  0.990458
541     1  0.486884  0.513116       0  ...  0.949083   1.0    0.0  0.989368

[5 rows x 10 columns]
2023-07-21 16:00:16,850:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496302  0.503698       0  ...  0.950629   1.0    0.0  0.988263
46     1  0.497814  0.502186       1  ...  0.922726   1.0    0.0  0.989551
47     0  0.508582  0.491418       1  ...  0.951672   1.0    0.0  0.989757
48     0  0.505686  0.494314       0  ...  0.921440   1.0    0.0  0.990899
49     1  0.486884  0.513116       0  ...  0.949083   1.0    0.0  0.989368

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '-2014.82231574552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29753.35808242', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230721   155000    155959  1689926399  29765.8  29757.8 -0.000265
2023-07-21 16:00:02,058:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [21/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9824 

self.closeSec=1689926999, self.tradeDate='20230721', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29757.8', self.close='29755.5'
2023-07-21 16:10:01,096:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689926999, self.tradeDate='20230721', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29757.8', self.close='29755.5'
2023-07-21 16:10:01,108:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230721   152000    152959  1689924599    29794  29790.6 -0.000070
525  20230721   153000    153959  1689925199  29790.7  29767.8 -0.000765
526  20230721   154000    154959  1689925799  29767.8  29765.7 -0.000071
527  20230721   155000    155959  1689926399  29765.8  29757.8 -0.000265
528  20230721   160000    160959  1689926999  29757.8  29755.5 -0.000077
2023-07-21 16:10:01,108:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9825 

self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29755.5', self.close='29782'
127.0.0.1 - - [21/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-21 16:20:06,378:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29755.5', self.close='29782'
2023-07-21 16:20:06,908:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230721   153000    153959  1689925199  29790.7  29767.8 -0.000765
526  20230721   154000    154959  1689925799  29767.8  29765.7 -0.000071
527  20230721   155000    155959  1689926399  29765.8  29757.8 -0.000265
528  20230721   160000    160959  1689926999  29757.8  29755.5 -0.000077
529  20230721   161000    161959  1689927599  29755.5    29782  0.000891
2023-07-21 16:20:06,908:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230721   155000    155959  1689926399  29765.8  29757.8
2023-07-21 16:00:02,067:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9827 

self.closeSec=1689926999, self.tradeDate='20230721', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29757.8', self.close='29755.5'
2023-07-21 16:10:01,108:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689926999, self.tradeDate='20230721', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29757.8', self.close='29755.5'
2023-07-21 16:10:01,118:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230721   152000    152959  1689924599    29794  29790.6
17517  20230721   153000    153959  1689925199  29790.7  29767.8
17518  20230721   154000    154959  1689925799  29767.8  29765.7
17519  20230721   155000    155959  1689926399  29765.8  29757.8
17520  20230721   160000    160959  1689926999  29757.8  29755.5
2023-07-21 16:10:01,118:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9828 

self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29755.5', self.close='29782'
127.0.0.1 - - [21/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-21 16:20:07,667:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29755.5', self.close='29782'
2023-07-21 16:20:07,876:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230721   153000    153959  1689925199  29790.7  29767.8
17518  20230721   154000    154959  1689925799  29767.8  29765.7
17519  20230721   155000    155959  1689926399  29765.8  29757.8
17520  20230721   160000    160959  1689926999  29757.8  29755.5
17521  20230721   161000    161959  1689927599  29755.5    29782
2023-07-21 16:20:07,876:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230721   155000    155959  1689926399  29765.8  29757.8
2023-07-21 16:00:02,076:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9827 

self.closeSec=1689926999, self.tradeDate='20230721', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29757.8', self.close='29755.5'
127.0.0.1 - - [21/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-21 16:10:01,100:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689926999, self.tradeDate='20230721', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29757.8', self.close='29755.5'
2023-07-21 16:10:01,118:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230721   152000    152959  1689924599    29794  29790.6
12189  20230721   153000    153959  1689925199  29790.7  29767.8
12190  20230721   154000    154959  1689925799  29767.8  29765.7
12191  20230721   155000    155959  1689926399  29765.8  29757.8
12192  20230721   160000    160959  1689926999  29757.8  29755.5
2023-07-21 16:10:01,119:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9828 

self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29755.5', self.close='29782'
127.0.0.1 - - [21/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-21 16:20:07,539:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29755.5', self.close='29782'
2023-07-21 16:20:07,747:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230721   153000    153959  1689925199  29790.7  29767.8
12190  20230721   154000    154959  1689925799  29767.8  29765.7
12191  20230721   155000    155959  1689926399  29765.8  29757.8
12192  20230721   160000    160959  1689926999  29757.8  29755.5
12193  20230721   161000    161959  1689927599  29755.5    29782
2023-07-21 16:20:07,749:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19648
self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29766.6, self.close=29782.0, self.high=29782.0, self.low=29757.0, self.vol=551.127, self.amt=16407045.4341 
127.0.0.1 - - [21/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-21 16:20:05,847:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230721   155500    155959  ...         0.0        0.0       0
5952  20230721   160000    160459  ...         0.0        0.0       0
5953  20230721   160500    160959  ...         0.0        0.0       0
5954  20230721   161000    161459  ...         0.0        0.0       0
5955  20230721   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 16:20:05,858:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689927599, self.tradeDate='20230721', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29766.6, self.close=29782.0, self.high=29782.0, self.low=29757.0, self.vol=551.127, self.amt=16407045.4341, ukdf['pct'].iloc[-1]=0.000517 , ukdf['amount'].iloc[-1]=16407045.4341, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '109120.258', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29782', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19649
self.closeSec=1689927899, self.tradeDate='20230721', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29782.0, self.close=29797.2, self.high=29797.6, self.low=29778.5, self.vol=609.174, self.amt=18144950.3218 
127.0.0.1 - - [21/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-21 16:25:00,799:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230721   160000    160459  ...         0.0        0.0       0
5953  20230721   160500    160959  ...         0.0        0.0       0
5954  20230721   161000    161459  ...         0.0        0.0       0
5955  20230721   161500    161959  ...         0.0        0.0       0
5956  20230721   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 16:25:00,800:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689927899, self.tradeDate='20230721', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29782.0, self.close=29797.2, self.high=29797.6, self.low=29778.5, self.vol=609.174, self.amt=18144950.3218, ukdf['pct'].iloc[-1]=0.00051 , ukdf['amount'].iloc[-1]=18144950.3218, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '109684.8012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29797.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230721   040000    075959  1689897599  ...    721  0.156485 -1.097778    -1.0
722  20230721   080000    115959  1689911999  ...    722  0.148863 -1.105886    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-714.8112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29884.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=409
self.closeSec=1689926399, self.tradeDate='20230721', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29884.3, self.close=29757.8, self.high=29893.3, self.low=29729.6, self.vol=26891.176, self.amt=801670874.34318 
127.0.0.1 - - [21/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-21 16:00:01,641:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689926399, self.tradeDate='20230721', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29884.3, self.close=29757.8, self.high=29893.3, self.low=29729.6, self.vol=26891.176, self.amt=801670874.34318 
2023-07-21 16:00:01,655:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230720   200000    235959  ...  146334.281  4.377740e+09 -0.015895
720  20230721   000000    035959  ...   78409.883  2.329877e+09 -0.001625
721  20230721   040000    075959  ...   28490.094  8.484414e+08  0.001567
722  20230721   080000    115959  ...   38621.219  1.152736e+09  0.003132
723  20230721   120000    155959  ...   26891.176  8.016709e+08 -0.004233

[5 rows x 11 columns]
2023-07-21 16:00:02,369:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230720   200000    235959  1689868799  ...    719  0.143075 -1.207132    -1.0
720  20230721   000000    035959  1689883199  ...    720  0.155606 -1.126586    -1.0
721  20230721   040000    075959  1689897599  ...    721  0.156485 -1.097778    -1.0
722  20230721   080000    115959  1689911999  ...    722  0.148863 -1.105886    -1.0
723  20230721   120000    155959  1689926399  ...    723  0.141051 -1.114406    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '5885.4528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29757.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


