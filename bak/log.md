# 20230612 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8416
self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25804.6, self.close=25834.3, self.high=25837.4, self.low=25803.0, self.vol=608.138, self.amt=15704266.6075 
127.0.0.1 - - [12/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-12 16:20:06,700:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230612   155500    155959  ...         0.0        0.0       0
5952  20230612   160000    160459  ...         0.0        0.0       0
5953  20230612   160500    160959  ...         0.0        0.0       0
5954  20230612   161000    161459  ...         0.0        0.0       0
5955  20230612   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 16:20:06,741:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25804.6, self.close=25834.3, self.high=25837.4, self.low=25803.0, self.vol=608.138, self.amt=15704266.6075, ukdf['pct'].iloc[-1]=0.001155 , ukdf['amount'].iloc[-1]=15704266.6075, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14360.0650797186', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25833.7305989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8417
self.closeSec=1686558299, self.tradeDate='20230612', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25834.3, self.close=25838.1, self.high=25846.1, self.low=25829.9, self.vol=726.009, self.amt=18758162.2613 
127.0.0.1 - - [12/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-12 16:25:04,599:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230612   160000    160459  ...         0.0        0.0       0
5953  20230612   160500    160959  ...         0.0        0.0       0
5954  20230612   161000    161459  ...         0.0        0.0       0
5955  20230612   161500    161959  ...         0.0        0.0       0
5956  20230612   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 16:25:04,604:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686558299, self.tradeDate='20230612', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25834.3, self.close=25838.1, self.high=25846.1, self.low=25829.9, self.vol=726.009, self.amt=18758162.2613, ukdf['pct'].iloc[-1]=0.000147 , ukdf['amount'].iloc[-1]=18758162.2613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14302.002', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25837.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25804.6, self.close=25834.3, self.high=25837.4, self.low=25803.0 
127.0.0.1 - - [12/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-12 16:20:04,450:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25804.6, self.close=25834.3, self.high=25837.4, self.low=25803.0   
2023-06-12 16:20:05,810:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230612   155500    155959  1686556799  ...  25761.3 -0.000225   1631    5
1632  20230612   160000    160459  1686557099  ...  25768.8  0.000364   1632    0
1633  20230612   160500    160959  1686557399  ...  25798.8  0.000508   1633    1
1634  20230612   161000    161459  1686557699  ...  25803.0 -0.000434   1634    2
1635  20230612   161500    161959  1686557999  ...  25803.0  0.001155   1635    3

[5 rows x 11 columns]
2023-06-12 16:20:05,820:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=43, self.factor=0.49819774050257065, self.count=8419 

self.closeSec=1686558299, self.tradeDate='20230612', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25834.3, self.close=25838.1, self.high=25846.1, self.low=25829.9 
127.0.0.1 - - [12/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-12 16:25:03,403:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686558299, self.tradeDate='20230612', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25834.3, self.close=25838.1, self.high=25846.1, self.low=25829.9   
2023-06-12 16:25:04,184:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230612   160000    160459  1686557099  ...  25768.8  0.000364   1632    0
1633  20230612   160500    160959  1686557399  ...  25798.8  0.000508   1633    1
1634  20230612   161000    161459  1686557699  ...  25803.0 -0.000434   1634    2
1635  20230612   161500    161959  1686557999  ...  25803.0  0.001155   1635    3
1636  20230612   162000    162459  1686558299  ...  25829.9  0.000147   1636    4

[5 rows x 11 columns]
2023-06-12 16:25:04,193:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-12 16:00:43,220:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230612    132959  25804.8  ...  49.166667  0.476643  0.519031
5787  20230612    135959  25799.2  ...  49.166667  0.467937  0.533566
5788  20230612    142959  25757.5  ...  49.583333  0.490154  0.536281
5789  20230612    145959  25855.1  ...  49.583333  0.485297  0.541364
5790  20230612    152959  25832.2  ...  49.166667  0.480776  0.548478

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-06-12 16:00:43,424:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502773  0.497227       0  ...  0.972349  -1.0    0.0  0.951877
538     1  0.487823  0.512177       1  ...  0.968669  -1.0    0.0  0.955480
539     0  0.524806  0.475194       0  ...  0.969527  -1.0    0.0  0.954634
540     1  0.499984  0.500016       0  ...  0.970326  -1.0    0.0  0.953846
541     1  0.497892  0.502108       0  ...  0.970988  -1.0    0.0  0.953196

[5 rows x 10 columns]
2023-06-12 16:00:43,467:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502789  0.497211       0  ...  0.972349  -1.0    0.0  0.948013
46     1  0.487851  0.512149       1  ...  0.968669  -1.0    0.0  0.951097
47     0  0.524575  0.475425       0  ...  0.969527  -1.0    0.0  0.949671
48     1  0.499889  0.500111       0  ...  0.970326  -1.0    0.0  0.946522
49     1  0.497892  0.502108       0  ...  0.970988  -1.0    0.0  0.953196

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-6452.96993402698', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25786.70582601', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230612   155000    155959  1686556799  25787.4  25793.3  0.000225
2023-06-12 16:00:02,382:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4208 

self.closeSec=1686557399, self.tradeDate='20230612', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25793.2', self.close='25815.7'
2023-06-12 16:10:01,154:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686557399, self.tradeDate='20230612', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25793.2', self.close='25815.7'
127.0.0.1 - - [12/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-12 16:10:01,188:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230612   152000    152959  1686554999  25822.4  25810.9 -0.000445
525  20230612   153000    153959  1686555599  25810.9  25792.4 -0.000717
526  20230612   154000    154959  1686556199  25792.4  25787.5 -0.000190
527  20230612   155000    155959  1686556799  25787.4  25793.3  0.000225
528  20230612   160000    160959  1686557399  25793.2  25815.7  0.000868
2023-06-12 16:10:01,188:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4209 

self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25815.7', self.close='25834.2'
127.0.0.1 - - [12/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-12 16:20:07,861:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25815.7', self.close='25834.2'
2023-06-12 16:20:08,760:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230612   153000    153959  1686555599  25810.9  25792.4 -0.000717
526  20230612   154000    154959  1686556199  25792.4  25787.5 -0.000190
527  20230612   155000    155959  1686556799  25787.4  25793.3  0.000225
528  20230612   160000    160959  1686557399  25793.2  25815.7  0.000868
529  20230612   161000    161959  1686557999  25815.7  25834.2  0.000717
2023-06-12 16:20:08,760:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230612   155000    155959  1686556799  25787.4  25793.3
2023-06-12 16:00:02,408:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4211 

self.closeSec=1686557399, self.tradeDate='20230612', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25793.2', self.close='25815.7'
2023-06-12 16:10:01,172:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686557399, self.tradeDate='20230612', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25793.2', self.close='25815.7'
2023-06-12 16:10:01,203:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230612   152000    152959  1686554999  25822.4  25810.9
17517  20230612   153000    153959  1686555599  25810.9  25792.4
17518  20230612   154000    154959  1686556199  25792.4  25787.5
17519  20230612   155000    155959  1686556799  25787.4  25793.3
17520  20230612   160000    160959  1686557399  25793.2  25815.7
2023-06-12 16:10:01,203:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4212 

self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25815.7', self.close='25834.2'
127.0.0.1 - - [12/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-12 16:20:09,771:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25815.7', self.close='25834.2'
2023-06-12 16:20:09,950:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230612   153000    153959  1686555599  25810.9  25792.4
17518  20230612   154000    154959  1686556199  25792.4  25787.5
17519  20230612   155000    155959  1686556799  25787.4  25793.3
17520  20230612   160000    160959  1686557399  25793.2  25815.7
17521  20230612   161000    161959  1686557999  25815.7  25834.2
2023-06-12 16:20:09,951:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230612   155000    155959  1686556799  25787.4  25793.3
2023-06-12 16:00:02,342:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4211 

self.closeSec=1686557399, self.tradeDate='20230612', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25793.2', self.close='25815.7'
2023-06-12 16:10:01,145:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686557399, self.tradeDate='20230612', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25793.2', self.close='25815.7'
127.0.0.1 - - [12/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-12 16:10:01,157:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230612   152000    152959  1686554999  25822.4  25810.9
12189  20230612   153000    153959  1686555599  25810.9  25792.4
12190  20230612   154000    154959  1686556199  25792.4  25787.5
12191  20230612   155000    155959  1686556799  25787.4  25793.3
12192  20230612   160000    160959  1686557399  25793.2  25815.7
2023-06-12 16:10:01,157:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4212 

self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25815.7', self.close='25834.2'
127.0.0.1 - - [12/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-12 16:20:09,452:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25815.7', self.close='25834.2'
2023-06-12 16:20:09,785:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230612   153000    153959  1686555599  25810.9  25792.4
12190  20230612   154000    154959  1686556199  25792.4  25787.5
12191  20230612   155000    155959  1686556799  25787.4  25793.3
12192  20230612   160000    160959  1686557399  25793.2  25815.7
12193  20230612   161000    161959  1686557999  25815.7  25834.2
2023-06-12 16:20:09,789:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8416
self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25804.6, self.close=25834.3, self.high=25837.4, self.low=25803.0, self.vol=608.138, self.amt=15704266.6075 
127.0.0.1 - - [12/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-12 16:20:06,970:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230612   155500    155959  ...         0.0        0.0       0
5952  20230612   160000    160459  ...         0.0        0.0       0
5953  20230612   160500    160959  ...         0.0        0.0       0
5954  20230612   161000    161459  ...         0.0        0.0       0
5955  20230612   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 16:20:07,000:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686557999, self.tradeDate='20230612', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25804.6, self.close=25834.3, self.high=25837.4, self.low=25803.0, self.vol=608.138, self.amt=15704266.6075, ukdf['pct'].iloc[-1]=0.001155 , ukdf['amount'].iloc[-1]=15704266.6075, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37522.4158262551', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25833.7305989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8417
self.closeSec=1686558299, self.tradeDate='20230612', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25834.3, self.close=25838.1, self.high=25846.1, self.low=25829.9, self.vol=726.009, self.amt=18758162.2613 
127.0.0.1 - - [12/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-12 16:25:04,594:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230612   160000    160459  ...         0.0        0.0       0
5953  20230612   160500    160959  ...         0.0        0.0       0
5954  20230612   161000    161459  ...         0.0        0.0       0
5955  20230612   161500    161959  ...         0.0        0.0       0
5956  20230612   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 16:25:04,600:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686558299, self.tradeDate='20230612', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25834.3, self.close=25838.1, self.high=25846.1, self.low=25829.9, self.vol=726.009, self.amt=18758162.2613, ukdf['pct'].iloc[-1]=0.000147 , ukdf['amount'].iloc[-1]=18758162.2613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37367.5601', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25837.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230612   040000    075959  1686527999  ...    721  0.464084 -0.433618     NaN
722  20230612   080000    115959  1686542399  ...    722  0.459192 -0.456180     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '71638.58955827464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25779.99960196', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [12/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=175
self.closeSec=1686556799, self.tradeDate='20230612', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25779.6, self.close=25793.2, self.high=25896.0, self.low=25729.9, self.vol=30360.911, self.amt=783432674.10338 
2023-06-12 16:00:01,907:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686556799, self.tradeDate='20230612', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25779.6, self.close=25793.2, self.high=25896.0, self.low=25729.9, self.vol=30360.911, self.amt=783432674.10338 
2023-06-12 16:00:01,968:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230611   200000    235959  ...  28819.212  7.417487e+08 -0.001695
720  20230612   000000    035959  ...  85800.036  2.226062e+09  0.010870
721  20230612   040000    075959  ...  74781.740  1.942771e+09 -0.004270
722  20230612   080000    115959  ...  67095.778  1.732531e+09 -0.005029
723  20230612   120000    155959  ...  30360.911  7.834327e+08  0.000528

[5 rows x 11 columns]
2023-06-12 16:00:04,092:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230611   200000    235959  1686499199  ...    719  0.493000 -0.328305     NaN
720  20230612   000000    035959  1686513599  ...    720  0.484214 -0.360866     NaN
721  20230612   040000    075959  1686527999  ...    721  0.464084 -0.433618     NaN
722  20230612   080000    115959  1686542399  ...    722  0.459192 -0.456180     NaN
723  20230612   120000    155959  1686556799  ...    723  0.472319 -0.417763     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '70960.0258', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25792.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


