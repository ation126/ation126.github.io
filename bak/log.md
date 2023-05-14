# 20230514 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [14/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=0, self.flagDict['side']='', self.tradeCount=0, self.count=64
self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26820.1, self.close=26835.9, self.high=26835.9, self.low=26820.1, self.vol=158.462, self.amt=4251518.2978 
2023-05-14 16:20:00,398:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230514   155500    155959  ...    0.532825   0.124716       0
5952  20230514   160000    160459  ...    0.532922   0.124768       0
5953  20230514   160500    160959  ...    0.533020   0.124820       0
5954  20230514   161000    161459  ...    0.533119   0.124874       0
5955  20230514   161500    161959  ...    0.533217   0.124932       0

[5 rows x 18 columns]
2023-05-14 16:20:00,398:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26820.1, self.close=26835.9, self.high=26835.9, self.low=26820.1, self.vol=158.462, self.amt=4251518.2978, ukdf['pct'].iloc[-1]=0.000585 , ukdf['amount'].iloc[-1]=4251518.2978, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.7834319588059913, value_mean=0.5332167572466446, signal=0, value_std=0.12493204715633144 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-620203.944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26835.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=0, self.flagDict['side']='', self.tradeCount=0, self.count=65
self.closeSec=1684052699, self.tradeDate='20230514', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26835.9, self.close=26840.9, self.high=26849.0, self.low=26833.9, self.vol=280.234, self.amt=7521668.341 
2023-05-14 16:25:00,371:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230514   160000    160459  ...    0.532922   0.124768       0
5953  20230514   160500    160959  ...    0.533020   0.124820       0
5954  20230514   161000    161459  ...    0.533119   0.124874       0
5955  20230514   161500    161959  ...    0.533217   0.124932       0
5956  20230514   162000    162459  ...    0.533316   0.124998       0

