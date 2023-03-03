# 20230303 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27676
self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22360.4, self.close=22365.0, self.high=22369.2, self.low=22354.2, self.vol=471.236, self.amt=10538071.0151 
127.0.0.1 - - [03/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-03 16:20:01,580:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230303   155500    155959  ...         0.0        0.0       0
5952  20230303   160000    160459  ...         0.0        0.0       0
5953  20230303   160500    160959  ...         0.0        0.0       0
5954  20230303   161000    161459  ...         0.0        0.0       0
5955  20230303   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 16:20:01,583:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22360.4, self.close=22365.0, self.high=22369.2, self.low=22354.2, self.vol=471.236, self.amt=10538071.0151, ukdf['pct'].iloc[-1]=0.000201 , ukdf['amount'].iloc[-1]=10538071.0151, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-351175.00013879072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22365.09832722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27677
self.closeSec=1677831899, self.tradeDate='20230303', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22364.9, self.close=22366.8, self.high=22374.0, self.low=22360.7, self.vol=718.472, self.amt=16070396.8904 
127.0.0.1 - - [03/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-03 16:25:01,564:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230303   160000    160459  ...         0.0        0.0       0
5953  20230303   160500    160959  ...         0.0        0.0       0
5954  20230303   161000    161459  ...         0.0        0.0       0
5955  20230303   161500    161959  ...         0.0        0.0       0
5956  20230303   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 16:25:01,575:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677831899, self.tradeDate='20230303', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22364.9, self.close=22366.8, self.high=22374.0, self.low=22360.7, self.vol=718.472, self.amt=16070396.8904, ukdf['pct'].iloc[-1]=8e-05 , ukdf['amount'].iloc[-1]=16070396.8904, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-351271.3824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22366.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6396963985004845, self.count=28242 

self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22360.4, self.close=22365.0, self.high=22369.2, self.low=22354.2 
2023-03-03 16:20:01,504:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22360.4, self.close=22365.0, self.high=22369.2, self.low=22354.2   
2023-03-03 16:20:01,647:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230303   155500    155959  1677830399  ...  22345.0 -0.000443   1631    5
1632  20230303   160000    160459  1677830699  ...  22344.4  0.000635   1632    0
1633  20230303   160500    160959  1677830999  ...  22345.6  0.000072   1633    1
1634  20230303   161000    161459  1677831299  ...  22350.4 -0.000139   1634    2
1635  20230303   161500    161959  1677831599  ...  22354.2  0.000201   1635    3

[5 rows x 11 columns]
2023-03-03 16:20:01,649:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6396963985004845, self.count=28243 

self.closeSec=1677831899, self.tradeDate='20230303', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22364.9, self.close=22366.8, self.high=22374.0, self.low=22360.7 
2023-03-03 16:25:01,509:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677831899, self.tradeDate='20230303', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22364.9, self.close=22366.8, self.high=22374.0, self.low=22360.7   
2023-03-03 16:25:01,539:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230303   160000    160459  1677830699  ...  22344.4  0.000635   1632    0
1633  20230303   160500    160959  1677830999  ...  22345.6  0.000072   1633    1
1634  20230303   161000    161459  1677831299  ...  22350.4 -0.000139   1634    2
1635  20230303   161500    161959  1677831599  ...  22354.2  0.000201   1635    3
1636  20230303   162000    162459  1677831899  ...  22360.7  0.000080   1636    4

[5 rows x 11 columns]
2023-03-03 16:25:01,539:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-03 16:00:32,452:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230303    132959  22363.8  ...  50.416667  0.351627  0.637432
5787  20230303    135959  22328.9  ...  50.833333  0.351955  0.643819
5788  20230303    142959  22330.4  ...  50.833333  0.363481  0.647550
5789  20230303    145959  22386.6  ...  50.416667  0.360959  0.651891
5790  20230303    152959  22365.1  ...  50.416667  0.358118  0.656905

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-03-03 16:00:32,615:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.519185  0.480815       1  ...  0.861699   1.0    0.0  0.922439
538     0  0.523384  0.476616       1  ...  0.863864   1.0    0.0  0.924757
539     0  0.553373  0.446627       0  ...  0.863030   1.0    0.0  0.923864
540     0  0.527875  0.472125       0  ...  0.862096   1.0    0.0  0.922865
541     0  0.519747  0.480253       1  ...  0.862367   1.0    0.0  0.923154

[5 rows x 10 columns]
2023-03-03 16:00:32,652:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.517885  0.482115       1  ...  0.861699   1.0    0.0  0.911881
46     0  0.522739  0.477261       1  ...  0.863864   1.0    0.0  0.917758
47     0  0.553231  0.446769       0  ...  0.863030   1.0    0.0  0.921664
48     0  0.527364  0.472636       0  ...  0.862096   1.0    0.0  0.918554
49     0  0.519747  0.480253       1  ...  0.862367   1.0    0.0  0.923154

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.837', 'enterprice': '22365.6', 'countrevence': '0', 'unrealprofit': '-507.72064696197', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22349.65249719', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230303   155000    155959  1677830399  22384.3  22347.8 -0.001635
2023-03-03 16:00:02,243:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14120 

self.closeSec=1677830999, self.tradeDate='20230303', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22347.8', self.close='22363.5'
2023-03-03 16:10:01,623:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677830999, self.tradeDate='20230303', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22347.8', self.close='22363.5'
2023-03-03 16:10:01,691:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230303   152000    152959  1677828599  22344.7  22340.8 -0.000170
525  20230303   153000    153959  1677829199  22340.8    22368  0.001218
526  20230303   154000    154959  1677829799    22368  22384.4  0.000733
527  20230303   155000    155959  1677830399  22384.3  22347.8 -0.001635
528  20230303   160000    160959  1677830999  22347.8  22363.5  0.000703
2023-03-03 16:10:01,692:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14121 

self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22363.5', self.close='22365'
2023-03-03 16:20:01,616:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22363.5', self.close='22365'
2023-03-03 16:20:01,661:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230303   153000    153959  1677829199  22340.8    22368  0.001218
526  20230303   154000    154959  1677829799    22368  22384.4  0.000733
527  20230303   155000    155959  1677830399  22384.3  22347.8 -0.001635
528  20230303   160000    160959  1677830999  22347.8  22363.5  0.000703
529  20230303   161000    161959  1677831599  22363.5    22365  0.000067
2023-03-03 16:20:01,661:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230303   155000    155959  1677830399  22384.3  22347.8
2023-03-03 16:00:02,212:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14121 

self.closeSec=1677830999, self.tradeDate='20230303', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22347.8', self.close='22363.5'
2023-03-03 16:10:01,649:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677830999, self.tradeDate='20230303', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22347.8', self.close='22363.5'
2023-03-03 16:10:01,695:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230303   152000    152959  1677828599  22344.7  22340.8
17517  20230303   153000    153959  1677829199  22340.8    22368
17518  20230303   154000    154959  1677829799    22368  22384.4
17519  20230303   155000    155959  1677830399  22384.3  22347.8
17520  20230303   160000    160959  1677830999  22347.8  22363.5
2023-03-03 16:10:01,698:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14122 

self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22363.5', self.close='22365'
2023-03-03 16:20:01,640:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22363.5', self.close='22365'
2023-03-03 16:20:01,684:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230303   153000    153959  1677829199  22340.8    22368
17518  20230303   154000    154959  1677829799    22368  22384.4
17519  20230303   155000    155959  1677830399  22384.3  22347.8
17520  20230303   160000    160959  1677830999  22347.8  22363.5
17521  20230303   161000    161959  1677831599  22363.5    22365
2023-03-03 16:20:01,684:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230303   155000    155959  1677830399  22384.3  22347.8
2023-03-03 16:00:02,208:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14121 

self.closeSec=1677830999, self.tradeDate='20230303', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22347.8', self.close='22363.5'
2023-03-03 16:10:01,625:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677830999, self.tradeDate='20230303', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22347.8', self.close='22363.5'
2023-03-03 16:10:01,658:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230303   152000    152959  1677828599  22344.7  22340.8
12189  20230303   153000    153959  1677829199  22340.8    22368
12190  20230303   154000    154959  1677829799    22368  22384.4
12191  20230303   155000    155959  1677830399  22384.3  22347.8
12192  20230303   160000    160959  1677830999  22347.8  22363.5
2023-03-03 16:10:01,658:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14122 

self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22363.5', self.close='22365'
2023-03-03 16:20:01,641:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22363.5', self.close='22365'
2023-03-03 16:20:01,664:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230303   153000    153959  1677829199  22340.8    22368
12190  20230303   154000    154959  1677829799    22368  22384.4
12191  20230303   155000    155959  1677830399  22384.3  22347.8
12192  20230303   160000    160959  1677830999  22347.8  22363.5
12193  20230303   161000    161959  1677831599  22363.5    22365
2023-03-03 16:20:01,665:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [03/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23674
self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22360.4, self.close=22365.0, self.high=22369.2, self.low=22354.2, self.vol=471.236, self.amt=10538071.0151 
2023-03-03 16:20:01,617:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230303   155500    155959  ...         0.0        0.0       0
5952  20230303   160000    160459  ...         0.0        0.0       0
5953  20230303   160500    160959  ...         0.0        0.0       0
5954  20230303   161000    161459  ...         0.0        0.0       0
5955  20230303   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 16:20:01,619:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677831599, self.tradeDate='20230303', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22360.4, self.close=22365.0, self.high=22369.2, self.low=22354.2, self.vol=471.236, self.amt=10538071.0151, ukdf['pct'].iloc[-1]=0.000201 , ukdf['amount'].iloc[-1]=10538071.0151, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23675
self.closeSec=1677831899, self.tradeDate='20230303', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22364.9, self.close=22366.8, self.high=22374.0, self.low=22360.7, self.vol=718.472, self.amt=16070396.8904 
2023-03-03 16:25:01,557:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230303   160000    160459  ...         0.0        0.0       0
5953  20230303   160500    160959  ...         0.0        0.0       0
5954  20230303   161000    161459  ...         0.0        0.0       0
5955  20230303   161500    161959  ...         0.0        0.0       0
5956  20230303   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 16:25:01,557:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677831899, self.tradeDate='20230303', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22364.9, self.close=22366.8, self.high=22374.0, self.low=22360.7, self.vol=718.472, self.amt=16070396.8904, ukdf['pct'].iloc[-1]=8e-05 , ukdf['amount'].iloc[-1]=16070396.8904, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230303   040000    075959  1677801599  ...    721  0.409550 -0.830516    -1.0
722  20230303   080000    115959  1677815999  ...    722  0.016977 -1.952277    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '44172.210699372', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22301.9503928', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=588
self.closeSec=1677830399, self.tradeDate='20230303', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22306.4, self.close=22347.8, self.high=22399.0, self.low=22234.0, self.vol=58370.469, self.amt=1304177150.6075 127.0.0.1 - - [03/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -

2023-03-03 16:00:02,085:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677830399, self.tradeDate='20230303', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22306.4, self.close=22347.8, self.high=22399.0, self.low=22234.0, self.vol=58370.469, self.amt=1304177150.6075 
2023-03-03 16:00:02,113:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230302   200000    235959  ...  124403.213  2.899906e+09 -0.002363
720  20230303   000000    035959  ...   77176.896  1.803088e+09  0.004552
721  20230303   040000    075959  ...   52550.701  1.233292e+09  0.000021
722  20230303   080000    115959  ...  265795.593  5.977734e+09 -0.049056
723  20230303   120000    155959  ...   58370.469  1.304177e+09  0.001856

[5 rows x 11 columns]
2023-03-03 16:00:04,377:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230302   200000    235959  1677772799  ...    719  0.467245 -0.693599    -1.0
720  20230303   000000    035959  1677787199  ...    720  0.423103 -0.803330    -1.0
721  20230303   040000    075959  1677801599  ...    721  0.409550 -0.830516    -1.0
722  20230303   080000    115959  1677815999  ...    722  0.016977 -1.952277    -1.0
723  20230303   120000    155959  1677830399  ...    723  0.128108 -1.587200    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '42179.8429844274', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22349.23573076', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


