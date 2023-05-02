# 20230503 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45045
self.closeSec=1683044399, self.tradeDate='20230503', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28466.6, self.close=28488.4, self.high=28492.1, self.low=28430.9, self.vol=3609.356, self.amt=102686382.5518 
127.0.0.1 - - [03/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-03 00:20:06,108:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230502   235500    235959  ...         0.0        0.0       0
5760  20230503   000000    000459  ...         0.0        0.0       0
5761  20230503   000500    000959  ...         0.0        0.0       0
5762  20230503   001000    001459  ...         0.0        0.0       0
5763  20230503   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 00:20:06,118:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683044399, self.tradeDate='20230503', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28466.6, self.close=28488.4, self.high=28492.1, self.low=28430.9, self.vol=3609.356, self.amt=102686382.5518, ukdf['pct'].iloc[-1]=0.000769 , ukdf['amount'].iloc[-1]=102686382.5518, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-719921.5936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28492.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45046
self.closeSec=1683044699, self.tradeDate='20230503', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28488.4, self.close=28491.9, self.high=28519.0, self.low=28451.5, self.vol=2247.32, self.amt=64017856.7804 
127.0.0.1 - - [03/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-03 00:25:02,158:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230503   000000    000459  ...         0.0        0.0       0
5761  20230503   000500    000959  ...         0.0        0.0       0
5762  20230503   001000    001459  ...         0.0        0.0       0
5763  20230503   001500    001959  ...         0.0        0.0       0
5764  20230503   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 00:25:02,159:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683044699, self.tradeDate='20230503', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28488.4, self.close=28491.9, self.high=28519.0, self.low=28451.5, self.vol=2247.32, self.amt=64017856.7804, ukdf['pct'].iloc[-1]=0.000123 , ukdf['amount'].iloc[-1]=64017856.7804, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-720276.632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28498.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1683043499, self.tradeDate='20230503', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=28521.0, self.close=28554.4, self.high=28554.6, self.low=28492.6 

--ukdf-hist--: overDate='20230428' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [03/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45609 

self.closeSec=1683043799, self.tradeDate='20230503', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28554.4, self.close=28529.4, self.high=28608.2, self.low=28508.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45610 

self.closeSec=1683044099, self.tradeDate='20230503', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28529.4, self.close=28466.5, self.high=28529.4, self.low=28459.2 
127.0.0.1 - - [03/May/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45611 

self.closeSec=1683044399, self.tradeDate='20230503', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28466.6, self.close=28488.4, self.high=28492.1, self.low=28430.9 
127.0.0.1 - - [03/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 00:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45612 

self.closeSec=1683044699, self.tradeDate='20230503', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28488.4, self.close=28491.9, self.high=28519.0, self.low=28451.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-03 00:00:19,362:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230502    212959  28095.7  ...  48.750000  0.438200  0.607483
5802  20230502    215959  28048.3  ...  48.333333  0.430179  0.597101
5803  20230502    222959  27994.9  ...  48.333333  0.513374  0.561724
5804  20230502    225959  28484.6  ...  48.333333  0.494320  0.542529
5805  20230502    232959  28357.9  ...  48.333333  0.514061  0.515319

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-05-03 00:00:19,463:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.512409  0.487591       0  ...  0.895439   1.0    0.0  0.994776
540     0  0.503459  0.496541       1  ...  0.911102   1.0    0.0  1.012178
541     0  0.635447  0.364553       0  ...  0.907050   1.0    0.0  1.007675
542     0  0.517022  0.482978       1  ...  0.911397   1.0    0.0  1.012504
543     0  0.569931  0.430069       1  ...  0.912414   1.0    0.0  1.013634

[5 rows x 10 columns]
2023-05-03 00:00:19,481:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511906  0.488094       0  ...  0.875917   1.0    0.0  0.994391
46     0  0.503480  0.496520       1  ...  0.891239   1.0    0.0  1.020888
47     0  0.635612  0.364388       0  ...  0.896441   1.0    0.0  1.018153
48     0  0.517207  0.482793       1  ...  0.900737   1.0    0.0  1.023032
49     0  0.569931  0.430069       1  ...  0.912414   1.0    0.0  1.013634

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22801 

self.closeSec=1683041399, self.tradeDate='20230502', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28519.5', self.close='28493.8'
127.0.0.1 - - [02/May/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22802 

self.closeSec=1683041999, self.tradeDate='20230502', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28493.8', self.close='28560'
127.0.0.1 - - [02/May/2023 23:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/May/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22803 

self.closeSec=1683042599, self.tradeDate='20230502', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28559.9', self.close='28592.8'
127.0.0.1 - - [03/May/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22804 

self.closeSec=1683043199, self.tradeDate='20230502', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28592.8', self.close='28525.6'
127.0.0.1 - - [03/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22805 

self.closeSec=1683043799, self.tradeDate='20230503', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28521', self.close='28529.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22806 

self.closeSec=1683044399, self.tradeDate='20230503', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28529.4', self.close='28488.4'
127.0.0.1 - - [03/May/2023 00:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22802 

self.closeSec=1683041399, self.tradeDate='20230502', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28519.5', self.close='28493.8'
127.0.0.1 - - [02/May/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22803 

self.closeSec=1683041999, self.tradeDate='20230502', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28493.8', self.close='28560'
127.0.0.1 - - [02/May/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22804 

self.closeSec=1683042599, self.tradeDate='20230502', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28559.9', self.close='28592.8'

--handleKline--:  127.0.0.1 - - [03/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22805 

self.closeSec=1683043199, self.tradeDate='20230502', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28592.8', self.close='28525.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22806 

self.closeSec=1683043799, self.tradeDate='20230503', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28521', self.close='28529.4'
127.0.0.1 - - [03/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22807 

self.closeSec=1683044399, self.tradeDate='20230503', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28529.4', self.close='28488.4'
127.0.0.1 - - [03/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22802 

self.closeSec=1683041399, self.tradeDate='20230502', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28519.5', self.close='28493.8'
127.0.0.1 - - [02/May/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22803 

self.closeSec=1683041999, self.tradeDate='20230502', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28493.8', self.close='28560'
127.0.0.1 - - [02/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22804 

self.closeSec=1683042599, self.tradeDate='20230502', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28559.9', self.close='28592.8'
127.0.0.1 - - [02/May/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22805 

self.closeSec=1683043199, self.tradeDate='20230502', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28592.8', self.close='28525.6'
127.0.0.1 - - [03/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22806 

self.closeSec=1683043799, self.tradeDate='20230503', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28521', self.close='28529.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22807 

self.closeSec=1683044399, self.tradeDate='20230503', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28529.4', self.close='28488.4'
127.0.0.1 - - [03/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41043
self.closeSec=1683044399, self.tradeDate='20230503', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28466.6, self.close=28488.4, self.high=28492.1, self.low=28430.9, self.vol=3609.356, self.amt=102686382.5518 
127.0.0.1 - - [03/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-03 00:20:06,106:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230502   235500    235959  ...         0.0        0.0       0
5760  20230503   000000    000459  ...         0.0        0.0       0
5761  20230503   000500    000959  ...         0.0        0.0       0
5762  20230503   001000    001459  ...         0.0        0.0       0
5763  20230503   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 00:20:06,117:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683044399, self.tradeDate='20230503', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28466.6, self.close=28488.4, self.high=28492.1, self.low=28430.9, self.vol=3609.356, self.amt=102686382.5518, ukdf['pct'].iloc[-1]=0.000769 , ukdf['amount'].iloc[-1]=102686382.5518, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41044
self.closeSec=1683044699, self.tradeDate='20230503', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28488.4, self.close=28491.9, self.high=28519.0, self.low=28451.5, self.vol=2247.32, self.amt=64017856.7804 
2023-05-03 00:25:02,157:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230503   000000    000459  ...         0.0        0.0       0
5761  20230503   000500    000959  ...         0.0        0.0       0
5762  20230503   001000    001459  ...         0.0        0.0       0
5763  20230503   001500    001959  ...         0.0        0.0       0
5764  20230503   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 00:25:02,158:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683044699, self.tradeDate='20230503', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28488.4, self.close=28491.9, self.high=28519.0, self.low=28451.5, self.vol=2247.32, self.amt=64017856.7804, ukdf['pct'].iloc[-1]=0.000123 , ukdf['amount'].iloc[-1]=64017856.7804, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230502   120000    155959  1683014399  ...    723  0.582597 -0.113055     NaN
724  20230502   160000    195959  1683028799  ...    724  0.643078  0.057836     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '59098.27', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28076.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [03/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=950
self.closeSec=1683043199, self.tradeDate='20230502', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28076.2, self.close=28525.6, self.high=28778.0, self.low=27900.0, self.vol=231567.459, self.amt=6564338573.72697 
2023-05-03 00:00:01,824:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683043199, self.tradeDate='20230502', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28076.2, self.close=28525.6, self.high=28778.0, self.low=27900.0, self.vol=231567.459, self.amt=6564338573.72697 
2023-05-03 00:00:01,880:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230502   040000    075959  ...   85032.810  2.372994e+09  0.007922
722  20230502   080000    115959  ...   44341.090  1.241580e+09 -0.000802
723  20230502   120000    155959  ...   39868.257  1.116407e+09  0.000467
724  20230502   160000    195959  ...   39176.734  1.097673e+09  0.001109
725  20230502   200000    235959  ...  231567.459  6.564339e+09  0.016010

[5 rows x 11 columns]
2023-05-03 00:00:03,721:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230502   040000    075959  1682985599  ...    721  0.467685 -0.435252     NaN
722  20230502   080000    115959  1682999999  ...    722  0.530782 -0.259239     NaN
723  20230502   120000    155959  1683014399  ...    723  0.582597 -0.113055     NaN
724  20230502   160000    195959  1683028799  ...    724  0.643078  0.057836     NaN
725  20230502   200000    235959  1683043199  ...    725  0.567059 -0.178762     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '38220.50580498906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28523.18908333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


