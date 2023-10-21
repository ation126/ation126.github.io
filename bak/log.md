# 20231022 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46228
self.closeSec=1697905199, self.tradeDate='20231022', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29894.8, self.close=29867.2, self.high=29894.8, self.low=29827.9, self.vol=1163.963, self.amt=34750616.4025 
127.0.0.1 - - [22/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-10-22 00:20:07,846:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231021   235500    235959  ...         0.0        0.0       0
5760  20231022   000000    000459  ...         0.0        0.0       0
5761  20231022   000500    000959  ...         0.0        0.0       0
5762  20231022   001000    001459  ...         0.0        0.0       0
5763  20231022   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 00:20:07,857:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697905199, self.tradeDate='20231022', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29894.8, self.close=29867.2, self.high=29894.8, self.low=29827.9, self.vol=1163.963, self.amt=34750616.4025, ukdf['pct'].iloc[-1]=-0.000923 , ukdf['amount'].iloc[-1]=34750616.4025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41810.0298', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29867.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46229
self.closeSec=1697905499, self.tradeDate='20231022', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29867.2, self.close=29903.5, self.high=29905.3, self.low=29850.7, self.vol=838.481, self.amt=25051661.3662 
127.0.0.1 - - [22/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-22 00:25:03,070:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231022   000000    000459  ...         0.0        0.0       0
5761  20231022   000500    000959  ...         0.0        0.0       0
5762  20231022   001000    001459  ...         0.0        0.0       0
5763  20231022   001500    001959  ...         0.0        0.0       0
5764  20231022   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 00:25:03,075:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697905499, self.tradeDate='20231022', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29867.2, self.close=29903.5, self.high=29905.3, self.low=29850.7, self.vol=838.481, self.amt=25051661.3662, ukdf['pct'].iloc[-1]=0.001215 , ukdf['amount'].iloc[-1]=25051661.3662, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42358.7142', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29906.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1697904299, self.tradeDate='20231022', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=29916.4, self.close=29901.7, self.high=29943.9, self.low=29882.0 

--ukdf-hist--: overDate='20231017' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46228 

self.closeSec=1697904599, self.tradeDate='20231022', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29904.9, self.close=29889.2, self.high=29930.4, self.low=29885.0 
127.0.0.1 - - [22/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46229 

self.closeSec=1697904899, self.tradeDate='20231022', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29882.0, self.close=29894.8, self.high=29894.8, self.low=29861.5 
127.0.0.1 - - [22/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46230 

self.closeSec=1697905199, self.tradeDate='20231022', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29894.8, self.close=29867.2, self.high=29894.8, self.low=29827.9 
127.0.0.1 - - [22/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46231 

self.closeSec=1697905499, self.tradeDate='20231022', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29867.2, self.close=29903.5, self.high=29905.3, self.low=29850.7 
127.0.0.1 - - [22/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-22 00:00:20,128:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231021    212959  29755.0  ...  52.916667  0.582275  0.350158
5802  20231021    215959  29733.3  ...  53.333333  0.586985  0.341740
5803  20231021    222959  29761.8  ...  53.333333  0.588320  0.332790
5804  20231021    225959  29772.5  ...  53.750000  0.604581  0.315726
5805  20231021    232959  29867.8  ...  53.750000  0.590697  0.313191

[5 rows x 33 columns]
0.5588235294117647
acc is : 0.5588235294117647
2023-10-22 00:00:20,196:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.502676  0.497324       1  ...  0.965571   1.0    0.0  1.076961
540     0  0.513423  0.486577       1  ...  0.965831   1.0    0.0  1.077250
541     0  0.507513  0.492487       1  ...  0.969069   1.0    0.0  1.080862
542     0  0.539024  0.460976       0  ...  0.967180   1.0    0.0  1.078755
543     1  0.495739  0.504261       1  ...  0.970668   1.0    0.0  1.082645

[5 rows x 10 columns]
2023-10-22 00:00:20,207:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502373  0.497627       1  ...  0.965571   1.0    0.0  1.077245
46     0  0.513448  0.486552       1  ...  0.965831   1.0    0.0  1.077129
47     0  0.507550  0.492450       1  ...  0.969069   1.0    0.0  1.080166
48     0  0.538951  0.461049       0  ...  0.967180   1.0    0.0  1.078061
49     1  0.495739  0.504261       1  ...  0.970668   1.0    0.0  1.082645

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.157', 'enterprice': '29765.1', 'countrevence': '0', 'unrealprofit': '3304.66539258368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29921.29725824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23111 

self.closeSec=1697902199, self.tradeDate='20231021', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29818.6', self.close='29811.3'
127.0.0.1 - - [21/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23112 

self.closeSec=1697902799, self.tradeDate='20231021', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29818.3', self.close='29847.6'
127.0.0.1 - - [21/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23113 

self.closeSec=1697903399, self.tradeDate='20231021', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29849.7', self.close='29857'

--handleKline--: 127.0.0.1 - - [22/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23114 

self.closeSec=1697903999, self.tradeDate='20231021', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29857', self.close='29918.8'
127.0.0.1 - - [22/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23115 

self.closeSec=1697904599, self.tradeDate='20231022', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29916.4', self.close='29889.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23116 

self.closeSec=1697905199, self.tradeDate='20231022', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29882', self.close='29867.2'
127.0.0.1 - - [22/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23114 

self.closeSec=1697902199, self.tradeDate='20231021', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29818.6', self.close='29811.3'
127.0.0.1 - - [21/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23115 

self.closeSec=1697902799, self.tradeDate='20231021', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29818.3', self.close='29847.6'
127.0.0.1 - - [21/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23116 

self.closeSec=1697903399, self.tradeDate='20231021', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29849.7', self.close='29857'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23117 

self.closeSec=1697903999, self.tradeDate='20231021', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29857', self.close='29918.8'
127.0.0.1 - - [22/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23118 

self.closeSec=1697904599, self.tradeDate='20231022', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29916.4', self.close='29889.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23119 

self.closeSec=1697905199, self.tradeDate='20231022', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29882', self.close='29867.2'
127.0.0.1 - - [22/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23114 

self.closeSec=1697902199, self.tradeDate='20231021', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29818.6', self.close='29811.3'
127.0.0.1 - - [21/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23115 

self.closeSec=1697902799, self.tradeDate='20231021', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29818.3', self.close='29847.6'

--handleKline--: 127.0.0.1 - - [21/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23116 

self.closeSec=1697903399, self.tradeDate='20231021', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29849.7', self.close='29857'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23117 

self.closeSec=1697903999, self.tradeDate='20231021', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29857', self.close='29918.8'
127.0.0.1 - - [22/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23118 

self.closeSec=1697904599, self.tradeDate='20231022', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29916.4', self.close='29889.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23119 

self.closeSec=1697905199, self.tradeDate='20231022', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29882', self.close='29867.2'
127.0.0.1 - - [22/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46228
self.closeSec=1697905199, self.tradeDate='20231022', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29894.8, self.close=29867.2, self.high=29894.8, self.low=29827.9, self.vol=1163.963, self.amt=34750616.4025 
127.0.0.1 - - [22/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-10-22 00:20:07,866:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231021   235500    235959  ...         0.0        0.0       0
5760  20231022   000000    000459  ...         0.0        0.0       0
5761  20231022   000500    000959  ...         0.0        0.0       0
5762  20231022   001000    001459  ...         0.0        0.0       0
5763  20231022   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 00:20:07,878:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697905199, self.tradeDate='20231022', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29894.8, self.close=29867.2, self.high=29894.8, self.low=29827.9, self.vol=1163.963, self.amt=34750616.4025, ukdf['pct'].iloc[-1]=-0.000923 , ukdf['amount'].iloc[-1]=34750616.4025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '112284.6712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29867.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46229
self.closeSec=1697905499, self.tradeDate='20231022', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29867.2, self.close=29903.5, self.high=29905.3, self.low=29850.7, self.vol=838.481, self.amt=25051661.3662 
127.0.0.1 - - [22/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-22 00:25:03,088:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231022   000000    000459  ...         0.0        0.0       0
5761  20231022   000500    000959  ...         0.0        0.0       0
5762  20231022   001000    001459  ...         0.0        0.0       0
5763  20231022   001500    001959  ...         0.0        0.0       0
5764  20231022   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 00:25:03,098:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697905499, self.tradeDate='20231022', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29867.2, self.close=29903.5, self.high=29905.3, self.low=29850.7, self.vol=838.481, self.amt=25051661.3662, ukdf['pct'].iloc[-1]=0.001215 , ukdf['amount'].iloc[-1]=25051661.3662, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '113748.0266', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29906.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231021   120000    155959  1697875199  ...    723  0.992068  0.595616     NaN
724  20231021   160000    195959  1697889599  ...    724  0.963248  0.545161     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '10786.9488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29800', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=963
self.closeSec=1697903999, self.tradeDate='20231021', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29794.6, self.close=29918.8, self.high=29973.9, self.low=29651.0, self.vol=45910.776, self.amt=1368943799.06454 
127.0.0.1 - - [22/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-10-22 00:00:01,599:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697903999, self.tradeDate='20231021', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29794.6, self.close=29918.8, self.high=29973.9, self.low=29651.0, self.vol=45910.776, self.amt=1368943799.06454 
2023-10-22 00:00:01,614:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231021   040000    075959  ...  34230.291  1.014654e+09  0.003492
722  20231021   080000    115959  ...  29914.061  8.840110e+08 -0.002091
723  20231021   120000    155959  ...  23430.769  6.943455e+08  0.003089
724  20231021   160000    195959  ...  35531.108  1.057606e+09  0.003780
725  20231021   200000    235959  ...  45910.776  1.368944e+09  0.004165

[5 rows x 11 columns]
2023-10-22 00:00:02,552:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231021   040000    075959  1697846399  ...    721  1.157986  0.864808     1.0
722  20231021   080000    115959  1697860799  ...    722  1.073225  0.726643     1.0
723  20231021   120000    155959  1697875199  ...    723  0.992068  0.595616     NaN
724  20231021   160000    195959  1697889599  ...    724  0.963248  0.545161     NaN
725  20231021   200000    235959  1697903999  ...    725  0.947711  0.509605     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '15892.66176914841', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29923.44268681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


