# 20230523 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [23/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2656
self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27268.4, self.close=27255.1, self.high=27274.3, self.low=27245.4, self.vol=680.682, self.amt=18555952.0047 
2023-05-23 16:20:01,428:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230523   155500    155959  ...    0.186097   0.307030       0
5952  20230523   160000    160459  ...    0.185962   0.307005       0
5953  20230523   160500    160959  ...    0.185827   0.306979       0
5954  20230523   161000    161459  ...    0.185691   0.306954       0
5955  20230523   161500    161959  ...    0.185558   0.306930       0

[5 rows x 18 columns]
2023-05-23 16:20:01,438:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27268.4, self.close=27255.1, self.high=27274.3, self.low=27245.4, self.vol=680.682, self.amt=18555952.0047, ukdf['pct'].iloc[-1]=-0.000484 , ukdf['amount'].iloc[-1]=18555952.0047, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.1855581869638121, signal=0, value_std=0.306930489844298 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5433.9252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27255.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2657
self.closeSec=1684830299, self.tradeDate='20230523', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27255.1, self.close=27254.3, self.high=27260.5, self.low=27246.6, self.vol=572.784, self.amt=15610014.1093 
2023-05-23 16:25:00,817:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230523   160000    160459  ...    0.185962   0.307005       0
5953  20230523   160500    160959  ...    0.185827   0.306979       0
5954  20230523   161000    161459  ...    0.185691   0.306954       0
5955  20230523   161500    161959  ...    0.185558   0.306930       0
5956  20230523   162000    162459  ...    0.185424   0.306906       0

[5 rows x 18 columns]
2023-05-23 16:25:00,819:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684830299, self.tradeDate='20230523', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27255.1, self.close=27254.3, self.high=27260.5, self.low=27246.6, self.vol=572.784, self.amt=15610014.1093, ukdf['pct'].iloc[-1]=-2.9e-05 , ukdf['amount'].iloc[-1]=15610014.1093, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.18542410157587005, signal=0, value_std=0.30690608480707043 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5424.177', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27254.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=43, self.factor=0.38988186941116115, self.count=2658 

self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27268.4, self.close=27255.1, self.high=27274.3, self.low=27245.4 
2023-05-23 16:20:01,189:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27268.4, self.close=27255.1, self.high=27274.3, self.low=27245.4   
2023-05-23 16:20:01,263:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230523   155500    155959  1684828799  ...  27265.7  0.001100   1631    5
1632  20230523   160000    160459  1684829099  ...  27284.2 -0.000421   1632    0
1633  20230523   160500    160959  1684829399  ...  27261.0 -0.000850   1633    1
1634  20230523   161000    161459  1684829699  ...  27250.6  0.000264   1634    2
1635  20230523   161500    161959  1684829999  ...  27245.4 -0.000484   1635    3

[5 rows x 11 columns]
2023-05-23 16:20:01,263:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=43, self.factor=0.38988186941116115, self.count=2659 

self.closeSec=1684830299, self.tradeDate='20230523', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27255.1, self.close=27254.3, self.high=27260.5, self.low=27246.6 
2023-05-23 16:25:00,776:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684830299, self.tradeDate='20230523', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27255.1, self.close=27254.3, self.high=27260.5, self.low=27246.6   
2023-05-23 16:25:00,876:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230523   160000    160459  1684829099  ...  27284.2 -0.000421   1632    0
1633  20230523   160500    160959  1684829399  ...  27261.0 -0.000850   1633    1
1634  20230523   161000    161459  1684829699  ...  27250.6  0.000264   1634    2
1635  20230523   161500    161959  1684829999  ...  27245.4 -0.000484   1635    3
1636  20230523   162000    162459  1684830299  ...  27246.6 -0.000029   1636    4

[5 rows x 11 columns]
2023-05-23 16:25:00,876:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-23 16:00:33,429:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230523    132959  27372.8  ...  49.166667  0.615303  0.317034
5787  20230523    135959  27372.0  ...  49.583333  0.615911  0.308037
5788  20230523    142959  27375.0  ...  49.583333  0.607375  0.301790
5789  20230523    145959  27348.0  ...  49.166667  0.587793  0.301022
5790  20230523    152959  27284.5  ...  48.750000  0.576843  0.303226

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-05-23 16:00:33,593:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.513280  0.486720       1  ...  0.967808   1.0    0.0  1.013142
538     1  0.495092  0.504908       0  ...  0.966853   1.0    0.0  1.012143
539     1  0.483328  0.516672       0  ...  0.964605   1.0    0.0  1.009789
540     1  0.469613  0.530387       0  ...  0.963307   1.0    0.0  1.008431
541     1  0.471811  0.528189       1  ...  0.965008   1.0    0.0  1.010211

