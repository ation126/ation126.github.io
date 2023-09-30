# 20231001 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40180
self.closeSec=1696090799, self.tradeDate='20231001', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26999.0, self.close=26968.5, self.high=26999.0, self.low=26968.4, self.vol=462.678, self.amt=12484555.5245 
127.0.0.1 - - [01/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-10-01 00:20:06,532:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230930   235500    235959  ...         0.0        0.0       0
5760  20231001   000000    000459  ...         0.0        0.0       0
5761  20231001   000500    000959  ...         0.0        0.0       0
5762  20231001   001000    001459  ...         0.0        0.0       0
5763  20231001   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 00:20:06,548:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696090799, self.tradeDate='20231001', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26999.0, self.close=26968.5, self.high=26999.0, self.low=26968.4, self.vol=462.678, self.amt=12484555.5245, ukdf['pct'].iloc[-1]=-0.00113 , ukdf['amount'].iloc[-1]=12484555.5245, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-1458.84720623466', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26969.65708791', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40181
self.closeSec=1696091099, self.tradeDate='20231001', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26969.7, self.close=26979.9, self.high=26980.0, self.low=26966.5, self.vol=447.529, self.amt=12071541.6567 
2023-10-01 00:25:00,811:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231001   000000    000459  ...         0.0        0.0       0
5761  20231001   000500    000959  ...         0.0        0.0       0
5762  20231001   001000    001459  ...         0.0        0.0       0
5763  20231001   001500    001959  ...         0.0        0.0       0
5764  20231001   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 00:25:00,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696091099, self.tradeDate='20231001', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26969.7, self.close=26979.9, self.high=26980.0, self.low=26966.5, self.vol=447.529, self.amt=12071541.6567, ukdf['pct'].iloc[-1]=0.000423 , ukdf['amount'].iloc[-1]=12071541.6567, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-1556.9268', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26976.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [01/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230926' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [01/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40180 

self.closeSec=1696090199, self.tradeDate='20231001', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26986.6, self.close=27010.1, self.high=27010.1, self.low=26973.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40181 

self.closeSec=1696090499, self.tradeDate='20231001', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27010.2, self.close=26999.0, self.high=27010.2, self.low=26985.1 
127.0.0.1 - - [01/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40182 

self.closeSec=1696090799, self.tradeDate='20231001', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26999.0, self.close=26968.5, self.high=26999.0, self.low=26968.4 
127.0.0.1 - - [01/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40183 

self.closeSec=1696091099, self.tradeDate='20231001', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26969.7, self.close=26979.9, self.high=26980.0, self.low=26966.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-01 00:00:17,473:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230930    212959  26914.2  ...  50.416667  0.523347  0.361251
5802  20230930    215959  26919.3  ...  50.416667  0.536165  0.343818
5803  20230930    222959  26962.0  ...  50.833333  0.537981  0.331528
5804  20230930    225959  26968.2  ...  50.833333  0.541016  0.318351
5805  20230930    232959  26977.6  ...  50.833333  0.549184  0.315586

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-10-01 00:00:17,531:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.493272  0.506728       1  ...  0.977230  -1.0    0.0  1.004695
540     0  0.506607  0.493393       1  ...  0.977009  -1.0    0.0  1.004922
541     1  0.498090  0.501910       1  ...  0.976643  -1.0    0.0  1.005299
542     1  0.499186  0.500814       1  ...  0.975655  -1.0    0.0  1.006316
543     0  0.506255  0.493745       0  ...  0.976352  -1.0    0.0  1.005597

[5 rows x 10 columns]
2023-10-01 00:00:17,542:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493355  0.506645       1  ...  0.977230  -1.0    0.0  1.007454
46     0  0.506618  0.493382       1  ...  0.977009  -1.0    0.0  1.005638
47     1  0.498013  0.501987       1  ...  0.976643  -1.0    0.0  1.005078
48     1  0.499469  0.500531       1  ...  0.975655  -1.0    0.0  1.006095
49     0  0.506255  0.493745       0  ...  0.976352  -1.0    0.0  1.005597

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.689', 'enterprice': '27080', 'countrevence': '0', 'unrealprofit': '2549.74325158245', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26980.74571795', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20087 

self.closeSec=1696087799, self.tradeDate='20230930', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27026.9', self.close='27005.5'
127.0.0.1 - - [30/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20088 

self.closeSec=1696088399, self.tradeDate='20230930', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27005.5', self.close='27036.3'
127.0.0.1 - - [30/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20089 

self.closeSec=1696088999, self.tradeDate='20230930', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27036.4', self.close='27024'
127.0.0.1 - - [01/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20090 

self.closeSec=1696089599, self.tradeDate='20230930', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27024.9', self.close='26986.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20091 

self.closeSec=1696090199, self.tradeDate='20231001', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26986.2', self.close='27010.1'
127.0.0.1 - - [01/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20092 

self.closeSec=1696090799, self.tradeDate='20231001', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27010.2', self.close='26969.7'
127.0.0.1 - - [01/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [30/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20090 

self.closeSec=1696087799, self.tradeDate='20230930', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27026.9', self.close='27005.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20091 

self.closeSec=1696088399, self.tradeDate='20230930', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27005.5', self.close='27036.3'
127.0.0.1 - - [30/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20092 

self.closeSec=1696088999, self.tradeDate='20230930', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27036.4', self.close='27024'
127.0.0.1 - - [01/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20093 

self.closeSec=1696089599, self.tradeDate='20230930', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27024.9', self.close='26986.2'
127.0.0.1 - - [01/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20094 

self.closeSec=1696090199, self.tradeDate='20231001', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26986.2', self.close='27010.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20095 

self.closeSec=1696090799, self.tradeDate='20231001', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27010.2', self.close='26969.7'
127.0.0.1 - - [01/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20090 

self.closeSec=1696087799, self.tradeDate='20230930', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27026.9', self.close='27005.5'
127.0.0.1 - - [30/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20091 

self.closeSec=1696088399, self.tradeDate='20230930', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27005.5', self.close='27036.3'

--handleKline--: 127.0.0.1 - - [30/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20092 

self.closeSec=1696088999, self.tradeDate='20230930', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27036.4', self.close='27024'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20093 

self.closeSec=1696089599, self.tradeDate='20230930', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27024.9', self.close='26986.2'
127.0.0.1 - - [01/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20094 

self.closeSec=1696090199, self.tradeDate='20231001', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26986.2', self.close='27010.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20095 

self.closeSec=1696090799, self.tradeDate='20231001', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27010.2', self.close='26969.7'
127.0.0.1 - - [01/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40180
self.closeSec=1696090799, self.tradeDate='20231001', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26999.0, self.close=26968.5, self.high=26999.0, self.low=26968.4, self.vol=462.678, self.amt=12484555.5245 
127.0.0.1 - - [01/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-01 00:20:06,507:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230930   235500    235959  ...         0.0        0.0       0
5760  20231001   000000    000459  ...         0.0        0.0       0
5761  20231001   000500    000959  ...         0.0        0.0       0
5762  20231001   001000    001459  ...         0.0        0.0       0
5763  20231001   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 00:20:06,517:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696090799, self.tradeDate='20231001', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26999.0, self.close=26968.5, self.high=26999.0, self.low=26968.4, self.vol=462.678, self.amt=12484555.5245, ukdf['pct'].iloc[-1]=-0.00113 , ukdf['amount'].iloc[-1]=12484555.5245, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '4667.02990206531', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26969.65708791', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40181
self.closeSec=1696091099, self.tradeDate='20231001', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26969.7, self.close=26979.9, self.high=26980.0, self.low=26966.5, self.vol=447.529, self.amt=12071541.6567 
2023-10-01 00:25:00,785:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231001   000000    000459  ...         0.0        0.0       0
5761  20231001   000500    000959  ...         0.0        0.0       0
5762  20231001   001000    001459  ...         0.0        0.0       0
5763  20231001   001500    001959  ...         0.0        0.0       0
5764  20231001   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 00:25:00,786:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696091099, self.tradeDate='20231001', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26969.7, self.close=26979.9, self.high=26980.0, self.low=26966.5, self.vol=447.529, self.amt=12071541.6567, ukdf['pct'].iloc[-1]=0.000423 , ukdf['amount'].iloc[-1]=12071541.6567, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '4928.6107', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26976.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230930   120000    155959  1696060799  ...    723  0.665911  0.052065     NaN
724  20230930   160000    195959  1696075199  ...    724  0.607552 -0.089134     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-10942.0033', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26924.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [01/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1272444.8790024, self.flagDict['side']='buy', self.tradeCount=27, self.count=837
self.closeSec=1696089599, self.tradeDate='20230930', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26924.3, self.close=26986.2, self.high=27085.0, self.low=26890.4, self.vol=28819.566, self.amt=777674005.9982 
2023-10-01 00:00:01,552:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696089599, self.tradeDate='20230930', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26924.3, self.close=26986.2, self.high=27085.0, self.low=26890.4, self.vol=28819.566, self.amt=777674005.9982 
2023-10-01 00:00:01,571:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230930   040000    075959  ...  14104.960  3.793057e+08 -0.000855
722  20230930   080000    115959  ...  10406.792  2.799548e+08  0.000491
723  20230930   120000    155959  ...   9597.371  2.583907e+08  0.000439
724  20230930   160000    195959  ...  13577.888  3.658304e+08  0.000316
725  20230930   200000    235959  ...  28819.566  7.776740e+08  0.002295

[5 rows x 11 columns]
2023-10-01 00:00:02,441:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230930   040000    075959  1696031999  ...    721  0.827709  0.447244     NaN
722  20230930   080000    115959  1696046399  ...    722  0.743179  0.240261     NaN
723  20230930   120000    155959  1696060799  ...    723  0.665911  0.052065     NaN
724  20230930   160000    195959  1696075199  ...    724  0.607552 -0.089134     NaN
725  20230930   200000    235959  1696089599  ...    725  0.577577 -0.161830     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-8038.8314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26986.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


