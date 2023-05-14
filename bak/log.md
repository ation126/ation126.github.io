# 20230515 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=160
self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27050.0, self.close=27029.3, self.high=27072.0, self.low=27005.4, self.vol=2172.925, self.amt=58746015.0942 
2023-05-15 00:20:00,391:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230514   235500    235959  ...    0.544906   0.173118      -1
5760  20230515   000000    000459  ...    0.544766   0.173355      -1
5761  20230515   000500    000959  ...    0.544624   0.173592      -1
5762  20230515   001000    001459  ...    0.544480   0.173828      -1
5763  20230515   001500    001959  ...    0.544338   0.174064      -1

[5 rows x 18 columns]
2023-05-15 00:20:00,396:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27050.0, self.close=27029.3, self.high=27072.0, self.low=27005.4, self.vol=2172.925, self.amt=58746015.0942, ukdf['pct'].iloc[-1]=-0.000769 , ukdf['amount'].iloc[-1]=58746015.0942, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.5443382481924779, signal=-1, value_std=0.17406405292793053 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2289.4344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27029.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=161
self.closeSec=1684081499, self.tradeDate='20230515', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27029.2, self.close=27047.8, self.high=27056.9, self.low=27002.0, self.vol=1296.894, self.amt=35055861.8127 
127.0.0.1 - - [15/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-15 00:25:00,405:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230515   000000    000459  ...    0.544766   0.173355      -1
5761  20230515   000500    000959  ...    0.544624   0.173592      -1
5762  20230515   001000    001459  ...    0.544480   0.173828      -1
5763  20230515   001500    001959  ...    0.544338   0.174064      -1
5764  20230515   002000    002459  ...    0.544195   0.174300      -1

[5 rows x 18 columns]
2023-05-15 00:25:00,406:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684081499, self.tradeDate='20230515', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27029.2, self.close=27047.8, self.high=27056.9, self.low=27002.0, self.vol=1296.894, self.amt=35055861.8127, ukdf['pct'].iloc[-1]=0.000684 , ukdf['amount'].iloc[-1]=35055861.8127, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.5441952651015609, signal=-1, value_std=0.17429956229594348 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2549.01654484356', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27047.94010806', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=-1, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=26, self.factor=0.38375297835416683, self.count=162 

self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27050.0, self.close=27029.3, self.high=27072.0, self.low=27005.4 
2023-05-15 00:20:00,343:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27050.0, self.close=27029.3, self.high=27072.0, self.low=27005.4   
2023-05-15 00:20:00,372:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230514   235500    235959  1684079999  ...  27050.1 -0.000111   1725    3
1439  20230515   000000    000459  1684080299  ...  27070.0  0.000502   1439    5
1440  20230515   000500    000959  1684080599  ...  27084.9  0.000934   1440    0
1441  20230515   001000    001459  1684080899  ...  27050.0 -0.002221   1441    1
1442  20230515   001500    001959  1684081199  ...  27005.4 -0.000769   1442    2

[5 rows x 11 columns]
2023-05-15 00:20:00,372:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=26, self.factor=0.38375297835416683, self.count=163 

self.closeSec=1684081499, self.tradeDate='20230515', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27029.2, self.close=27047.8, self.high=27056.9, self.low=27002.0 
2023-05-15 00:25:00,368:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684081499, self.tradeDate='20230515', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27029.2, self.close=27047.8, self.high=27056.9, self.low=27002.0   
2023-05-15 00:25:00,398:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230515   000000    000459  1684080299  ...  27070.0  0.000502   1439    5
1440  20230515   000500    000959  1684080599  ...  27084.9  0.000934   1440    0
1441  20230515   001000    001459  1684080899  ...  27050.0 -0.002221   1441    1
1442  20230515   001500    001959  1684081199  ...  27005.4 -0.000769   1442    2
1443  20230515   002000    002459  1684081499  ...  27002.0  0.000684   1443    3

[5 rows x 11 columns]
2023-05-15 00:25:00,399:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-15 00:00:16,935:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230514    212959  26861.0  ...  50.416667  0.507655  0.470916
5803  20230514    215959  26842.4  ...  50.833333  0.521325  0.460216
5804  20230514    222959  26898.0  ...  50.833333  0.509918  0.456147
5805  20230514    225959  26854.0  ...  50.833333  0.532733  0.429407
5806  20230514    232959  26950.1  ...  51.250000  0.554154  0.416623

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-05-15 00:00:16,999:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494636  0.505364       1  ...  0.977669   1.0    0.0  0.939232
540     0  0.514428  0.485572       0  ...  0.976073   1.0    0.0  0.937699
541     1  0.493408  0.506592       1  ...  0.979563   1.0    0.0  0.941051
542     0  0.531900  0.468100       1  ...  0.983092   1.0    0.0  0.944442
543     0  0.529397  0.470603       1  ...  0.983972   1.0    0.0  0.945287

[5 rows x 10 columns]
2023-05-15 00:00:17,009:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
22     1  0.494462  0.505538       1  ...  0.977669   1.0    0.0  0.943174
23     0  0.514102  0.485898       0  ...  0.976073   1.0    0.0  0.939299
24     1  0.493394  0.506606       1  ...  0.979563   1.0    0.0  0.942657
25     0  0.531710  0.468290       1  ...  0.983092   1.0    0.0  0.944250
26     0  0.529397  0.470603       1  ...  0.983972   1.0    0.0  0.945287

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.199', 'enterprice': '26801.5', 'countrevence': '0', 'unrealprofit': '7706.7867', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27074.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-05-15 00:00:00,607:INFO:modifiedmom:main.py:206:insertFactor:2218259: curDateTime:5150000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230514, closeTime:235959, close:27071.4, total:69712.39782000001, mom:0.006532106581034425, thd:0.0, side:sell 

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=80 

self.closeSec=1684080599, self.tradeDate='20230515', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27071.4', self.close='27110.3'
2023-05-15 00:10:00,371:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684080599, self.tradeDate='20230515', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27071.4', self.close='27110.3'
127.0.0.1 - - [15/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-15 00:10:00,400:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230514   232000    232959  1684078199  27080.1  27047.2 -0.001215
573  20230514   233000    233959  1684078799  27047.1  27038.8 -0.000311
574  20230514   234000    234959  1684079399  27038.8  27104.3  0.002422
575  20230514   235000    235959  1684079999  27104.3  27071.4 -0.001214
576  20230515   000000    000959  1684080599  27071.4  27110.3  0.001437
2023-05-15 00:10:00,400:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=81 

self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27110.4', self.close='27029.3'
127.0.0.1 - - [15/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 00:20:00,454:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27110.4', self.close='27029.3'
2023-05-15 00:20:00,463:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230514   233000    233959  1684078799  27047.1  27038.8 -0.000311
574  20230514   234000    234959  1684079399  27038.8  27104.3  0.002422
575  20230514   235000    235959  1684079999  27104.3  27071.4 -0.001214
576  20230515   000000    000959  1684080599  27071.4  27110.3  0.001437
577  20230515   001000    001959  1684081199  27110.4  27029.3 -0.002988
2023-05-15 00:20:00,463:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [15/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-05-15 00:00:02,977:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42165F1684080002308I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684080002825757, 'quantity': '36.422', 'price': '27074.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684080000973, 'updatetime': 1684080002825, 'tradetype': 'usdt', 'selfid': 42165, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684080002825, 'clientorderid': '42165F1684080002308I0L57', 'price': '27074.9', 'quantity': '36.422', 'commission': '986.1220078', 'commissionasset': 'USDT', 'tradetime': 1684080002825, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684080002825}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=83 

self.closeSec=1684080599, self.tradeDate='20230515', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27071.4', self.close='27110.3'
2023-05-15 00:10:00,372:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684080599, self.tradeDate='20230515', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27071.4', self.close='27110.3'
127.0.0.1 - - [15/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-15 00:10:00,392:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230514   232000    232959  1684078199  27080.1  27047.2
17421  20230514   233000    233959  1684078799  27047.1  27038.8
17422  20230514   234000    234959  1684079399  27038.8  27104.3
17423  20230514   235000    235959  1684079999  27104.3  27071.4
17424  20230515   000000    000959  1684080599  27071.4  27110.3
2023-05-15 00:10:00,394:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=84 

self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27110.4', self.close='27029.3'
127.0.0.1 - - [15/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 00:20:00,530:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27110.4', self.close='27029.3'
2023-05-15 00:20:00,584:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230514   233000    233959  1684078799  27047.1  27038.8
17422  20230514   234000    234959  1684079399  27038.8  27104.3
17423  20230514   235000    235959  1684079999  27104.3  27071.4
17424  20230515   000000    000959  1684080599  27071.4  27110.3
17425  20230515   001000    001959  1684081199  27110.4  27029.3
2023-05-15 00:20:00,584:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [15/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-05-15 00:00:02,447:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42164F1684080001786I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684080002223784, 'quantity': '45.625', 'price': '27074.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684080000611, 'updatetime': 1684080002223, 'tradetype': 'usdt', 'selfid': 42164, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684080002223, 'clientorderid': '42164F1684080001786I0L2', 'price': '27074.9', 'quantity': '45.625', 'commission': '1235.2923125', 'commissionasset': 'USDT', 'tradetime': 1684080002223, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684080002223}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=83 

self.closeSec=1684080599, self.tradeDate='20230515', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27071.4', self.close='27110.3'
2023-05-15 00:10:00,374:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684080599, self.tradeDate='20230515', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27071.4', self.close='27110.3'
2023-05-15 00:10:00,405:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230514   232000    232959  1684078199  27080.1  27047.2
12237  20230514   233000    233959  1684078799  27047.1  27038.8
12238  20230514   234000    234959  1684079399  27038.8  27104.3
12239  20230514   235000    235959  1684079999  27104.3  27071.4
12240  20230515   000000    000959  1684080599  27071.4  27110.3
2023-05-15 00:10:00,406:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': False, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=84 

self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27110.4', self.close='27029.3'
127.0.0.1 - - [15/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 00:20:00,467:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27110.4', self.close='27029.3'
2023-05-15 00:20:00,515:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230514   233000    233959  1684078799  27047.1  27038.8
12238  20230514   234000    234959  1684079399  27038.8  27104.3
12239  20230514   235000    235959  1684079999  27104.3  27071.4
12240  20230515   000000    000959  1684080599  27071.4  27110.3
12241  20230515   001000    001959  1684081199  27110.4  27029.3
2023-05-15 00:20:00,516:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': False, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=160
self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27050.0, self.close=27029.3, self.high=27072.0, self.low=27005.4, self.vol=2172.925, self.amt=58746015.0942 
127.0.0.1 - - [15/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 00:20:00,395:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230514   235500    235959  ...    0.497700   0.132717       1
5760  20230515   000000    000459  ...    0.497994   0.133656       1
5761  20230515   000500    000959  ...    0.498293   0.134587       1
5762  20230515   001000    001459  ...    0.498602   0.135541       1
5763  20230515   001500    001959  ...    0.498933   0.136568       1

[5 rows x 18 columns]
2023-05-15 00:20:00,396:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684081199, self.tradeDate='20230515', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27050.0, self.close=27029.3, self.high=27072.0, self.low=27005.4, self.vol=2172.925, self.amt=58746015.0942, ukdf['pct'].iloc[-1]=-0.000769 , ukdf['amount'].iloc[-1]=58746015.0942, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=1.2387503534382192, value_mean=0.4989331221569048, signal=1, value_std=0.13656770731577056 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '6882.2273', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27029.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=161
self.closeSec=1684081499, self.tradeDate='20230515', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27029.2, self.close=27047.8, self.high=27056.9, self.low=27002.0, self.vol=1296.894, self.amt=35055861.8127 
127.0.0.1 - - [15/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-15 00:25:00,389:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230515   000000    000459  ...    0.497994   0.133656       1
5761  20230515   000500    000959  ...    0.498293   0.134587       1
5762  20230515   001000    001459  ...    0.498602   0.135541       1
5763  20230515   001500    001959  ...    0.498933   0.136568       1
5764  20230515   002000    002459  ...    0.499301   0.137783       1

[5 rows x 18 columns]
2023-05-15 00:25:00,390:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684081499, self.tradeDate='20230515', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27029.2, self.close=27047.8, self.high=27056.9, self.low=27002.0, self.vol=1296.894, self.amt=35055861.8127, ukdf['pct'].iloc[-1]=0.000684 , ukdf['amount'].iloc[-1]=35055861.8127, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=1.3055400055680393, value_mean=0.49930097867784173, signal=1, value_std=0.13778324716911267 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '7574.53955345646', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27047.94010806', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=1, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230514   120000    155959  1684051199  ...    723  0.480029  0.185044     NaN
724  20230514   160000    195959  1684065599  ...    724  0.480727  0.180878     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '1187.58128419668', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26796.05179487', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=6897.9369698, self.flagDict['side']='', self.tradeCount=0, self.count=3
self.closeSec=1684079999, self.tradeDate='20230514', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26794.8, self.close=27071.4, self.high=27200.0, self.low=26730.0, self.vol=86298.935, self.amt=2327455422.54989 
127.0.0.1 - - [15/May/2023 00:00:00] "POST / HTTP/1.1" 200 -
2023-05-15 00:00:00,355:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684079999, self.tradeDate='20230514', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26794.8, self.close=27071.4, self.high=27200.0, self.low=26730.0, self.vol=86298.935, self.amt=2327455422.54989 
2023-05-15 00:00:00,480:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230514   040000    075959  ...  31112.700  8.352078e+08 -0.002233
722  20230514   080000    115959  ...  47550.339  1.270832e+09  0.003359
723  20230514   120000    155959  ...  20315.573  5.451243e+08 -0.000473
724  20230514   160000    195959  ...  18182.978  4.876535e+08 -0.001680
725  20230514   200000    235959  ...  86298.935  2.327455e+09  0.010323

[5 rows x 11 columns]
2023-05-15 00:00:01,330:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230514   040000    075959  1684022399  ...    721  0.480154  0.187069     NaN
722  20230514   080000    115959  1684036799  ...    722  0.489190  0.227805     NaN
723  20230514   120000    155959  1684051199  ...    723  0.480029  0.185044     NaN
724  20230514   160000    195959  1684065599  ...    724  0.480727  0.180878     NaN
725  20230514   200000    235959  1684079999  ...    725  0.492854  0.222064     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-13318.744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27072.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


