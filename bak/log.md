# 20230418 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40725
self.closeSec=1681748399, self.tradeDate='20230418', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29380.1, self.close=29375.1, self.high=29387.4, self.low=29365.4, self.vol=2046.608, self.amt=60120401.6093 
127.0.0.1 - - [18/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-18 00:20:07,380:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230417   235500    235959  ...         0.0        0.0       0
5753  20230418   000000    000459  ...         0.0        0.0       0
5754  20230418   000500    000959  ...         0.0        0.0       0
5755  20230418   001000    001459  ...         0.0        0.0       0
5756  20230418   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 00:20:07,392:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681748399, self.tradeDate='20230418', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29380.1, self.close=29375.1, self.high=29387.4, self.low=29365.4, self.vol=2046.608, self.amt=60120401.6093, ukdf['pct'].iloc[-1]=-0.000167 , ukdf['amount'].iloc[-1]=60120401.6093, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-772978.7728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29374.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40726
self.closeSec=1681748699, self.tradeDate='20230418', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29375.0, self.close=29329.0, self.high=29388.2, self.low=29316.3, self.vol=2028.458, self.amt=59546277.1512 
2023-04-18 00:25:01,622:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230418   000000    000459  ...         0.0        0.0       0
5754  20230418   000500    000959  ...         0.0        0.0       0
5755  20230418   001000    001459  ...         0.0        0.0       0
5756  20230418   001500    001959  ...         0.0        0.0       0
5757  20230418   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 00:25:01,623:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681748699, self.tradeDate='20230418', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29375.0, self.close=29329.0, self.high=29388.2, self.low=29316.3, self.vol=2028.458, self.amt=59546277.1512, ukdf['pct'].iloc[-1]=-0.001569 , ukdf['amount'].iloc[-1]=59546277.1512, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-770262.02415759232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29329.45328632', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [18/Apr/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230413' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [18/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41289 

self.closeSec=1681747799, self.tradeDate='20230418', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29360.4, self.close=29365.6, self.high=29375.0, self.low=29346.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41290 

self.closeSec=1681748099, self.tradeDate='20230418', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29365.5, self.close=29380.0, self.high=29387.9, self.low=29364.9 
127.0.0.1 - - [18/Apr/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41291 

self.closeSec=1681748399, self.tradeDate='20230418', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29380.1, self.close=29375.1, self.high=29387.4, self.low=29365.4 
127.0.0.1 - - [18/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41292 

self.closeSec=1681748699, self.tradeDate='20230418', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29375.0, self.close=29329.0, self.high=29388.2, self.low=29316.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-18 00:00:34,019:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230417    212959  29520.0  ...  52.500000  0.337159  0.754510
5802  20230417    215959  29354.4  ...  52.916667  0.346002  0.762845
5803  20230417    222959  29391.0  ...  52.916667  0.358720  0.768337
5804  20230417    225959  29436.8  ...  52.916667  0.356919  0.774044
5805  20230417    232959  29425.1  ...  52.916667  0.348436  0.782081

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-04-18 00:00:34,168:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.456649  0.543351       1  ...  1.043698  -1.0    0.0  1.048858
540     0  0.506233  0.493767       1  ...  1.042079  -1.0    0.0  1.050485
541     0  0.525947  0.474053       0  ...  1.042490  -1.0    0.0  1.050071
542     0  0.517238  0.482762       0  ...  1.044442  -1.0    0.0  1.048105
543     0  0.504207  0.495793       0  ...  1.045277  -1.0    0.0  1.047266

[5 rows x 10 columns]
2023-04-18 00:00:34,199:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.457289  0.542711       1  ...  1.043698  -1.0    0.0  1.048824
46     0  0.506239  0.493761       1  ...  1.042079  -1.0    0.0  1.050384
47     0  0.525510  0.474490       0  ...  1.042490  -1.0    0.0  1.048892
48     0  0.516384  0.483616       0  ...  1.044442  -1.0    0.0  1.046928
49     0  0.504207  0.495793       0  ...  1.045277  -1.0    0.0  1.047266

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [17/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20641 

self.closeSec=1681745399, self.tradeDate='20230417', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29394', self.close='29370'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20642 

self.closeSec=1681745999, self.tradeDate='20230417', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29370.1', self.close='29288.3'
127.0.0.1 - - [17/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20643 

self.closeSec=1681746599, self.tradeDate='20230417', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29288.3', self.close='29351.6'
127.0.0.1 - - [17/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20644 

self.closeSec=1681747199, self.tradeDate='20230417', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29351.6', self.close='29346.5'
127.0.0.1 - - [18/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20645 

self.closeSec=1681747799, self.tradeDate='20230418', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29346.5', self.close='29365.6'
127.0.0.1 - - [18/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20646 

self.closeSec=1681748399, self.tradeDate='20230418', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29365.5', self.close='29375.1'
127.0.0.1 - - [18/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [17/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20642 

self.closeSec=1681745399, self.tradeDate='20230417', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29394', self.close='29370'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20643 

self.closeSec=1681745999, self.tradeDate='20230417', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29370.1', self.close='29288.3'
127.0.0.1 - - [17/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20644 

self.closeSec=1681746599, self.tradeDate='20230417', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29288.3', self.close='29351.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20645 

self.closeSec=1681747199, self.tradeDate='20230417', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29351.6', self.close='29346.5'
127.0.0.1 - - [18/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20646 

self.closeSec=1681747799, self.tradeDate='20230418', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29346.5', self.close='29365.6'
127.0.0.1 - - [18/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20647 

self.closeSec=1681748399, self.tradeDate='20230418', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29365.5', self.close='29375.1'
127.0.0.1 - - [18/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20642 

self.closeSec=1681745399, self.tradeDate='20230417', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29394', self.close='29370'
127.0.0.1 - - [17/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20643 

self.closeSec=1681745999, self.tradeDate='20230417', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29370.1', self.close='29288.3'
127.0.0.1 - - [17/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20644 

self.closeSec=1681746599, self.tradeDate='20230417', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29288.3', self.close='29351.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20645 

self.closeSec=1681747199, self.tradeDate='20230417', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29351.6', self.close='29346.5'
127.0.0.1 - - [18/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20646 

self.closeSec=1681747799, self.tradeDate='20230418', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29346.5', self.close='29365.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20647 

self.closeSec=1681748399, self.tradeDate='20230418', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29365.5', self.close='29375.1'
127.0.0.1 - - [18/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36723
self.closeSec=1681748399, self.tradeDate='20230418', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29380.1, self.close=29375.1, self.high=29387.4, self.low=29365.4, self.vol=2046.608, self.amt=60120401.6093 
127.0.0.1 - - [18/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-18 00:20:07,230:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230417   235500    235959  ...         0.0        0.0       0
5753  20230418   000000    000459  ...         0.0        0.0       0
5754  20230418   000500    000959  ...         0.0        0.0       0
5755  20230418   001000    001459  ...         0.0        0.0       0
5756  20230418   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 00:20:07,241:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681748399, self.tradeDate='20230418', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29380.1, self.close=29375.1, self.high=29387.4, self.low=29365.4, self.vol=2046.608, self.amt=60120401.6093, ukdf['pct'].iloc[-1]=-0.000167 , ukdf['amount'].iloc[-1]=60120401.6093, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36724
self.closeSec=1681748699, self.tradeDate='20230418', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29375.0, self.close=29329.0, self.high=29388.2, self.low=29316.3, self.vol=2028.458, self.amt=59546277.1512 
127.0.0.1 - - [18/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-18 00:25:01,616:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230418   000000    000459  ...         0.0        0.0       0
5754  20230418   000500    000959  ...         0.0        0.0       0
5755  20230418   001000    001459  ...         0.0        0.0       0
5756  20230418   001500    001959  ...         0.0        0.0       0
5757  20230418   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 00:25:01,617:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681748699, self.tradeDate='20230418', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29375.0, self.close=29329.0, self.high=29388.2, self.low=29316.3, self.vol=2028.458, self.amt=59546277.1512, ukdf['pct'].iloc[-1]=-0.001569 , ukdf['amount'].iloc[-1]=59546277.1512, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230417   120000    155959  1681718399  ...    723  0.309766 -0.351132     NaN
724  20230417   160000    195959  1681732799  ...    724  0.278616 -0.425114     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '67007.5672429692', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29545.87005128', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=860
self.closeSec=1681747199, self.tradeDate='20230417', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29558.1, self.close=29346.5, self.high=29589.4, self.low=29219.9, self.vol=131855.384, self.amt=3877899172.91268 
127.0.0.1 - - [18/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-18 00:00:01,798:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681747199, self.tradeDate='20230417', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29558.1, self.close=29346.5, self.high=29589.4, self.low=29219.9, self.vol=131855.384, self.amt=3877899172.91268 
2023-04-18 00:00:01,861:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230417   040000    075959  ...   41632.548  1.261525e+09 -0.000640
722  20230417   080000    115959  ...  111581.657  3.342124e+09 -0.010569
723  20230417   120000    155959  ...   33276.831  9.956101e+08 -0.004518
724  20230417   160000    195959  ...   93915.835  2.787477e+09 -0.009152
725  20230417   200000    235959  ...  131855.384  3.877899e+09 -0.007159

[5 rows x 11 columns]
2023-04-18 00:00:04,208:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230417   040000    075959  1681689599  ...    721  0.410187 -0.127665     NaN
722  20230417   080000    115959  1681703999  ...    722  0.218240 -0.543022     NaN
723  20230417   120000    155959  1681718399  ...    723  0.309766 -0.351132     NaN
724  20230417   160000    195959  1681732799  ...    724  0.278616 -0.425114     NaN
725  20230417   200000    235959  1681747199  ...    725  0.416468 -0.132860     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '56542.9005', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29346.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


