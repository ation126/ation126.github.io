# 20230925 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38548
self.closeSec=1695601199, self.tradeDate='20230925', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26178.7, self.close=26110.1, self.high=26189.0, self.low=26101.2, self.vol=2712.932, self.amt=70932806.6633 
127.0.0.1 - - [25/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-25 08:20:06,189:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230925   075500    075959  ...         0.0        0.0       0
5856  20230925   080000    080459  ...         0.0        0.0       0
5857  20230925   080500    080959  ...         0.0        0.0       0
5858  20230925   081000    081459  ...         0.0        0.0       0
5859  20230925   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 08:20:06,195:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695601199, self.tradeDate='20230925', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26178.7, self.close=26110.1, self.high=26189.0, self.low=26101.2, self.vol=2712.932, self.amt=70932806.6633, ukdf['pct'].iloc[-1]=-0.00267 , ukdf['amount'].iloc[-1]=70932806.6633, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10451.463', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26114.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38549
self.closeSec=1695601499, self.tradeDate='20230925', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26108.4, self.close=26112.7, self.high=26149.8, self.low=25965.0, self.vol=11571.108, self.amt=301425218.42986 
2023-09-25 08:25:00,797:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230925   080000    080459  ...         0.0        0.0       0
5857  20230925   080500    080959  ...         0.0        0.0       0
5858  20230925   081000    081459  ...         0.0        0.0       0
5859  20230925   081500    081959  ...         0.0        0.0       0
5860  20230925   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 08:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695601499, self.tradeDate='20230925', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26108.4, self.close=26112.7, self.high=26149.8, self.low=25965.0, self.vol=11571.108, self.amt=301425218.42986, ukdf['pct'].iloc[-1]=0.0001 , ukdf['amount'].iloc[-1]=301425218.42986, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10402.722', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26117.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [25/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38546 

self.closeSec=1695599999, self.tradeDate='20230925', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26239.7, self.close=26235.7, self.high=26250.0, self.low=26228.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38547 

self.closeSec=1695600299, self.tradeDate='20230925', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26232.4, self.close=26200.0, self.high=26232.4, self.low=26189.4 
127.0.0.1 - - [25/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38548 

self.closeSec=1695600599, self.tradeDate='20230925', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26203.2, self.close=26172.4, self.high=26214.6, self.low=26163.2 
127.0.0.1 - - [25/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38549 

self.closeSec=1695600899, self.tradeDate='20230925', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26178.5, self.close=26180.0, self.high=26180.0, self.low=26133.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38550 

self.closeSec=1695601199, self.tradeDate='20230925', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26178.7, self.close=26110.1, self.high=26189.0, self.low=26101.2 
127.0.0.1 - - [25/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38551 

self.closeSec=1695601499, self.tradeDate='20230925', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26108.4, self.close=26112.7, self.high=26149.8, self.low=25965.0 
127.0.0.1 - - [25/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-25 08:00:16,341:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230925    052959  26489.3  ...  45.000000  0.450676  0.563843
5770  20230925    055959  26476.5  ...  45.000000  0.465341  0.561973
5771  20230925    062959  26504.3  ...  45.000000  0.457278  0.562926
5772  20230925    065959  26486.4  ...  44.583333  0.453628  0.565043
5773  20230925    072959  26478.3  ...  44.166667  0.362156  0.579258

[5 rows x 33 columns]
0.5425925925925926
acc is : 0.5425925925925926
2023-09-25 08:00:16,400:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.486635  0.513365       1  ...  0.921716  -1.0    0.0  1.016238
536     0  0.503658  0.496342       0  ...  0.922335  -1.0    0.0  1.015556
537     1  0.491126  0.508874       0  ...  0.922617  -1.0    0.0  1.015245
538     1  0.493110  0.506890       0  ...  0.931370  -1.0    0.0  1.005613
539     1  0.415562  0.584438       1  ...  0.931171  -1.0    0.0  1.005828

[5 rows x 10 columns]
2023-09-25 08:00:16,412:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486376  0.513624       1  ...  0.921716  -1.0    0.0  1.010488
46     0  0.502980  0.497020       0  ...  0.922335  -1.0    0.0  1.004753
47     1  0.490715  0.509285       0  ...  0.922617  -1.0    0.0  1.008098
48     1  0.492879  0.507121       0  ...  0.931370  -1.0    0.0  1.001933
49     1  0.415562  0.584438       1  ...  0.931171  -1.0    0.0  1.005828

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '23541.957', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26214.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19271 

self.closeSec=1695598199, self.tradeDate='20230925', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26416.7', self.close='26227.1'
127.0.0.1 - - [25/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19272 

self.closeSec=1695598799, self.tradeDate='20230925', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26228', self.close='26249.7'
127.0.0.1 - - [25/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19273 

self.closeSec=1695599399, self.tradeDate='20230925', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26248.9', self.close='26234.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19274 

self.closeSec=1695599999, self.tradeDate='20230925', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26238.8', self.close='26232.7'
127.0.0.1 - - [25/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19275 

self.closeSec=1695600599, self.tradeDate='20230925', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26232.4', self.close='26172.4'
127.0.0.1 - - [25/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19276 

self.closeSec=1695601199, self.tradeDate='20230925', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26178.5', self.close='26110.1'
127.0.0.1 - - [25/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19274 

self.closeSec=1695598199, self.tradeDate='20230925', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26416.7', self.close='26227.1'
127.0.0.1 - - [25/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19275 

self.closeSec=1695598799, self.tradeDate='20230925', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26228', self.close='26249.7'
127.0.0.1 - - [25/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19276 

self.closeSec=1695599399, self.tradeDate='20230925', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26248.9', self.close='26234.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19277 

self.closeSec=1695599999, self.tradeDate='20230925', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26238.8', self.close='26232.7'
127.0.0.1 - - [25/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19278 

self.closeSec=1695600599, self.tradeDate='20230925', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26232.4', self.close='26172.4'
127.0.0.1 - - [25/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19279 

self.closeSec=1695601199, self.tradeDate='20230925', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26178.5', self.close='26110.1'
127.0.0.1 - - [25/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19274 

self.closeSec=1695598199, self.tradeDate='20230925', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26416.7', self.close='26227.1'
127.0.0.1 - - [25/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19275 

self.closeSec=1695598799, self.tradeDate='20230925', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26228', self.close='26249.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19276 

self.closeSec=1695599399, self.tradeDate='20230925', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26248.9', self.close='26234.9'
127.0.0.1 - - [25/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19277 

self.closeSec=1695599999, self.tradeDate='20230925', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26238.8', self.close='26232.7'
127.0.0.1 - - [25/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19278 

self.closeSec=1695600599, self.tradeDate='20230925', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26232.4', self.close='26172.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19279 

self.closeSec=1695601199, self.tradeDate='20230925', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26178.5', self.close='26110.1'
127.0.0.1 - - [25/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38548
self.closeSec=1695601199, self.tradeDate='20230925', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26178.7, self.close=26110.1, self.high=26189.0, self.low=26101.2, self.vol=2712.932, self.amt=70932806.6633 
127.0.0.1 - - [25/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-25 08:20:06,194:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230925   075500    075959  ...         0.0        0.0       0
5856  20230925   080000    080459  ...         0.0        0.0       0
5857  20230925   080500    080959  ...         0.0        0.0       0
5858  20230925   081000    081459  ...         0.0        0.0       0
5859  20230925   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 08:20:06,204:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695601199, self.tradeDate='20230925', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26178.7, self.close=26110.1, self.high=26189.0, self.low=26101.2, self.vol=2712.932, self.amt=70932806.6633, ukdf['pct'].iloc[-1]=-0.00267 , ukdf['amount'].iloc[-1]=70932806.6633, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27098.0736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26114.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38549
self.closeSec=1695601499, self.tradeDate='20230925', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26108.4, self.close=26112.7, self.high=26149.8, self.low=25965.0, self.vol=11571.108, self.amt=301425218.42986 
2023-09-25 08:25:00,797:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230925   080000    080459  ...         0.0        0.0       0
5857  20230925   080500    080959  ...         0.0        0.0       0
5858  20230925   081000    081459  ...         0.0        0.0       0
5859  20230925   081500    081959  ...         0.0        0.0       0
5860  20230925   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 08:25:00,797:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695601499, self.tradeDate='20230925', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26108.4, self.close=26112.7, self.high=26149.8, self.low=25965.0, self.vol=11571.108, self.amt=301425218.42986, ukdf['pct'].iloc[-1]=0.0001 , ukdf['amount'].iloc[-1]=301425218.42986, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26968.0801', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26117.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230924   200000    235959  1695571199  ...    719  1.143992  1.302496     1.0
720  20230925   000000    035959  1695585599  ...    720  0.713147  0.265088     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-41791.08101663187', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26428.53034799', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [25/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=803
self.closeSec=1695599999, self.tradeDate='20230925', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26432.5, self.close=26232.7, self.high=26512.0, self.low=26081.0, self.vol=44285.803, self.amt=1165495943.67904 
2023-09-25 08:00:01,520:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695599999, self.tradeDate='20230925', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26432.5, self.close=26232.7, self.high=26512.0, self.low=26081.0, self.vol=44285.803, self.amt=1165495943.67904 
2023-09-25 08:00:01,537:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230924   120000    155959  ...   7565.140  2.008375e+08 -0.000286
718  20230924   160000    195959  ...   9640.884  2.562574e+08  0.001326
719  20230924   200000    235959  ...   9585.642  2.547617e+08 -0.000809
720  20230925   000000    035959  ...  70194.323  1.862757e+09 -0.005029
721  20230925   040000    075959  ...  44285.803  1.165496e+09 -0.007559

[5 rows x 11 columns]
2023-09-25 08:00:02,266:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230924   120000    155959  1695542399  ...    717  1.179588  1.453880     1.0
718  20230924   160000    195959  1695556799  ...    718  1.180396  1.420219     1.0
719  20230924   200000    235959  1695571199  ...    719  1.143992  1.302496     1.0
720  20230925   000000    035959  1695585599  ...    720  0.713147  0.265088     NaN
721  20230925   040000    075959  1695599999  ...    721  0.389653 -0.518665     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-51663.5431579971', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26234.1407967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


