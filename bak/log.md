# 20230629 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13120
self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30422.0, self.close=30372.9, self.high=30433.2, self.low=30348.5, self.vol=2363.312, self.amt=71798433.7135 
127.0.0.1 - - [29/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-29 00:20:07,352:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230628   235500    235959  ...         0.0        0.0       0
5760  20230629   000000    000459  ...         0.0        0.0       0
5761  20230629   000500    000959  ...         0.0        0.0       0
5762  20230629   001000    001459  ...         0.0        0.0       0
5763  20230629   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 00:20:07,391:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30422.0, self.close=30372.9, self.high=30433.2, self.low=30348.5, self.vol=2363.312, self.amt=71798433.7135, ukdf['pct'].iloc[-1]=-0.001611 , ukdf['amount'].iloc[-1]=71798433.7135, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48823.1634', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30370.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13121
self.closeSec=1687969499, self.tradeDate='20230629', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30373.0, self.close=30386.0, self.high=30403.3, self.low=30368.8, self.vol=719.07, self.amt=21850852.6031 
127.0.0.1 - - [29/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-29 00:25:00,805:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230629   000000    000459  ...         0.0        0.0       0
5761  20230629   000500    000959  ...         0.0        0.0       0
5762  20230629   001000    001459  ...         0.0        0.0       0
5763  20230629   001500    001959  ...         0.0        0.0       0
5764  20230629   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 00:25:00,808:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687969499, self.tradeDate='20230629', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30373.0, self.close=30386.0, self.high=30403.3, self.low=30368.8, self.vol=719.07, self.amt=21850852.6031, ukdf['pct'].iloc[-1]=0.000431 , ukdf['amount'].iloc[-1]=21850852.6031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49044.08138312496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30386.66370696', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30422.0, self.close=30372.9, self.high=30433.2, self.low=30348.5 
127.0.0.1 - - [29/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-29 00:20:04,908:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30422.0, self.close=30372.9, self.high=30433.2, self.low=30348.5   
2023-06-29 00:20:06,461:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230628   235500    235959  1687967999  ...  30375.4  0.000273   1727    5
1440  20230629   000000    000459  1687968299  ...  30390.1  0.000898   1440    0
1441  20230629   000500    000959  1687968599  ...  30401.5 -0.000118   1441    1
1442  20230629   001000    001459  1687968899  ...  30413.5 -0.000053   1442    2
1443  20230629   001500    001959  1687969199  ...  30348.5 -0.001611   1443    3

[5 rows x 11 columns]
2023-06-29 00:20:06,480:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6089637881704203, self.count=13123 

self.closeSec=1687969499, self.tradeDate='20230629', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30373.0, self.close=30386.0, self.high=30403.3, self.low=30368.8 
127.0.0.1 - - [29/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-29 00:25:00,745:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687969499, self.tradeDate='20230629', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30373.0, self.close=30386.0, self.high=30403.3, self.low=30368.8   
2023-06-29 00:25:00,781:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230629   000000    000459  1687968299  ...  30390.1  0.000898   1440    0
1441  20230629   000500    000959  1687968599  ...  30401.5 -0.000118   1441    1
1442  20230629   001000    001459  1687968899  ...  30413.5 -0.000053   1442    2
1443  20230629   001500    001959  1687969199  ...  30348.5 -0.001611   1443    3
1444  20230629   002000    002459  1687969499  ...  30368.8  0.000431   1444    4

[5 rows x 11 columns]
2023-06-29 00:25:00,781:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-29 00:00:18,627:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230628    212959  30091.6  ...  49.166667  0.452662  0.729794
5803  20230628    215959  30154.5  ...  49.583333  0.459989  0.729853
5804  20230628    222959  30193.5  ...  49.583333  0.472677  0.723770
5805  20230628    225959  30262.2  ...  49.583333  0.480223  0.714377
5806  20230628    232959  30304.8  ...  49.583333  0.489663  0.700903

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-06-29 00:00:18,725:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.501705  0.498295       1  ...  1.049118  -1.0    0.0  1.135623
540     1  0.499031  0.500969       1  ...  1.046731  -1.0    0.0  1.138207
541     0  0.512123  0.487877       1  ...  1.045292  -1.0    0.0  1.139772
542     0  0.510687  0.489313       1  ...  1.043475  -1.0    0.0  1.141754
543     0  0.531023  0.468977       1  ...  1.041986  -1.0    0.0  1.143383

[5 rows x 10 columns]
2023-06-29 00:00:18,749:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503132  0.496868       1  ...  1.060104  -1.0    0.0  1.131813
46     1  0.499908  0.500092       1  ...  1.046731  -1.0    0.0  1.135346
47     0  0.512928  0.487072       1  ...  1.045292  -1.0    0.0  1.136907
48     0  0.510766  0.489234       1  ...  1.043475  -1.0    0.0  1.139722
49     0  0.531023  0.468977       1  ...  1.041986  -1.0    0.0  1.143383

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.381', 'enterprice': '30103.1', 'countrevence': '0', 'unrealprofit': '-8323.824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30407.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [29/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-29 00:00:04,084:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42483F1687968003478I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687968003857447, 'quantity': '26.572', 'price': '30399.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687968002614, 'updatetime': 1687968003857, 'tradetype': 'usdt', 'selfid': 42483, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687968003857, 'clientorderid': '42483F1687968003478I0L59', 'price': '30399.5', 'quantity': '26.572', 'commission': '807.775514', 'commissionasset': 'USDT', 'tradetime': 1687968003857, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687968003857}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6560 

self.closeSec=1687968599, self.tradeDate='20230629', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30399.8', self.close='30423.5'
2023-06-29 00:10:01,165:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687968599, self.tradeDate='20230629', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30399.8', self.close='30423.5'
2023-06-29 00:10:01,179:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230628   232000    232959  1687966199  30365.9  30356.5 -0.000310
573  20230628   233000    233959  1687966799  30356.6  30412.5  0.001845
574  20230628   234000    234959  1687967399  30412.5  30378.4 -0.001121
575  20230628   235000    235959  1687967999  30378.5  30399.8  0.000704
576  20230629   000000    000959  1687968599  30399.8  30423.5  0.000780
2023-06-29 00:10:01,182:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6561 

self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30423.6', self.close='30372.9'
127.0.0.1 - - [29/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-29 00:20:07,340:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30423.6', self.close='30372.9'
2023-06-29 00:20:08,150:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230628   233000    233959  1687966799  30356.6  30412.5  0.001845
574  20230628   234000    234959  1687967399  30412.5  30378.4 -0.001121
575  20230628   235000    235959  1687967999  30378.5  30399.8  0.000704
576  20230629   000000    000959  1687968599  30399.8  30423.5  0.000780
577  20230629   001000    001959  1687969199  30423.6  30372.9 -0.001663
2023-06-29 00:20:08,151:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-29 00:00:02,096:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-29 00:00:02,179:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6290000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230628, closeTime:235959, close:30399.8, total:992420.1027844, pct_pre:-0.008617529619689757, thd:-0.6206280452882196, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6563 

self.closeSec=1687968599, self.tradeDate='20230629', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30399.8', self.close='30423.5'
2023-06-29 00:10:01,157:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687968599, self.tradeDate='20230629', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30399.8', self.close='30423.5'
127.0.0.1 - - [29/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-29 00:10:01,181:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230628   232000    232959  1687966199  30365.9  30356.5
17421  20230628   233000    233959  1687966799  30356.6  30412.5
17422  20230628   234000    234959  1687967399  30412.5  30378.4
17423  20230628   235000    235959  1687967999  30378.5  30399.8
17424  20230629   000000    000959  1687968599  30399.8  30423.5
2023-06-29 00:10:01,181:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6564 

self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30423.6', self.close='30372.9'
127.0.0.1 - - [29/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-29 00:20:09,122:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30423.6', self.close='30372.9'
2023-06-29 00:20:09,242:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230628   233000    233959  1687966799  30356.6  30412.5
17422  20230628   234000    234959  1687967399  30412.5  30378.4
17423  20230628   235000    235959  1687967999  30378.5  30399.8
17424  20230629   000000    000959  1687968599  30399.8  30423.5
17425  20230629   001000    001959  1687969199  30423.6  30372.9
2023-06-29 00:20:09,242:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [29/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-29 00:00:04,338:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42484F1687968003548I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687968003913442, 'quantity': '37.629', 'price': '30399.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687968002670, 'updatetime': 1687968003913, 'tradetype': 'usdt', 'selfid': 42484, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687968003913, 'clientorderid': '42484F1687968003548I0L2', 'price': '30399.5', 'quantity': '37.629', 'commission': '1143.9027855', 'commissionasset': 'USDT', 'tradetime': 1687968003913, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687968003913}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6563 

self.closeSec=1687968599, self.tradeDate='20230629', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30399.8', self.close='30423.5'
2023-06-29 00:10:01,149:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687968599, self.tradeDate='20230629', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30399.8', self.close='30423.5'
2023-06-29 00:10:01,180:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230628   232000    232959  1687966199  30365.9  30356.5
12237  20230628   233000    233959  1687966799  30356.6  30412.5
12238  20230628   234000    234959  1687967399  30412.5  30378.4
12239  20230628   235000    235959  1687967999  30378.5  30399.8
12240  20230629   000000    000959  1687968599  30399.8  30423.5
2023-06-29 00:10:01,180:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6564 

self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30423.6', self.close='30372.9'
127.0.0.1 - - [29/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-29 00:20:08,683:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30423.6', self.close='30372.9'
2023-06-29 00:20:09,011:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230628   233000    233959  1687966799  30356.6  30412.5
12238  20230628   234000    234959  1687967399  30412.5  30378.4
12239  20230628   235000    235959  1687967999  30378.5  30399.8
12240  20230629   000000    000959  1687968599  30399.8  30423.5
12241  20230629   001000    001959  1687969199  30423.6  30372.9
2023-06-29 00:20:09,012:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13120
self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30422.0, self.close=30372.9, self.high=30433.2, self.low=30348.5, self.vol=2363.312, self.amt=71798433.7135 
127.0.0.1 - - [29/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-29 00:20:07,471:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230628   235500    235959  ...         0.0        0.0       0
5760  20230629   000000    000459  ...         0.0        0.0       0
5761  20230629   000500    000959  ...         0.0        0.0       0
5762  20230629   001000    001459  ...         0.0        0.0       0
5763  20230629   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 00:20:07,491:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687969199, self.tradeDate='20230629', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30422.0, self.close=30372.9, self.high=30433.2, self.low=30348.5, self.vol=2363.312, self.amt=71798433.7135, ukdf['pct'].iloc[-1]=-0.001611 , ukdf['amount'].iloc[-1]=71798433.7135, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '130988.8788', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30370.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [29/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13121
self.closeSec=1687969499, self.tradeDate='20230629', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30373.0, self.close=30386.0, self.high=30403.3, self.low=30368.8, self.vol=719.07, self.amt=21850852.6031 
2023-06-29 00:25:00,806:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230629   000000    000459  ...         0.0        0.0       0
5761  20230629   000500    000959  ...         0.0        0.0       0
5762  20230629   001000    001459  ...         0.0        0.0       0
5763  20230629   001500    001959  ...         0.0        0.0       0
5764  20230629   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 00:25:00,806:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687969499, self.tradeDate='20230629', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30373.0, self.close=30386.0, self.high=30403.3, self.low=30368.8, self.vol=719.07, self.amt=21850852.6031, ukdf['pct'].iloc[-1]=0.000431 , ukdf['amount'].iloc[-1]=21850852.6031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '131578.07274020136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30386.66370696', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230628   120000    155959  1687939199  ...    723  0.254736 -0.770019    -1.0
724  20230628   160000    195959  1687953599  ...    724  0.303718 -0.641460    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '21976.36959144624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30294.43768132', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=273
self.closeSec=1687967999, self.tradeDate='20230628', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30294.4, self.close=30399.8, self.high=30485.0, self.low=29992.5, self.vol=125197.93, self.amt=3784724317.82304 
127.0.0.1 - - [29/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-29 00:00:01,697:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687967999, self.tradeDate='20230628', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30294.4, self.close=30399.8, self.high=30485.0, self.low=29992.5, self.vol=125197.93, self.amt=3784724317.82304 
2023-06-29 00:00:01,722:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230628   040000    075959  ...   42008.165  1.286968e+09  0.001462
722  20230628   080000    115959  ...   52611.526  1.604522e+09 -0.007867
723  20230628   120000    155959  ...   53843.360  1.631942e+09 -0.008699
724  20230628   160000    195959  ...   42990.331  1.301075e+09  0.003887
725  20230628   200000    235959  ...  125197.930  3.784724e+09  0.003483

[5 rows x 11 columns]
2023-06-29 00:00:03,225:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230628   040000    075959  1687910399  ...    721  0.263494 -0.758499    -1.0
722  20230628   080000    115959  1687924799  ...    722  0.244068 -0.802369    -1.0
723  20230628   120000    155959  1687939199  ...    723  0.254736 -0.770019    -1.0
724  20230628   160000    195959  1687953599  ...    724  0.303718 -0.641460    -1.0
725  20230628   200000    235959  1687967999  ...    725  0.322935 -0.594812     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '16358.6028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30399.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


