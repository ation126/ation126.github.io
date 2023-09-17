# 20230917 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36244
self.closeSec=1694909999, self.tradeDate='20230917', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26499.7, self.close=26503.4, self.high=26505.5, self.low=26470.5, self.vol=1153.498, self.amt=30552388.3845 
127.0.0.1 - - [17/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-17 08:20:06,354:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230917   075500    075959  ...         0.0        0.0       0
5856  20230917   080000    080459  ...         0.0        0.0       0
5857  20230917   080500    080959  ...         0.0        0.0       0
5858  20230917   081000    081459  ...         0.0        0.0       0
5859  20230917   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 08:20:06,364:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694909999, self.tradeDate='20230917', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26499.7, self.close=26503.4, self.high=26505.5, self.low=26470.5, self.vol=1153.498, self.amt=30552388.3845, ukdf['pct'].iloc[-1]=0.00014 , ukdf['amount'].iloc[-1]=30552388.3845, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5083.53364959396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26499.86096154', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36245
self.closeSec=1694910299, self.tradeDate='20230917', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26503.4, self.close=26512.1, self.high=26514.3, self.low=26497.8, self.vol=238.847, self.amt=6331457.2661 
2023-09-17 08:25:00,782:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230917   080000    080459  ...         0.0        0.0       0
5857  20230917   080500    080959  ...         0.0        0.0       0
5858  20230917   081000    081459  ...         0.0        0.0       0
5859  20230917   081500    081959  ...         0.0        0.0       0
5860  20230917   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 08:25:00,782:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694910299, self.tradeDate='20230917', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26503.4, self.close=26512.1, self.high=26514.3, self.low=26497.8, self.vol=238.847, self.amt=6331457.2661, ukdf['pct'].iloc[-1]=0.000328 , ukdf['amount'].iloc[-1]=6331457.2661, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4899.02748903084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26513.11000366', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [17/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36242 

self.closeSec=1694908799, self.tradeDate='20230917', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26535.0, self.close=26546.9, self.high=26547.7, self.low=26534.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36243 

self.closeSec=1694909099, self.tradeDate='20230917', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26547.0, self.close=26541.5, self.high=26548.3, self.low=26541.4 
127.0.0.1 - - [17/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36244 

self.closeSec=1694909399, self.tradeDate='20230917', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26541.5, self.close=26531.1, self.high=26542.5, self.low=26531.1 
127.0.0.1 - - [17/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36245 

self.closeSec=1694909699, self.tradeDate='20230917', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26529.8, self.close=26499.7, self.high=26529.8, self.low=26491.0 
127.0.0.1 - - [17/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36246 

self.closeSec=1694909999, self.tradeDate='20230917', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26499.7, self.close=26503.4, self.high=26505.5, self.low=26470.5 
127.0.0.1 - - [17/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36247 

self.closeSec=1694910299, self.tradeDate='20230917', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26503.4, self.close=26512.1, self.high=26514.3, self.low=26497.8 
127.0.0.1 - - [17/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-17 08:00:18,211:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230917    052959  26515.8  ...  52.916667  0.520525  0.666041
5770  20230917    055959  26543.3  ...  53.333333  0.523881  0.663437
5771  20230917    062959  26554.3  ...  53.333333  0.525560  0.655285
5772  20230917    065959  26559.9  ...  53.333333  0.520452  0.648518
5773  20230917    072959  26545.0  ...  53.333333  0.511591  0.645785

[5 rows x 33 columns]
0.5555555555555556
acc is : 0.5555555555555556
2023-09-17 08:00:18,299:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.504523  0.495477       1  ...  0.944471   1.0    0.0  1.031692
536     0  0.503090  0.496910       1  ...  0.944667   1.0    0.0  1.031905
537     0  0.501767  0.498233       0  ...  0.944133   1.0    0.0  1.031322
538     1  0.495383  0.504617       0  ...  0.943201   1.0    0.0  1.030305
539     1  0.492172  0.507828       1  ...  0.944208   1.0    0.0  1.031404

[5 rows x 10 columns]
2023-09-17 08:00:18,319:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504559  0.495441       1  ...  0.944471   1.0    0.0  1.031327
46     0  0.502858  0.497142       1  ...  0.944667   1.0    0.0  1.030804
47     0  0.501882  0.498118       0  ...  0.944133   1.0    0.0  1.031262
48     1  0.495573  0.504427       0  ...  0.943201   1.0    0.0  1.030485
49     1  0.492172  0.507828       1  ...  0.944208   1.0    0.0  1.031404

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '-1220.39458379055', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26546.57306593', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18119 

self.closeSec=1694906999, self.tradeDate='20230917', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26516.6', self.close='26518.6'
127.0.0.1 - - [17/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18120 

self.closeSec=1694907599, self.tradeDate='20230917', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26518.7', self.close='26532.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18121 

self.closeSec=1694908199, self.tradeDate='20230917', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26532.4', self.close='26534.3'
127.0.0.1 - - [17/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18122 

self.closeSec=1694908799, self.tradeDate='20230917', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26534.3', self.close='26546.9'
127.0.0.1 - - [17/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18123 

self.closeSec=1694909399, self.tradeDate='20230917', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26547', self.close='26531.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18124 

self.closeSec=1694909999, self.tradeDate='20230917', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26529.8', self.close='26503.4'
127.0.0.1 - - [17/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18122 

self.closeSec=1694906999, self.tradeDate='20230917', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26516.6', self.close='26518.6'
127.0.0.1 - - [17/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18123 

self.closeSec=1694907599, self.tradeDate='20230917', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26518.7', self.close='26532.4'
127.0.0.1 - - [17/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18124 

self.closeSec=1694908199, self.tradeDate='20230917', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26532.4', self.close='26534.3'
127.0.0.1 - - [17/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18125 

self.closeSec=1694908799, self.tradeDate='20230917', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26534.3', self.close='26546.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18126 

self.closeSec=1694909399, self.tradeDate='20230917', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26547', self.close='26531.1'
127.0.0.1 - - [17/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18127 

self.closeSec=1694909999, self.tradeDate='20230917', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26529.8', self.close='26503.4'
127.0.0.1 - - [17/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18122 

self.closeSec=1694906999, self.tradeDate='20230917', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26516.6', self.close='26518.6'
127.0.0.1 - - [17/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18123 

self.closeSec=1694907599, self.tradeDate='20230917', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26518.7', self.close='26532.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18124 

self.closeSec=1694908199, self.tradeDate='20230917', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26532.4', self.close='26534.3'
127.0.0.1 - - [17/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18125 

self.closeSec=1694908799, self.tradeDate='20230917', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26534.3', self.close='26546.9'
127.0.0.1 - - [17/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18126 

self.closeSec=1694909399, self.tradeDate='20230917', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26547', self.close='26531.1'
127.0.0.1 - - [17/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18127 

self.closeSec=1694909999, self.tradeDate='20230917', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26529.8', self.close='26503.4'
127.0.0.1 - - [17/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36244
self.closeSec=1694909999, self.tradeDate='20230917', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26499.7, self.close=26503.4, self.high=26505.5, self.low=26470.5, self.vol=1153.498, self.amt=30552388.3845 
127.0.0.1 - - [17/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-17 08:20:06,358:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230917   075500    075959  ...         0.0        0.0       0
5856  20230917   080000    080459  ...         0.0        0.0       0
5857  20230917   080500    080959  ...         0.0        0.0       0
5858  20230917   081000    081459  ...         0.0        0.0       0
5859  20230917   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 08:20:06,376:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694909999, self.tradeDate='20230917', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26499.7, self.close=26503.4, self.high=26505.5, self.low=26470.5, self.vol=1153.498, self.amt=30552388.3845, ukdf['pct'].iloc[-1]=0.00014 , ukdf['amount'].iloc[-1]=30552388.3845, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12781.66802744286', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26499.86096154', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [17/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36245
self.closeSec=1694910299, self.tradeDate='20230917', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26503.4, self.close=26512.1, self.high=26514.3, self.low=26497.8, self.vol=238.847, self.amt=6331457.2661 
2023-09-17 08:25:00,793:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230917   080000    080459  ...         0.0        0.0       0
5857  20230917   080500    080959  ...         0.0        0.0       0
5858  20230917   081000    081459  ...         0.0        0.0       0
5859  20230917   081500    081959  ...         0.0        0.0       0
5860  20230917   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 08:25:00,793:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694910299, self.tradeDate='20230917', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26503.4, self.close=26512.1, self.high=26514.3, self.low=26497.8, self.vol=238.847, self.amt=6331457.2661, ukdf['pct'].iloc[-1]=0.000328 , ukdf['amount'].iloc[-1]=6331457.2661, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12289.58535406394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26513.11000366', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230916   200000    235959  1694879999  ...    719  0.386956  0.223744     NaN
720  20230917   000000    035959  1694894399  ...    720  0.370838  0.172720     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-8289.7675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26524.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1431863.74296, self.flagDict['side']='buy', self.tradeCount=23, self.count=755
self.closeSec=1694908799, self.tradeDate='20230917', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26524.1, self.close=26546.9, self.high=26570.0, self.low=26492.0, self.vol=9029.999, self.amt=239638217.0165 
127.0.0.1 - - [17/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-17 08:00:01,573:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694908799, self.tradeDate='20230917', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26524.1, self.close=26546.9, self.high=26570.0, self.low=26492.0, self.vol=9029.999, self.amt=239638217.0165 
2023-09-17 08:00:01,591:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230916   120000    155959  ...  32167.402  8.531910e+08 -0.004376
718  20230916   160000    195959  ...  31565.807  8.364129e+08  0.000933
719  20230916   200000    235959  ...  15417.259  4.088440e+08 -0.000645
720  20230917   000000    035959  ...  19314.111  5.127177e+08  0.001155
721  20230917   040000    075959  ...   9029.999  2.396382e+08  0.000856

[5 rows x 11 columns]
2023-09-17 08:00:02,312:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230916   120000    155959  1694851199  ...    717  0.426659  0.347395     NaN
718  20230916   160000    195959  1694865599  ...    718  0.357263  0.098166     NaN
719  20230916   200000    235959  1694879999  ...    719  0.386956  0.223744     NaN
720  20230917   000000    035959  1694894399  ...    720  0.370838  0.172720     NaN
721  20230917   040000    075959  1694908799  ...    721  0.483101  0.617305     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-7064.8375', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26546.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


