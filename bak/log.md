# 20230728 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21664
self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29127.2, self.close=29143.1, self.high=29145.0, self.low=29121.8, self.vol=533.525, self.amt=15545686.0121 
127.0.0.1 - - [28/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-28 16:20:05,214:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230728   155500    155959  ...         0.0        0.0       0
5952  20230728   160000    160459  ...         0.0        0.0       0
5953  20230728   160500    160959  ...         0.0        0.0       0
5954  20230728   161000    161459  ...         0.0        0.0       0
5955  20230728   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 16:20:05,225:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29127.2, self.close=29143.1, self.high=29145.0, self.low=29121.8, self.vol=533.525, self.amt=15545686.0121, ukdf['pct'].iloc[-1]=0.000542 , ukdf['amount'].iloc[-1]=15545686.0121, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31724.8206', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29143', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21665
self.closeSec=1690532699, self.tradeDate='20230728', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29143.0, self.close=29151.3, self.high=29155.5, self.low=29140.0, self.vol=514.078, self.amt=14983856.9606 
2023-07-28 16:25:00,763:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230728   160000    160459  ...         0.0        0.0       0
5953  20230728   160500    160959  ...         0.0        0.0       0
5954  20230728   161000    161459  ...         0.0        0.0       0
5955  20230728   161500    161959  ...         0.0        0.0       0
5956  20230728   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 16:25:00,763:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690532699, self.tradeDate='20230728', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29143.0, self.close=29151.3, self.high=29155.5, self.low=29140.0, self.vol=514.078, self.amt=14983856.9606, ukdf['pct'].iloc[-1]=0.000281 , ukdf['amount'].iloc[-1]=14983856.9606, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31853.9339799252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29152.2713902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29127.2, self.close=29143.1, self.high=29145.0, self.low=29121.8 
127.0.0.1 - - [28/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-28 16:20:03,234:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29127.2, self.close=29143.1, self.high=29145.0, self.low=29121.8   
2023-07-28 16:20:04,273:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230728   155500    155959  1690531199  ...  29126.8 -0.000196   1631    5
1632  20230728   160000    160459  1690531499  ...  29126.3  0.000220   1632    0
1633  20230728   160500    160959  1690531799  ...  29115.0 -0.000628   1633    1
1634  20230728   161000    161459  1690532099  ...  29114.1  0.000422   1634    2
1635  20230728   161500    161959  1690532399  ...  29121.8  0.000542   1635    3

[5 rows x 11 columns]
2023-07-28 16:20:04,283:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6769465438061482, self.count=21667 

self.closeSec=1690532699, self.tradeDate='20230728', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29143.0, self.close=29151.3, self.high=29155.5, self.low=29140.0 
2023-07-28 16:25:00,743:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690532699, self.tradeDate='20230728', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29143.0, self.close=29151.3, self.high=29155.5, self.low=29140.0   
2023-07-28 16:25:00,757:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230728   160000    160459  1690531499  ...  29126.3  0.000220   1632    0
1633  20230728   160500    160959  1690531799  ...  29115.0 -0.000628   1633    1
1634  20230728   161000    161459  1690532099  ...  29114.1  0.000422   1634    2
1635  20230728   161500    161959  1690532399  ...  29121.8  0.000542   1635    3
1636  20230728   162000    162459  1690532699  ...  29140.0  0.000281   1636    4

[5 rows x 11 columns]
2023-07-28 16:25:00,757:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-28 16:00:17,500:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230728    132959  29249.4  ...  48.750000  0.464481  0.683001
5787  20230728    135959  29205.2  ...  48.750000  0.452671  0.689312
5788  20230728    142959  29172.0  ...  49.166667  0.453913  0.693788
5789  20230728    145959  29174.9  ...  49.166667  0.454174  0.697852
5790  20230728    152959  29175.5  ...  49.583333  0.456958  0.700708

[5 rows x 33 columns]
0.5608856088560885
acc is : 0.5608856088560885
2023-07-28 16:00:17,575:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.491074  0.508926       0  ...  0.919068   1.0    0.0  0.965944
538     1  0.488577  0.511423       1  ...  0.919159   1.0    0.0  0.966040
539     1  0.496091  0.503909       0  ...  0.919178   1.0    0.0  0.966060
540     1  0.497192  0.502808       1  ...  0.919377   1.0    0.0  0.966269
541     1  0.495051  0.504949       0  ...  0.917647   1.0    0.0  0.964451

[5 rows x 10 columns]
2023-07-28 16:00:17,588:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491082  0.508918       0  ...  0.919068   1.0    0.0  0.962471
46     1  0.488780  0.511220       1  ...  0.919159   1.0    0.0  0.966399
47     1  0.496034  0.503966       0  ...  0.919178   1.0    0.0  0.965539
48     1  0.497023  0.502977       1  ...  0.919377   1.0    0.0  0.964624
49     1  0.495051  0.504949       0  ...  0.917647   1.0    0.0  0.964451

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-8251.55130615426', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29131.55817843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230728   155000    155959  1690531199  29129.9  29126.9 -0.000103
2023-07-28 16:00:02,317:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10832 

self.closeSec=1690531799, self.tradeDate='20230728', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29126.9', self.close='29115'
2023-07-28 16:10:01,126:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690531799, self.tradeDate='20230728', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29126.9', self.close='29115'
2023-07-28 16:10:01,133:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230728   152000    152959  1690529399  29174.4  29181.8  0.000254
525  20230728   153000    153959  1690529999  29181.7    29163 -0.000644
526  20230728   154000    154959  1690530599    29163  29129.9 -0.001135
527  20230728   155000    155959  1690531199  29129.9  29126.9 -0.000103
528  20230728   160000    160959  1690531799  29126.9    29115 -0.000409
2023-07-28 16:10:01,133:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10833 

self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29115.1', self.close='29143'
127.0.0.1 - - [28/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-28 16:20:05,973:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29115.1', self.close='29143'
2023-07-28 16:20:06,293:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230728   153000    153959  1690529999  29181.7    29163 -0.000644
526  20230728   154000    154959  1690530599    29163  29129.9 -0.001135
527  20230728   155000    155959  1690531199  29129.9  29126.9 -0.000103
528  20230728   160000    160959  1690531799  29126.9    29115 -0.000409
529  20230728   161000    161959  1690532399  29115.1    29143  0.000962
2023-07-28 16:20:06,293:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230728   155000    155959  1690531199  29129.9  29126.9
2023-07-28 16:00:02,323:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10835 

self.closeSec=1690531799, self.tradeDate='20230728', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29126.9', self.close='29115'
2023-07-28 16:10:01,130:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690531799, self.tradeDate='20230728', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29126.9', self.close='29115'
2023-07-28 16:10:01,137:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230728   152000    152959  1690529399  29174.4  29181.8
17517  20230728   153000    153959  1690529999  29181.7    29163
17518  20230728   154000    154959  1690530599    29163  29129.9
17519  20230728   155000    155959  1690531199  29129.9  29126.9
17520  20230728   160000    160959  1690531799  29126.9    29115
2023-07-28 16:10:01,137:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10836 

self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29115.1', self.close='29143'
127.0.0.1 - - [28/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-28 16:20:06,995:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29115.1', self.close='29143'
2023-07-28 16:20:07,087:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230728   153000    153959  1690529999  29181.7    29163
17518  20230728   154000    154959  1690530599    29163  29129.9
17519  20230728   155000    155959  1690531199  29129.9  29126.9
17520  20230728   160000    160959  1690531799  29126.9    29115
17521  20230728   161000    161959  1690532399  29115.1    29143
2023-07-28 16:20:07,087:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230728   155000    155959  1690531199  29129.9  29126.9
2023-07-28 16:00:02,320:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10835 

self.closeSec=1690531799, self.tradeDate='20230728', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29126.9', self.close='29115'
2023-07-28 16:10:01,123:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690531799, self.tradeDate='20230728', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29126.9', self.close='29115'
2023-07-28 16:10:01,140:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230728   152000    152959  1690529399  29174.4  29181.8
12189  20230728   153000    153959  1690529999  29181.7    29163
12190  20230728   154000    154959  1690530599    29163  29129.9
12191  20230728   155000    155959  1690531199  29129.9  29126.9
12192  20230728   160000    160959  1690531799  29126.9    29115
2023-07-28 16:10:01,140:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10836 

self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29115.1', self.close='29143'
127.0.0.1 - - [28/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-28 16:20:06,894:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29115.1', self.close='29143'
2023-07-28 16:20:07,002:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230728   153000    153959  1690529999  29181.7    29163
12190  20230728   154000    154959  1690530599    29163  29129.9
12191  20230728   155000    155959  1690531199  29129.9  29126.9
12192  20230728   160000    160959  1690531799  29126.9    29115
12193  20230728   161000    161959  1690532399  29115.1    29143
2023-07-28 16:20:07,003:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21664
self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29127.2, self.close=29143.1, self.high=29145.0, self.low=29121.8, self.vol=533.525, self.amt=15545686.0121 
127.0.0.1 - - [28/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-28 16:20:05,257:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230728   155500    155959  ...         0.0        0.0       0
5952  20230728   160000    160459  ...         0.0        0.0       0
5953  20230728   160500    160959  ...         0.0        0.0       0
5954  20230728   161000    161459  ...         0.0        0.0       0
5955  20230728   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 16:20:05,284:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690532399, self.tradeDate='20230728', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29127.2, self.close=29143.1, self.high=29145.0, self.low=29121.8, self.vol=533.525, self.amt=15545686.0121, ukdf['pct'].iloc[-1]=0.000542 , ukdf['amount'].iloc[-1]=15545686.0121, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '85387.159', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29143', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [28/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21665
self.closeSec=1690532699, self.tradeDate='20230728', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29143.0, self.close=29151.3, self.high=29155.5, self.low=29140.0, self.vol=514.078, self.amt=14983856.9606 
2023-07-28 16:25:00,784:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230728   160000    160459  ...         0.0        0.0       0
5953  20230728   160500    160959  ...         0.0        0.0       0
5954  20230728   161000    161459  ...         0.0        0.0       0
5955  20230728   161500    161959  ...         0.0        0.0       0
5956  20230728   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-28 16:25:00,784:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690532699, self.tradeDate='20230728', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29143.0, self.close=29151.3, self.high=29155.5, self.low=29140.0, self.vol=514.078, self.amt=14983856.9606, ukdf['pct'].iloc[-1]=0.000281 , ukdf['amount'].iloc[-1]=14983856.9606, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '85731.5077034182', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29152.2713902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230727   200000    235959  ...  55283.047  1.623142e+09 -0.007320
720  20230728   000000    035959  ...  63642.422  1.857446e+09 -0.004283
721  20230728   040000    075959  ...  20489.076  5.978041e+08  0.001959
722  20230728   080000    115959  ...  23272.406  6.803464e+08  0.001030
723  20230728   120000    155959  ...  19221.001  5.608905e+08 -0.003861

[5 rows x 11 columns]
2023-07-28 16:00:02,610:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230727   200000    235959  1690473599  ...    719  0.644596  0.965451     1.0
720  20230728   000000    035959  1690487999  ...    720  0.702865  1.167903     1.0
721  20230728   040000    075959  1690502399  ...    721  0.490120  0.346234     NaN
722  20230728   080000    115959  1690516799  ...    722  0.335138 -0.248092     NaN
723  20230728   120000    155959  1690531199  ...    723  0.114819 -1.076804    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '685.49790795252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29130.10429412', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '686.27185109496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29130.11841176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-07-28 16:00:09,353:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1599993.9146797', 'total': '1599993.9146797', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-07-28 16:00:09,864:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 54.767, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42752F1690531209862I0L65'}
2023-07-28 16:00:09,882:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:7281600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230728, closeTime:155959, close:29126.9, sign:-1, total:1599993.9146797, side:sell  
127.0.0.1 - - [28/Jul/2023 16:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Jul/2023 16:00:09] "POST / HTTP/1.1" 200 -
2023-07-28 16:00:09,885:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42751F1690531204292I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690531204700121, 'quantity': '54.821', 'price': '29126.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690531203443, 'updatetime': 1690531204700, 'tradetype': 'usdt', 'selfid': 42751, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690531204700, 'clientorderid': '42751F1690531204292I0L65', 'price': '29126.8', 'quantity': '54.821', 'commission': '1596.7603028', 'commissionasset': 'USDT', 'tradetime': 1690531204700, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690531204700}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-28 16:00:09,886:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42751F1690531204292I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690531204700121, 'quantity': '54.821', 'price': '29126.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690531203443, 'updatetime': 1690531204700, 'tradetype': 'usdt', 'selfid': 42751, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690531204700, 'clientorderid': '42751F1690531204292I0L65', 'price': '29126.8', 'quantity': '54.821', 'commission': '1596.7603028', 'commissionasset': 'USDT', 'tradetime': 1690531204700, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690531204700}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jul/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-07-28 16:00:10,311:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42752F1690531209862I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690531210255988, 'quantity': '54.767', 'price': '29133.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690531209366, 'updatetime': 1690531210255, 'tradetype': 'usdt', 'selfid': 42752, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690531210255, 'clientorderid': '42752F1690531209862I0L65', 'price': '29133.6', 'quantity': '54.767', 'commission': '1595.5598712', 'commissionasset': 'USDT', 'tradetime': 1690531210255, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690531210255}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-28 16:00:10,440:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42752F1690531209862I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690531210255988, 'quantity': '54.767', 'price': '29133.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690531209366, 'updatetime': 1690531210255, 'tradetype': 'usdt', 'selfid': 42752, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690531210255, 'clientorderid': '42752F1690531209862I0L65', 'price': '29133.6', 'quantity': '54.767', 'commission': '1595.5598712', 'commissionasset': 'USDT', 'tradetime': 1690531210255, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690531210255}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jul/2023 16:00:10] "POST / HTTP/1.1" 200 -


