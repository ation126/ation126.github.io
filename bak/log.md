# 20230910 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34324
self.closeSec=1694333999, self.tradeDate='20230910', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25822.3, self.close=25833.9, self.high=25833.9, self.low=25822.3, self.vol=337.927, self.amt=8728770.9577 
127.0.0.1 - - [10/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-10 16:20:06,332:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230910   155500    155959  ...         0.0        0.0       0
5952  20230910   160000    160459  ...         0.0        0.0       0
5953  20230910   160500    160959  ...         0.0        0.0       0
5954  20230910   161000    161459  ...         0.0        0.0       0
5955  20230910   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 16:20:06,335:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694333999, self.tradeDate='20230910', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25822.3, self.close=25833.9, self.high=25833.9, self.low=25822.3, self.vol=337.927, self.amt=8728770.9577, ukdf['pct'].iloc[-1]=0.000445 , ukdf['amount'].iloc[-1]=8728770.9577, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14346.5652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25834.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34325
self.closeSec=1694334299, self.tradeDate='20230910', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25833.9, self.close=25837.7, self.high=25841.7, self.low=25828.7, self.vol=226.506, self.amt=5852088.7123 
2023-09-10 16:25:00,820:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230910   160000    160459  ...         0.0        0.0       0
5953  20230910   160500    160959  ...         0.0        0.0       0
5954  20230910   161000    161459  ...         0.0        0.0       0
5955  20230910   161500    161959  ...         0.0        0.0       0
5956  20230910   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 16:25:00,820:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694334299, self.tradeDate='20230910', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25833.9, self.close=25837.7, self.high=25841.7, self.low=25828.7, self.vol=226.506, self.amt=5852088.7123, ukdf['pct'].iloc[-1]=0.000147 , ukdf['amount'].iloc[-1]=5852088.7123, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14268.7918057806', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25840.2847619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [10/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34322 

self.closeSec=1694332799, self.tradeDate='20230910', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25840.2, self.close=25843.0, self.high=25844.6, self.low=25837.6 
127.0.0.1 - - [10/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34323 

self.closeSec=1694333099, self.tradeDate='20230910', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25843.1, self.close=25835.6, self.high=25845.0, self.low=25832.7 
127.0.0.1 - - [10/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34324 

self.closeSec=1694333399, self.tradeDate='20230910', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25835.6, self.close=25832.6, self.high=25838.7, self.low=25830.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34325 

self.closeSec=1694333699, self.tradeDate='20230910', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25832.7, self.close=25822.4, self.high=25832.7, self.low=25811.0 
127.0.0.1 - - [10/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34326 

self.closeSec=1694333999, self.tradeDate='20230910', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25822.3, self.close=25833.9, self.high=25833.9, self.low=25822.3 
127.0.0.1 - - [10/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34327 

self.closeSec=1694334299, self.tradeDate='20230910', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25833.9, self.close=25837.7, self.high=25841.7, self.low=25828.7 
127.0.0.1 - - [10/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-10 16:00:17,562:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230910    132959  25821.4  ...  54.583333  0.484273  0.524060
5786  20230910    135959  25841.8  ...  54.166667  0.483120  0.522049
5787  20230910    142959  25835.6  ...  54.583333  0.492006  0.514533
5788  20230910    145959  25853.5  ...  54.583333  0.486506  0.511152
5789  20230910    152959  25842.0  ...  54.583333  0.489018  0.506429

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2023-09-10 16:00:17,625:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495580  0.504420       0  ...  1.047464  -1.0    0.0  0.935665
538     1  0.491686  0.508314       1  ...  1.046734  -1.0    0.0  0.936317
539     1  0.497337  0.502663       0  ...  1.047204  -1.0    0.0  0.935897
540     1  0.494730  0.505270       1  ...  1.047001  -1.0    0.0  0.936078
541     1  0.496081  0.503919       0  ...  1.047159  -1.0    0.0  0.935937

[5 rows x 10 columns]
2023-09-10 16:00:17,637:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495073  0.504927       0  ...  1.047464  -1.0    0.0  0.935232
46     1  0.491481  0.508519       1  ...  1.046734  -1.0    0.0  0.936528
47     1  0.496952  0.503048       0  ...  1.047204  -1.0    0.0  0.932917
48     1  0.494648  0.505352       1  ...  1.047001  -1.0    0.0  0.933536
49     1  0.496081  0.503919       0  ...  1.047159  -1.0    0.0  0.935937

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '-2016.51573417848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25842.73986908', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [10/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17159 

self.closeSec=1694330999, self.tradeDate='20230910', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25862', self.close='25846.9'
127.0.0.1 - - [10/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17160 

self.closeSec=1694331599, self.tradeDate='20230910', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25846.9', self.close='25853.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17161 

self.closeSec=1694332199, self.tradeDate='20230910', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25853.1', self.close='25844.7'
127.0.0.1 - - [10/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17162 

self.closeSec=1694332799, self.tradeDate='20230910', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25844.7', self.close='25843'
127.0.0.1 - - [10/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17163 

self.closeSec=1694333399, self.tradeDate='20230910', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25843.1', self.close='25832.6'
127.0.0.1 - - [10/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17164 

self.closeSec=1694333999, self.tradeDate='20230910', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25832.7', self.close='25833.9'
127.0.0.1 - - [10/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [10/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17162 

self.closeSec=1694330999, self.tradeDate='20230910', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25862', self.close='25846.9'

--handleKline--: 127.0.0.1 - - [10/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17163 

self.closeSec=1694331599, self.tradeDate='20230910', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25846.9', self.close='25853.1'
127.0.0.1 - - [10/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17164 

self.closeSec=1694332199, self.tradeDate='20230910', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25853.1', self.close='25844.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17165 

self.closeSec=1694332799, self.tradeDate='20230910', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25844.7', self.close='25843'
127.0.0.1 - - [10/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17166 

self.closeSec=1694333399, self.tradeDate='20230910', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25843.1', self.close='25832.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17167 

self.closeSec=1694333999, self.tradeDate='20230910', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25832.7', self.close='25833.9'
127.0.0.1 - - [10/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17162 

self.closeSec=1694330999, self.tradeDate='20230910', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25862', self.close='25846.9'
127.0.0.1 - - [10/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17163 

self.closeSec=1694331599, self.tradeDate='20230910', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25846.9', self.close='25853.1'
127.0.0.1 - - [10/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17164 

self.closeSec=1694332199, self.tradeDate='20230910', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25853.1', self.close='25844.7'
127.0.0.1 - - [10/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17165 

self.closeSec=1694332799, self.tradeDate='20230910', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25844.7', self.close='25843'
127.0.0.1 - - [10/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17166 

self.closeSec=1694333399, self.tradeDate='20230910', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25843.1', self.close='25832.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17167 

self.closeSec=1694333999, self.tradeDate='20230910', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25832.7', self.close='25833.9'
127.0.0.1 - - [10/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34324
self.closeSec=1694333999, self.tradeDate='20230910', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25822.3, self.close=25833.9, self.high=25833.9, self.low=25822.3, self.vol=337.927, self.amt=8728770.9577 
127.0.0.1 - - [10/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-10 16:20:06,328:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230910   155500    155959  ...         0.0        0.0       0
5952  20230910   160000    160459  ...         0.0        0.0       0
5953  20230910   160500    160959  ...         0.0        0.0       0
5954  20230910   161000    161459  ...         0.0        0.0       0
5955  20230910   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 16:20:06,331:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694333999, self.tradeDate='20230910', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25822.3, self.close=25833.9, self.high=25833.9, self.low=25822.3, self.vol=337.927, self.amt=8728770.9577, ukdf['pct'].iloc[-1]=0.000445 , ukdf['amount'].iloc[-1]=8728770.9577, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37519.8382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25833.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34325
self.closeSec=1694334299, self.tradeDate='20230910', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25833.9, self.close=25837.7, self.high=25841.7, self.low=25828.7, self.vol=226.506, self.amt=5852088.7123 
127.0.0.1 - - [10/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-10 16:25:00,830:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230910   160000    160459  ...         0.0        0.0       0
5953  20230910   160500    160959  ...         0.0        0.0       0
5954  20230910   161000    161459  ...         0.0        0.0       0
5955  20230910   161500    161959  ...         0.0        0.0       0
5956  20230910   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 16:25:00,831:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694334299, self.tradeDate='20230910', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25833.9, self.close=25837.7, self.high=25841.7, self.low=25828.7, self.vol=226.506, self.amt=5852088.7123, ukdf['pct'].iloc[-1]=0.000147 , ukdf['amount'].iloc[-1]=5852088.7123, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37278.9876582721', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25840.2847619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230910   040000    075959  1694303999  ...    721  0.125757 -0.764330    -1.0
722  20230910   080000    115959  1694318399  ...    722  0.111707 -0.801232    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '2394.63944267625', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25850.41883375', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=715
self.closeSec=1694332799, self.tradeDate='20230910', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25851.1, self.close=25843.0, self.high=25864.2, self.low=25727.8, self.vol=21004.581, self.amt=542142366.8513 127.0.0.1 - - [10/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

2023-09-10 16:00:01,545:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694332799, self.tradeDate='20230910', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25851.1, self.close=25843.0, self.high=25864.2, self.low=25727.8, self.vol=21004.581, self.amt=542142366.8513 
2023-09-10 16:00:01,558:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230909   200000    235959  ...  19660.804  5.082788e+08  0.001203
720  20230910   000000    035959  ...  10147.831  2.625691e+08 -0.000923
721  20230910   040000    075959  ...   6773.836  1.752851e+08  0.001338
722  20230910   080000    115959  ...  10214.867  2.640082e+08 -0.001603
723  20230910   120000    155959  ...  21004.581  5.421424e+08 -0.000313

[5 rows x 11 columns]
2023-09-10 16:00:02,287:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230909   200000    235959  1694275199  ...    719  0.141142 -0.724742    -1.0
720  20230910   000000    035959  1694289599  ...    720  0.139596 -0.727565    -1.0
721  20230910   040000    075959  1694303999  ...    721  0.125757 -0.764330    -1.0
722  20230910   080000    115959  1694318399  ...    722  0.111707 -0.801232    -1.0
723  20230910   120000    155959  1694332799  ...    723  0.113988 -0.792834    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '2813.1084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25843.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


