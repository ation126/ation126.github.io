# 20230907 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33268
self.closeSec=1694017199, self.tradeDate='20230907', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25558.5, self.close=25545.4, self.high=25586.1, self.low=25540.5, self.vol=932.069, self.amt=23828260.9524 
127.0.0.1 - - [07/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-09-07 00:20:05,509:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230906   235500    235959  ...         0.0        0.0       0
5760  20230907   000000    000459  ...         0.0        0.0       0
5761  20230907   000500    000959  ...         0.0        0.0       0
5762  20230907   001000    001459  ...         0.0        0.0       0
5763  20230907   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 00:20:05,515:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694017199, self.tradeDate='20230907', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25558.5, self.close=25545.4, self.high=25586.1, self.low=25540.5, self.vol=932.069, self.amt=23828260.9524, ukdf['pct'].iloc[-1]=-0.000509 , ukdf['amount'].iloc[-1]=23828260.9524, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '18387.8904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25544.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33269
self.closeSec=1694017499, self.tradeDate='20230907', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25544.4, self.close=25587.1, self.high=25591.2, self.low=25540.1, self.vol=1063.135, self.amt=27173807.9097 
2023-09-07 00:25:00,821:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230907   000000    000459  ...         0.0        0.0       0
5761  20230907   000500    000959  ...         0.0        0.0       0
5762  20230907   001000    001459  ...         0.0        0.0       0
5763  20230907   001500    001959  ...         0.0        0.0       0
5764  20230907   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 00:25:00,821:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694017499, self.tradeDate='20230907', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25544.4, self.close=25587.1, self.high=25591.2, self.low=25540.1, self.vol=1063.135, self.amt=27173807.9097, ukdf['pct'].iloc[-1]=0.001632 , ukdf['amount'].iloc[-1]=27173807.9097, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '17780.28198112122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25588.13122353', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [07/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230902' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33268 

self.closeSec=1694016599, self.tradeDate='20230907', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25575.8, self.close=25560.1, self.high=25588.2, self.low=25560.0 
127.0.0.1 - - [07/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33269 

self.closeSec=1694016899, self.tradeDate='20230907', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25560.1, self.close=25558.4, self.high=25567.0, self.low=25548.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33270 

self.closeSec=1694017199, self.tradeDate='20230907', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25558.5, self.close=25545.4, self.high=25586.1, self.low=25540.5 
127.0.0.1 - - [07/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33271 

self.closeSec=1694017499, self.tradeDate='20230907', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25544.4, self.close=25587.1, self.high=25591.2, self.low=25540.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-07 00:00:18,635:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230906    212959  25700.1  ...  50.000000  0.464238  0.578104
5802  20230906    215959  25689.5  ...  50.416667  0.481813  0.583157
5803  20230906    222959  25728.6  ...  50.416667  0.430166  0.608776
5804  20230906    225959  25582.4  ...  50.833333  0.438208  0.619646
5805  20230906    232959  25605.9  ...  50.416667  0.433794  0.632116

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-09-07 00:00:18,705:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.487746  0.512254       1  ...  1.006903  -1.0    0.0  0.988057
540     0  0.501682  0.498318       0  ...  1.012405  -1.0    0.0  0.982657
541     1  0.444589  0.555411       1  ...  1.011677  -1.0    0.0  0.983364
542     1  0.485660  0.514340       0  ...  1.012191  -1.0    0.0  0.982865
543     1  0.479064  0.520936       0  ...  1.012871  -1.0    0.0  0.982204

[5 rows x 10 columns]
2023-09-07 00:00:18,719:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487237  0.512763       1  ...  1.006903  -1.0    0.0  0.987829
46     0  0.500830  0.499170       0  ...  1.012405  -1.0    0.0  0.981636
47     1  0.444155  0.555845       1  ...  1.011677  -1.0    0.0  0.982873
48     1  0.485132  0.514868       0  ...  1.012191  -1.0    0.0  0.982374
49     1  0.479064  0.520936       0  ...  1.012871  -1.0    0.0  0.982204

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '29185.49720384195', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25571.42188235', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [06/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16631 

self.closeSec=1694014199, self.tradeDate='20230906', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25566', self.close='25593.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16632 

self.closeSec=1694014799, self.tradeDate='20230906', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25593.5', self.close='25597.8'
127.0.0.1 - - [06/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16633 

self.closeSec=1694015399, self.tradeDate='20230906', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25597.8', self.close='25611'
127.0.0.1 - - [06/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16634 

self.closeSec=1694015999, self.tradeDate='20230906', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25611.8', self.close='25576.3'
127.0.0.1 - - [07/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16635 

self.closeSec=1694016599, self.tradeDate='20230907', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25576.3', self.close='25560.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16636 

self.closeSec=1694017199, self.tradeDate='20230907', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25560.1', self.close='25544.5'
127.0.0.1 - - [07/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [06/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16634 

self.closeSec=1694014199, self.tradeDate='20230906', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25566', self.close='25593.5'
127.0.0.1 - - [06/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16635 

self.closeSec=1694014799, self.tradeDate='20230906', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25593.5', self.close='25597.8'
127.0.0.1 - - [06/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16636 

self.closeSec=1694015399, self.tradeDate='20230906', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25597.8', self.close='25611'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16637 

self.closeSec=1694015999, self.tradeDate='20230906', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25611.8', self.close='25576.3'
127.0.0.1 - - [07/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16638 

self.closeSec=1694016599, self.tradeDate='20230907', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25576.3', self.close='25560.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16639 

self.closeSec=1694017199, self.tradeDate='20230907', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25560.1', self.close='25544.5'
127.0.0.1 - - [07/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16634 

self.closeSec=1694014199, self.tradeDate='20230906', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25566', self.close='25593.5'
127.0.0.1 - - [06/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16635 

self.closeSec=1694014799, self.tradeDate='20230906', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25593.5', self.close='25597.8'
127.0.0.1 - - [06/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16636 

self.closeSec=1694015399, self.tradeDate='20230906', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25597.8', self.close='25611'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16637 

self.closeSec=1694015999, self.tradeDate='20230906', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25611.8', self.close='25576.3'
127.0.0.1 - - [07/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16638 

self.closeSec=1694016599, self.tradeDate='20230907', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25576.3', self.close='25560.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16639 

self.closeSec=1694017199, self.tradeDate='20230907', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25560.1', self.close='25544.5'
127.0.0.1 - - [07/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33268
self.closeSec=1694017199, self.tradeDate='20230907', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25558.5, self.close=25545.4, self.high=25586.1, self.low=25540.5, self.vol=932.069, self.amt=23828260.9524 
127.0.0.1 - - [07/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-09-07 00:20:05,506:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230906   235500    235959  ...         0.0        0.0       0
5760  20230907   000000    000459  ...         0.0        0.0       0
5761  20230907   000500    000959  ...         0.0        0.0       0
5762  20230907   001000    001459  ...         0.0        0.0       0
5763  20230907   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 00:20:05,509:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694017199, self.tradeDate='20230907', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25558.5, self.close=25545.4, self.high=25586.1, self.low=25540.5, self.vol=932.069, self.amt=23828260.9524, ukdf['pct'].iloc[-1]=-0.000509 , ukdf['amount'].iloc[-1]=23828260.9524, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-48264.7295', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25544.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [07/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33269
self.closeSec=1694017499, self.tradeDate='20230907', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25544.4, self.close=25587.1, self.high=25591.2, self.low=25540.1, self.vol=1063.135, self.amt=27173807.9097 
2023-09-07 00:25:00,819:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230907   000000    000459  ...         0.0        0.0       0
5761  20230907   000500    000959  ...         0.0        0.0       0
5762  20230907   001000    001459  ...         0.0        0.0       0
5763  20230907   001500    001959  ...         0.0        0.0       0
5764  20230907   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 00:25:00,819:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694017499, self.tradeDate='20230907', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25544.4, self.close=25587.1, self.high=25591.2, self.low=25540.1, self.vol=1063.135, self.amt=27173807.9097, ukdf['pct'].iloc[-1]=0.001632 , ukdf['amount'].iloc[-1]=27173807.9097, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-46644.22222687227', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25588.13122353', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230906   120000    155959  1693987199  ...    723  0.235360 -0.430896     NaN
724  20230906   160000    195959  1694001599  ...    724  0.257673 -0.377964     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '9768.94438334886', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25721.44555882', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [07/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=693
self.closeSec=1694015999, self.tradeDate='20230906', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25722.0, self.close=25576.3, self.high=25769.3, self.low=25530.0, self.vol=58993.312, self.amt=1512452735.5492 
2023-09-07 00:00:01,569:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694015999, self.tradeDate='20230906', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25722.0, self.close=25576.3, self.high=25769.3, self.low=25530.0, self.vol=58993.312, self.amt=1512452735.5492 
2023-09-07 00:00:01,584:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230906   040000    075959  ...  13973.252  3.594576e+08  0.004258
722  20230906   080000    115959  ...  16399.582  4.230987e+08 -0.000372
723  20230906   120000    155959  ...  14492.862  3.731917e+08 -0.002138
724  20230906   160000    195959  ...  13681.083  3.520082e+08  0.000276
725  20230906   200000    235959  ...  58993.312  1.512453e+09 -0.005668

[5 rows x 11 columns]
2023-09-07 00:00:02,283:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230906   040000    075959  1693958399  ...    721  0.144573 -0.675100    -1.0
722  20230906   080000    115959  1693972799  ...    722  0.223616 -0.456905     NaN
723  20230906   120000    155959  1693987199  ...    723  0.235360 -0.430896     NaN
724  20230906   160000    195959  1694001599  ...    724  0.257673 -0.377964     NaN
725  20230906   200000    235959  1694015999  ...    725  0.281480 -0.322471     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '18125.109', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25575.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


