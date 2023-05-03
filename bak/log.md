# 20230504 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45333
self.closeSec=1683130799, self.tradeDate='20230504', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28285.5, self.close=28242.4, self.high=28288.2, self.low=28232.5, self.vol=1583.48, self.amt=44746449.9325 
127.0.0.1 - - [04/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-04 00:20:06,282:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230503   235500    235959  ...         0.0        0.0       0
5760  20230504   000000    000459  ...         0.0        0.0       0
5761  20230504   000500    000959  ...         0.0        0.0       0
5762  20230504   001000    001459  ...         0.0        0.0       0
5763  20230504   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 00:20:06,295:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683130799, self.tradeDate='20230504', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28285.5, self.close=28242.4, self.high=28288.2, self.low=28232.5, self.vol=1583.48, self.amt=44746449.9325, ukdf['pct'].iloc[-1]=-0.001524 , ukdf['amount'].iloc[-1]=44746449.9325, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-704378.38974189184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28234.60426984', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45334
self.closeSec=1683131099, self.tradeDate='20230504', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28242.4, self.close=28373.5, self.high=28384.5, self.low=28230.1, self.vol=3524.799, self.amt=99793263.9038 
127.0.0.1 - - [04/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-04 00:25:02,090:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230504   000000    000459  ...         0.0        0.0       0
5761  20230504   000500    000959  ...         0.0        0.0       0
5762  20230504   001000    001459  ...         0.0        0.0       0
5763  20230504   001500    001959  ...         0.0        0.0       0
5764  20230504   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 00:25:02,092:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683131099, self.tradeDate='20230504', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28242.4, self.close=28373.5, self.high=28384.5, self.low=28230.1, self.vol=3524.799, self.amt=99793263.9038, ukdf['pct'].iloc[-1]=0.004642 , ukdf['amount'].iloc[-1]=99793263.9038, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-712802.7728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28374.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1683129899, self.tradeDate='20230504', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=28292.6, self.close=28289.2, self.high=28306.3, self.low=28280.0 

--ukdf-hist--: overDate='20230429' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [04/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45897 

self.closeSec=1683130199, self.tradeDate='20230504', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28289.2, self.close=28303.5, self.high=28307.0, self.low=28289.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45898 

self.closeSec=1683130499, self.tradeDate='20230504', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28303.5, self.close=28285.5, self.high=28311.0, self.low=28281.1 
127.0.0.1 - - [04/May/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45899 

self.closeSec=1683130799, self.tradeDate='20230504', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28285.5, self.close=28242.4, self.high=28288.2, self.low=28232.5 
127.0.0.1 - - [04/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 00:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45900 

self.closeSec=1683131099, self.tradeDate='20230504', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28242.4, self.close=28373.5, self.high=28384.5, self.low=28230.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-04 00:00:19,716:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230503    212959  28296.3  ...  49.166667  0.450837  0.442099
5802  20230503    215959  28215.6  ...  49.583333  0.477149  0.458263
5803  20230503    222959  28359.1  ...  49.166667  0.455545  0.485353
5804  20230503    225959  28220.0  ...  49.166667  0.453526  0.509218
5805  20230503    232959  28206.6  ...  49.583333  0.456752  0.528945

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-05-04 00:00:19,819:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.461391  0.538609       1  ...  0.922147  -1.0    0.0  1.040002
540     0  0.509883  0.490117       0  ...  0.926670  -1.0    0.0  1.034901
541     1  0.452980  0.547020       0  ...  0.927110  -1.0    0.0  1.034410
542     1  0.476623  0.523377       1  ...  0.926532  -1.0    0.0  1.035055
543     0  0.500729  0.499271       1  ...  0.924283  -1.0    0.0  1.037567

[5 rows x 10 columns]
2023-05-04 00:00:19,837:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.461690  0.538310       1  ...  0.922147  -1.0    0.0  1.038662
46     0  0.509960  0.490040       0  ...  0.926670  -1.0    0.0  1.032387
47     1  0.453183  0.546817       0  ...  0.927110  -1.0    0.0  1.032502
48     1  0.476868  0.523132       1  ...  0.926532  -1.0    0.0  1.033146
49     0  0.500729  0.499271       1  ...  0.924283  -1.0    0.0  1.037567

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22945 

self.closeSec=1683127799, self.tradeDate='20230503', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28266.2', self.close='28224.2'
127.0.0.1 - - [03/May/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22946 

self.closeSec=1683128399, self.tradeDate='20230503', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28224.2', self.close='28298.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22947 

self.closeSec=1683128999, self.tradeDate='20230503', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28298.2', self.close='28276.3'
127.0.0.1 - - [03/May/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22948 

self.closeSec=1683129599, self.tradeDate='20230503', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28276.2', self.close='28292.7'
127.0.0.1 - - [04/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22949 

self.closeSec=1683130199, self.tradeDate='20230504', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28292.6', self.close='28303.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22950 

self.closeSec=1683130799, self.tradeDate='20230504', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28303.5', self.close='28242.4'
127.0.0.1 - - [04/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22946 

self.closeSec=1683127799, self.tradeDate='20230503', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28266.2', self.close='28224.2'
127.0.0.1 - - [03/May/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22947 

self.closeSec=1683128399, self.tradeDate='20230503', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28224.2', self.close='28298.6'
127.0.0.1 - - [03/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22948 

self.closeSec=1683128999, self.tradeDate='20230503', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28298.2', self.close='28276.3'
127.0.0.1 - - [03/May/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22949 

self.closeSec=1683129599, self.tradeDate='20230503', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28276.2', self.close='28292.7'
127.0.0.1 - - [04/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22950 

self.closeSec=1683130199, self.tradeDate='20230504', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28292.6', self.close='28303.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22951 

self.closeSec=1683130799, self.tradeDate='20230504', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28303.5', self.close='28242.4'
127.0.0.1 - - [04/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22946 

self.closeSec=1683127799, self.tradeDate='20230503', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28266.2', self.close='28224.2'
127.0.0.1 - - [03/May/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22947 

self.closeSec=1683128399, self.tradeDate='20230503', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28224.2', self.close='28298.6'
127.0.0.1 - - [03/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22948 

self.closeSec=1683128999, self.tradeDate='20230503', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28298.2', self.close='28276.3'
127.0.0.1 - - [03/May/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22949 

self.closeSec=1683129599, self.tradeDate='20230503', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28276.2', self.close='28292.7'
127.0.0.1 - - [04/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22950 

self.closeSec=1683130199, self.tradeDate='20230504', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28292.6', self.close='28303.5'
127.0.0.1 - - [04/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22951 

self.closeSec=1683130799, self.tradeDate='20230504', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28303.5', self.close='28242.4'
127.0.0.1 - - [04/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41331
self.closeSec=1683130799, self.tradeDate='20230504', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28285.5, self.close=28242.4, self.high=28288.2, self.low=28232.5, self.vol=1583.48, self.amt=44746449.9325 
127.0.0.1 - - [04/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-04 00:20:06,221:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230503   235500    235959  ...         0.0        0.0       0
5760  20230504   000000    000459  ...         0.0        0.0       0
5761  20230504   000500    000959  ...         0.0        0.0       0
5762  20230504   001000    001459  ...         0.0        0.0       0
5763  20230504   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 00:20:06,235:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683130799, self.tradeDate='20230504', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28285.5, self.close=28242.4, self.high=28288.2, self.low=28232.5, self.vol=1583.48, self.amt=44746449.9325, ukdf['pct'].iloc[-1]=-0.001524 , ukdf['amount'].iloc[-1]=44746449.9325, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41332
self.closeSec=1683131099, self.tradeDate='20230504', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28242.4, self.close=28373.5, self.high=28384.5, self.low=28230.1, self.vol=3524.799, self.amt=99793263.9038 
127.0.0.1 - - [04/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-04 00:25:02,110:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230504   000000    000459  ...         0.0        0.0       0
5761  20230504   000500    000959  ...         0.0        0.0       0
5762  20230504   001000    001459  ...         0.0        0.0       0
5763  20230504   001500    001959  ...         0.0        0.0       0
5764  20230504   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 00:25:02,111:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683131099, self.tradeDate='20230504', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28242.4, self.close=28373.5, self.high=28384.5, self.low=28230.1, self.vol=3524.799, self.amt=99793263.9038, ukdf['pct'].iloc[-1]=0.004642 , ukdf['amount'].iloc[-1]=99793263.9038, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230503   120000    155959  1683100799  ...    723  0.575571 -0.147166     NaN
724  20230503   160000    195959  1683115199  ...    724  0.584878 -0.120900     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '37752.79034850078', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28533.20054479', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=956
self.closeSec=1683129599, self.tradeDate='20230503', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28535.0, self.close=28292.7, self.high=28567.0, self.low=28080.0, self.vol=135071.937, self.amt=3821706071.46254 
127.0.0.1 - - [04/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-04 00:00:03,193:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683129599, self.tradeDate='20230503', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28535.0, self.close=28292.7, self.high=28567.0, self.low=28080.0, self.vol=135071.937, self.amt=3821706071.46254 
2023-05-04 00:00:03,258:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230503   040000    075959  ...   48455.705  1.390300e+09 -0.000589
722  20230503   080000    115959  ...   58108.623  1.656345e+09 -0.005273
723  20230503   120000    155959  ...   44177.432  1.261075e+09  0.004662
724  20230503   160000    195959  ...   52280.691  1.497084e+09 -0.003607
725  20230503   200000    235959  ...  135071.937  3.821706e+09 -0.008491

[5 rows x 11 columns]
2023-05-04 00:00:04,805:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230503   040000    075959  1683071999  ...    721  0.553597 -0.218806     NaN
722  20230503   080000    115959  1683086399  ...    722  0.566359 -0.177206     NaN
723  20230503   120000    155959  1683100799  ...    723  0.575571 -0.147166     NaN
724  20230503   160000    195959  1683115199  ...    724  0.584878 -0.120900     NaN
725  20230503   200000    235959  1683129599  ...    725  0.606136 -0.059211     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '48879.43700530744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28295.03438492', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


