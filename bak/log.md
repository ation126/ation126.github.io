# 20231023 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46612
self.closeSec=1698020399, self.tradeDate='20231023', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29962.0, self.close=29953.7, self.high=29962.8, self.low=29935.0, self.vol=337.279, self.amt=10101136.7287 
127.0.0.1 - - [23/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-23 08:20:13,873:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231023   075500    075959  ...         0.0        0.0       0
5856  20231023   080000    080459  ...         0.0        0.0       0
5857  20231023   080500    080959  ...         0.0        0.0       0
5858  20231023   081000    081459  ...         0.0        0.0       0
5859  20231023   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 08:20:13,882:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698020399, self.tradeDate='20231023', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29962.0, self.close=29953.7, self.high=29962.8, self.low=29935.0, self.vol=337.279, self.amt=10101136.7287, ukdf['pct'].iloc[-1]=-0.000224 , ukdf['amount'].iloc[-1]=10101136.7287, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43078.6884', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29958.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46613
self.closeSec=1698020699, self.tradeDate='20231023', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29953.8, self.close=29879.2, self.high=29959.0, self.low=29875.7, self.vol=938.096, self.amt=28050429.123 
127.0.0.1 - - [23/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-23 08:25:03,183:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231023   080000    080459  ...         0.0        0.0       0
5857  20231023   080500    080959  ...         0.0        0.0       0
5858  20231023   081000    081459  ...         0.0        0.0       0
5859  20231023   081500    081959  ...         0.0        0.0       0
5860  20231023   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 08:25:03,186:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698020699, self.tradeDate='20231023', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29953.8, self.close=29879.2, self.high=29959.0, self.low=29875.7, self.vol=938.096, self.amt=28050429.123, ukdf['pct'].iloc[-1]=-0.002487 , ukdf['amount'].iloc[-1]=28050429.123, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41991.39694839078', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29880.22363553', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [23/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46610 

self.closeSec=1698019199, self.tradeDate='20231023', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29954.4, self.close=29981.5, self.high=29981.5, self.low=29951.7 
127.0.0.1 - - [23/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46611 

self.closeSec=1698019499, self.tradeDate='20231023', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29981.4, self.close=29939.9, self.high=29988.6, self.low=29897.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46612 

self.closeSec=1698019799, self.tradeDate='20231023', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29943.0, self.close=29944.8, self.high=29962.8, self.low=29920.7 
127.0.0.1 - - [23/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46613 

self.closeSec=1698020099, self.tradeDate='20231023', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29944.8, self.close=29960.4, self.high=29973.4, self.low=29940.9 
127.0.0.1 - - [23/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46614 

self.closeSec=1698020399, self.tradeDate='20231023', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29962.0, self.close=29953.7, self.high=29962.8, self.low=29935.0 
127.0.0.1 - - [23/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46615 

self.closeSec=1698020699, self.tradeDate='20231023', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29953.8, self.close=29879.2, self.high=29959.0, self.low=29875.7 
127.0.0.1 - - [23/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-23 08:00:17,451:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231023    052959  29838.8  ...  53.333333  0.510680  0.591043
5770  20231023    055959  29791.0  ...  53.333333  0.498695  0.604141
5771  20231023    062959  29740.5  ...  53.750000  0.518986  0.606565
5772  20231023    065959  29820.9  ...  54.166667  0.557880  0.587954
5773  20231023    072959  30023.4  ...  53.750000  0.538786  0.579549

[5 rows x 33 columns]
0.5722222222222222
acc is : 0.5722222222222222
2023-10-23 08:00:17,509:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.491042  0.508958       0  ...  0.962003   1.0    0.0  1.116903
536     1  0.484634  0.515366       1  ...  0.964966   1.0    0.0  1.120343
537     0  0.529658  0.470342       1  ...  0.971277   1.0    0.0  1.127671
538     0  0.568542  0.431458       0  ...  0.968566   1.0    0.0  1.124523
539     1  0.496160  0.503840       1  ...  0.969847   1.0    0.0  1.126011

[5 rows x 10 columns]
2023-10-23 08:00:17,520:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491167  0.508833       0  ...  0.950449   1.0    0.0  1.110908
46     1  0.484044  0.515956       1  ...  0.953376   1.0    0.0  1.117473
47     0  0.529880  0.470120       1  ...  0.971277   1.0    0.0  1.125675
48     0  0.568784  0.431216       0  ...  0.968566   1.0    0.0  1.122576
49     1  0.496160  0.503840       1  ...  0.969847   1.0    0.0  1.126011

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.157', 'enterprice': '29765.1', 'countrevence': '0', 'unrealprofit': '4696.51052816449', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29987.08376557', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23303 

self.closeSec=1698017399, self.tradeDate='20231023', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29938.1', self.close='29941.9'
127.0.0.1 - - [23/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23304 

self.closeSec=1698017999, self.tradeDate='20231023', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29941.9', self.close='29964.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23305 127.0.0.1 - - [23/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -


self.closeSec=1698018599, self.tradeDate='20231023', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29964.6', self.close='29976.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23306 

self.closeSec=1698019199, self.tradeDate='20231023', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29980', self.close='29981.5'
127.0.0.1 - - [23/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23307 

self.closeSec=1698019799, self.tradeDate='20231023', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29981.4', self.close='29944.8'
127.0.0.1 - - [23/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23308 

self.closeSec=1698020399, self.tradeDate='20231023', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29944.8', self.close='29953.7'
127.0.0.1 - - [23/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23306 

self.closeSec=1698017399, self.tradeDate='20231023', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29938.1', self.close='29941.9'
127.0.0.1 - - [23/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [23/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23307 

self.closeSec=1698017999, self.tradeDate='20231023', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29941.9', self.close='29964.6'
127.0.0.1 - - [23/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23308 

self.closeSec=1698018599, self.tradeDate='20231023', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29964.6', self.close='29976.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23309 

self.closeSec=1698019199, self.tradeDate='20231023', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29980', self.close='29981.5'
127.0.0.1 - - [23/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23310 

self.closeSec=1698019799, self.tradeDate='20231023', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29981.4', self.close='29944.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23311 

self.closeSec=1698020399, self.tradeDate='20231023', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29944.8', self.close='29953.7'
127.0.0.1 - - [23/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23306 

self.closeSec=1698017399, self.tradeDate='20231023', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29938.1', self.close='29941.9'
127.0.0.1 - - [23/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23307 

self.closeSec=1698017999, self.tradeDate='20231023', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29941.9', self.close='29964.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23308 

self.closeSec=1698018599, self.tradeDate='20231023', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29964.6', self.close='29976.9'
127.0.0.1 - - [23/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23309 

self.closeSec=1698019199, self.tradeDate='20231023', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29980', self.close='29981.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23310 

self.closeSec=1698019799, self.tradeDate='20231023', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29981.4', self.close='29944.8'
127.0.0.1 - - [23/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23311 

self.closeSec=1698020399, self.tradeDate='20231023', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29944.8', self.close='29953.7'
127.0.0.1 - - [23/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46612
self.closeSec=1698020399, self.tradeDate='20231023', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29962.0, self.close=29953.7, self.high=29962.8, self.low=29935.0, self.vol=337.279, self.amt=10101136.7287 
127.0.0.1 - - [23/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -
2023-10-23 08:20:13,884:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231023   075500    075959  ...         0.0        0.0       0
5856  20231023   080000    080459  ...         0.0        0.0       0
5857  20231023   080500    080959  ...         0.0        0.0       0
5858  20231023   081000    081459  ...         0.0        0.0       0
5859  20231023   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 08:20:13,893:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698020399, self.tradeDate='20231023', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29962.0, self.close=29953.7, self.high=29962.8, self.low=29935.0, self.vol=337.279, self.amt=10101136.7287, ukdf['pct'].iloc[-1]=-0.000224 , ukdf['amount'].iloc[-1]=10101136.7287, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '115668.2163', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29958.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46613
self.closeSec=1698020699, self.tradeDate='20231023', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29953.8, self.close=29879.2, self.high=29959.0, self.low=29875.7, self.vol=938.096, self.amt=28050429.123 
127.0.0.1 - - [23/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-23 08:25:03,184:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231023   080000    080459  ...         0.0        0.0       0
5857  20231023   080500    080959  ...         0.0        0.0       0
5858  20231023   081000    081459  ...         0.0        0.0       0
5859  20231023   081500    081959  ...         0.0        0.0       0
5860  20231023   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 08:25:03,186:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698020699, self.tradeDate='20231023', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29953.8, self.close=29879.2, self.high=29959.0, self.low=29875.7, self.vol=938.096, self.amt=28050429.123, ukdf['pct'].iloc[-1]=-0.002487 , ukdf['amount'].iloc[-1]=28050429.123, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '112768.38204721973', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29880.22363553', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231022   200000    235959  1697990399  ...    719  0.948686  0.433889     NaN
720  20231023   000000    035959  1698004799  ...    720  0.896727  0.339813     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '12095.01345397758', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29831.62555678', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [23/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=971
self.closeSec=1698019199, self.tradeDate='20231023', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29830.0, self.close=29981.5, self.high=30060.2, self.low=29698.0, self.vol=33501.912, self.amt=1001635036.82812 
2023-10-23 08:00:01,534:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698019199, self.tradeDate='20231023', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29830.0, self.close=29981.5, self.high=30060.2, self.low=29698.0, self.vol=33501.912, self.amt=1001635036.82812 
2023-10-23 08:00:01,554:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231022   120000    155959  ...  63562.834  1.903340e+09 -0.003224
718  20231022   160000    195959  ...  35444.616  1.058783e+09  0.003198
719  20231022   200000    235959  ...  23241.182  6.941179e+08 -0.002696
720  20231023   000000    035959  ...  17704.232  5.288255e+08  0.000490
721  20231023   040000    075959  ...  33501.912  1.001635e+09  0.005082

[5 rows x 11 columns]
2023-10-23 08:00:02,369:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231022   120000    155959  1697961599  ...    717  0.958796  0.474248     NaN
718  20231022   160000    195959  1697975999  ...    718  0.971829  0.482675     NaN
719  20231022   200000    235959  1697990399  ...    719  0.948686  0.433889     NaN
720  20231023   000000    035959  1698004799  ...    720  0.896727  0.339813     NaN
721  20231023   040000    075959  1698019199  ...    721  0.864482  0.277100     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '18289.8342', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29981.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


