# 20230625 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12160
self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30736.3, self.close=30721.0, self.high=30736.4, self.low=30692.1, self.vol=811.593, self.amt=24924163.5159 
127.0.0.1 - - [25/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-25 16:20:07,421:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230625   155500    155959  ...         0.0        0.0       0
5952  20230625   160000    160459  ...         0.0        0.0       0
5953  20230625   160500    160959  ...         0.0        0.0       0
5954  20230625   161000    161459  ...         0.0        0.0       0
5955  20230625   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 16:20:07,452:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30736.3, self.close=30721.0, self.high=30736.4, self.low=30692.1, self.vol=811.593, self.amt=24924163.5159, ukdf['pct'].iloc[-1]=-0.000498 , ukdf['amount'].iloc[-1]=24924163.5159, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-53667.1132019682', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30718.6349707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12161
self.closeSec=1687681499, self.tradeDate='20230625', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30720.9, self.close=30736.8, self.high=30749.7, self.low=30713.0, self.vol=454.642, self.amt=13971200.5978 
127.0.0.1 - - [25/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-25 16:25:00,767:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230625   160000    160459  ...         0.0        0.0       0
5953  20230625   160500    160959  ...         0.0        0.0       0
5954  20230625   161000    161459  ...         0.0        0.0       0
5955  20230625   161500    161959  ...         0.0        0.0       0
5956  20230625   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 16:25:00,767:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687681499, self.tradeDate='20230625', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30720.9, self.close=30736.8, self.high=30749.7, self.low=30713.0, self.vol=454.642, self.amt=13971200.5978, ukdf['pct'].iloc[-1]=0.000514 , ukdf['amount'].iloc[-1]=13971200.5978, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-53945.24924223402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30738.60739927', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30736.3, self.close=30721.0, self.high=30736.4, self.low=30692.1 
127.0.0.1 - - [25/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-25 16:20:05,023:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30736.3, self.close=30721.0, self.high=30736.4, self.low=30692.1   
2023-06-25 16:20:06,471:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230625   155500    155959  1687679999  ...  30702.0  0.000287   1631    5
1632  20230625   160000    160459  1687680299  ...  30703.0  0.000322   1632    0
1633  20230625   160500    160959  1687680599  ...  30716.2  0.000573   1633    1
1634  20230625   161000    161459  1687680899  ...  30727.8 -0.000169   1634    2
1635  20230625   161500    161959  1687681199  ...  30692.1 -0.000498   1635    3

[5 rows x 11 columns]
2023-06-25 16:20:06,482:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=405, self.factor=0.4344192189125282, self.count=12163 

self.closeSec=1687681499, self.tradeDate='20230625', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30720.9, self.close=30736.8, self.high=30749.7, self.low=30713.0 
2023-06-25 16:25:00,719:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687681499, self.tradeDate='20230625', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30720.9, self.close=30736.8, self.high=30749.7, self.low=30713.0   
2023-06-25 16:25:00,749:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230625   160000    160459  1687680299  ...  30703.0  0.000322   1632    0
1633  20230625   160500    160959  1687680599  ...  30716.2  0.000573   1633    1
1634  20230625   161000    161459  1687680899  ...  30727.8 -0.000169   1634    2
1635  20230625   161500    161959  1687681199  ...  30692.1 -0.000498   1635    3
1636  20230625   162000    162459  1687681499  ...  30713.0  0.000514   1636    4

[5 rows x 11 columns]
2023-06-25 16:25:00,749:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-25 16:00:18,138:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230625    132959  30880.1  ...  52.916667  0.566826  0.371141
5787  20230625    135959  30860.5  ...  52.916667  0.564920  0.362672
5788  20230625    142959  30850.4  ...  53.333333  0.576977  0.348038
5789  20230625    145959  30934.2  ...  53.333333  0.563586  0.340035
5790  20230625    152959  30863.6  ...  52.916667  0.538599  0.343641

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-06-25 16:00:18,226:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.508176  0.491824       0  ...  1.164091  -1.0    0.0  1.187546
538     0  0.502276  0.497724       1  ...  1.160925  -1.0    0.0  1.190775
539     0  0.516388  0.483612       0  ...  1.163571  -1.0    0.0  1.188062
540     1  0.475926  0.524074       0  ...  1.168777  -1.0    0.0  1.182746
541     1  0.459107  0.540893       0  ...  1.169219  -1.0    0.0  1.182299

[5 rows x 10 columns]
2023-06-25 16:00:18,250:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507844  0.492156       0  ...  1.164091  -1.0    0.0  1.194401
46     0  0.502233  0.497767       1  ...  1.160925  -1.0    0.0  1.196278
47     0  0.516326  0.483674       0  ...  1.163571  -1.0    0.0  1.190816
48     1  0.475936  0.524064       0  ...  1.168777  -1.0    0.0  1.184798
49     1  0.459107  0.540893       0  ...  1.169219  -1.0    0.0  1.182299

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.697', 'enterprice': '30938.2', 'countrevence': '0', 'unrealprofit': '6007.65930581124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30713.16874908', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230625   155000    155959  1687679999    30699    30714  0.000492
2023-06-25 16:00:02,078:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6080 

self.closeSec=1687680599, self.tradeDate='20230625', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30714', self.close='30741.5'
2023-06-25 16:10:01,160:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687680599, self.tradeDate='20230625', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30714', self.close='30741.5'
2023-06-25 16:10:01,174:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230625   152000    152959  1687678199  30758.9  30725.6 -0.001086
525  20230625   153000    153959  1687678799  30725.7  30695.1 -0.000993
526  20230625   154000    154959  1687679399  30695.2  30698.9  0.000124
527  20230625   155000    155959  1687679999    30699    30714  0.000492
528  20230625   160000    160959  1687680599    30714  30741.5  0.000895
2023-06-25 16:10:01,174:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6081 

self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30741.5', self.close='30721'
127.0.0.1 - - [25/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-25 16:20:07,210:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30741.5', self.close='30721'
2023-06-25 16:20:08,022:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230625   153000    153959  1687678799  30725.7  30695.1 -0.000993
526  20230625   154000    154959  1687679399  30695.2  30698.9  0.000124
527  20230625   155000    155959  1687679999    30699    30714  0.000492
528  20230625   160000    160959  1687680599    30714  30741.5  0.000895
529  20230625   161000    161959  1687681199  30741.5    30721 -0.000667
2023-06-25 16:20:08,031:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230625   155000    155959  1687679999    30699    30714
2023-06-25 16:00:02,093:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6083 

self.closeSec=1687680599, self.tradeDate='20230625', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30714', self.close='30741.5'
2023-06-25 16:10:01,181:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687680599, self.tradeDate='20230625', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30714', self.close='30741.5'
127.0.0.1 - - [25/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-25 16:10:01,190:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230625   152000    152959  1687678199  30758.9  30725.6
17517  20230625   153000    153959  1687678799  30725.7  30695.1
17518  20230625   154000    154959  1687679399  30695.2  30698.9
17519  20230625   155000    155959  1687679999    30699    30714
17520  20230625   160000    160959  1687680599    30714  30741.5
2023-06-25 16:10:01,190:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6084 

self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30741.5', self.close='30721'
127.0.0.1 - - [25/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-25 16:20:09,181:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30741.5', self.close='30721'
2023-06-25 16:20:09,298:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230625   153000    153959  1687678799  30725.7  30695.1
17518  20230625   154000    154959  1687679399  30695.2  30698.9
17519  20230625   155000    155959  1687679999    30699    30714
17520  20230625   160000    160959  1687680599    30714  30741.5
17521  20230625   161000    161959  1687681199  30741.5    30721
2023-06-25 16:20:09,299:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230625   155000    155959  1687679999    30699    30714
2023-06-25 16:00:02,081:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6083 

self.closeSec=1687680599, self.tradeDate='20230625', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30714', self.close='30741.5'
2023-06-25 16:10:01,167:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687680599, self.tradeDate='20230625', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30714', self.close='30741.5'
2023-06-25 16:10:01,172:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230625   152000    152959  1687678199  30758.9  30725.6
12189  20230625   153000    153959  1687678799  30725.7  30695.1
12190  20230625   154000    154959  1687679399  30695.2  30698.9
12191  20230625   155000    155959  1687679999    30699    30714
12192  20230625   160000    160959  1687680599    30714  30741.5
2023-06-25 16:10:01,172:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6084 

self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30741.5', self.close='30721'
127.0.0.1 - - [25/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-25 16:20:08,775:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30741.5', self.close='30721'
2023-06-25 16:20:09,062:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230625   153000    153959  1687678799  30725.7  30695.1
12190  20230625   154000    154959  1687679399  30695.2  30698.9
12191  20230625   155000    155959  1687679999    30699    30714
12192  20230625   160000    160959  1687680599    30714  30741.5
12193  20230625   161000    161959  1687681199  30741.5    30721
2023-06-25 16:20:09,063:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12160
self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30736.3, self.close=30721.0, self.high=30736.4, self.low=30692.1, self.vol=811.593, self.amt=24924163.5159 
127.0.0.1 - - [25/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-25 16:20:07,421:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230625   155500    155959  ...         0.0        0.0       0
5952  20230625   160000    160459  ...         0.0        0.0       0
5953  20230625   160500    160959  ...         0.0        0.0       0
5954  20230625   161000    161459  ...         0.0        0.0       0
5955  20230625   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 16:20:07,442:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687681199, self.tradeDate='20230625', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30736.3, self.close=30721.0, self.high=30736.4, self.low=30692.1, self.vol=811.593, self.amt=24924163.5159, ukdf['pct'].iloc[-1]=-0.000498 , ukdf['amount'].iloc[-1]=24924163.5159, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '143907.8174467687', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30718.6349707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12161
self.closeSec=1687681499, self.tradeDate='20230625', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30720.9, self.close=30736.8, self.high=30749.7, self.low=30713.0, self.vol=454.642, self.amt=13971200.5978 
2023-06-25 16:25:00,766:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230625   160000    160459  ...         0.0        0.0       0
5953  20230625   160500    160959  ...         0.0        0.0       0
5954  20230625   161000    161459  ...         0.0        0.0       0
5955  20230625   161500    161959  ...         0.0        0.0       0
5956  20230625   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 16:25:00,767:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687681499, self.tradeDate='20230625', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30720.9, self.close=30736.8, self.high=30749.7, self.low=30713.0, self.vol=454.642, self.amt=13971200.5978, ukdf['pct'].iloc[-1]=0.000514 , ukdf['amount'].iloc[-1]=13971200.5978, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '144649.61341628707', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30738.60739927', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230625   040000    075959  1687651199  ...    721  0.620402  0.062441     NaN
722  20230625   080000    115959  1687665599  ...    722  0.493758 -0.296012     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '147885.5712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30750', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [25/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=253
self.closeSec=1687679999, self.tradeDate='20230625', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30742.0, self.close=30714.0, self.high=31053.2, self.low=30652.8, self.vol=79266.773, self.amt=2445980338.77762 
2023-06-25 16:00:01,688:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687679999, self.tradeDate='20230625', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30742.0, self.close=30714.0, self.high=31053.2, self.low=30652.8, self.vol=79266.773, self.amt=2445980338.77762 
2023-06-25 16:00:01,731:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230624   200000    235959  ...  72296.954  2.209368e+09 -0.009474
720  20230625   000000    035959  ...  58688.914  1.790778e+09  0.007833
721  20230625   040000    075959  ...  31333.988  9.561354e+08 -0.003204
722  20230625   080000    115959  ...  36315.838  1.111841e+09  0.007135
723  20230625   120000    155959  ...  79266.773  2.445980e+09 -0.000911

[5 rows x 11 columns]
2023-06-25 16:00:03,129:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230624   200000    235959  1687622399  ...    719  0.734894  0.390758     NaN
720  20230625   000000    035959  1687636799  ...    720  0.615898  0.050613     NaN
721  20230625   040000    075959  1687651199  ...    721  0.620402  0.062441     NaN
722  20230625   080000    115959  1687665599  ...    722  0.493758 -0.296012     NaN
723  20230625   120000    155959  1687679999  ...    723  0.469958 -0.369203     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '145965.1872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


