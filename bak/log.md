# 20230715 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17920
self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30288.4, self.close=30292.5, self.high=30292.5, self.low=30258.9, self.vol=805.004, self.amt=24373609.7464 
127.0.0.1 - - [15/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-15 16:20:06,220:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230715   155500    155959  ...         0.0        0.0       0
5952  20230715   160000    160459  ...         0.0        0.0       0
5953  20230715   160500    160959  ...         0.0        0.0       0
5954  20230715   161000    161459  ...         0.0        0.0       0
5955  20230715   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 16:20:06,241:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30288.4, self.close=30292.5, self.high=30292.5, self.low=30258.9, self.vol=805.004, self.amt=24373609.7464, ukdf['pct'].iloc[-1]=0.000135 , ukdf['amount'].iloc[-1]=24373609.7464, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47732.7576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30292.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17921
self.closeSec=1689409499, self.tradeDate='20230715', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30292.5, self.close=30274.6, self.high=30292.5, self.low=30269.8, self.vol=560.275, self.amt=16964653.7253 
2023-07-15 16:25:00,730:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230715   160000    160459  ...         0.0        0.0       0
5953  20230715   160500    160959  ...         0.0        0.0       0
5954  20230715   161000    161459  ...         0.0        0.0       0
5955  20230715   161500    161959  ...         0.0        0.0       0
5956  20230715   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 16:25:00,730:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689409499, self.tradeDate='20230715', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30292.5, self.close=30274.6, self.high=30292.5, self.low=30269.8, self.vol=560.275, self.amt=16964653.7253, ukdf['pct'].iloc[-1]=-0.000591 , ukdf['amount'].iloc[-1]=16964653.7253, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47484.81548025336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30274.69574036', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30288.4, self.close=30292.5, self.high=30292.5, self.low=30258.9 
127.0.0.1 - - [15/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-15 16:20:04,171:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30288.4, self.close=30292.5, self.high=30292.5, self.low=30258.9   
2023-07-15 16:20:05,491:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230715   155500    155959  1689407999  ...  30316.2 -0.000445   1631    5
1632  20230715   160000    160459  1689408299  ...  30292.0 -0.000759   1632    0
1633  20230715   160500    160959  1689408599  ...  30288.1 -0.000218   1633    1
1634  20230715   161000    161459  1689408899  ...  30288.1  0.000010   1634    2
1635  20230715   161500    161959  1689409199  ...  30258.9  0.000135   1635    3

[5 rows x 11 columns]
2023-07-15 16:20:05,503:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6535184242180794, self.count=17923 

self.closeSec=1689409499, self.tradeDate='20230715', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30292.5, self.close=30274.6, self.high=30292.5, self.low=30269.8 
127.0.0.1 - - [15/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-15 16:25:00,702:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689409499, self.tradeDate='20230715', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30292.5, self.close=30274.6, self.high=30292.5, self.low=30269.8   
2023-07-15 16:25:00,744:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230715   160000    160459  1689408299  ...  30292.0 -0.000759   1632    0
1633  20230715   160500    160959  1689408599  ...  30288.1 -0.000218   1633    1
1634  20230715   161000    161459  1689408899  ...  30288.1  0.000010   1634    2
1635  20230715   161500    161959  1689409199  ...  30258.9  0.000135   1635    3
1636  20230715   162000    162459  1689409499  ...  30269.8 -0.000591   1636    4

[5 rows x 11 columns]
2023-07-15 16:25:00,744:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-15 16:00:20,429:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230715    132959  30283.0  ...  55.000000  0.420890  0.723858
5787  20230715    135959  30252.4  ...  55.416667  0.426249  0.724243
5788  20230715    142959  30279.0  ...  55.416667  0.427080  0.724418
5789  20230715    145959  30283.1  ...  55.833333  0.430487  0.723838
5790  20230715    152959  30299.8  ...  55.833333  0.432582  0.722844

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-07-15 16:00:20,578:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495167  0.504833       1  ...  0.987130  -1.0    0.0  0.973517
538     0  0.513083  0.486917       1  ...  0.986997  -1.0    0.0  0.973649
539     0  0.511479  0.488521       1  ...  0.986456  -1.0    0.0  0.974182
540     0  0.510013  0.489987       1  ...  0.986127  -1.0    0.0  0.974507
541     0  0.512164  0.487836       1  ...  0.985870  -1.0    0.0  0.974761

[5 rows x 10 columns]
2023-07-15 16:00:20,596:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493959  0.506041       1  ...  1.000472  -1.0    0.0  0.973204
46     0  0.512150  0.487850       1  ...  0.986997  -1.0    0.0  0.973486
47     0  0.510838  0.489162       1  ...  0.999789  -1.0    0.0  0.972734
48     0  0.509109  0.490891       1  ...  0.986127  -1.0    0.0  0.973324
49     0  0.512164  0.487836       1  ...  0.985870  -1.0    0.0  0.974761

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.927', 'enterprice': '30608.5', 'countrevence': '0', 'unrealprofit': '6924.4738', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30319.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230715   155000    155959  1689407999    30325  30317.6 -0.000241
2023-07-15 16:00:02,184:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8960 

self.closeSec=1689408599, self.tradeDate='20230715', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30317.7', self.close='30288.2'
2023-07-15 16:10:01,170:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689408599, self.tradeDate='20230715', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30317.7', self.close='30288.2'
127.0.0.1 - - [15/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-15 16:10:01,196:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230715   152000    152959  1689406199  30318.7  30309.8 -0.000294
525  20230715   153000    153959  1689406799  30309.8  30327.6  0.000587
526  20230715   154000    154959  1689407399  30327.6  30324.9 -0.000089
527  20230715   155000    155959  1689407999    30325  30317.6 -0.000241
528  20230715   160000    160959  1689408599  30317.7  30288.2 -0.000970
2023-07-15 16:10:01,196:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8961 

self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30288.2', self.close='30292.5'
127.0.0.1 - - [15/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-15 16:20:06,519:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30288.2', self.close='30292.5'
2023-07-15 16:20:07,229:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230715   153000    153959  1689406799  30309.8  30327.6  0.000587
526  20230715   154000    154959  1689407399  30327.6  30324.9 -0.000089
527  20230715   155000    155959  1689407999    30325  30317.6 -0.000241
528  20230715   160000    160959  1689408599  30317.7  30288.2 -0.000970
529  20230715   161000    161959  1689409199  30288.2  30292.5  0.000142
2023-07-15 16:20:07,230:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230715   155000    155959  1689407999    30325  30317.6
2023-07-15 16:00:02,196:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8963 

self.closeSec=1689408599, self.tradeDate='20230715', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30317.7', self.close='30288.2'
2023-07-15 16:10:01,175:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689408599, self.tradeDate='20230715', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30317.7', self.close='30288.2'
2023-07-15 16:10:01,206:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230715   152000    152959  1689406199  30318.7  30309.8
17517  20230715   153000    153959  1689406799  30309.8  30327.6
17518  20230715   154000    154959  1689407399  30327.6  30324.9
17519  20230715   155000    155959  1689407999    30325  30317.6
17520  20230715   160000    160959  1689408599  30317.7  30288.2
2023-07-15 16:10:01,207:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8964 

self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30288.2', self.close='30292.5'
127.0.0.1 - - [15/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-15 16:20:07,967:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30288.2', self.close='30292.5'
2023-07-15 16:20:08,158:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230715   153000    153959  1689406799  30309.8  30327.6
17518  20230715   154000    154959  1689407399  30327.6  30324.9
17519  20230715   155000    155959  1689407999    30325  30317.6
17520  20230715   160000    160959  1689408599  30317.7  30288.2
17521  20230715   161000    161959  1689409199  30288.2  30292.5
2023-07-15 16:20:08,158:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230715   155000    155959  1689407999    30325  30317.6
2023-07-15 16:00:02,192:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8963 

self.closeSec=1689408599, self.tradeDate='20230715', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30317.7', self.close='30288.2'
2023-07-15 16:10:01,187:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689408599, self.tradeDate='20230715', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30317.7', self.close='30288.2'
127.0.0.1 - - [15/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-15 16:10:01,208:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230715   152000    152959  1689406199  30318.7  30309.8
12189  20230715   153000    153959  1689406799  30309.8  30327.6
12190  20230715   154000    154959  1689407399  30327.6  30324.9
12191  20230715   155000    155959  1689407999    30325  30317.6
12192  20230715   160000    160959  1689408599  30317.7  30288.2
2023-07-15 16:10:01,209:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8964 

self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30288.2', self.close='30292.5'
127.0.0.1 - - [15/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-15 16:20:07,807:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30288.2', self.close='30292.5'
2023-07-15 16:20:08,024:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230715   153000    153959  1689406799  30309.8  30327.6
12190  20230715   154000    154959  1689407399  30327.6  30324.9
12191  20230715   155000    155959  1689407999    30325  30317.6
12192  20230715   160000    160959  1689408599  30317.7  30288.2
12193  20230715   161000    161959  1689409199  30288.2  30292.5
2023-07-15 16:20:08,026:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17920
self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30288.4, self.close=30292.5, self.high=30292.5, self.low=30258.9, self.vol=805.004, self.amt=24373609.7464 
127.0.0.1 - - [15/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-15 16:20:06,219:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230715   155500    155959  ...         0.0        0.0       0
5952  20230715   160000    160459  ...         0.0        0.0       0
5953  20230715   160500    160959  ...         0.0        0.0       0
5954  20230715   161000    161459  ...         0.0        0.0       0
5955  20230715   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 16:20:06,231:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689409199, self.tradeDate='20230715', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30288.4, self.close=30292.5, self.high=30292.5, self.low=30258.9, self.vol=805.004, self.amt=24373609.7464, ukdf['pct'].iloc[-1]=0.000135 , ukdf['amount'].iloc[-1]=24373609.7464, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '128080.7385', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30292.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17921
self.closeSec=1689409499, self.tradeDate='20230715', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30292.5, self.close=30274.6, self.high=30292.5, self.low=30269.8, self.vol=560.275, self.amt=16964653.7253 
127.0.0.1 - - [15/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-15 16:25:00,766:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230715   160000    160459  ...         0.0        0.0       0
5953  20230715   160500    160959  ...         0.0        0.0       0
5954  20230715   161000    161459  ...         0.0        0.0       0
5955  20230715   161500    161959  ...         0.0        0.0       0
5956  20230715   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 16:25:00,766:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689409499, self.tradeDate='20230715', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30292.5, self.close=30274.6, self.high=30292.5, self.low=30269.8, self.vol=560.275, self.amt=16964653.7253, ukdf['pct'].iloc[-1]=-0.000591 , ukdf['amount'].iloc[-1]=16964653.7253, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127419.47049271076', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30274.69574036', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230715   040000    075959  1689379199  ...    721  0.334821  0.061710     NaN
722  20230715   080000    115959  1689393599  ...    722  0.452623  0.490778     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-12276.635', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30276.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [15/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=373
self.closeSec=1689407999, self.tradeDate='20230715', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30276.0, self.close=30317.6, self.high=30349.7, self.low=30241.0, self.vol=18539.329, self.amt=561705650.8721 
2023-07-15 16:00:01,767:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689407999, self.tradeDate='20230715', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30276.0, self.close=30317.6, self.high=30349.7, self.low=30241.0, self.vol=18539.329, self.amt=561705650.8721 
2023-07-15 16:00:01,798:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230714   200000    235959  ...   60181.765  1.878756e+09  0.000965
720  20230715   000000    035959  ...  267411.025  8.149555e+09 -0.036387
721  20230715   040000    075959  ...   59521.811  1.795398e+09  0.006425
722  20230715   080000    115959  ...   29471.378  8.929200e+08 -0.000571
723  20230715   120000    155959  ...   18539.329  5.617057e+08  0.001374

[5 rows x 11 columns]
2023-07-15 16:00:03,089:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230714   200000    235959  1689350399  ...    719  0.665636  1.274415     1.0
720  20230715   000000    035959  1689364799  ...    720  0.275558 -0.155933     NaN
721  20230715   040000    075959  1689379199  ...    721  0.334821  0.061710     NaN
722  20230715   080000    115959  1689393599  ...    722  0.452623  0.490778     NaN
723  20230715   120000    155959  1689407999  ...    723  0.473833  0.585196     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-10034.35770539839', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30319.02179121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


