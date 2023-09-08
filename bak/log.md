# 20230909 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33844
self.closeSec=1694189999, self.tradeDate='20230909', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25846.2, self.close=25837.2, self.high=25858.6, self.low=25835.5, self.vol=343.839, self.amt=8888264.2296 
127.0.0.1 - - [09/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-09 00:20:05,972:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230908   235500    235959  ...         0.0        0.0       0
5760  20230909   000000    000459  ...         0.0        0.0       0
5761  20230909   000500    000959  ...         0.0        0.0       0
5762  20230909   001000    001459  ...         0.0        0.0       0
5763  20230909   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 00:20:05,975:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694189999, self.tradeDate='20230909', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25846.2, self.close=25837.2, self.high=25858.6, self.low=25835.5, self.vol=343.839, self.amt=8888264.2296, ukdf['pct'].iloc[-1]=-0.000348 , ukdf['amount'].iloc[-1]=8888264.2296, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14290.8612', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25838.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33845
self.closeSec=1694190299, self.tradeDate='20230909', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25837.1, self.close=25840.9, self.high=25850.4, self.low=25836.6, self.vol=290.832, self.amt=7516104.788 
2023-09-09 00:25:00,790:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230909   000000    000459  ...         0.0        0.0       0
5761  20230909   000500    000959  ...         0.0        0.0       0
5762  20230909   001000    001459  ...         0.0        0.0       0
5763  20230909   001500    001959  ...         0.0        0.0       0
5764  20230909   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 00:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694190299, self.tradeDate='20230909', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25837.1, self.close=25840.9, self.high=25850.4, self.low=25836.6, self.vol=290.832, self.amt=7516104.788, ukdf['pct'].iloc[-1]=0.000143 , ukdf['amount'].iloc[-1]=7516104.788, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14232.57961465692', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25842.88509158', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [09/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230904' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [09/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33844 

self.closeSec=1694189399, self.tradeDate='20230909', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25851.4, self.close=25854.8, self.high=25856.9, self.low=25847.1 
127.0.0.1 - - [09/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33845 

self.closeSec=1694189699, self.tradeDate='20230909', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25854.7, self.close=25846.2, self.high=25856.8, self.low=25846.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33846 

self.closeSec=1694189999, self.tradeDate='20230909', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25846.2, self.close=25837.2, self.high=25858.6, self.low=25835.5 
127.0.0.1 - - [09/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33847 

self.closeSec=1694190299, self.tradeDate='20230909', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25837.1, self.close=25840.9, self.high=25850.4, self.low=25836.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-09 00:00:18,048:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230908    212959  25839.3  ...  50.000000  0.479299  0.465114
5802  20230908    215959  25854.4  ...  50.416667  0.484113  0.481025
5803  20230908    222959  25873.3  ...  50.416667  0.497092  0.491677
5804  20230908    225959  25924.9  ...  50.000000  0.471524  0.510486
5805  20230908    232959  25815.7  ...  50.416667  0.478369  0.525824

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-09-09 00:00:18,110:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.501101  0.498899       1  ...  1.012050  -1.0    0.0  0.998079
540     0  0.503772  0.496228       1  ...  1.010028  -1.0    0.0  1.000073
541     0  0.516657  0.483343       0  ...  1.014282  -1.0    0.0  0.995861
542     1  0.463524  0.536476       1  ...  1.013210  -1.0    0.0  0.996914
543     0  0.501891  0.498109       0  ...  1.013727  -1.0    0.0  0.996405

[5 rows x 10 columns]
2023-09-09 00:00:18,121:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501400  0.498600       1  ...  1.012050  -1.0    0.0  0.997775
46     0  0.503746  0.496254       1  ...  1.010028  -1.0    0.0  0.999618
47     0  0.517003  0.482997       0  ...  1.014282  -1.0    0.0  0.996507
48     1  0.463982  0.536018       1  ...  1.013210  -1.0    0.0  0.997560
49     0  0.501891  0.498109       0  ...  1.013727  -1.0    0.0  0.996405

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '-1567.21767983412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25826.86697802', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16919 

self.closeSec=1694186999, self.tradeDate='20230908', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25846.5', self.close='25843'
127.0.0.1 - - [08/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16920 

self.closeSec=1694187599, self.tradeDate='20230908', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25843', self.close='25864'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16921 

self.closeSec=1694188199, self.tradeDate='20230908', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25864', self.close='25836.4'
127.0.0.1 - - [08/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16922 

self.closeSec=1694188799, self.tradeDate='20230908', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25836.3', self.close='25829.8'
127.0.0.1 - - [09/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16923 

self.closeSec=1694189399, self.tradeDate='20230909', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25829.9', self.close='25854.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16924 

self.closeSec=1694189999, self.tradeDate='20230909', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25854.7', self.close='25837.2'
127.0.0.1 - - [09/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16922 

self.closeSec=1694186999, self.tradeDate='20230908', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25846.5', self.close='25843'
127.0.0.1 - - [08/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16923 

self.closeSec=1694187599, self.tradeDate='20230908', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25843', self.close='25864'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16924 

self.closeSec=1694188199, self.tradeDate='20230908', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25864', self.close='25836.4'
127.0.0.1 - - [08/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16925 

self.closeSec=1694188799, self.tradeDate='20230908', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25836.3', self.close='25829.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16926 

self.closeSec=1694189399, self.tradeDate='20230909', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25829.9', self.close='25854.8'
127.0.0.1 - - [09/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16927 

self.closeSec=1694189999, self.tradeDate='20230909', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25854.7', self.close='25837.2'
127.0.0.1 - - [09/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16922 

self.closeSec=1694186999, self.tradeDate='20230908', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25846.5', self.close='25843'
127.0.0.1 - - [08/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16923 

self.closeSec=1694187599, self.tradeDate='20230908', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25843', self.close='25864'
127.0.0.1 - - [08/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16924 

self.closeSec=1694188199, self.tradeDate='20230908', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25864', self.close='25836.4'
127.0.0.1 - - [09/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16925 

self.closeSec=1694188799, self.tradeDate='20230908', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25836.3', self.close='25829.8'
127.0.0.1 - - [09/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16926 

self.closeSec=1694189399, self.tradeDate='20230909', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25829.9', self.close='25854.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16927 

self.closeSec=1694189999, self.tradeDate='20230909', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25854.7', self.close='25837.2'
127.0.0.1 - - [09/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33844
self.closeSec=1694189999, self.tradeDate='20230909', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25846.2, self.close=25837.2, self.high=25858.6, self.low=25835.5, self.vol=343.839, self.amt=8888264.2296 
127.0.0.1 - - [09/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-09 00:20:05,968:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230908   235500    235959  ...         0.0        0.0       0
5760  20230909   000000    000459  ...         0.0        0.0       0
5761  20230909   000500    000959  ...         0.0        0.0       0
5762  20230909   001000    001459  ...         0.0        0.0       0
5763  20230909   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 00:20:05,970:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694189999, self.tradeDate='20230909', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25846.2, self.close=25837.2, self.high=25858.6, self.low=25835.5, self.vol=343.839, self.amt=8888264.2296, ukdf['pct'].iloc[-1]=-0.000348 , ukdf['amount'].iloc[-1]=8888264.2296, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37337.8473', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25838.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33845
self.closeSec=1694190299, self.tradeDate='20230909', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25837.1, self.close=25840.9, self.high=25850.4, self.low=25836.6, self.vol=290.832, self.amt=7516104.788 
2023-09-09 00:25:00,775:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230909   000000    000459  ...         0.0        0.0       0
5761  20230909   000500    000959  ...         0.0        0.0       0
5762  20230909   001000    001459  ...         0.0        0.0       0
5763  20230909   001500    001959  ...         0.0        0.0       0
5764  20230909   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 00:25:00,775:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694190299, self.tradeDate='20230909', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25837.1, self.close=25840.9, self.high=25850.4, self.low=25836.6, self.vol=290.832, self.amt=7516104.788, ukdf['pct'].iloc[-1]=0.000143 , ukdf['amount'].iloc[-1]=7516104.788, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37182.40881362722', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25842.88509158', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230908   120000    155959  1694159999  ...    723  0.269430 -0.364649     NaN
724  20230908   160000    195959  1694174399  ...    724  0.205650 -0.544857     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '3928.46328087615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25823.59294505', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=705
self.closeSec=1694188799, self.tradeDate='20230908', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25828.9, self.close=25829.8, self.high=25945.7, self.low=25777.4, self.vol=36852.122, self.amt=953206689.2079 
127.0.0.1 - - [09/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-09 00:00:01,532:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694188799, self.tradeDate='20230908', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25828.9, self.close=25829.8, self.high=25945.7, self.low=25777.4, self.vol=36852.122, self.amt=953206689.2079 
2023-09-09 00:00:01,552:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230908   040000    075959  ...  115647.917  3.031112e+09  0.014408
722  20230908   080000    115959  ...   36619.154  9.622821e+08 -0.000160
723  20230908   120000    155959  ...   33675.232  8.847911e+08  0.000324
724  20230908   160000    195959  ...   92561.921  2.396823e+09 -0.015821
725  20230908   200000    235959  ...   36852.122  9.532067e+08  0.000035

[5 rows x 11 columns]
2023-09-09 00:00:02,458:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230908   040000    075959  1694131199  ...    721  0.049128 -0.974409    -1.0
722  20230908   080000    115959  1694145599  ...    722  0.174553 -0.625975    -1.0
723  20230908   120000    155959  1694159999  ...    723  0.269430 -0.364649     NaN
724  20230908   160000    195959  1694174399  ...    724  0.205650 -0.544857     NaN
725  20230908   200000    235959  1694188799  ...    725  0.206120 -0.544597     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '3518.81332347258', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25830.75753846', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


