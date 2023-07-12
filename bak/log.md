# 20230712 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17056
self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30720.1, self.close=30713.6, self.high=30730.0, self.low=30711.0, self.vol=468.617, self.amt=14396619.2435 
127.0.0.1 - - [12/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-12 16:20:07,180:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230712   155500    155959  ...         0.0        0.0       0
5952  20230712   160000    160459  ...         0.0        0.0       0
5953  20230712   160500    160959  ...         0.0        0.0       0
5954  20230712   161000    161459  ...         0.0        0.0       0
5955  20230712   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 16:20:07,209:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30720.1, self.close=30713.6, self.high=30730.0, self.low=30711.0, self.vol=468.617, self.amt=14396619.2435, ukdf['pct'].iloc[-1]=-0.000212 , ukdf['amount'].iloc[-1]=14396619.2435, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-53623.16738792178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30715.47930403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17057
self.closeSec=1689150299, self.tradeDate='20230712', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30713.6, self.close=30703.9, self.high=30723.0, self.low=30700.2, self.vol=756.062, self.amt=23217792.2185 
127.0.0.1 - - [12/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-12 16:25:00,816:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230712   160000    160459  ...         0.0        0.0       0
5953  20230712   160500    160959  ...         0.0        0.0       0
5954  20230712   161000    161459  ...         0.0        0.0       0
5955  20230712   161500    161959  ...         0.0        0.0       0
5956  20230712   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 16:25:00,817:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689150299, self.tradeDate='20230712', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30713.6, self.close=30703.9, self.high=30723.0, self.low=30700.2, self.vol=756.062, self.amt=23217792.2185, ukdf['pct'].iloc[-1]=-0.000316 , ukdf['amount'].iloc[-1]=23217792.2185, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-53509.26739901622', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30707.30035897', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30720.1, self.close=30713.6, self.high=30730.0, self.low=30711.0 
127.0.0.1 - - [12/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-12 16:20:04,640:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30720.1, self.close=30713.6, self.high=30730.0, self.low=30711.0   
2023-07-12 16:20:06,199:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230712   155500    155959  1689148799  ...  30718.0 -0.002295   1631    5
1632  20230712   160000    160459  1689149099  ...  30702.9 -0.000277   1632    0
1633  20230712   160500    160959  1689149399  ...  30716.4  0.000000   1633    1
1634  20230712   161000    161459  1689149699  ...  30720.0 -0.000046   1634    2
1635  20230712   161500    161959  1689149999  ...  30711.0 -0.000212   1635    3

[5 rows x 11 columns]
2023-07-12 16:20:06,210:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=175, self.factor=0.36925364097359464, self.count=17059 

self.closeSec=1689150299, self.tradeDate='20230712', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30713.6, self.close=30703.9, self.high=30723.0, self.low=30700.2 
127.0.0.1 - - [12/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-12 16:25:00,739:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689150299, self.tradeDate='20230712', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30713.6, self.close=30703.9, self.high=30723.0, self.low=30700.2   
2023-07-12 16:25:00,778:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230712   160000    160459  1689149099  ...  30702.9 -0.000277   1632    0
1633  20230712   160500    160959  1689149399  ...  30716.4  0.000000   1633    1
1634  20230712   161000    161459  1689149699  ...  30720.0 -0.000046   1634    2
1635  20230712   161500    161959  1689149999  ...  30711.0 -0.000212   1635    3
1636  20230712   162000    162459  1689150299  ...  30700.2 -0.000316   1636    4

[5 rows x 11 columns]
2023-07-12 16:25:00,779:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-12 16:00:19,193:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230712    132959  30623.9  ...  50.416667  0.544193  0.447348
5787  20230712    135959  30624.4  ...  50.416667  0.548365  0.437445
5788  20230712    142959  30642.5  ...  50.833333  0.567730  0.417555
5789  20230712    145959  30729.3  ...  50.833333  0.561307  0.401776
5790  20230712    152959  30706.6  ...  51.250000  0.576947  0.378131

[5 rows x 33 columns]
0.577490774907749
acc is : 0.577490774907749
2023-07-12 16:00:19,341:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.509600  0.490400       1  ...  1.013195   1.0    0.0  1.006021
538     0  0.513965  0.486035       1  ...  1.016065   1.0    0.0  1.008871
539     0  0.543423  0.456577       0  ...  1.015315   1.0    0.0  1.008126
540     0  0.514046  0.485954       1  ...  1.017719   1.0    0.0  1.010512
541     0  0.539348  0.460652       0  ...  1.016115   1.0    0.0  1.008920

[5 rows x 10 columns]
2023-07-12 16:00:19,379:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509658  0.490342       1  ...  1.013195   1.0    0.0  1.005708
46     0  0.513435  0.486565       1  ...  1.016065   1.0    0.0  1.007644
47     0  0.543407  0.456593       0  ...  1.015315   1.0    0.0  1.008089
48     0  0.513619  0.486381       1  ...  0.988335   1.0    0.0  1.009025
49     0  0.539348  0.460652       0  ...  1.016115   1.0    0.0  1.008920

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.383', 'enterprice': '30486.7', 'countrevence': '0', 'unrealprofit': '6346.8949', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30747', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230712   155000    155959  1689148799  30803.3  30730.8 -0.002350
2023-07-12 16:00:02,062:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8528 

self.closeSec=1689149399, self.tradeDate='20230712', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30730.7', self.close='30721.6'
2023-07-12 16:10:01,067:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689149399, self.tradeDate='20230712', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30730.7', self.close='30721.6'
2023-07-12 16:10:01,100:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230712   152000    152959  1689146999  30744.1  30779.3  0.001145
525  20230712   153000    153959  1689147599  30779.4    30782  0.000088
526  20230712   154000    154959  1689148199  30782.1  30803.2  0.000689
527  20230712   155000    155959  1689148799  30803.3  30730.8 -0.002350
528  20230712   160000    160959  1689149399  30730.7  30721.6 -0.000299
2023-07-12 16:10:01,101:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8529 

self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30721.5', self.close='30713.5'
127.0.0.1 - - [12/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-12 16:20:07,069:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30721.5', self.close='30713.5'
2023-07-12 16:20:07,830:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230712   153000    153959  1689147599  30779.4    30782  0.000088
526  20230712   154000    154959  1689148199  30782.1  30803.2  0.000689
527  20230712   155000    155959  1689148799  30803.3  30730.8 -0.002350
528  20230712   160000    160959  1689149399  30730.7  30721.6 -0.000299
529  20230712   161000    161959  1689149999  30721.5  30713.5 -0.000264
2023-07-12 16:20:07,830:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230712   155000    155959  1689148799  30803.3  30730.8
2023-07-12 16:00:02,074:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8531 

self.closeSec=1689149399, self.tradeDate='20230712', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30730.7', self.close='30721.6'
127.0.0.1 - - [12/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-12 16:10:01,089:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689149399, self.tradeDate='20230712', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30730.7', self.close='30721.6'
2023-07-12 16:10:01,109:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230712   152000    152959  1689146999  30744.1  30779.3
17517  20230712   153000    153959  1689147599  30779.4    30782
17518  20230712   154000    154959  1689148199  30782.1  30803.2
17519  20230712   155000    155959  1689148799  30803.3  30730.8
17520  20230712   160000    160959  1689149399  30730.7  30721.6
2023-07-12 16:10:01,109:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8532 

self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30721.5', self.close='30713.5'
127.0.0.1 - - [12/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-12 16:20:08,651:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30721.5', self.close='30713.5'
2023-07-12 16:20:08,849:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230712   153000    153959  1689147599  30779.4    30782
17518  20230712   154000    154959  1689148199  30782.1  30803.2
17519  20230712   155000    155959  1689148799  30803.3  30730.8
17520  20230712   160000    160959  1689149399  30730.7  30721.6
17521  20230712   161000    161959  1689149999  30721.5  30713.5
2023-07-12 16:20:08,850:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230712   155000    155959  1689148799  30803.3  30730.8
2023-07-12 16:00:02,091:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8531 

self.closeSec=1689149399, self.tradeDate='20230712', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30730.7', self.close='30721.6'
2023-07-12 16:10:01,073:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689149399, self.tradeDate='20230712', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30730.7', self.close='30721.6'
127.0.0.1 - - [12/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-12 16:10:01,105:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230712   152000    152959  1689146999  30744.1  30779.3
12189  20230712   153000    153959  1689147599  30779.4    30782
12190  20230712   154000    154959  1689148199  30782.1  30803.2
12191  20230712   155000    155959  1689148799  30803.3  30730.8
12192  20230712   160000    160959  1689149399  30730.7  30721.6
2023-07-12 16:10:01,105:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8532 

self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30721.5', self.close='30713.5'
127.0.0.1 - - [12/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-12 16:20:08,440:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30721.5', self.close='30713.5'
2023-07-12 16:20:08,704:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230712   153000    153959  1689147599  30779.4    30782
12190  20230712   154000    154959  1689148199  30782.1  30803.2
12191  20230712   155000    155959  1689148799  30803.3  30730.8
12192  20230712   160000    160959  1689149399  30730.7  30721.6
12193  20230712   161000    161959  1689149999  30721.5  30713.5
2023-07-12 16:20:08,709:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17056
self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30720.1, self.close=30713.6, self.high=30730.0, self.low=30711.0, self.vol=468.617, self.amt=14396619.2435 
127.0.0.1 - - [12/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-12 16:20:07,189:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230712   155500    155959  ...         0.0        0.0       0
5952  20230712   160000    160459  ...         0.0        0.0       0
5953  20230712   160500    160959  ...         0.0        0.0       0
5954  20230712   161000    161459  ...         0.0        0.0       0
5955  20230712   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 16:20:07,220:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689149999, self.tradeDate='20230712', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30720.1, self.close=30713.6, self.high=30730.0, self.low=30711.0, self.vol=468.617, self.amt=14396619.2435, ukdf['pct'].iloc[-1]=-0.000212 , ukdf['amount'].iloc[-1]=14396619.2435, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '143790.61283097823', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30715.47930403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [12/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17057
self.closeSec=1689150299, self.tradeDate='20230712', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30713.6, self.close=30703.9, self.high=30723.0, self.low=30700.2, self.vol=756.062, self.amt=23217792.2185 
2023-07-12 16:25:00,821:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230712   160000    160459  ...         0.0        0.0       0
5953  20230712   160500    160959  ...         0.0        0.0       0
5954  20230712   161000    161459  ...         0.0        0.0       0
5955  20230712   161500    161959  ...         0.0        0.0       0
5956  20230712   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-12 16:25:00,821:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689150299, self.tradeDate='20230712', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30713.6, self.close=30703.9, self.high=30723.0, self.low=30700.2, self.vol=756.062, self.amt=23217792.2185, ukdf['pct'].iloc[-1]=-0.000316 , ukdf['amount'].iloc[-1]=23217792.2185, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '143486.83863250477', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30707.30035897', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230712   040000    075959  1689119999  ...    721  0.249948 -0.076812     NaN
722  20230712   080000    115959  1689134399  ...    722  0.263795 -0.019669     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-14833.597', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30583.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1604933.5124475, self.flagDict['side']='sell', self.tradeCount=10, self.count=355
self.closeSec=1689148799, self.tradeDate='20230712', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30581.3, self.close=30730.8, self.high=30849.2, self.low=30555.0, self.vol=50264.091, self.amt=1543708552.23259 
127.0.0.1 - - [12/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-12 16:00:01,686:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689148799, self.tradeDate='20230712', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30581.3, self.close=30730.8, self.high=30849.2, self.low=30555.0, self.vol=50264.091, self.amt=1543708552.23259 
2023-07-12 16:00:01,726:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230711   200000    235959  ...  98194.832  2.997190e+09  0.006390
720  20230712   000000    035959  ...  52691.726  1.609284e+09 -0.000654
721  20230712   040000    075959  ...  26843.465  8.204939e+08  0.001404
722  20230712   080000    115959  ...  28484.366  8.705943e+08 -0.000885
723  20230712   120000    155959  ...  50264.091  1.543709e+09  0.004889

[5 rows x 11 columns]
2023-07-12 16:00:02,732:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230711   200000    235959  1689091199  ...    719  0.168446 -0.433802     NaN
720  20230712   000000    035959  1689105599  ...    720  0.258325 -0.037801     NaN
721  20230712   040000    075959  1689119999  ...    721  0.249948 -0.076812     NaN
722  20230712   080000    115959  1689134399  ...    722  0.263795 -0.019669     NaN
723  20230712   120000    155959  1689148799  ...    723  0.355324  0.374296     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-22653.3095', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30730.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


