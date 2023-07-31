# 20230731 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22528
self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29369.0, self.close=29349.0, self.high=29373.9, self.low=29340.6, self.vol=845.288, self.amt=24814046.7682 
127.0.0.1 - - [31/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-31 16:20:05,306:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230731   155500    155959  ...         0.0        0.0       0
5952  20230731   160000    160459  ...         0.0        0.0       0
5953  20230731   160500    160959  ...         0.0        0.0       0
5954  20230731   161000    161459  ...         0.0        0.0       0
5955  20230731   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 16:20:05,326:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29369.0, self.close=29349.0, self.high=29373.9, self.low=29340.6, self.vol=845.288, self.amt=24814046.7682, ukdf['pct'].iloc[-1]=-0.000684 , ukdf['amount'].iloc[-1]=24814046.7682, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34594.00626556248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29349.03085348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22529
self.closeSec=1690791899, self.tradeDate='20230731', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29349.1, self.close=29380.7, self.high=29380.7, self.low=29349.0, self.vol=597.435, self.amt=17542955.1303 
127.0.0.1 - - [31/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-31 16:25:00,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230731   160000    160459  ...         0.0        0.0       0
5953  20230731   160500    160959  ...         0.0        0.0       0
5954  20230731   161000    161459  ...         0.0        0.0       0
5955  20230731   161500    161959  ...         0.0        0.0       0
5956  20230731   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 16:25:00,776:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690791899, self.tradeDate='20230731', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29349.1, self.close=29380.7, self.high=29380.7, self.low=29349.0, self.vol=597.435, self.amt=17542955.1303, ukdf['pct'].iloc[-1]=0.00108 , ukdf['amount'].iloc[-1]=17542955.1303, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35035.0308', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29380.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29369.0, self.close=29349.0, self.high=29373.9, self.low=29340.6 
127.0.0.1 - - [31/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-31 16:20:03,846:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29369.0, self.close=29349.0, self.high=29373.9, self.low=29340.6   
2023-07-31 16:20:04,765:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230731   155500    155959  1690790399  ...  29362.3 -0.000368   1631    5
1632  20230731   160000    160459  1690790699  ...  29358.6  0.000054   1632    0
1633  20230731   160500    160959  1690790999  ...  29362.7 -0.000061   1633    1
1634  20230731   161000    161459  1690791299  ...  29363.5  0.000187   1634    2
1635  20230731   161500    161959  1690791599  ...  29340.6 -0.000684   1635    3

[5 rows x 11 columns]
2023-07-31 16:20:04,766:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.44332550901361245, self.count=22531 

self.closeSec=1690791899, self.tradeDate='20230731', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29349.1, self.close=29380.7, self.high=29380.7, self.low=29349.0 
127.0.0.1 - - [31/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-31 16:25:00,760:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690791899, self.tradeDate='20230731', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29349.1, self.close=29380.7, self.high=29380.7, self.low=29349.0   
2023-07-31 16:25:00,780:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230731   160000    160459  1690790699  ...  29358.6  0.000054   1632    0
1633  20230731   160500    160959  1690790999  ...  29362.7 -0.000061   1633    1
1634  20230731   161000    161459  1690791299  ...  29363.5  0.000187   1634    2
1635  20230731   161500    161959  1690791599  ...  29340.6 -0.000684   1635    3
1636  20230731   162000    162459  1690791899  ...  29349.0  0.001080   1636    4

[5 rows x 11 columns]
2023-07-31 16:25:00,780:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-31 16:00:16,758:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230731    132959  29389.0  ...  47.083333  0.529962  0.352577
5787  20230731    135959  29390.5  ...  46.666667  0.520524  0.349324
5788  20230731    142959  29367.8  ...  47.083333  0.537842  0.340310
5789  20230731    145959  29414.5  ...  47.083333  0.531785  0.333744
5790  20230731    152959  29400.1  ...  46.666667  0.530473  0.328014

[5 rows x 33 columns]
0.5701107011070111
acc is : 0.5701107011070111
2023-07-31 16:00:16,819:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.496432  0.503568       0  ...  0.931995   1.0    0.0  0.979420
538     1  0.492899  0.507101       1  ...  0.933474   1.0    0.0  0.980974
539     0  0.514497  0.485503       0  ...  0.933017   1.0    0.0  0.980494
540     0  0.500106  0.499894       0  ...  0.932919   1.0    0.0  0.980390
541     0  0.503191  0.496809       0  ...  0.931865   1.0    0.0  0.979283

[5 rows x 10 columns]
2023-07-31 16:00:16,830:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496717  0.503283       0  ...  0.931995   1.0    0.0  0.983648
46     1  0.493030  0.506970       1  ...  0.933474   1.0    0.0  0.983842
47     0  0.514873  0.485127       0  ...  0.933017   1.0    0.0  0.983429
48     0  0.500255  0.499745       0  ...  0.932919   1.0    0.0  0.983210
49     0  0.503191  0.496809       0  ...  0.931865   1.0    0.0  0.979283

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-2755.7426', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29362.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230731   155000    155959  1690790399  29379.9  29363.8 -0.000545
2023-07-31 16:00:02,057:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [31/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11264 

self.closeSec=1690790999, self.tradeDate='20230731', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29363.8', self.close='29363.6'
2023-07-31 16:10:01,211:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690790999, self.tradeDate='20230731', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29363.8', self.close='29363.6'
2023-07-31 16:10:01,221:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230731   152000    152959  1690788599    29381    29397  0.000582
525  20230731   153000    153959  1690789199  29397.1  29383.3 -0.000466
526  20230731   154000    154959  1690789799  29383.2  29379.8 -0.000119
527  20230731   155000    155959  1690790399  29379.9  29363.8 -0.000545
528  20230731   160000    160959  1690790999  29363.8  29363.6 -0.000007
2023-07-31 16:10:01,221:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11265 

self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29363.5', self.close='29349'
127.0.0.1 - - [31/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-31 16:20:05,956:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29363.5', self.close='29349'
2023-07-31 16:20:06,355:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230731   153000    153959  1690789199  29397.1  29383.3 -0.000466
526  20230731   154000    154959  1690789799  29383.2  29379.8 -0.000119
527  20230731   155000    155959  1690790399  29379.9  29363.8 -0.000545
528  20230731   160000    160959  1690790999  29363.8  29363.6 -0.000007
529  20230731   161000    161959  1690791599  29363.5    29349 -0.000497
2023-07-31 16:20:06,355:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230731   155000    155959  1690790399  29379.9  29363.8
2023-07-31 16:00:02,065:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11267 

self.closeSec=1690790999, self.tradeDate='20230731', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29363.8', self.close='29363.6'
127.0.0.1 - - [31/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-31 16:10:01,223:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690790999, self.tradeDate='20230731', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29363.8', self.close='29363.6'
2023-07-31 16:10:01,229:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230731   152000    152959  1690788599    29381    29397
17517  20230731   153000    153959  1690789199  29397.1  29383.3
17518  20230731   154000    154959  1690789799  29383.2  29379.8
17519  20230731   155000    155959  1690790399  29379.9  29363.8
17520  20230731   160000    160959  1690790999  29363.8  29363.6
2023-07-31 16:10:01,229:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11268 

self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29363.5', self.close='29349'
127.0.0.1 - - [31/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-31 16:20:07,062:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29363.5', self.close='29349'
2023-07-31 16:20:07,156:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230731   153000    153959  1690789199  29397.1  29383.3
17518  20230731   154000    154959  1690789799  29383.2  29379.8
17519  20230731   155000    155959  1690790399  29379.9  29363.8
17520  20230731   160000    160959  1690790999  29363.8  29363.6
17521  20230731   161000    161959  1690791599  29363.5    29349
2023-07-31 16:20:07,156:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230731   155000    155959  1690790399  29379.9  29363.8
2023-07-31 16:00:02,041:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11267 

self.closeSec=1690790999, self.tradeDate='20230731', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29363.8', self.close='29363.6'
2023-07-31 16:10:01,215:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690790999, self.tradeDate='20230731', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29363.8', self.close='29363.6'
127.0.0.1 - - [31/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-31 16:10:01,226:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230731   152000    152959  1690788599    29381    29397
12189  20230731   153000    153959  1690789199  29397.1  29383.3
12190  20230731   154000    154959  1690789799  29383.2  29379.8
12191  20230731   155000    155959  1690790399  29379.9  29363.8
12192  20230731   160000    160959  1690790999  29363.8  29363.6
2023-07-31 16:10:01,227:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11268 

self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29363.5', self.close='29349'
127.0.0.1 - - [31/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-31 16:20:06,956:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29363.5', self.close='29349'
2023-07-31 16:20:07,066:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230731   153000    153959  1690789199  29397.1  29383.3
12190  20230731   154000    154959  1690789799  29383.2  29379.8
12191  20230731   155000    155959  1690790399  29379.9  29363.8
12192  20230731   160000    160959  1690790999  29363.8  29363.6
12193  20230731   161000    161959  1690791599  29363.5    29349
2023-07-31 16:20:07,066:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22528
self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29369.0, self.close=29349.0, self.high=29373.9, self.low=29340.6, self.vol=845.288, self.amt=24814046.7682 
127.0.0.1 - - [31/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-31 16:20:05,305:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230731   155500    155959  ...         0.0        0.0       0
5952  20230731   160000    160459  ...         0.0        0.0       0
5953  20230731   160500    160959  ...         0.0        0.0       0
5954  20230731   161000    161459  ...         0.0        0.0       0
5955  20230731   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 16:20:05,316:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690791599, self.tradeDate='20230731', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29369.0, self.close=29349.0, self.high=29373.9, self.low=29340.6, self.vol=845.288, self.amt=24814046.7682, ukdf['pct'].iloc[-1]=-0.000684 , ukdf['amount'].iloc[-1]=24814046.7682, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '93039.35092910068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29349.03085348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22529
self.closeSec=1690791899, self.tradeDate='20230731', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29349.1, self.close=29380.7, self.high=29380.7, self.low=29349.0, self.vol=597.435, self.amt=17542955.1303 
127.0.0.1 - - [31/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-31 16:25:00,795:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230731   160000    160459  ...         0.0        0.0       0
5953  20230731   160500    160959  ...         0.0        0.0       0
5954  20230731   161000    161459  ...         0.0        0.0       0
5955  20230731   161500    161959  ...         0.0        0.0       0
5956  20230731   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 16:25:00,797:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690791899, self.tradeDate='20230731', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29349.1, self.close=29380.7, self.high=29380.7, self.low=29349.0, self.vol=597.435, self.amt=17542955.1303, ukdf['pct'].iloc[-1]=0.00108 , ukdf['amount'].iloc[-1]=17542955.1303, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '94215.5747', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29380.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230731   040000    075959  1690761599  ...    721  0.098298 -0.965533    -1.0
722  20230731   080000    115959  1690775999  ...    722  0.101916 -0.929582    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-8957.1792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29413.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [31/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=469
self.closeSec=1690790399, self.tradeDate='20230731', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29411.8, self.close=29363.8, self.high=29434.5, self.low=29343.0, self.vol=19913.294, self.amt=585237661.997 
2023-07-31 16:00:01,627:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690790399, self.tradeDate='20230731', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29411.8, self.close=29363.8, self.high=29434.5, self.low=29343.0, self.vol=19913.294, self.amt=585237661.997 
2023-07-31 16:00:01,640:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230730   200000    235959  ...  40656.643  1.193675e+09  0.001222
720  20230731   000000    035959  ...  37631.169  1.101025e+09 -0.005110
721  20230731   040000    075959  ...  50696.613  1.478429e+09  0.002875
722  20230731   080000    115959  ...  49619.636  1.459752e+09  0.004807
723  20230731   120000    155959  ...  19913.294  5.852377e+08 -0.001632

[5 rows x 11 columns]
2023-07-31 16:00:02,296:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230730   200000    235959  1690732799  ...    719  0.097821 -1.014500    -1.0
720  20230731   000000    035959  1690747199  ...    720  0.066577 -1.120057    -1.0
721  20230731   040000    075959  1690761599  ...    721  0.098298 -0.965533    -1.0
722  20230731   080000    115959  1690775999  ...    722  0.101916 -0.929582    -1.0
723  20230731   120000    155959  1690790399  ...    723  0.097876 -0.926380    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-6250.5768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29363.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


