# 20230413 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39285
self.closeSec=1681316399, self.tradeDate='20230413', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29951.5, self.close=29985.7, self.high=29990.0, self.low=29913.5, self.vol=1663.322, self.amt=49830234.7675 
127.0.0.1 - - [13/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-13 00:20:06,354:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230412   235500    235959  ...         0.0        0.0       0
5753  20230413   000000    000459  ...         0.0        0.0       0
5754  20230413   000500    000959  ...         0.0        0.0       0
5755  20230413   001000    001459  ...         0.0        0.0       0
5756  20230413   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 00:20:06,371:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681316399, self.tradeDate='20230413', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29951.5, self.close=29985.7, self.high=29990.0, self.low=29913.5, self.vol=1663.322, self.amt=49830234.7675, ukdf['pct'].iloc[-1]=0.001142 , ukdf['amount'].iloc[-1]=49830234.7675, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-809920.8192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29988.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39286
self.closeSec=1681316699, self.tradeDate='20230413', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29985.8, self.close=29984.3, self.high=29990.9, self.low=29948.0, self.vol=1469.281, self.amt=44045308.6869 
2023-04-13 00:25:01,589:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230413   000000    000459  ...         0.0        0.0       0
5754  20230413   000500    000959  ...         0.0        0.0       0
5755  20230413   001000    001459  ...         0.0        0.0       0
5756  20230413   001500    001959  ...         0.0        0.0       0
5757  20230413   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 00:25:01,594:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681316699, self.tradeDate='20230413', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29985.8, self.close=29984.3, self.high=29990.9, self.low=29948.0, self.vol=1469.281, self.amt=44045308.6869, ukdf['pct'].iloc[-1]=-4.7e-05 , ukdf['amount'].iloc[-1]=44045308.6869, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-809818.28541529744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29986.79610169', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
739  20230410   133500    133959  1681105199  ...  28220.3  0.000011   1603    1
740  20230410   134000    134459  1681105499  ...  28232.1  0.001654   1604    2
741  20230410   134500    134959  1681105799  ...  28265.5 -0.000453   1605    3
742  20230410   135000    135459  1681106099  ...  28251.1  0.000340   1606    4
743  20230410   135500    135959  1681106399  ...  28268.0 -0.000141   1607    5

[5 rows x 11 columns] 

127.0.0.1 - - [13/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39849 

self.closeSec=1681315799, self.tradeDate='20230413', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29954.5, self.close=29907.7, self.high=29954.6, self.low=29900.0 
127.0.0.1 - - [13/Apr/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39850 

self.closeSec=1681316099, self.tradeDate='20230413', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29907.8, self.close=29951.5, self.high=29970.0, self.low=29907.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39851 

self.closeSec=1681316399, self.tradeDate='20230413', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29951.5, self.close=29985.7, self.high=29990.0, self.low=29913.5 
127.0.0.1 - - [13/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39852 

self.closeSec=1681316699, self.tradeDate='20230413', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29985.8, self.close=29984.3, self.high=29990.9, self.low=29948.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-13 00:00:33,358:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230412    212959  30132.6  ...  51.666667  0.579776  0.675691
5802  20230412    215959  30157.0  ...  51.666667  0.556690  0.677073
5803  20230412    222959  30039.6  ...  51.666667  0.578998  0.664807
5804  20230412    225959  30192.8  ...  51.250000  0.544965  0.669845
5805  20230412    232959  30006.6  ...  51.250000  0.527695  0.669770

[5 rows x 33 columns]
0.5716911764705882
acc is : 0.5716911764705882
2023-04-13 00:00:33,543:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.521791  0.478209       0  ...  1.018146  -1.0    0.0  1.058045
540     1  0.488959  0.511041       1  ...  1.012957  -1.0    0.0  1.063438
541     0  0.548330  0.451670       0  ...  1.019204  -1.0    0.0  1.056879
542     1  0.472377  0.527623       0  ...  1.022655  -1.0    0.0  1.053301
543     1  0.473789  0.526211       1  ...  1.021181  -1.0    0.0  1.054819

[5 rows x 10 columns]
2023-04-13 00:00:33,582:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.521283  0.478717       0  ...  1.018146  -1.0    0.0  1.051844
46     1  0.489045  0.510955       1  ...  1.012957  -1.0    0.0  1.062936
47     0  0.547843  0.452157       0  ...  1.019204  -1.0    0.0  1.053788
48     1  0.471893  0.528107       0  ...  1.022655  -1.0    0.0  1.050220
49     1  0.473789  0.526211       1  ...  1.021181  -1.0    0.0  1.054819

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19921 

self.closeSec=1681313399, self.tradeDate='20230412', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29824.7', self.close='29906.7'
127.0.0.1 - - [12/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19922 

self.closeSec=1681313999, self.tradeDate='20230412', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29906.7', self.close='29887'
127.0.0.1 - - [12/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19923 

self.closeSec=1681314599, self.tradeDate='20230412', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29886.9', self.close='29979.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19924 

self.closeSec=1681315199, self.tradeDate='20230412', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29979.9', self.close='29948'
127.0.0.1 - - [13/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19925 

self.closeSec=1681315799, self.tradeDate='20230413', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29948', self.close='29907.7'
127.0.0.1 - - [13/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19926 

self.closeSec=1681316399, self.tradeDate='20230413', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29907.8', self.close='29985.7'
127.0.0.1 - - [13/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [12/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19922 

self.closeSec=1681313399, self.tradeDate='20230412', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29824.7', self.close='29906.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19923 

self.closeSec=1681313999, self.tradeDate='20230412', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29906.7', self.close='29887'
127.0.0.1 - - [12/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19924 

self.closeSec=1681314599, self.tradeDate='20230412', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29886.9', self.close='29979.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19925 

self.closeSec=1681315199, self.tradeDate='20230412', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29979.9', self.close='29948'
127.0.0.1 - - [13/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19926 

self.closeSec=1681315799, self.tradeDate='20230413', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29948', self.close='29907.7'
127.0.0.1 - - [13/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19927 

self.closeSec=1681316399, self.tradeDate='20230413', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29907.8', self.close='29985.7'
127.0.0.1 - - [13/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [12/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19922 

self.closeSec=1681313399, self.tradeDate='20230412', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29824.7', self.close='29906.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19923 

self.closeSec=1681313999, self.tradeDate='20230412', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29906.7', self.close='29887'
127.0.0.1 - - [12/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19924 

self.closeSec=1681314599, self.tradeDate='20230412', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29886.9', self.close='29979.9'
127.0.0.1 - - [13/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19925 

self.closeSec=1681315199, self.tradeDate='20230412', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29979.9', self.close='29948'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19926 

self.closeSec=1681315799, self.tradeDate='20230413', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29948', self.close='29907.7'
127.0.0.1 - - [13/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19927 

self.closeSec=1681316399, self.tradeDate='20230413', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29907.8', self.close='29985.7'
127.0.0.1 - - [13/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35283
self.closeSec=1681316399, self.tradeDate='20230413', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29951.5, self.close=29985.7, self.high=29990.0, self.low=29913.5, self.vol=1663.322, self.amt=49830234.7675 
127.0.0.1 - - [13/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-04-13 00:20:06,045:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230412   235500    235959  ...         0.0        0.0       0
5753  20230413   000000    000459  ...         0.0        0.0       0
5754  20230413   000500    000959  ...         0.0        0.0       0
5755  20230413   001000    001459  ...         0.0        0.0       0
5756  20230413   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 00:20:06,056:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681316399, self.tradeDate='20230413', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29951.5, self.close=29985.7, self.high=29990.0, self.low=29913.5, self.vol=1663.322, self.amt=49830234.7675, ukdf['pct'].iloc[-1]=0.001142 , ukdf['amount'].iloc[-1]=49830234.7675, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35284
self.closeSec=1681316699, self.tradeDate='20230413', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29985.8, self.close=29984.3, self.high=29990.9, self.low=29948.0, self.vol=1469.281, self.amt=44045308.6869 
127.0.0.1 - - [13/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-13 00:25:01,602:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230413   000000    000459  ...         0.0        0.0       0
5754  20230413   000500    000959  ...         0.0        0.0       0
5755  20230413   001000    001459  ...         0.0        0.0       0
5756  20230413   001500    001959  ...         0.0        0.0       0
5757  20230413   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 00:25:01,603:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681316699, self.tradeDate='20230413', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29985.8, self.close=29984.3, self.high=29990.9, self.low=29948.0, self.vol=1469.281, self.amt=44045308.6869, ukdf['pct'].iloc[-1]=-4.7e-05 , ukdf['amount'].iloc[-1]=44045308.6869, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230412   120000    155959  1681286399  ...    723  1.174109  1.754042     1.0
724  20230412   160000    195959  1681300799  ...    724  1.126781  1.597307     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '91137.65043248685', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30005.35940079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=830
self.closeSec=1681315199, self.tradeDate='20230412', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30003.7, self.close=29948.0, self.high=30480.0, self.low=29620.0, self.vol=266359.4, self.amt=8017304127.29863 
127.0.0.1 - - [13/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-13 00:00:01,980:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681315199, self.tradeDate='20230412', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30003.7, self.close=29948.0, self.high=30480.0, self.low=29620.0, self.vol=266359.4, self.amt=8017304127.29863 
2023-04-13 00:00:02,025:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230412   040000    075959  ...   67110.773  2.021571e+09  0.002098
722  20230412   080000    115959  ...   93503.580  2.808320e+09 -0.008955
723  20230412   120000    155959  ...   47788.578  1.430809e+09  0.002159
724  20230412   160000    195959  ...   37903.678  1.135899e+09  0.000811
725  20230412   200000    235959  ...  266359.400  8.017304e+09 -0.001856

[5 rows x 11 columns]
2023-04-13 00:00:04,286:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230412   040000    075959  1681257599  ...    721  1.211553  1.963309     1.0
722  20230412   080000    115959  1681271999  ...    722  1.214636  1.905647     1.0
723  20230412   120000    155959  1681286399  ...    723  1.174109  1.754042     1.0
724  20230412   160000    195959  1681300799  ...    724  1.126781  1.597307     1.0
725  20230412   200000    235959  1681315199  ...    725  1.148402  1.602193     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '88120.17', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29947.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


