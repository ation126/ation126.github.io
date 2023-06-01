# 20230601 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5248
self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26808.9, self.close=26827.8, self.high=26827.8, self.low=26806.6, self.vol=541.121, self.amt=14509933.6035 
127.0.0.1 - - [01/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-01 16:20:06,758:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230601   155500    155959  ...         0.0        0.0       0
5952  20230601   160000    160459  ...         0.0        0.0       0
5953  20230601   160500    160959  ...         0.0        0.0       0
5954  20230601   161000    161459  ...         0.0        0.0       0
5955  20230601   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 16:20:06,786:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26808.9, self.close=26827.8, self.high=26827.8, self.low=26806.6, self.vol=541.121, self.amt=14509933.6035, ukdf['pct'].iloc[-1]=0.000701 , ukdf['amount'].iloc[-1]=14509933.6035, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '527.7954', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26827', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5249
self.closeSec=1685607899, self.tradeDate='20230601', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26827.8, self.close=26813.0, self.high=26831.5, self.low=26807.6, self.vol=428.328, self.amt=11486676.2242 
127.0.0.1 - - [01/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-01 16:25:00,799:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230601   160000    160459  ...         0.0        0.0       0
5953  20230601   160500    160959  ...         0.0        0.0       0
5954  20230601   161000    161459  ...         0.0        0.0       0
5955  20230601   161500    161959  ...         0.0        0.0       0
5956  20230601   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 16:25:00,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685607899, self.tradeDate='20230601', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26827.8, self.close=26813.0, self.high=26831.5, self.low=26807.6, self.vol=428.328, self.amt=11486676.2242, ukdf['pct'].iloc[-1]=-0.000552 , ukdf['amount'].iloc[-1]=11486676.2242, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '722.7594', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26813', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26808.9, self.close=26827.8, self.high=26827.8, self.low=26806.6 
127.0.0.1 - - [01/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-01 16:20:04,705:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26808.9, self.close=26827.8, self.high=26827.8, self.low=26806.6   
2023-06-01 16:20:05,905:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230601   155500    155959  1685606399  ...  26775.3  0.000549   1631    5
1632  20230601   160000    160459  1685606699  ...  26776.7 -0.000004   1632    0
1633  20230601   160500    160959  1685606999  ...  26787.3  0.000347   1633    1
1634  20230601   161000    161459  1685607299  ...  26795.1  0.000362   1634    2
1635  20230601   161500    161959  1685607599  ...  26806.6  0.000701   1635    3

[5 rows x 11 columns]
2023-06-01 16:20:05,906:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7116573637420786, self.count=5251 

self.closeSec=1685607899, self.tradeDate='20230601', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26827.8, self.close=26813.0, self.high=26831.5, self.low=26807.6 
127.0.0.1 - - [01/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-01 16:25:00,722:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685607899, self.tradeDate='20230601', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26827.8, self.close=26813.0, self.high=26831.5, self.low=26807.6   
2023-06-01 16:25:00,762:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230601   160000    160459  1685606699  ...  26776.7 -0.000004   1632    0
1633  20230601   160500    160959  1685606999  ...  26787.3  0.000347   1633    1
1634  20230601   161000    161459  1685607299  ...  26795.1  0.000362   1634    2
1635  20230601   161500    161959  1685607599  ...  26806.6  0.000701   1635    3
1636  20230601   162000    162459  1685607899  ...  26807.6 -0.000552   1636    4

[5 rows x 11 columns]
2023-06-01 16:25:00,762:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-01 16:00:34,351:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230601    132959  26797.1  ...  50.416667  0.414501  0.710171
5787  20230601    135959  26823.9  ...  50.833333  0.418551  0.707939
5788  20230601    142959  26843.0  ...  50.833333  0.411988  0.709457
5789  20230601    145959  26801.5  ...  50.416667  0.408141  0.712996
5790  20230601    152959  26777.6  ...  50.833333  0.423309  0.710442

[5 rows x 33 columns]
0.5166051660516605
acc is : 0.5166051660516605
2023-06-01 16:00:34,510:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.515971  0.484029       1  ...  1.081551  -1.0    0.0  0.985783
538     0  0.514197  0.485803       0  ...  1.083179  -1.0    0.0  0.984300
539     1  0.497912  0.502088       0  ...  1.084141  -1.0    0.0  0.983426
540     1  0.499538  0.500462       1  ...  1.081481  -1.0    0.0  0.985839
541     0  0.517383  0.482617       0  ...  1.083624  -1.0    0.0  0.983885

[5 rows x 10 columns]
2023-06-01 16:00:34,540:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515979  0.484021       1  ...  1.081551  -1.0    0.0  0.992123
46     0  0.514574  0.485426       0  ...  1.042930  -1.0    0.0  0.990744
47     1  0.497927  0.502073       0  ...  1.084141  -1.0    0.0  0.988486
48     1  0.499842  0.500158       1  ...  1.041295  -1.0    0.0  0.991512
49     0  0.517383  0.482617       0  ...  1.083624  -1.0    0.0  0.983885

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '29520.92256043832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26793.24721032', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230601   155000    155959  1685606399  26787.2  26790.2  0.000112
2023-06-01 16:00:02,335:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2624 

self.closeSec=1685606999, self.tradeDate='20230601', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26790.1', self.close='26799.3'
2023-06-01 16:10:01,092:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685606999, self.tradeDate='20230601', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26790.1', self.close='26799.3'
127.0.0.1 - - [01/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-01 16:10:01,141:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230601   152000    152959  1685604599  26795.2  26843.3  0.001791
525  20230601   153000    153959  1685605199  26843.3  26828.6 -0.000548
526  20230601   154000    154959  1685605799  26828.6  26787.2 -0.001543
527  20230601   155000    155959  1685606399  26787.2  26790.2  0.000112
528  20230601   160000    160959  1685606999  26790.1  26799.3  0.000340
2023-06-01 16:10:01,143:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2625 

self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26799.3', self.close='26827.8'
127.0.0.1 - - [01/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-01 16:20:06,759:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26799.3', self.close='26827.8'
2023-06-01 16:20:07,279:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230601   153000    153959  1685605199  26843.3  26828.6 -0.000548
526  20230601   154000    154959  1685605799  26828.6  26787.2 -0.001543
527  20230601   155000    155959  1685606399  26787.2  26790.2  0.000112
528  20230601   160000    160959  1685606999  26790.1  26799.3  0.000340
529  20230601   161000    161959  1685607599  26799.3  26827.8  0.001063
2023-06-01 16:20:07,288:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230601   155000    155959  1685606399  26787.2  26790.2
2023-06-01 16:00:02,337:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2627 

self.closeSec=1685606999, self.tradeDate='20230601', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26790.1', self.close='26799.3'
2023-06-01 16:10:01,102:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685606999, self.tradeDate='20230601', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26790.1', self.close='26799.3'
127.0.0.1 - - [01/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-01 16:10:01,122:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230601   152000    152959  1685604599  26795.2  26843.3
17517  20230601   153000    153959  1685605199  26843.3  26828.6
17518  20230601   154000    154959  1685605799  26828.6  26787.2
17519  20230601   155000    155959  1685606399  26787.2  26790.2
17520  20230601   160000    160959  1685606999  26790.1  26799.3
2023-06-01 16:10:01,122:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2628 

self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26799.3', self.close='26827.8'
127.0.0.1 - - [01/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-01 16:20:08,330:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26799.3', self.close='26827.8'
2023-06-01 16:20:08,444:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230601   153000    153959  1685605199  26843.3  26828.6
17518  20230601   154000    154959  1685605799  26828.6  26787.2
17519  20230601   155000    155959  1685606399  26787.2  26790.2
17520  20230601   160000    160959  1685606999  26790.1  26799.3
17521  20230601   161000    161959  1685607599  26799.3  26827.8
2023-06-01 16:20:08,444:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230601   155000    155959  1685606399  26787.2  26790.2
2023-06-01 16:00:02,330:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2627 

self.closeSec=1685606999, self.tradeDate='20230601', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26790.1', self.close='26799.3'
2023-06-01 16:10:01,094:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685606999, self.tradeDate='20230601', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26790.1', self.close='26799.3'
127.0.0.1 - - [01/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-01 16:10:01,120:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230601   152000    152959  1685604599  26795.2  26843.3
12189  20230601   153000    153959  1685605199  26843.3  26828.6
12190  20230601   154000    154959  1685605799  26828.6  26787.2
12191  20230601   155000    155959  1685606399  26787.2  26790.2
12192  20230601   160000    160959  1685606999  26790.1  26799.3
2023-06-01 16:10:01,120:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2628 

self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26799.3', self.close='26827.8'
127.0.0.1 - - [01/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-01 16:20:08,011:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26799.3', self.close='26827.8'
2023-06-01 16:20:08,267:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230601   153000    153959  1685605199  26843.3  26828.6
12190  20230601   154000    154959  1685605799  26828.6  26787.2
12191  20230601   155000    155959  1685606399  26787.2  26790.2
12192  20230601   160000    160959  1685606999  26790.1  26799.3
12193  20230601   161000    161959  1685607599  26799.3  26827.8
2023-06-01 16:20:08,268:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5248
self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26808.9, self.close=26827.8, self.high=26827.8, self.low=26806.6, self.vol=541.121, self.amt=14509933.6035 
127.0.0.1 - - [01/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-01 16:20:06,766:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230601   155500    155959  ...         0.0        0.0       0
5952  20230601   160000    160459  ...         0.0        0.0       0
5953  20230601   160500    160959  ...         0.0        0.0       0
5954  20230601   161000    161459  ...         0.0        0.0       0
5955  20230601   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 16:20:06,785:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685607599, self.tradeDate='20230601', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26808.9, self.close=26827.8, self.high=26827.8, self.low=26806.6, self.vol=541.121, self.amt=14509933.6035, ukdf['pct'].iloc[-1]=0.000701 , ukdf['amount'].iloc[-1]=14509933.6035, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-631.397', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26827', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5249
self.closeSec=1685607899, self.tradeDate='20230601', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26827.8, self.close=26813.0, self.high=26831.5, self.low=26807.6, self.vol=428.328, self.amt=11486676.2242 
2023-06-01 16:25:00,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230601   160000    160459  ...         0.0        0.0       0
5953  20230601   160500    160959  ...         0.0        0.0       0
5954  20230601   161000    161459  ...         0.0        0.0       0
5955  20230601   161500    161959  ...         0.0        0.0       0
5956  20230601   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 16:25:00,790:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685607899, self.tradeDate='20230601', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26827.8, self.close=26813.0, self.high=26831.5, self.low=26807.6, self.vol=428.328, self.amt=11486676.2242, ukdf['pct'].iloc[-1]=-0.000552 , ukdf['amount'].iloc[-1]=11486676.2242, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1151.371', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26813', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230601   040000    075959  1685577599  ...    721  0.807567  0.836682     1.0
722  20230601   080000    115959  1685591999  ...    722  0.590263  0.196307     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '35580.356', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26772.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=109
self.closeSec=1685606399, self.tradeDate='20230601', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26768.6, self.close=26790.1, self.high=26876.6, self.low=26742.0, self.vol=39306.804, self.amt=1053710626.1979 
127.0.0.1 - - [01/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-01 16:00:01,821:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685606399, self.tradeDate='20230601', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26768.6, self.close=26790.1, self.high=26876.6, self.low=26742.0, self.vol=39306.804, self.amt=1053710626.1979 
2023-06-01 16:00:01,852:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230531   200000    235959  ...  119487.274  3.226958e+09 -0.006933
720  20230601   000000    035959  ...   58700.858  1.584253e+09  0.003639
721  20230601   040000    075959  ...   40645.961  1.103126e+09  0.007523
722  20230601   080000    115959  ...  121061.589  3.261094e+09 -0.015900
723  20230601   120000    155959  ...   39306.804  1.053711e+09  0.000803

[5 rows x 11 columns]
2023-06-01 16:00:03,843:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230531   200000    235959  1685548799  ...    719  0.890645  1.114161     1.0
720  20230601   000000    035959  1685563199  ...    720  0.855047  0.988011     1.0
721  20230601   040000    075959  1685577599  ...    721  0.807567  0.836682     1.0
722  20230601   080000    115959  1685591999  ...    722  0.590263  0.196307     NaN
723  20230601   120000    155959  1685606399  ...    723  0.684852  0.484603     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '36821.13541104262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26794.65795238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


