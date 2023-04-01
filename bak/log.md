# 20230401 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36028
self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28429.9, self.close=28410.0, self.high=28440.0, self.low=28395.1, self.vol=976.678, self.amt=27763584.1981 
127.0.0.1 - - [01/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-01 16:20:09,612:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230401   155500    155959  ...         0.0        0.0       0
5952  20230401   160000    160459  ...         0.0        0.0       0
5953  20230401   160500    160959  ...         0.0        0.0       0
5954  20230401   161000    161459  ...         0.0        0.0       0
5955  20230401   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 16:20:09,632:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28429.9, self.close=28410.0, self.high=28440.0, self.low=28395.1, self.vol=976.678, self.amt=27763584.1981, ukdf['pct'].iloc[-1]=-0.0007 , ukdf['amount'].iloc[-1]=27763584.1981, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-715155.6544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28413.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36029
self.closeSec=1680337499, self.tradeDate='20230401', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28410.0, self.close=28398.4, self.high=28415.0, self.low=28375.5, self.vol=1268.764, self.amt=36025991.1545 
2023-04-01 16:25:01,604:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230401   160000    160459  ...         0.0        0.0       0
5953  20230401   160500    160959  ...         0.0        0.0       0
5954  20230401   161000    161459  ...         0.0        0.0       0
5955  20230401   161500    161959  ...         0.0        0.0       0
5956  20230401   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 16:25:01,604:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680337499, self.tradeDate='20230401', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28410.0, self.close=28398.4, self.high=28415.0, self.low=28375.5, self.vol=1268.764, self.amt=36025991.1545, ukdf['pct'].iloc[-1]=-0.000408 , ukdf['amount'].iloc[-1]=36025991.1545, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-714319.208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28399.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28429.9, self.close=28410.0, self.high=28440.0, self.low=28395.1 
127.0.0.1 - - [01/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-01 16:20:06,996:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28429.9, self.close=28410.0, self.high=28440.0, self.low=28395.1   
2023-04-01 16:20:08,261:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230401   155500    155959  1680335999  ...  28412.5  0.000039   1631    5
1632  20230401   160000    160459  1680336299  ...  28399.1 -0.000310   1632    0
1633  20230401   160500    160959  1680336599  ...  28407.2  0.000743   1633    1
1634  20230401   161000    161459  1680336899  ...  28416.3  0.000053   1634    2
1635  20230401   161500    161959  1680337199  ...  28395.1 -0.000700   1635    3

[5 rows x 11 columns]
2023-04-01 16:20:08,261:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=38, self.factor=0.3309836218259289, self.count=36595 

self.closeSec=1680337499, self.tradeDate='20230401', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28410.0, self.close=28398.4, self.high=28415.0, self.low=28375.5 
2023-04-01 16:25:01,530:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680337499, self.tradeDate='20230401', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28410.0, self.close=28398.4, self.high=28415.0, self.low=28375.5   
2023-04-01 16:25:01,570:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230401   160000    160459  1680336299  ...  28399.1 -0.000310   1632    0
1633  20230401   160500    160959  1680336599  ...  28407.2  0.000743   1633    1
1634  20230401   161000    161459  1680336899  ...  28416.3  0.000053   1634    2
1635  20230401   161500    161959  1680337199  ...  28395.1 -0.000700   1635    3
1636  20230401   162000    162459  1680337499  ...  28375.5 -0.000408   1636    4

[5 rows x 11 columns]
2023-04-01 16:25:01,571:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-01 16:00:36,785:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230401    132959  28563.7  ...  51.666667  0.542280  0.251085
5787  20230401    135959  28522.0  ...  52.083333  0.547714  0.252313
5788  20230401    142959  28558.9  ...  51.666667  0.521422  0.264205
5789  20230401    145959  28415.9  ...  51.666667  0.531831  0.270746
5790  20230401    152959  28474.9  ...  51.250000  0.518127  0.282283

[5 rows x 33 columns]
0.5166051660516605
acc is : 0.5166051660516605
2023-04-01 16:00:36,951:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502926  0.497074       1  ...  0.968269   1.0    0.0  1.026051
538     0  0.523716  0.476284       0  ...  0.963048   1.0    0.0  1.020518
539     1  0.479855  0.520145       1  ...  0.965418   1.0    0.0  1.023029
540     0  0.522497  0.477503       0  ...  0.962593   1.0    0.0  1.020037
541     1  0.491076  0.508924       1  ...  0.963424   1.0    0.0  1.020917

[5 rows x 10 columns]
2023-04-01 16:00:36,990:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502939  0.497061       1  ...  0.968269   1.0    0.0  1.022257
46     0  0.523930  0.476070       0  ...  0.963048   1.0    0.0  1.021678
47     1  0.481152  0.518848       1  ...  0.965418   1.0    0.0  1.027823
48     0  0.523329  0.476671       0  ...  0.962593   1.0    0.0  1.020789
49     1  0.491076  0.508924       1  ...  0.963424   1.0    0.0  1.020917

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230401   155000    155959  1680335999    28415  28416.1  0.000039
2023-04-01 16:00:02,146:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18296 

self.closeSec=1680336599, self.tradeDate='20230401', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28416.1', self.close='28428.7'
2023-04-01 16:10:01,604:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680336599, self.tradeDate='20230401', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28416.1', self.close='28428.7'
2023-04-01 16:10:01,677:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230401   152000    152959  1680334199  28342.7  28391.6  0.001722
525  20230401   153000    153959  1680334799  28391.5  28408.1  0.000581
526  20230401   154000    154959  1680335399  28408.1    28415  0.000243
527  20230401   155000    155959  1680335999    28415  28416.1  0.000039
528  20230401   160000    160959  1680336599  28416.1  28428.7  0.000443
2023-04-01 16:10:01,677:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18297 

self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28428.7', self.close='28410'
127.0.0.1 - - [01/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-01 16:20:08,160:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28428.7', self.close='28410'
2023-04-01 16:20:08,951:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230401   153000    153959  1680334799  28391.5  28408.1  0.000581
526  20230401   154000    154959  1680335399  28408.1    28415  0.000243
527  20230401   155000    155959  1680335999    28415  28416.1  0.000039
528  20230401   160000    160959  1680336599  28416.1  28428.7  0.000443
529  20230401   161000    161959  1680337199  28428.7    28410 -0.000658
2023-04-01 16:20:08,951:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230401   155000    155959  1680335999    28415  28416.1
2023-04-01 16:00:02,162:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18297 

self.closeSec=1680336599, self.tradeDate='20230401', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28416.1', self.close='28428.7'
2023-04-01 16:10:01,620:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680336599, self.tradeDate='20230401', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28416.1', self.close='28428.7'
2023-04-01 16:10:01,669:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230401   152000    152959  1680334199  28342.7  28391.6
17517  20230401   153000    153959  1680334799  28391.5  28408.1
17518  20230401   154000    154959  1680335399  28408.1    28415
17519  20230401   155000    155959  1680335999    28415  28416.1
17520  20230401   160000    160959  1680336599  28416.1  28428.7
2023-04-01 16:10:01,678:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18298 

self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28428.7', self.close='28410'
127.0.0.1 - - [01/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-01 16:20:11,386:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28428.7', self.close='28410'
2023-04-01 16:20:11,543:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230401   153000    153959  1680334799  28391.5  28408.1
17518  20230401   154000    154959  1680335399  28408.1    28415
17519  20230401   155000    155959  1680335999    28415  28416.1
17520  20230401   160000    160959  1680336599  28416.1  28428.7
17521  20230401   161000    161959  1680337199  28428.7    28410
2023-04-01 16:20:11,544:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230401   155000    155959  1680335999    28415  28416.1
2023-04-01 16:00:02,064:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18297 

self.closeSec=1680336599, self.tradeDate='20230401', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28416.1', self.close='28428.7'
2023-04-01 16:10:01,600:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680336599, self.tradeDate='20230401', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28416.1', self.close='28428.7'
127.0.0.1 - - [01/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-01 16:10:01,616:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230401   152000    152959  1680334199  28342.7  28391.6
12189  20230401   153000    153959  1680334799  28391.5  28408.1
12190  20230401   154000    154959  1680335399  28408.1    28415
12191  20230401   155000    155959  1680335999    28415  28416.1
12192  20230401   160000    160959  1680336599  28416.1  28428.7
2023-04-01 16:10:01,616:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18298 

self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28428.7', self.close='28410'
127.0.0.1 - - [01/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-01 16:20:10,832:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28428.7', self.close='28410'
2023-04-01 16:20:11,145:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230401   153000    153959  1680334799  28391.5  28408.1
12190  20230401   154000    154959  1680335399  28408.1    28415
12191  20230401   155000    155959  1680335999    28415  28416.1
12192  20230401   160000    160959  1680336599  28416.1  28428.7
12193  20230401   161000    161959  1680337199  28428.7    28410
2023-04-01 16:20:11,145:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32026
self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28429.9, self.close=28410.0, self.high=28440.0, self.low=28395.1, self.vol=976.678, self.amt=27763584.1981 
127.0.0.1 - - [01/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-01 16:20:08,930:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230401   155500    155959  ...         0.0        0.0       0
5952  20230401   160000    160459  ...         0.0        0.0       0
5953  20230401   160500    160959  ...         0.0        0.0       0
5954  20230401   161000    161459  ...         0.0        0.0       0
5955  20230401   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 16:20:08,952:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680337199, self.tradeDate='20230401', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28429.9, self.close=28410.0, self.high=28440.0, self.low=28395.1, self.vol=976.678, self.amt=27763584.1981, ukdf['pct'].iloc[-1]=-0.0007 , ukdf['amount'].iloc[-1]=27763584.1981, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32027
self.closeSec=1680337499, self.tradeDate='20230401', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28410.0, self.close=28398.4, self.high=28415.0, self.low=28375.5, self.vol=1268.764, self.amt=36025991.1545 
2023-04-01 16:25:01,598:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230401   160000    160459  ...         0.0        0.0       0
5953  20230401   160500    160959  ...         0.0        0.0       0
5954  20230401   161000    161459  ...         0.0        0.0       0
5955  20230401   161500    161959  ...         0.0        0.0       0
5956  20230401   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 16:25:01,598:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680337499, self.tradeDate='20230401', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28410.0, self.close=28398.4, self.high=28415.0, self.low=28375.5, self.vol=1268.764, self.amt=36025991.1545, ukdf['pct'].iloc[-1]=-0.000408 , ukdf['amount'].iloc[-1]=36025991.1545, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230401   040000    075959  1680307199  ...    721  0.816670  1.124941     1.0
722  20230401   080000    115959  1680321599  ...    722  0.792670  1.040657     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '1799.2785', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28530.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [01/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1484665.736112, self.flagDict['side']='buy', self.tradeCount=28, self.count=762
self.closeSec=1680335999, self.tradeDate='20230401', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28532.1, self.close=28416.1, self.high=28617.8, self.low=28328.0, self.vol=46755.745, self.amt=1330722885.10522 
2023-04-01 16:00:01,783:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680335999, self.tradeDate='20230401', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28532.1, self.close=28416.1, self.high=28617.8, self.low=28328.0, self.vol=46755.745, self.amt=1330722885.10522 
2023-04-01 16:00:01,813:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230331   200000    235959  ...  217230.739  6.157321e+09  0.020508
720  20230401   000000    035959  ...   81724.628  2.319688e+09 -0.001408
721  20230401   040000    075959  ...   51498.288  1.466608e+09  0.000228
722  20230401   080000    115959  ...   65781.338  1.879983e+09  0.002710
723  20230401   120000    155959  ...   46755.745  1.330723e+09 -0.004062

[5 rows x 11 columns]
2023-04-01 16:00:04,477:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230331   200000    235959  1680278399  ...    719  0.648754  0.667380     1.0
720  20230401   000000    035959  1680292799  ...    720  0.851423  1.243553     1.0
721  20230401   040000    075959  1680307199  ...    721  0.816670  1.124941     1.0
722  20230401   080000    115959  1680321599  ...    722  0.792670  1.040657     1.0
723  20230401   120000    155959  1680335999  ...    723  0.730416  0.849276     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '-4167.0247', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28416.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


