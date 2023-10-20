# 20231021 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45940
self.closeSec=1697818799, self.tradeDate='20231021', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29456.2, self.close=29498.1, self.high=29498.1, self.low=29428.7, self.vol=1327.394, self.amt=39098333.1658 
127.0.0.1 - - [21/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-10-21 00:20:08,406:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231020   235500    235959  ...         0.0        0.0       0
5760  20231021   000000    000459  ...         0.0        0.0       0
5761  20231021   000500    000959  ...         0.0        0.0       0
5762  20231021   001000    001459  ...         0.0        0.0       0
5763  20231021   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 00:20:08,416:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697818799, self.tradeDate='20231021', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29456.2, self.close=29498.1, self.high=29498.1, self.low=29428.7, self.vol=1327.394, self.amt=39098333.1658, ukdf['pct'].iloc[-1]=0.001426 , ukdf['amount'].iloc[-1]=39098333.1658, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-36657.4098', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29497.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45941
self.closeSec=1697819099, self.tradeDate='20231021', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29498.5, self.close=29536.3, self.high=29544.3, self.low=29496.0, self.vol=1075.346, self.amt=31745282.0046 
127.0.0.1 - - [21/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-21 00:25:02,764:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231021   000000    000459  ...         0.0        0.0       0
5761  20231021   000500    000959  ...         0.0        0.0       0
5762  20231021   001000    001459  ...         0.0        0.0       0
5763  20231021   001500    001959  ...         0.0        0.0       0
5764  20231021   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 00:25:02,765:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697819099, self.tradeDate='20231021', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29498.5, self.close=29536.3, self.high=29544.3, self.low=29496.0, self.vol=1075.346, self.amt=31745282.0046, ukdf['pct'].iloc[-1]=0.001295 , ukdf['amount'].iloc[-1]=31745282.0046, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-37202.22942890652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29536.32247802', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1697817899, self.tradeDate='20231021', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=29538.7, self.close=29508.8, self.high=29540.0, self.low=29475.2 

--ukdf-hist--: overDate='20231016' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [21/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45940 

self.closeSec=1697818199, self.tradeDate='20231021', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29509.7, self.close=29490.3, self.high=29510.5, self.low=29486.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45941 

self.closeSec=1697818499, self.tradeDate='20231021', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29490.3, self.close=29456.1, self.high=29490.3, self.low=29456.1 
127.0.0.1 - - [21/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45942 

self.closeSec=1697818799, self.tradeDate='20231021', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29456.2, self.close=29498.1, self.high=29498.1, self.low=29428.7 
127.0.0.1 - - [21/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45943 

self.closeSec=1697819099, self.tradeDate='20231021', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29498.5, self.close=29536.3, self.high=29544.3, self.low=29496.0 
127.0.0.1 - - [21/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-21 00:00:21,868:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231020    212959  29498.8  ...  54.583333  0.604718  0.239605
5802  20231020    215959  29504.0  ...  55.000000  0.619960  0.246933
5803  20231020    222959  29635.8  ...  54.583333  0.597038  0.259621
5804  20231020    225959  29507.1  ...  55.000000  0.604237  0.269004
5805  20231020    232959  29569.2  ...  54.583333  0.603900  0.277836

[5 rows x 33 columns]
0.5698529411764706
acc is : 0.5698529411764706
2023-10-21 00:00:21,947:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495027  0.504973       1  ...  0.954960  -1.0    0.0  1.065898
540     0  0.530854  0.469146       0  ...  0.959110  -1.0    0.0  1.061265
541     1  0.461934  0.538066       1  ...  0.957092  -1.0    0.0  1.063499
542     0  0.527682  0.472318       0  ...  0.957153  -1.0    0.0  1.063430
543     0  0.515718  0.484282       0  ...  0.958076  -1.0    0.0  1.062405

[5 rows x 10 columns]
2023-10-21 00:00:21,961:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494830  0.505170       1  ...  0.954960  -1.0    0.0  1.063167
46     0  0.530277  0.469723       0  ...  0.959110  -1.0    0.0  1.057943
47     1  0.461496  0.538504       1  ...  0.957092  -1.0    0.0  1.062494
48     0  0.527766  0.472234       0  ...  0.957153  -1.0    0.0  1.062425
49     0  0.515718  0.484282       0  ...  0.958076  -1.0    0.0  1.062405

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.539', 'enterprice': '29526.5', 'countrevence': '0', 'unrealprofit': '-145.92049204418', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29533.27471062', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22967 

self.closeSec=1697815799, self.tradeDate='20231020', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29511.6', self.close='29567.3'
127.0.0.1 - - [20/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22968 

self.closeSec=1697816399, self.tradeDate='20231020', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29567.3', self.close='29506.6'
127.0.0.1 - - [20/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22969 

self.closeSec=1697816999, self.tradeDate='20231020', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29505.5', self.close='29512.9'
127.0.0.1 - - [21/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22970 

self.closeSec=1697817599, self.tradeDate='20231020', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29512.9', self.close='29538.8'
127.0.0.1 - - [21/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22971 

self.closeSec=1697818199, self.tradeDate='20231021', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29538.7', self.close='29490.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22972 

self.closeSec=1697818799, self.tradeDate='20231021', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29490.3', self.close='29498.1'
127.0.0.1 - - [21/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [20/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22970 

self.closeSec=1697815799, self.tradeDate='20231020', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29511.6', self.close='29567.3'
127.0.0.1 - - [20/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22971 

self.closeSec=1697816399, self.tradeDate='20231020', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29567.3', self.close='29506.6'
127.0.0.1 - - [20/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22972 

self.closeSec=1697816999, self.tradeDate='20231020', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29505.5', self.close='29512.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22973 

self.closeSec=1697817599, self.tradeDate='20231020', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29512.9', self.close='29538.8'
127.0.0.1 - - [21/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22974 

self.closeSec=1697818199, self.tradeDate='20231021', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29538.7', self.close='29490.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22975 

self.closeSec=1697818799, self.tradeDate='20231021', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29490.3', self.close='29498.1'
127.0.0.1 - - [21/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22970 

self.closeSec=1697815799, self.tradeDate='20231020', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29511.6', self.close='29567.3'
127.0.0.1 - - [20/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22971 

self.closeSec=1697816399, self.tradeDate='20231020', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29567.3', self.close='29506.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22972 

self.closeSec=1697816999, self.tradeDate='20231020', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29505.5', self.close='29512.9'
127.0.0.1 - - [20/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22973 

self.closeSec=1697817599, self.tradeDate='20231020', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29512.9', self.close='29538.8'
127.0.0.1 - - [21/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22974 

self.closeSec=1697818199, self.tradeDate='20231021', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29538.7', self.close='29490.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22975 

self.closeSec=1697818799, self.tradeDate='20231021', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29490.3', self.close='29498.1'
127.0.0.1 - - [21/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45940
self.closeSec=1697818799, self.tradeDate='20231021', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29456.2, self.close=29498.1, self.high=29498.1, self.low=29428.7, self.vol=1327.394, self.amt=39098333.1658 
127.0.0.1 - - [21/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-10-21 00:20:08,407:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231020   235500    235959  ...         0.0        0.0       0
5760  20231021   000000    000459  ...         0.0        0.0       0
5761  20231021   000500    000959  ...         0.0        0.0       0
5762  20231021   001000    001459  ...         0.0        0.0       0
5763  20231021   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 00:20:08,426:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697818799, self.tradeDate='20231021', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29456.2, self.close=29498.1, self.high=29498.1, self.low=29428.7, self.vol=1327.394, self.amt=39098333.1658, ukdf['pct'].iloc[-1]=0.001426 , ukdf['amount'].iloc[-1]=39098333.1658, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '98542.5012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29497.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45941
self.closeSec=1697819099, self.tradeDate='20231021', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29498.5, self.close=29536.3, self.high=29544.3, self.low=29496.0, self.vol=1075.346, self.amt=31745282.0046 
127.0.0.1 - - [21/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-21 00:25:02,764:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231021   000000    000459  ...         0.0        0.0       0
5761  20231021   000500    000959  ...         0.0        0.0       0
5762  20231021   001000    001459  ...         0.0        0.0       0
5763  20231021   001500    001959  ...         0.0        0.0       0
5764  20231021   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 00:25:02,766:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697819099, self.tradeDate='20231021', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29498.5, self.close=29536.3, self.high=29544.3, self.low=29496.0, self.vol=1075.346, self.amt=31745282.0046, ukdf['pct'].iloc[-1]=0.001295 , ukdf['amount'].iloc[-1]=31745282.0046, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '99995.54915614082', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29536.32247802', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231020   120000    155959  1697788799  ...    723  0.008180 -0.962225    -1.0
724  20231020   160000    195959  1697803199  ...    724  0.074023 -0.844133    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.755', 'enterprice': '28761.1', 'countrevence': '0', 'unrealprofit': '-46896.609', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29832.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [21/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1257183.4885695, self.flagDict['side']='sell', self.tradeCount=36, self.count=957
self.closeSec=1697817599, self.tradeDate='20231020', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29829.9, self.close=29538.8, self.high=29900.0, self.low=29358.5, self.vol=114979.415, self.amt=3399972054.23065 
2023-10-21 00:00:01,531:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697817599, self.tradeDate='20231020', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29829.9, self.close=29538.8, self.high=29900.0, self.low=29358.5, self.vol=114979.415, self.amt=3399972054.23065 
2023-10-21 00:00:01,580:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20231020   040000    075959  ...   36228.044  1.039869e+09 -0.001448
722  20231020   080000    115959  ...  110974.902  3.219885e+09  0.018326
723  20231020   120000    155959  ...   65199.235  1.906398e+09  0.000195
724  20231020   160000    195959  ...  187716.424  5.594120e+09  0.020463
725  20231020   200000    235959  ...  114979.415  3.399972e+09 -0.009649

[5 rows x 11 columns]
2023-10-21 00:00:02,357:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231020   040000    075959  1697759999  ...    721  0.082168 -0.875769    -1.0
722  20231020   080000    115959  1697774399  ...    722  0.044257 -0.920352    -1.0
723  20231020   120000    155959  1697788799  ...    723  0.008180 -0.962225    -1.0
724  20231020   160000    195959  1697803199  ...    724  0.074023 -0.844133    -1.0
725  20231020   200000    235959  1697817599  ...    725  0.094832 -0.801326    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.755', 'enterprice': '28761.1', 'countrevence': '0', 'unrealprofit': '-34023.888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29538.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


