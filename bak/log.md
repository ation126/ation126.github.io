# 20230614 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8992
self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25875.6, self.close=25891.7, self.high=25900.0, self.low=25872.5, self.vol=524.052, self.amt=13566197.0609 
127.0.0.1 - - [14/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-14 16:20:07,279:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230614   155500    155959  ...         0.0        0.0       0
5952  20230614   160000    160459  ...         0.0        0.0       0
5953  20230614   160500    160959  ...         0.0        0.0       0
5954  20230614   161000    161459  ...         0.0        0.0       0
5955  20230614   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 16:20:07,310:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25875.6, self.close=25891.7, self.high=25900.0, self.low=25872.5, self.vol=524.052, self.amt=13566197.0609, ukdf['pct'].iloc[-1]=0.000622 , ukdf['amount'].iloc[-1]=13566197.0609, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13535.0975880318', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25892.9699707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8993
self.closeSec=1686731099, self.tradeDate='20230614', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25891.7, self.close=25903.5, self.high=25903.5, self.low=25890.0, self.vol=320.204, self.amt=8292138.699 
127.0.0.1 - - [14/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-14 16:25:00,822:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230614   160000    160459  ...         0.0        0.0       0
5953  20230614   160500    160959  ...         0.0        0.0       0
5954  20230614   161000    161459  ...         0.0        0.0       0
5955  20230614   161500    161959  ...         0.0        0.0       0
5956  20230614   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 16:25:00,822:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686731099, self.tradeDate='20230614', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25891.7, self.close=25903.5, self.high=25903.5, self.low=25890.0, self.vol=320.204, self.amt=8292138.699, ukdf['pct'].iloc[-1]=0.000456 , ukdf['amount'].iloc[-1]=8292138.699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13400.9898', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25902.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25875.6, self.close=25891.7, self.high=25900.0, self.low=25872.5 
127.0.0.1 - - [14/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-14 16:20:04,770:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25875.6, self.close=25891.7, self.high=25900.0, self.low=25872.5   
2023-06-14 16:20:06,330:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230614   155500    155959  1686729599  ...  25861.3  0.000120   1631    5
1632  20230614   160000    160459  1686729899  ...  25879.3  0.000498   1632    0
1633  20230614   160500    160959  1686730199  ...  25875.3 -0.000351   1633    1
1634  20230614   161000    161459  1686730499  ...  25873.7 -0.000475   1634    2
1635  20230614   161500    161959  1686730799  ...  25872.5  0.000622   1635    3

[5 rows x 11 columns]
2023-06-14 16:20:06,340:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=90, self.factor=0.5140835055440566, self.count=8995 

self.closeSec=1686731099, self.tradeDate='20230614', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25891.7, self.close=25903.5, self.high=25903.5, self.low=25890.0 
2023-06-14 16:25:00,770:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686731099, self.tradeDate='20230614', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25891.7, self.close=25903.5, self.high=25903.5, self.low=25890.0   
2023-06-14 16:25:00,806:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230614   160000    160459  1686729899  ...  25879.3  0.000498   1632    0
1633  20230614   160500    160959  1686730199  ...  25875.3 -0.000351   1633    1
1634  20230614   161000    161459  1686730499  ...  25873.7 -0.000475   1634    2
1635  20230614   161500    161959  1686730799  ...  25872.5  0.000622   1635    3
1636  20230614   162000    162459  1686731099  ...  25890.0  0.000456   1636    4

[5 rows x 11 columns]
2023-06-14 16:25:00,806:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-14 16:00:18,118:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230614    132959  25965.5  ...  47.916667  0.502971  0.648057
5787  20230614    135959  25951.9  ...  47.500000  0.473204  0.659967
5788  20230614    142959  25833.2  ...  47.500000  0.483839  0.667346
5789  20230614    145959  25873.7  ...  47.916667  0.485253  0.673736
5790  20230614    152959  25879.1  ...  47.916667  0.481910  0.680935

[5 rows x 33 columns]
0.5239852398523985
acc is : 0.5239852398523985
2023-06-14 16:00:18,220:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494937  0.505063       0  ...  1.008480  -1.0    0.0  0.951257
538     1  0.468866  0.531134       1  ...  1.006899  -1.0    0.0  0.952749
539     1  0.498480  0.501520       1  ...  1.006689  -1.0    0.0  0.952948
540     1  0.491686  0.508314       0  ...  1.007210  -1.0    0.0  0.952454
541     1  0.489410  0.510590       1  ...  1.006494  -1.0    0.0  0.953132

[5 rows x 10 columns]
2023-06-14 16:00:18,245:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494691  0.505309       0  ...  1.008480  -1.0    0.0  0.947882
46     1  0.469015  0.530985       1  ...  1.006899  -1.0    0.0  0.950421
47     1  0.498355  0.501645       1  ...  1.006689  -1.0    0.0  0.950466
48     1  0.491776  0.508224       0  ...  1.007210  -1.0    0.0  0.951018
49     1  0.489410  0.510590       1  ...  1.006494  -1.0    0.0  0.953132

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-9228.0902209626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25886.1796337', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230614   155000    155959  1686729599    25880  25884.1  0.000155
2023-06-14 16:00:02,141:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4496 

self.closeSec=1686730199, self.tradeDate='20230614', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25884.1', self.close='25888'
2023-06-14 16:10:01,121:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686730199, self.tradeDate='20230614', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25884.1', self.close='25888'
127.0.0.1 - - [14/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-14 16:10:01,131:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230614   152000    152959  1686727799  25886.6  25865.7 -0.000807
525  20230614   153000    153959  1686728399  25865.8  25863.9 -0.000070
526  20230614   154000    154959  1686728999  25863.9  25880.1  0.000626
527  20230614   155000    155959  1686729599    25880  25884.1  0.000155
528  20230614   160000    160959  1686730199  25884.1    25888  0.000151
2023-06-14 16:10:01,132:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4497 

self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25888', self.close='25891.7'
127.0.0.1 - - [14/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-14 16:20:07,329:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25888', self.close='25891.7'
2023-06-14 16:20:08,088:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230614   153000    153959  1686728399  25865.8  25863.9 -0.000070
526  20230614   154000    154959  1686728999  25863.9  25880.1  0.000626
527  20230614   155000    155959  1686729599    25880  25884.1  0.000155
528  20230614   160000    160959  1686730199  25884.1    25888  0.000151
529  20230614   161000    161959  1686730799    25888  25891.7  0.000143
2023-06-14 16:20:08,098:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230614   155000    155959  1686729599    25880  25884.1
2023-06-14 16:00:02,169:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4499 

self.closeSec=1686730199, self.tradeDate='20230614', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25884.1', self.close='25888'
2023-06-14 16:10:01,127:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686730199, self.tradeDate='20230614', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25884.1', self.close='25888'
2023-06-14 16:10:01,144:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230614   152000    152959  1686727799  25886.6  25865.7
17517  20230614   153000    153959  1686728399  25865.8  25863.9
17518  20230614   154000    154959  1686728999  25863.9  25880.1
17519  20230614   155000    155959  1686729599    25880  25884.1
17520  20230614   160000    160959  1686730199  25884.1    25888
2023-06-14 16:10:01,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4500 

self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25888', self.close='25891.7'
127.0.0.1 - - [14/Jun/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-06-14 16:20:08,984:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25888', self.close='25891.7'
2023-06-14 16:20:09,127:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230614   153000    153959  1686728399  25865.8  25863.9
17518  20230614   154000    154959  1686728999  25863.9  25880.1
17519  20230614   155000    155959  1686729599    25880  25884.1
17520  20230614   160000    160959  1686730199  25884.1    25888
17521  20230614   161000    161959  1686730799    25888  25891.7
2023-06-14 16:20:09,127:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230614   155000    155959  1686729599    25880  25884.1
2023-06-14 16:00:02,145:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4499 

self.closeSec=1686730199, self.tradeDate='20230614', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25884.1', self.close='25888'
2023-06-14 16:10:01,117:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686730199, self.tradeDate='20230614', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25884.1', self.close='25888'
127.0.0.1 - - [14/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-14 16:10:01,135:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230614   152000    152959  1686727799  25886.6  25865.7
12189  20230614   153000    153959  1686728399  25865.8  25863.9
12190  20230614   154000    154959  1686728999  25863.9  25880.1
12191  20230614   155000    155959  1686729599    25880  25884.1
12192  20230614   160000    160959  1686730199  25884.1    25888
2023-06-14 16:10:01,135:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4500 

self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25888', self.close='25891.7'
127.0.0.1 - - [14/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-14 16:20:08,652:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25888', self.close='25891.7'
2023-06-14 16:20:08,922:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230614   153000    153959  1686728399  25865.8  25863.9
12190  20230614   154000    154959  1686728999  25863.9  25880.1
12191  20230614   155000    155959  1686729599    25880  25884.1
12192  20230614   160000    160959  1686730199  25884.1    25888
12193  20230614   161000    161959  1686730799    25888  25891.7
2023-06-14 16:20:08,929:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8992
self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25875.6, self.close=25891.7, self.high=25900.0, self.low=25872.5, self.vol=524.052, self.amt=13566197.0609 
127.0.0.1 - - [14/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-14 16:20:07,280:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230614   155500    155959  ...         0.0        0.0       0
5952  20230614   160000    160459  ...         0.0        0.0       0
5953  20230614   160500    160959  ...         0.0        0.0       0
5954  20230614   161000    161459  ...         0.0        0.0       0
5955  20230614   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 16:20:07,310:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686730799, self.tradeDate='20230614', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25875.6, self.close=25891.7, self.high=25900.0, self.low=25872.5, self.vol=524.052, self.amt=13566197.0609, ukdf['pct'].iloc[-1]=0.000622 , ukdf['amount'].iloc[-1]=13566197.0609, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35322.2063182313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25892.9699707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8993
self.closeSec=1686731099, self.tradeDate='20230614', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25891.7, self.close=25903.5, self.high=25903.5, self.low=25890.0, self.vol=320.204, self.amt=8292138.699 
127.0.0.1 - - [14/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-14 16:25:00,818:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230614   160000    160459  ...         0.0        0.0       0
5953  20230614   160500    160959  ...         0.0        0.0       0
5954  20230614   161000    161459  ...         0.0        0.0       0
5955  20230614   161500    161959  ...         0.0        0.0       0
5956  20230614   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 16:25:00,818:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686731099, self.tradeDate='20230614', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25891.7, self.close=25903.5, self.high=25903.5, self.low=25890.0, self.vol=320.204, self.amt=8292138.699, ukdf['pct'].iloc[-1]=0.000456 , ukdf['amount'].iloc[-1]=8292138.699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-34964.5374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25902.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230614   040000    075959  1686700799  ...    721  0.092837 -1.599018    -1.0
722  20230614   080000    115959  1686715199  ...    722  0.038794 -1.770530    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '60876.36552289772', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25975.08759158', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [14/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=187
self.closeSec=1686729599, self.tradeDate='20230614', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25970.7, self.close=25884.1, self.high=25996.4, self.low=25820.0, self.vol=30116.376, self.amt=780011055.7656 
2023-06-14 16:00:01,748:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686729599, self.tradeDate='20230614', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25970.7, self.close=25884.1, self.high=25996.4, self.low=25820.0, self.vol=30116.376, self.amt=780011055.7656 
2023-06-14 16:00:01,771:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230613   200000    235959  ...  185012.495  4.820442e+09 -0.016315
720  20230614   000000    035959  ...   49220.461  1.272345e+09  0.005444
721  20230614   040000    075959  ...   28618.868  7.399962e+08  0.001035
722  20230614   080000    115959  ...   33269.028  8.642652e+08  0.002033
723  20230614   120000    155959  ...   30116.376  7.800111e+08 -0.003335

[5 rows x 11 columns]
2023-06-14 16:00:02,900:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230613   200000    235959  1686671999  ...    719  0.245567 -1.098139    -1.0
720  20230614   000000    035959  1686686399  ...    720  0.145470 -1.430737    -1.0
721  20230614   040000    075959  1686700799  ...    721  0.092837 -1.599018    -1.0
722  20230614   080000    115959  1686715199  ...    722  0.038794 -1.770530    -1.0
723  20230614   120000    155959  1686729599  ...    723  0.001596 -1.874697    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '65779.37986962636', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25886.21012454', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


