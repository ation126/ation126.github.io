# 20230320 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [20/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32572
self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28081.2, self.close=28042.9, self.high=28131.1, self.low=27990.0, self.vol=8291.191, self.amt=232608819.3426 
2023-03-20 16:20:02,650:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230320   155500    155959  ...         0.0        0.0       0
5952  20230320   160000    160459  ...         0.0        0.0       0
5953  20230320   160500    160959  ...         0.0        0.0       0
5954  20230320   161000    161459  ...         0.0        0.0       0
5955  20230320   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 16:20:02,660:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28081.2, self.close=28042.9, self.high=28131.1, self.low=27990.0, self.vol=8291.191, self.amt=232608819.3426, ukdf['pct'].iloc[-1]=-0.00136 , ukdf['amount'].iloc[-1]=232608819.3426, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-691871.78774218176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28026.77054876', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32573
self.closeSec=1679300699, self.tradeDate='20230320', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28037.6, self.close=28137.2, self.high=28147.2, self.low=28021.7, self.vol=4376.354, self.amt=122998909.1151 
127.0.0.1 - - [20/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-20 16:25:01,580:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230320   160000    160459  ...         0.0        0.0       0
5953  20230320   160500    160959  ...         0.0        0.0       0
5954  20230320   161000    161459  ...         0.0        0.0       0
5955  20230320   161500    161959  ...         0.0        0.0       0
5956  20230320   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 16:25:01,582:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679300699, self.tradeDate='20230320', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28037.6, self.close=28137.2, self.high=28147.2, self.low=28021.7, self.vol=4376.354, self.amt=122998909.1151, ukdf['pct'].iloc[-1]=0.003363 , ukdf['amount'].iloc[-1]=122998909.1151, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-698548.46627699888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28137.72306363', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28081.2, self.close=28042.9, self.high=28131.1, self.low=27990.0 
127.0.0.1 - - [20/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-20 16:20:02,950:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28081.2, self.close=28042.9, self.high=28131.1, self.low=27990.0   
2023-03-20 16:20:03,232:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230320   155500    155959  1679299199  ...  28150.0 -0.001273   1631    5
1632  20230320   160000    160459  1679299499  ...  28168.5  0.002276   1632    0
1633  20230320   160500    160959  1679299799  ...  28229.8  0.002950   1633    1
1634  20230320   161000    161459  1679300099  ...  28060.0 -0.008292   1634    2
1635  20230320   161500    161959  1679300399  ...  27990.0 -0.001360   1635    3

[5 rows x 11 columns]
2023-03-20 16:20:03,232:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=140, self.factor=0.42178459786807726, self.count=33139 

self.closeSec=1679300699, self.tradeDate='20230320', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28037.6, self.close=28137.2, self.high=28147.2, self.low=28021.7 
2023-03-20 16:25:01,504:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679300699, self.tradeDate='20230320', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28037.6, self.close=28137.2, self.high=28147.2, self.low=28021.7   
2023-03-20 16:25:01,581:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230320   160000    160459  1679299499  ...  28168.5  0.002276   1632    0
1633  20230320   160500    160959  1679299799  ...  28229.8  0.002950   1633    1
1634  20230320   161000    161459  1679300099  ...  28060.0 -0.008292   1634    2
1635  20230320   161500    161959  1679300399  ...  27990.0 -0.001360   1635    3
1636  20230320   162000    162459  1679300699  ...  28021.7  0.003363   1636    4

[5 rows x 11 columns]
2023-03-20 16:25:01,581:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-20 16:00:34,615:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230320    132959  27422.3  ...  48.750000  0.515568  0.434857
5787  20230320    135959  27417.6  ...  49.166667  0.525421  0.445901
5788  20230320    142959  27510.1  ...  49.166667  0.527256  0.455428
5789  20230320    145959  27527.4  ...  49.166667  0.536734  0.460270
5790  20230320    152959  27617.2  ...  49.583333  0.558849  0.456941

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-03-20 16:00:34,770:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.516570  0.483430       1  ...  1.196945  -1.0  0.0000  1.267087
538     0  0.573966  0.426034       1  ...  1.195782   1.0 -0.0016  1.267884
539     0  0.552338  0.447662       1  ...  1.199679   1.0  0.0000  1.272015
540     0  0.568961  0.431039       1  ...  1.209227   1.0  0.0000  1.282139
541     0  0.626309  0.373691       1  ...  1.223631   1.0  0.0000  1.297412

[5 rows x 10 columns]
2023-03-20 16:00:34,798:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.516417  0.483583       1  ...  1.195913  -1.0  0.0000  1.262192
46     0  0.573747  0.426253       1  ...  1.202258   1.0 -0.0016  1.269041
47     0  0.551478  0.448522       1  ...  1.212986   1.0  0.0000  1.272947
48     0  0.568796  0.431204       1  ...  1.222640   1.0  0.0000  1.280075
49     0  0.626309  0.373691       1  ...  1.223631   1.0  0.0000  1.297412

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230320   155000    155959  1679299199  28137.3  28168.5  0.001066
2023-03-20 16:00:02,370:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16568 

self.closeSec=1679299799, self.tradeDate='20230320', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28168.5', self.close='28315.9'
2023-03-20 16:10:01,637:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679299799, self.tradeDate='20230320', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28168.5', self.close='28315.9'
2023-03-20 16:10:01,681:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230320   152000    152959  1679297399  27829.3  27836.9  0.000187
525  20230320   153000    153959  1679297999  27836.8  27931.4  0.003395
526  20230320   154000    154959  1679298599  27931.5  28138.5  0.007415
527  20230320   155000    155959  1679299199  28137.3  28168.5  0.001066
528  20230320   160000    160959  1679299799  28168.5  28315.9  0.005233
2023-03-20 16:10:01,681:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16569 

self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28325.9', self.close='28042.9'
127.0.0.1 - - [20/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-20 16:20:03,471:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28325.9', self.close='28042.9'
2023-03-20 16:20:03,865:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230320   153000    153959  1679297999  27836.8  27931.4  0.003395
526  20230320   154000    154959  1679298599  27931.5  28138.5  0.007415
527  20230320   155000    155959  1679299199  28137.3  28168.5  0.001066
528  20230320   160000    160959  1679299799  28168.5  28315.9  0.005233
529  20230320   161000    161959  1679300399  28325.9  28042.9 -0.009641
2023-03-20 16:20:03,865:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230320   155000    155959  1679299199  28137.3  28168.5
2023-03-20 16:00:02,428:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16569 

self.closeSec=1679299799, self.tradeDate='20230320', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28168.5', self.close='28315.9'
2023-03-20 16:10:01,646:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679299799, self.tradeDate='20230320', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28168.5', self.close='28315.9'
2023-03-20 16:10:01,699:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230320   152000    152959  1679297399  27829.3  27836.9
17517  20230320   153000    153959  1679297999  27836.8  27931.4
17518  20230320   154000    154959  1679298599  27931.5  28138.5
17519  20230320   155000    155959  1679299199  28137.3  28168.5
17520  20230320   160000    160959  1679299799  28168.5  28315.9
2023-03-20 16:10:01,699:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16570 

self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28325.9', self.close='28042.9'
127.0.0.1 - - [20/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-20 16:20:05,045:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28325.9', self.close='28042.9'
2023-03-20 16:20:05,140:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230320   153000    153959  1679297999  27836.8  27931.4
17518  20230320   154000    154959  1679298599  27931.5  28138.5
17519  20230320   155000    155959  1679299199  28137.3  28168.5
17520  20230320   160000    160959  1679299799  28168.5  28315.9
17521  20230320   161000    161959  1679300399  28325.9  28042.9
2023-03-20 16:20:05,140:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230320   155000    155959  1679299199  28137.3  28168.5
2023-03-20 16:00:02,408:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [20/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16569 

self.closeSec=1679299799, self.tradeDate='20230320', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28168.5', self.close='28315.9'
2023-03-20 16:10:01,643:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679299799, self.tradeDate='20230320', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28168.5', self.close='28315.9'
2023-03-20 16:10:01,674:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230320   152000    152959  1679297399  27829.3  27836.9
12189  20230320   153000    153959  1679297999  27836.8  27931.4
12190  20230320   154000    154959  1679298599  27931.5  28138.5
12191  20230320   155000    155959  1679299199  28137.3  28168.5
12192  20230320   160000    160959  1679299799  28168.5  28315.9
2023-03-20 16:10:01,674:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16570 

self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28325.9', self.close='28042.9'
127.0.0.1 - - [20/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-20 16:20:04,712:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28325.9', self.close='28042.9'
2023-03-20 16:20:04,943:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230320   153000    153959  1679297999  27836.8  27931.4
12190  20230320   154000    154959  1679298599  27931.5  28138.5
12191  20230320   155000    155959  1679299199  28137.3  28168.5
12192  20230320   160000    160959  1679299799  28168.5  28315.9
12193  20230320   161000    161959  1679300399  28325.9  28042.9
2023-03-20 16:20:04,943:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [20/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28570
self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28081.2, self.close=28042.9, self.high=28131.1, self.low=27990.0, self.vol=8291.191, self.amt=232608819.3426 
2023-03-20 16:20:01,596:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230320   155500    155959  ...         0.0        0.0       0
5952  20230320   160000    160459  ...         0.0        0.0       0
5953  20230320   160500    160959  ...         0.0        0.0       0
5954  20230320   161000    161459  ...         0.0        0.0       0
5955  20230320   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 16:20:01,598:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679300399, self.tradeDate='20230320', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28081.2, self.close=28042.9, self.high=28131.1, self.low=27990.0, self.vol=8291.191, self.amt=232608819.3426, ukdf['pct'].iloc[-1]=-0.00136 , ukdf['amount'].iloc[-1]=232608819.3426, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [20/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28571
self.closeSec=1679300699, self.tradeDate='20230320', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28037.6, self.close=28137.2, self.high=28147.2, self.low=28021.7, self.vol=4376.354, self.amt=122998909.1151 
2023-03-20 16:25:01,631:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230320   160000    160459  ...         0.0        0.0       0
5953  20230320   160500    160959  ...         0.0        0.0       0
5954  20230320   161000    161459  ...         0.0        0.0       0
5955  20230320   161500    161959  ...         0.0        0.0       0
5956  20230320   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 16:25:01,633:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679300699, self.tradeDate='20230320', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28037.6, self.close=28137.2, self.high=28147.2, self.low=28021.7, self.vol=4376.354, self.amt=122998909.1151, ukdf['pct'].iloc[-1]=0.003363 , ukdf['amount'].iloc[-1]=122998909.1151, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230320   040000    075959  1679270399  ...    721  1.027322  1.009618     1.0
722  20230320   080000    115959  1679284799  ...    722  1.020162  0.973997     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '-7547.071983906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27259.7068132', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [20/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=690
self.closeSec=1679299199, self.tradeDate='20230320', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27264.3, self.close=28168.5, self.high=28261.9, self.low=27140.0, self.vol=139390.542, self.amt=3864202106.21372 
2023-03-20 16:00:02,230:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679299199, self.tradeDate='20230320', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27264.3, self.close=28168.5, self.high=28261.9, self.low=27140.0, self.vol=139390.542, self.amt=3864202106.21372 
2023-03-20 16:00:02,266:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230319   200000    235959  ...  164948.133  4.515101e+09  0.014073
720  20230320   000000    035959  ...  261334.591  7.308131e+09  0.025822
721  20230320   040000    075959  ...  146620.436  4.111874e+09 -0.010253
722  20230320   080000    115959  ...  154695.612  4.262960e+09 -0.024732
723  20230320   120000    155959  ...  139390.542  3.864202e+09  0.033164

[5 rows x 11 columns]
2023-03-20 16:00:04,701:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230319   200000    235959  1679241599  ...    719  0.978582  0.898154     1.0
720  20230320   000000    035959  1679255999  ...    720  1.021906  1.009114     1.0
721  20230320   040000    075959  1679270399  ...    721  1.027322  1.009618     1.0
722  20230320   080000    115959  1679284799  ...    722  1.020162  0.973997     1.0
723  20230320   120000    155959  1679299199  ...    723  0.997496  0.896116     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '41954.7205', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28179.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


