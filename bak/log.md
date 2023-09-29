# 20230930 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39892
self.closeSec=1696004399, self.tradeDate='20230930', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26841.8, self.close=26866.6, self.high=26872.4, self.low=26829.4, self.vol=857.236, self.amt=23018104.5324 
127.0.0.1 - - [30/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-30 00:20:06,574:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230929   235500    235959  ...         0.0        0.0       0
5760  20230930   000000    000459  ...         0.0        0.0       0
5761  20230930   000500    000959  ...         0.0        0.0       0
5762  20230930   001000    001459  ...         0.0        0.0       0
5763  20230930   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 00:20:06,585:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696004399, self.tradeDate='20230930', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26841.8, self.close=26866.6, self.high=26872.4, self.low=26829.4, self.vol=857.236, self.amt=23018104.5324, ukdf['pct'].iloc[-1]=0.000969 , ukdf['amount'].iloc[-1]=23018104.5324, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-54.48386821812', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26868.81238462', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39893
self.closeSec=1696004699, self.tradeDate='20230930', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26866.6, self.close=26867.7, self.high=26872.3, self.low=26847.2, self.vol=310.428, self.amt=8338473.7871 
2023-09-30 00:25:00,788:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230930   000000    000459  ...         0.0        0.0       0
5761  20230930   000500    000959  ...         0.0        0.0       0
5762  20230930   001000    001459  ...         0.0        0.0       0
5763  20230930   001500    001959  ...         0.0        0.0       0
5764  20230930   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 00:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696004699, self.tradeDate='20230930', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26866.6, self.close=26867.7, self.high=26872.3, self.low=26847.2, self.vol=310.428, self.amt=8338473.7871, ukdf['pct'].iloc[-1]=4.1e-05 , ukdf['amount'].iloc[-1]=8338473.7871, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-88.76973118728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26871.27438828', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [30/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230925' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39892 

self.closeSec=1696003799, self.tradeDate='20230930', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26877.4, self.close=26856.4, self.high=26899.7, self.low=26855.3 
127.0.0.1 - - [30/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39893 

self.closeSec=1696004099, self.tradeDate='20230930', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26856.4, self.close=26840.6, self.high=26866.8, self.low=26818.0 
127.0.0.1 - - [30/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39894 

self.closeSec=1696004399, self.tradeDate='20230930', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26841.8, self.close=26866.6, self.high=26872.4, self.low=26829.4 
127.0.0.1 - - [30/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39895 

self.closeSec=1696004699, self.tradeDate='20230930', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26866.6, self.close=26867.7, self.high=26872.3, self.low=26847.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-30 00:00:17,806:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230929    212959  26988.6  ...  50.833333  0.551049  0.443121
5802  20230929    215959  26990.7  ...  50.833333  0.526290  0.472839
5803  20230929    222959  26881.0  ...  50.833333  0.502032  0.492517
5804  20230929    225959  26765.7  ...  50.833333  0.526171  0.497144
5805  20230929    232959  26897.6  ...  50.833333  0.510123  0.510200

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-09-30 00:00:17,875:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.492281  0.507719       0  ...  0.945821  -1.0    0.0  1.006719
540     1  0.453669  0.546331       0  ...  0.949882  -1.0    0.0  1.002397
541     1  0.445879  0.554121       1  ...  0.945446  -1.0    0.0  1.007078
542     0  0.525743  0.474257       0  ...  0.948241  -1.0    0.0  1.004101
543     1  0.458918  0.541082       1  ...  0.945991  -1.0    0.0  1.006483

[5 rows x 10 columns]
2023-09-30 00:00:17,887:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492057  0.507943       0  ...  0.945821  -1.0    0.0  1.008078
46     1  0.453937  0.546063       0  ...  0.949882  -1.0    0.0  1.005806
47     1  0.445797  0.554203       1  ...  0.945446  -1.0    0.0  1.005944
48     0  0.525513  0.474487       0  ...  0.948241  -1.0    0.0  1.002970
49     1  0.458918  0.541082       1  ...  0.945991  -1.0    0.0  1.006483

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.689', 'enterprice': '27080', 'countrevence': '0', 'unrealprofit': '4938.05885043054', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26887.77535714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19943 

self.closeSec=1696001399, self.tradeDate='20230929', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26892.1', self.close='26811.2'
127.0.0.1 - - [29/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19944 

self.closeSec=1696001999, self.tradeDate='20230929', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26816.1', self.close='26834.7'
127.0.0.1 - - [29/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19945 

self.closeSec=1696002599, self.tradeDate='20230929', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26834.7', self.close='26868.8'
127.0.0.1 - - [30/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19946 

self.closeSec=1696003199, self.tradeDate='20230929', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26868.8', self.close='26874.8'
127.0.0.1 - - [30/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19947 

self.closeSec=1696003799, self.tradeDate='20230930', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26874.9', self.close='26856.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19948 

self.closeSec=1696004399, self.tradeDate='20230930', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26856.4', self.close='26866.6'
127.0.0.1 - - [30/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [29/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19946 

self.closeSec=1696001399, self.tradeDate='20230929', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26892.1', self.close='26811.2'
127.0.0.1 - - [29/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19947 

self.closeSec=1696001999, self.tradeDate='20230929', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26816.1', self.close='26834.7'
127.0.0.1 - - [29/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19948 

self.closeSec=1696002599, self.tradeDate='20230929', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26834.7', self.close='26868.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19949 

self.closeSec=1696003199, self.tradeDate='20230929', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26868.8', self.close='26874.8'
127.0.0.1 - - [30/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19950 

self.closeSec=1696003799, self.tradeDate='20230930', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26874.9', self.close='26856.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19951 

self.closeSec=1696004399, self.tradeDate='20230930', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26856.4', self.close='26866.6'
127.0.0.1 - - [30/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19946 

self.closeSec=1696001399, self.tradeDate='20230929', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26892.1', self.close='26811.2'
127.0.0.1 - - [29/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19947 

self.closeSec=1696001999, self.tradeDate='20230929', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26816.1', self.close='26834.7'
127.0.0.1 - - [29/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19948 

self.closeSec=1696002599, self.tradeDate='20230929', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26834.7', self.close='26868.8'
127.0.0.1 - - [29/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19949 

self.closeSec=1696003199, self.tradeDate='20230929', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26868.8', self.close='26874.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19950 

self.closeSec=1696003799, self.tradeDate='20230930', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26874.9', self.close='26856.4'
127.0.0.1 - - [30/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19951 

self.closeSec=1696004399, self.tradeDate='20230930', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26856.4', self.close='26866.6'
127.0.0.1 - - [30/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39892
self.closeSec=1696004399, self.tradeDate='20230930', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26841.8, self.close=26866.6, self.high=26872.4, self.low=26829.4, self.vol=857.236, self.amt=23018104.5324 
127.0.0.1 - - [30/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-30 00:20:06,575:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230929   235500    235959  ...         0.0        0.0       0
5760  20230930   000000    000459  ...         0.0        0.0       0
5761  20230930   000500    000959  ...         0.0        0.0       0
5762  20230930   001000    001459  ...         0.0        0.0       0
5763  20230930   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 00:20:06,585:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696004399, self.tradeDate='20230930', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26841.8, self.close=26866.6, self.high=26872.4, self.low=26829.4, self.vol=857.236, self.amt=23018104.5324, ukdf['pct'].iloc[-1]=0.000969 , ukdf['amount'].iloc[-1]=23018104.5324, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '921.55677717142', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26868.81238462', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [30/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39893
self.closeSec=1696004699, self.tradeDate='20230930', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26866.6, self.close=26867.7, self.high=26872.3, self.low=26847.2, self.vol=310.428, self.amt=8338473.7871 
2023-09-30 00:25:00,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230930   000000    000459  ...         0.0        0.0       0
5761  20230930   000500    000959  ...         0.0        0.0       0
5762  20230930   001000    001459  ...         0.0        0.0       0
5763  20230930   001500    001959  ...         0.0        0.0       0
5764  20230930   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 00:25:00,791:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696004699, self.tradeDate='20230930', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26866.6, self.close=26867.7, self.high=26872.3, self.low=26847.2, self.vol=310.428, self.amt=8338473.7871, ukdf['pct'].iloc[-1]=4.1e-05 , ukdf['amount'].iloc[-1]=8338473.7871, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '1012.99805510748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26871.27438828', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230929   120000    155959  1695974399  ...    723  0.948493  0.777177     1.0
724  20230929   160000    195959  1695988799  ...    724  0.888722  0.620769     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-9534.65461380213', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26954.30679487', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [30/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1272444.8790024, self.flagDict['side']='buy', self.tradeCount=27, self.count=831
self.closeSec=1696003199, self.tradeDate='20230929', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26958.3, self.close=26874.8, self.high=27098.0, self.low=26625.0, self.vol=112689.694, self.amt=3029299854.29528 
2023-09-30 00:00:01,543:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696003199, self.tradeDate='20230929', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26958.3, self.close=26874.8, self.high=27098.0, self.low=26625.0, self.vol=112689.694, self.amt=3029299854.29528 
2023-09-30 00:00:01,556:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230929   040000    075959  ...   38159.338  1.031164e+09 -0.002831
722  20230929   080000    115959  ...   42838.866  1.155957e+09 -0.002488
723  20230929   120000    155959  ...   39116.334  1.058424e+09  0.008332
724  20230929   160000    195959  ...   35285.051  9.539245e+08 -0.007744
725  20230929   200000    235959  ...  112689.694  3.029300e+09 -0.003112

[5 rows x 11 columns]
2023-09-30 00:00:02,312:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230929   040000    075959  1695945599  ...    721  0.776522  0.387464     NaN
722  20230929   080000    115959  1695959999  ...    722  0.846240  0.544805     NaN
723  20230929   120000    155959  1695974399  ...    723  0.948493  0.777177     1.0
724  20230929   160000    195959  1695988799  ...    724  0.888722  0.620769     1.0
725  20230929   200000    235959  1696003199  ...    725  0.913452  0.669172     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-13199.10172745693', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26876.17526007', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


