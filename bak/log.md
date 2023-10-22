# 20231022 16:26:08

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46420
self.closeSec=1697962799, self.tradeDate='20231022', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29849.0, self.close=29835.1, self.high=29869.0, self.low=29817.5, self.vol=1309.014, self.amt=39076244.5418 
127.0.0.1 - - [22/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-10-22 16:20:07,399:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231022   155500    155959  ...         0.0        0.0       0
5952  20231022   160000    160459  ...         0.0        0.0       0
5953  20231022   160500    160959  ...         0.0        0.0       0
5954  20231022   161000    161459  ...         0.0        0.0       0
5955  20231022   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 16:20:07,402:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697962799, self.tradeDate='20231022', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29849.0, self.close=29835.1, self.high=29869.0, self.low=29817.5, self.vol=1309.014, self.amt=39076244.5418, ukdf['pct'].iloc[-1]=-0.000462 , ukdf['amount'].iloc[-1]=39076244.5418, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41429.85', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29839.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46421
self.closeSec=1697963099, self.tradeDate='20231022', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29835.1, self.close=29787.0, self.high=29842.8, self.low=29787.0, self.vol=1000.769, self.amt=29832550.5383 
127.0.0.1 - - [22/Oct/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-10-22 16:25:04,087:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231022   160000    160459  ...         0.0        0.0       0
5953  20231022   160500    160959  ...         0.0        0.0       0
5954  20231022   161000    161459  ...         0.0        0.0       0
5955  20231022   161500    161959  ...         0.0        0.0       0
5956  20231022   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 16:25:04,091:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697963099, self.tradeDate='20231022', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29835.1, self.close=29787.0, self.high=29842.8, self.low=29787.0, self.vol=1000.769, self.amt=29832550.5383, ukdf['pct'].iloc[-1]=-0.001612 , ukdf['amount'].iloc[-1]=29832550.5383, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40629.96527488998', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29782.46177473', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [22/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46418 

self.closeSec=1697961599, self.tradeDate='20231022', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29805.1, self.close=29800.7, self.high=29811.6, self.low=29770.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46419 

self.closeSec=1697961899, self.tradeDate='20231022', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29800.4, self.close=29829.1, self.high=29844.2, self.low=29766.6 
127.0.0.1 - - [22/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46420 

self.closeSec=1697962199, self.tradeDate='20231022', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29826.6, self.close=29830.4, self.high=29847.3, self.low=29810.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46421 

self.closeSec=1697962499, self.tradeDate='20231022', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29830.3, self.close=29848.9, self.high=29858.5, self.low=29822.4 
127.0.0.1 - - [22/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46422 

self.closeSec=1697962799, self.tradeDate='20231022', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29849.0, self.close=29835.1, self.high=29869.0, self.low=29817.5 
127.0.0.1 - - [22/Oct/2023 16:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46423 

self.closeSec=1697963099, self.tradeDate='20231022', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29835.1, self.close=29787.0, self.high=29842.8, self.low=29787.0 
127.0.0.1 - - [22/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-22 16:00:19,287:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231022    132959  29944.2  ...  55.000000  0.576124  0.476221
5786  20231022    135959  30000.6  ...  55.000000  0.592307  0.469754
5787  20231022    142959  30103.3  ...  55.000000  0.589150  0.464980
5788  20231022    145959  30086.5  ...  54.583333  0.583521  0.462764
5789  20231022    152959  30062.1  ...  54.583333  0.554657  0.472644

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2023-10-22 16:00:19,359:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.532588  0.467412       1  ...  0.976553   1.0    0.0  1.096391
538     0  0.550734  0.449266       0  ...  0.976109   1.0    0.0  1.095892
539     0  0.520755  0.479245       0  ...  0.975320   1.0    0.0  1.095007
540     0  0.514158  0.485842       0  ...  0.971113   1.0    0.0  1.090282
541     1  0.478116  0.521884       0  ...  0.966833   1.0    0.0  1.085478

[5 rows x 10 columns]
2023-10-22 16:00:19,371:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.532545  0.467455       1  ...  0.976553   1.0    0.0  1.097150
46     0  0.550619  0.449381       0  ...  0.976109   1.0    0.0  1.096966
47     0  0.520669  0.479331       0  ...  0.975320   1.0    0.0  1.097910
48     0  0.513763  0.486237       0  ...  0.971113   1.0    0.0  1.093037
49     1  0.478116  0.521884       0  ...  0.966833   1.0    0.0  1.085478

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.157', 'enterprice': '29765.1', 'countrevence': '0', 'unrealprofit': '738.3793', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29800', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23207 

self.closeSec=1697959799, self.tradeDate='20231022', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29961.6', self.close='29932.5'
127.0.0.1 - - [22/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23208 

self.closeSec=1697960399, self.tradeDate='20231022', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29932.5', self.close='29854'
127.0.0.1 - - [22/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23209 

self.closeSec=1697960999, self.tradeDate='20231022', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29858.8', self.close='29807.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23210 

self.closeSec=1697961599, self.tradeDate='20231022', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29806', self.close='29800.6'
127.0.0.1 - - [22/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23211 

self.closeSec=1697962199, self.tradeDate='20231022', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29800.4', self.close='29830.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23212 

self.closeSec=1697962799, self.tradeDate='20231022', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29830.3', self.close='29835.1'
127.0.0.1 - - [22/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [22/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23210 

self.closeSec=1697959799, self.tradeDate='20231022', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29961.6', self.close='29932.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23211 

self.closeSec=1697960399, self.tradeDate='20231022', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29932.5', self.close='29854'
127.0.0.1 - - [22/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [22/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23212 

self.closeSec=1697960999, self.tradeDate='20231022', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29858.8', self.close='29807.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23213 

self.closeSec=1697961599, self.tradeDate='20231022', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29806', self.close='29800.6'
127.0.0.1 - - [22/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23214 

self.closeSec=1697962199, self.tradeDate='20231022', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29800.4', self.close='29830.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23215 

self.closeSec=1697962799, self.tradeDate='20231022', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29830.3', self.close='29835.1'
127.0.0.1 - - [22/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23210 

self.closeSec=1697959799, self.tradeDate='20231022', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29961.6', self.close='29932.5'
127.0.0.1 - - [22/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23211 

self.closeSec=1697960399, self.tradeDate='20231022', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29932.5', self.close='29854'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23212 

self.closeSec=1697960999, self.tradeDate='20231022', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29858.8', self.close='29807.7'
127.0.0.1 - - [22/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23213 

self.closeSec=1697961599, self.tradeDate='20231022', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29806', self.close='29800.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23214 

self.closeSec=1697962199, self.tradeDate='20231022', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29800.4', self.close='29830.4'
127.0.0.1 - - [22/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23215 

self.closeSec=1697962799, self.tradeDate='20231022', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29830.3', self.close='29835.1'
127.0.0.1 - - [22/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46420
self.closeSec=1697962799, self.tradeDate='20231022', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29849.0, self.close=29835.1, self.high=29869.0, self.low=29817.5, self.vol=1309.014, self.amt=39076244.5418 
127.0.0.1 - - [22/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-10-22 16:20:07,399:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231022   155500    155959  ...         0.0        0.0       0
5952  20231022   160000    160459  ...         0.0        0.0       0
5953  20231022   160500    160959  ...         0.0        0.0       0
5954  20231022   161000    161459  ...         0.0        0.0       0
5955  20231022   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 16:20:07,402:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697962799, self.tradeDate='20231022', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29849.0, self.close=29835.1, self.high=29869.0, self.low=29817.5, self.vol=1309.014, self.amt=39076244.5418, ukdf['pct'].iloc[-1]=-0.000462 , ukdf['amount'].iloc[-1]=39076244.5418, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '111270.7219', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29839.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46421
self.closeSec=1697963099, self.tradeDate='20231022', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29835.1, self.close=29787.0, self.high=29842.8, self.low=29787.0, self.vol=1000.769, self.amt=29832550.5383 
127.0.0.1 - - [22/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-22 16:25:04,091:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231022   160000    160459  ...         0.0        0.0       0
5953  20231022   160500    160959  ...         0.0        0.0       0
5954  20231022   161000    161459  ...         0.0        0.0       0
5955  20231022   161500    161959  ...         0.0        0.0       0
5956  20231022   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 16:25:04,101:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697963099, self.tradeDate='20231022', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29835.1, self.close=29787.0, self.high=29842.8, self.low=29787.0, self.vol=1000.769, self.amt=29832550.5383, ukdf['pct'].iloc[-1]=-0.001612 , ukdf['amount'].iloc[-1]=29832550.5383, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '109137.40877524693', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29782.46177473', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231022   040000    075959  1697932799  ...    721  0.991878  0.550760     NaN
722  20231022   080000    115959  1697947199  ...    722  0.948324  0.469893     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '14798.9658', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29897', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=967
self.closeSec=1697961599, self.tradeDate='20231022', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29897.0, self.close=29800.6, self.high=30229.7, self.low=29606.6, self.vol=63562.834, self.amt=1903340410.10802 
127.0.0.1 - - [22/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-22 16:00:01,535:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697961599, self.tradeDate='20231022', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29897.0, self.close=29800.6, self.high=30229.7, self.low=29606.6, self.vol=63562.834, self.amt=1903340410.10802 
2023-10-22 16:00:01,572:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231021   200000    235959  ...  45910.776  1.368944e+09  0.004165
720  20231022   000000    035959  ...  95226.326  2.864382e+09  0.007016
721  20231022   040000    075959  ...  28156.934  8.439439e+08 -0.007750
722  20231022   080000    115959  ...  25140.467  7.520558e+08  0.000060
723  20231022   120000    155959  ...  63562.834  1.903340e+09 -0.003224

[5 rows x 11 columns]
2023-10-22 16:00:02,486:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231021   200000    235959  1697903999  ...    719  0.947711  0.509605     NaN
720  20231022   000000    035959  1697918399  ...    720  1.012641  0.597133     NaN
721  20231022   040000    075959  1697932799  ...    721  0.991878  0.550760     NaN
722  20231022   080000    115959  1697947199  ...    722  0.948324  0.469893     NaN
723  20231022   120000    155959  1697961599  ...    723  0.958796  0.474248     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '10826.83193962203', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29800.96426923', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


