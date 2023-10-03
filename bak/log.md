# 20231004 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41044
self.closeSec=1696349999, self.tradeDate='20231004', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27347.5, self.close=27370.0, self.high=27405.0, self.low=27343.4, self.vol=1832.037, self.amt=50174518.6377 
127.0.0.1 - - [04/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-04 00:20:05,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231003   235500    235959  ...         0.0        0.0       0
5760  20231004   000000    000459  ...         0.0        0.0       0
5761  20231004   000500    000959  ...         0.0        0.0       0
5762  20231004   001000    001459  ...         0.0        0.0       0
5763  20231004   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 00:20:05,815:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696349999, self.tradeDate='20231004', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27347.5, self.close=27370.0, self.high=27405.0, self.low=27343.4, self.vol=1832.037, self.amt=50174518.6377, ukdf['pct'].iloc[-1]=0.000823 , ukdf['amount'].iloc[-1]=50174518.6377, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7164.927', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27379.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41045
self.closeSec=1696350299, self.tradeDate='20231004', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27370.0, self.close=27395.2, self.high=27402.0, self.low=27357.5, self.vol=740.326, self.amt=20272105.8419 
127.0.0.1 - - [04/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-10-04 00:25:00,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231004   000000    000459  ...         0.0        0.0       0
5761  20231004   000500    000959  ...         0.0        0.0       0
5762  20231004   001000    001459  ...         0.0        0.0       0
5763  20231004   001500    001959  ...         0.0        0.0       0
5764  20231004   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 00:25:00,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696350299, self.tradeDate='20231004', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27370.0, self.close=27395.2, self.high=27402.0, self.low=27357.5, self.vol=740.326, self.amt=20272105.8419, ukdf['pct'].iloc[-1]=0.000921 , ukdf['amount'].iloc[-1]=20272105.8419, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7411.4172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27397.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1696349099, self.tradeDate='20231004', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27332.1, self.close=27384.9, self.high=27386.7, self.low=27314.7 

--ukdf-hist--: overDate='20230929' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41044 

self.closeSec=1696349399, self.tradeDate='20231004', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27384.7, self.close=27315.5, self.high=27395.0, self.low=27312.6 
127.0.0.1 - - [04/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41045 

self.closeSec=1696349699, self.tradeDate='20231004', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27312.4, self.close=27347.5, self.high=27358.0, self.low=27305.3 
127.0.0.1 - - [04/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41046 

self.closeSec=1696349999, self.tradeDate='20231004', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27347.5, self.close=27370.0, self.high=27405.0, self.low=27343.4 
127.0.0.1 - - [04/Oct/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41047 

self.closeSec=1696350299, self.tradeDate='20231004', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27370.0, self.close=27395.2, self.high=27402.0, self.low=27357.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-04 00:00:19,045:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231003    212959  27458.1  ...  56.666667  0.484577  0.720866
5802  20231003    215959  27520.0  ...  56.666667  0.486950  0.717380
5803  20231003    222959  27533.4  ...  56.250000  0.459635  0.727118
5804  20231003    225959  27362.6  ...  55.833333  0.456272  0.737253
5805  20231003    232959  27338.6  ...  55.833333  0.464721  0.742336

[5 rows x 33 columns]
0.5680147058823529
acc is : 0.5680147058823529
2023-10-04 00:00:19,113:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510287  0.489713       1  ...  0.951473  -1.0    0.0  1.032726
540     0  0.505440  0.494560       0  ...  0.957376  -1.0    0.0  1.026319
541     1  0.443296  0.556704       0  ...  0.958145  -1.0    0.0  1.025494
542     1  0.483524  0.516476       1  ...  0.956516  -1.0    0.0  1.027238
543     0  0.506068  0.493932       0  ...  0.958315  -1.0    0.0  1.025307

[5 rows x 10 columns]
2023-10-04 00:00:19,126:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510610  0.489390       1  ...  0.951473  -1.0    0.0  1.033540
46     0  0.506072  0.493928       0  ...  0.957376  -1.0    0.0  1.028391
47     1  0.444182  0.555818       0  ...  0.940026  -1.0    0.0  1.028933
48     1  0.484121  0.515879       1  ...  0.938427  -1.0    0.0  1.030683
49     0  0.506068  0.493932       0  ...  0.958315  -1.0    0.0  1.025307

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.906', 'enterprice': '28298.9', 'countrevence': '0', 'unrealprofit': '23302.06066417152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27324.16308608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20519 

self.closeSec=1696346999, self.tradeDate='20231003', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27394.9', self.close='27387.1'
127.0.0.1 - - [03/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [03/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20520 

self.closeSec=1696347599, self.tradeDate='20231003', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27387.1', self.close='27343.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20521 

self.closeSec=1696348199, self.tradeDate='20231003', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27346.5', self.close='27290.7'
127.0.0.1 - - [03/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20522 

self.closeSec=1696348799, self.tradeDate='20231003', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27290.7', self.close='27332'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20523 

self.closeSec=1696349399, self.tradeDate='20231004', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27332.1', self.close='27312.4'
127.0.0.1 - - [04/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20524 

self.closeSec=1696349999, self.tradeDate='20231004', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27312.4', self.close='27370'
127.0.0.1 - - [04/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [03/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20522 

self.closeSec=1696346999, self.tradeDate='20231003', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27394.9', self.close='27387.1'
127.0.0.1 - - [03/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20523 

self.closeSec=1696347599, self.tradeDate='20231003', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27387.1', self.close='27343.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20524 

self.closeSec=1696348199, self.tradeDate='20231003', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27346.5', self.close='27290.7'
127.0.0.1 - - [03/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20525 

self.closeSec=1696348799, self.tradeDate='20231003', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27290.7', self.close='27332'
127.0.0.1 - - [04/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20526 

self.closeSec=1696349399, self.tradeDate='20231004', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27332.1', self.close='27312.4'
127.0.0.1 - - [04/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20527 

self.closeSec=1696349999, self.tradeDate='20231004', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27312.4', self.close='27370'
127.0.0.1 - - [04/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20522 

self.closeSec=1696346999, self.tradeDate='20231003', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27394.9', self.close='27387.1'
127.0.0.1 - - [03/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20523 

self.closeSec=1696347599, self.tradeDate='20231003', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27387.1', self.close='27343.7'
127.0.0.1 - - [03/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [03/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20524 

self.closeSec=1696348199, self.tradeDate='20231003', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27346.5', self.close='27290.7'
127.0.0.1 - - [04/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20525 

self.closeSec=1696348799, self.tradeDate='20231003', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27290.7', self.close='27332'
127.0.0.1 - - [04/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20526 

self.closeSec=1696349399, self.tradeDate='20231004', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27332.1', self.close='27312.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20527 

self.closeSec=1696349999, self.tradeDate='20231004', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27312.4', self.close='27370'
127.0.0.1 - - [04/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41044
self.closeSec=1696349999, self.tradeDate='20231004', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27347.5, self.close=27370.0, self.high=27405.0, self.low=27343.4, self.vol=1832.037, self.amt=50174518.6377 
127.0.0.1 - - [04/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-04 00:20:05,813:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231003   235500    235959  ...         0.0        0.0       0
5760  20231004   000000    000459  ...         0.0        0.0       0
5761  20231004   000500    000959  ...         0.0        0.0       0
5762  20231004   001000    001459  ...         0.0        0.0       0
5763  20231004   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 00:20:05,822:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696349999, self.tradeDate='20231004', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27347.5, self.close=27370.0, self.high=27405.0, self.low=27343.4, self.vol=1832.037, self.amt=50174518.6377, ukdf['pct'].iloc[-1]=0.000823 , ukdf['amount'].iloc[-1]=50174518.6377, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '19885.2914', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27379.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [04/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41045
self.closeSec=1696350299, self.tradeDate='20231004', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27370.0, self.close=27395.2, self.high=27402.0, self.low=27357.5, self.vol=740.326, self.amt=20272105.8419 
2023-10-04 00:25:00,803:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231004   000000    000459  ...         0.0        0.0       0
5761  20231004   000500    000959  ...         0.0        0.0       0
5762  20231004   001000    001459  ...         0.0        0.0       0
5763  20231004   001500    001959  ...         0.0        0.0       0
5764  20231004   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 00:25:00,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696350299, self.tradeDate='20231004', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27370.0, self.close=27395.2, self.high=27402.0, self.low=27357.5, self.vol=740.326, self.amt=20272105.8419, ukdf['pct'].iloc[-1]=0.000921 , ukdf['amount'].iloc[-1]=20272105.8419, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '20542.6871', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27397.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231003   120000    155959  1696319999  ...    723  1.122867  1.016519     1.0
724  20231003   160000    195959  1696334399  ...    724  1.109387  0.961711     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-20326.02824022732', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27550.71384249', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [04/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1223948.6721539998, self.flagDict['side']='buy', self.tradeCount=29, self.count=855
self.closeSec=1696348799, self.tradeDate='20231003', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27549.1, self.close=27332.0, self.high=27569.2, self.low=27212.3, self.vol=90415.713, self.amt=2476739805.76576 
2023-10-04 00:00:01,590:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696348799, self.tradeDate='20231003', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27549.1, self.close=27332.0, self.high=27569.2, self.low=27212.3, self.vol=90415.713, self.amt=2476739805.76576 
2023-10-04 00:00:01,606:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231003   040000    075959  ...  88961.527  2.450607e+09 -0.016941
722  20231003   080000    115959  ...  39247.062  1.079420e+09  0.003788
723  20231003   120000    155959  ...  24064.809  6.638310e+08 -0.002095
724  20231003   160000    195959  ...  33099.077  9.119116e+08  0.000763
725  20231003   200000    235959  ...  90415.713  2.476740e+09 -0.007877

[5 rows x 11 columns]
2023-10-04 00:00:02,517:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231003   040000    075959  1696291199  ...    721  1.177827  1.194833     1.0
722  20231003   080000    115959  1696305599  ...    722  1.166157  1.143800     1.0
723  20231003   120000    155959  1696319999  ...    723  1.122867  1.016519     1.0
724  20231003   160000    195959  1696334399  ...    724  1.109387  0.961711     1.0
725  20231003   200000    235959  1696348799  ...    725  1.102317  0.925811     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-29776.17263500204', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27334.62163553', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


