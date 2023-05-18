# 20230519 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1312
self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27042.3, self.close=27062.0, self.high=27062.9, self.low=27017.0, self.vol=2283.224, self.amt=61738303.6367 
127.0.0.1 - - [19/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-19 00:20:00,502:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230518   235500    235959  ...    0.392545   0.309920       0
5760  20230519   000000    000459  ...    0.392418   0.309988       0
5761  20230519   000500    000959  ...    0.392285   0.310053       0
5762  20230519   001000    001459  ...    0.392150   0.310118       0
5763  20230519   001500    001959  ...    0.392010   0.310181       0

[5 rows x 18 columns]
2023-05-19 00:20:00,505:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27042.3, self.close=27062.0, self.high=27062.9, self.low=27017.0, self.vol=2283.224, self.amt=61738303.6367, ukdf['pct'].iloc[-1]=0.000728 , ukdf['amount'].iloc[-1]=61738303.6367, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.39200977269941584, signal=0, value_std=0.31018133158898575 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2737.8516', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27061.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1313
self.closeSec=1684427099, self.tradeDate='20230519', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27061.9, self.close=27050.9, self.high=27062.0, self.low=27003.9, self.vol=2740.089, self.amt=74062838.8722 
2023-05-19 00:25:00,429:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230519   000000    000459  ...    0.392418   0.309988       0
5761  20230519   000500    000959  ...    0.392285   0.310053       0
5762  20230519   001000    001459  ...    0.392150   0.310118       0
5763  20230519   001500    001959  ...    0.392010   0.310181       0
5764  20230519   002000    002459  ...    0.391867   0.310244       0

[5 rows x 18 columns]
2023-05-19 00:25:00,430:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684427099, self.tradeDate='20230519', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27061.9, self.close=27050.9, self.high=27062.0, self.low=27003.9, self.vol=2740.089, self.amt=74062838.8722, ukdf['pct'].iloc[-1]=-0.00041 , ukdf['amount'].iloc[-1]=74062838.8722, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.39186735324118754, signal=0, value_std=0.31024357839351807 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2561.14792726518', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27048.81123993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=41, self.factor=0.3859268503553228, self.count=1314 

self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27042.3, self.close=27062.0, self.high=27062.9, self.low=27017.0 
2023-05-19 00:20:00,437:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27042.3, self.close=27062.0, self.high=27062.9, self.low=27017.0   
2023-05-19 00:20:00,563:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230518   235500    235959  1684425599  ...  27031.0 -0.002638   1727    5
1440  20230519   000000    000459  1684425899  ...  27027.8  0.000454   1440    0
1441  20230519   000500    000959  1684426199  ...  27050.0 -0.000609   1441    1
1442  20230519   001000    001459  1684426499  ...  27018.6 -0.001060   1442    2
1443  20230519   001500    001959  1684426799  ...  27017.0  0.000728   1443    3

[5 rows x 11 columns]
2023-05-19 00:20:00,563:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=41, self.factor=0.3859268503553228, self.count=1315 

self.closeSec=1684427099, self.tradeDate='20230519', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27061.9, self.close=27050.9, self.high=27062.0, self.low=27003.9 
2023-05-19 00:25:00,360:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684427099, self.tradeDate='20230519', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27061.9, self.close=27050.9, self.high=27062.0, self.low=27003.9   
2023-05-19 00:25:00,408:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230519   000000    000459  1684425899  ...  27027.8  0.000454   1440    0
1441  20230519   000500    000959  1684426199  ...  27050.0 -0.000609   1441    1
1442  20230519   001000    001459  1684426499  ...  27018.6 -0.001060   1442    2
1443  20230519   001500    001959  1684426799  ...  27017.0  0.000728   1443    3
1444  20230519   002000    002459  1684427099  ...  27003.9 -0.000410   1444    4

[5 rows x 11 columns]
2023-05-19 00:25:00,408:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-19 00:00:17,908:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230518    212959  27224.5  ...  49.166667  0.506798  0.251377
5803  20230518    215959  27188.4  ...  49.166667  0.519492  0.272332
5804  20230518    222959  27246.4  ...  49.583333  0.530732  0.286049
5805  20230518    225959  27299.3  ...  49.166667  0.515990  0.302686
5806  20230518    232959  27236.0  ...  48.750000  0.487834  0.335621

[5 rows x 33 columns]
0.5275735294117647
acc is : 0.5275735294117647
2023-05-19 00:00:18,042:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.473841  0.526159       1  ...  0.977889   1.0    0.0  0.943046
540     1  0.491568  0.508432       1  ...  0.979784   1.0    0.0  0.944874
541     1  0.492455  0.507545       0  ...  0.977516   1.0    0.0  0.942686
542     1  0.475065  0.524935       0  ...  0.972897   1.0    0.0  0.938232
543     1  0.462232  0.537768       0  ...  0.971744   1.0    0.0  0.937121

[5 rows x 10 columns]
2023-05-19 00:00:18,076:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.474210  0.525790       1  ...  0.977889   1.0    0.0  0.944236
46     1  0.491669  0.508331       1  ...  0.979784   1.0    0.0  0.944629
47     1  0.492605  0.507395       0  ...  0.977516   1.0    0.0  0.942442
48     1  0.475108  0.524892       0  ...  0.972897   1.0    0.0  0.938755
49     1  0.462232  0.537768       0  ...  0.971744   1.0    0.0  0.937121

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.819', 'enterprice': '27153.5', 'countrevence': '0', 'unrealprofit': '-2557.06770828366', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27061.58196886', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [19/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-05-19 00:00:02,977:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42188F1684425602270I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684425602706334, 'quantity': '25.975', 'price': '27071.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684425601022, 'updatetime': 1684425602706, 'tradetype': 'usdt', 'selfid': 42188, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684425602706, 'clientorderid': '42188F1684425602270I0L59', 'price': '27071.1', 'quantity': '25.975', 'commission': '703.1718225', 'commissionasset': 'USDT', 'tradetime': 1684425602706, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684425602706}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=656 

self.closeSec=1684426199, self.tradeDate='20230519', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27075.2', self.close='27071'
2023-05-19 00:10:00,376:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684426199, self.tradeDate='20230519', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27075.2', self.close='27071'
2023-05-19 00:10:00,424:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230518   232000    232959  1684423799  27204.8  27107.3 -0.003584
573  20230518   233000    233959  1684424399  27107.3  27113.9  0.000243
574  20230518   234000    234959  1684424999  27113.9  27142.4  0.001051
575  20230518   235000    235959  1684425599  27142.5  27075.2 -0.002476
576  20230519   000000    000959  1684426199  27075.2    27071 -0.000155
2023-05-19 00:10:00,424:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/May/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=657 

self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27071.1', self.close='27062'
2023-05-19 00:20:00,496:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27071.1', self.close='27062'
2023-05-19 00:20:00,529:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230518   233000    233959  1684424399  27107.3  27113.9  0.000243
574  20230518   234000    234959  1684424999  27113.9  27142.4  0.001051
575  20230518   235000    235959  1684425599  27142.5  27075.2 -0.002476
576  20230519   000000    000959  1684426199  27075.2    27071 -0.000155
577  20230519   001000    001959  1684426799  27071.1    27062 -0.000332
2023-05-19 00:20:00,533:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [19/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-19 00:00:03,385:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42189F1684425602463I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684425602867515, 'quantity': '35.963', 'price': '27071', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684425601134, 'updatetime': 1684425602867, 'tradetype': 'usdt', 'selfid': 42189, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684425602867, 'clientorderid': '42189F1684425602463I0L57', 'price': '27071', 'quantity': '35.963', 'commission': '973.554373', 'commissionasset': 'USDT', 'tradetime': 1684425602867, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684425602867}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=659 

self.closeSec=1684426199, self.tradeDate='20230519', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27075.2', self.close='27071'
127.0.0.1 - - [19/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-19 00:10:00,373:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684426199, self.tradeDate='20230519', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27075.2', self.close='27071'
2023-05-19 00:10:00,421:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230518   232000    232959  1684423799  27204.8  27107.3
17421  20230518   233000    233959  1684424399  27107.3  27113.9
17422  20230518   234000    234959  1684424999  27113.9  27142.4
17423  20230518   235000    235959  1684425599  27142.5  27075.2
17424  20230519   000000    000959  1684426199  27075.2    27071
2023-05-19 00:10:00,421:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/May/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=660 

self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27071.1', self.close='27062'
2023-05-19 00:20:00,480:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27071.1', self.close='27062'
2023-05-19 00:20:00,546:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230518   233000    233959  1684424399  27107.3  27113.9
17422  20230518   234000    234959  1684424999  27113.9  27142.4
17423  20230518   235000    235959  1684425599  27142.5  27075.2
17424  20230519   000000    000959  1684426199  27075.2    27071
17425  20230519   001000    001959  1684426799  27071.1    27062
2023-05-19 00:20:00,546:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [19/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-19 00:00:03,153:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42190F1684425602513I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684425602947847, 'quantity': '46.657', 'price': '27071.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684425601156, 'updatetime': 1684425602947, 'tradetype': 'usdt', 'selfid': 42190, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684425602947, 'clientorderid': '42190F1684425602513I0L2', 'price': '27071.1', 'quantity': '46.657', 'commission': '1263.0563127', 'commissionasset': 'USDT', 'tradetime': 1684425602947, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684425602947}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=659 

self.closeSec=1684426199, self.tradeDate='20230519', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27075.2', self.close='27071'
2023-05-19 00:10:00,333:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684426199, self.tradeDate='20230519', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27075.2', self.close='27071'
2023-05-19 00:10:00,402:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230518   232000    232959  1684423799  27204.8  27107.3
12237  20230518   233000    233959  1684424399  27107.3  27113.9
12238  20230518   234000    234959  1684424999  27113.9  27142.4
12239  20230518   235000    235959  1684425599  27142.5  27075.2
12240  20230519   000000    000959  1684426199  27075.2    27071
2023-05-19 00:10:00,402:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [19/May/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=660 

self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27071.1', self.close='27062'
2023-05-19 00:20:00,482:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27071.1', self.close='27062'
2023-05-19 00:20:00,537:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230518   233000    233959  1684424399  27107.3  27113.9
12238  20230518   234000    234959  1684424999  27113.9  27142.4
12239  20230518   235000    235959  1684425599  27142.5  27075.2
12240  20230519   000000    000959  1684426199  27075.2    27071
12241  20230519   001000    001959  1684426799  27071.1    27062
2023-05-19 00:20:00,537:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1312
self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27042.3, self.close=27062.0, self.high=27062.9, self.low=27017.0, self.vol=2283.224, self.amt=61738303.6367 
127.0.0.1 - - [19/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-19 00:20:00,501:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230518   235500    235959  ...    0.239030   0.301016       0
5760  20230519   000000    000459  ...    0.238786   0.301020       0
5761  20230519   000500    000959  ...    0.238542   0.301024       0
5762  20230519   001000    001459  ...    0.238297   0.301026       0
5763  20230519   001500    001959  ...    0.238051   0.301028       0

[5 rows x 18 columns]
2023-05-19 00:20:00,504:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684426799, self.tradeDate='20230519', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27042.3, self.close=27062.0, self.high=27062.9, self.low=27017.0, self.vol=2283.224, self.amt=61738303.6367, ukdf['pct'].iloc[-1]=0.000728 , ukdf['amount'].iloc[-1]=61738303.6367, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.23805129656774598, signal=0, value_std=0.3010283136472924 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8078.1675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27061.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [19/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1313
self.closeSec=1684427099, self.tradeDate='20230519', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27061.9, self.close=27050.9, self.high=27062.0, self.low=27003.9, self.vol=2740.089, self.amt=74062838.8722 
2023-05-19 00:25:00,427:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230519   000000    000459  ...    0.238786   0.301020       0
5761  20230519   000500    000959  ...    0.238542   0.301024       0
5762  20230519   001000    001459  ...    0.238297   0.301026       0
5763  20230519   001500    001959  ...    0.238051   0.301028       0
5764  20230519   002000    002459  ...    0.237817   0.301038       0

[5 rows x 18 columns]
2023-05-19 00:25:00,427:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684427099, self.tradeDate='20230519', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27061.9, self.close=27050.9, self.high=27062.0, self.low=27003.9, self.vol=2740.089, self.amt=74062838.8722, ukdf['pct'].iloc[-1]=-0.00041 , ukdf['amount'].iloc[-1]=74062838.8722, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.23781675980219, signal=0, value_std=0.3010382696317229 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '7606.89426224013', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27048.81123993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230518   040000    075959  ...   67419.315  1.844731e+09  0.000683
722  20230518   080000    115959  ...   35846.271  9.806639e+08 -0.001405
723  20230518   120000    155959  ...   61937.260  1.689377e+09  0.000651
724  20230518   160000    195959  ...   42133.547  1.153398e+09  0.000614
725  20230518   200000    235959  ...  145244.456  3.954902e+09 -0.011562

[5 rows x 11 columns]
2023-05-19 00:00:02,073:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230518   040000    075959  1684367999  ...    721  0.532623  0.155524     NaN
722  20230518   080000    115959  1684382399  ...    722  0.500527 -0.024523     NaN
723  20230518   120000    155959  1684396799  ...    723  0.476310 -0.157409     NaN
724  20230518   160000    195959  1684411199  ...    724  0.408356 -0.536552     NaN
725  20230518   200000    235959  1684425599  ...    725  0.382483 -0.670594    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '2554.695', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27074.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '2554.695', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27074.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-05-19 00:00:09,177:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1399908.3323396', 'total': '1399908.3323396', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-05-19 00:00:09,694:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 51.549, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42192F1684425609690I0L65'}
2023-05-19 00:00:09,719:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:5190000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230518, closeTime:235959, close:27075.2, sign:-1, total:1399908.3323396, side:sell  
127.0.0.1 - - [19/May/2023 00:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/May/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-05-19 00:00:09,723:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42191F1684425604064I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684425604496353, 'quantity': '51.61', 'price': '27070.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684425603127, 'updatetime': 1684425604496, 'tradetype': 'usdt', 'selfid': 42191, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684425604496, 'clientorderid': '42191F1684425604064I0L65', 'price': '27070.1', 'quantity': '51.61', 'commission': '1397.087861', 'commissionasset': 'USDT', 'tradetime': 1684425604496, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684425604496}], 'gatetype': 'simulator', 'handletime': 0}
2023-05-19 00:00:09,724:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42191F1684425604064I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684425604496353, 'quantity': '51.61', 'price': '27070.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684425603127, 'updatetime': 1684425604496, 'tradetype': 'usdt', 'selfid': 42191, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684425604496, 'clientorderid': '42191F1684425604064I0L65', 'price': '27070.1', 'quantity': '51.61', 'commission': '1397.087861', 'commissionasset': 'USDT', 'tradetime': 1684425604496, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684425604496}], 'gatetype': 'simulator', 'handletime': 0}
2023-05-19 00:00:10,143:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42192F1684425609690I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684425610103261, 'quantity': '51.549', 'price': '27070.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684425609194, 'updatetime': 1684425610103, 'tradetype': 'usdt', 'selfid': 42192, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684425610103, 'clientorderid': '42192F1684425609690I0L65', 'price': '27070.5', 'quantity': '51.549', 'commission': '1395.4572045', 'commissionasset': 'USDT', 'tradetime': 1684425610103, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684425610103}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/May/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-05-19 00:00:10,355:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42192F1684425609690I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684425610103261, 'quantity': '51.549', 'price': '27070.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684425609194, 'updatetime': 1684425610103, 'tradetype': 'usdt', 'selfid': 42192, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684425610103, 'clientorderid': '42192F1684425609690I0L65', 'price': '27070.5', 'quantity': '51.549', 'commission': '1395.4572045', 'commissionasset': 'USDT', 'tradetime': 1684425610103, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684425610103}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/May/2023 00:00:10] "POST / HTTP/1.1" 200 -


