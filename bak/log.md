# 20230628 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13024
self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30171.9, self.close=30239.8, self.high=30241.7, self.low=30153.7, self.vol=2263.929, self.amt=68383767.683 
127.0.0.1 - - [28/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-28 16:20:07,144:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230628   155500    155959  ...         0.0        0.0       0
5952  20230628   160000    160459  ...         0.0        0.0       0
5953  20230628   160500    160959  ...         0.0        0.0       0
5954  20230628   161000    161459  ...         0.0        0.0       0
5955  20230628   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 16:20:07,184:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30171.9, self.close=30239.8, self.high=30241.7, self.low=30153.7, self.vol=2263.929, self.amt=68383767.683, ukdf['pct'].iloc[-1]=0.00225 , ukdf['amount'].iloc[-1]=68383767.683, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-46922.1842572626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30234.2942451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13025
self.closeSec=1687940699, self.tradeDate='20230628', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30238.4, self.close=30238.0, self.high=30244.1, self.low=30219.9, self.vol=1317.804, self.amt=39838151.6059 
2023-06-28 16:25:00,748:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230628   160000    160459  ...         0.0        0.0       0
5953  20230628   160500    160959  ...         0.0        0.0       0
5954  20230628   161000    161459  ...         0.0        0.0       0
5955  20230628   161500    161959  ...         0.0        0.0       0
5956  20230628   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 16:25:00,748:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687940699, self.tradeDate='20230628', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30238.4, self.close=30238.0, self.high=30244.1, self.low=30219.9, self.vol=1317.804, self.amt=39838151.6059, ukdf['pct'].iloc[-1]=-6e-05 , ukdf['amount'].iloc[-1]=39838151.6059, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-46973.62856695146', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30237.98836471', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30171.9, self.close=30239.8, self.high=30241.7, self.low=30153.7 
127.0.0.1 - - [28/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-28 16:20:04,888:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30171.9, self.close=30239.8, self.high=30241.7, self.low=30153.7   
2023-06-28 16:20:06,244:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230628   155500    155959  1687939199  ...  30170.0 -0.000268   1631    5
1632  20230628   160000    160459  1687939499  ...  30126.6 -0.000653   1632    0
1633  20230628   160500    160959  1687939799  ...  30146.5  0.000839   1633    1
1634  20230628   161000    161459  1687940099  ...  30144.9 -0.000355   1634    2
1635  20230628   161500    161959  1687940399  ...  30153.7  0.002250   1635    3

[5 rows x 11 columns]
2023-06-28 16:20:06,254:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=5, self.factor=0.5484092142758514, self.count=13027 

self.closeSec=1687940699, self.tradeDate='20230628', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30238.4, self.close=30238.0, self.high=30244.1, self.low=30219.9 
2023-06-28 16:25:00,718:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687940699, self.tradeDate='20230628', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30238.4, self.close=30238.0, self.high=30244.1, self.low=30219.9   
2023-06-28 16:25:00,747:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230628   160000    160459  1687939499  ...  30126.6 -0.000653   1632    0
1633  20230628   160500    160959  1687939799  ...  30146.5  0.000839   1633    1
1634  20230628   161000    161459  1687940099  ...  30144.9 -0.000355   1634    2
1635  20230628   161500    161959  1687940399  ...  30153.7  0.002250   1635    3
1636  20230628   162000    162459  1687940699  ...  30219.9 -0.000060   1636    4

[5 rows x 11 columns]
2023-06-28 16:25:00,747:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-28 16:00:18,159:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230628    132959  30466.7  ...  48.333333  0.491097  0.582130
5787  20230628    135959  30427.7  ...  48.750000  0.492639  0.597417
5788  20230628    142959  30436.9  ...  48.333333  0.483654  0.616955
5789  20230628    145959  30382.2  ...  48.333333  0.479705  0.637521
5790  20230628    152959  30358.0  ...  48.333333  0.475108  0.656053

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2023-06-28 16:00:18,253:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.503393  0.496607       1  ...  1.048362  -1.0    0.0  1.157204
538     0  0.506489  0.493511       0  ...  1.050246  -1.0    0.0  1.155124
539     1  0.489799  0.510201       0  ...  1.051083  -1.0    0.0  1.154204
540     1  0.493465  0.506535       0  ...  1.052056  -1.0    0.0  1.153136
541     1  0.487614  0.512386       0  ...  1.057360  -1.0    0.0  1.147323

[5 rows x 10 columns]
2023-06-28 16:00:18,277:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503693  0.496307       1  ...  1.048362  -1.0    0.0  1.154838
46     0  0.506930  0.493070       0  ...  1.050246  -1.0    0.0  1.154045
47     1  0.489761  0.510239       0  ...  1.051083  -1.0    0.0  1.152719
48     1  0.493791  0.506209       0  ...  1.052056  -1.0    0.0  1.152326
49     1  0.487614  0.512386       0  ...  1.057360  -1.0    0.0  1.147323

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.381', 'enterprice': '30103.1', 'countrevence': '0', 'unrealprofit': '-1834.527', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30170.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230628   155000    155959  1687939199  30240.2    30176 -0.002120
2023-06-28 16:00:02,115:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6512 

self.closeSec=1687939799, self.tradeDate='20230628', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30176', self.close='30182.6'
2023-06-28 16:10:01,084:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687939799, self.tradeDate='20230628', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30176', self.close='30182.6'
2023-06-28 16:10:01,133:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230628   152000    152959  1687937399  30317.4  30329.9  0.000416
525  20230628   153000    153959  1687937999  30331.3  30249.9 -0.002638
526  20230628   154000    154959  1687938599  30249.9  30240.1 -0.000324
527  20230628   155000    155959  1687939199  30240.2    30176 -0.002120
528  20230628   160000    160959  1687939799    30176  30182.6  0.000219
2023-06-28 16:10:01,133:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6513 

self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30182.6', self.close='30239.8'
127.0.0.1 - - [28/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-28 16:20:07,335:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30182.6', self.close='30239.8'
2023-06-28 16:20:08,034:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230628   153000    153959  1687937999  30331.3  30249.9 -0.002638
526  20230628   154000    154959  1687938599  30249.9  30240.1 -0.000324
527  20230628   155000    155959  1687939199  30240.2    30176 -0.002120
528  20230628   160000    160959  1687939799    30176  30182.6  0.000219
529  20230628   161000    161959  1687940399  30182.6  30239.8  0.001895
2023-06-28 16:20:08,034:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230628   155000    155959  1687939199  30240.2    30176
2023-06-28 16:00:02,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6515 

self.closeSec=1687939799, self.tradeDate='20230628', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30176', self.close='30182.6'
127.0.0.1 - - [28/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-28 16:10:01,105:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687939799, self.tradeDate='20230628', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30176', self.close='30182.6'
2023-06-28 16:10:01,139:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230628   152000    152959  1687937399  30317.4  30329.9
17517  20230628   153000    153959  1687937999  30331.3  30249.9
17518  20230628   154000    154959  1687938599  30249.9  30240.1
17519  20230628   155000    155959  1687939199  30240.2    30176
17520  20230628   160000    160959  1687939799    30176  30182.6
2023-06-28 16:10:01,140:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6516 

self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30182.6', self.close='30239.8'
127.0.0.1 - - [28/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-28 16:20:09,015:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30182.6', self.close='30239.8'
2023-06-28 16:20:09,144:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230628   153000    153959  1687937999  30331.3  30249.9
17518  20230628   154000    154959  1687938599  30249.9  30240.1
17519  20230628   155000    155959  1687939199  30240.2    30176
17520  20230628   160000    160959  1687939799    30176  30182.6
17521  20230628   161000    161959  1687940399  30182.6  30239.8
2023-06-28 16:20:09,145:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230628   155000    155959  1687939199  30240.2    30176
2023-06-28 16:00:02,123:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6515 

self.closeSec=1687939799, self.tradeDate='20230628', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30176', self.close='30182.6'
2023-06-28 16:10:01,073:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687939799, self.tradeDate='20230628', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30176', self.close='30182.6'
2023-06-28 16:10:01,120:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230628   152000    152959  1687937399  30317.4  30329.9
12189  20230628   153000    153959  1687937999  30331.3  30249.9
12190  20230628   154000    154959  1687938599  30249.9  30240.1
12191  20230628   155000    155959  1687939199  30240.2    30176
12192  20230628   160000    160959  1687939799    30176  30182.6
2023-06-28 16:10:01,120:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6516 

self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30182.6', self.close='30239.8'
127.0.0.1 - - [28/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-28 16:20:08,578:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30182.6', self.close='30239.8'
2023-06-28 16:20:08,885:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230628   153000    153959  1687937999  30331.3  30249.9
12190  20230628   154000    154959  1687938599  30249.9  30240.1
12191  20230628   155000    155959  1687939199  30240.2    30176
12192  20230628   160000    160959  1687939799    30176  30182.6
12193  20230628   161000    161959  1687940399  30182.6  30239.8
2023-06-28 16:20:08,885:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13024
self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30171.9, self.close=30239.8, self.high=30241.7, self.low=30153.7, self.vol=2263.929, self.amt=68383767.683 
127.0.0.1 - - [28/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-28 16:20:07,294:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230628   155500    155959  ...         0.0        0.0       0
5952  20230628   160000    160459  ...         0.0        0.0       0
5953  20230628   160500    160959  ...         0.0        0.0       0
5954  20230628   161000    161459  ...         0.0        0.0       0
5955  20230628   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 16:20:07,325:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687940399, self.tradeDate='20230628', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30171.9, self.close=30239.8, self.high=30241.7, self.low=30153.7, self.vol=2263.929, self.amt=68383767.683, ukdf['pct'].iloc[-1]=0.00225 , ukdf['amount'].iloc[-1]=68383767.683, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '125918.9185572591', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30234.2942451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13025
self.closeSec=1687940699, self.tradeDate='20230628', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30238.4, self.close=30238.0, self.high=30244.1, self.low=30219.9, self.vol=1317.804, self.amt=39838151.6059 
127.0.0.1 - - [28/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-28 16:25:00,746:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230628   160000    160459  ...         0.0        0.0       0
5953  20230628   160500    160959  ...         0.0        0.0       0
5954  20230628   161000    161459  ...         0.0        0.0       0
5955  20230628   161500    161959  ...         0.0        0.0       0
5956  20230628   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-28 16:25:00,747:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687940699, self.tradeDate='20230628', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30238.4, self.close=30238.0, self.high=30244.1, self.low=30219.9, self.vol=1317.804, self.amt=39838151.6059, ukdf['pct'].iloc[-1]=-6e-05 , ukdf['amount'].iloc[-1]=39838151.6059, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126056.12185369411', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30237.98836471', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230628   040000    075959  1687910399  ...    721  0.263494 -0.758499    -1.0
722  20230628   080000    115959  1687924799  ...    722  0.244068 -0.802369    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '14382.59030579604', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30436.99567647', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=271
self.closeSec=1687939199, self.tradeDate='20230628', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30441.8, self.close=30177.0, self.high=30479.5, self.low=30127.0, self.vol=53843.36, self.amt=1631942355.86336 
127.0.0.1 - - [28/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-28 16:00:01,677:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687939199, self.tradeDate='20230628', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30441.8, self.close=30177.0, self.high=30479.5, self.low=30127.0, self.vol=53843.36, self.amt=1631942355.86336 
2023-06-28 16:00:01,703:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230627   200000    235959  ...  147090.862  4.514834e+09 -0.007575
720  20230628   000000    035959  ...   57462.807  1.760219e+09  0.004953
721  20230628   040000    075959  ...   42008.165  1.286968e+09  0.001462
722  20230628   080000    115959  ...   52611.526  1.604522e+09 -0.007867
723  20230628   120000    155959  ...   53843.360  1.631942e+09 -0.008699

[5 rows x 11 columns]
2023-06-28 16:00:03,081:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230627   200000    235959  1687881599  ...    719  0.026213 -1.386319    -1.0
720  20230628   000000    035959  1687895999  ...    720  0.424090 -0.345511     NaN
721  20230628   040000    075959  1687910399  ...    721  0.263494 -0.758499    -1.0
722  20230628   080000    115959  1687924799  ...    722  0.244068 -0.802369    -1.0
723  20230628   120000    155959  1687939199  ...    723  0.254736 -0.770019    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '28285.308', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


