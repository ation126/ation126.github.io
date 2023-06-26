# 20230626 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12448
self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30403.4, self.close=30373.0, self.high=30407.6, self.low=30362.5, self.vol=1359.511, self.amt=41303402.5796 
127.0.0.1 - - [26/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-26 16:20:07,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230626   155500    155959  ...         0.0        0.0       0
5952  20230626   160000    160459  ...         0.0        0.0       0
5953  20230626   160500    160959  ...         0.0        0.0       0
5954  20230626   161000    161459  ...         0.0        0.0       0
5955  20230626   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 16:20:07,844:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30403.4, self.close=30373.0, self.high=30407.6, self.low=30362.5, self.vol=1359.511, self.amt=41303402.5796, ukdf['pct'].iloc[-1]=-0.001003 , ukdf['amount'].iloc[-1]=41303402.5796, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48821.8766222814', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30370.7075989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12449
self.closeSec=1687767899, self.tradeDate='20230626', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30372.9, self.close=30358.0, self.high=30389.2, self.low=30342.2, self.vol=673.857, self.amt=20459398.6529 
127.0.0.1 - - [26/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-26 16:25:00,836:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230626   160000    160459  ...         0.0        0.0       0
5953  20230626   160500    160959  ...         0.0        0.0       0
5954  20230626   161000    161459  ...         0.0        0.0       0
5955  20230626   161500    161959  ...         0.0        0.0       0
5956  20230626   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 16:25:00,836:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687767899, self.tradeDate='20230626', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30372.9, self.close=30358.0, self.high=30389.2, self.low=30342.2, self.vol=673.857, self.amt=20459398.6529, ukdf['pct'].iloc[-1]=-0.000494 , ukdf['amount'].iloc[-1]=20459398.6529, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48646.3032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30358.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30403.4, self.close=30373.0, self.high=30407.6, self.low=30362.5 
127.0.0.1 - - [26/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-26 16:20:05,102:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30403.4, self.close=30373.0, self.high=30407.6, self.low=30362.5   
2023-06-26 16:20:06,764:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230626   155500    155959  1687766399  ...  30385.8 -0.000368   1631    5
1632  20230626   160000    160459  1687766699  ...  30362.0 -0.001056   1632    0
1633  20230626   160500    160959  1687766999  ...  30326.4  0.000112   1633    1
1634  20230626   161000    161459  1687767299  ...  30362.4  0.001205   1634    2
1635  20230626   161500    161959  1687767599  ...  30362.5 -0.001003   1635    3

[5 rows x 11 columns]
2023-06-26 16:20:06,773:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6433244250214682, self.count=12451 

self.closeSec=1687767899, self.tradeDate='20230626', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30372.9, self.close=30358.0, self.high=30389.2, self.low=30342.2 
2023-06-26 16:25:00,760:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687767899, self.tradeDate='20230626', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30372.9, self.close=30358.0, self.high=30389.2, self.low=30342.2   
2023-06-26 16:25:00,811:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230626   160000    160459  1687766699  ...  30362.0 -0.001056   1632    0
1633  20230626   160500    160959  1687766999  ...  30326.4  0.000112   1633    1
1634  20230626   161000    161459  1687767299  ...  30362.4  0.001205   1634    2
1635  20230626   161500    161959  1687767599  ...  30362.5 -0.001003   1635    3
1636  20230626   162000    162459  1687767899  ...  30342.2 -0.000494   1636    4

[5 rows x 11 columns]
2023-06-26 16:25:00,812:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-26 16:00:19,075:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230626    132959  30235.7  ...  48.750000  0.454413  0.682687
5787  20230626    135959  30209.7  ...  48.333333  0.454152  0.680213
5788  20230626    142959  30208.1  ...  48.750000  0.468834  0.671713
5789  20230626    145959  30283.6  ...  48.750000  0.503356  0.648099
5790  20230626    152959  30474.8  ...  48.333333  0.492659  0.631194

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2023-06-26 16:00:19,154:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.499036  0.500964       0  ...  1.155051  -1.0    0.0  1.199043
538     1  0.498773  0.501227       1  ...  1.152164  -1.0    0.0  1.202040
539     0  0.511831  0.488169       1  ...  1.144889  -1.0    0.0  1.209629
540     0  0.546825  0.453175       0  ...  1.147241  -1.0    0.0  1.207145
541     0  0.504136  0.495864       0  ...  1.147867  -1.0    0.0  1.206486

[5 rows x 10 columns]
2023-06-26 16:00:19,166:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499206  0.500794       0  ...  1.184710  -1.0    0.0  1.207358
46     1  0.498823  0.501177       1  ...  1.181749  -1.0    0.0  1.208261
47     0  0.511752  0.488248       1  ...  1.174288  -1.0    0.0  1.213362
48     0  0.546948  0.453052       0  ...  1.147241  -1.0    0.0  1.210527
49     0  0.504136  0.495864       0  ...  1.147867  -1.0    0.0  1.206486

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.697', 'enterprice': '30938.2', 'countrevence': '0', 'unrealprofit': '14296.2435', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30402.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230626   155000    155959  1687766399  30349.1  30395.6  0.001532
2023-06-26 16:00:02,101:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6224 

self.closeSec=1687766999, self.tradeDate='20230626', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30395.5', self.close='30366.9'
2023-06-26 16:10:01,132:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687766999, self.tradeDate='20230626', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30395.5', self.close='30366.9'
2023-06-26 16:10:01,165:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230626   152000    152959  1687764599  30493.1  30412.2 -0.002650
525  20230626   153000    153959  1687765199  30412.3    30319 -0.003065
526  20230626   154000    154959  1687765799  30317.2  30349.1  0.000993
527  20230626   155000    155959  1687766399  30349.1  30395.6  0.001532
528  20230626   160000    160959  1687766999  30395.5  30366.9 -0.000944
2023-06-26 16:10:01,166:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6225 

self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30366.9', self.close='30373'
127.0.0.1 - - [26/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-26 16:20:07,492:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30366.9', self.close='30373'
2023-06-26 16:20:08,354:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230626   153000    153959  1687765199  30412.3    30319 -0.003065
526  20230626   154000    154959  1687765799  30317.2  30349.1  0.000993
527  20230626   155000    155959  1687766399  30349.1  30395.6  0.001532
528  20230626   160000    160959  1687766999  30395.5  30366.9 -0.000944
529  20230626   161000    161959  1687767599  30366.9    30373  0.000201
2023-06-26 16:20:08,363:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230626   155000    155959  1687766399  30349.1  30395.6
2023-06-26 16:00:02,118:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6227 

self.closeSec=1687766999, self.tradeDate='20230626', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30395.5', self.close='30366.9'
127.0.0.1 - - [26/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-26 16:10:01,130:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687766999, self.tradeDate='20230626', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30395.5', self.close='30366.9'
2023-06-26 16:10:01,138:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230626   152000    152959  1687764599  30493.1  30412.2
17517  20230626   153000    153959  1687765199  30412.3    30319
17518  20230626   154000    154959  1687765799  30317.2  30349.1
17519  20230626   155000    155959  1687766399  30349.1  30395.6
17520  20230626   160000    160959  1687766999  30395.5  30366.9
2023-06-26 16:10:01,139:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6228 

self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30366.9', self.close='30373'
127.0.0.1 - - [26/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-26 16:20:09,710:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30366.9', self.close='30373'
2023-06-26 16:20:09,844:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230626   153000    153959  1687765199  30412.3    30319
17518  20230626   154000    154959  1687765799  30317.2  30349.1
17519  20230626   155000    155959  1687766399  30349.1  30395.6
17520  20230626   160000    160959  1687766999  30395.5  30366.9
17521  20230626   161000    161959  1687767599  30366.9    30373
2023-06-26 16:20:09,845:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230626   155000    155959  1687766399  30349.1  30395.6
2023-06-26 16:00:02,098:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6227 

self.closeSec=1687766999, self.tradeDate='20230626', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30395.5', self.close='30366.9'
2023-06-26 16:10:01,144:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687766999, self.tradeDate='20230626', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30395.5', self.close='30366.9'
127.0.0.1 - - [26/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-26 16:10:01,157:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230626   152000    152959  1687764599  30493.1  30412.2
12189  20230626   153000    153959  1687765199  30412.3    30319
12190  20230626   154000    154959  1687765799  30317.2  30349.1
12191  20230626   155000    155959  1687766399  30349.1  30395.6
12192  20230626   160000    160959  1687766999  30395.5  30366.9
2023-06-26 16:10:01,157:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6228 

self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30366.9', self.close='30373'
127.0.0.1 - - [26/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-26 16:20:09,197:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30366.9', self.close='30373'
2023-06-26 16:20:09,535:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230626   153000    153959  1687765199  30412.3    30319
12190  20230626   154000    154959  1687765799  30317.2  30349.1
12191  20230626   155000    155959  1687766399  30349.1  30395.6
12192  20230626   160000    160959  1687766999  30395.5  30366.9
12193  20230626   161000    161959  1687767599  30366.9    30373
2023-06-26 16:20:09,544:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12448
self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30403.4, self.close=30373.0, self.high=30407.6, self.low=30362.5, self.vol=1359.511, self.amt=41303402.5796 
127.0.0.1 - - [26/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-26 16:20:07,782:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230626   155500    155959  ...         0.0        0.0       0
5952  20230626   160000    160459  ...         0.0        0.0       0
5953  20230626   160500    160959  ...         0.0        0.0       0
5954  20230626   161000    161459  ...         0.0        0.0       0
5955  20230626   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 16:20:07,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687767599, self.tradeDate='20230626', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30403.4, self.close=30373.0, self.high=30407.6, self.low=30362.5, self.vol=1359.511, self.amt=41303402.5796, ukdf['pct'].iloc[-1]=-0.001003 , ukdf['amount'].iloc[-1]=41303402.5796, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '130867.37120214082', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30367.52847802', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12449
self.closeSec=1687767899, self.tradeDate='20230626', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30372.9, self.close=30358.0, self.high=30389.2, self.low=30342.2, self.vol=673.857, self.amt=20459398.6529 
127.0.0.1 - - [26/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-26 16:25:00,835:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230626   160000    160459  ...         0.0        0.0       0
5953  20230626   160500    160959  ...         0.0        0.0       0
5954  20230626   161000    161459  ...         0.0        0.0       0
5955  20230626   161500    161959  ...         0.0        0.0       0
5956  20230626   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 16:25:00,836:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687767899, self.tradeDate='20230626', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30372.9, self.close=30358.0, self.high=30389.2, self.low=30342.2, self.vol=673.857, self.amt=20459398.6529, ukdf['pct'].iloc[-1]=-0.000494 , ukdf['amount'].iloc[-1]=20459398.6529, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '130517.1881', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30358.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230626   040000    075959  1687737599  ...    721  0.240057 -0.983551    -1.0
722  20230626   080000    115959  1687751999  ...    722  0.206493 -1.061974    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '22305.61861151136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30288.25669048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=259
self.closeSec=1687766399, self.tradeDate='20230626', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30284.9, self.close=30395.6, self.high=30580.0, self.low=30153.6, self.vol=60412.33, self.amt=1834276262.2683 
2023-06-26 16:00:01,669:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687766399, self.tradeDate='20230626', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30284.9, self.close=30395.6, self.high=30580.0, self.low=30153.6, self.vol=60412.33, self.amt=1834276262.2683 
2023-06-26 16:00:01,715:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230625   200000    235959  ...  60922.334  1.864297e+09 -0.004425
720  20230626   000000    035959  ...  49478.271  1.506910e+09 -0.005040
721  20230626   040000    075959  ...  38707.641  1.178424e+09  0.001249
722  20230626   080000    115959  ...  87301.166  2.637983e+09 -0.005680
723  20230626   120000    155959  ...  60412.330  1.834276e+09  0.003652

[5 rows x 11 columns]
2023-06-26 16:00:03,178:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230625   200000    235959  1687708799  ...    719  0.151870 -1.257836    -1.0
720  20230626   000000    035959  1687723199  ...    720  0.168752 -1.197892    -1.0
721  20230626   040000    075959  1687737599  ...    721  0.240057 -0.983551    -1.0
722  20230626   080000    115959  1687751999  ...    722  0.206493 -1.061974    -1.0
723  20230626   120000    155959  1687766399  ...    723  0.211291 -1.035406    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '16587.6552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30395.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


