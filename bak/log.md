# 20230228 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26812
self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23257.3, self.close=23244.3, self.high=23258.1, self.low=23226.5, self.vol=1248.474, self.amt=29018758.1968 
127.0.0.1 - - [28/Feb/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-02-28 16:20:10,777:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230228   155500    155959  ...         0.0        0.0       0
5952  20230228   160000    160459  ...         0.0        0.0       0
5953  20230228   160500    160959  ...         0.0        0.0       0
5954  20230228   161000    161459  ...         0.0        0.0       0
5955  20230228   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 16:20:10,779:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23257.3, self.close=23244.3, self.high=23258.1, self.low=23226.5, self.vol=1248.474, self.amt=29018758.1968, ukdf['pct'].iloc[-1]=-0.000555 , ukdf['amount'].iloc[-1]=29018758.1968, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-403561.9082244312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23235.65981495', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26813
self.closeSec=1677572699, self.tradeDate='20230228', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23244.2, self.close=23283.8, self.high=23283.9, self.low=23227.9, self.vol=1155.724, self.amt=26878549.11 
127.0.0.1 - - [28/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-28 16:25:01,708:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230228   160000    160459  ...         0.0        0.0       0
5953  20230228   160500    160959  ...         0.0        0.0       0
5954  20230228   161000    161459  ...         0.0        0.0       0
5955  20230228   161500    161959  ...         0.0        0.0       0
5956  20230228   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 16:25:01,709:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677572699, self.tradeDate='20230228', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23244.2, self.close=23283.8, self.high=23283.9, self.low=23227.9, self.vol=1155.724, self.amt=26878549.11, ukdf['pct'].iloc[-1]=0.001699 , ukdf['amount'].iloc[-1]=26878549.11, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-406488.88', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23284.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23257.3, self.close=23244.3, self.high=23258.1, self.low=23226.5 
127.0.0.1 - - [28/Feb/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-02-28 16:20:07,499:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23257.3, self.close=23244.3, self.high=23258.1, self.low=23226.5   
2023-02-28 16:20:09,148:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230228   155500    155959  1677571199  ...  23210.0 -0.000916   1631    5
1632  20230228   160000    160459  1677571499  ...  23190.2  0.001021   1632    0
1633  20230228   160500    160959  1677571799  ...  23224.2  0.000779   1633    1
1634  20230228   161000    161459  1677572099  ...  23232.1 -0.000340   1634    2
1635  20230228   161500    161959  1677572399  ...  23226.5 -0.000555   1635    3

[5 rows x 11 columns]
2023-02-28 16:20:09,157:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=52, self.factor=0.5406024881999243, self.count=27379 

self.closeSec=1677572699, self.tradeDate='20230228', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23244.2, self.close=23283.8, self.high=23283.9, self.low=23227.9 
2023-02-28 16:25:01,644:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677572699, self.tradeDate='20230228', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23244.2, self.close=23283.8, self.high=23283.9, self.low=23227.9   
2023-02-28 16:25:01,683:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230228   160000    160459  1677571499  ...  23190.2  0.001021   1632    0
1633  20230228   160500    160959  1677571799  ...  23224.2  0.000779   1633    1
1634  20230228   161000    161459  1677572099  ...  23232.1 -0.000340   1634    2
1635  20230228   161500    161959  1677572399  ...  23226.5 -0.000555   1635    3
1636  20230228   162000    162459  1677572699  ...  23227.9  0.001699   1636    4

[5 rows x 11 columns]
2023-02-28 16:25:01,684:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-28 16:00:33,656:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230228    132959  23402.0  ...  48.333333  0.506311  0.573553
5787  20230228    135959  23416.2  ...  48.333333  0.494883  0.578875
5788  20230228    142959  23365.3  ...  48.333333  0.493900  0.584208
5789  20230228    145959  23361.0  ...  48.333333  0.498361  0.587577
5790  20230228    152959  23380.2  ...  47.916667  0.490295  0.593664

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-02-28 16:00:33,807:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.508323  0.491677       0  ...  0.843959  -1.0    0.0  0.985109
538     1  0.490113  0.509887       0  ...  0.844118  -1.0    0.0  0.984923
539     1  0.498606  0.501394       1  ...  0.843420  -1.0    0.0  0.985737
540     0  0.508706  0.491294       0  ...  0.844694  -1.0    0.0  0.984249
541     1  0.498034  0.501966       0  ...  0.849094  -1.0    0.0  0.979122

[5 rows x 10 columns]
2023-02-28 16:00:33,842:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507864  0.492136       0  ...  0.854260  -1.0    0.0  0.972974
46     1  0.490381  0.509619       0  ...  0.849254  -1.0    0.0  0.978758
47     1  0.499846  0.500154       1  ...  0.836565  -1.0    0.0  0.993777
48     0  0.509201  0.490799       0  ...  0.841707  -1.0    0.0  0.987726
49     1  0.498034  0.501966       0  ...  0.849094  -1.0    0.0  0.979122

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.752', 'enterprice': '23379.5', 'countrevence': '0', 'unrealprofit': '5602.18471927936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23208.45137032', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230228   155000    155959  1677571199  23262.1  23223.3 -0.001668
2023-02-28 16:00:02,284:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13688 

self.closeSec=1677571799, self.tradeDate='20230228', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23223.4', self.close='23265.1'
2023-02-28 16:10:01,628:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677571799, self.tradeDate='20230228', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23223.4', self.close='23265.1'
127.0.0.1 - - [28/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-28 16:10:01,649:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230228   152000    152959  1677569399  23377.8  23344.9 -0.001403
525  20230228   153000    153959  1677569999    23345  23302.5 -0.001816
526  20230228   154000    154959  1677570599  23302.4  23262.1 -0.001734
527  20230228   155000    155959  1677571199  23262.1  23223.3 -0.001668
528  20230228   160000    160959  1677571799  23223.4  23265.1  0.001800
2023-02-28 16:10:01,649:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13689 

self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23265.1', self.close='23244.3'
127.0.0.1 - - [28/Feb/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-02-28 16:20:08,608:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23265.1', self.close='23244.3'
2023-02-28 16:20:09,417:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230228   153000    153959  1677569999    23345  23302.5 -0.001816
526  20230228   154000    154959  1677570599  23302.4  23262.1 -0.001734
527  20230228   155000    155959  1677571199  23262.1  23223.3 -0.001668
528  20230228   160000    160959  1677571799  23223.4  23265.1  0.001800
529  20230228   161000    161959  1677572399  23265.1  23244.3 -0.000894
2023-02-28 16:20:09,418:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230228   155000    155959  1677571199  23262.1  23223.3
2023-02-28 16:00:02,322:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13689 

self.closeSec=1677571799, self.tradeDate='20230228', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23223.4', self.close='23265.1'
2023-02-28 16:10:01,609:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677571799, self.tradeDate='20230228', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23223.4', self.close='23265.1'
127.0.0.1 - - [28/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-02-28 16:10:01,664:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230228   152000    152959  1677569399  23377.8  23344.9
17517  20230228   153000    153959  1677569999    23345  23302.5
17518  20230228   154000    154959  1677570599  23302.4  23262.1
17519  20230228   155000    155959  1677571199  23262.1  23223.3
17520  20230228   160000    160959  1677571799  23223.4  23265.1
2023-02-28 16:10:01,665:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13690 

self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23265.1', self.close='23244.3'
127.0.0.1 - - [28/Feb/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-02-28 16:20:11,459:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23265.1', self.close='23244.3'
2023-02-28 16:20:11,827:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230228   153000    153959  1677569999    23345  23302.5
17518  20230228   154000    154959  1677570599  23302.4  23262.1
17519  20230228   155000    155959  1677571199  23262.1  23223.3
17520  20230228   160000    160959  1677571799  23223.4  23265.1
17521  20230228   161000    161959  1677572399  23265.1  23244.3
2023-02-28 16:20:11,828:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230228   155000    155959  1677571199  23262.1  23223.3
2023-02-28 16:00:02,306:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13689 

self.closeSec=1677571799, self.tradeDate='20230228', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23223.4', self.close='23265.1'
2023-02-28 16:10:01,653:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677571799, self.tradeDate='20230228', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23223.4', self.close='23265.1'
2023-02-28 16:10:01,700:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230228   152000    152959  1677569399  23377.8  23344.9
12189  20230228   153000    153959  1677569999    23345  23302.5
12190  20230228   154000    154959  1677570599  23302.4  23262.1
12191  20230228   155000    155959  1677571199  23262.1  23223.3
12192  20230228   160000    160959  1677571799  23223.4  23265.1
2023-02-28 16:10:01,700:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13690 

self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23265.1', self.close='23244.3'
127.0.0.1 - - [28/Feb/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-02-28 16:20:11,278:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23265.1', self.close='23244.3'
2023-02-28 16:20:11,739:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230228   153000    153959  1677569999    23345  23302.5
12190  20230228   154000    154959  1677570599  23302.4  23262.1
12191  20230228   155000    155959  1677571199  23262.1  23223.3
12192  20230228   160000    160959  1677571799  23223.4  23265.1
12193  20230228   161000    161959  1677572399  23265.1  23244.3
2023-02-28 16:20:11,739:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22810
self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23257.3, self.close=23244.3, self.high=23258.1, self.low=23226.5, self.vol=1248.474, self.amt=29018758.1968 
127.0.0.1 - - [28/Feb/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-02-28 16:20:06,289:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230228   155500    155959  ...         0.0        0.0       0
5952  20230228   160000    160459  ...         0.0        0.0       0
5953  20230228   160500    160959  ...         0.0        0.0       0
5954  20230228   161000    161459  ...         0.0        0.0       0
5955  20230228   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 16:20:06,308:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677572399, self.tradeDate='20230228', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23257.3, self.close=23244.3, self.high=23258.1, self.low=23226.5, self.vol=1248.474, self.amt=29018758.1968, ukdf['pct'].iloc[-1]=-0.000555 , ukdf['amount'].iloc[-1]=29018758.1968, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22811
self.closeSec=1677572699, self.tradeDate='20230228', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23244.2, self.close=23283.8, self.high=23283.9, self.low=23227.9, self.vol=1155.724, self.amt=26878549.11 
127.0.0.1 - - [28/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-02-28 16:25:01,570:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230228   160000    160459  ...         0.0        0.0       0
5953  20230228   160500    160959  ...         0.0        0.0       0
5954  20230228   161000    161459  ...         0.0        0.0       0
5955  20230228   161500    161959  ...         0.0        0.0       0
5956  20230228   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 16:25:01,571:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677572699, self.tradeDate='20230228', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23244.2, self.close=23283.8, self.high=23283.9, self.low=23227.9, self.vol=1155.724, self.amt=26878549.11, ukdf['pct'].iloc[-1]=0.001699 , ukdf['amount'].iloc[-1]=26878549.11, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230228   040000    075959  1677542399  ...    721  0.716158  0.166024     NaN
722  20230228   080000    115959  1677556799  ...    722  0.666186  0.050230     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '14572.8445', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23454.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  127.0.0.1 - - [28/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=570
self.closeSec=1677571199, self.tradeDate='20230228', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23454.3, self.close=23223.3, self.high=23456.2, self.low=23210.0, self.vol=44074.367, self.amt=1028988454.9902 
2023-02-28 16:00:02,199:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677571199, self.tradeDate='20230228', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23454.3, self.close=23223.3, self.high=23456.2, self.low=23210.0, self.vol=44074.367, self.amt=1028988454.9902 
2023-02-28 16:00:02,236:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230227   200000    235959  ...  184984.884  4.377125e+09  0.005397
720  20230228   000000    035959  ...  166667.763  3.885504e+09 -0.012057
721  20230228   040000    075959  ...   76820.163  1.793671e+09  0.009350
722  20230228   080000    115959  ...   44084.232  1.033383e+09 -0.001095
723  20230228   120000    155959  ...   44074.367  1.028988e+09 -0.009849

[5 rows x 11 columns]
2023-02-28 16:00:04,790:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230227   200000    235959  1677513599  ...    719  0.854884  0.495060     NaN
720  20230228   000000    035959  1677527999  ...    720  0.774757  0.304801     NaN
721  20230228   040000    075959  1677542399  ...    721  0.716158  0.166024     NaN
722  20230228   080000    115959  1677556799  ...    722  0.666186  0.050230     NaN
723  20230228   120000    155959  1677571199  ...    723  0.613378 -0.076614     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '4833.7134', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23223.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


