# 20230421 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41589
self.closeSec=1682007599, self.tradeDate='20230421', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28529.4, self.close=28559.4, self.high=28571.0, self.low=28505.8, self.vol=4730.103, self.amt=135011202.5957 
127.0.0.1 - - [21/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-21 00:20:06,178:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230420   235500    235959  ...         0.0        0.0       0
5753  20230421   000000    000459  ...         0.0        0.0       0
5754  20230421   000500    000959  ...         0.0        0.0       0
5755  20230421   001000    001459  ...         0.0        0.0       0
5756  20230421   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 00:20:06,183:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682007599, self.tradeDate='20230421', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28529.4, self.close=28559.4, self.high=28571.0, self.low=28505.8, self.vol=4730.103, self.amt=135011202.5957, ukdf['pct'].iloc[-1]=0.001052 , ukdf['amount'].iloc[-1]=135011202.5957, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-724206.1248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28564.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41590
self.closeSec=1682007899, self.tradeDate='20230421', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28559.6, self.close=28601.3, self.high=28650.0, self.low=28539.4, self.vol=5371.24, self.amt=153643842.525 
127.0.0.1 - - [21/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-21 00:25:01,553:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230421   000000    000459  ...         0.0        0.0       0
5754  20230421   000500    000959  ...         0.0        0.0       0
5755  20230421   001000    001459  ...         0.0        0.0       0
5756  20230421   001500    001959  ...         0.0        0.0       0
5757  20230421   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 00:25:01,554:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682007899, self.tradeDate='20230421', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28559.6, self.close=28601.3, self.high=28650.0, self.low=28539.4, self.vol=5371.24, self.amt=153643842.525, ukdf['pct'].iloc[-1]=0.001467 , ukdf['amount'].iloc[-1]=153643842.525, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-726638.94615652704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28604.52843254', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1682006699, self.tradeDate='20230421', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=28492.4, self.close=28381.9, self.high=28501.7, self.low=28200.0 

--ukdf-hist--: overDate='20230416' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42153 

self.closeSec=1682006999, self.tradeDate='20230421', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28381.8, self.close=28475.4, self.high=28500.8, self.low=28366.1 
127.0.0.1 - - [21/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42154 

self.closeSec=1682007299, self.tradeDate='20230421', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28477.5, self.close=28529.4, self.high=28533.9, self.low=28443.6 
127.0.0.1 - - [21/Apr/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42155 

self.closeSec=1682007599, self.tradeDate='20230421', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28529.4, self.close=28559.4, self.high=28571.0, self.low=28505.8 
127.0.0.1 - - [21/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42156 

self.closeSec=1682007899, self.tradeDate='20230421', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28559.6, self.close=28601.3, self.high=28650.0, self.low=28539.4 
127.0.0.1 - - [21/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-21 00:00:20,338:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230420    212959  28876.3  ...  50.833333  0.419821  0.671986
5802  20230420    215959  28768.0  ...  51.250000  0.426062  0.661553
5803  20230420    222959  28803.9  ...  50.833333  0.420219  0.654593
5804  20230420    225959  28758.4  ...  50.833333  0.413657  0.651427
5805  20230420    232959  28706.5  ...  50.416667  0.411021  0.649548

[5 rows x 33 columns]
0.5
acc is : 0.5
2023-04-21 00:00:20,432:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510288  0.489712       1  ...  0.992943   1.0    0.0  1.032709
540     0  0.549991  0.450009       0  ...  0.991371   1.0    0.0  1.031074
541     0  0.533253  0.466747       0  ...  0.989589   1.0    0.0  1.029220
542     0  0.519496  0.480504       0  ...  0.988872   1.0    0.0  1.028475
543     0  0.513240  0.486760       0  ...  0.982201   1.0    0.0  1.021537

[5 rows x 10 columns]
2023-04-21 00:00:20,453:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509914  0.490086       1  ...  0.992943   1.0    0.0  1.029159
46     0  0.550218  0.449782       0  ...  0.991371   1.0    0.0  1.029288
47     0  0.533616  0.466384       0  ...  0.989589   1.0    0.0  1.030181
48     0  0.519895  0.480105       0  ...  0.988872   1.0    0.0  1.029434
49     0  0.513240  0.486760       0  ...  0.982201   1.0    0.0  1.021537

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21073 

self.closeSec=1682004599, self.tradeDate='20230420', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28669.2', self.close='28685.8'
127.0.0.1 - - [20/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21074 

self.closeSec=1682005199, self.tradeDate='20230420', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28685.8', self.close='28580.1'
127.0.0.1 - - [20/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21075 

self.closeSec=1682005799, self.tradeDate='20230420', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28580', self.close='28585.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21076 

self.closeSec=1682006399, self.tradeDate='20230420', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28585.1', self.close='28492.3'
127.0.0.1 - - [21/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21077 

self.closeSec=1682006999, self.tradeDate='20230421', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28492.4', self.close='28477.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21078 

self.closeSec=1682007599, self.tradeDate='20230421', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28477.5', self.close='28559.4'
127.0.0.1 - - [21/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21074 

self.closeSec=1682004599, self.tradeDate='20230420', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28669.2', self.close='28685.8'
127.0.0.1 - - [20/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21075 

self.closeSec=1682005199, self.tradeDate='20230420', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28685.8', self.close='28580.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21076 

self.closeSec=1682005799, self.tradeDate='20230420', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28580', self.close='28585.1'
127.0.0.1 - - [20/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21077 

self.closeSec=1682006399, self.tradeDate='20230420', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28585.1', self.close='28492.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21078 

self.closeSec=1682006999, self.tradeDate='20230421', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28492.4', self.close='28477.5'
127.0.0.1 - - [21/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21079 

self.closeSec=1682007599, self.tradeDate='20230421', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28477.5', self.close='28559.4'
127.0.0.1 - - [21/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21074 

self.closeSec=1682004599, self.tradeDate='20230420', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28669.2', self.close='28685.8'
127.0.0.1 - - [20/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21075 

self.closeSec=1682005199, self.tradeDate='20230420', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28685.8', self.close='28580.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21076 

self.closeSec=1682005799, self.tradeDate='20230420', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28580', self.close='28585.1'
127.0.0.1 - - [20/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21077 

self.closeSec=1682006399, self.tradeDate='20230420', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28585.1', self.close='28492.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21078 

self.closeSec=1682006999, self.tradeDate='20230421', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28492.4', self.close='28477.5'
127.0.0.1 - - [21/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21079 

self.closeSec=1682007599, self.tradeDate='20230421', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28477.5', self.close='28559.4'
127.0.0.1 - - [21/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37587
self.closeSec=1682007599, self.tradeDate='20230421', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28529.4, self.close=28559.4, self.high=28571.0, self.low=28505.8, self.vol=4730.103, self.amt=135011202.5957 
127.0.0.1 - - [21/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-21 00:20:05,449:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230420   235500    235959  ...         0.0        0.0       0
5753  20230421   000000    000459  ...         0.0        0.0       0
5754  20230421   000500    000959  ...         0.0        0.0       0
5755  20230421   001000    001459  ...         0.0        0.0       0
5756  20230421   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 00:20:05,467:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682007599, self.tradeDate='20230421', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28529.4, self.close=28559.4, self.high=28571.0, self.low=28505.8, self.vol=4730.103, self.amt=135011202.5957, ukdf['pct'].iloc[-1]=0.001052 , ukdf['amount'].iloc[-1]=135011202.5957, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37588
self.closeSec=1682007899, self.tradeDate='20230421', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28559.6, self.close=28601.3, self.high=28650.0, self.low=28539.4, self.vol=5371.24, self.amt=153643842.525 
127.0.0.1 - - [21/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-21 00:25:01,558:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230421   000000    000459  ...         0.0        0.0       0
5754  20230421   000500    000959  ...         0.0        0.0       0
5755  20230421   001000    001459  ...         0.0        0.0       0
5756  20230421   001500    001959  ...         0.0        0.0       0
5757  20230421   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 00:25:01,564:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682007899, self.tradeDate='20230421', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28559.6, self.close=28601.3, self.high=28650.0, self.low=28539.4, self.vol=5371.24, self.amt=153643842.525, ukdf['pct'].iloc[-1]=0.001467 , ukdf['amount'].iloc[-1]=153643842.525, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230420   120000    155959  1681977599  ...    723  0.494668 -0.082384     NaN
724  20230420   160000    195959  1681991999  ...    724  0.552418  0.039686     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '16239.79340727975', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28579.14104365', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=878
self.closeSec=1682006399, self.tradeDate='20230420', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28601.5, self.close=28492.3, self.high=28940.0, self.low=28300.0, self.vol=164293.111, self.amt=4712963034.64566 
127.0.0.1 - - [21/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-04-21 00:00:02,094:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682006399, self.tradeDate='20230420', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28601.5, self.close=28492.3, self.high=28940.0, self.low=28300.0, self.vol=164293.111, self.amt=4712963034.64566 
2023-04-21 00:00:02,129:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230420   040000    075959  ...  159240.579  4.607687e+09 -0.014224
722  20230420   080000    115959  ...   91900.129  2.647339e+09  0.001910
723  20230420   120000    155959  ...   58959.523  1.704867e+09  0.000263
724  20230420   160000    195959  ...   68189.911  1.961852e+09 -0.008875
725  20230420   200000    235959  ...  164293.111  4.712963e+09 -0.003821

[5 rows x 11 columns]
2023-04-21 00:00:03,949:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230420   040000    075959  1681948799  ...    721  0.375786 -0.336869     NaN
722  20230420   080000    115959  1681963199  ...    722  0.445561 -0.185512     NaN
723  20230420   120000    155959  1681977599  ...    723  0.494668 -0.082384     NaN
724  20230420   160000    195959  1681991999  ...    724  0.552418  0.039686     NaN
725  20230420   200000    235959  1682006399  ...    725  0.579524  0.090516     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '11569.0782567357', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28490.20045238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


