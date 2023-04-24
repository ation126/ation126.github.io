# 20230425 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42741
self.closeSec=1682353199, self.tradeDate='20230425', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27290.5, self.close=27318.5, self.high=27320.0, self.low=27251.7, self.vol=1980.468, self.amt=54035658.0323 
127.0.0.1 - - [25/Apr/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-04-25 00:20:01,761:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230424   235500    235959  ...         0.0        0.0       0
5753  20230425   000000    000459  ...         0.0        0.0       0
5754  20230425   000500    000959  ...         0.0        0.0       0
5755  20230425   001000    001459  ...         0.0        0.0       0
5756  20230425   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 00:20:01,763:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682353199, self.tradeDate='20230425', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27290.5, self.close=27318.5, self.high=27320.0, self.low=27251.7, self.vol=1980.468, self.amt=54035658.0323, ukdf['pct'].iloc[-1]=0.001022 , ukdf['amount'].iloc[-1]=54035658.0323, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-649401.3392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27321', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42742
self.closeSec=1682353499, self.tradeDate='20230425', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27318.6, self.close=27336.0, self.high=27360.9, self.low=27305.6, self.vol=2519.968, self.amt=68875923.0682 
127.0.0.1 - - [25/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-25 00:25:01,611:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230425   000000    000459  ...         0.0        0.0       0
5754  20230425   000500    000959  ...         0.0        0.0       0
5755  20230425   001000    001459  ...         0.0        0.0       0
5756  20230425   001500    001959  ...         0.0        0.0       0
5757  20230425   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 00:25:01,612:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682353499, self.tradeDate='20230425', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27318.6, self.close=27336.0, self.high=27360.9, self.low=27305.6, self.vol=2519.968, self.amt=68875923.0682, ukdf['pct'].iloc[-1]=0.000641 , ukdf['amount'].iloc[-1]=68875923.0682, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-650303.9792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27336', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [25/Apr/2023 00:05:02] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230420' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [25/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43305 

self.closeSec=1682352599, self.tradeDate='20230425', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27318.8, self.close=27288.8, self.high=27322.5, self.low=27267.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43306 

self.closeSec=1682352899, self.tradeDate='20230425', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27288.8, self.close=27290.6, self.high=27300.0, self.low=27280.0 
127.0.0.1 - - [25/Apr/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43307 

self.closeSec=1682353199, self.tradeDate='20230425', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27290.5, self.close=27318.5, self.high=27320.0, self.low=27251.7 
127.0.0.1 - - [25/Apr/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43308 

self.closeSec=1682353499, self.tradeDate='20230425', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27318.6, self.close=27336.0, self.high=27360.9, self.low=27305.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-25 00:00:22,540:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230424    212959  27431.3  ...  50.000000  0.466453  0.615942
5802  20230424    215959  27402.9  ...  50.000000  0.503777  0.604964
5803  20230424    222959  27611.9  ...  49.583333  0.501671  0.595672
5804  20230424    225959  27600.0  ...  49.583333  0.471756  0.601170
5805  20230424    232959  27416.7  ...  49.583333  0.444544  0.620557

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-04-25 00:00:22,668:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.505678  0.494322       1  ...  0.856863   1.0    0.0  0.918712
540     0  0.572917  0.427083       0  ...  0.856481   1.0    0.0  0.918303
541     0  0.513663  0.486337       0  ...  0.850809   1.0    0.0  0.912221
542     1  0.469458  0.530542       0  ...  0.845102   1.0    0.0  0.906102
543     1  0.460023  0.539977       1  ...  0.845819   1.0    0.0  0.906871

[5 rows x 10 columns]
2023-04-25 00:00:22,692:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506051  0.493949       1  ...  0.856863   1.0    0.0  0.918566
46     0  0.573615  0.426385       0  ...  0.866954   1.0    0.0  0.919977
47     0  0.513509  0.486491       0  ...  0.850809   1.0    0.0  0.912464
48     1  0.469766  0.530234       0  ...  0.845102   1.0    0.0  0.906343
49     1  0.460023  0.539977       1  ...  0.845819   1.0    0.0  0.906871

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21649 

self.closeSec=1682350199, self.tradeDate='20230424', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27329.9', self.close='27232.9'
127.0.0.1 - - [24/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21650 

self.closeSec=1682350799, self.tradeDate='20230424', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27232.9', self.close='27276.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21651 

self.closeSec=1682351399, self.tradeDate='20230424', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27276.9', self.close='27230.1'
127.0.0.1 - - [24/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21652 

self.closeSec=1682351999, self.tradeDate='20230424', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27230.1', self.close='27256'
127.0.0.1 - - [25/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21653 

self.closeSec=1682352599, self.tradeDate='20230425', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27255.9', self.close='27288.8'
127.0.0.1 - - [25/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21654 

self.closeSec=1682353199, self.tradeDate='20230425', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27288.8', self.close='27318.6'
127.0.0.1 - - [25/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [24/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21650 

self.closeSec=1682350199, self.tradeDate='20230424', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27329.9', self.close='27232.9'
127.0.0.1 - - [24/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21651 

self.closeSec=1682350799, self.tradeDate='20230424', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27232.9', self.close='27276.9'
127.0.0.1 - - [24/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21652 

self.closeSec=1682351399, self.tradeDate='20230424', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27276.9', self.close='27230.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21653 

self.closeSec=1682351999, self.tradeDate='20230424', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27230.1', self.close='27256'
127.0.0.1 - - [25/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21654 

self.closeSec=1682352599, self.tradeDate='20230425', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27255.9', self.close='27288.8'
127.0.0.1 - - [25/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21655 

self.closeSec=1682353199, self.tradeDate='20230425', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27288.8', self.close='27318.6'
127.0.0.1 - - [25/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21650 

self.closeSec=1682350199, self.tradeDate='20230424', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27329.9', self.close='27232.9'
127.0.0.1 - - [24/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21651 

self.closeSec=1682350799, self.tradeDate='20230424', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27232.9', self.close='27276.9'
127.0.0.1 - - [24/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21652 

self.closeSec=1682351399, self.tradeDate='20230424', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27276.9', self.close='27230.1'
127.0.0.1 - - [24/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21653 

self.closeSec=1682351999, self.tradeDate='20230424', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27230.1', self.close='27256'
127.0.0.1 - - [25/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21654 

self.closeSec=1682352599, self.tradeDate='20230425', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27255.9', self.close='27288.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21655 

self.closeSec=1682353199, self.tradeDate='20230425', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27288.8', self.close='27318.6'
127.0.0.1 - - [25/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38739
self.closeSec=1682353199, self.tradeDate='20230425', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27290.5, self.close=27318.5, self.high=27320.0, self.low=27251.7, self.vol=1980.468, self.amt=54035658.0323 
127.0.0.1 - - [25/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-04-25 00:20:04,365:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230424   235500    235959  ...         0.0        0.0       0
5753  20230425   000000    000459  ...         0.0        0.0       0
5754  20230425   000500    000959  ...         0.0        0.0       0
5755  20230425   001000    001459  ...         0.0        0.0       0
5756  20230425   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 00:20:04,369:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682353199, self.tradeDate='20230425', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27290.5, self.close=27318.5, self.high=27320.0, self.low=27251.7, self.vol=1980.468, self.amt=54035658.0323, ukdf['pct'].iloc[-1]=0.001022 , ukdf['amount'].iloc[-1]=54035658.0323, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [25/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38740
self.closeSec=1682353499, self.tradeDate='20230425', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27318.6, self.close=27336.0, self.high=27360.9, self.low=27305.6, self.vol=2519.968, self.amt=68875923.0682 
2023-04-25 00:25:01,601:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230425   000000    000459  ...         0.0        0.0       0
5754  20230425   000500    000959  ...         0.0        0.0       0
5755  20230425   001000    001459  ...         0.0        0.0       0
5756  20230425   001500    001959  ...         0.0        0.0       0
5757  20230425   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 00:25:01,602:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682353499, self.tradeDate='20230425', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27318.6, self.close=27336.0, self.high=27360.9, self.low=27305.6, self.vol=2519.968, self.amt=68875923.0682, ukdf['pct'].iloc[-1]=0.000641 , ukdf['amount'].iloc[-1]=68875923.0682, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230424   120000    155959  1682323199  ...    723  0.946303  0.563779     NaN
724  20230424   160000    195959  1682337599  ...    724  1.007050  0.697512     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-37915.83', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27547.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=902
self.closeSec=1682351999, self.tradeDate='20230424', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27539.9, self.close=27256.0, self.high=27700.0, self.low=27208.0, self.vol=135196.378, self.amt=3711698212.98184 
127.0.0.1 - - [25/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-25 00:00:01,785:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682351999, self.tradeDate='20230424', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27539.9, self.close=27256.0, self.high=27700.0, self.low=27208.0, self.vol=135196.378, self.amt=3711698212.98184 
2023-04-25 00:00:01,825:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230424   040000    075959  ...   37569.391  1.034168e+09  0.004469
722  20230424   080000    115959  ...   99571.446  2.762542e+09  0.007398
723  20230424   120000    155959  ...   65884.391  1.814763e+09 -0.012210
724  20230424   160000    195959  ...  101737.772  2.780949e+09  0.003615
725  20230424   200000    235959  ...  135196.378  3.711698e+09 -0.010312

[5 rows x 11 columns]
2023-04-25 00:00:03,347:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230424   040000    075959  1682294399  ...    721  1.101631  0.980042     1.0
722  20230424   080000    115959  1682308799  ...    722  0.986282  0.678939     1.0
723  20230424   120000    155959  1682323199  ...    723  0.946303  0.563779     NaN
724  20230424   160000    195959  1682337599  ...    724  1.007050  0.697512     1.0
725  20230424   200000    235959  1682351999  ...    725  1.016895  0.705436     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-53560.0485', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27250', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


