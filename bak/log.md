# 20230518 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1216
self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27336.1, self.close=27340.9, self.high=27389.3, self.low=27336.0, self.vol=1368.478, self.amt=37443840.1815 
2023-05-18 16:20:00,544:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230518   155500    155959  ...    0.402153   0.303184       0
5952  20230518   160000    160459  ...    0.402049   0.303257       0
5953  20230518   160500    160959  ...    0.401945   0.303331       0
5954  20230518   161000    161459  ...    0.401844   0.303404       0
5955  20230518   161500    161959  ...    0.401745   0.303477       0

[5 rows x 18 columns]
2023-05-18 16:20:00,547:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27336.1, self.close=27340.9, self.high=27389.3, self.low=27336.0, self.vol=1368.478, self.amt=37443840.1815, ukdf['pct'].iloc[-1]=0.000179 , ukdf['amount'].iloc[-1]=37443840.1815, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.40174479625008697, signal=0, value_std=0.3034772569058474 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-6656.77218256248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27342.91035348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1217
self.closeSec=1684398299, self.tradeDate='20230518', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27340.9, self.close=27365.8, self.high=27373.0, self.low=27340.8, self.vol=697.159, self.amt=19071763.7782 
2023-05-18 16:25:00,446:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230518   160000    160459  ...    0.402049   0.303257       0
5953  20230518   160500    160959  ...    0.401945   0.303331       0
5954  20230518   161000    161459  ...    0.401844   0.303404       0
5955  20230518   161500    161959  ...    0.401745   0.303477       0
5956  20230518   162000    162459  ...    0.401646   0.303550       0

