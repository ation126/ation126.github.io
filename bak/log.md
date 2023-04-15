# 20230416 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40149
self.closeSec=1681575599, self.tradeDate='20230416', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30268.0, self.close=30300.1, self.high=30300.7, self.low=30263.0, self.vol=1151.657, self.amt=34879397.473 
127.0.0.1 - - [16/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-16 00:20:07,320:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230415   235500    235959  ...         0.0        0.0       0
5753  20230416   000000    000459  ...         0.0        0.0       0
5754  20230416   000500    000959  ...         0.0        0.0       0
5755  20230416   001000    001459  ...         0.0        0.0       0
5756  20230416   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 00:20:07,335:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681575599, self.tradeDate='20230416', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30268.0, self.close=30300.1, self.high=30300.7, self.low=30263.0, self.vol=1151.657, self.amt=34879397.473, ukdf['pct'].iloc[-1]=0.001061 , ukdf['amount'].iloc[-1]=34879397.473, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-828759.61017288496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30301.56153571', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40150
self.closeSec=1681575899, self.tradeDate='20230416', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30300.0, self.close=30293.1, self.high=30314.9, self.low=30291.0, self.vol=880.909, self.amt=26695620.4899 
2023-04-16 00:25:01,609:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230416   000000    000459  ...         0.0        0.0       0
5754  20230416   000500    000959  ...         0.0        0.0       0
5755  20230416   001000    001459  ...         0.0        0.0       0
5756  20230416   001500    001959  ...         0.0        0.0       0
5757  20230416   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 00:25:01,610:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681575899, self.tradeDate='20230416', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30300.0, self.close=30293.1, self.high=30314.9, self.low=30291.0, self.vol=880.909, self.amt=26695620.4899, ukdf['pct'].iloc[-1]=-0.000231 , ukdf['amount'].iloc[-1]=26695620.4899, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-828423.14848620256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30295.97024206', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1681574699, self.tradeDate='20230416', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=30319.9, self.close=30320.4, self.high=30330.0, self.low=30307.8 

--ukdf-hist--: overDate='20230411' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [16/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40713 

self.closeSec=1681574999, self.tradeDate='20230416', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=30320.5, self.close=30274.0, self.high=30320.5, self.low=30260.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40714 

self.closeSec=1681575299, self.tradeDate='20230416', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=30274.7, self.close=30268.0, self.high=30296.3, self.low=30240.3 
127.0.0.1 - - [16/Apr/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40715 

self.closeSec=1681575599, self.tradeDate='20230416', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30268.0, self.close=30300.1, self.high=30300.7, self.low=30263.0 
127.0.0.1 - - [16/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40716 

self.closeSec=1681575899, self.tradeDate='20230416', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30300.0, self.close=30293.1, self.high=30314.9, self.low=30291.0 
127.0.0.1 - - [16/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-16 00:00:37,495:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230415    212959  30407.4  ...  56.666667  0.509302  0.448858
5802  20230415    215959  30407.7  ...  56.666667  0.489044  0.463284
5803  20230415    222959  30320.4  ...  56.666667  0.498019  0.470641
5804  20230415    225959  30358.9  ...  56.250000  0.496494  0.478554
5805  20230415    232959  30352.3  ...  56.250000  0.505003  0.486940

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-04-16 00:00:37,670:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.518678  0.481322       0  ...  1.016976  -1.0    0.0  1.082107
540     1  0.494498  0.505502       1  ...  1.015684  -1.0    0.0  1.083481
541     0  0.522740  0.477260       0  ...  1.015905  -1.0    0.0  1.083245
542     0  0.513403  0.486597       1  ...  1.014690  -1.0    0.0  1.084541
543     0  0.522162  0.477838       0  ...  1.016981  -1.0    0.0  1.082092

[5 rows x 10 columns]
2023-04-16 00:00:37,700:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519289  0.480711       0  ...  1.038455  -1.0    0.0  1.087728
46     1  0.494674  0.505326       1  ...  1.037136  -1.0    0.0  1.088593
47     0  0.522282  0.477718       0  ...  1.021147  -1.0    0.0  1.081574
48     0  0.513137  0.486863       1  ...  1.036121  -1.0    0.0  1.082867
49     0  0.522162  0.477838       0  ...  1.016981  -1.0    0.0  1.082092

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [15/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20353 

self.closeSec=1681572599, self.tradeDate='20230415', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30391.7', self.close='30388.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20354 

self.closeSec=1681573199, self.tradeDate='20230415', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30388.4', self.close='30404'
127.0.0.1 - - [15/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20355 

self.closeSec=1681573799, self.tradeDate='20230415', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30404', self.close='30356.7'
127.0.0.1 - - [15/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20356 

self.closeSec=1681574399, self.tradeDate='20230415', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30356.7', self.close='30319.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20357 

self.closeSec=1681574999, self.tradeDate='20230416', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30319.9', self.close='30274'
127.0.0.1 - - [16/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20358 

self.closeSec=1681575599, self.tradeDate='20230416', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30274.7', self.close='30300.1'
127.0.0.1 - - [16/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20354 

self.closeSec=1681572599, self.tradeDate='20230415', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30391.7', self.close='30388.5'
127.0.0.1 - - [15/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20355 

self.closeSec=1681573199, self.tradeDate='20230415', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30388.4', self.close='30404'
127.0.0.1 - - [15/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20356 

self.closeSec=1681573799, self.tradeDate='20230415', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30404', self.close='30356.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20357 

self.closeSec=1681574399, self.tradeDate='20230415', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30356.7', self.close='30319.9'
127.0.0.1 - - [16/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20358 

self.closeSec=1681574999, self.tradeDate='20230416', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30319.9', self.close='30274'
127.0.0.1 - - [16/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20359 

self.closeSec=1681575599, self.tradeDate='20230416', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30274.7', self.close='30300.1'
127.0.0.1 - - [16/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20354 

self.closeSec=1681572599, self.tradeDate='20230415', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30391.7', self.close='30388.5'
127.0.0.1 - - [15/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20355 

self.closeSec=1681573199, self.tradeDate='20230415', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30388.4', self.close='30404'
127.0.0.1 - - [15/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20356 

self.closeSec=1681573799, self.tradeDate='20230415', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30404', self.close='30356.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20357 

self.closeSec=1681574399, self.tradeDate='20230415', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30356.7', self.close='30319.9'
127.0.0.1 - - [16/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20358 

self.closeSec=1681574999, self.tradeDate='20230416', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30319.9', self.close='30274'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20359 

self.closeSec=1681575599, self.tradeDate='20230416', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30274.7', self.close='30300.1'
127.0.0.1 - - [16/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36147
self.closeSec=1681575599, self.tradeDate='20230416', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30268.0, self.close=30300.1, self.high=30300.7, self.low=30263.0, self.vol=1151.657, self.amt=34879397.473 
127.0.0.1 - - [16/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-16 00:20:07,100:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230415   235500    235959  ...         0.0        0.0       0
5753  20230416   000000    000459  ...         0.0        0.0       0
5754  20230416   000500    000959  ...         0.0        0.0       0
5755  20230416   001000    001459  ...         0.0        0.0       0
5756  20230416   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 00:20:07,114:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681575599, self.tradeDate='20230416', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30268.0, self.close=30300.1, self.high=30300.7, self.low=30263.0, self.vol=1151.657, self.amt=34879397.473, ukdf['pct'].iloc[-1]=0.001061 , ukdf['amount'].iloc[-1]=34879397.473, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36148
self.closeSec=1681575899, self.tradeDate='20230416', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30300.0, self.close=30293.1, self.high=30314.9, self.low=30291.0, self.vol=880.909, self.amt=26695620.4899 
2023-04-16 00:25:01,636:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230416   000000    000459  ...         0.0        0.0       0
5754  20230416   000500    000959  ...         0.0        0.0       0
5755  20230416   001000    001459  ...         0.0        0.0       0
5756  20230416   001500    001959  ...         0.0        0.0       0
5757  20230416   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 00:25:01,636:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681575899, self.tradeDate='20230416', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30300.0, self.close=30293.1, self.high=30314.9, self.low=30291.0, self.vol=880.909, self.amt=26695620.4899, ukdf['pct'].iloc[-1]=-0.000231 , ukdf['amount'].iloc[-1]=26695620.4899, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230415   120000    155959  1681545599  ...    723  0.409521 -0.207092     NaN
724  20230415   160000    195959  1681559999  ...    724  0.356162 -0.316022     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '110339.2665', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30371', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=848
self.closeSec=1681574399, self.tradeDate='20230415', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30370.9, self.close=30319.9, self.high=30432.1, self.low=30270.7, self.vol=32820.069, self.amt=996381116.6452 
127.0.0.1 - - [16/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-16 00:00:01,949:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681574399, self.tradeDate='20230415', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30370.9, self.close=30319.9, self.high=30432.1, self.low=30270.7, self.vol=32820.069, self.amt=996381116.6452 
2023-04-16 00:00:02,000:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230415   040000    075959  ...  48626.219  1.479058e+09  0.004681
722  20230415   080000    115959  ...  41220.216  1.253534e+09 -0.002824
723  20230415   120000    155959  ...  20229.732  6.146483e+08  0.001630
724  20230415   160000    195959  ...  24960.612  7.588878e+08 -0.001499
725  20230415   200000    235959  ...  32820.069  9.963811e+08 -0.001683

[5 rows x 11 columns]
2023-04-16 00:00:04,732:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230415   040000    075959  1681516799  ...    721  0.279484 -0.500986     NaN
722  20230415   080000    115959  1681531199  ...    722  0.291453 -0.467049     NaN
723  20230415   120000    155959  1681545599  ...    723  0.409521 -0.207092     NaN
724  20230415   160000    195959  1681559999  ...    724  0.356162 -0.316022     NaN
725  20230415   200000    235959  1681574399  ...    725  0.323811 -0.377998     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '107650.4985', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30319.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