[5 rows x 10 columns]
2023-05-23 16:00:33,612:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513355  0.486645       1  ...  0.967808   1.0    0.0  1.018033
46     1  0.495184  0.504816       0  ...  0.966853   1.0    0.0  1.015820
47     1  0.483330  0.516670       0  ...  0.964605   1.0    0.0  1.012168
48     1  0.469934  0.530066       0  ...  0.963307   1.0    0.0  1.011358
49     1  0.471811  0.528189       1  ...  0.965008   1.0    0.0  1.010211

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.741', 'enterprice': '27035', 'countrevence': '0', 'unrealprofit': '7190.6549', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27303.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230523   155000    155959  1684828799  27251.2  27295.8  0.001640
2023-05-23 16:00:02,213:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1328 

self.closeSec=1684829399, self.tradeDate='20230523', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27295.8', self.close='27261.1'
2023-05-23 16:10:01,117:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684829399, self.tradeDate='20230523', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27295.8', self.close='27261.1'
127.0.0.1 - - [23/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-23 16:10:01,151:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230523   152000    152959  1684826999  27304.5  27247.7 -0.002077
525  20230523   153000    153959  1684827599  27247.8  27249.4  0.000062
526  20230523   154000    154959  1684828199  27249.4  27251.1  0.000062
527  20230523   155000    155959  1684828799  27251.2  27295.8  0.001640
528  20230523   160000    160959  1684829399  27295.8  27261.1 -0.001271
2023-05-23 16:10:01,151:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1329 

self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27261.1', self.close='27255.1'
127.0.0.1 - - [23/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 16:20:02,216:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27261.1', self.close='27255.1'
2023-05-23 16:20:02,404:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230523   153000    153959  1684827599  27247.8  27249.4  0.000062
526  20230523   154000    154959  1684828199  27249.4  27251.1  0.000062
527  20230523   155000    155959  1684828799  27251.2  27295.8  0.001640
528  20230523   160000    160959  1684829399  27295.8  27261.1 -0.001271
529  20230523   161000    161959  1684829999  27261.1  27255.1 -0.000220
2023-05-23 16:20:02,404:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230523   155000    155959  1684828799  27251.2  27295.8
2023-05-23 16:00:02,226:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1331 

self.closeSec=1684829399, self.tradeDate='20230523', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27295.8', self.close='27261.1'
2023-05-23 16:10:01,139:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684829399, self.tradeDate='20230523', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27295.8', self.close='27261.1'
127.0.0.1 - - [23/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-23 16:10:01,168:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230523   152000    152959  1684826999  27304.5  27247.7
17517  20230523   153000    153959  1684827599  27247.8  27249.4
17518  20230523   154000    154959  1684828199  27249.4  27251.1
17519  20230523   155000    155959  1684828799  27251.2  27295.8
17520  20230523   160000    160959  1684829399  27295.8  27261.1
2023-05-23 16:10:01,169:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1332 

self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27261.1', self.close='27255.1'
127.0.0.1 - - [23/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 16:20:03,261:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27261.1', self.close='27255.1'
2023-05-23 16:20:03,325:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230523   153000    153959  1684827599  27247.8  27249.4
17518  20230523   154000    154959  1684828199  27249.4  27251.1
17519  20230523   155000    155959  1684828799  27251.2  27295.8
17520  20230523   160000    160959  1684829399  27295.8  27261.1
17521  20230523   161000    161959  1684829999  27261.1  27255.1
2023-05-23 16:20:03,326:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230523   155000    155959  1684828799  27251.2  27295.8
2023-05-23 16:00:02,230:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1331 

self.closeSec=1684829399, self.tradeDate='20230523', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27295.8', self.close='27261.1'
2023-05-23 16:10:01,127:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684829399, self.tradeDate='20230523', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27295.8', self.close='27261.1'
127.0.0.1 - - [23/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-23 16:10:01,162:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230523   152000    152959  1684826999  27304.5  27247.7
12189  20230523   153000    153959  1684827599  27247.8  27249.4
12190  20230523   154000    154959  1684828199  27249.4  27251.1
12191  20230523   155000    155959  1684828799  27251.2  27295.8
12192  20230523   160000    160959  1684829399  27295.8  27261.1
2023-05-23 16:10:01,162:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1332 

self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27261.1', self.close='27255.1'
127.0.0.1 - - [23/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 16:20:02,889:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27261.1', self.close='27255.1'
2023-05-23 16:20:03,144:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230523   153000    153959  1684827599  27247.8  27249.4
12190  20230523   154000    154959  1684828199  27249.4  27251.1
12191  20230523   155000    155959  1684828799  27251.2  27295.8
12192  20230523   160000    160959  1684829399  27295.8  27261.1
12193  20230523   161000    161959  1684829999  27261.1  27255.1
2023-05-23 16:20:03,146:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2656
self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27268.4, self.close=27255.1, self.high=27274.3, self.low=27245.4, self.vol=680.682, self.amt=18555952.0047 
127.0.0.1 - - [23/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 16:20:01,432:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230523   155500    155959  ...         0.0        0.0       0
5952  20230523   160000    160459  ...         0.0        0.0       0
5953  20230523   160500    160959  ...         0.0        0.0       0
5954  20230523   161000    161459  ...         0.0        0.0       0
5955  20230523   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-23 16:20:01,435:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684829999, self.tradeDate='20230523', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27268.4, self.close=27255.1, self.high=27274.3, self.low=27245.4, self.vol=680.682, self.amt=18555952.0047, ukdf['pct'].iloc[-1]=-0.000484 , ukdf['amount'].iloc[-1]=18555952.0047, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '15268.6651', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27255.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2657
self.closeSec=1684830299, self.tradeDate='20230523', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27255.1, self.close=27254.3, self.high=27260.5, self.low=27246.6, self.vol=572.784, self.amt=15610014.1093 
127.0.0.1 - - [23/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-23 16:25:00,912:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230523   160000    160459  ...         0.0        0.0       0
5953  20230523   160500    160959  ...         0.0        0.0       0
5954  20230523   161000    161459  ...         0.0        0.0       0
5955  20230523   161500    161959  ...         0.0        0.0       0
5956  20230523   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-23 16:25:00,914:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684830299, self.tradeDate='20230523', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27255.1, self.close=27254.3, self.high=27260.5, self.low=27246.6, self.vol=572.784, self.amt=15610014.1093, ukdf['pct'].iloc[-1]=-2.9e-05 , ukdf['amount'].iloc[-1]=15610014.1093, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '15242.6664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27254.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230523   040000    075959  1684799999  ...    721  0.070159 -1.676941    -1.0
722  20230523   080000    115959  1684814399  ...    722  0.058479 -1.698103    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '-15521.4039', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27371.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=55
self.closeSec=1684828799, self.tradeDate='20230523', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27354.7, self.close=27295.8, self.high=27527.5, self.low=27202.2, self.vol=83809.328, self.amt=2292564500.55133 
127.0.0.1 - - [23/May/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-05-23 16:00:01,782:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684828799, self.tradeDate='20230523', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27354.7, self.close=27295.8, self.high=27527.5, self.low=27202.2, self.vol=83809.328, self.amt=2292564500.55133 
2023-05-23 16:00:01,813:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230522   200000    235959  ...  129893.083  3.493352e+09  0.001614
720  20230523   000000    035959  ...   41038.257  1.101761e+09 -0.000231
721  20230523   040000    075959  ...   19533.419  5.250148e+08 -0.000626
722  20230523   080000    115959  ...  112108.995  3.042695e+09  0.019165
723  20230523   120000    155959  ...   83809.328  2.292565e+09 -0.002150

[5 rows x 11 columns]
2023-05-23 16:00:03,617:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230522   200000    235959  1684771199  ...    719  0.030624 -1.905052    -1.0
720  20230523   000000    035959  1684785599  ...    720  0.006426 -1.987827    -1.0
721  20230523   040000    075959  1684799999  ...    721  0.070159 -1.676941    -1.0
722  20230523   080000    115959  1684814399  ...    722  0.058479 -1.698103    -1.0
723  20230523   120000    155959  1684828799  ...    723  0.225133 -0.915867    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '-11681.92432700892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27297.11786508', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


