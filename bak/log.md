# 20230927 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39220
self.closeSec=1695802799, self.tradeDate='20230927', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26223.4, self.close=26220.9, self.high=26228.0, self.low=26220.9, self.vol=224.843, self.amt=5896541.9314 
127.0.0.1 - - [27/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-27 16:20:06,012:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230927   155500    155959  ...         0.0        0.0       0
5952  20230927   160000    160459  ...         0.0        0.0       0
5953  20230927   160500    160959  ...         0.0        0.0       0
5954  20230927   161000    161459  ...         0.0        0.0       0
5955  20230927   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 16:20:06,015:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695802799, self.tradeDate='20230927', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26223.4, self.close=26220.9, self.high=26228.0, self.low=26220.9, self.vol=224.843, self.amt=5896541.9314, ukdf['pct'].iloc[-1]=-9.5e-05 , ukdf['amount'].iloc[-1]=5896541.9314, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8934.83786477238', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26223.30601287', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39221
self.closeSec=1695803099, self.tradeDate='20230927', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26221.0, self.close=26217.3, self.high=26223.5, self.low=26213.2, self.vol=300.689, self.amt=7883646.2293 
127.0.0.1 - - [27/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-27 16:25:00,801:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230927   160000    160459  ...         0.0        0.0       0
5953  20230927   160500    160959  ...         0.0        0.0       0
5954  20230927   161000    161459  ...         0.0        0.0       0
5955  20230927   161500    161959  ...         0.0        0.0       0
5956  20230927   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 16:25:00,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695803099, self.tradeDate='20230927', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26221.0, self.close=26217.3, self.high=26223.5, self.low=26213.2, self.vol=300.689, self.amt=7883646.2293, ukdf['pct'].iloc[-1]=-0.000137 , ukdf['amount'].iloc[-1]=7883646.2293, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9021.2628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26217.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [27/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39218 

self.closeSec=1695801599, self.tradeDate='20230927', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26236.4, self.close=26233.4, self.high=26237.5, self.low=26233.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39219 

self.closeSec=1695801899, self.tradeDate='20230927', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26233.4, self.close=26225.6, self.high=26233.4, self.low=26225.5 
127.0.0.1 - - [27/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39220 

self.closeSec=1695802199, self.tradeDate='20230927', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26225.6, self.close=26232.2, self.high=26232.2, self.low=26222.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39221 

self.closeSec=1695802499, self.tradeDate='20230927', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26232.2, self.close=26223.4, self.high=26232.2, self.low=26221.9 
127.0.0.1 - - [27/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39222 

self.closeSec=1695802799, self.tradeDate='20230927', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26223.4, self.close=26220.9, self.high=26228.0, self.low=26220.9 
127.0.0.1 - - [27/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39223 

self.closeSec=1695803099, self.tradeDate='20230927', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26221.0, self.close=26217.3, self.high=26223.5, self.low=26213.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-27 16:00:17,482:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230927    132959  26235.0  ...  46.666667  0.491459  0.484522
5786  20230927    135959  26234.7  ...  46.666667  0.495308  0.467660
5787  20230927    142959  26245.0  ...  46.666667  0.487845  0.458027
5788  20230927    145959  26224.6  ...  47.083333  0.495750  0.442812
5789  20230927    152959  26245.5  ...  47.083333  0.489596  0.433578

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-09-27 16:00:17,544:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.491211  0.508789       1  ...  0.979229  -1.0    0.0  0.985942
538     1  0.493390  0.506610       0  ...  0.979990  -1.0    0.0  0.985176
539     1  0.482072  0.517928       1  ...  0.979213  -1.0    0.0  0.985958
540     1  0.496562  0.503438       0  ...  0.979833  -1.0    0.0  0.985334
541     1  0.485543  0.514457       1  ...  0.979661  -1.0    0.0  0.985507

[5 rows x 10 columns]
2023-09-27 16:00:17,556:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490799  0.509201       1  ...  0.974810  -1.0    0.0  0.980682
46     1  0.493209  0.506791       0  ...  0.979990  -1.0    0.0  0.983705
47     1  0.482092  0.517908       1  ...  0.979213  -1.0    0.0  0.987011
48     1  0.495871  0.504129       0  ...  0.979833  -1.0    0.0  0.984276
49     1  0.485543  0.514457       1  ...  0.979661  -1.0    0.0  0.985507

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '23000.3431889945', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26235.39909665', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [27/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19607 

self.closeSec=1695799799, self.tradeDate='20230927', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26240', self.close='26228.8'
127.0.0.1 - - [27/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19608 

self.closeSec=1695800399, self.tradeDate='20230927', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26228.8', self.close='26236.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19609 

self.closeSec=1695800999, self.tradeDate='20230927', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26236.2', self.close='26234.1'
127.0.0.1 - - [27/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19610 

self.closeSec=1695801599, self.tradeDate='20230927', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26234.1', self.close='26233.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19611 

self.closeSec=1695802199, self.tradeDate='20230927', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26233.4', self.close='26232.2'
127.0.0.1 - - [27/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19612 

self.closeSec=1695802799, self.tradeDate='20230927', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26232.2', self.close='26220.9'
127.0.0.1 - - [27/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19610 

self.closeSec=1695799799, self.tradeDate='20230927', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26240', self.close='26228.8'
127.0.0.1 - - [27/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19611 

self.closeSec=1695800399, self.tradeDate='20230927', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26228.8', self.close='26236.1'
127.0.0.1 - - [27/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19612 

self.closeSec=1695800999, self.tradeDate='20230927', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26236.2', self.close='26234.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19613 

self.closeSec=1695801599, self.tradeDate='20230927', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26234.1', self.close='26233.4'
127.0.0.1 - - [27/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19614 

self.closeSec=1695802199, self.tradeDate='20230927', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26233.4', self.close='26232.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19615 

self.closeSec=1695802799, self.tradeDate='20230927', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26232.2', self.close='26220.9'
127.0.0.1 - - [27/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19610 

self.closeSec=1695799799, self.tradeDate='20230927', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26240', self.close='26228.8'
127.0.0.1 - - [27/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19611 

self.closeSec=1695800399, self.tradeDate='20230927', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26228.8', self.close='26236.1'
127.0.0.1 - - [27/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19612 

self.closeSec=1695800999, self.tradeDate='20230927', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26236.2', self.close='26234.1'
127.0.0.1 - - [27/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19613 

self.closeSec=1695801599, self.tradeDate='20230927', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26234.1', self.close='26233.4'
127.0.0.1 - - [27/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19614 

self.closeSec=1695802199, self.tradeDate='20230927', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26233.4', self.close='26232.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19615 

self.closeSec=1695802799, self.tradeDate='20230927', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26232.2', self.close='26220.9'
127.0.0.1 - - [27/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39220
self.closeSec=1695802799, self.tradeDate='20230927', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26223.4, self.close=26220.9, self.high=26228.0, self.low=26220.9, self.vol=224.843, self.amt=5896541.9314 
127.0.0.1 - - [27/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-27 16:20:06,010:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230927   155500    155959  ...         0.0        0.0       0
5952  20230927   160000    160459  ...         0.0        0.0       0
5953  20230927   160500    160959  ...         0.0        0.0       0
5954  20230927   161000    161459  ...         0.0        0.0       0
5955  20230927   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 16:20:06,013:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695802799, self.tradeDate='20230927', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26223.4, self.close=26220.9, self.high=26228.0, self.low=26220.9, self.vol=224.843, self.amt=5896541.9314, ukdf['pct'].iloc[-1]=-9.5e-05 , ukdf['amount'].iloc[-1]=5896541.9314, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-23053.19537599533', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26223.30601287', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39221
self.closeSec=1695803099, self.tradeDate='20230927', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26221.0, self.close=26217.3, self.high=26223.5, self.low=26213.2, self.vol=300.689, self.amt=7883646.2293 
127.0.0.1 - - [27/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-27 16:25:00,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230927   160000    160459  ...         0.0        0.0       0
5953  20230927   160500    160959  ...         0.0        0.0       0
5954  20230927   161000    161459  ...         0.0        0.0       0
5955  20230927   161500    161959  ...         0.0        0.0       0
5956  20230927   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 16:25:00,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695803099, self.tradeDate='20230927', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26221.0, self.close=26217.3, self.high=26223.5, self.low=26213.2, self.vol=300.689, self.amt=7883646.2293, ukdf['pct'].iloc[-1]=-0.000137 , ukdf['amount'].iloc[-1]=7883646.2293, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-23283.6929', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26217.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230927   040000    075959  1695772799  ...    721  0.268882 -0.846173    -1.0
722  20230927   080000    115959  1695787199  ...    722  0.269419 -0.848148    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-6146.5516', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26270', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=817
self.closeSec=1695801599, self.tradeDate='20230927', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26266.9, self.close=26233.4, self.high=26280.1, self.low=26220.9, self.vol=10642.269, self.amt=279293600.3164 
2023-09-27 16:00:01,564:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695801599, self.tradeDate='20230927', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26266.9, self.close=26233.4, self.high=26280.1, self.low=26220.9, self.vol=10642.269, self.amt=279293600.3164 
2023-09-27 16:00:01,583:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230926   200000    235959  ...  54593.775  1.429196e+09 -0.005620
720  20230927   000000    035959  ...  36140.137  9.469580e+08  0.004633
721  20230927   040000    075959  ...  23705.843  6.206869e+08 -0.001029
722  20230927   080000    115959  ...  18602.743  4.880133e+08  0.002217
723  20230927   120000    155959  ...  10642.269  2.792936e+08 -0.001275

[5 rows x 11 columns]
2023-09-27 16:00:02,354:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230926   200000    235959  1695743999  ...    719  0.266004 -0.852583    -1.0
720  20230927   000000    035959  1695758399  ...    720  0.264997 -0.857729    -1.0
721  20230927   040000    075959  1695772799  ...    721  0.268882 -0.846173    -1.0
722  20230927   080000    115959  1695787199  ...    722  0.269419 -0.848148    -1.0
723  20230927   120000    155959  1695801599  ...    723  0.261979 -0.872222    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-4422.58755171676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26236.03428071', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


