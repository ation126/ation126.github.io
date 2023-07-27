# 20230727 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21376
self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29401.2, self.close=29396.6, self.high=29401.2, self.low=29391.0, self.vol=401.6, self.amt=11806008.4582 
127.0.0.1 - - [27/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-27 16:20:04,375:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230727   155500    155959  ...         0.0        0.0       0
5952  20230727   160000    160459  ...         0.0        0.0       0
5953  20230727   160500    160959  ...         0.0        0.0       0
5954  20230727   161000    161459  ...         0.0        0.0       0
5955  20230727   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 16:20:04,394:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29401.2, self.close=29396.6, self.high=29401.2, self.low=29391.0, self.vol=401.6, self.amt=11806008.4582, ukdf['pct'].iloc[-1]=-0.000156 , ukdf['amount'].iloc[-1]=11806008.4582, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35239.46792055756', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29395.38024706', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21377
self.closeSec=1690446299, self.tradeDate='20230727', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29396.5, self.close=29399.7, self.high=29399.8, self.low=29386.4, self.vol=328.072, self.amt=9643080.6078 
127.0.0.1 - - [27/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-27 16:25:00,794:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230727   160000    160459  ...         0.0        0.0       0
5953  20230727   160500    160959  ...         0.0        0.0       0
5954  20230727   161000    161459  ...         0.0        0.0       0
5955  20230727   161500    161959  ...         0.0        0.0       0
5956  20230727   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 16:25:00,794:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690446299, self.tradeDate='20230727', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29396.5, self.close=29399.7, self.high=29399.8, self.low=29386.4, self.vol=328.072, self.amt=9643080.6078, ukdf['pct'].iloc[-1]=0.000105 , ukdf['amount'].iloc[-1]=9643080.6078, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35301.0174', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29399.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29401.2, self.close=29396.6, self.high=29401.2, self.low=29391.0 
127.0.0.1 - - [27/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-27 16:20:02,845:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29401.2, self.close=29396.6, self.high=29401.2, self.low=29391.0   
2023-07-27 16:20:03,785:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230727   155500    155959  1690444799  ...  29393.5 -0.000418   1631    5
1632  20230727   160000    160459  1690445099  ...  29385.0 -0.000405   1632    0
1633  20230727   160500    160959  1690445399  ...  29380.0  0.000099   1633    1
1634  20230727   161000    161459  1690445699  ...  29388.0  0.000453   1634    2
1635  20230727   161500    161959  1690445999  ...  29391.0 -0.000156   1635    3

[5 rows x 11 columns]
2023-07-27 16:20:03,786:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=35, self.factor=0.4284089979673533, self.count=21379 

self.closeSec=1690446299, self.tradeDate='20230727', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29396.5, self.close=29399.7, self.high=29399.8, self.low=29386.4 
2023-07-27 16:25:00,747:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690446299, self.tradeDate='20230727', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29396.5, self.close=29399.7, self.high=29399.8, self.low=29386.4   
2023-07-27 16:25:00,766:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230727   160000    160459  1690445099  ...  29385.0 -0.000405   1632    0
1633  20230727   160500    160959  1690445399  ...  29380.0  0.000099   1633    1
1634  20230727   161000    161459  1690445699  ...  29388.0  0.000453   1634    2
1635  20230727   161500    161959  1690445999  ...  29391.0 -0.000156   1635    3
1636  20230727   162000    162459  1690446299  ...  29386.4  0.000105   1636    4

[5 rows x 11 columns]
2023-07-27 16:25:00,766:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-27 16:00:17,582:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230727    132959  29473.9  ...  50.416667  0.544464  0.464228
5787  20230727    135959  29458.3  ...  50.000000  0.540083  0.461784
5788  20230727    142959  29446.0  ...  49.583333  0.535123  0.461280
5789  20230727    145959  29432.0  ...  49.166667  0.513336  0.468855
5790  20230727    152959  29368.5  ...  49.166667  0.528895  0.469529

[5 rows x 33 columns]
0.5682656826568265
acc is : 0.5682656826568265
2023-07-27 16:00:17,643:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.504082  0.495918       0  ...  0.927697   1.0    0.0  0.972136
538     0  0.503706  0.496294       0  ...  0.927256   1.0    0.0  0.971674
539     0  0.504514  0.495486       0  ...  0.925259   1.0    0.0  0.969581
540     1  0.484288  0.515712       1  ...  0.926847   1.0    0.0  0.971245
541     0  0.509447  0.490553       0  ...  0.926154   1.0    0.0  0.970518

[5 rows x 10 columns]
2023-07-27 16:00:17,654:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504451  0.495549       0  ...  0.927697   1.0    0.0  0.972698
46     0  0.503882  0.496118       0  ...  0.927256   1.0    0.0  0.972197
47     0  0.504525  0.495475       0  ...  0.925259   1.0    0.0  0.970013
48     1  0.484947  0.515053       1  ...  0.889388   1.0    0.0  0.972073
49     0  0.509447  0.490553       0  ...  0.926154   1.0    0.0  0.970518

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-1862.5676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29399.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230727   155000    155959  1690444799  29431.2  29396.9 -0.001162
2023-07-27 16:00:02,292:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [27/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10688 

self.closeSec=1690445399, self.tradeDate='20230727', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29396.9', self.close='29387.9'
2023-07-27 16:10:01,154:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690445399, self.tradeDate='20230727', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29396.9', self.close='29387.9'
2023-07-27 16:10:01,163:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230727   152000    152959  1690442999  29420.4  29418.9 -0.000051
525  20230727   153000    153959  1690443599  29418.9    29439  0.000683
526  20230727   154000    154959  1690444199    29439  29431.1 -0.000268
527  20230727   155000    155959  1690444799  29431.2  29396.9 -0.001162
528  20230727   160000    160959  1690445399  29396.9  29387.9 -0.000306
2023-07-27 16:10:01,163:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10689 

self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29388', self.close='29396.6'
127.0.0.1 - - [27/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-27 16:20:05,435:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29388', self.close='29396.6'
2023-07-27 16:20:05,705:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230727   153000    153959  1690443599  29418.9    29439  0.000683
526  20230727   154000    154959  1690444199    29439  29431.1 -0.000268
527  20230727   155000    155959  1690444799  29431.2  29396.9 -0.001162
528  20230727   160000    160959  1690445399  29396.9  29387.9 -0.000306
529  20230727   161000    161959  1690445999    29388  29396.6  0.000296
2023-07-27 16:20:05,705:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230727   155000    155959  1690444799  29431.2  29396.9
2023-07-27 16:00:02,315:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10691 

self.closeSec=1690445399, self.tradeDate='20230727', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29396.9', self.close='29387.9'
127.0.0.1 - - [27/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-27 16:10:01,166:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690445399, self.tradeDate='20230727', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29396.9', self.close='29387.9'
2023-07-27 16:10:01,173:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230727   152000    152959  1690442999  29420.4  29418.9
17517  20230727   153000    153959  1690443599  29418.9    29439
17518  20230727   154000    154959  1690444199    29439  29431.1
17519  20230727   155000    155959  1690444799  29431.2  29396.9
17520  20230727   160000    160959  1690445399  29396.9  29387.9
2023-07-27 16:10:01,173:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10692 

self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29388', self.close='29396.6'
127.0.0.1 - - [27/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-27 16:20:06,358:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29388', self.close='29396.6'
2023-07-27 16:20:06,450:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230727   153000    153959  1690443599  29418.9    29439
17518  20230727   154000    154959  1690444199    29439  29431.1
17519  20230727   155000    155959  1690444799  29431.2  29396.9
17520  20230727   160000    160959  1690445399  29396.9  29387.9
17521  20230727   161000    161959  1690445999    29388  29396.6
2023-07-27 16:20:06,451:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230727   155000    155959  1690444799  29431.2  29396.9
2023-07-27 16:00:02,312:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10691 

self.closeSec=1690445399, self.tradeDate='20230727', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29396.9', self.close='29387.9'
2023-07-27 16:10:01,158:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690445399, self.tradeDate='20230727', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29396.9', self.close='29387.9'
127.0.0.1 - - [27/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-27 16:10:01,169:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230727   152000    152959  1690442999  29420.4  29418.9
12189  20230727   153000    153959  1690443599  29418.9    29439
12190  20230727   154000    154959  1690444199    29439  29431.1
12191  20230727   155000    155959  1690444799  29431.2  29396.9
12192  20230727   160000    160959  1690445399  29396.9  29387.9
2023-07-27 16:10:01,170:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10692 

self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29388', self.close='29396.6'
127.0.0.1 - - [27/Jul/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-07-27 16:20:06,247:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29388', self.close='29396.6'
2023-07-27 16:20:06,374:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230727   153000    153959  1690443599  29418.9    29439
12190  20230727   154000    154959  1690444199    29439  29431.1
12191  20230727   155000    155959  1690444799  29431.2  29396.9
12192  20230727   160000    160959  1690445399  29396.9  29387.9
12193  20230727   161000    161959  1690445999    29388  29396.6
2023-07-27 16:20:06,375:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21376
self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29401.2, self.close=29396.6, self.high=29401.2, self.low=29391.0, self.vol=401.6, self.amt=11806008.4582 
127.0.0.1 - - [27/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-27 16:20:04,344:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230727   155500    155959  ...         0.0        0.0       0
5952  20230727   160000    160459  ...         0.0        0.0       0
5953  20230727   160500    160959  ...         0.0        0.0       0
5954  20230727   161000    161459  ...         0.0        0.0       0
5955  20230727   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 16:20:04,365:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690445999, self.tradeDate='20230727', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29401.2, self.close=29396.6, self.high=29401.2, self.low=29391.0, self.vol=401.6, self.amt=11806008.4582, ukdf['pct'].iloc[-1]=-0.000156 , ukdf['amount'].iloc[-1]=11806008.4582, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '94760.81375605546', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29395.38024706', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21377
self.closeSec=1690446299, self.tradeDate='20230727', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29396.5, self.close=29399.7, self.high=29399.8, self.low=29386.4, self.vol=328.072, self.amt=9643080.6078 
127.0.0.1 - - [27/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-27 16:25:00,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230727   160000    160459  ...         0.0        0.0       0
5953  20230727   160500    160959  ...         0.0        0.0       0
5954  20230727   161000    161459  ...         0.0        0.0       0
5955  20230727   161500    161959  ...         0.0        0.0       0
5956  20230727   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 16:25:00,789:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690446299, self.tradeDate='20230727', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29396.5, self.close=29399.7, self.high=29399.8, self.low=29386.4, self.vol=328.072, self.amt=9643080.6078, ukdf['pct'].iloc[-1]=0.000105 , ukdf['amount'].iloc[-1]=9643080.6078, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '94924.9678', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29399.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230727   040000    075959  1690415999  ...    721  0.621201  0.937997     1.0
722  20230727   080000    115959  1690430399  ...    722  0.616412  0.900702     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '14829.0805', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29388.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [27/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1594659.6936504, self.flagDict['side']='buy', self.tradeCount=13, self.count=445
self.closeSec=1690444799, self.tradeDate='20230727', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29388.1, self.close=29396.9, self.high=29485.9, self.low=29366.0, self.vol=27656.693, self.amt=814095436.9781 
2023-07-27 16:00:01,815:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690444799, self.tradeDate='20230727', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29388.1, self.close=29396.9, self.high=29485.9, self.low=29366.0, self.vol=27656.693, self.amt=814095436.9781 
2023-07-27 16:00:01,828:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230726   200000    235959  ...  42475.796  1.242892e+09  0.004914
720  20230727   000000    035959  ...  94415.230  2.768011e+09  0.002835
721  20230727   040000    075959  ...  90685.517  2.674287e+09 -0.001848
722  20230727   080000    115959  ...  22249.763  6.533111e+08  0.001776
723  20230727   120000    155959  ...  27656.693  8.140954e+08  0.000299

[5 rows x 11 columns]
2023-07-27 16:00:02,484:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230726   200000    235959  1690387199  ...    719  0.609597  0.931236     1.0
720  20230727   000000    035959  1690401599  ...    720  0.618229  0.945891     1.0
721  20230727   040000    075959  1690415999  ...    721  0.621201  0.937997     1.0
722  20230727   080000    115959  1690430399  ...    722  0.616412  0.900702     1.0
723  20230727   120000    155959  1690444799  ...    723  0.611399  0.866264     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '15369.41691446187', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29397.95637647', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


