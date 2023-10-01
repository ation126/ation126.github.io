# 20231002 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40468
self.closeSec=1696177199, self.tradeDate='20231002', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27142.5, self.close=27120.1, self.high=27142.5, self.low=27116.1, self.vol=375.787, self.amt=10192789.8705 
127.0.0.1 - - [02/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-10-02 00:20:08,329:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231001   235500    235959  ...         0.0        0.0       0
5760  20231002   000000    000459  ...         0.0        0.0       0
5761  20231002   000500    000959  ...         0.0        0.0       0
5762  20231002   001000    001459  ...         0.0        0.0       0
5763  20231002   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 00:20:08,347:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696177199, self.tradeDate='20231002', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27142.5, self.close=27120.1, self.high=27142.5, self.low=27116.1, self.vol=375.787, self.amt=10192789.8705, ukdf['pct'].iloc[-1]=-0.000822 , ukdf['amount'].iloc[-1]=10192789.8705, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3555.3078', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27120.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40469
self.closeSec=1696177499, self.tradeDate='20231002', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27120.2, self.close=27120.4, self.high=27124.6, self.low=27115.3, self.vol=177.495, self.amt=4813533.1865 
127.0.0.1 - - [02/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-02 00:25:02,990:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231002   000000    000459  ...         0.0        0.0       0
5761  20231002   000500    000959  ...         0.0        0.0       0
5762  20231002   001000    001459  ...         0.0        0.0       0
5763  20231002   001500    001959  ...         0.0        0.0       0
5764  20231002   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 00:25:02,999:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696177499, self.tradeDate='20231002', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27120.2, self.close=27120.4, self.high=27124.6, self.low=27115.3, self.vol=177.495, self.amt=4813533.1865, ukdf['pct'].iloc[-1]=1.1e-05 , ukdf['amount'].iloc[-1]=4813533.1865, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3556.7004', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27120.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1696176299, self.tradeDate='20231002', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27135.8, self.close=27137.5, self.high=27137.5, self.low=27128.5 

--ukdf-hist--: overDate='20230927' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40468 

self.closeSec=1696176599, self.tradeDate='20231002', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27137.4, self.close=27126.1, self.high=27137.5, self.low=27126.1 
127.0.0.1 - - [02/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40469 

self.closeSec=1696176899, self.tradeDate='20231002', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27125.8, self.close=27142.4, self.high=27142.5, self.low=27124.1 
127.0.0.1 - - [02/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40470 

self.closeSec=1696177199, self.tradeDate='20231002', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27142.5, self.close=27120.1, self.high=27142.5, self.low=27116.1 
127.0.0.1 - - [02/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40471 

self.closeSec=1696177499, self.tradeDate='20231002', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27120.2, self.close=27120.4, self.high=27124.6, self.low=27115.3 
127.0.0.1 - - [02/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-02 00:00:18,068:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231001    212959  27176.3  ...  53.333333  0.576613  0.266472
5802  20231001    215959  27155.5  ...  53.750000  0.584093  0.268495
5803  20231001    222959  27175.6  ...  54.166667  0.594352  0.265008
5804  20231001    225959  27203.9  ...  53.750000  0.547847  0.279883
5805  20231001    232959  27108.8  ...  54.166667  0.551611  0.291860

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-10-02 00:00:18,124:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.485629  0.514371       1  ...  0.980989  -1.0    0.0  1.003182
540     1  0.498370  0.501630       1  ...  0.979971  -1.0    0.0  1.004223
541     0  0.503137  0.496863       0  ...  0.983397  -1.0    0.0  1.000712
542     1  0.464428  0.535572       1  ...  0.983034  -1.0    0.0  1.001082
543     1  0.492285  0.507715       1  ...  0.982418  -1.0    0.0  1.001709

[5 rows x 10 columns]
2023-10-02 00:00:18,136:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485912  0.514088       1  ...  0.980989  -1.0    0.0  1.004718
46     1  0.498535  0.501465       1  ...  0.979971  -1.0    0.0  1.005715
47     0  0.503090  0.496910       0  ...  0.983397  -1.0    0.0  1.001622
48     1  0.464546  0.535454       1  ...  0.983034  -1.0    0.0  1.001992
49     1  0.492285  0.507715       1  ...  0.982418  -1.0    0.0  1.001709

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.689', 'enterprice': '27080', 'countrevence': '0', 'unrealprofit': '-1436.96131141437', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27135.93683333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20231 

self.closeSec=1696174199, self.tradeDate='20231001', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27106.8', self.close='27118.8'
127.0.0.1 - - [01/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20232 

self.closeSec=1696174799, self.tradeDate='20231001', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27118.7', self.close='27130.7'
127.0.0.1 - - [01/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20233 

self.closeSec=1696175399, self.tradeDate='20231001', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27128.2', self.close='27123'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20234 

self.closeSec=1696175999, self.tradeDate='20231001', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27124.7', self.close='27135.8'
127.0.0.1 - - [02/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20235 

self.closeSec=1696176599, self.tradeDate='20231002', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27135.8', self.close='27125.9'
127.0.0.1 - - [02/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20236 

self.closeSec=1696177199, self.tradeDate='20231002', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27125.8', self.close='27120.1'
127.0.0.1 - - [02/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [01/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20234 

self.closeSec=1696174199, self.tradeDate='20231001', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27106.8', self.close='27118.8'

--handleKline--:  127.0.0.1 - - [01/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20235 

self.closeSec=1696174799, self.tradeDate='20231001', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27118.7', self.close='27130.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20236 

self.closeSec=1696175399, self.tradeDate='20231001', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27128.2', self.close='27123'
127.0.0.1 - - [01/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20237 

self.closeSec=1696175999, self.tradeDate='20231001', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27124.7', self.close='27135.8'
127.0.0.1 - - [02/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20238 

self.closeSec=1696176599, self.tradeDate='20231002', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27135.8', self.close='27125.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20239 

self.closeSec=1696177199, self.tradeDate='20231002', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27125.8', self.close='27120.1'
127.0.0.1 - - [02/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20234 

self.closeSec=1696174199, self.tradeDate='20231001', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27106.8', self.close='27118.8'
127.0.0.1 - - [01/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20235 

self.closeSec=1696174799, self.tradeDate='20231001', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27118.7', self.close='27130.7'
127.0.0.1 - - [01/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20236 

self.closeSec=1696175399, self.tradeDate='20231001', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27128.2', self.close='27123'
127.0.0.1 - - [02/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20237 

self.closeSec=1696175999, self.tradeDate='20231001', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27124.7', self.close='27135.8'
127.0.0.1 - - [02/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20238 

self.closeSec=1696176599, self.tradeDate='20231002', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27135.8', self.close='27125.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20239 

self.closeSec=1696177199, self.tradeDate='20231002', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27125.8', self.close='27120.1'
127.0.0.1 - - [02/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40468
self.closeSec=1696177199, self.tradeDate='20231002', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27142.5, self.close=27120.1, self.high=27142.5, self.low=27116.1, self.vol=375.787, self.amt=10192789.8705 
127.0.0.1 - - [02/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-10-02 00:20:08,315:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231001   235500    235959  ...         0.0        0.0       0
5760  20231002   000000    000459  ...         0.0        0.0       0
5761  20231002   000500    000959  ...         0.0        0.0       0
5762  20231002   001000    001459  ...         0.0        0.0       0
5763  20231002   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 00:20:08,329:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696177199, self.tradeDate='20231002', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27142.5, self.close=27120.1, self.high=27142.5, self.low=27116.1, self.vol=375.787, self.amt=10192789.8705, ukdf['pct'].iloc[-1]=-0.000822 , ukdf['amount'].iloc[-1]=10192789.8705, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10258.3442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27120.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40469
self.closeSec=1696177499, self.tradeDate='20231002', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27120.2, self.close=27120.4, self.high=27124.6, self.low=27115.3, self.vol=177.495, self.amt=4813533.1865 
127.0.0.1 - - [02/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-02 00:25:02,981:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231002   000000    000459  ...         0.0        0.0       0
5761  20231002   000500    000959  ...         0.0        0.0       0
5762  20231002   001000    001459  ...         0.0        0.0       0
5763  20231002   001500    001959  ...         0.0        0.0       0
5764  20231002   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 00:25:02,990:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696177499, self.tradeDate='20231002', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27120.2, self.close=27120.4, self.high=27124.6, self.low=27115.3, self.vol=177.495, self.amt=4813533.1865, ukdf['pct'].iloc[-1]=1.1e-05 , ukdf['amount'].iloc[-1]=4813533.1865, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10262.0583', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27120.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231001   120000    155959  1696147199  ...    723  0.339582 -0.726072    -1.0
724  20231001   160000    195959  1696161599  ...    724  0.295177 -0.829722    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.874', 'enterprice': '27094.9', 'countrevence': '0', 'unrealprofit': '-3763.9822', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27175.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [02/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1268776.2962574002, self.flagDict['side']='sell', self.tradeCount=28, self.count=843
self.closeSec=1696175999, self.tradeDate='20231001', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27174.2, self.close=27135.8, self.high=27219.7, self.low=27067.4, self.vol=29635.945, self.amt=804299138.0494 
2023-10-02 00:00:01,575:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696175999, self.tradeDate='20231001', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27174.2, self.close=27135.8, self.high=27219.7, self.low=27067.4, self.vol=29635.945, self.amt=804299138.0494 
2023-10-02 00:00:01,592:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231001   040000    075959  ...  15733.976  4.248488e+08 -0.002229
722  20231001   080000    115959  ...  10992.656  2.968000e+08  0.003046
723  20231001   120000    155959  ...  19731.246  5.344221e+08  0.002186
724  20231001   160000    195959  ...  39467.035  1.072977e+09  0.003030
725  20231001   200000    235959  ...  29635.945  8.042991e+08 -0.001413

[5 rows x 11 columns]
2023-10-02 00:00:02,354:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231001   040000    075959  1696118399  ...    721  0.464797 -0.427593     NaN
722  20231001   080000    115959  1696132799  ...    722  0.398204 -0.588849     NaN
723  20231001   120000    155959  1696147199  ...    723  0.339582 -0.726072    -1.0
724  20231001   160000    195959  1696161599  ...    724  0.295177 -0.829722    -1.0
725  20231001   200000    235959  1696175999  ...    725  0.361394 -0.670357    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.874', 'enterprice': '27094.9', 'countrevence': '0', 'unrealprofit': '-2006.2429133006', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27137.7007619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


