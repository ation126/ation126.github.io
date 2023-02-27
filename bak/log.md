# 20230227 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26524
self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23376.4, self.close=23387.8, self.high=23394.0, self.low=23371.0, self.vol=791.839, self.amt=18515434.2657 
127.0.0.1 - - [27/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:20:02,903:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230227   155500    155959  ...         0.0        0.0       0
5952  20230227   160000    160459  ...         0.0        0.0       0
5953  20230227   160500    160959  ...         0.0        0.0       0
5954  20230227   161000    161459  ...         0.0        0.0       0
5955  20230227   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 16:20:02,904:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23376.4, self.close=23387.8, self.high=23394.0, self.low=23371.0, self.vol=791.839, self.amt=18515434.2657, ukdf['pct'].iloc[-1]=0.000304 , ukdf['amount'].iloc[-1]=18515434.2657, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-412759.2192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23388.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26525
self.closeSec=1677486299, self.tradeDate='20230227', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23388.4, self.close=23362.4, self.high=23396.9, self.low=23350.0, self.vol=1412.412, self.amt=33003034.3023 
127.0.0.1 - - [27/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:25:01,598:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230227   160000    160459  ...         0.0        0.0       0
5953  20230227   160500    160959  ...         0.0        0.0       0
5954  20230227   161000    161459  ...         0.0        0.0       0
5955  20230227   161500    161959  ...         0.0        0.0       0
5956  20230227   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 16:25:01,599:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677486299, self.tradeDate='20230227', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23388.4, self.close=23362.4, self.high=23396.9, self.low=23350.0, self.vol=1412.412, self.amt=33003034.3023, ukdf['pct'].iloc[-1]=-0.001086 , ukdf['amount'].iloc[-1]=33003034.3023, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-411176.5904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23362.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23376.4, self.close=23387.8, self.high=23394.0, self.low=23371.0 
127.0.0.1 - - [27/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:20:02,136:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23376.4, self.close=23387.8, self.high=23394.0, self.low=23371.0   
2023-02-27 16:20:02,559:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230227   155500    155959  1677484799  ...  23403.8 -0.000794   1631    5
1632  20230227   160000    160459  1677485099  ...  23407.1  0.000483   1632    0
1633  20230227   160500    160959  1677485399  ...  23393.5 -0.001204   1633    1
1634  20230227   161000    161459  1677485699  ...  23361.0 -0.000577   1634    2
1635  20230227   161500    161959  1677485999  ...  23371.0  0.000304   1635    3

[5 rows x 11 columns]
2023-02-27 16:20:02,560:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.34058131601621167, self.count=27091 

self.closeSec=1677486299, self.tradeDate='20230227', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23388.4, self.close=23362.4, self.high=23396.9, self.low=23350.0 
127.0.0.1 - - [27/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:25:01,520:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677486299, self.tradeDate='20230227', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23388.4, self.close=23362.4, self.high=23396.9, self.low=23350.0   
2023-02-27 16:25:01,573:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230227   160000    160459  1677485099  ...  23407.1  0.000483   1632    0
1633  20230227   160500    160959  1677485399  ...  23393.5 -0.001204   1633    1
1634  20230227   161000    161459  1677485699  ...  23361.0 -0.000577   1634    2
1635  20230227   161500    161959  1677485999  ...  23371.0  0.000304   1635    3
1636  20230227   162000    162459  1677486299  ...  23350.0 -0.001086   1636    4

[5 rows x 11 columns]
2023-02-27 16:25:01,573:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-27 16:00:41,553:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230227    132959  23480.3  ...  47.916667  0.530303  0.258197
5787  20230227    135959  23467.7  ...  47.500000  0.509122  0.276390
5788  20230227    142959  23377.8  ...  47.500000  0.508293  0.293799
5789  20230227    145959  23374.1  ...  47.916667  0.512548  0.307796
5790  20230227    152959  23393.2  ...  47.916667  0.523609  0.314939

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2023-02-27 16:00:41,752:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495111  0.504889       0  ...  0.920952   1.0    0.0  0.949935
538     1  0.470794  0.529206       0  ...  0.920810   1.0    0.0  0.949788
539     1  0.488524  0.511476       1  ...  0.921555   1.0    0.0  0.950556
540     1  0.497937  0.502063       1  ...  0.923513   1.0    0.0  0.952576
541     0  0.509185  0.490815       0  ...  0.922264   1.0    0.0  0.951288

[5 rows x 10 columns]
2023-02-27 16:00:41,791:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496642  0.503358       0  ...  0.919147   1.0    0.0  0.967796
46     1  0.471905  0.528095       0  ...  0.914966   1.0    0.0  0.962024
47     1  0.488725  0.511275       1  ...  0.913312   1.0    0.0  0.961389
48     1  0.497456  0.502544       1  ...  0.915253   1.0    0.0  0.946041
49     0  0.509185  0.490815       0  ...  0.922264   1.0    0.0  0.951288

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.793', 'enterprice': '23035.2', 'countrevence': '0', 'unrealprofit': '12356.4024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23412', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230227   155000    155959  1677484799  23423.8  23411.1 -0.000546
2023-02-27 16:00:02,255:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13544 

self.closeSec=1677485399, self.tradeDate='20230227', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23411.1', self.close='23394.2'
2023-02-27 16:10:01,609:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677485399, self.tradeDate='20230227', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23411.1', self.close='23394.2'
127.0.0.1 - - [27/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:10:01,637:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230227   152000    152959  1677482999  23405.2  23442.8  0.001606
525  20230227   153000    153959  1677483599  23442.7  23419.7 -0.000985
526  20230227   154000    154959  1677484199  23419.6  23423.9  0.000179
527  20230227   155000    155959  1677484799  23423.8  23411.1 -0.000546
528  20230227   160000    160959  1677485399  23411.1  23394.2 -0.000722
2023-02-27 16:10:01,637:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13545 

self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23394.4', self.close='23387.8'
127.0.0.1 - - [27/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:20:02,316:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23394.4', self.close='23387.8'
2023-02-27 16:20:02,417:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230227   153000    153959  1677483599  23442.7  23419.7 -0.000985
526  20230227   154000    154959  1677484199  23419.6  23423.9  0.000179
527  20230227   155000    155959  1677484799  23423.8  23411.1 -0.000546
528  20230227   160000    160959  1677485399  23411.1  23394.2 -0.000722
529  20230227   161000    161959  1677485999  23394.4  23387.8 -0.000274
2023-02-27 16:20:02,417:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230227   155000    155959  1677484799  23423.8  23411.1
2023-02-27 16:00:02,302:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13545 

self.closeSec=1677485399, self.tradeDate='20230227', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23411.1', self.close='23394.2'
127.0.0.1 - - [27/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:10:01,642:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677485399, self.tradeDate='20230227', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23411.1', self.close='23394.2'
2023-02-27 16:10:01,691:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230227   152000    152959  1677482999  23405.2  23442.8
17517  20230227   153000    153959  1677483599  23442.7  23419.7
17518  20230227   154000    154959  1677484199  23419.6  23423.9
17519  20230227   155000    155959  1677484799  23423.8  23411.1
17520  20230227   160000    160959  1677485399  23411.1  23394.2
2023-02-27 16:10:01,691:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [27/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13546 

self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23394.4', self.close='23387.8'
2023-02-27 16:20:02,651:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23394.4', self.close='23387.8'
2023-02-27 16:20:02,747:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230227   153000    153959  1677483599  23442.7  23419.7
17518  20230227   154000    154959  1677484199  23419.6  23423.9
17519  20230227   155000    155959  1677484799  23423.8  23411.1
17520  20230227   160000    160959  1677485399  23411.1  23394.2
17521  20230227   161000    161959  1677485999  23394.4  23387.8
2023-02-27 16:20:02,747:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230227   155000    155959  1677484799  23423.8  23411.1
2023-02-27 16:00:02,218:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13545 

self.closeSec=1677485399, self.tradeDate='20230227', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23411.1', self.close='23394.2'
2023-02-27 16:10:01,594:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677485399, self.tradeDate='20230227', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23411.1', self.close='23394.2'
127.0.0.1 - - [27/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:10:01,634:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230227   152000    152959  1677482999  23405.2  23442.8
12189  20230227   153000    153959  1677483599  23442.7  23419.7
12190  20230227   154000    154959  1677484199  23419.6  23423.9
12191  20230227   155000    155959  1677484799  23423.8  23411.1
12192  20230227   160000    160959  1677485399  23411.1  23394.2
2023-02-27 16:10:01,634:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13546 

self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23394.4', self.close='23387.8'
127.0.0.1 - - [27/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:20:02,665:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23394.4', self.close='23387.8'
2023-02-27 16:20:02,732:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230227   153000    153959  1677483599  23442.7  23419.7
12190  20230227   154000    154959  1677484199  23419.6  23423.9
12191  20230227   155000    155959  1677484799  23423.8  23411.1
12192  20230227   160000    160959  1677485399  23411.1  23394.2
12193  20230227   161000    161959  1677485999  23394.4  23387.8
2023-02-27 16:20:02,732:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [27/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22522
self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23376.4, self.close=23387.8, self.high=23394.0, self.low=23371.0, self.vol=791.839, self.amt=18515434.2657 
2023-02-27 16:20:01,723:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230227   155500    155959  ...         0.0        0.0       0
5952  20230227   160000    160459  ...         0.0        0.0       0
5953  20230227   160500    160959  ...         0.0        0.0       0
5954  20230227   161000    161459  ...         0.0        0.0       0
5955  20230227   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 16:20:01,727:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677485999, self.tradeDate='20230227', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23376.4, self.close=23387.8, self.high=23394.0, self.low=23371.0, self.vol=791.839, self.amt=18515434.2657, ukdf['pct'].iloc[-1]=0.000304 , ukdf['amount'].iloc[-1]=18515434.2657, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22523
self.closeSec=1677486299, self.tradeDate='20230227', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23388.4, self.close=23362.4, self.high=23396.9, self.low=23350.0, self.vol=1412.412, self.amt=33003034.3023 
127.0.0.1 - - [27/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-27 16:25:01,614:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230227   160000    160459  ...         0.0        0.0       0
5953  20230227   160500    160959  ...         0.0        0.0       0
5954  20230227   161000    161459  ...         0.0        0.0       0
5955  20230227   161500    161959  ...         0.0        0.0       0
5956  20230227   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 16:25:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677486299, self.tradeDate='20230227', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23388.4, self.close=23362.4, self.high=23396.9, self.low=23350.0, self.vol=1412.412, self.amt=33003034.3023, ukdf['pct'].iloc[-1]=-0.001086 , ukdf['amount'].iloc[-1]=33003034.3023, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230227   040000    075959  1677455999  ...    721  0.989702  0.819695     1.0
722  20230227   080000    115959  1677470399  ...    722  0.958338  0.740519     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '18267.28331708246', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23541.88953074', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=564
self.closeSec=1677484799, self.tradeDate='20230227', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23541.0, self.close=23411.1, self.high=23547.0, self.low=23331.0, self.vol=53778.498, self.amt=1260109709.1064 
127.0.0.1 - - [27/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-02-27 16:00:02,084:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677484799, self.tradeDate='20230227', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23541.0, self.close=23411.1, self.high=23547.0, self.low=23331.0, self.vol=53778.498, self.amt=1260109709.1064 
2023-02-27 16:00:02,138:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230226   200000    235959  ...   63502.842  1.473863e+09 -0.000194
720  20230227   000000    035959  ...   93742.249  2.190288e+09  0.010818
721  20230227   040000    075959  ...  102114.230  2.402483e+09  0.002307
722  20230227   080000    115959  ...   47678.291  1.121959e+09 -0.000183
723  20230227   120000    155959  ...   53778.498  1.260110e+09 -0.005518

[5 rows x 11 columns]
2023-02-27 16:00:04,664:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230226   200000    235959  1677427199  ...    719  1.023122  0.908203     1.0
720  20230227   000000    035959  1677441599  ...    720  0.995328  0.837074     1.0
721  20230227   040000    075959  1677455999  ...    721  0.989702  0.819695     1.0
722  20230227   080000    115959  1677470399  ...    722  0.958338  0.740519     1.0
723  20230227   120000    155959  1677484799  ...    723  0.893048  0.580876     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '12837.57893672401', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23413.15949019', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


