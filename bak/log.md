# 20230524 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2944
self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26694.8, self.close=26713.4, self.high=26713.4, self.low=26690.0, self.vol=647.428, self.amt=17286084.9459 
127.0.0.1 - - [24/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-24 16:20:04,031:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230524   155500    155959  ...    0.142577   0.290155       0
5952  20230524   160000    160459  ...    0.142413   0.290069       0
5953  20230524   160500    160959  ...    0.142249   0.289982       0
5954  20230524   161000    161459  ...    0.142084   0.289895       0
5955  20230524   161500    161959  ...    0.141923   0.289812       0

[5 rows x 18 columns]
2023-05-24 16:20:04,040:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26694.8, self.close=26713.4, self.high=26713.4, self.low=26690.0, self.vol=647.428, self.amt=17286084.9459, ukdf['pct'].iloc[-1]=0.000701 , ukdf['amount'].iloc[-1]=17286084.9459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.14192277331429956, signal=0, value_std=0.28981236410442335 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2109.789', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26713.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2945
self.closeSec=1684916699, self.tradeDate='20230524', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26713.3, self.close=26731.5, self.high=26735.9, self.low=26697.5, self.vol=1286.278, self.amt=34371995.506 
127.0.0.1 - - [24/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-24 16:25:00,847:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230524   160000    160459  ...    0.142413   0.290069       0
5953  20230524   160500    160959  ...    0.142249   0.289982       0
5954  20230524   161000    161459  ...    0.142084   0.289895       0
5955  20230524   161500    161959  ...    0.141923   0.289812       0
5956  20230524   162000    162459  ...    0.141761   0.289729       0

[5 rows x 18 columns]
2023-05-24 16:25:00,848:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684916699, self.tradeDate='20230524', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26713.3, self.close=26731.5, self.high=26735.9, self.low=26697.5, self.vol=1286.278, self.amt=34371995.506, ukdf['pct'].iloc[-1]=0.000678 , ukdf['amount'].iloc[-1]=34371995.506, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.14176093868086553, signal=0, value_std=0.2897288915908343 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1803.44910722856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26735.39769444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


127.0.0.1 - - [24/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26694.8, self.close=26713.4, self.high=26713.4, self.low=26690.0 
2023-05-24 16:20:02,301:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26694.8, self.close=26713.4, self.high=26713.4, self.low=26690.0   
2023-05-24 16:20:03,300:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230524   155500    155959  1684915199  ...  26654.9 -0.000723   1631    5
1632  20230524   160000    160459  1684915499  ...  26650.0  0.001189   1632    0
1633  20230524   160500    160959  1684915799  ...  26688.1  0.000228   1633    1
1634  20230524   161000    161459  1684916099  ...  26677.2 -0.000277   1634    2
1635  20230524   161500    161959  1684916399  ...  26690.0  0.000701   1635    3

[5 rows x 11 columns]
2023-05-24 16:20:03,301:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=43, self.factor=0.5814561995344465, self.count=2947 

self.closeSec=1684916699, self.tradeDate='20230524', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26713.3, self.close=26731.5, self.high=26735.9, self.low=26697.5 
2023-05-24 16:25:00,774:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684916699, self.tradeDate='20230524', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26713.3, self.close=26731.5, self.high=26735.9, self.low=26697.5   
2023-05-24 16:25:00,835:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230524   160000    160459  1684915499  ...  26650.0  0.001189   1632    0
1633  20230524   160500    160959  1684915799  ...  26688.1  0.000228   1633    1
1634  20230524   161000    161459  1684916099  ...  26677.2 -0.000277   1634    2
1635  20230524   161500    161959  1684916399  ...  26690.0  0.000701   1635    3
1636  20230524   162000    162459  1684916699  ...  26697.5  0.000678   1636    4

[5 rows x 11 columns]
2023-05-24 16:25:00,835:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-24 16:00:35,478:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230524    132959  26791.3  ...  48.333333  0.430471  0.654341
5787  20230524    135959  26809.5  ...  47.916667  0.419889  0.666728
5788  20230524    142959  26762.3  ...  47.500000  0.412803  0.681204
5789  20230524    145959  26730.0  ...  47.083333  0.406283  0.691565
5790  20230524    152959  26700.0  ...  47.083333  0.406196  0.701268

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-05-24 16:00:35,636:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.473954  0.526046       0  ...  0.934173  -1.0    0.0  0.997637
538     1  0.479612  0.520388       0  ...  0.935300  -1.0    0.0  0.996433
539     1  0.493262  0.506738       0  ...  0.936353  -1.0    0.0  0.995310
540     1  0.493189  0.506811       0  ...  0.936367  -1.0    0.0  0.995296
541     1  0.495082  0.504918       0  ...  0.937605  -1.0    0.0  0.993980

[5 rows x 10 columns]
2023-05-24 16:00:35,672:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.473405  0.526595       0  ...  0.934173  -1.0    0.0  1.003246
46     1  0.479574  0.520426       0  ...  0.935300  -1.0    0.0  0.999738
47     1  0.493346  0.506654       0  ...  0.936353  -1.0    0.0  0.996819
48     1  0.493476  0.506524       0  ...  0.936367  -1.0    0.0  0.999993
49     1  0.495082  0.504918       0  ...  0.937605  -1.0    0.0  0.993980

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.649', 'enterprice': '26743.4', 'countrevence': '0', 'unrealprofit': '2169.2286', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26662', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230524   155000    155959  1684915199    26675  26664.2 -0.000405
2023-05-24 16:00:02,392:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [24/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1472 

self.closeSec=1684915799, self.tradeDate='20230524', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26664.2', self.close='26702.1'
2023-05-24 16:10:01,168:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684915799, self.tradeDate='20230524', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26664.2', self.close='26702.1'
2023-05-24 16:10:01,181:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230524   152000    152959  1684913399  26722.9  26699.5 -0.000876
525  20230524   153000    153959  1684913999  26699.4  26664.4 -0.001315
526  20230524   154000    154959  1684914599  26664.5    26675  0.000398
527  20230524   155000    155959  1684915199    26675  26664.2 -0.000405
528  20230524   160000    160959  1684915799  26664.2  26702.1  0.001421
2023-05-24 16:10:01,185:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1473 

self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26702.1', self.close='26713.4'
127.0.0.1 - - [24/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-24 16:20:04,370:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26702.1', self.close='26713.4'
2023-05-24 16:20:04,810:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230524   153000    153959  1684913999  26699.4  26664.4 -0.001315
526  20230524   154000    154959  1684914599  26664.5    26675  0.000398
527  20230524   155000    155959  1684915199    26675  26664.2 -0.000405
528  20230524   160000    160959  1684915799  26664.2  26702.1  0.001421
529  20230524   161000    161959  1684916399  26702.1  26713.4  0.000423
2023-05-24 16:20:04,817:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230524   155000    155959  1684915199    26675  26664.2
2023-05-24 16:00:02,438:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1475 

self.closeSec=1684915799, self.tradeDate='20230524', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26664.2', self.close='26702.1'
2023-05-24 16:10:01,193:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684915799, self.tradeDate='20230524', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26664.2', self.close='26702.1'
127.0.0.1 - - [24/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-24 16:10:01,214:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230524   152000    152959  1684913399  26722.9  26699.5
17517  20230524   153000    153959  1684913999  26699.4  26664.4
17518  20230524   154000    154959  1684914599  26664.5    26675
17519  20230524   155000    155959  1684915199    26675  26664.2
17520  20230524   160000    160959  1684915799  26664.2  26702.1
2023-05-24 16:10:01,214:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1476 

self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26702.1', self.close='26713.4'
127.0.0.1 - - [24/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-24 16:20:05,324:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26702.1', self.close='26713.4'
2023-05-24 16:20:05,457:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230524   153000    153959  1684913999  26699.4  26664.4
17518  20230524   154000    154959  1684914599  26664.5    26675
17519  20230524   155000    155959  1684915199    26675  26664.2
17520  20230524   160000    160959  1684915799  26664.2  26702.1
17521  20230524   161000    161959  1684916399  26702.1  26713.4
2023-05-24 16:20:05,457:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230524   155000    155959  1684915199    26675  26664.2
2023-05-24 16:00:02,432:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1475 

self.closeSec=1684915799, self.tradeDate='20230524', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26664.2', self.close='26702.1'
2023-05-24 16:10:01,200:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684915799, self.tradeDate='20230524', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26664.2', self.close='26702.1'
127.0.0.1 - - [24/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-24 16:10:01,223:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230524   152000    152959  1684913399  26722.9  26699.5
12189  20230524   153000    153959  1684913999  26699.4  26664.4
12190  20230524   154000    154959  1684914599  26664.5    26675
12191  20230524   155000    155959  1684915199    26675  26664.2
12192  20230524   160000    160959  1684915799  26664.2  26702.1
2023-05-24 16:10:01,223:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1476 

self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26702.1', self.close='26713.4'
127.0.0.1 - - [24/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-24 16:20:05,141:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26702.1', self.close='26713.4'
2023-05-24 16:20:05,218:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230524   153000    153959  1684913999  26699.4  26664.4
12190  20230524   154000    154959  1684914599  26664.5    26675
12191  20230524   155000    155959  1684915199    26675  26664.2
12192  20230524   160000    160959  1684915799  26664.2  26702.1
12193  20230524   161000    161959  1684916399  26702.1  26713.4
2023-05-24 16:20:05,218:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2944
self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26694.8, self.close=26713.4, self.high=26713.4, self.low=26690.0, self.vol=647.428, self.amt=17286084.9459 
127.0.0.1 - - [24/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-24 16:20:03,931:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230524   155500    155959  ...         0.0        0.0       0
5952  20230524   160000    160459  ...         0.0        0.0       0
5953  20230524   160500    160959  ...         0.0        0.0       0
5954  20230524   161000    161459  ...         0.0        0.0       0
5955  20230524   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-24 16:20:03,968:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684916399, self.tradeDate='20230524', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26694.8, self.close=26713.4, self.high=26713.4, self.low=26690.0, self.vol=647.428, self.amt=17286084.9459, ukdf['pct'].iloc[-1]=0.000701 , ukdf['amount'].iloc[-1]=17286084.9459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-4850.6146', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26713.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2945
self.closeSec=1684916699, self.tradeDate='20230524', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26713.3, self.close=26731.5, self.high=26735.9, self.low=26697.5, self.vol=1286.278, self.amt=34371995.506 
2023-05-24 16:25:00,863:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230524   160000    160459  ...         0.0        0.0       0
5953  20230524   160500    160959  ...         0.0        0.0       0
5954  20230524   161000    161459  ...         0.0        0.0       0
5955  20230524   161500    161959  ...         0.0        0.0       0
5956  20230524   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-24 16:25:00,864:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684916699, self.tradeDate='20230524', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26713.3, self.close=26731.5, self.high=26735.9, self.low=26697.5, self.vol=1286.278, self.amt=34371995.506, ukdf['pct'].iloc[-1]=0.000678 , ukdf['amount'].iloc[-1]=34371995.506, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-4033.59823080396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26735.39769444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230524   040000    075959  1684886399  ...    721  0.467182  0.243154     NaN
722  20230524   080000    115959  1684900799  ...    722  0.322284 -0.413415     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '15976.82499571878', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26760.56527778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=61
self.closeSec=1684915199, self.tradeDate='20230524', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26770.0, self.close=26664.2, self.high=26810.0, self.low=26566.5, self.vol=72171.252, self.amt=1928814158.98383 
127.0.0.1 - - [24/May/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-05-24 16:00:01,916:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684915199, self.tradeDate='20230524', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26770.0, self.close=26664.2, self.high=26810.0, self.low=26566.5, self.vol=72171.252, self.amt=1928814158.98383 
2023-05-24 16:00:01,939:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230523   200000    235959  ...   63502.505  1.732442e+09 -0.000593
720  20230524   000000    035959  ...   55692.994  1.514264e+09 -0.005093
721  20230524   040000    075959  ...   21367.419  5.811356e+08  0.001410
722  20230524   080000    115959  ...  105289.512  2.832790e+09 -0.016167
723  20230524   120000    155959  ...   72171.252  1.928814e+09 -0.003952

[5 rows x 11 columns]
2023-05-24 16:00:04,191:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230523   200000    235959  1684857599  ...    719  0.307050 -0.510986     NaN
720  20230524   000000    035959  1684871999  ...    720  0.492751  0.349268     NaN
721  20230524   040000    075959  1684886399  ...    721  0.467182  0.243154     NaN
722  20230524   080000    115959  1684900799  ...    722  0.322284 -0.413415     NaN
723  20230524   120000    155959  1684915199  ...    723  0.351419 -0.259060     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '20958.24133644648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26663.93069048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


