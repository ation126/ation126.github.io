# 20230330 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35452
self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28705.1, self.close=28672.2, self.high=28710.0, self.low=28671.0, self.vol=689.591, self.amt=19787289.8717 
127.0.0.1 - - [30/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 16:20:08,604:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230330   155500    155959  ...         0.0        0.0       0
5952  20230330   160000    160459  ...         0.0        0.0       0
5953  20230330   160500    160959  ...         0.0        0.0       0
5954  20230330   161000    161459  ...         0.0        0.0       0
5955  20230330   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 16:20:08,624:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28705.1, self.close=28672.2, self.high=28710.0, self.low=28671.0, self.vol=689.591, self.amt=19787289.8717, ukdf['pct'].iloc[-1]=-0.001146 , ukdf['amount'].iloc[-1]=19787289.8717, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-730859.3834692704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28674.6633254', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35453
self.closeSec=1680164699, self.tradeDate='20230330', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28672.3, self.close=28666.1, self.high=28687.7, self.low=28659.9, self.vol=752.816, self.amt=21585573.3718 
2023-03-30 16:25:01,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230330   160000    160459  ...         0.0        0.0       0
5953  20230330   160500    160959  ...         0.0        0.0       0
5954  20230330   161000    161459  ...         0.0        0.0       0
5955  20230330   161500    161959  ...         0.0        0.0       0
5956  20230330   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 16:25:01,577:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680164699, self.tradeDate='20230330', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28672.3, self.close=28666.1, self.high=28687.7, self.low=28659.9, self.vol=752.816, self.amt=21585573.3718, ukdf['pct'].iloc[-1]=-0.000213 , ukdf['amount'].iloc[-1]=21585573.3718, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-730386.2', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28666.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28705.1, self.close=28672.2, self.high=28710.0, self.low=28671.0 
127.0.0.1 - - [30/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-30 16:20:06,955:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28705.1, self.close=28672.2, self.high=28710.0, self.low=28671.0   
2023-03-30 16:20:07,795:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230330   155500    155959  1680163199  ...  28683.9 -0.000104   1631    5
1632  20230330   160000    160459  1680163499  ...  28702.1  0.000794   1632    0
1633  20230330   160500    160959  1680163799  ...  28676.9 -0.001114   1633    1
1634  20230330   161000    161459  1680164099  ...  28668.1  0.000268   1634    2
1635  20230330   161500    161959  1680164399  ...  28671.0 -0.001146   1635    3

[5 rows x 11 columns]
2023-03-30 16:20:07,804:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=24, self.factor=0.30103984989702115, self.count=36019 

self.closeSec=1680164699, self.tradeDate='20230330', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28672.3, self.close=28666.1, self.high=28687.7, self.low=28659.9 
2023-03-30 16:25:01,531:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680164699, self.tradeDate='20230330', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28672.3, self.close=28666.1, self.high=28687.7, self.low=28659.9   
2023-03-30 16:25:01,575:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230330   160000    160459  1680163499  ...  28702.1  0.000794   1632    0
1633  20230330   160500    160959  1680163799  ...  28676.9 -0.001114   1633    1
1634  20230330   161000    161459  1680164099  ...  28668.1  0.000268   1634    2
1635  20230330   161500    161959  1680164399  ...  28671.0 -0.001146   1635    3
1636  20230330   162000    162459  1680164699  ...  28659.9 -0.000213   1636    4

[5 rows x 11 columns]
2023-03-30 16:25:01,575:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-30 16:00:35,400:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230330    132959  28567.8  ...  51.250000  0.559361  0.320450
5787  20230330    135959  28478.2  ...  51.666667  0.571307  0.333886
5788  20230330    142959  28600.7  ...  51.250000  0.568840  0.347570
5789  20230330    145959  28581.7  ...  51.250000  0.571143  0.358948
5790  20230330    152959  28605.0  ...  51.250000  0.575101  0.367183

[5 rows x 33 columns]
0.5055350553505535
acc is : 0.5055350553505535
2023-03-30 16:00:35,566:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.451643  0.548357       1  ...  0.992988   1.0    0.0  1.056366
538     0  0.545950  0.454050       0  ...  0.992322   1.0    0.0  1.055657
539     0  0.511387  0.488613       1  ...  0.993134   1.0    0.0  1.056521
540     0  0.508634  0.491366       1  ...  0.994523   1.0    0.0  1.057999
541     0  0.521377  0.478623       1  ...  0.996661   1.0    0.0  1.060274

[5 rows x 10 columns]
2023-03-30 16:00:35,588:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.453325  0.546675       1  ...  0.986239   1.0    0.0  1.063152
46     0  0.548198  0.451802       0  ...  0.992322   1.0    0.0  1.064349
47     0  0.512000  0.488000       1  ...  0.993134   1.0    0.0  1.063106
48     0  0.509564  0.490436       1  ...  0.994523   1.0    0.0  1.061795
49     0  0.521377  0.478623       1  ...  0.996661   1.0    0.0  1.060274

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230330   155000    155959  1680163199  28665.9  28706.6  0.001420
2023-03-30 16:00:02,092:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18008 

self.closeSec=1680163799, self.tradeDate='20230330', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28706.5', self.close='28697.4'
2023-03-30 16:10:01,603:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680163799, self.tradeDate='20230330', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28706.5', self.close='28697.4'
127.0.0.1 - - [30/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-30 16:10:01,615:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230330   152000    152959  1680161399  28596.5    28645  0.001696
525  20230330   153000    153959  1680161999    28648  28725.7  0.002817
526  20230330   154000    154959  1680162599  28725.9  28665.9 -0.002082
527  20230330   155000    155959  1680163199  28665.9  28706.6  0.001420
528  20230330   160000    160959  1680163799  28706.5  28697.4 -0.000320
2023-03-30 16:10:01,617:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18009 

self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28697.4', self.close='28672.3'
127.0.0.1 - - [30/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 16:20:07,674:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28697.4', self.close='28672.3'
2023-03-30 16:20:08,364:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230330   153000    153959  1680161999    28648  28725.7  0.002817
526  20230330   154000    154959  1680162599  28725.9  28665.9 -0.002082
527  20230330   155000    155959  1680163199  28665.9  28706.6  0.001420
528  20230330   160000    160959  1680163799  28706.5  28697.4 -0.000320
529  20230330   161000    161959  1680164399  28697.4  28672.3 -0.000875
2023-03-30 16:20:08,364:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230330   155000    155959  1680163199  28665.9  28706.6
2023-03-30 16:00:02,125:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18009 

self.closeSec=1680163799, self.tradeDate='20230330', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28706.5', self.close='28697.4'
2023-03-30 16:10:01,647:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680163799, self.tradeDate='20230330', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28706.5', self.close='28697.4'
2023-03-30 16:10:01,675:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230330   152000    152959  1680161399  28596.5    28645
17517  20230330   153000    153959  1680161999    28648  28725.7
17518  20230330   154000    154959  1680162599  28725.9  28665.9
17519  20230330   155000    155959  1680163199  28665.9  28706.6
17520  20230330   160000    160959  1680163799  28706.5  28697.4
2023-03-30 16:10:01,675:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18010 

self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28697.4', self.close='28672.3'
127.0.0.1 - - [30/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 16:20:10,375:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28697.4', self.close='28672.3'
2023-03-30 16:20:10,494:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230330   153000    153959  1680161999    28648  28725.7
17518  20230330   154000    154959  1680162599  28725.9  28665.9
17519  20230330   155000    155959  1680163199  28665.9  28706.6
17520  20230330   160000    160959  1680163799  28706.5  28697.4
17521  20230330   161000    161959  1680164399  28697.4  28672.3
2023-03-30 16:20:10,495:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230330   155000    155959  1680163199  28665.9  28706.6
2023-03-30 16:00:02,065:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18009 

self.closeSec=1680163799, self.tradeDate='20230330', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28706.5', self.close='28697.4'
2023-03-30 16:10:01,636:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680163799, self.tradeDate='20230330', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28706.5', self.close='28697.4'
2023-03-30 16:10:01,671:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230330   152000    152959  1680161399  28596.5    28645
12189  20230330   153000    153959  1680161999    28648  28725.7
12190  20230330   154000    154959  1680162599  28725.9  28665.9
12191  20230330   155000    155959  1680163199  28665.9  28706.6
12192  20230330   160000    160959  1680163799  28706.5  28697.4
2023-03-30 16:10:01,671:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18010 

self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28697.4', self.close='28672.3'
127.0.0.1 - - [30/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 16:20:09,805:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28697.4', self.close='28672.3'
2023-03-30 16:20:10,114:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230330   153000    153959  1680161999    28648  28725.7
12190  20230330   154000    154959  1680162599  28725.9  28665.9
12191  20230330   155000    155959  1680163199  28665.9  28706.6
12192  20230330   160000    160959  1680163799  28706.5  28697.4
12193  20230330   161000    161959  1680164399  28697.4  28672.3
2023-03-30 16:20:10,115:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31450
self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28705.1, self.close=28672.2, self.high=28710.0, self.low=28671.0, self.vol=689.591, self.amt=19787289.8717 
127.0.0.1 - - [30/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-30 16:20:06,365:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230330   155500    155959  ...         0.0        0.0       0
5952  20230330   160000    160459  ...         0.0        0.0       0
5953  20230330   160500    160959  ...         0.0        0.0       0
5954  20230330   161000    161459  ...         0.0        0.0       0
5955  20230330   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 16:20:06,386:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680164399, self.tradeDate='20230330', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28705.1, self.close=28672.2, self.high=28710.0, self.low=28671.0, self.vol=689.591, self.amt=19787289.8717, ukdf['pct'].iloc[-1]=-0.001146 , ukdf['amount'].iloc[-1]=19787289.8717, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31451
self.closeSec=1680164699, self.tradeDate='20230330', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28672.3, self.close=28666.1, self.high=28687.7, self.low=28659.9, self.vol=752.816, self.amt=21585573.3718 
127.0.0.1 - - [30/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-30 16:25:01,619:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230330   160000    160459  ...         0.0        0.0       0
5953  20230330   160500    160959  ...         0.0        0.0       0
5954  20230330   161000    161459  ...         0.0        0.0       0
5955  20230330   161500    161959  ...         0.0        0.0       0
5956  20230330   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 16:25:01,622:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680164699, self.tradeDate='20230330', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28672.3, self.close=28666.1, self.high=28687.7, self.low=28659.9, self.vol=752.816, self.amt=21585573.3718, ukdf['pct'].iloc[-1]=-0.000213 , ukdf['amount'].iloc[-1]=21585573.3718, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230330   040000    075959  1680134399  ...    721  0.463239 -0.015555     NaN
722  20230330   080000    115959  1680148799  ...    722  0.546246  0.218175     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-20123.6382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28465.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=750
self.closeSec=1680163199, self.tradeDate='20230330', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28470.4, self.close=28706.6, self.high=28760.0, self.low=28425.0, self.vol=79859.667, self.amt=2284421736.80251 
127.0.0.1 - - [30/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-03-30 16:00:01,930:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680163199, self.tradeDate='20230330', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28470.4, self.close=28706.6, self.high=28760.0, self.low=28425.0, self.vol=79859.667, self.amt=2284421736.80251 
2023-03-30 16:00:01,996:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230329   200000    235959  ...  132706.077  3.766132e+09  0.002780
720  20230330   000000    035959  ...   91922.458  2.599163e+09 -0.000711
721  20230330   040000    075959  ...   59350.476  1.683516e+09 -0.002380
722  20230330   080000    115959  ...  244943.146  7.017047e+09  0.004658
723  20230330   120000    155959  ...   79859.667  2.284422e+09  0.008293

[5 rows x 11 columns]
2023-03-30 16:00:04,438:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230329   200000    235959  1680105599  ...    719  0.409578 -0.188305     NaN
720  20230330   000000    035959  1680119999  ...    720  0.436156 -0.104025     NaN
721  20230330   040000    075959  1680134399  ...    721  0.463239 -0.015555     NaN
722  20230330   080000    115959  1680148799  ...    722  0.546246  0.218175     NaN
723  20230330   120000    155959  1680163199  ...    723  0.568499  0.298260     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-33123.64798497972', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28707.85879762', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