[5 rows x 18 columns]
2023-05-14 16:25:00,371:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684052699, self.tradeDate='20230514', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26835.9, self.close=26840.9, self.high=26849.0, self.low=26833.9, self.vol=280.234, self.amt=7521668.341, ukdf['pct'].iloc[-1]=0.000186 , ukdf['amount'].iloc[-1]=7521668.341, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.7955528705945873, value_mean=0.5333161458432546, signal=0, value_std=0.12499836730765829 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-620669.65008796912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26843.53906687', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26820.1, self.close=26835.9, self.high=26835.9, self.low=26820.1 
127.0.0.1 - - [14/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-14 16:20:00,345:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26820.1, self.close=26835.9, self.high=26835.9, self.low=26820.1   
2023-05-14 16:20:00,394:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230514   155500    155959  1684051199  ...  26822.7  0.000555   1629    3
1630  20230514   160000    160459  1684051499  ...  26828.6 -0.000339   1630    4
1631  20230514   160500    160959  1684051799  ...  26821.0 -0.000071   1631    5
1632  20230514   161000    161459  1684052099  ...  26814.2 -0.000324   1632    0
1633  20230514   161500    161959  1684052399  ...  26820.1  0.000585   1633    1

[5 rows x 11 columns]
2023-05-14 16:20:00,394:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=10, self.factor=0.3974447320614163, self.count=67 

self.closeSec=1684052699, self.tradeDate='20230514', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26835.9, self.close=26840.9, self.high=26849.0, self.low=26833.9 
2023-05-14 16:25:00,341:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684052699, self.tradeDate='20230514', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26835.9, self.close=26840.9, self.high=26849.0, self.low=26833.9   
127.0.0.1 - - [14/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-14 16:25:00,354:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230514   160000    160459  1684051499  ...  26828.6 -0.000339   1630    4
1631  20230514   160500    160959  1684051799  ...  26821.0 -0.000071   1631    5
1632  20230514   161000    161459  1684052099  ...  26814.2 -0.000324   1632    0
1633  20230514   161500    161959  1684052399  ...  26820.1  0.000585   1633    1
1634  20230514   162000    162459  1684052699  ...  26833.9  0.000186   1634    2

[5 rows x 11 columns]
2023-05-14 16:25:00,354:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-14 16:00:19,749:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230514    132959  26813.1  ...  51.250000  0.500641  0.476738
5787  20230514    135959  26811.8  ...  51.666667  0.501828  0.476570
5788  20230514    142959  26817.0  ...  52.083333  0.516046  0.467920
5789  20230514    145959  26880.0  ...  51.666667  0.504160  0.466722
5790  20230514    152959  26829.0  ...  51.250000  0.504090  0.465644

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2023-05-14 16:00:19,852:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.496738  0.503262       1  ...  0.981338   1.0    0.0  0.941212
538     1  0.497261  0.502739       1  ...  0.983643   1.0    0.0  0.943423
539     0  0.508928  0.491072       0  ...  0.981777   1.0    0.0  0.941633
540     1  0.487176  0.512824       0  ...  0.981766   1.0    0.0  0.941622
541     1  0.498566  0.501434       1  ...  0.982176   1.0    0.0  0.942015

[5 rows x 10 columns]
2023-05-14 16:00:19,871:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
6      1  0.496634  0.503366       1  ...  0.981338   1.0    0.0  0.933512
7      1  0.497358  0.502642       1  ...  0.983643   1.0    0.0  0.937824
8      0  0.508937  0.491063       0  ...  0.981777   1.0    0.0  0.936227
9      1  0.487322  0.512678       0  ...  0.981766   1.0    0.0  0.937467
10     1  0.498566  0.501434       1  ...  0.982176   1.0    0.0  0.942015

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.199', 'enterprice': '26801.5', 'countrevence': '0', 'unrealprofit': '1223.8366', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26844.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230514   155000    155959  1684051199  26827.3  26839.9  0.000470
2023-05-14 16:00:00,436:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=32 

self.closeSec=1684051799, self.tradeDate='20230514', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26839.9', self.close='26828.9'
2023-05-14 16:10:00,333:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684051799, self.tradeDate='20230514', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26839.9', self.close='26828.9'
2023-05-14 16:10:00,342:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230514   152000    152959  1684049399  26845.8  26828.7 -0.000637
525  20230514   153000    153959  1684049999  26828.8  26818.2 -0.000391
526  20230514   154000    154959  1684050599  26818.3  26827.3  0.000339
527  20230514   155000    155959  1684051199  26827.3  26839.9  0.000470
528  20230514   160000    160959  1684051799  26839.9  26828.9 -0.000410
2023-05-14 16:10:00,342:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=33 

self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26828.9', self.close='26835.9'
127.0.0.1 - - [14/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-14 16:20:02,061:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26828.9', self.close='26835.9'
2023-05-14 16:20:02,530:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230514   153000    153959  1684049999  26828.8  26818.2 -0.000391
526  20230514   154000    154959  1684050599  26818.3  26827.3  0.000339
527  20230514   155000    155959  1684051199  26827.3  26839.9  0.000470
528  20230514   160000    160959  1684051799  26839.9  26828.9 -0.000410
529  20230514   161000    161959  1684052399  26828.9  26835.9  0.000261
2023-05-14 16:20:02,539:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17375  20230514   155000    155959  1684051199  26827.3  26839.9
2023-05-14 16:00:00,450:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': False, 'isTrig': False}
127.0.0.1 - - [14/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=35 

self.closeSec=1684051799, self.tradeDate='20230514', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26839.9', self.close='26828.9'
2023-05-14 16:10:00,350:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684051799, self.tradeDate='20230514', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26839.9', self.close='26828.9'
2023-05-14 16:10:00,369:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17372  20230514   152000    152959  1684049399  26845.8  26828.7
17373  20230514   153000    153959  1684049999  26828.8  26818.2
17374  20230514   154000    154959  1684050599  26818.3  26827.3
17375  20230514   155000    155959  1684051199  26827.3  26839.9
17376  20230514   160000    160959  1684051799  26839.9  26828.9
2023-05-14 16:10:00,369:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': False, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=36 

self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26828.9', self.close='26835.9'
127.0.0.1 - - [14/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-14 16:20:04,317:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26828.9', self.close='26835.9'
2023-05-14 16:20:04,483:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17373  20230514   153000    153959  1684049999  26828.8  26818.2
17374  20230514   154000    154959  1684050599  26818.3  26827.3
17375  20230514   155000    155959  1684051199  26827.3  26839.9
17376  20230514   160000    160959  1684051799  26839.9  26828.9
17377  20230514   161000    161959  1684052399  26828.9  26835.9
2023-05-14 16:20:04,484:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': False, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230514   155000    155959  1684051199  26827.3  26839.9
2023-05-14 16:00:00,441:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': False, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=35 

self.closeSec=1684051799, self.tradeDate='20230514', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26839.9', self.close='26828.9'
2023-05-14 16:10:00,356:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684051799, self.tradeDate='20230514', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26839.9', self.close='26828.9'
127.0.0.1 - - [14/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-14 16:10:00,368:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230514   152000    152959  1684049399  26845.8  26828.7
12189  20230514   153000    153959  1684049999  26828.8  26818.2
12190  20230514   154000    154959  1684050599  26818.3  26827.3
12191  20230514   155000    155959  1684051199  26827.3  26839.9
12192  20230514   160000    160959  1684051799  26839.9  26828.9
2023-05-14 16:10:00,368:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': False, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=36 

self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26828.9', self.close='26835.9'
127.0.0.1 - - [14/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-14 16:20:03,758:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26828.9', self.close='26835.9'
2023-05-14 16:20:04,131:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230514   153000    153959  1684049999  26828.8  26818.2
12190  20230514   154000    154959  1684050599  26818.3  26827.3
12191  20230514   155000    155959  1684051199  26827.3  26839.9
12192  20230514   160000    160959  1684051799  26839.9  26828.9
12193  20230514   161000    161959  1684052399  26828.9  26835.9
2023-05-14 16:20:04,138:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': False, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [14/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=64
self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26820.1, self.close=26835.9, self.high=26835.9, self.low=26820.1, self.vol=158.462, self.amt=4251518.2978 
2023-05-14 16:20:00,363:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230514   155500    155959  ...    0.493865   0.121018       0
5952  20230514   160000    160459  ...    0.493820   0.120957       0
5953  20230514   160500    160959  ...    0.493769   0.120885       0
5954  20230514   161000    161459  ...    0.493724   0.120824       0
5955  20230514   161500    161959  ...    0.493672   0.120750       0

[5 rows x 18 columns]
2023-05-14 16:20:00,363:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684052399, self.tradeDate='20230514', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26820.1, self.close=26835.9, self.high=26835.9, self.low=26820.1, self.vol=158.462, self.amt=4251518.2978, ukdf['pct'].iloc[-1]=0.000585 , ukdf['amount'].iloc[-1]=4251518.2978, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.6150967458449248, value_mean=0.4936719118882472, signal=0, value_std=0.1207501108388062 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [14/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=65
self.closeSec=1684052699, self.tradeDate='20230514', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26835.9, self.close=26840.9, self.high=26849.0, self.low=26833.9, self.vol=280.234, self.amt=7521668.341 
2023-05-14 16:25:00,391:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230514   160000    160459  ...    0.493820   0.120957       0
5953  20230514   160500    160959  ...    0.493769   0.120885       0
5954  20230514   161000    161459  ...    0.493724   0.120824       0
5955  20230514   161500    161959  ...    0.493672   0.120750       0
5956  20230514   162000    162459  ...    0.493612   0.120669       0

[5 rows x 18 columns]
2023-05-14 16:25:00,392:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684052699, self.tradeDate='20230514', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26835.9, self.close=26840.9, self.high=26849.0, self.low=26833.9, self.vol=280.234, self.amt=7521668.341, ukdf['pct'].iloc[-1]=0.000186 , ukdf['amount'].iloc[-1]=7521668.341, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.6015583804681851, value_mean=0.49361236781010914, signal=0, value_std=0.12066868014009727 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230514   040000    075959  1684022399  ...    721  0.480154  0.187069     NaN
722  20230514   080000    115959  1684036799  ...    722  0.489190  0.227805     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-2048.06929739568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26857.75845788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [14/May/2023 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=6897.9369698, self.flagDict['side']='', self.tradeCount=0, self.count=1
self.closeSec=1684051199, self.tradeDate='20230514', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26853.6, self.close=26839.9, self.high=26888.7, self.low=26778.2, self.vol=20315.573, self.amt=545124322.1901 
2023-05-14 16:00:00,346:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684051199, self.tradeDate='20230514', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26853.6, self.close=26839.9, self.high=26888.7, self.low=26778.2, self.vol=20315.573, self.amt=545124322.1901 
2023-05-14 16:00:00,379:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230513   200000    235959  ...  40717.301  1.091401e+09 -0.000459
720  20230514   000000    035959  ...  54284.517  1.457953e+09  0.000769
721  20230514   040000    075959  ...  31112.700  8.352078e+08 -0.002233
722  20230514   080000    115959  ...  47550.339  1.270832e+09  0.003359
723  20230514   120000    155959  ...  20315.573  5.451243e+08 -0.000473

[5 rows x 11 columns]
2023-05-14 16:00:01,136:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230513   200000    235959  1683993599  ...    719  0.499312  0.256247     NaN
720  20230514   000000    035959  1684007999  ...    720  0.486805  0.210534     NaN
721  20230514   040000    075959  1684022399  ...    721  0.480154  0.187069     NaN
722  20230514   080000    115959  1684036799  ...    722  0.489190  0.227805     NaN
723  20230514   120000    155959  1684051199  ...    723  0.480029  0.185044     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-1154.30690298552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26840.71363382', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


