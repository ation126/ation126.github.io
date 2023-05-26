# 20230526 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3520
self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26517.2, self.close=26496.9, self.high=26517.3, self.low=26493.3, self.vol=592.448, self.amt=15701014.6417 
127.0.0.1 - - [26/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-26 16:20:06,710:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230526   155500    155959  ...    0.048627   0.213263       0
5952  20230526   160000    160459  ...    0.048468   0.213086       0
5953  20230526   160500    160959  ...    0.048309   0.212908       0
5954  20230526   161000    161459  ...    0.048149   0.212728       0
5955  20230526   161500    161959  ...    0.047975   0.212511       0

[5 rows x 18 columns]
2023-05-26 16:20:06,721:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26517.2, self.close=26496.9, self.high=26517.3, self.low=26493.3, self.vol=592.448, self.amt=15701014.6417, ukdf['pct'].iloc[-1]=-0.000766 , ukdf['amount'].iloc[-1]=15701014.6417, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.047975330694222024, signal=0, value_std=0.2125113983238334 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5108.41175828214', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26498.07451111', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3521
self.closeSec=1685089499, self.tradeDate='20230526', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26497.0, self.close=26491.3, self.high=26504.9, self.low=26490.0, self.vol=411.619, self.amt=10906212.7212 
127.0.0.1 - - [26/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-26 16:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230526   160000    160459  ...    0.048468   0.213086       0
5953  20230526   160500    160959  ...    0.048309   0.212908       0
5954  20230526   161000    161459  ...    0.048149   0.212728       0
5955  20230526   161500    161959  ...    0.047975   0.212511       0
5956  20230526   162000    162459  ...    0.047801   0.212293       0

[5 rows x 18 columns]
2023-05-26 16:25:00,792:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685089499, self.tradeDate='20230526', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26497.0, self.close=26491.3, self.high=26504.9, self.low=26490.0, self.vol=411.619, self.amt=10906212.7212, ukdf['pct'].iloc[-1]=-0.000211 , ukdf['amount'].iloc[-1]=10906212.7212, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.04780111955269652, signal=0, value_std=0.21229347955998534 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5202.7536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26491.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26517.2, self.close=26496.9, self.high=26517.3, self.low=26493.3 
127.0.0.1 - - [26/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-26 16:20:04,309:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26517.2, self.close=26496.9, self.high=26517.3, self.low=26493.3   
2023-05-26 16:20:05,689:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230526   155500    155959  1685087999  ...  26488.7 -0.000932   1631    5
1632  20230526   160000    160459  1685088299  ...  26480.7 -0.000298   1632    0
1633  20230526   160500    160959  1685088599  ...  26480.0 -0.000098   1633    1
1634  20230526   161000    161459  1685088899  ...  26480.8  0.001375   1634    2
1635  20230526   161500    161959  1685089199  ...  26493.3 -0.000766   1635    3

[5 rows x 11 columns]
2023-05-26 16:20:05,698:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.3917817682069277, self.count=3523 

self.closeSec=1685089499, self.tradeDate='20230526', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26497.0, self.close=26491.3, self.high=26504.9, self.low=26490.0 
2023-05-26 16:25:00,721:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685089499, self.tradeDate='20230526', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26497.0, self.close=26491.3, self.high=26504.9, self.low=26490.0   
2023-05-26 16:25:00,809:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230526   160000    160459  1685088299  ...  26480.7 -0.000298   1632    0
1633  20230526   160500    160959  1685088599  ...  26480.0 -0.000098   1633    1
1634  20230526   161000    161459  1685088899  ...  26480.8  0.001375   1634    2
1635  20230526   161500    161959  1685089199  ...  26493.3 -0.000766   1635    3
1636  20230526   162000    162459  1685089499  ...  26490.0 -0.000211   1636    4

[5 rows x 11 columns]
2023-05-26 16:25:00,809:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-26 16:00:33,761:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230526    132959  26420.1  ...  45.833333  0.472398  0.392073
5787  20230526    135959  26366.1  ...  45.833333  0.465773  0.407077
5788  20230526    142959  26340.0  ...  46.250000  0.478414  0.415099
5789  20230526    145959  26384.2  ...  46.666667  0.489540  0.417186
5790  20230526    152959  26424.0  ...  47.083333  0.491620  0.418119

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-05-26 16:00:33,937:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.486425  0.513575       0  ...  0.913391  -1.0    0.0  0.983283
538     1  0.487318  0.512682       1  ...  0.911859  -1.0    0.0  0.984933
539     1  0.499504  0.500496       1  ...  0.910480  -1.0    0.0  0.986423
540     0  0.502501  0.497499       1  ...  0.910221  -1.0    0.0  0.986703
541     1  0.495096  0.504904       1  ...  0.908165  -1.0    0.0  0.988932

[5 rows x 10 columns]
2023-05-26 16:00:33,973:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486471  0.513529       0  ...  0.913391  -1.0    0.0  0.979612
46     1  0.487527  0.512473       1  ...  0.911859  -1.0    0.0  0.981559
47     1  0.499455  0.500545       1  ...  0.910480  -1.0    0.0  0.982239
48     0  0.502722  0.497278       1  ...  0.910221  -1.0    0.0  0.986876
49     1  0.495096  0.504904       1  ...  0.908165  -1.0    0.0  0.988932

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.287', 'enterprice': '26103', 'countrevence': '0', 'unrealprofit': '-10713.48864143428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26495.62244444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230526   155000    155959  1685087999  26458.1  26491.3  0.001259
2023-05-26 16:00:02,425:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1760 

self.closeSec=1685088599, self.tradeDate='20230526', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26491.2', self.close='26480.8'
2023-05-26 16:10:01,156:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685088599, self.tradeDate='20230526', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26491.2', self.close='26480.8'
2023-05-26 16:10:01,202:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230526   152000    152959  1685086199  26458.9  26431.6 -0.001028
525  20230526   153000    153959  1685086799  26431.6  26445.8  0.000537
526  20230526   154000    154959  1685087399  26445.8    26458  0.000461
527  20230526   155000    155959  1685087999  26458.1  26491.3  0.001259
528  20230526   160000    160959  1685088599  26491.2  26480.8 -0.000396
2023-05-26 16:10:01,202:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1761 

self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26480.9', self.close='26496.9'
127.0.0.1 - - [26/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-26 16:20:06,959:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26480.9', self.close='26496.9'
2023-05-26 16:20:07,659:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230526   153000    153959  1685086799  26431.6  26445.8  0.000537
526  20230526   154000    154959  1685087399  26445.8    26458  0.000461
527  20230526   155000    155959  1685087999  26458.1  26491.3  0.001259
528  20230526   160000    160959  1685088599  26491.2  26480.8 -0.000396
529  20230526   161000    161959  1685089199  26480.9  26496.9  0.000608
2023-05-26 16:20:07,659:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230526   155000    155959  1685087999  26458.1  26491.3
2023-05-26 16:00:02,346:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1763 

self.closeSec=1685088599, self.tradeDate='20230526', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26491.2', self.close='26480.8'
2023-05-26 16:10:01,131:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685088599, self.tradeDate='20230526', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26491.2', self.close='26480.8'
2023-05-26 16:10:01,160:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230526   152000    152959  1685086199  26458.9  26431.6
17517  20230526   153000    153959  1685086799  26431.6  26445.8
17518  20230526   154000    154959  1685087399  26445.8    26458
17519  20230526   155000    155959  1685087999  26458.1  26491.3
17520  20230526   160000    160959  1685088599  26491.2  26480.8
2023-05-26 16:10:01,160:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1764 

self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26480.9', self.close='26496.9'
127.0.0.1 - - [26/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-26 16:20:08,480:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26480.9', self.close='26496.9'
2023-05-26 16:20:08,606:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230526   153000    153959  1685086799  26431.6  26445.8
17518  20230526   154000    154959  1685087399  26445.8    26458
17519  20230526   155000    155959  1685087999  26458.1  26491.3
17520  20230526   160000    160959  1685088599  26491.2  26480.8
17521  20230526   161000    161959  1685089199  26480.9  26496.9
2023-05-26 16:20:08,607:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230526   155000    155959  1685087999  26458.1  26491.3
2023-05-26 16:00:02,357:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1763 

self.closeSec=1685088599, self.tradeDate='20230526', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26491.2', self.close='26480.8'
2023-05-26 16:10:01,127:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685088599, self.tradeDate='20230526', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26491.2', self.close='26480.8'
2023-05-26 16:10:01,148:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230526   152000    152959  1685086199  26458.9  26431.6
12189  20230526   153000    153959  1685086799  26431.6  26445.8
12190  20230526   154000    154959  1685087399  26445.8    26458
12191  20230526   155000    155959  1685087999  26458.1  26491.3
12192  20230526   160000    160959  1685088599  26491.2  26480.8
2023-05-26 16:10:01,148:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1764 

self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26480.9', self.close='26496.9'
127.0.0.1 - - [26/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-26 16:20:08,202:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26480.9', self.close='26496.9'
2023-05-26 16:20:08,448:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230526   153000    153959  1685086799  26431.6  26445.8
12190  20230526   154000    154959  1685087399  26445.8    26458
12191  20230526   155000    155959  1685087999  26458.1  26491.3
12192  20230526   160000    160959  1685088599  26491.2  26480.8
12193  20230526   161000    161959  1685089199  26480.9  26496.9
2023-05-26 16:20:08,449:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3520
self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26517.2, self.close=26496.9, self.high=26517.3, self.low=26493.3, self.vol=592.448, self.amt=15701014.6417 
127.0.0.1 - - [26/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-26 16:20:06,630:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230526   155500    155959  ...         0.0        0.0       0
5952  20230526   160000    160459  ...         0.0        0.0       0
5953  20230526   160500    160959  ...         0.0        0.0       0
5954  20230526   161000    161459  ...         0.0        0.0       0
5955  20230526   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-26 16:20:06,650:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685089199, self.tradeDate='20230526', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26517.2, self.close=26496.9, self.high=26517.3, self.low=26493.3, self.vol=592.448, self.amt=15701014.6417, ukdf['pct'].iloc[-1]=-0.000766 , ukdf['amount'].iloc[-1]=15701014.6417, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12848.01858286349', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26498.07451111', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3521
self.closeSec=1685089499, self.tradeDate='20230526', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26497.0, self.close=26491.3, self.high=26504.9, self.low=26490.0, self.vol=411.619, self.amt=10906212.7212 
2023-05-26 16:25:00,831:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230526   160000    160459  ...         0.0        0.0       0
5953  20230526   160500    160959  ...         0.0        0.0       0
5954  20230526   161000    161459  ...         0.0        0.0       0
5955  20230526   161500    161959  ...         0.0        0.0       0
5956  20230526   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-26 16:25:00,831:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685089499, self.tradeDate='20230526', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26497.0, self.close=26491.3, self.high=26504.9, self.low=26490.0, self.vol=411.619, self.amt=10906212.7212, ukdf['pct'].iloc[-1]=-0.000211 , ukdf['amount'].iloc[-1]=10906212.7212, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-13099.6307', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26491.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230526   040000    075959  1685059199  ...    721  0.598183  1.345687     1.0
722  20230526   080000    115959  1685073599  ...    722  0.610372  1.394063     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '16436.5775', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26425.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [26/May/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=73
self.closeSec=1685087999, self.tradeDate='20230526', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26425.7, self.close=26491.3, self.high=26527.8, self.low=26313.9, self.vol=34980.918, self.amt=923892188.5779 
2023-05-26 16:00:01,907:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685087999, self.tradeDate='20230526', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26425.7, self.close=26491.3, self.high=26527.8, self.low=26313.9, self.vol=34980.918, self.amt=923892188.5779 
2023-05-26 16:00:01,968:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230525   200000    235959  ...  110196.106  2.902615e+09 -0.002496
720  20230526   000000    035959  ...   80074.610  2.114028e+09  0.009193
721  20230526   040000    075959  ...   28461.259  7.533183e+08  0.000147
722  20230526   080000    115959  ...   38579.969  1.019498e+09 -0.001364
723  20230526   120000    155959  ...   34980.918  9.238922e+08  0.002482

[5 rows x 11 columns]
2023-05-26 16:00:03,879:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230525   200000    235959  1685030399  ...    719  0.581766  1.282105     1.0
720  20230526   000000    035959  1685044799  ...    720  0.573831  1.220977     1.0
721  20230526   040000    075959  1685059199  ...    721  0.598183  1.345687     1.0
722  20230526   080000    115959  1685073599  ...    722  0.610372  1.394063     1.0
723  20230526   120000    155959  1685087999  ...    723  0.620975  1.427004     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '20287.4328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26495.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


