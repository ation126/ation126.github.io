# 20230509 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46773
self.closeSec=1683562799, self.tradeDate='20230509', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27845.9, self.close=27835.0, self.high=27855.2, self.low=27820.8, self.vol=682.634, self.amt=19000874.3409 
127.0.0.1 - - [09/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-09 00:20:06,847:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230508   235500    235959  ...         0.0        0.0       0
5760  20230509   000000    000459  ...         0.0        0.0       0
5761  20230509   000500    000959  ...         0.0        0.0       0
5762  20230509   001000    001459  ...         0.0        0.0       0
5763  20230509   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 00:20:06,857:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683562799, self.tradeDate='20230509', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27845.9, self.close=27835.0, self.high=27855.2, self.low=27820.8, self.vol=682.634, self.amt=19000874.3409, ukdf['pct'].iloc[-1]=-0.000391 , ukdf['amount'].iloc[-1]=19000874.3409, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-680325.7856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27834.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46774
self.closeSec=1683563099, self.tradeDate='20230509', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27835.0, self.close=27878.1, self.high=27880.1, self.low=27824.3, self.vol=1225.207, self.amt=34137481.5234 
127.0.0.1 - - [09/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-09 00:25:02,150:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230509   000000    000459  ...         0.0        0.0       0
5761  20230509   000500    000959  ...         0.0        0.0       0
5762  20230509   001000    001459  ...         0.0        0.0       0
5763  20230509   001500    001959  ...         0.0        0.0       0
5764  20230509   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 00:25:02,151:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683563099, self.tradeDate='20230509', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27835.0, self.close=27878.1, self.high=27880.1, self.low=27824.3, self.vol=1225.207, self.amt=34137481.5234, ukdf['pct'].iloc[-1]=0.001548 , ukdf['amount'].iloc[-1]=34137481.5234, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-682937.424', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27878.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [09/May/2023 00:05:02] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230504' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [09/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47337 

self.closeSec=1683562199, self.tradeDate='20230509', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27870.6, self.close=27853.2, self.high=27882.5, self.low=27828.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47338 

self.closeSec=1683562499, self.tradeDate='20230509', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27853.2, self.close=27845.9, self.high=27853.2, self.low=27818.4 
127.0.0.1 - - [09/May/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47339 

self.closeSec=1683562799, self.tradeDate='20230509', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27845.9, self.close=27835.0, self.high=27855.2, self.low=27820.8 
127.0.0.1 - - [09/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 00:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47340 

self.closeSec=1683563099, self.tradeDate='20230509', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27835.0, self.close=27878.1, self.high=27880.1, self.low=27824.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-09 00:00:20,900:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230508    212959  27756.9  ...  50.416667  0.392720  0.775245
5802  20230508    215959  27916.4  ...  50.000000  0.383555  0.776177
5803  20230508    222959  27844.6  ...  50.000000  0.374598  0.780481
5804  20230508    225959  27772.6  ...  50.416667  0.410774  0.775651
5805  20230508    232959  27958.2  ...  50.000000  0.404151  0.773598

[5 rows x 33 columns]
0.5606617647058824
acc is : 0.5606617647058824
2023-05-09 00:00:21,005:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.533350  0.466650       0  ...  0.953408  -1.0    0.0  0.964148
540     1  0.492390  0.507610       0  ...  0.955874  -1.0    0.0  0.961655
541     1  0.486172  0.513828       1  ...  0.949489  -1.0    0.0  0.968078
542     0  0.546244  0.453756       0  ...  0.951238  -1.0    0.0  0.966295
543     0  0.512983  0.487017       0  ...  0.952346  -1.0    0.0  0.965170

[5 rows x 10 columns]
2023-05-09 00:00:21,028:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.533674  0.466326       0  ...  0.935852  -1.0    0.0  0.961040
46     1  0.493273  0.506727       0  ...  0.938272  -1.0    0.0  0.965043
47     1  0.486129  0.513871       1  ...  0.969899  -1.0    0.0  0.970114
48     0  0.546292  0.453708       0  ...  0.951238  -1.0    0.0  0.968327
49     0  0.512983  0.487017       0  ...  0.952346  -1.0    0.0  0.965170

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23665 

self.closeSec=1683559799, self.tradeDate='20230508', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27920.4', self.close='27906.6'
127.0.0.1 - - [08/May/2023 23:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23666 

self.closeSec=1683560399, self.tradeDate='20230508', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27906.5', self.close='27887.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23667 

self.closeSec=1683560999, self.tradeDate='20230508', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27887.1', self.close='27884.9'
127.0.0.1 - - [08/May/2023 23:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23668 

self.closeSec=1683561599, self.tradeDate='20230508', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27884.9', self.close='27874.1'
127.0.0.1 - - [09/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23669 

self.closeSec=1683562199, self.tradeDate='20230509', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27874.2', self.close='27853.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23670 

self.closeSec=1683562799, self.tradeDate='20230509', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27853.2', self.close='27835'
127.0.0.1 - - [09/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23666 

self.closeSec=1683559799, self.tradeDate='20230508', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27920.4', self.close='27906.6'
127.0.0.1 - - [08/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23667 

self.closeSec=1683560399, self.tradeDate='20230508', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27906.5', self.close='27887.2'
127.0.0.1 - - [08/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23668 

self.closeSec=1683560999, self.tradeDate='20230508', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27887.1', self.close='27884.9'
127.0.0.1 - - [08/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23669 

self.closeSec=1683561599, self.tradeDate='20230508', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27884.9', self.close='27874.1'
127.0.0.1 - - [09/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23670 

self.closeSec=1683562199, self.tradeDate='20230509', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27874.2', self.close='27853.2'
127.0.0.1 - - [09/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23671 

self.closeSec=1683562799, self.tradeDate='20230509', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27853.2', self.close='27835'
127.0.0.1 - - [09/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [08/May/2023 23:30:03] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23666 

self.closeSec=1683559799, self.tradeDate='20230508', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27920.4', self.close='27906.6'
127.0.0.1 - - [08/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23667 

self.closeSec=1683560399, self.tradeDate='20230508', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27906.5', self.close='27887.2'
127.0.0.1 - - [08/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23668 

self.closeSec=1683560999, self.tradeDate='20230508', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27887.1', self.close='27884.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23669 

self.closeSec=1683561599, self.tradeDate='20230508', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27884.9', self.close='27874.1'
127.0.0.1 - - [09/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23670 

self.closeSec=1683562199, self.tradeDate='20230509', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27874.2', self.close='27853.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23671 

self.closeSec=1683562799, self.tradeDate='20230509', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27853.2', self.close='27835'
127.0.0.1 - - [09/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42771
self.closeSec=1683562799, self.tradeDate='20230509', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27845.9, self.close=27835.0, self.high=27855.2, self.low=27820.8, self.vol=682.634, self.amt=19000874.3409 
127.0.0.1 - - [09/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-09 00:20:06,847:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230508   235500    235959  ...         0.0        0.0       0
5760  20230509   000000    000459  ...         0.0        0.0       0
5761  20230509   000500    000959  ...         0.0        0.0       0
5762  20230509   001000    001459  ...         0.0        0.0       0
5763  20230509   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 00:20:06,857:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683562799, self.tradeDate='20230509', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27845.9, self.close=27835.0, self.high=27855.2, self.low=27820.8, self.vol=682.634, self.amt=19000874.3409, ukdf['pct'].iloc[-1]=-0.000391 , ukdf['amount'].iloc[-1]=19000874.3409, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42772
self.closeSec=1683563099, self.tradeDate='20230509', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27835.0, self.close=27878.1, self.high=27880.1, self.low=27824.3, self.vol=1225.207, self.amt=34137481.5234 
2023-05-09 00:25:02,154:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230509   000000    000459  ...         0.0        0.0       0
5761  20230509   000500    000959  ...         0.0        0.0       0
5762  20230509   001000    001459  ...         0.0        0.0       0
5763  20230509   001500    001959  ...         0.0        0.0       0
5764  20230509   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 00:25:02,154:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683563099, self.tradeDate='20230509', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27835.0, self.close=27878.1, self.high=27880.1, self.low=27824.3, self.vol=1225.207, self.amt=34137481.5234, ukdf['pct'].iloc[-1]=0.001548 , ukdf['amount'].iloc[-1]=34137481.5234, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230508   120000    155959  1683532799  ...    723  0.391871 -0.483625     NaN
724  20230508   160000    195959  1683547199  ...    724  0.529717 -0.031896     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '66545.0886581075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27916.90065375', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=986
self.closeSec=1683561599, self.tradeDate='20230508', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27922.2, self.close=27874.1, self.high=28074.9, self.low=27651.5, self.vol=110121.512, self.amt=3068480538.1998 
127.0.0.1 - - [09/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-09 00:00:03,123:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683561599, self.tradeDate='20230508', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27922.2, self.close=27874.1, self.high=28074.9, self.low=27651.5, self.vol=110121.512, self.amt=3068480538.1998 
2023-05-09 00:00:03,151:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230508   040000    075959  ...   66956.679  1.920791e+09 -0.016426
722  20230508   080000    115959  ...  142837.352  4.040366e+09 -0.008142
723  20230508   120000    155959  ...   82354.151  2.312412e+09 -0.008167
724  20230508   160000    195959  ...  108980.277  3.032535e+09 -0.001273
725  20230508   200000    235959  ...  110121.512  3.068481e+09 -0.001723

[5 rows x 11 columns]
2023-05-09 00:00:04,508:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230508   040000    075959  1683503999  ...    721  0.129701 -1.323498    -1.0
722  20230508   080000    115959  1683518399  ...    722  0.264857 -0.891031    -1.0
723  20230508   120000    155959  1683532799  ...    723  0.391871 -0.483625     NaN
724  20230508   160000    195959  1683547199  ...    724  0.529717 -0.031896     NaN
725  20230508   200000    235959  1683561599  ...    725  0.588915  0.176150     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '68539.9778', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27874.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


