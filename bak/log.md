# 20230616 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9568
self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25572.0, self.close=25588.8, self.high=25599.8, self.low=25560.0, self.vol=1190.351, self.amt=30455527.2756 
127.0.0.1 - - [16/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-16 16:20:07,565:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230616   155500    155959  ...         0.0        0.0       0
5952  20230616   160000    160459  ...         0.0        0.0       0
5953  20230616   160500    160959  ...         0.0        0.0       0
5954  20230616   161000    161459  ...         0.0        0.0       0
5955  20230616   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 16:20:07,597:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25572.0, self.close=25588.8, self.high=25599.8, self.low=25560.0, self.vol=1190.351, self.amt=30455527.2756, ukdf['pct'].iloc[-1]=0.000657 , ukdf['amount'].iloc[-1]=30455527.2756, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '17725.1685365469', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25592.08881685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9569
self.closeSec=1686903899, self.tradeDate='20230616', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25588.9, self.close=25600.7, self.high=25609.1, self.low=25587.4, self.vol=1043.177, self.amt=26704339.5394 
127.0.0.1 - - [16/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-16 16:25:00,804:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230616   160000    160459  ...         0.0        0.0       0
5953  20230616   160500    160959  ...         0.0        0.0       0
5954  20230616   161000    161459  ...         0.0        0.0       0
5955  20230616   161500    161959  ...         0.0        0.0       0
5956  20230616   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 16:25:00,804:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686903899, self.tradeDate='20230616', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25588.9, self.close=25600.7, self.high=25609.1, self.low=25587.4, self.vol=1043.177, self.amt=26704339.5394, ukdf['pct'].iloc[-1]=0.000465 , ukdf['amount'].iloc[-1]=26704339.5394, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '17603.8566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25600.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25572.0, self.close=25588.8, self.high=25599.8, self.low=25560.0 
127.0.0.1 - - [16/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-16 16:20:04,877:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25572.0, self.close=25588.8, self.high=25599.8, self.low=25560.0   
2023-06-16 16:20:06,486:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230616   155500    155959  1686902399  ...  25525.0 -0.000024   1631    5
1632  20230616   160000    160459  1686902699  ...  25526.0  0.000447   1632    0
1633  20230616   160500    160959  1686902999  ...  25537.4  0.000489   1633    1
1634  20230616   161000    161459  1686903299  ...  25549.9  0.000861   1634    2
1635  20230616   161500    161959  1686903599  ...  25560.0  0.000657   1635    3

[5 rows x 11 columns]
2023-06-16 16:20:06,506:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.41814220105510974, self.count=9571 

self.closeSec=1686903899, self.tradeDate='20230616', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25588.9, self.close=25600.7, self.high=25609.1, self.low=25587.4 
127.0.0.1 - - [16/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-16 16:25:00,760:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686903899, self.tradeDate='20230616', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25588.9, self.close=25600.7, self.high=25609.1, self.low=25587.4   
2023-06-16 16:25:00,775:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230616   160000    160459  1686902699  ...  25526.0  0.000447   1632    0
1633  20230616   160500    160959  1686902999  ...  25537.4  0.000489   1633    1
1634  20230616   161000    161459  1686903299  ...  25549.9  0.000861   1634    2
1635  20230616   161500    161959  1686903599  ...  25560.0  0.000657   1635    3
1636  20230616   162000    162459  1686903899  ...  25587.4  0.000465   1636    4

[5 rows x 11 columns]
2023-06-16 16:25:00,775:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-16 16:00:18,857:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230616    132959  25515.0  ...  50.000000  0.508931  0.317175
5787  20230616    135959  25479.9  ...  50.000000  0.520747  0.310329
5788  20230616    142959  25541.2  ...  50.416667  0.526045  0.302022
5789  20230616    145959  25569.3  ...  50.416667  0.525009  0.294603
5790  20230616    152959  25564.4  ...  50.833333  0.525904  0.289210

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-06-16 16:00:18,966:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.488327  0.511673       1  ...  1.030014   1.0    0.0  0.945319
538     0  0.511447  0.488553       1  ...  1.031143   1.0    0.0  0.946356
539     0  0.505607  0.494393       0  ...  1.030946   1.0    0.0  0.946174
540     1  0.497990  0.502010       1  ...  1.031131   1.0    0.0  0.946345
541     0  0.503997  0.496003       0  ...  1.029401   1.0    0.0  0.944757

[5 rows x 10 columns]
2023-06-16 16:00:18,991:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488456  0.511544       1  ...  1.030014   1.0    0.0  0.938291
46     0  0.511687  0.488313       1  ...  1.031143   1.0    0.0  0.942386
47     0  0.505636  0.494364       0  ...  1.030946   1.0    0.0  0.943249
48     1  0.497911  0.502089       1  ...  1.031131   1.0    0.0  0.942775
49     0  0.503997  0.496003       0  ...  1.029401   1.0    0.0  0.944757

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '3054.5922', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25532.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230616   155000    155959  1686902399  25535.8  25526.1 -0.000384
2023-06-16 16:00:02,404:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4784 

self.closeSec=1686902999, self.tradeDate='20230616', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25526.1', self.close='25550'
2023-06-16 16:10:01,087:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686902999, self.tradeDate='20230616', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25526.1', self.close='25550'
2023-06-16 16:10:01,102:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230616   152000    152959  1686900599  25561.3    25569  0.000305
525  20230616   153000    153959  1686901199  25569.1  25546.7 -0.000872
526  20230616   154000    154959  1686901799  25546.7  25535.9 -0.000423
527  20230616   155000    155959  1686902399  25535.8  25526.1 -0.000384
528  20230616   160000    160959  1686902999  25526.1    25550  0.000936
2023-06-16 16:10:01,102:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4785 

self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25549.9', self.close='25588.8'
127.0.0.1 - - [16/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-16 16:20:07,436:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25549.9', self.close='25588.8'
2023-06-16 16:20:08,267:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230616   153000    153959  1686901199  25569.1  25546.7 -0.000872
526  20230616   154000    154959  1686901799  25546.7  25535.9 -0.000423
527  20230616   155000    155959  1686902399  25535.8  25526.1 -0.000384
528  20230616   160000    160959  1686902999  25526.1    25550  0.000936
529  20230616   161000    161959  1686903599  25549.9  25588.8  0.001519
2023-06-16 16:20:08,276:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230616   155000    155959  1686902399  25535.8  25526.1
2023-06-16 16:00:02,411:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4787 

self.closeSec=1686902999, self.tradeDate='20230616', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25526.1', self.close='25550'
2023-06-16 16:10:01,115:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686902999, self.tradeDate='20230616', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25526.1', self.close='25550'
127.0.0.1 - - [16/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-16 16:10:01,121:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230616   152000    152959  1686900599  25561.3    25569
17517  20230616   153000    153959  1686901199  25569.1  25546.7
17518  20230616   154000    154959  1686901799  25546.7  25535.9
17519  20230616   155000    155959  1686902399  25535.8  25526.1
17520  20230616   160000    160959  1686902999  25526.1    25550
2023-06-16 16:10:01,122:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4788 

self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25549.9', self.close='25588.8'
127.0.0.1 - - [16/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-16 16:20:09,490:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25549.9', self.close='25588.8'
2023-06-16 16:20:09,629:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230616   153000    153959  1686901199  25569.1  25546.7
17518  20230616   154000    154959  1686901799  25546.7  25535.9
17519  20230616   155000    155959  1686902399  25535.8  25526.1
17520  20230616   160000    160959  1686902999  25526.1    25550
17521  20230616   161000    161959  1686903599  25549.9  25588.8
2023-06-16 16:20:09,631:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230616   155000    155959  1686902399  25535.8  25526.1
2023-06-16 16:00:02,407:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4787 

self.closeSec=1686902999, self.tradeDate='20230616', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25526.1', self.close='25550'
2023-06-16 16:10:01,096:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686902999, self.tradeDate='20230616', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25526.1', self.close='25550'
2023-06-16 16:10:01,103:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230616   152000    152959  1686900599  25561.3    25569
12189  20230616   153000    153959  1686901199  25569.1  25546.7
12190  20230616   154000    154959  1686901799  25546.7  25535.9
12191  20230616   155000    155959  1686902399  25535.8  25526.1
12192  20230616   160000    160959  1686902999  25526.1    25550
2023-06-16 16:10:01,103:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4788 

self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25549.9', self.close='25588.8'
127.0.0.1 - - [16/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-16 16:20:09,037:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25549.9', self.close='25588.8'
2023-06-16 16:20:09,338:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230616   153000    153959  1686901199  25569.1  25546.7
12190  20230616   154000    154959  1686901799  25546.7  25535.9
12191  20230616   155000    155959  1686902399  25535.8  25526.1
12192  20230616   160000    160959  1686902999  25526.1    25550
12193  20230616   161000    161959  1686903599  25549.9  25588.8
2023-06-16 16:20:09,346:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9568
self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25572.0, self.close=25588.8, self.high=25599.8, self.low=25560.0, self.vol=1190.351, self.amt=30455527.2756 
127.0.0.1 - - [16/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-16 16:20:07,566:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230616   155500    155959  ...         0.0        0.0       0
5952  20230616   160000    160459  ...         0.0        0.0       0
5953  20230616   160500    160959  ...         0.0        0.0       0
5954  20230616   161000    161459  ...         0.0        0.0       0
5955  20230616   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 16:20:07,606:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686903599, self.tradeDate='20230616', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25572.0, self.close=25588.8, self.high=25599.8, self.low=25560.0, self.vol=1190.351, self.amt=30455527.2756, ukdf['pct'].iloc[-1]=0.000657 , ukdf['amount'].iloc[-1]=30455527.2756, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-46497.23325337415', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25592.08881685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9569
self.closeSec=1686903899, self.tradeDate='20230616', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25588.9, self.close=25600.7, self.high=25609.1, self.low=25587.4, self.vol=1043.177, self.amt=26704339.5394 
127.0.0.1 - - [16/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-16 16:25:00,817:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230616   160000    160459  ...         0.0        0.0       0
5953  20230616   160500    160959  ...         0.0        0.0       0
5954  20230616   161000    161459  ...         0.0        0.0       0
5955  20230616   161500    161959  ...         0.0        0.0       0
5956  20230616   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-16 16:25:00,817:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686903899, self.tradeDate='20230616', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25588.9, self.close=25600.7, self.high=25609.1, self.low=25587.4, self.vol=1043.177, self.amt=26704339.5394, ukdf['pct'].iloc[-1]=0.000465 , ukdf['amount'].iloc[-1]=26704339.5394, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-46173.6912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25600.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230616   040000    075959  1686873599  ...    721  0.448839  0.146325     NaN
722  20230616   080000    115959  1686887999  ...    722  0.444398  0.133506     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '84122.385153', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25553.7045', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=199
self.closeSec=1686902399, self.tradeDate='20230616', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25545.7, self.close=25526.1, self.high=25620.0, self.low=25461.0, self.vol=40458.494, self.amt=1033505762.1295 
127.0.0.1 - - [16/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-16 16:00:01,933:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686902399, self.tradeDate='20230616', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25545.7, self.close=25526.1, self.high=25620.0, self.low=25461.0, self.vol=40458.494, self.amt=1033505762.1295 
2023-06-16 16:00:01,957:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230615   200000    235959  ...   70290.723  1.757902e+09 -0.002343
720  20230616   000000    035959  ...  112855.178  2.849100e+09  0.019829
721  20230616   040000    075959  ...  113154.066  2.888633e+09  0.005620
722  20230616   080000    115959  ...   43049.905  1.098014e+09 -0.001579
723  20230616   120000    155959  ...   40458.494  1.033506e+09 -0.000767

[5 rows x 11 columns]
2023-06-16 16:00:03,276:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230615   200000    235959  1686844799  ...    719  0.498045  0.326385     NaN
720  20230616   000000    035959  1686859199  ...    720  0.472700  0.235766     NaN
721  20230616   040000    075959  1686873599  ...    721  0.448839  0.146325     NaN
722  20230616   080000    115959  1686887999  ...    722  0.444398  0.133506     NaN
723  20230616   120000    155959  1686902399  ...    723  0.444552  0.148233     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '85645.215', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25526.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


