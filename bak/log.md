# 20230903 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32116
self.closeSec=1693671599, self.tradeDate='20230903', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25922.5, self.close=25897.2, self.high=25926.5, self.low=25897.2, self.vol=703.898, self.amt=18237636.0499 
127.0.0.1 - - [03/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-03 00:20:05,272:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230902   235500    235959  ...         0.0        0.0       0
5748  20230903   000000    000459  ...         0.0        0.0       0
5749  20230903   000500    000959  ...         0.0        0.0       0
5750  20230903   001000    001459  ...         0.0        0.0       0
5751  20230903   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 00:20:05,280:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693671599, self.tradeDate='20230903', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25922.5, self.close=25897.2, self.high=25926.5, self.low=25897.2, self.vol=703.898, self.amt=18237636.0499, ukdf['pct'].iloc[-1]=-0.000976 , ukdf['amount'].iloc[-1]=18237636.0499, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13454.04177865506', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25898.79043669', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32117
self.closeSec=1693671899, self.tradeDate='20230903', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25897.2, self.close=25889.1, self.high=25904.8, self.low=25889.0, self.vol=205.652, self.amt=5326095.167 
2023-09-03 00:25:00,795:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230903   000000    000459  ...         0.0        0.0       0
5749  20230903   000500    000959  ...         0.0        0.0       0
5750  20230903   001000    001459  ...         0.0        0.0       0
5751  20230903   001500    001959  ...         0.0        0.0       0
5752  20230903   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 00:25:00,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693671899, self.tradeDate='20230903', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25897.2, self.close=25889.1, self.high=25904.8, self.low=25889.0, self.vol=205.652, self.amt=5326095.167, ukdf['pct'].iloc[-1]=-0.000313 , ukdf['amount'].iloc[-1]=5326095.167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13552.02734587878', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25891.75427647', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [03/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230829' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [03/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32116 

self.closeSec=1693670999, self.tradeDate='20230903', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25892.3, self.close=25912.7, self.high=25914.9, self.low=25892.3 
127.0.0.1 - - [03/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32117 

self.closeSec=1693671299, self.tradeDate='20230903', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25912.7, self.close=25922.5, self.high=25926.0, self.low=25912.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32118 

self.closeSec=1693671599, self.tradeDate='20230903', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25922.5, self.close=25897.2, self.high=25926.5, self.low=25897.2 
127.0.0.1 - - [03/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32119 

self.closeSec=1693671899, self.tradeDate='20230903', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25897.2, self.close=25889.1, self.high=25904.8, self.low=25889.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-03 00:00:17,823:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230902    212959  25798.3  ...  45.833333  0.436551  0.367001
5802  20230902    215959  25800.0  ...  46.250000  0.440762  0.358134
5803  20230902    222959  25814.5  ...  45.833333  0.436879  0.352207
5804  20230902    225959  25795.3  ...  45.833333  0.452177  0.342807
5805  20230902    232959  25850.1  ...  45.833333  0.475523  0.321776

[5 rows x 33 columns]
0.5128676470588235
acc is : 0.5128676470588235
2023-09-03 00:00:17,889:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494801  0.505199       1  ...  1.005577  -1.0    0.0  0.989380
540     1  0.499464  0.500536       0  ...  1.006235  -1.0    0.0  0.988732
541     1  0.491001  0.508999       1  ...  1.004187  -1.0    0.0  0.990744
542     0  0.513837  0.486163       1  ...  1.000912  -1.0    0.0  0.993975
543     0  0.531146  0.468854       0  ...  1.003012  -1.0    0.0  0.991890

[5 rows x 10 columns]
2023-09-03 00:00:17,901:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496519  0.503481       1  ...  1.005577  -1.0    0.0  0.991165
46     0  0.500115  0.499885       0  ...  1.006235  -1.0    0.0  0.990007
47     1  0.491329  0.508671       1  ...  1.004187  -1.0    0.0  0.991622
48     0  0.514169  0.485831       1  ...  1.000912  -1.0    0.0  0.994856
49     0  0.531146  0.468854       0  ...  1.003012  -1.0    0.0  0.991890

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '20963.1266', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25884.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16055 

self.closeSec=1693668599, self.tradeDate='20230902', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25931.2', self.close='25934.4'
127.0.0.1 - - [02/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16056 

self.closeSec=1693669199, self.tradeDate='20230902', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25934.4', self.close='25935.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16057 

self.closeSec=1693669799, self.tradeDate='20230902', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25935.4', self.close='25890'
127.0.0.1 - - [02/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16058 

self.closeSec=1693670399, self.tradeDate='20230902', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25890', self.close='25880'
127.0.0.1 - - [03/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16059 

self.closeSec=1693670999, self.tradeDate='20230903', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25880.1', self.close='25912.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16060 

self.closeSec=1693671599, self.tradeDate='20230903', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25912.7', self.close='25897.3'
127.0.0.1 - - [03/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [02/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16058 

self.closeSec=1693668599, self.tradeDate='20230902', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25931.2', self.close='25934.4'

--handleKline--: 127.0.0.1 - - [02/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16059 

self.closeSec=1693669199, self.tradeDate='20230902', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25934.4', self.close='25935.4'
127.0.0.1 - - [02/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16060 

self.closeSec=1693669799, self.tradeDate='20230902', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25935.4', self.close='25890'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16061 

self.closeSec=1693670399, self.tradeDate='20230902', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25890', self.close='25880'
127.0.0.1 - - [03/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16062 

self.closeSec=1693670999, self.tradeDate='20230903', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25880.1', self.close='25912.7'
127.0.0.1 - - [03/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16063 

self.closeSec=1693671599, self.tradeDate='20230903', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25912.7', self.close='25897.3'
127.0.0.1 - - [03/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16058 

self.closeSec=1693668599, self.tradeDate='20230902', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25931.2', self.close='25934.4'
127.0.0.1 - - [02/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16059 

self.closeSec=1693669199, self.tradeDate='20230902', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25934.4', self.close='25935.4'
127.0.0.1 - - [02/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16060 

self.closeSec=1693669799, self.tradeDate='20230902', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25935.4', self.close='25890'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16061 

self.closeSec=1693670399, self.tradeDate='20230902', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25890', self.close='25880'
127.0.0.1 - - [03/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16062 

self.closeSec=1693670999, self.tradeDate='20230903', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25880.1', self.close='25912.7'
127.0.0.1 - - [03/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16063 

self.closeSec=1693671599, self.tradeDate='20230903', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25912.7', self.close='25897.3'
127.0.0.1 - - [03/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32116
self.closeSec=1693671599, self.tradeDate='20230903', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25922.5, self.close=25897.2, self.high=25926.5, self.low=25897.2, self.vol=703.898, self.amt=18237636.0499 
127.0.0.1 - - [03/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-03 00:20:05,267:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230902   235500    235959  ...         0.0        0.0       0
5748  20230903   000000    000459  ...         0.0        0.0       0
5749  20230903   000500    000959  ...         0.0        0.0       0
5750  20230903   001000    001459  ...         0.0        0.0       0
5751  20230903   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 00:20:05,270:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693671599, self.tradeDate='20230903', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25922.5, self.close=25897.2, self.high=25926.5, self.low=25897.2, self.vol=703.898, self.amt=18237636.0499, ukdf['pct'].iloc[-1]=-0.000976 , ukdf['amount'].iloc[-1]=18237636.0499, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35106.02839089671', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25898.79043669', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32117
self.closeSec=1693671899, self.tradeDate='20230903', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25897.2, self.close=25889.1, self.high=25904.8, self.low=25889.0, self.vol=205.652, self.amt=5326095.167 
2023-09-03 00:25:00,796:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230903   000000    000459  ...         0.0        0.0       0
5749  20230903   000500    000959  ...         0.0        0.0       0
5750  20230903   001000    001459  ...         0.0        0.0       0
5751  20230903   001500    001959  ...         0.0        0.0       0
5752  20230903   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 00:25:00,796:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693671899, self.tradeDate='20230903', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25897.2, self.close=25889.1, self.high=25904.8, self.low=25889.0, self.vol=205.652, self.amt=5326095.167, ukdf['pct'].iloc[-1]=-0.000313 , ukdf['amount'].iloc[-1]=5326095.167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35367.35841762773', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25891.75427647', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230902   120000    155959  1693641599  ...    723  0.654133  0.889894     1.0
724  20230902   160000    195959  1693655999  ...    724  0.668007  0.916750     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-116379.98054984652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25801.03292549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [03/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=669
self.closeSec=1693670399, self.tradeDate='20230902', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25800.1, self.close=25880.0, self.high=25975.0, self.low=25771.1, self.vol=31794.939, self.amt=822647088.522 
2023-09-03 00:00:01,614:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693670399, self.tradeDate='20230902', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25800.1, self.close=25880.0, self.high=25975.0, self.low=25771.1, self.vol=31794.939, self.amt=822647088.522 
2023-09-03 00:00:01,631:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230902   040000    075959  ...  37989.932  9.790657e+08  0.006182
722  20230902   080000    115959  ...  12086.818  3.116060e+08 -0.000368
723  20230902   120000    155959  ...  13773.944  3.552750e+08 -0.000085
724  20230902   160000    195959  ...  18478.625  4.768100e+08  0.000628
725  20230902   200000    235959  ...  31794.939  8.226471e+08  0.003097

[5 rows x 11 columns]
2023-09-03 00:00:02,349:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230902   040000    075959  1693612799  ...    721  0.614138  0.799056     1.0
722  20230902   080000    115959  1693627199  ...    722  0.633890  0.843596     1.0
723  20230902   120000    155959  1693641599  ...    723  0.654133  0.889894     1.0
724  20230902   160000    195959  1693655999  ...    724  0.668007  0.916750     1.0
725  20230902   200000    235959  1693670399  ...    725  0.671203  0.911753     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-111663.98838385128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25883.40545686', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