[5 rows x 18 columns]
2023-05-18 16:25:00,446:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684398299, self.tradeDate='20230518', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27340.9, self.close=27365.8, self.high=27373.0, self.low=27340.8, self.vol=697.159, self.amt=19071763.7782, ukdf['pct'].iloc[-1]=0.000911 , ukdf['amount'].iloc[-1]=19071763.7782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.4016457735860937, signal=0, value_std=0.30355015990245565 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-6975.5334', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27365.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27336.1, self.close=27340.9, self.high=27389.3, self.low=27336.0 
127.0.0.1 - - [18/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 16:20:00,449:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27336.1, self.close=27340.9, self.high=27389.3, self.low=27336.0   
2023-05-18 16:20:00,513:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230518   155500    155959  1684396799  ...  27375.1 -0.001860   1631    5
1632  20230518   160000    160459  1684397099  ...  27343.6 -0.000921   1632    0
1633  20230518   160500    160959  1684397399  ...  27342.0  0.000790   1633    1
1634  20230518   161000    161459  1684397699  ...  27336.0 -0.001297   1634    2
1635  20230518   161500    161959  1684397999  ...  27336.0  0.000179   1635    3

[5 rows x 11 columns]
2023-05-18 16:20:00,513:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=25, self.factor=0.3898850175996995, self.count=1219 

self.closeSec=1684398299, self.tradeDate='20230518', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27340.9, self.close=27365.8, self.high=27373.0, self.low=27340.8 
2023-05-18 16:25:00,393:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684398299, self.tradeDate='20230518', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27340.9, self.close=27365.8, self.high=27373.0, self.low=27340.8   
127.0.0.1 - - [18/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-18 16:25:00,435:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230518   160000    160459  1684397099  ...  27343.6 -0.000921   1632    0
1633  20230518   160500    160959  1684397399  ...  27342.0  0.000790   1633    1
1634  20230518   161000    161459  1684397699  ...  27336.0 -0.001297   1634    2
1635  20230518   161500    161959  1684397999  ...  27336.0  0.000179   1635    3
1636  20230518   162000    162459  1684398299  ...  27340.8  0.000911   1636    4

[5 rows x 11 columns]
2023-05-18 16:25:00,435:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-18 16:00:19,342:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230518    132959  27292.3  ...  49.583333  0.534723  0.265268
5787  20230518    135959  27257.3  ...  49.583333  0.523831  0.267374
5788  20230518    142959  27211.2  ...  49.166667  0.512348  0.272740
5789  20230518    145959  27161.7  ...  49.583333  0.519883  0.275363
5790  20230518    152959  27196.5  ...  50.000000  0.524515  0.276337

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-05-18 16:00:19,453:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.475274  0.524726       0  ...  0.976629   1.0    0.0  0.940607
538     1  0.469084  0.530916       0  ...  0.974849   1.0    0.0  0.938893
539     1  0.463763  0.536237       1  ...  0.976098   1.0    0.0  0.940096
540     1  0.486539  0.513461       1  ...  0.976870   1.0    0.0  0.940839
541     1  0.486783  0.513217       1  ...  0.982508   1.0    0.0  0.946269

[5 rows x 10 columns]
2023-05-18 16:00:19,469:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.475487  0.524513       0  ...  0.976629   1.0    0.0  0.944286
46     1  0.469189  0.530811       0  ...  0.974849   1.0    0.0  0.942270
47     1  0.463936  0.536064       1  ...  0.976098   1.0    0.0  0.943085
48     1  0.487111  0.512889       1  ...  0.976870   1.0    0.0  0.945069
49     1  0.486783  0.513217       1  ...  0.982508   1.0    0.0  0.946269

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.819', 'enterprice': '27153.5', 'countrevence': '0', 'unrealprofit': '6517.9917', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27387.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230518   155000    155959  1684396799  27410.2  27375.1 -0.001281
2023-05-18 16:00:00,406:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=608 

self.closeSec=1684397399, self.tradeDate='20230518', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27375.1', self.close='27371.5'
2023-05-18 16:10:00,364:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684397399, self.tradeDate='20230518', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27375.1', self.close='27371.5'
2023-05-18 16:10:00,416:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230518   152000    152959  1684394999  27225.4    27218 -0.000275
525  20230518   153000    153959  1684395599  27217.9  27279.4  0.002256
526  20230518   154000    154959  1684396199  27279.4  27410.2  0.004795
527  20230518   155000    155959  1684396799  27410.2  27375.1 -0.001281
528  20230518   160000    160959  1684397399  27375.1  27371.5 -0.000132
2023-05-18 16:10:00,417:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=609 

self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27371.4', self.close='27340.9'
127.0.0.1 - - [18/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 16:20:00,629:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27371.4', self.close='27340.9'
2023-05-18 16:20:00,704:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230518   153000    153959  1684395599  27217.9  27279.4  0.002256
526  20230518   154000    154959  1684396199  27279.4  27410.2  0.004795
527  20230518   155000    155959  1684396799  27410.2  27375.1 -0.001281
528  20230518   160000    160959  1684397399  27375.1  27371.5 -0.000132
529  20230518   161000    161959  1684397999  27371.4  27340.9 -0.001118
2023-05-18 16:20:00,704:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230518   155000    155959  1684396799  27410.2  27375.1
2023-05-18 16:00:00,433:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=611 

self.closeSec=1684397399, self.tradeDate='20230518', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27375.1', self.close='27371.5'
2023-05-18 16:10:00,388:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684397399, self.tradeDate='20230518', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27375.1', self.close='27371.5'
2023-05-18 16:10:00,439:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230518   152000    152959  1684394999  27225.4    27218
17517  20230518   153000    153959  1684395599  27217.9  27279.4
17518  20230518   154000    154959  1684396199  27279.4  27410.2
17519  20230518   155000    155959  1684396799  27410.2  27375.1
17520  20230518   160000    160959  1684397399  27375.1  27371.5
2023-05-18 16:10:00,439:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [18/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=612 

self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27371.4', self.close='27340.9'
2023-05-18 16:20:00,809:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27371.4', self.close='27340.9'
2023-05-18 16:20:00,848:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230518   153000    153959  1684395599  27217.9  27279.4
17518  20230518   154000    154959  1684396199  27279.4  27410.2
17519  20230518   155000    155959  1684396799  27410.2  27375.1
17520  20230518   160000    160959  1684397399  27375.1  27371.5
17521  20230518   161000    161959  1684397999  27371.4  27340.9
2023-05-18 16:20:00,848:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230518   155000    155959  1684396799  27410.2  27375.1
2023-05-18 16:00:00,424:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=611 

self.closeSec=1684397399, self.tradeDate='20230518', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27375.1', self.close='27371.5'
2023-05-18 16:10:00,401:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684397399, self.tradeDate='20230518', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27375.1', self.close='27371.5'
2023-05-18 16:10:00,438:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230518   152000    152959  1684394999  27225.4    27218
12189  20230518   153000    153959  1684395599  27217.9  27279.4
12190  20230518   154000    154959  1684396199  27279.4  27410.2
12191  20230518   155000    155959  1684396799  27410.2  27375.1
12192  20230518   160000    160959  1684397399  27375.1  27371.5
2023-05-18 16:10:00,438:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--: 127.0.0.1 - - [18/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=612 

self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27371.4', self.close='27340.9'
2023-05-18 16:20:00,729:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27371.4', self.close='27340.9'
2023-05-18 16:20:00,782:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230518   153000    153959  1684395599  27217.9  27279.4
12190  20230518   154000    154959  1684396199  27279.4  27410.2
12191  20230518   155000    155959  1684396799  27410.2  27375.1
12192  20230518   160000    160959  1684397399  27375.1  27371.5
12193  20230518   161000    161959  1684397999  27371.4  27340.9
2023-05-18 16:20:00,782:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1216
self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27336.1, self.close=27340.9, self.high=27389.3, self.low=27336.0, self.vol=1368.478, self.amt=37443840.1815 
2023-05-18 16:20:00,599:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230518   155500    155959  ...    0.261482   0.299119       0
5952  20230518   160000    160459  ...    0.261247   0.299147       0
5953  20230518   160500    160959  ...    0.261002   0.299168       0
5954  20230518   161000    161459  ...    0.260757   0.299189       0
5955  20230518   161500    161959  ...    0.260513   0.299211       0

[5 rows x 18 columns]
2023-05-18 16:20:00,600:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684397999, self.tradeDate='20230518', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27336.1, self.close=27340.9, self.high=27389.3, self.low=27336.0, self.vol=1368.478, self.amt=37443840.1815, ukdf['pct'].iloc[-1]=0.000179 , ukdf['amount'].iloc[-1]=37443840.1815, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.2605132724003559, signal=0, value_std=0.2992106672234908 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '18530.02943860068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27342.91035348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1217
self.closeSec=1684398299, self.tradeDate='20230518', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27340.9, self.close=27365.8, self.high=27373.0, self.low=27340.8, self.vol=697.159, self.amt=19071763.7782 
2023-05-18 16:25:00,444:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230518   160000    160459  ...    0.261247   0.299147       0
5953  20230518   160500    160959  ...    0.261002   0.299168       0
5954  20230518   161000    161459  ...    0.260757   0.299189       0
5955  20230518   161500    161959  ...    0.260513   0.299211       0
5956  20230518   162000    162459  ...    0.260269   0.299232       0

[5 rows x 18 columns]
2023-05-18 16:25:00,445:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684398299, self.tradeDate='20230518', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27340.9, self.close=27365.8, self.high=27373.0, self.low=27340.8, self.vol=697.159, self.amt=19071763.7782, ukdf['pct'].iloc[-1]=0.000911 , ukdf['amount'].iloc[-1]=19071763.7782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.260268748713498, signal=0, value_std=0.2992316270048743 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '19380.1738', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27365.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230518   040000    075959  1684367999  ...    721  0.532623  0.155524     NaN
722  20230518   080000    115959  1684382399  ...    722  0.500527 -0.024523     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '17165.486', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27357.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [18/May/2023 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1393350.022233, self.flagDict['side']='buy', self.tradeCount=1, self.count=25
self.closeSec=1684396799, self.tradeDate='20230518', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27357.2, self.close=27375.1, self.high=27445.9, self.low=27139.0, self.vol=61937.26, self.amt=1689376871.93044 
2023-05-18 16:00:00,376:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684396799, self.tradeDate='20230518', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27357.2, self.close=27375.1, self.high=27445.9, self.low=27139.0, self.vol=61937.26, self.amt=1689376871.93044 
2023-05-18 16:00:00,471:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230517   200000    235959  ...  106131.008  2.833126e+09  0.006065
720  20230518   000000    035959  ...  129947.055  3.521987e+09  0.021991
721  20230518   040000    075959  ...   67419.315  1.844731e+09  0.000683
722  20230518   080000    115959  ...   35846.271  9.806639e+08 -0.001405
723  20230518   120000    155959  ...   61937.260  1.689377e+09  0.000651

[5 rows x 11 columns]
2023-05-18 16:00:01,864:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230517   200000    235959  1684339199  ...    719  0.709365  1.165997     1.0
720  20230518   000000    035959  1684353599  ...    720  0.531636  0.148478     NaN
721  20230518   040000    075959  1684367999  ...    721  0.532623  0.155524     NaN
722  20230518   080000    115959  1684382399  ...    722  0.500527 -0.024523     NaN
723  20230518   120000    155959  1684396799  ...    723  0.476310 -0.157409     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '18103.3942704017', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27375.47299497', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


