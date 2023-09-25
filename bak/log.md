# 20230926 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38740
self.closeSec=1695658799, self.tradeDate='20230926', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26356.5, self.close=26393.5, self.high=26419.4, self.low=26321.8, self.vol=5568.304, self.amt=146853821.0261 
127.0.0.1 - - [26/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-26 00:20:06,457:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230925   235500    235959  ...         0.0        0.0       0
5760  20230926   000000    000459  ...         0.0        0.0       0
5761  20230926   000500    000959  ...         0.0        0.0       0
5762  20230926   001000    001459  ...         0.0        0.0       0
5763  20230926   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 00:20:06,461:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695658799, self.tradeDate='20230926', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26356.5, self.close=26393.5, self.high=26419.4, self.low=26321.8, self.vol=5568.304, self.amt=146853821.0261, ukdf['pct'].iloc[-1]=0.001826 , ukdf['amount'].iloc[-1]=146853821.0261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6837.57545551542', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26373.90650183', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38741
self.closeSec=1695659099, self.tradeDate='20230926', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26388.9, self.close=26328.8, self.high=26393.4, self.low=26324.4, self.vol=2958.646, self.amt=77970192.1496 
2023-09-26 00:25:00,799:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230926   000000    000459  ...         0.0        0.0       0
5761  20230926   000500    000959  ...         0.0        0.0       0
5762  20230926   001000    001459  ...         0.0        0.0       0
5763  20230926   001500    001959  ...         0.0        0.0       0
5764  20230926   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 00:25:00,799:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695659099, self.tradeDate='20230926', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26388.9, self.close=26328.8, self.high=26393.4, self.low=26324.4, self.vol=2958.646, self.amt=77970192.1496, ukdf['pct'].iloc[-1]=-0.002451 , ukdf['amount'].iloc[-1]=77970192.1496, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7499.58755210874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26326.36865201', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [26/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230921' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [26/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38740 

self.closeSec=1695658199, self.tradeDate='20230926', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26284.1, self.close=26278.9, self.high=26293.0, self.low=26257.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38741 

self.closeSec=1695658499, self.tradeDate='20230926', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26283.5, self.close=26345.4, self.high=26350.0, self.low=26283.4 
127.0.0.1 - - [26/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38742 

self.closeSec=1695658799, self.tradeDate='20230926', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26356.5, self.close=26393.5, self.high=26419.4, self.low=26321.8 
127.0.0.1 - - [26/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38743 

self.closeSec=1695659099, self.tradeDate='20230926', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26388.9, self.close=26328.8, self.high=26393.4, self.low=26324.4 
127.0.0.1 - - [26/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-26 00:00:18,629:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230925    212959  26092.0  ...  45.416667  0.416594  0.775399
5802  20230925    215959  26142.8  ...  45.416667  0.422523  0.774207
5803  20230925    222959  26153.0  ...  45.000000  0.409465  0.774947
5804  20230925    225959  26107.9  ...  45.416667  0.415784  0.772797
5805  20230925    232959  26123.4  ...  45.833333  0.457016  0.755586

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-09-26 00:00:18,688:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510474  0.489526       1  ...  0.964830  -1.0    0.0  0.993191
540     0  0.504466  0.495534       0  ...  0.966487  -1.0    0.0  0.991486
541     1  0.482762  0.517238       1  ...  0.965917  -1.0    0.0  0.992071
542     1  0.498829  0.501171       1  ...  0.961957  -1.0    0.0  0.996138
543     0  0.527473  0.472527       0  ...  0.961986  -1.0    0.0  0.996107

[5 rows x 10 columns]
2023-09-26 00:00:18,699:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510659  0.489341       1  ...  0.964830  -1.0    0.0  0.996339
46     0  0.504477  0.495523       0  ...  0.966487  -1.0    0.0  0.993425
47     1  0.482955  0.517045       1  ...  0.965917  -1.0    0.0  0.994931
48     1  0.499019  0.500981       1  ...  0.961957  -1.0    0.0  0.999010
49     0  0.527473  0.472527       0  ...  0.961986  -1.0    0.0  0.996107

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '22969.516', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26236.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19367 

self.closeSec=1695655799, self.tradeDate='20230925', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26180', self.close='26230.5'
127.0.0.1 - - [25/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19368 

self.closeSec=1695656399, self.tradeDate='20230925', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26243.2', self.close='26208.5'
127.0.0.1 - - [25/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19369 

self.closeSec=1695656999, self.tradeDate='20230925', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26208.4', self.close='26228'
127.0.0.1 - - [26/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19370 

self.closeSec=1695657599, self.tradeDate='20230925', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26227.4', self.close='26230.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19371 

self.closeSec=1695658199, self.tradeDate='20230926', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26231', self.close='26278.9'
127.0.0.1 - - [26/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19372 

self.closeSec=1695658799, self.tradeDate='20230926', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26283.5', self.close='26393.5'
127.0.0.1 - - [26/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19370 

self.closeSec=1695655799, self.tradeDate='20230925', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26180', self.close='26230.5'
127.0.0.1 - - [25/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19371 

self.closeSec=1695656399, self.tradeDate='20230925', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26243.2', self.close='26208.5'
127.0.0.1 - - [25/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19372 

self.closeSec=1695656999, self.tradeDate='20230925', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26208.4', self.close='26228'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19373 

self.closeSec=1695657599, self.tradeDate='20230925', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26227.4', self.close='26230.9'
127.0.0.1 - - [26/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19374 

self.closeSec=1695658199, self.tradeDate='20230926', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26231', self.close='26278.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19375 

self.closeSec=1695658799, self.tradeDate='20230926', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26283.5', self.close='26393.5'
127.0.0.1 - - [26/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19370 

self.closeSec=1695655799, self.tradeDate='20230925', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26180', self.close='26230.5'

--handleKline--: 127.0.0.1 - - [25/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19371 

self.closeSec=1695656399, self.tradeDate='20230925', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26243.2', self.close='26208.5'

--handleKline--: 127.0.0.1 - - [25/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19372 

self.closeSec=1695656999, self.tradeDate='20230925', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26208.4', self.close='26228'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19373 

self.closeSec=1695657599, self.tradeDate='20230925', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26227.4', self.close='26230.9'
127.0.0.1 - - [26/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19374 

self.closeSec=1695658199, self.tradeDate='20230926', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26231', self.close='26278.9'
127.0.0.1 - - [26/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19375 

self.closeSec=1695658799, self.tradeDate='20230926', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26283.5', self.close='26393.5'
127.0.0.1 - - [26/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38740
self.closeSec=1695658799, self.tradeDate='20230926', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26356.5, self.close=26393.5, self.high=26419.4, self.low=26321.8, self.vol=5568.304, self.amt=146853821.0261 
127.0.0.1 - - [26/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-26 00:20:06,462:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230925   235500    235959  ...         0.0        0.0       0
5760  20230926   000000    000459  ...         0.0        0.0       0
5761  20230926   000500    000959  ...         0.0        0.0       0
5762  20230926   001000    001459  ...         0.0        0.0       0
5763  20230926   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 00:20:06,471:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695658799, self.tradeDate='20230926', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26356.5, self.close=26393.5, self.high=26419.4, self.low=26321.8, self.vol=5568.304, self.amt=146853821.0261, ukdf['pct'].iloc[-1]=0.001826 , ukdf['amount'].iloc[-1]=146853821.0261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-17459.74261553197', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26373.90650183', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38741
self.closeSec=1695659099, self.tradeDate='20230926', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26388.9, self.close=26328.8, self.high=26393.4, self.low=26324.4, self.vol=2958.646, self.amt=77970192.1496 
127.0.0.1 - - [26/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-26 00:25:00,788:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230926   000000    000459  ...         0.0        0.0       0
5761  20230926   000500    000959  ...         0.0        0.0       0
5762  20230926   001000    001459  ...         0.0        0.0       0
5763  20230926   001500    001959  ...         0.0        0.0       0
5764  20230926   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 00:25:00,788:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695659099, self.tradeDate='20230926', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26388.9, self.close=26328.8, self.high=26393.4, self.low=26324.4, self.vol=2958.646, self.amt=77970192.1496, ukdf['pct'].iloc[-1]=-0.002451 , ukdf['amount'].iloc[-1]=77970192.1496, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-19225.34589569659', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26326.36865201', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230925   120000    155959  1695628799  ...    723  0.251184 -0.866226    -1.0
724  20230925   160000    195959  1695643199  ...    724  0.218555 -0.951504    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '4319.3356', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26063.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=807
self.closeSec=1695657599, self.tradeDate='20230925', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26064.5, self.close=26229.7, self.high=26289.9, self.low=25977.0, self.vol=58168.921, self.amt=1520600070.04374 
2023-09-26 00:00:01,543:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695657599, self.tradeDate='20230925', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26064.5, self.close=26229.7, self.high=26289.9, self.low=25977.0, self.vol=58168.921, self.amt=1520600070.04374 
2023-09-26 00:00:01,559:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230925   040000    075959  ...  44285.803  1.165496e+09 -0.007559
722  20230925   080000    115959  ...  70352.779  1.840985e+09 -0.003206
723  20230925   120000    155959  ...  29109.864  7.602567e+08  0.001078
724  20230925   160000    195959  ...  33858.819  8.832737e+08 -0.004290
725  20230925   200000    235959  ...  58168.921  1.520600e+09  0.006338

[5 rows x 11 columns]
2023-09-26 00:00:02,384:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230925   040000    075959  1695599999  ...    721  0.389653 -0.518665     NaN
722  20230925   080000    115959  1695614399  ...    722  0.259476 -0.839195    -1.0
723  20230925   120000    155959  1695628799  ...    723  0.251184 -0.866226    -1.0
724  20230925   160000    195959  1695643199  ...    724  0.218555 -0.951504    -1.0
725  20230925   200000    235959  1695657599  ...    725  0.217799 -0.959629    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-4167.0676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26231', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


