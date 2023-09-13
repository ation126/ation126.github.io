# 20230913 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35188
self.closeSec=1694593199, self.tradeDate='20230913', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25920.3, self.close=25920.2, self.high=25930.2, self.low=25900.1, self.vol=615.314, self.amt=15943513.3568 
127.0.0.1 - - [13/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-13 16:20:06,110:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230913   155500    155959  ...         0.0        0.0       0
5952  20230913   160000    160459  ...         0.0        0.0       0
5953  20230913   160500    160959  ...         0.0        0.0       0
5954  20230913   161000    161459  ...         0.0        0.0       0
5955  20230913   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 16:20:06,116:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694593199, self.tradeDate='20230913', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25920.3, self.close=25920.2, self.high=25930.2, self.low=25900.1, self.vol=615.314, self.amt=15943513.3568, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=15943513.3568, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13182.34981454754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25918.30012821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35189
self.closeSec=1694593499, self.tradeDate='20230913', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25920.2, self.close=25948.7, self.high=25948.7, self.low=25917.9, self.vol=611.297, self.amt=15854787.0159 
2023-09-13 16:25:00,821:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230913   160000    160459  ...         0.0        0.0       0
5953  20230913   160500    160959  ...         0.0        0.0       0
5954  20230913   161000    161459  ...         0.0        0.0       0
5955  20230913   161500    161959  ...         0.0        0.0       0
5956  20230913   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 16:25:00,821:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694593499, self.tradeDate='20230913', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25920.2, self.close=25948.7, self.high=25948.7, self.low=25917.9, self.vol=611.297, self.amt=15854787.0159, ukdf['pct'].iloc[-1]=0.0011 , ukdf['amount'].iloc[-1]=15854787.0159, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12759.0012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25948.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [13/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35186 

self.closeSec=1694591999, self.tradeDate='20230913', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25892.1, self.close=25867.0, self.high=25900.2, self.low=25844.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35187 

self.closeSec=1694592299, self.tradeDate='20230913', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25865.7, self.close=25898.2, self.high=25903.0, self.low=25850.8 
127.0.0.1 - - [13/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35188 

self.closeSec=1694592599, self.tradeDate='20230913', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25898.1, self.close=25904.1, self.high=25913.7, self.low=25890.0 
127.0.0.1 - - [13/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [13/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -
version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35189 

self.closeSec=1694592899, self.tradeDate='20230913', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25906.0, self.close=25920.3, self.high=25934.5, self.low=25906.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35190 

self.closeSec=1694593199, self.tradeDate='20230913', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25920.3, self.close=25920.2, self.high=25930.2, self.low=25900.1 
127.0.0.1 - - [13/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35191 

self.closeSec=1694593499, self.tradeDate='20230913', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25920.2, self.close=25948.7, self.high=25948.7, self.low=25917.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-13 16:00:16,340:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230913    132959  25912.9  ...  47.916667  0.508701  0.589261
5786  20230913    135959  25863.2  ...  48.333333  0.512726  0.605688
5787  20230913    142959  25886.4  ...  48.333333  0.516766  0.619164
5788  20230913    145959  25909.4  ...  48.750000  0.523105  0.628826
5789  20230913    152959  25945.7  ...  48.750000  0.525555  0.636720

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-09-13 16:00:16,398:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494361  0.505639       1  ...  1.005232  -1.0    0.0  1.004229
538     0  0.514087  0.485913       1  ...  1.004335  -1.0    0.0  1.005125
539     0  0.516599  0.483401       1  ...  1.002928  -1.0    0.0  1.006533
540     0  0.519461  0.480539       1  ...  1.002387  -1.0    0.0  1.007076
541     0  0.518209  0.481791       0  ...  1.005970  -1.0    0.0  1.003476

[5 rows x 10 columns]
2023-09-13 16:00:16,409:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495238  0.504762       1  ...  1.005232  -1.0    0.0  1.005301
46     0  0.514729  0.485271       1  ...  1.004335  -1.0    0.0  1.004532
47     0  0.516740  0.483260       1  ...  1.002928  -1.0    0.0  1.005823
48     0  0.519569  0.480431       1  ...  1.002387  -1.0    0.0  1.005414
49     0  0.518209  0.481791       0  ...  1.005970  -1.0    0.0  1.003476

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.172', 'enterprice': '26023.2', 'countrevence': '0', 'unrealprofit': '4639.57382495424', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25858.51258608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17591 

self.closeSec=1694590199, self.tradeDate='20230913', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25951.2', self.close='25959.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17592 

self.closeSec=1694590799, self.tradeDate='20230913', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25959.8', self.close='26057.9'
127.0.0.1 - - [13/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [13/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17593 

self.closeSec=1694591399, self.tradeDate='20230913', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26052.5', self.close='25955.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17594 

self.closeSec=1694591999, self.tradeDate='20230913', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25957.8', self.close='25865.8'
127.0.0.1 - - [13/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17595 

self.closeSec=1694592599, self.tradeDate='20230913', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25865.7', self.close='25904.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17596 

self.closeSec=1694593199, self.tradeDate='20230913', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25906', self.close='25920.2'
127.0.0.1 - - [13/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [13/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17594 

self.closeSec=1694590199, self.tradeDate='20230913', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25951.2', self.close='25959.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17595 

self.closeSec=1694590799, self.tradeDate='20230913', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25959.8', self.close='26057.9'
127.0.0.1 - - [13/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17596 

self.closeSec=1694591399, self.tradeDate='20230913', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26052.5', self.close='25955.8'
127.0.0.1 - - [13/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17597 

self.closeSec=1694591999, self.tradeDate='20230913', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25957.8', self.close='25865.8'
127.0.0.1 - - [13/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17598 

self.closeSec=1694592599, self.tradeDate='20230913', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25865.7', self.close='25904.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17599 

self.closeSec=1694593199, self.tradeDate='20230913', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25906', self.close='25920.2'
127.0.0.1 - - [13/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17594 

self.closeSec=1694590199, self.tradeDate='20230913', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25951.2', self.close='25959.8'
127.0.0.1 - - [13/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [13/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17595 

self.closeSec=1694590799, self.tradeDate='20230913', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25959.8', self.close='26057.9'
127.0.0.1 - - [13/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17596 

self.closeSec=1694591399, self.tradeDate='20230913', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26052.5', self.close='25955.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17597 

self.closeSec=1694591999, self.tradeDate='20230913', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25957.8', self.close='25865.8'
127.0.0.1 - - [13/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17598 

self.closeSec=1694592599, self.tradeDate='20230913', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25865.7', self.close='25904.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17599 

self.closeSec=1694593199, self.tradeDate='20230913', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25906', self.close='25920.2'
127.0.0.1 - - [13/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35188
self.closeSec=1694593199, self.tradeDate='20230913', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25920.3, self.close=25920.2, self.high=25930.2, self.low=25900.1, self.vol=615.314, self.amt=15943513.3568 
127.0.0.1 - - [13/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-13 16:20:06,112:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230913   155500    155959  ...         0.0        0.0       0
5952  20230913   160000    160459  ...         0.0        0.0       0
5953  20230913   160500    160959  ...         0.0        0.0       0
5954  20230913   161000    161459  ...         0.0        0.0       0
5955  20230913   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 16:20:06,119:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694593199, self.tradeDate='20230913', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25920.3, self.close=25920.2, self.high=25930.2, self.low=25900.1, self.vol=615.314, self.amt=15943513.3568, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=15943513.3568, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-34381.41893815239', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25918.30012821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35189
self.closeSec=1694593499, self.tradeDate='20230913', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25920.2, self.close=25948.7, self.high=25948.7, self.low=25917.9, self.vol=611.297, self.amt=15854787.0159 
127.0.0.1 - - [13/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-13 16:25:00,809:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230913   160000    160459  ...         0.0        0.0       0
5953  20230913   160500    160959  ...         0.0        0.0       0
5954  20230913   161000    161459  ...         0.0        0.0       0
5955  20230913   161500    161959  ...         0.0        0.0       0
5956  20230913   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 16:25:00,809:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694593499, self.tradeDate='20230913', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25920.2, self.close=25948.7, self.high=25948.7, self.low=25917.9, self.vol=611.297, self.amt=15854787.0159, ukdf['pct'].iloc[-1]=0.0011 , ukdf['amount'].iloc[-1]=15854787.0159, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-33252.3373', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25948.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230913   040000    075959  1694563199  ...    721  0.182931 -0.601752    -1.0
722  20230913   080000    115959  1694577599  ...    722  0.191800 -0.585802     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '1394.73667753245', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25867.90668315', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=733
self.closeSec=1694591999, self.tradeDate='20230913', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25868.3, self.close=25867.0, self.high=26099.5, self.low=25835.0, self.vol=46656.095, self.amt=1210203880.62364 
127.0.0.1 - - [13/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-13 16:00:01,539:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694591999, self.tradeDate='20230913', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25868.3, self.close=25867.0, self.high=26099.5, self.low=25835.0, self.vol=46656.095, self.amt=1210203880.62364 
2023-09-13 16:00:01,553:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230912   200000    235959  ...  104596.895  2.736354e+09  0.004052
720  20230913   000000    035959  ...  134082.041  3.505512e+09 -0.005357
721  20230913   040000    075959  ...   40646.871  1.054920e+09 -0.008683
722  20230913   080000    115959  ...   33520.940  8.677007e+08  0.001650
723  20230913   120000    155959  ...   46656.095  1.210204e+09 -0.000054

[5 rows x 11 columns]
2023-09-13 16:00:02,242:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230912   200000    235959  1694534399  ...    719  0.154263 -0.664905    -1.0
720  20230913   000000    035959  1694548799  ...    720  0.174697 -0.616181    -1.0
721  20230913   040000    075959  1694563199  ...    721  0.182931 -0.601752    -1.0
722  20230913   080000    115959  1694577599  ...    722  0.191800 -0.585802     NaN
723  20230913   120000    155959  1694591999  ...    723  0.210407 -0.542773     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '1514.28216044835', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25865.81588645', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


