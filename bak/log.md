# 20231025 16:26:09

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47284
self.closeSec=1698221999, self.tradeDate='20231025', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=33796.9, self.close=33876.3, self.high=33883.8, self.low=33773.3, self.vol=932.33, self.amt=31546604.1577 
127.0.0.1 - - [25/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -
2023-10-25 16:20:18,783:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231025   155500    155959  ...         0.0        0.0       0
5952  20231025   160000    160459  ...         0.0        0.0       0
5953  20231025   160500    160959  ...         0.0        0.0       0
5954  20231025   161000    161459  ...         0.0        0.0       0
5955  20231025   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 16:20:18,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698221999, self.tradeDate='20231025', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=33796.9, self.close=33876.3, self.high=33883.8, self.low=33773.3, self.vol=932.33, self.amt=31546604.1577, ukdf['pct'].iloc[-1]=0.002622 , ukdf['amount'].iloc[-1]=31546604.1577, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-97755.07773967122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '33884.50920147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47285
self.closeSec=1698222299, self.tradeDate='20231025', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=33876.4, self.close=33912.1, self.high=33923.2, self.low=33862.8, self.vol=1001.162, self.amt=33930042.6775 
127.0.0.1 - - [25/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-25 16:25:02,505:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231025   160000    160459  ...         0.0        0.0       0
5953  20231025   160500    160959  ...         0.0        0.0       0
5954  20231025   161000    161459  ...         0.0        0.0       0
5955  20231025   161500    161959  ...         0.0        0.0       0
5956  20231025   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 16:25:02,506:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698222299, self.tradeDate='20231025', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=33876.4, self.close=33912.1, self.high=33923.2, self.low=33862.8, self.vol=1001.162, self.amt=33930042.6775, ukdf['pct'].iloc[-1]=0.001057 , ukdf['amount'].iloc[-1]=33930042.6775, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-98115.633', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '33910.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [25/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47282 

self.closeSec=1698220799, self.tradeDate='20231025', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=33852.4, self.close=33853.4, self.high=33874.8, self.low=33819.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47283 

self.closeSec=1698221099, self.tradeDate='20231025', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=33853.4, self.close=33832.9, self.high=33916.3, self.low=33818.2 
127.0.0.1 - - [25/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47284 

self.closeSec=1698221399, self.tradeDate='20231025', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=33828.3, self.close=33819.4, self.high=33849.3, self.low=33794.2 

--handleKline--:  127.0.0.1 - - [25/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -
version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47285 

self.closeSec=1698221699, self.tradeDate='20231025', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=33816.1, self.close=33787.7, self.high=33857.6, self.low=33777.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47286 

self.closeSec=1698221999, self.tradeDate='20231025', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=33796.9, self.close=33876.3, self.high=33883.8, self.low=33773.3 
127.0.0.1 - - [25/Oct/2023 16:20:10] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47287 

self.closeSec=1698222299, self.tradeDate='20231025', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=33876.4, self.close=33912.1, self.high=33923.2, self.low=33862.8 
127.0.0.1 - - [25/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-25 16:00:20,936:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231025    132959  34194.3  ...  56.666667  0.568639  0.496232
5786  20231025    135959  34005.6  ...  56.666667  0.569043  0.498677
5787  20231025    142959  34011.5  ...  57.083333  0.577462  0.495217
5788  20231025    145959  34152.4  ...  56.666667  0.574969  0.493236
5789  20231025    152959  34122.8  ...  56.666667  0.554905  0.501029

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-10-25 16:00:20,999:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.489166  0.510834       1  ...  1.085478   1.0    0.0  1.265328
538     0  0.530857  0.469143       1  ...  1.089997   1.0    0.0  1.270596
539     0  0.566192  0.433808       0  ...  1.089014   1.0    0.0  1.269450
540     0  0.525371  0.474629       0  ...  1.080946   1.0    0.0  1.260046
541     1  0.457123  0.542877       0  ...  1.080420   1.0    0.0  1.259432

[5 rows x 10 columns]
2023-10-25 16:00:21,010:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487836  0.512164       1  ...  1.085478   1.0    0.0  1.268443
46     0  0.529956  0.470044       1  ...  1.089997   1.0    0.0  1.273985
47     0  0.565861  0.434139       0  ...  1.089014   1.0    0.0  1.270874
48     0  0.525182  0.474818       0  ...  1.080946   1.0    0.0  1.260477
49     1  0.457123  0.542877       0  ...  1.080420   1.0    0.0  1.259432

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '20.978', 'enterprice': '33828.2', 'countrevence': '0', 'unrealprofit': '853.56757943766', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33868.88870147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23639 

self.closeSec=1698218999, self.tradeDate='20231025', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='34119.4', self.close='33869.9'
127.0.0.1 - - [25/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [25/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23640 

self.closeSec=1698219599, self.tradeDate='20231025', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='33876.5', self.close='33911.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23641 

self.closeSec=1698220199, self.tradeDate='20231025', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='33909', self.close='33797.6'
127.0.0.1 - - [25/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23642 

self.closeSec=1698220799, self.tradeDate='20231025', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='33799', self.close='33853.4'
127.0.0.1 - - [25/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23643 

self.closeSec=1698221399, self.tradeDate='20231025', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='33853.4', self.close='33820.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23644 

self.closeSec=1698221999, self.tradeDate='20231025', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='33816.1', self.close='33876.3'
127.0.0.1 - - [25/Oct/2023 16:20:13] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [25/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23642 

self.closeSec=1698218999, self.tradeDate='20231025', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='34119.4', self.close='33869.9'

--handleKline--: 127.0.0.1 - - [25/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23643 

self.closeSec=1698219599, self.tradeDate='20231025', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='33876.5', self.close='33911.3'
127.0.0.1 - - [25/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23644 

self.closeSec=1698220199, self.tradeDate='20231025', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='33909', self.close='33797.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23645 

self.closeSec=1698220799, self.tradeDate='20231025', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='33799', self.close='33853.4'
127.0.0.1 - - [25/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23646 

self.closeSec=1698221399, self.tradeDate='20231025', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='33853.4', self.close='33820.2'
127.0.0.1 - - [25/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23647 

self.closeSec=1698221999, self.tradeDate='20231025', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='33816.1', self.close='33876.3'
127.0.0.1 - - [25/Oct/2023 16:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23642 

self.closeSec=1698218999, self.tradeDate='20231025', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='34119.4', self.close='33869.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23643 

self.closeSec=1698219599, self.tradeDate='20231025', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='33876.5', self.close='33911.3'
127.0.0.1 - - [25/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23644 

self.closeSec=1698220199, self.tradeDate='20231025', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='33909', self.close='33797.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23645 

self.closeSec=1698220799, self.tradeDate='20231025', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='33799', self.close='33853.4'
127.0.0.1 - - [25/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23646 

self.closeSec=1698221399, self.tradeDate='20231025', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='33853.4', self.close='33820.2'
127.0.0.1 - - [25/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23647 

self.closeSec=1698221999, self.tradeDate='20231025', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='33816.1', self.close='33876.3'
127.0.0.1 - - [25/Oct/2023 16:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47284
self.closeSec=1698221999, self.tradeDate='20231025', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=33796.9, self.close=33876.3, self.high=33883.8, self.low=33773.3, self.vol=932.33, self.amt=31546604.1577 
127.0.0.1 - - [25/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -
2023-10-25 16:20:18,824:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231025   155500    155959  ...         0.0        0.0       0
5952  20231025   160000    160459  ...         0.0        0.0       0
5953  20231025   160500    160959  ...         0.0        0.0       0
5954  20231025   161000    161459  ...         0.0        0.0       0
5955  20231025   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 16:20:18,843:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698221999, self.tradeDate='20231025', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=33796.9, self.close=33876.3, self.high=33883.8, self.low=33773.3, self.vol=932.33, self.amt=31546604.1577, ukdf['pct'].iloc[-1]=0.002622 , ukdf['amount'].iloc[-1]=31546604.1577, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '261491.55225179727', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33884.50920147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47285
self.closeSec=1698222299, self.tradeDate='20231025', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=33876.4, self.close=33912.1, self.high=33923.2, self.low=33862.8, self.vol=1001.162, self.amt=33930042.6775 
127.0.0.1 - - [25/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-25 16:25:02,511:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231025   160000    160459  ...         0.0        0.0       0
5953  20231025   160500    160959  ...         0.0        0.0       0
5954  20231025   161000    161459  ...         0.0        0.0       0
5955  20231025   161500    161959  ...         0.0        0.0       0
5956  20231025   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 16:25:02,512:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698222299, self.tradeDate='20231025', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=33876.4, self.close=33912.1, self.high=33923.2, self.low=33862.8, self.vol=1001.162, self.amt=33930042.6775, ukdf['pct'].iloc[-1]=0.001057 , ukdf['amount'].iloc[-1]=33930042.6775, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '262453.1624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33910.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231025   040000    075959  1698191999  ...    721  1.339134  0.738939     1.0
722  20231025   080000    115959  1698206399  ...    722  1.245298  0.577926     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '184709.85729113787', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34004.99766667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=985
self.closeSec=1698220799, self.tradeDate='20231025', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=34003.7, self.close=33853.4, self.high=34209.4, self.low=33660.6, self.vol=54108.207, self.amt=1839218572.39983 
127.0.0.1 - - [25/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-25 16:00:01,604:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698220799, self.tradeDate='20231025', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=34003.7, self.close=33853.4, self.high=34209.4, self.low=33660.6, self.vol=54108.207, self.amt=1839218572.39983 
2023-10-25 16:00:01,624:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231024   200000    235959  ...  208256.417  7.087042e+09 -0.025305
720  20231025   000000    035959  ...  118528.892  4.012456e+09  0.003457
721  20231025   040000    075959  ...   87728.961  2.975642e+09  0.003699
722  20231025   080000    115959  ...   57592.236  1.962838e+09  0.002530
723  20231025   120000    155959  ...   54108.207  1.839219e+09 -0.004394

[5 rows x 11 columns]
2023-10-25 16:00:02,437:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231024   200000    235959  1698163199  ...    719  1.481802  0.996100     1.0
720  20231025   000000    035959  1698177599  ...    720  1.422184  0.884482     1.0
721  20231025   040000    075959  1698191999  ...    721  1.339134  0.738939     1.0
722  20231025   080000    115959  1698206399  ...    722  1.245298  0.577926     NaN
723  20231025   120000    155959  1698220799  ...    723  1.167537  0.441805     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '178588.30255648416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33856.99460256', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


