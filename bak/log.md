# 20230930 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40084
self.closeSec=1696061999, self.tradeDate='20230930', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26920.4, self.close=26910.0, self.high=26924.9, self.low=26907.0, self.vol=233.002, self.amt=6271631.7167 
127.0.0.1 - - [30/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-30 16:20:06,214:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230930   155500    155959  ...         0.0        0.0       0
5952  20230930   160000    160459  ...         0.0        0.0       0
5953  20230930   160500    160959  ...         0.0        0.0       0
5954  20230930   161000    161459  ...         0.0        0.0       0
5955  20230930   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 16:20:06,219:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696061999, self.tradeDate='20230930', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26920.4, self.close=26910.0, self.high=26924.9, self.low=26907.0, self.vol=233.002, self.amt=6271631.7167, ukdf['pct'].iloc[-1]=-0.000386 , ukdf['amount'].iloc[-1]=6271631.7167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-660.0924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26912.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40085
self.closeSec=1696062299, self.tradeDate='20230930', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26910.1, self.close=26921.2, self.high=26921.2, self.low=26906.0, self.vol=229.557, self.amt=6177822.0598 
2023-09-30 16:25:00,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230930   160000    160459  ...         0.0        0.0       0
5953  20230930   160500    160959  ...         0.0        0.0       0
5954  20230930   161000    161459  ...         0.0        0.0       0
5955  20230930   161500    161959  ...         0.0        0.0       0
5956  20230930   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 16:25:00,776:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696062299, self.tradeDate='20230930', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26910.1, self.close=26921.2, self.high=26921.2, self.low=26906.0, self.vol=229.557, self.amt=6177822.0598, ukdf['pct'].iloc[-1]=0.000416 , ukdf['amount'].iloc[-1]=6177822.0598, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-784.0338', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26921.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [30/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40082 

self.closeSec=1696060799, self.tradeDate='20230930', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26916.3, self.close=26915.8, self.high=26919.8, self.low=26915.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40083 

self.closeSec=1696061099, self.tradeDate='20230930', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26915.9, self.close=26918.0, self.high=26923.5, self.low=26912.4 
127.0.0.1 - - [30/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40084 

self.closeSec=1696061399, self.tradeDate='20230930', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26918.0, self.close=26919.9, self.high=26920.0, self.low=26910.1 
127.0.0.1 - - [30/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40085 

self.closeSec=1696061699, self.tradeDate='20230930', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26920.0, self.close=26920.4, self.high=26920.4, self.low=26918.0 
127.0.0.1 - - [30/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40086 

self.closeSec=1696061999, self.tradeDate='20230930', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26920.4, self.close=26910.0, self.high=26924.9, self.low=26907.0 
127.0.0.1 - - [30/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40087 

self.closeSec=1696062299, self.tradeDate='20230930', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26910.1, self.close=26921.2, self.high=26921.2, self.low=26906.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-30 16:00:18,974:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230930    132959  26909.4  ...  51.666667  0.532306  0.518482
5786  20230930    135959  26938.0  ...  51.250000  0.528436  0.508427
5787  20230930    142959  26924.2  ...  50.833333  0.528070  0.499225
5788  20230930    145959  26922.8  ...  50.416667  0.525098  0.492103
5789  20230930    152959  26912.4  ...  50.833333  0.528870  0.483412

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-09-30 16:00:19,034:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.503686  0.496314       0  ...  0.978613  -1.0    0.0  1.009656
538     1  0.491237  0.508763       0  ...  0.978661  -1.0    0.0  1.009608
539     1  0.494349  0.505651       0  ...  0.979039  -1.0    0.0  1.009218
540     1  0.490456  0.509544       1  ...  0.978511  -1.0    0.0  1.009761
541     1  0.498829  0.501171       0  ...  0.978911  -1.0    0.0  1.009349

[5 rows x 10 columns]
2023-09-30 16:00:19,046:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503433  0.496567       0  ...  0.978613  -1.0    0.0  1.002420
46     1  0.491102  0.508898       0  ...  0.978661  -1.0    0.0  1.006441
47     1  0.494412  0.505588       0  ...  0.979039  -1.0    0.0  1.006075
48     1  0.490277  0.509723       1  ...  0.978511  -1.0    0.0  1.009413
49     1  0.498829  0.501171       0  ...  0.978911  -1.0    0.0  1.009349

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.689', 'enterprice': '27080', 'countrevence': '0', 'unrealprofit': '4076.8443', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26921.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [30/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20039 

self.closeSec=1696058999, self.tradeDate='20230930', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26908.9', self.close='26926.9'
127.0.0.1 - - [30/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20040 

self.closeSec=1696059599, self.tradeDate='20230930', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26926.9', self.close='26931.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20041 

self.closeSec=1696060199, self.tradeDate='20230930', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26931.8', self.close='26918.9'
127.0.0.1 - - [30/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20042 

self.closeSec=1696060799, self.tradeDate='20230930', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26918.9', self.close='26915.9'
127.0.0.1 - - [30/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20043 

self.closeSec=1696061399, self.tradeDate='20230930', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26915.9', self.close='26919.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20044 

self.closeSec=1696061999, self.tradeDate='20230930', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26920', self.close='26910'
127.0.0.1 - - [30/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20042 

self.closeSec=1696058999, self.tradeDate='20230930', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26908.9', self.close='26926.9'
127.0.0.1 - - [30/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20043 

self.closeSec=1696059599, self.tradeDate='20230930', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26926.9', self.close='26931.7'
127.0.0.1 - - [30/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20044 

self.closeSec=1696060199, self.tradeDate='20230930', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26931.8', self.close='26918.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20045 

self.closeSec=1696060799, self.tradeDate='20230930', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26918.9', self.close='26915.9'
127.0.0.1 - - [30/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20046 

self.closeSec=1696061399, self.tradeDate='20230930', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26915.9', self.close='26919.9'
127.0.0.1 - - [30/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20047 

self.closeSec=1696061999, self.tradeDate='20230930', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26920', self.close='26910'
127.0.0.1 - - [30/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20042 

self.closeSec=1696058999, self.tradeDate='20230930', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26908.9', self.close='26926.9'
127.0.0.1 - - [30/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20043 

self.closeSec=1696059599, self.tradeDate='20230930', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26926.9', self.close='26931.7'
127.0.0.1 - - [30/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [30/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20044 

self.closeSec=1696060199, self.tradeDate='20230930', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26931.8', self.close='26918.9'
127.0.0.1 - - [30/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20045 

self.closeSec=1696060799, self.tradeDate='20230930', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26918.9', self.close='26915.9'
127.0.0.1 - - [30/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20046 

self.closeSec=1696061399, self.tradeDate='20230930', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26915.9', self.close='26919.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20047 

self.closeSec=1696061999, self.tradeDate='20230930', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26920', self.close='26910'
127.0.0.1 - - [30/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40084
self.closeSec=1696061999, self.tradeDate='20230930', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26920.4, self.close=26910.0, self.high=26924.9, self.low=26907.0, self.vol=233.002, self.amt=6271631.7167 
127.0.0.1 - - [30/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-30 16:20:06,215:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230930   155500    155959  ...         0.0        0.0       0
5952  20230930   160000    160459  ...         0.0        0.0       0
5953  20230930   160500    160959  ...         0.0        0.0       0
5954  20230930   161000    161459  ...         0.0        0.0       0
5955  20230930   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 16:20:06,221:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696061999, self.tradeDate='20230930', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26920.4, self.close=26910.0, self.high=26924.9, self.low=26907.0, self.vol=233.002, self.amt=6271631.7167, ukdf['pct'].iloc[-1]=-0.000386 , ukdf['amount'].iloc[-1]=6271631.7167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2536.7303', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26912.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40085
self.closeSec=1696062299, self.tradeDate='20230930', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26910.1, self.close=26921.2, self.high=26921.2, self.low=26906.0, self.vol=229.557, self.amt=6177822.0598 
127.0.0.1 - - [30/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-30 16:25:00,779:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230930   160000    160459  ...         0.0        0.0       0
5953  20230930   160500    160959  ...         0.0        0.0       0
5954  20230930   161000    161459  ...         0.0        0.0       0
5955  20230930   161500    161959  ...         0.0        0.0       0
5956  20230930   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 16:25:00,779:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696062299, self.tradeDate='20230930', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26910.1, self.close=26921.2, self.high=26921.2, self.low=26906.0, self.vol=229.557, self.amt=6177822.0598, ukdf['pct'].iloc[-1]=0.000416 , ukdf['amount'].iloc[-1]=6177822.0598, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2867.2852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26921.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230930   040000    075959  1696031999  ...    721  0.827709  0.447244     NaN
722  20230930   080000    115959  1696046399  ...    722  0.743179  0.240261     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-11889.4035', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26904.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [30/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1272444.8790024, self.flagDict['side']='buy', self.tradeCount=27, self.count=835
self.closeSec=1696060799, self.tradeDate='20230930', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26904.1, self.close=26915.9, self.high=26949.5, self.low=26895.8, self.vol=9597.371, self.amt=258390684.0244 
2023-09-30 16:00:01,559:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696060799, self.tradeDate='20230930', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26904.1, self.close=26915.9, self.high=26949.5, self.low=26895.8, self.vol=9597.371, self.amt=258390684.0244 
2023-09-30 16:00:01,572:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230929   200000    235959  ...  112689.694  3.029300e+09 -0.003112
720  20230930   000000    035959  ...   33352.761  8.954973e+08  0.001455
721  20230930   040000    075959  ...   14104.960  3.793057e+08 -0.000855
722  20230930   080000    115959  ...   10406.792  2.799548e+08  0.000491
723  20230930   120000    155959  ...    9597.371  2.583907e+08  0.000439

[5 rows x 11 columns]
2023-09-30 16:00:02,211:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230929   200000    235959  1696003199  ...    719  0.913452  0.669172     1.0
720  20230930   000000    035959  1696017599  ...    720  0.900775  0.629290     1.0
721  20230930   040000    075959  1696031999  ...    721  0.827709  0.447244     NaN
722  20230930   080000    115959  1696046399  ...    722  0.743179  0.240261     NaN
723  20230930   120000    155959  1696060799  ...    723  0.665911  0.052065     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-11273.61163371841', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26917.22961059', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


