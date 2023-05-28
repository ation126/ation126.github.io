# 20230529 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4192
self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27302.5, self.close=27226.7, self.high=27327.7, self.low=27213.9, self.vol=4176.306, self.amt=113902487.0742 
127.0.0.1 - - [29/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-29 00:20:06,146:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230528   235500    235959  ...         0.0        0.0       0
5760  20230529   000000    000459  ...         0.0        0.0       0
5761  20230529   000500    000959  ...         0.0        0.0       0
5762  20230529   001000    001459  ...         0.0        0.0       0
5763  20230529   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 00:20:06,156:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27302.5, self.close=27226.7, self.high=27327.7, self.low=27213.9, self.vol=4176.306, self.amt=113902487.0742, ukdf['pct'].iloc[-1]=-0.00278 , ukdf['amount'].iloc[-1]=113902487.0742, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5027.286', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27225.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4193
self.closeSec=1685291099, self.tradeDate='20230529', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27226.7, self.close=27243.5, self.high=27255.7, self.low=27211.8, self.vol=1973.945, self.amt=53762392.5198 
127.0.0.1 - - [29/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-29 00:25:00,849:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230529   000000    000459  ...         0.0        0.0       0
5761  20230529   000500    000959  ...         0.0        0.0       0
5762  20230529   001000    001459  ...         0.0        0.0       0
5763  20230529   001500    001959  ...         0.0        0.0       0
5764  20230529   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 00:25:00,851:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685291099, self.tradeDate='20230529', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27226.7, self.close=27243.5, self.high=27255.7, self.low=27211.8, self.vol=1973.945, self.amt=53762392.5198, ukdf['pct'].iloc[-1]=0.000617 , ukdf['amount'].iloc[-1]=53762392.5198, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5272.3836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27243.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27302.5, self.close=27226.7, self.high=27327.7, self.low=27213.9 
127.0.0.1 - - [29/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-29 00:20:03,907:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27302.5, self.close=27226.7, self.high=27327.7, self.low=27213.9   
2023-05-29 00:20:05,086:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230528   235500    235959  1685289599  ...  27242.0  0.000573   1727    5
1440  20230529   000000    000459  1685289899  ...  27243.8 -0.000458   1440    0
1441  20230529   000500    000959  1685290199  ...  27243.7  0.000594   1441    1
1442  20230529   001000    001459  1685290499  ...  27257.5  0.001276   1442    2
1443  20230529   001500    001959  1685290799  ...  27213.9 -0.002780   1443    3

[5 rows x 11 columns]
2023-05-29 00:20:05,087:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=99, self.factor=0.1807139499731981, self.count=4195 

self.closeSec=1685291099, self.tradeDate='20230529', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27226.7, self.close=27243.5, self.high=27255.7, self.low=27211.8 
2023-05-29 00:25:00,729:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685291099, self.tradeDate='20230529', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27226.7, self.close=27243.5, self.high=27255.7, self.low=27211.8   
2023-05-29 00:25:00,797:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230529   000000    000459  1685289899  ...  27243.8 -0.000458   1440    0
1441  20230529   000500    000959  1685290199  ...  27243.7  0.000594   1441    1
1442  20230529   001000    001459  1685290499  ...  27257.5  0.001276   1442    2
1443  20230529   001500    001959  1685290799  ...  27213.9 -0.002780   1443    3
1444  20230529   002000    002459  1685291099  ...  27211.8  0.000617   1444    4

[5 rows x 11 columns]
2023-05-29 00:25:00,798:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-29 00:00:35,047:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230528    212959  27132.8  ...  47.916667  0.605251  0.214070
5803  20230528    215959  27182.4  ...  47.916667  0.601629  0.220157
5804  20230528    222959  27173.2  ...  47.916667  0.602605  0.225487
5805  20230528    225959  27176.9  ...  47.916667  0.602953  0.230411
5806  20230528    232959  27178.2  ...  47.916667  0.611988  0.232399

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-05-29 00:00:35,220:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.496337  0.503663       0  ...  0.922472   1.0    0.0  1.012720
540     1  0.486106  0.513894       1  ...  0.922597   1.0    0.0  1.012858
541     1  0.492922  0.507078       1  ...  0.922641   1.0    0.0  1.012906
542     1  0.491202  0.508798       1  ...  0.923789   1.0    0.0  1.014166
543     0  0.501461  0.498539       1  ...  0.925557   1.0    0.0  1.016108

[5 rows x 10 columns]
2023-05-29 00:00:35,259:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496344  0.503656       0  ...  0.922472   1.0    0.0  1.008469
46     1  0.485896  0.514104       1  ...  0.922597   1.0    0.0  1.007078
47     1  0.492914  0.507086       1  ...  0.922641   1.0    0.0  1.007126
48     1  0.491101  0.508899       1  ...  0.923789   1.0    0.0  1.008547
49     0  0.501461  0.498539       1  ...  0.925557   1.0    0.0  1.016108

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.918', 'enterprice': '26792.4', 'countrevence': '0', 'unrealprofit': '12162.85910392828', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27261.68231746', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [29/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-29 00:00:04,542:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42279F1685289603842I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685289604219440, 'quantity': '25.346', 'price': '27265.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685289602897, 'updatetime': 1685289604219, 'tradetype': 'usdt', 'selfid': 42279, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685289604219, 'clientorderid': '42279F1685289603842I0L59', 'price': '27265.5', 'quantity': '25.346', 'commission': '691.071363', 'commissionasset': 'USDT', 'tradetime': 1685289604219, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685289604219}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2096 

self.closeSec=1685290199, self.tradeDate='20230529', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27264.1', self.close='27267.8'
2023-05-29 00:10:01,157:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685290199, self.tradeDate='20230529', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27264.1', self.close='27267.8'
2023-05-29 00:10:01,203:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230528   232000    232959  1685287799  27242.6    27212 -0.001120
573  20230528   233000    233959  1685288399    27212  27242.8  0.001132
574  20230528   234000    234959  1685288999  27242.9  27240.6 -0.000081
575  20230528   235000    235959  1685289599  27240.7  27264.1  0.000863
576  20230529   000000    000959  1685290199  27264.1  27267.8  0.000136
2023-05-29 00:10:01,204:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2097 

self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27267.9', self.close='27226.7'
127.0.0.1 - - [29/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-29 00:20:06,188:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27267.9', self.close='27226.7'
2023-05-29 00:20:06,797:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230528   233000    233959  1685288399    27212  27242.8  0.001132
574  20230528   234000    234959  1685288999  27242.9  27240.6 -0.000081
575  20230528   235000    235959  1685289599  27240.7  27264.1  0.000863
576  20230529   000000    000959  1685290199  27264.1  27267.8  0.000136
577  20230529   001000    001959  1685290799  27267.9  27226.7 -0.001507
2023-05-29 00:20:06,797:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-29 00:00:02,324:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-29 00:00:02,399:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5290000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230528, closeTime:235959, close:27264.1, total:983849.5331272, pct_pre:0.01753347026281471, thd:-0.9042483905442624, side:sell 
127.0.0.1 - - [29/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2099 

self.closeSec=1685290199, self.tradeDate='20230529', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27264.1', self.close='27267.8'
2023-05-29 00:10:01,160:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685290199, self.tradeDate='20230529', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27264.1', self.close='27267.8'
2023-05-29 00:10:01,206:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230528   232000    232959  1685287799  27242.6    27212
17421  20230528   233000    233959  1685288399    27212  27242.8
17422  20230528   234000    234959  1685288999  27242.9  27240.6
17423  20230528   235000    235959  1685289599  27240.7  27264.1
17424  20230529   000000    000959  1685290199  27264.1  27267.8
2023-05-29 00:10:01,207:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2100 

self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27267.9', self.close='27226.7'
127.0.0.1 - - [29/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-29 00:20:07,591:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27267.9', self.close='27226.7'
2023-05-29 00:20:07,686:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230528   233000    233959  1685288399    27212  27242.8
17422  20230528   234000    234959  1685288999  27242.9  27240.6
17423  20230528   235000    235959  1685289599  27240.7  27264.1
17424  20230529   000000    000959  1685290199  27264.1  27267.8
17425  20230529   001000    001959  1685290799  27267.9  27226.7
2023-05-29 00:20:07,686:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [29/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-29 00:00:04,336:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42278F1685289603800I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685289604156567, 'quantity': '46.275', 'price': '27265.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685289602954, 'updatetime': 1685289604156, 'tradetype': 'usdt', 'selfid': 42278, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685289604156, 'clientorderid': '42278F1685289603800I0L2', 'price': '27265.5', 'quantity': '46.275', 'commission': '1261.7110125', 'commissionasset': 'USDT', 'tradetime': 1685289604156, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685289604156}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2099 

self.closeSec=1685290199, self.tradeDate='20230529', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27264.1', self.close='27267.8'
127.0.0.1 - - [29/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-29 00:10:01,123:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685290199, self.tradeDate='20230529', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27264.1', self.close='27267.8'
2023-05-29 00:10:01,173:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230528   232000    232959  1685287799  27242.6    27212
12237  20230528   233000    233959  1685288399    27212  27242.8
12238  20230528   234000    234959  1685288999  27242.9  27240.6
12239  20230528   235000    235959  1685289599  27240.7  27264.1
12240  20230529   000000    000959  1685290199  27264.1  27267.8
2023-05-29 00:10:01,173:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2100 

self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27267.9', self.close='27226.7'
127.0.0.1 - - [29/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-29 00:20:07,308:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27267.9', self.close='27226.7'
2023-05-29 00:20:07,529:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230528   233000    233959  1685288399    27212  27242.8
12238  20230528   234000    234959  1685288999  27242.9  27240.6
12239  20230528   235000    235959  1685289599  27240.7  27264.1
12240  20230529   000000    000959  1685290199  27264.1  27267.8
12241  20230529   001000    001959  1685290799  27267.9  27226.7
2023-05-29 00:20:07,530:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4192
self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27302.5, self.close=27226.7, self.high=27327.7, self.low=27213.9, self.vol=4176.306, self.amt=113902487.0742 
127.0.0.1 - - [29/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-29 00:20:06,087:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230528   235500    235959  ...         0.0        0.0       0
5760  20230529   000000    000459  ...         0.0        0.0       0
5761  20230529   000500    000959  ...         0.0        0.0       0
5762  20230529   001000    001459  ...         0.0        0.0       0
5763  20230529   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 00:20:06,118:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685290799, self.tradeDate='20230529', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27302.5, self.close=27226.7, self.high=27327.7, self.low=27213.9, self.vol=4176.306, self.amt=113902487.0742, ukdf['pct'].iloc[-1]=-0.00278 , ukdf['amount'].iloc[-1]=113902487.0742, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '14184.1479', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27225.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [29/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4193
self.closeSec=1685291099, self.tradeDate='20230529', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27226.7, self.close=27243.5, self.high=27255.7, self.low=27211.8, self.vol=1973.945, self.amt=53762392.5198 
2023-05-29 00:25:00,828:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230529   000000    000459  ...         0.0        0.0       0
5761  20230529   000500    000959  ...         0.0        0.0       0
5762  20230529   001000    001459  ...         0.0        0.0       0
5763  20230529   001500    001959  ...         0.0        0.0       0
5764  20230529   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 00:25:00,831:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685291099, self.tradeDate='20230529', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27226.7, self.close=27243.5, self.high=27255.7, self.low=27211.8, self.vol=1973.945, self.amt=53762392.5198, ukdf['pct'].iloc[-1]=0.000617 , ukdf['amount'].iloc[-1]=53762392.5198, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '14837.8295', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27243.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230528   120000    155959  1685260799  ...    723  0.365024 -0.185390     NaN
724  20230528   160000    195959  1685275199  ...    724  0.452764  0.315743     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '56608.1254', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27152.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=87
self.closeSec=1685289599, self.tradeDate='20230528', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27145.9, self.close=27264.1, self.high=27266.0, self.low=27081.7, self.vol=37541.126, self.amt=1020329076.8737 
127.0.0.1 - - [29/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-05-29 00:00:01,784:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685289599, self.tradeDate='20230528', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27145.9, self.close=27264.1, self.high=27266.0, self.low=27081.7, self.vol=37541.126, self.amt=1020329076.8737 
2023-05-29 00:00:01,830:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230528   040000    075959  ...  21946.952  5.879028e+08  0.004491
722  20230528   080000    115959  ...  89784.520  2.429619e+09  0.012399
723  20230528   120000    155959  ...  40838.873  1.110311e+09  0.001638
724  20230528   160000    195959  ...  42170.252  1.147435e+09 -0.002678
725  20230528   200000    235959  ...  37541.126  1.020329e+09  0.004351

[5 rows x 11 columns]
2023-05-29 00:00:04,063:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230528   040000    075959  1685231999  ...    721  0.320607 -0.451685     NaN
722  20230528   080000    115959  1685246399  ...    722  0.324389 -0.422521     NaN
723  20230528   120000    155959  1685260799  ...    723  0.365024 -0.185390     NaN
724  20230528   160000    195959  1685275199  ...    724  0.452764  0.315743     NaN
725  20230528   200000    235959  1685289599  ...    725  0.490371  0.530561     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '62740.7644', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27263.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


