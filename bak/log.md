# 20230331 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35740
self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27770.3, self.close=27738.2, self.high=27804.6, self.low=27733.0, self.vol=1852.453, self.amt=51445984.073 
127.0.0.1 - - [31/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-31 16:20:08,938:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230331   155500    155959  ...         0.0        0.0       0
5952  20230331   160000    160459  ...         0.0        0.0       0
5953  20230331   160500    160959  ...         0.0        0.0       0
5954  20230331   161000    161459  ...         0.0        0.0       0
5955  20230331   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 16:20:08,947:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27770.3, self.close=27738.2, self.high=27804.6, self.low=27733.0, self.vol=1852.453, self.amt=51445984.073, ukdf['pct'].iloc[-1]=-0.001145 , ukdf['amount'].iloc[-1]=51445984.073, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-674681.2768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27741.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [31/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35741
self.closeSec=1680251099, self.tradeDate='20230331', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27738.2, self.close=27747.5, self.high=27764.4, self.low=27695.0, self.vol=2495.965, self.amt=69203497.9438 
2023-03-31 16:25:01,648:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230331   160000    160459  ...         0.0        0.0       0
5953  20230331   160500    160959  ...         0.0        0.0       0
5954  20230331   161000    161459  ...         0.0        0.0       0
5955  20230331   161500    161959  ...         0.0        0.0       0
5956  20230331   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 16:25:01,649:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680251099, self.tradeDate='20230331', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27738.2, self.close=27747.5, self.high=27764.4, self.low=27695.0, self.vol=2495.965, self.amt=69203497.9438, ukdf['pct'].iloc[-1]=0.000335 , ukdf['amount'].iloc[-1]=69203497.9438, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-675083.23344994176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27747.77968376', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27770.3, self.close=27738.2, self.high=27804.6, self.low=27733.0 
127.0.0.1 - - [31/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-31 16:20:06,356:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27770.3, self.close=27738.2, self.high=27804.6, self.low=27733.0   
2023-03-31 16:20:07,696:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230331   155500    155959  1680249599  ...  27700.0  0.000390   1631    5
1632  20230331   160000    160459  1680249899  ...  27701.0  0.002048   1632    0
1633  20230331   160500    160959  1680250199  ...  27750.0  0.000435   1633    1
1634  20230331   161000    161459  1680250499  ...  27770.0 -0.001158   1634    2
1635  20230331   161500    161959  1680250799  ...  27733.0 -0.001145   1635    3

[5 rows x 11 columns]
2023-03-31 16:20:07,705:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=72, self.factor=0.5645871287464876, self.count=36307 

self.closeSec=1680251099, self.tradeDate='20230331', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27738.2, self.close=27747.5, self.high=27764.4, self.low=27695.0 
2023-03-31 16:25:01,540:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680251099, self.tradeDate='20230331', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27738.2, self.close=27747.5, self.high=27764.4, self.low=27695.0   
2023-03-31 16:25:01,622:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230331   160000    160459  1680249899  ...  27701.0  0.002048   1632    0
1633  20230331   160500    160959  1680250199  ...  27750.0  0.000435   1633    1
1634  20230331   161000    161459  1680250499  ...  27770.0 -0.001158   1634    2
1635  20230331   161500    161959  1680250799  ...  27733.0 -0.001145   1635    3
1636  20230331   162000    162459  1680251099  ...  27695.0  0.000335   1636    4

[5 rows x 11 columns]
2023-03-31 16:25:01,623:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

5787  20230331    135959  28128.2  ...  50.416667  0.485790  0.608912
5788  20230331    142959  28025.4  ...  50.833333  0.490261  0.608985
5789  20230331    145959  28056.5  ...  51.250000  0.491798  0.608368
5790  20230331    152959  28067.1  ...  50.833333  0.456021  0.625256

[5 rows x 33 columns]
0.514760147601476
acc is : 0.514760147601476
2023-03-31 16:00:35,819:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.519392  0.480608       0  ...  0.979306   1.0  0.0000  1.007564
538     1  0.492333  0.507667       1  ...  0.980393   1.0  0.0000  1.008682
539     0  0.527418  0.472582       1  ...  0.980764   1.0  0.0000  1.009063
540     0  0.523477  0.476523       0  ...  0.971318   1.0  0.0000  0.999346
541     1  0.446520  0.553480       0  ...  0.971983  -1.0 -0.0016  0.997063

[5 rows x 10 columns]
2023-03-31 16:00:35,856:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.519048  0.480952       0  ...  0.964146   1.0  0.0000  0.997331
46     1  0.491970  0.508030       1  ...  0.965216   1.0  0.0000  0.994189
47     0  0.527276  0.472724       1  ...  0.999693   1.0  0.0000  1.003985
48     0  0.522873  0.477127       0  ...  0.971318   1.0  0.0000  0.993555
49     1  0.446520  0.553480       0  ...  0.971983  -1.0 -0.0016  0.997063

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-03-31 16:00:36,093:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '27.579', 'sell' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:764167.81876655313', 'result': 'success', 'clientorderid': ''}
2023-03-31 16:00:36,111:INFO:logic:main.py:494:insertFactor:885513: curDateTime:3311600, name:logic, symbol:BTCUSDT, tradeDate:20230331, closeTime:155959, close:27733.3, sign:-1, total:767183.2585902, side:sell  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230331   155000    155959  1680249599  27650.7  27733.3  0.002273
2023-03-31 16:00:02,140:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [31/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18152 

self.closeSec=1680250199, self.tradeDate='20230331', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27733.3', self.close='27802.2'
2023-03-31 16:10:01,602:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680250199, self.tradeDate='20230331', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27733.3', self.close='27802.2'
2023-03-31 16:10:01,669:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230331   152000    152959  1680247799  27838.8  27796.8 -0.001509
525  20230331   153000    153959  1680248399  27796.9  27575.9 -0.007947
526  20230331   154000    154959  1680248999  27552.8  27670.4  0.003427
527  20230331   155000    155959  1680249599  27650.7  27733.3  0.002273
528  20230331   160000    160959  1680250199  27733.3  27802.2  0.002484
2023-03-31 16:10:01,670:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18153 

self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27802.2', self.close='27738.2'
127.0.0.1 - - [31/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-31 16:20:07,696:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27802.2', self.close='27738.2'
2023-03-31 16:20:08,609:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230331   153000    153959  1680248399  27796.9  27575.9 -0.007947
526  20230331   154000    154959  1680248999  27552.8  27670.4  0.003427
527  20230331   155000    155959  1680249599  27650.7  27733.3  0.002273
528  20230331   160000    160959  1680250199  27733.3  27802.2  0.002484
529  20230331   161000    161959  1680250799  27802.2  27738.2 -0.002302
2023-03-31 16:20:08,610:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230331   155000    155959  1680249599  27650.7  27733.3
2023-03-31 16:00:02,221:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18153 

self.closeSec=1680250199, self.tradeDate='20230331', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27733.3', self.close='27802.2'
127.0.0.1 - - [31/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-31 16:10:01,644:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680250199, self.tradeDate='20230331', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27733.3', self.close='27802.2'
2023-03-31 16:10:01,674:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230331   152000    152959  1680247799  27838.8  27796.8
17517  20230331   153000    153959  1680248399  27796.9  27575.9
17518  20230331   154000    154959  1680248999  27552.8  27670.4
17519  20230331   155000    155959  1680249599  27650.7  27733.3
17520  20230331   160000    160959  1680250199  27733.3  27802.2
2023-03-31 16:10:01,674:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18154 

self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27802.2', self.close='27738.2'
127.0.0.1 - - [31/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-31 16:20:10,231:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27802.2', self.close='27738.2'
2023-03-31 16:20:10,364:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230331   153000    153959  1680248399  27796.9  27575.9
17518  20230331   154000    154959  1680248999  27552.8  27670.4
17519  20230331   155000    155959  1680249599  27650.7  27733.3
17520  20230331   160000    160959  1680250199  27733.3  27802.2
17521  20230331   161000    161959  1680250799  27802.2  27738.2
2023-03-31 16:20:10,365:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230331   155000    155959  1680249599  27650.7  27733.3
2023-03-31 16:00:02,158:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [31/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18153 

self.closeSec=1680250199, self.tradeDate='20230331', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27733.3', self.close='27802.2'
2023-03-31 16:10:01,630:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680250199, self.tradeDate='20230331', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27733.3', self.close='27802.2'
2023-03-31 16:10:01,673:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230331   152000    152959  1680247799  27838.8  27796.8
12189  20230331   153000    153959  1680248399  27796.9  27575.9
12190  20230331   154000    154959  1680248999  27552.8  27670.4
12191  20230331   155000    155959  1680249599  27650.7  27733.3
12192  20230331   160000    160959  1680250199  27733.3  27802.2
2023-03-31 16:10:01,673:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18154 

self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27802.2', self.close='27738.2'
127.0.0.1 - - [31/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-31 16:20:09,720:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27802.2', self.close='27738.2'
2023-03-31 16:20:10,029:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230331   153000    153959  1680248399  27796.9  27575.9
12190  20230331   154000    154959  1680248999  27552.8  27670.4
12191  20230331   155000    155959  1680249599  27650.7  27733.3
12192  20230331   160000    160959  1680250199  27733.3  27802.2
12193  20230331   161000    161959  1680250799  27802.2  27738.2
2023-03-31 16:20:10,030:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31738
self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27770.3, self.close=27738.2, self.high=27804.6, self.low=27733.0, self.vol=1852.453, self.amt=51445984.073 
127.0.0.1 - - [31/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-31 16:20:06,846:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230331   155500    155959  ...         0.0        0.0       0
5952  20230331   160000    160459  ...         0.0        0.0       0
5953  20230331   160500    160959  ...         0.0        0.0       0
5954  20230331   161000    161459  ...         0.0        0.0       0
5955  20230331   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 16:20:06,876:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680250799, self.tradeDate='20230331', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27770.3, self.close=27738.2, self.high=27804.6, self.low=27733.0, self.vol=1852.453, self.amt=51445984.073, ukdf['pct'].iloc[-1]=-0.001145 , ukdf['amount'].iloc[-1]=51445984.073, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [31/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31739
self.closeSec=1680251099, self.tradeDate='20230331', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27738.2, self.close=27747.5, self.high=27764.4, self.low=27695.0, self.vol=2495.965, self.amt=69203497.9438 
2023-03-31 16:25:01,582:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230331   160000    160459  ...         0.0        0.0       0
5953  20230331   160500    160959  ...         0.0        0.0       0
5954  20230331   161000    161459  ...         0.0        0.0       0
5955  20230331   161500    161959  ...         0.0        0.0       0
5956  20230331   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 16:25:01,582:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680251099, self.tradeDate='20230331', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27738.2, self.close=27747.5, self.high=27764.4, self.low=27695.0, self.vol=2495.965, self.amt=69203497.9438, ukdf['pct'].iloc[-1]=0.000335 , ukdf['amount'].iloc[-1]=69203497.9438, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230331   040000    075959  1680220799  ...    721  0.604340  0.486068     NaN
722  20230331   080000    115959  1680235199  ...    722  0.607554  0.514258     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-3451.1224121655', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28155.35953175', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [31/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=756
self.closeSec=1680249599, self.tradeDate='20230331', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28152.2, self.close=27733.3, self.high=28214.8, self.low=27500.0, self.vol=101966.835, self.amt=2840422191.95997 
2023-03-31 16:00:02,030:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680249599, self.tradeDate='20230331', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28152.2, self.close=27733.3, self.high=28214.8, self.low=27500.0, self.vol=101966.835, self.amt=2840422191.95997 
2023-03-31 16:00:02,073:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230330   200000    235959  ...  132432.531  3.763736e+09 -0.012068
720  20230331   000000    035959  ...  176918.772  4.948472e+09 -0.011077
721  20230331   040000    075959  ...   73207.708  2.050605e+09  0.001562
722  20230331   080000    115959  ...   82802.246  2.332319e+09  0.004901
723  20230331   120000    155959  ...  101966.835  2.840422e+09 -0.014883

[5 rows x 11 columns]
2023-03-31 16:00:04,520:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230330   200000    235959  1680191999  ...    719  0.600231  0.430188     NaN
720  20230331   000000    035959  1680206399  ...    720  0.601653  0.457105     NaN
721  20230331   040000    075959  1680220799  ...    721  0.604340  0.486068     NaN
722  20230331   080000    115959  1680235199  ...    722  0.607554  0.514258     NaN
723  20230331   120000    155959  1680249599  ...    723  0.615690  0.553546     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '19935.6672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27719.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


