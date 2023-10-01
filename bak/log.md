# 20231001 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40372
self.closeSec=1696148399, self.tradeDate='20231001', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27088.3, self.close=27083.3, self.high=27091.0, self.low=27080.0, self.vol=474.19, self.amt=12842443.5412 
127.0.0.1 - - [01/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-01 16:20:06,190:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231001   155500    155959  ...         0.0        0.0       0
5952  20231001   160000    160459  ...         0.0        0.0       0
5953  20231001   160500    160959  ...         0.0        0.0       0
5954  20231001   161000    161459  ...         0.0        0.0       0
5955  20231001   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 16:20:06,201:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696148399, self.tradeDate='20231001', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27088.3, self.close=27083.3, self.high=27091.0, self.low=27080.0, self.vol=474.19, self.amt=12842443.5412, ukdf['pct'].iloc[-1]=-0.00021 , ukdf['amount'].iloc[-1]=12842443.5412, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3001.053', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27080.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40373
self.closeSec=1696148699, self.tradeDate='20231001', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27083.2, self.close=27081.6, self.high=27083.3, self.low=27070.5, self.vol=397.95, self.amt=10775686.5187 
2023-10-01 16:25:00,801:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231001   160000    160459  ...         0.0        0.0       0
5953  20231001   160500    160959  ...         0.0        0.0       0
5954  20231001   161000    161459  ...         0.0        0.0       0
5955  20231001   161500    161959  ...         0.0        0.0       0
5956  20231001   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 16:25:00,801:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696148699, self.tradeDate='20231001', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27083.2, self.close=27081.6, self.high=27083.3, self.low=27070.5, self.vol=397.95, self.amt=10775686.5187, ukdf['pct'].iloc[-1]=-6.3e-05 , ukdf['amount'].iloc[-1]=10775686.5187, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3017.7642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27081.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [01/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40370 

self.closeSec=1696147199, self.tradeDate='20231001', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27098.3, self.close=27092.1, self.high=27105.6, self.low=27092.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40371 

self.closeSec=1696147499, self.tradeDate='20231001', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27092.1, self.close=27103.8, self.high=27104.6, self.low=27092.0 
127.0.0.1 - - [01/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40372 

self.closeSec=1696147799, self.tradeDate='20231001', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27103.8, self.close=27100.1, self.high=27107.4, self.low=27100.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40373 

self.closeSec=1696148099, self.tradeDate='20231001', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27100.0, self.close=27089.0, self.high=27100.1, self.low=27080.1 
127.0.0.1 - - [01/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40374 

self.closeSec=1696148399, self.tradeDate='20231001', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27088.3, self.close=27083.3, self.high=27091.0, self.low=27080.0 
127.0.0.1 - - [01/Oct/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40375 

self.closeSec=1696148699, self.tradeDate='20231001', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27083.2, self.close=27081.6, self.high=27083.3, self.low=27070.5 
127.0.0.1 - - [01/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-01 16:00:18,480:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231001    132959  27035.0  ...  51.250000  0.556347  0.355939
5786  20231001    135959  27058.9  ...  51.666667  0.557514  0.340089
5787  20231001    142959  27061.9  ...  52.083333  0.563267  0.321805
5788  20231001    145959  27077.8  ...  52.083333  0.575987  0.305514
5789  20231001    152959  27113.1  ...  52.083333  0.565896  0.299665

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-10-01 16:00:18,540:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.501880  0.498120       1  ...  0.985124  -1.0    0.0  0.995216
538     1  0.495770  0.504230       1  ...  0.984552  -1.0    0.0  0.995793
539     1  0.499905  0.500095       1  ...  0.983262  -1.0    0.0  0.997098
540     0  0.508356  0.491644       0  ...  0.984034  -1.0    0.0  0.996315
541     1  0.490582  0.509418       1  ...  0.984027  -1.0    0.0  0.996322

[5 rows x 10 columns]
2023-10-01 16:00:18,551:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501849  0.498151       1  ...  0.985124  -1.0    0.0  0.995904
46     1  0.495615  0.504385       1  ...  0.984552  -1.0    0.0  0.995548
47     0  0.500062  0.499938       1  ...  0.983262  -1.0    0.0  0.996959
48     0  0.508508  0.491492       0  ...  0.984034  -1.0    0.0  0.997162
49     1  0.490582  0.509418       1  ...  0.984027  -1.0    0.0  0.996322

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.689', 'enterprice': '27080', 'countrevence': '0', 'unrealprofit': '-400.7484', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27095.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [01/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20183 

self.closeSec=1696145399, self.tradeDate='20231001', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27134.3', self.close='27091.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20184 

self.closeSec=1696145999, self.tradeDate='20231001', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27091.9', self.close='27107.3'
127.0.0.1 - - [01/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20185 

self.closeSec=1696146599, self.tradeDate='20231001', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27107.3', self.close='27100.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20186 

self.closeSec=1696147199, self.tradeDate='20231001', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27100.6', self.close='27092.1'
127.0.0.1 - - [01/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20187 

self.closeSec=1696147799, self.tradeDate='20231001', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27092.1', self.close='27100.1'
127.0.0.1 - - [01/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20188 

self.closeSec=1696148399, self.tradeDate='20231001', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27100', self.close='27083.3'
127.0.0.1 - - [01/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20186 

self.closeSec=1696145399, self.tradeDate='20231001', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27134.3', self.close='27091.9'
127.0.0.1 - - [01/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20187 127.0.0.1 - - [01/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -


self.closeSec=1696145999, self.tradeDate='20231001', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27091.9', self.close='27107.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20188 

self.closeSec=1696146599, self.tradeDate='20231001', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27107.3', self.close='27100.7'
127.0.0.1 - - [01/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20189 

self.closeSec=1696147199, self.tradeDate='20231001', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27100.6', self.close='27092.1'
127.0.0.1 - - [01/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20190 

self.closeSec=1696147799, self.tradeDate='20231001', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27092.1', self.close='27100.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20191 

self.closeSec=1696148399, self.tradeDate='20231001', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27100', self.close='27083.3'
127.0.0.1 - - [01/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20186 

self.closeSec=1696145399, self.tradeDate='20231001', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27134.3', self.close='27091.9'
127.0.0.1 - - [01/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20187 

self.closeSec=1696145999, self.tradeDate='20231001', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27091.9', self.close='27107.3'
127.0.0.1 - - [01/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20188 

self.closeSec=1696146599, self.tradeDate='20231001', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27107.3', self.close='27100.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20189 

self.closeSec=1696147199, self.tradeDate='20231001', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27100.6', self.close='27092.1'
127.0.0.1 - - [01/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20190 

self.closeSec=1696147799, self.tradeDate='20231001', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27092.1', self.close='27100.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20191 

self.closeSec=1696148399, self.tradeDate='20231001', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27100', self.close='27083.3'
127.0.0.1 - - [01/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40372
self.closeSec=1696148399, self.tradeDate='20231001', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27088.3, self.close=27083.3, self.high=27091.0, self.low=27080.0, self.vol=474.19, self.amt=12842443.5412 
127.0.0.1 - - [01/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-01 16:20:06,181:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231001   155500    155959  ...         0.0        0.0       0
5952  20231001   160000    160459  ...         0.0        0.0       0
5953  20231001   160500    160959  ...         0.0        0.0       0
5954  20231001   161000    161459  ...         0.0        0.0       0
5955  20231001   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 16:20:06,183:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696148399, self.tradeDate='20231001', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27088.3, self.close=27083.3, self.high=27091.0, self.low=27080.0, self.vol=474.19, self.amt=12842443.5412, ukdf['pct'].iloc[-1]=-0.00021 , ukdf['amount'].iloc[-1]=12842443.5412, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8780.1324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27080.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40373
self.closeSec=1696148699, self.tradeDate='20231001', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27083.2, self.close=27081.6, self.high=27083.3, self.low=27070.5, self.vol=397.95, self.amt=10775686.5187 
127.0.0.1 - - [01/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-10-01 16:25:00,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231001   160000    160459  ...         0.0        0.0       0
5953  20231001   160500    160959  ...         0.0        0.0       0
5954  20231001   161000    161459  ...         0.0        0.0       0
5955  20231001   161500    161959  ...         0.0        0.0       0
5956  20231001   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 16:25:00,805:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696148699, self.tradeDate='20231001', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27083.2, self.close=27081.6, self.high=27083.3, self.low=27070.5, self.vol=397.95, self.amt=10775686.5187, ukdf['pct'].iloc[-1]=-6.3e-05 , ukdf['amount'].iloc[-1]=10775686.5187, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8824.7016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27081.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230930   200000    235959  ...  28819.566  7.776740e+08  0.002295
720  20231001   000000    035959  ...  14178.540  3.827586e+08  0.000923
721  20231001   040000    075959  ...  15733.976  4.248488e+08 -0.002229
722  20231001   080000    115959  ...  10992.656  2.968000e+08  0.003046
723  20231001   120000    155959  ...  19731.246  5.344221e+08  0.002186

[5 rows x 11 columns]
2023-10-01 16:00:02,373:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230930   200000    235959  1696089599  ...    719  0.577577 -0.161830     NaN
720  20231001   000000    035959  1696103999  ...    720  0.515879 -0.307095     NaN
721  20231001   040000    075959  1696118399  ...    721  0.464797 -0.427593     NaN
722  20231001   080000    115959  1696132799  ...    722  0.398204 -0.588849     NaN
723  20231001   120000    155959  1696147199  ...    723  0.339582 -0.726072    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-2949.70980371424', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27094.70774176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-3026.17933326885', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27093.07729615', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-01 16:00:09,314:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1273750.4459882', 'total': '1273750.4459882', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-01 16:00:09,799:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 46.874, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42974F1696147209794I0L65'}
2023-10-01 16:00:09,824:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:10011600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20231001, closeTime:155959, close:27092.1, sign:-1, total:1273750.4459882, side:sell  
127.0.0.1 - - [01/Oct/2023 16:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 16:00:09] "POST / HTTP/1.1" 200 -
2023-10-01 16:00:09,830:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42973F1696147204245I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696147204647386, 'quantity': '46.901', 'price': '27092', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696147203219, 'updatetime': 1696147204647, 'tradetype': 'usdt', 'selfid': 42973, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696147204647, 'clientorderid': '42973F1696147204245I0L65', 'price': '27092', 'quantity': '46.901', 'commission': '1270.641892', 'commissionasset': 'USDT', 'tradetime': 1696147204647, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696147204647}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-01 16:00:09,832:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42973F1696147204245I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696147204647386, 'quantity': '46.901', 'price': '27092', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696147203219, 'updatetime': 1696147204647, 'tradetype': 'usdt', 'selfid': 42973, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696147204647, 'clientorderid': '42973F1696147204245I0L65', 'price': '27092', 'quantity': '46.901', 'commission': '1270.641892', 'commissionasset': 'USDT', 'tradetime': 1696147204647, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696147204647}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-01 16:00:10,262:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42974F1696147209794I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696147210211466, 'quantity': '46.874', 'price': '27094.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696147209328, 'updatetime': 1696147210211, 'tradetype': 'usdt', 'selfid': 42974, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696147210211, 'clientorderid': '42974F1696147209794I0L65', 'price': '27094.9', 'quantity': '46.874', 'commission': '1270.0463426', 'commissionasset': 'USDT', 'tradetime': 1696147210211, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696147210211}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Oct/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-10-01 16:00:10,414:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42974F1696147209794I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696147210211466, 'quantity': '46.874', 'price': '27094.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696147209328, 'updatetime': 1696147210211, 'tradetype': 'usdt', 'selfid': 42974, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696147210211, 'clientorderid': '42974F1696147209794I0L65', 'price': '27094.9', 'quantity': '46.874', 'commission': '1270.0463426', 'commissionasset': 'USDT', 'tradetime': 1696147210211, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696147210211}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Oct/2023 16:00:10] "POST / HTTP/1.1" 200 -


