# 20230507 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46197
self.closeSec=1683389999, self.tradeDate='20230507', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28640.6, self.close=28622.4, self.high=28642.0, self.low=28588.9, self.vol=1897.951, self.amt=54319689.6608 
127.0.0.1 - - [07/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-07 00:20:06,608:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230506   235500    235959  ...         0.0        0.0       0
5760  20230507   000000    000459  ...         0.0        0.0       0
5761  20230507   000500    000959  ...         0.0        0.0       0
5762  20230507   001000    001459  ...         0.0        0.0       0
5763  20230507   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 00:20:06,621:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683389999, self.tradeDate='20230507', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28640.6, self.close=28622.4, self.high=28642.0, self.low=28588.9, self.vol=1897.951, self.amt=54319689.6608, ukdf['pct'].iloc[-1]=-0.000635 , ukdf['amount'].iloc[-1]=54319689.6608, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-728093.4944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28628.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/May/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46198
self.closeSec=1683390299, self.tradeDate='20230507', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28622.5, self.close=28658.6, self.high=28665.5, self.low=28610.6, self.vol=1494.256, self.amt=42787331.9191 
2023-05-07 00:25:01,605:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230507   000000    000459  ...         0.0        0.0       0
5761  20230507   000500    000959  ...         0.0        0.0       0
5762  20230507   001000    001459  ...         0.0        0.0       0
5763  20230507   001500    001959  ...         0.0        0.0       0
5764  20230507   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 00:25:01,605:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683390299, self.tradeDate='20230507', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28622.5, self.close=28658.6, self.high=28665.5, self.low=28610.6, self.vol=1494.256, self.amt=42787331.9191, ukdf['pct'].iloc[-1]=0.001265 , ukdf['amount'].iloc[-1]=42787331.9191, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-729892.7568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28658.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [07/May/2023 00:05:02] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230502' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [07/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46761 

self.closeSec=1683389399, self.tradeDate='20230507', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28557.6, self.close=28603.5, self.high=28608.2, self.low=28537.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46762 

self.closeSec=1683389699, self.tradeDate='20230507', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28603.6, self.close=28640.6, self.high=28647.0, self.low=28589.0 
127.0.0.1 - - [07/May/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46763 

self.closeSec=1683389999, self.tradeDate='20230507', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28640.6, self.close=28622.4, self.high=28642.0, self.low=28588.9 
127.0.0.1 - - [07/May/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46764 

self.closeSec=1683390299, self.tradeDate='20230507', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28622.5, self.close=28658.6, self.high=28665.5, self.low=28610.6 
127.0.0.1 - - [07/May/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-07 00:00:18,988:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230506    212959  29087.9  ...  50.000000  0.465516  0.569400
5802  20230506    215959  29020.7  ...  50.000000  0.450788  0.592228
5803  20230506    222959  28937.4  ...  49.583333  0.402464  0.613070
5804  20230506    225959  28627.5  ...  49.583333  0.397343  0.634338
5805  20230506    232959  28591.0  ...  49.583333  0.394188  0.648297

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-05-07 00:00:19,055:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.464337  0.535663       0  ...  1.004211  -1.0    0.0  1.061830
540     1  0.455123  0.544877       0  ...  1.014962  -1.0    0.0  1.050462
541     1  0.389981  0.610019       0  ...  1.016256  -1.0    0.0  1.049122
542     1  0.435095  0.564905       0  ...  1.017056  -1.0    0.0  1.048297
543     1  0.449665  0.550335       0  ...  1.017434  -1.0    0.0  1.047908

[5 rows x 10 columns]
2023-05-07 00:00:19,068:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.464320  0.535680       0  ...  1.017538  -1.0    0.0  1.055278
46     1  0.456056  0.543944       0  ...  1.014962  -1.0    0.0  1.046824
47     1  0.391625  0.608375       0  ...  1.016256  -1.0    0.0  1.045941
48     1  0.435740  0.564260       0  ...  1.017056  -1.0    0.0  1.045118
49     1  0.449665  0.550335       0  ...  1.017434  -1.0    0.0  1.047908

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [06/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23377 

self.closeSec=1683386999, self.tradeDate='20230506', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28531.5', self.close='28568.5'
127.0.0.1 - - [06/May/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23378 

self.closeSec=1683387599, self.tradeDate='20230506', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28568.5', self.close='28548.9'
127.0.0.1 - - [06/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23379 

self.closeSec=1683388199, self.tradeDate='20230506', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28548.9', self.close='28594.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23380 

self.closeSec=1683388799, self.tradeDate='20230506', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28594.3', self.close='28557.9'
127.0.0.1 - - [07/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23381 

self.closeSec=1683389399, self.tradeDate='20230507', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28557.9', self.close='28603.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23382 

self.closeSec=1683389999, self.tradeDate='20230507', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28603.6', self.close='28622.4'
127.0.0.1 - - [07/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23378 

self.closeSec=1683386999, self.tradeDate='20230506', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28531.5', self.close='28568.5'
127.0.0.1 - - [06/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23379 

self.closeSec=1683387599, self.tradeDate='20230506', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28568.5', self.close='28548.9'
127.0.0.1 - - [06/May/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23380 

self.closeSec=1683388199, self.tradeDate='20230506', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28548.9', self.close='28594.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23381 

self.closeSec=1683388799, self.tradeDate='20230506', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28594.3', self.close='28557.9'
127.0.0.1 - - [07/May/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23382 

self.closeSec=1683389399, self.tradeDate='20230507', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28557.9', self.close='28603.5'
127.0.0.1 - - [07/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23383 

self.closeSec=1683389999, self.tradeDate='20230507', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28603.6', self.close='28622.4'
127.0.0.1 - - [07/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [06/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23378 

self.closeSec=1683386999, self.tradeDate='20230506', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28531.5', self.close='28568.5'
127.0.0.1 - - [06/May/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23379 

self.closeSec=1683387599, self.tradeDate='20230506', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28568.5', self.close='28548.9'
127.0.0.1 - - [06/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23380 

self.closeSec=1683388199, self.tradeDate='20230506', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28548.9', self.close='28594.3'
127.0.0.1 - - [07/May/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23381 

self.closeSec=1683388799, self.tradeDate='20230506', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28594.3', self.close='28557.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23382 

self.closeSec=1683389399, self.tradeDate='20230507', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28557.9', self.close='28603.5'
127.0.0.1 - - [07/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23383 

self.closeSec=1683389999, self.tradeDate='20230507', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28603.6', self.close='28622.4'
127.0.0.1 - - [07/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42195
self.closeSec=1683389999, self.tradeDate='20230507', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28640.6, self.close=28622.4, self.high=28642.0, self.low=28588.9, self.vol=1897.951, self.amt=54319689.6608 
127.0.0.1 - - [07/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-07 00:20:06,476:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230506   235500    235959  ...         0.0        0.0       0
5760  20230507   000000    000459  ...         0.0        0.0       0
5761  20230507   000500    000959  ...         0.0        0.0       0
5762  20230507   001000    001459  ...         0.0        0.0       0
5763  20230507   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 00:20:06,499:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683389999, self.tradeDate='20230507', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28640.6, self.close=28622.4, self.high=28642.0, self.low=28588.9, self.vol=1897.951, self.amt=54319689.6608, ukdf['pct'].iloc[-1]=-0.000635 , ukdf['amount'].iloc[-1]=54319689.6608, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42196
self.closeSec=1683390299, self.tradeDate='20230507', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28622.5, self.close=28658.6, self.high=28665.5, self.low=28610.6, self.vol=1494.256, self.amt=42787331.9191 
127.0.0.1 - - [07/May/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-05-07 00:25:01,589:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230507   000000    000459  ...         0.0        0.0       0
5761  20230507   000500    000959  ...         0.0        0.0       0
5762  20230507   001000    001459  ...         0.0        0.0       0
5763  20230507   001500    001959  ...         0.0        0.0       0
5764  20230507   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 00:25:01,590:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683390299, self.tradeDate='20230507', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28622.5, self.close=28658.6, self.high=28665.5, self.low=28610.6, self.vol=1494.256, self.amt=42787331.9191, ukdf['pct'].iloc[-1]=0.001265 , ukdf['amount'].iloc[-1]=42787331.9191, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230506   120000    155959  1683359999  ...    723  0.511397 -0.376513     NaN
724  20230506   160000    195959  1683374399  ...    724  0.430030 -0.616101    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '3527.209', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29265.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [07/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=974
self.closeSec=1683388799, self.tradeDate='20230506', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29264.5, self.close=28557.9, self.high=29266.7, self.low=28333.0, self.vol=181672.364, self.amt=5225997753.05422 
2023-05-07 00:00:01,915:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683388799, self.tradeDate='20230506', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29264.5, self.close=28557.9, self.high=29266.7, self.low=28333.0, self.vol=181672.364, self.amt=5225997753.05422 
2023-05-07 00:00:01,952:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230506   040000    075959  ...   40781.438  1.203951e+09 -0.001936
722  20230506   080000    115959  ...   76988.632  2.276442e+09 -0.004456
723  20230506   120000    155959  ...   42728.114  1.253976e+09 -0.000337
724  20230506   160000    195959  ...   58055.462  1.698515e+09 -0.002920
725  20230506   200000    235959  ...  181672.364  5.225998e+09 -0.024145

[5 rows x 11 columns]
2023-05-07 00:00:03,317:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230506   040000    075959  1683331199  ...    721  0.566793 -0.216533     NaN
722  20230506   080000    115959  1683345599  ...    722  0.593235 -0.130025     NaN
723  20230506   120000    155959  1683359999  ...    723  0.511397 -0.376513     NaN
724  20230506   160000    195959  1683374399  ...    724  0.430030 -0.616101    -1.0
725  20230506   200000    235959  1683388799  ...    725  0.274583 -1.074422    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '36483.80994610394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28560.36310317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


