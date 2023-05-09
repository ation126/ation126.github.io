# 20230510 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47061
self.closeSec=1683649199, self.tradeDate='20230510', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27437.8, self.close=27453.8, self.high=27486.7, self.low=27435.9, self.vol=2053.513, self.amt=56389119.2117 
127.0.0.1 - - [10/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-10 00:20:06,188:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230509   235500    235959  ...         0.0        0.0       0
5760  20230510   000000    000459  ...         0.0        0.0       0
5761  20230510   000500    000959  ...         0.0        0.0       0
5762  20230510   001000    001459  ...         0.0        0.0       0
5763  20230510   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 00:20:06,191:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683649199, self.tradeDate='20230510', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27437.8, self.close=27453.8, self.high=27486.7, self.low=27435.9, self.vol=2053.513, self.amt=56389119.2117, ukdf['pct'].iloc[-1]=0.000583 , ukdf['amount'].iloc[-1]=56389119.2117, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-657216.57161389152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27450.87291302', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47062
self.closeSec=1683649499, self.tradeDate='20230510', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27453.8, self.close=27395.0, self.high=27469.5, self.low=27380.2, self.vol=2166.086, self.amt=59380091.5642 
127.0.0.1 - - [10/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-10 00:25:02,072:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230510   000000    000459  ...         0.0        0.0       0
5761  20230510   000500    000959  ...         0.0        0.0       0
5762  20230510   001000    001459  ...         0.0        0.0       0
5763  20230510   001500    001959  ...         0.0        0.0       0
5764  20230510   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 00:25:02,073:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683649499, self.tradeDate='20230510', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27453.8, self.close=27395.0, self.high=27469.5, self.low=27380.2, self.vol=2166.086, self.amt=59380091.5642, ukdf['pct'].iloc[-1]=-0.002142 , ukdf['amount'].iloc[-1]=59380091.5642, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-653848.3456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27394.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [10/May/2023 00:05:02] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230505' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47625 

self.closeSec=1683648599, self.tradeDate='20230510', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27348.4, self.close=27416.9, self.high=27439.0, self.low=27334.6 
127.0.0.1 - - [10/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47626 

self.closeSec=1683648899, self.tradeDate='20230510', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27416.9, self.close=27437.8, self.high=27439.0, self.low=27379.4 
127.0.0.1 - - [10/May/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47627 

self.closeSec=1683649199, self.tradeDate='20230510', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27437.8, self.close=27453.8, self.high=27486.7, self.low=27435.9 
127.0.0.1 - - [10/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 00:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47628 

self.closeSec=1683649499, self.tradeDate='20230510', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27453.8, self.close=27395.0, self.high=27469.5, self.low=27380.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-10 00:00:21,273:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230509    212959  27744.9  ...  49.166667  0.448166  0.549987
5802  20230509    215959  27692.1  ...  49.166667  0.434486  0.538098
5803  20230509    222959  27605.4  ...  48.750000  0.404594  0.551211
5804  20230509    225959  27399.9  ...  49.166667  0.428633  0.548940
5805  20230509    232959  27523.1  ...  48.750000  0.421676  0.552632

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-05-10 00:00:21,376:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.505833  0.494167       0  ...  0.991901  -1.0    0.0  0.936605
540     1  0.491782  0.508218       0  ...  0.999281  -1.0    0.0  0.929636
541     1  0.449031  0.550969       1  ...  0.994791  -1.0    0.0  0.933813
542     0  0.504188  0.495812       0  ...  0.996573  -1.0    0.0  0.932140
543     1  0.473936  0.526064       0  ...  0.999765  -1.0    0.0  0.929154

[5 rows x 10 columns]
2023-05-10 00:00:21,387:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506043  0.493957       0  ...  0.971027  -1.0    0.0  0.938225
46     1  0.491787  0.508213       0  ...  0.999281  -1.0    0.0  0.930103
47     1  0.449265  0.550735       1  ...  0.994791  -1.0    0.0  0.934894
48     0  0.504362  0.495638       0  ...  0.996573  -1.0    0.0  0.933220
49     1  0.473936  0.526064       0  ...  0.999765  -1.0    0.0  0.929154

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [09/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23809 

self.closeSec=1683646199, self.tradeDate='20230509', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27506.5', self.close='27473.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23810 

self.closeSec=1683646799, self.tradeDate='20230509', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27473.8', self.close='27476'
127.0.0.1 - - [09/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23811 

self.closeSec=1683647399, self.tradeDate='20230509', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27475.9', self.close='27444.3'
127.0.0.1 - - [09/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23812 

self.closeSec=1683647999, self.tradeDate='20230509', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27444.3', self.close='27385.8'
127.0.0.1 - - [10/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23813 

self.closeSec=1683648599, self.tradeDate='20230510', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27385.8', self.close='27416.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23814 

self.closeSec=1683649199, self.tradeDate='20230510', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27416.9', self.close='27453.8'
127.0.0.1 - - [10/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23810 

self.closeSec=1683646199, self.tradeDate='20230509', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27506.5', self.close='27473.8'
127.0.0.1 - - [09/May/2023 23:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23811 

self.closeSec=1683646799, self.tradeDate='20230509', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27473.8', self.close='27476'
127.0.0.1 - - [09/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23812 

self.closeSec=1683647399, self.tradeDate='20230509', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27475.9', self.close='27444.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23813 

self.closeSec=1683647999, self.tradeDate='20230509', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27444.3', self.close='27385.8'
127.0.0.1 - - [10/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23814 

self.closeSec=1683648599, self.tradeDate='20230510', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27385.8', self.close='27416.9'
127.0.0.1 - - [10/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23815 

self.closeSec=1683649199, self.tradeDate='20230510', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27416.9', self.close='27453.8'
127.0.0.1 - - [10/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23810 

self.closeSec=1683646199, self.tradeDate='20230509', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27506.5', self.close='27473.8'
127.0.0.1 - - [09/May/2023 23:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23811 

self.closeSec=1683646799, self.tradeDate='20230509', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27473.8', self.close='27476'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23812 

self.closeSec=1683647399, self.tradeDate='20230509', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27475.9', self.close='27444.3'
127.0.0.1 - - [09/May/2023 23:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23813 

self.closeSec=1683647999, self.tradeDate='20230509', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27444.3', self.close='27385.8'
127.0.0.1 - - [10/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23814 

self.closeSec=1683648599, self.tradeDate='20230510', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27385.8', self.close='27416.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23815 

self.closeSec=1683649199, self.tradeDate='20230510', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27416.9', self.close='27453.8'
127.0.0.1 - - [10/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43059
self.closeSec=1683649199, self.tradeDate='20230510', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27437.8, self.close=27453.8, self.high=27486.7, self.low=27435.9, self.vol=2053.513, self.amt=56389119.2117 
127.0.0.1 - - [10/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-10 00:20:06,186:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230509   235500    235959  ...         0.0        0.0       0
5760  20230510   000000    000459  ...         0.0        0.0       0
5761  20230510   000500    000959  ...         0.0        0.0       0
5762  20230510   001000    001459  ...         0.0        0.0       0
5763  20230510   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 00:20:06,190:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683649199, self.tradeDate='20230510', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27437.8, self.close=27453.8, self.high=27486.7, self.low=27435.9, self.vol=2053.513, self.amt=56389119.2117, ukdf['pct'].iloc[-1]=0.000583 , ukdf['amount'].iloc[-1]=56389119.2117, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43060
self.closeSec=1683649499, self.tradeDate='20230510', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27453.8, self.close=27395.0, self.high=27469.5, self.low=27380.2, self.vol=2166.086, self.amt=59380091.5642 
127.0.0.1 - - [10/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-10 00:25:02,070:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230510   000000    000459  ...         0.0        0.0       0
5761  20230510   000500    000959  ...         0.0        0.0       0
5762  20230510   001000    001459  ...         0.0        0.0       0
5763  20230510   001500    001959  ...         0.0        0.0       0
5764  20230510   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 00:25:02,071:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683649499, self.tradeDate='20230510', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27453.8, self.close=27395.0, self.high=27469.5, self.low=27380.2, self.vol=2166.086, self.amt=59380091.5642, ukdf['pct'].iloc[-1]=-0.002142 , ukdf['amount'].iloc[-1]=59380091.5642, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230509   120000    155959  1683619199  ...    723  0.764124  0.834596     1.0
724  20230509   160000    195959  1683633599  ...    724  0.808445  1.003837     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '3045.058', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27668.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [10/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1448108.3022399, self.flagDict['side']='buy', self.tradeCount=34, self.count=992
self.closeSec=1683647999, self.tradeDate='20230509', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27663.9, self.close=27385.8, self.high=27815.6, self.low=27316.8, self.vol=119288.926, self.amt=3290036429.48026 
2023-05-10 00:00:03,128:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683647999, self.tradeDate='20230509', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27663.9, self.close=27385.8, self.high=27815.6, self.low=27316.8, self.vol=119288.926, self.amt=3290036429.48026 
2023-05-10 00:00:03,169:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230509   040000    075959  ...   65257.965  1.794462e+09  0.012101
722  20230509   080000    115959  ...   46056.079  1.272192e+09 -0.001710
723  20230509   120000    155959  ...   47560.102  1.310025e+09  0.001333
724  20230509   160000    195959  ...   42312.157  1.167581e+09  0.000528
725  20230509   200000    235959  ...  119288.926  3.290036e+09 -0.010053

[5 rows x 11 columns]
2023-05-10 00:00:04,879:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230509   040000    075959  1683590399  ...    721  0.663889  0.466367     NaN
722  20230509   080000    115959  1683604799  ...    722  0.727677  0.697560     1.0
723  20230509   120000    155959  1683619199  ...    723  0.764124  0.834596     1.0
724  20230509   160000    195959  1683633599  ...    724  0.808445  1.003837     1.0
725  20230509   200000    235959  1683647999  ...    725  0.826353  1.084247     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '-11508.2192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27390.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


