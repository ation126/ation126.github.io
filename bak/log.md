# 20230415 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40053
self.closeSec=1681546799, self.tradeDate='20230415', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30402.8, self.close=30395.4, self.high=30411.2, self.low=30395.4, self.vol=317.091, self.amt=9641199.5853 
127.0.0.1 - - [15/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-15 16:20:06,980:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230415   155500    155959  ...         0.0        0.0       0
5945  20230415   160000    160459  ...         0.0        0.0       0
5946  20230415   160500    160959  ...         0.0        0.0       0
5947  20230415   161000    161459  ...         0.0        0.0       0
5948  20230415   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 16:20:06,985:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681546799, self.tradeDate='20230415', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30402.8, self.close=30395.4, self.high=30411.2, self.low=30395.4, self.vol=317.091, self.amt=9641199.5853, ukdf['pct'].iloc[-1]=-0.000247 , ukdf['amount'].iloc[-1]=9641199.5853, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-834369.44804514848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30394.78537698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40054
self.closeSec=1681547099, self.tradeDate='20230415', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30395.4, self.close=30410.2, self.high=30413.1, self.low=30392.9, self.vol=266.735, self.amt=8109504.3735 
2023-04-15 16:25:01,599:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230415   160000    160459  ...         0.0        0.0       0
5946  20230415   160500    160959  ...         0.0        0.0       0
5947  20230415   161000    161459  ...         0.0        0.0       0
5948  20230415   161500    161959  ...         0.0        0.0       0
5949  20230415   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 16:25:01,600:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681547099, self.tradeDate='20230415', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30395.4, self.close=30410.2, self.high=30413.1, self.low=30392.9, self.vol=266.735, self.amt=8109504.3735, ukdf['pct'].iloc[-1]=0.000487 , ukdf['amount'].iloc[-1]=8109504.3735, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-835297.0384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30410.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40615 

self.closeSec=1681545599, self.tradeDate='20230415', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30420.0, self.close=30416.6, self.high=30464.0, self.low=30416.6 
127.0.0.1 - - [15/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40616 

self.closeSec=1681545899, self.tradeDate='20230415', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=30416.6, self.close=30431.2, self.high=30435.0, self.low=30416.6 
127.0.0.1 - - [15/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40617 

self.closeSec=1681546199, self.tradeDate='20230415', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=30431.3, self.close=30413.6, self.high=30431.3, self.low=30407.8 
127.0.0.1 - - [15/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40618 

self.closeSec=1681546499, self.tradeDate='20230415', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=30413.6, self.close=30402.9, self.high=30413.7, self.low=30402.2 
127.0.0.1 - - [15/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40619 

self.closeSec=1681546799, self.tradeDate='20230415', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30402.8, self.close=30395.4, self.high=30411.2, self.low=30395.4 
127.0.0.1 - - [15/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40620 

self.closeSec=1681547099, self.tradeDate='20230415', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30395.4, self.close=30410.2, self.high=30413.1, self.low=30392.9 
127.0.0.1 - - [15/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-15 16:00:34,688:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230415    132959  30348.1  ...  56.666667  0.506691  0.557477
5786  20230415    135959  30390.7  ...  57.083333  0.510441  0.551641
5787  20230415    142959  30410.0  ...  56.666667  0.503357  0.548760
5788  20230415    145959  30374.7  ...  57.083333  0.503677  0.545953
5789  20230415    152959  30376.5  ...  57.083333  0.512398  0.540158

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-04-15 16:00:34,855:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.521192  0.478808       1  ...  1.035411  -1.0    0.0  1.095994
538     0  0.518078  0.481922       0  ...  1.036610  -1.0    0.0  1.094725
539     0  0.506424  0.493576       1  ...  1.036555  -1.0    0.0  1.094783
540     0  0.520043  0.479957       1  ...  1.035068  -1.0    0.0  1.096354
541     0  0.529955  0.470045       0  ...  1.035183  -1.0    0.0  1.096232

[5 rows x 10 columns]
2023-04-15 16:00:34,886:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.520140  0.479860       1  ...  1.019227  -1.0    0.0  1.090511
46     0  0.517550  0.482450       0  ...  1.036610  -1.0    0.0  1.093020
47     0  0.505499  0.494501       1  ...  1.020353  -1.0    0.0  1.090374
48     0  0.519598  0.480402       1  ...  1.035068  -1.0    0.0  1.094792
49     0  0.529955  0.470045       0  ...  1.035183  -1.0    0.0  1.096232

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20305 

self.closeSec=1681543799, self.tradeDate='20230415', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30395.6', self.close='30420'
127.0.0.1 - - [15/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20306 

self.closeSec=1681544399, self.tradeDate='20230415', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30420.4', self.close='30380.4'
127.0.0.1 - - [15/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20307 

self.closeSec=1681544999, self.tradeDate='20230415', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30380.5', self.close='30386.5'
127.0.0.1 - - [15/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20308 

self.closeSec=1681545599, self.tradeDate='20230415', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30386.6', self.close='30416.6'
127.0.0.1 - - [15/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20309 

self.closeSec=1681546199, self.tradeDate='20230415', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30416.6', self.close='30413.6'
127.0.0.1 - - [15/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20310 

self.closeSec=1681546799, self.tradeDate='20230415', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30413.6', self.close='30395.4'
127.0.0.1 - - [15/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [15/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20306 

self.closeSec=1681543799, self.tradeDate='20230415', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30395.6', self.close='30420'
127.0.0.1 - - [15/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20307 

self.closeSec=1681544399, self.tradeDate='20230415', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30420.4', self.close='30380.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20308 

self.closeSec=1681544999, self.tradeDate='20230415', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30380.5', self.close='30386.5'
127.0.0.1 - - [15/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20309 

self.closeSec=1681545599, self.tradeDate='20230415', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30386.6', self.close='30416.6'
127.0.0.1 - - [15/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20310 

self.closeSec=1681546199, self.tradeDate='20230415', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30416.6', self.close='30413.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20311 

self.closeSec=1681546799, self.tradeDate='20230415', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30413.6', self.close='30395.4'
127.0.0.1 - - [15/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20306 

self.closeSec=1681543799, self.tradeDate='20230415', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30395.6', self.close='30420'
127.0.0.1 - - [15/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20307 

self.closeSec=1681544399, self.tradeDate='20230415', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30420.4', self.close='30380.4'
127.0.0.1 - - [15/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20308 

self.closeSec=1681544999, self.tradeDate='20230415', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30380.5', self.close='30386.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20309 

self.closeSec=1681545599, self.tradeDate='20230415', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30386.6', self.close='30416.6'
127.0.0.1 - - [15/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20310 

self.closeSec=1681546199, self.tradeDate='20230415', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30416.6', self.close='30413.6'
127.0.0.1 - - [15/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20311 

self.closeSec=1681546799, self.tradeDate='20230415', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30413.6', self.close='30395.4'
127.0.0.1 - - [15/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36051
self.closeSec=1681546799, self.tradeDate='20230415', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30402.8, self.close=30395.4, self.high=30411.2, self.low=30395.4, self.vol=317.091, self.amt=9641199.5853 
127.0.0.1 - - [15/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-15 16:20:06,793:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230415   155500    155959  ...         0.0        0.0       0
5945  20230415   160000    160459  ...         0.0        0.0       0
5946  20230415   160500    160959  ...         0.0        0.0       0
5947  20230415   161000    161459  ...         0.0        0.0       0
5948  20230415   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 16:20:06,805:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681546799, self.tradeDate='20230415', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30402.8, self.close=30395.4, self.high=30411.2, self.low=30395.4, self.vol=317.091, self.amt=9641199.5853, ukdf['pct'].iloc[-1]=-0.000247 , ukdf['amount'].iloc[-1]=9641199.5853, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36052
self.closeSec=1681547099, self.tradeDate='20230415', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30395.4, self.close=30410.2, self.high=30413.1, self.low=30392.9, self.vol=266.735, self.amt=8109504.3735 
127.0.0.1 - - [15/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-15 16:25:01,602:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230415   160000    160459  ...         0.0        0.0       0
5946  20230415   160500    160959  ...         0.0        0.0       0
5947  20230415   161000    161459  ...         0.0        0.0       0
5948  20230415   161500    161959  ...         0.0        0.0       0
5949  20230415   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 16:25:01,603:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681547099, self.tradeDate='20230415', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30395.4, self.close=30410.2, self.high=30413.1, self.low=30392.9, self.vol=266.735, self.amt=8109504.3735, ukdf['pct'].iloc[-1]=0.000487 , ukdf['amount'].iloc[-1]=8109504.3735, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230415   040000    075959  1681516799  ...    721  0.279484 -0.500986     NaN
722  20230415   080000    115959  1681531199  ...    722  0.291453 -0.467049     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '110134.458', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30367.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [15/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=846
self.closeSec=1681545599, self.tradeDate='20230415', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30367.0, self.close=30416.6, self.high=30464.0, self.low=30327.4, self.vol=20229.732, self.amt=614648294.3839 
2023-04-15 16:00:02,059:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681545599, self.tradeDate='20230415', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30367.0, self.close=30416.6, self.high=30464.0, self.low=30327.4, self.vol=20229.732, self.amt=614648294.3839 
2023-04-15 16:00:02,099:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230414   200000    235959  ...  173876.177  5.301979e+09 -0.018295
720  20230415   000000    035959  ...  102233.968  3.085413e+09  0.002796
721  20230415   040000    075959  ...   48626.219  1.479058e+09  0.004681
722  20230415   080000    115959  ...   41220.216  1.253534e+09 -0.002824
723  20230415   120000    155959  ...   20229.732  6.146483e+08  0.001630

[5 rows x 11 columns]
2023-04-15 16:00:04,524:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230414   200000    235959  1681487999  ...    719  0.537512  0.042998     NaN
720  20230415   000000    035959  1681502399  ...    720  0.344675 -0.368287     NaN
721  20230415   040000    075959  1681516799  ...    721  0.279484 -0.500986     NaN
722  20230415   080000    115959  1681531199  ...    722  0.291453 -0.467049     NaN
723  20230415   120000    155959  1681545599  ...    723  0.409521 -0.207092     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '112954.7346049548', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30420.80421032', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


