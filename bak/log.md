# 20230513 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47925
self.closeSec=1683908399, self.tradeDate='20230513', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26300.4, self.close=26354.3, self.high=26398.2, self.low=26296.4, self.vol=3765.469, self.amt=99224290.6845 
127.0.0.1 - - [13/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-13 00:20:06,572:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230512   235500    235959  ...         0.0        0.0       0
5760  20230513   000000    000459  ...         0.0        0.0       0
5761  20230513   000500    000959  ...         0.0        0.0       0
5762  20230513   001000    001459  ...         0.0        0.0       0
5763  20230513   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 00:20:06,576:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683908399, self.tradeDate='20230513', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26300.4, self.close=26354.3, self.high=26398.2, self.low=26296.4, self.vol=3765.469, self.amt=99224290.6845, ukdf['pct'].iloc[-1]=0.002046 , ukdf['amount'].iloc[-1]=99224290.6845, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-591542.1152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26359.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47926
self.closeSec=1683908699, self.tradeDate='20230513', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26354.3, self.close=26334.8, self.high=26362.0, self.low=26320.1, self.vol=1717.177, self.amt=45227887.111 
127.0.0.1 - - [13/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-13 00:25:02,224:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230513   000000    000459  ...         0.0        0.0       0
5761  20230513   000500    000959  ...         0.0        0.0       0
5762  20230513   001000    001459  ...         0.0        0.0       0
5763  20230513   001500    001959  ...         0.0        0.0       0
5764  20230513   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 00:25:02,224:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683908699, self.tradeDate='20230513', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26354.3, self.close=26334.8, self.high=26362.0, self.low=26320.1, self.vol=1717.177, self.amt=45227887.111, ukdf['pct'].iloc[-1]=-0.00074 , ukdf['amount'].iloc[-1]=45227887.111, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-590055.768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26334.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [13/May/2023 00:05:02] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230508' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [13/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48489 

self.closeSec=1683907799, self.tradeDate='20230513', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26290.0, self.close=26250.7, self.high=26308.1, self.low=26225.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48490 

self.closeSec=1683908099, self.tradeDate='20230513', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26250.9, self.close=26300.5, self.high=26304.1, self.low=26248.1 
127.0.0.1 - - [13/May/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48491 

self.closeSec=1683908399, self.tradeDate='20230513', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26300.4, self.close=26354.3, self.high=26398.2, self.low=26296.4 
127.0.0.1 - - [13/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 00:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48492 

self.closeSec=1683908699, self.tradeDate='20230513', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26354.3, self.close=26334.8, self.high=26362.0, self.low=26320.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-13 00:00:19,049:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230512    212959  26397.2  ...  49.166667  0.397442  0.794182
5802  20230512    215959  26404.7  ...  49.166667  0.403788  0.785268
5803  20230512    222959  26436.1  ...  49.166667  0.408834  0.775257
5804  20230512    225959  26461.3  ...  48.750000  0.387603  0.776636
5805  20230512    232959  26302.1  ...  48.750000  0.386381  0.778563

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-05-13 00:00:19,155:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.520441  0.479559       1  ...  0.968159  -1.0    0.0  0.924020
540     0  0.525074  0.474926       1  ...  0.967239  -1.0    0.0  0.924897
541     0  0.526663  0.473337       0  ...  0.973059  -1.0    0.0  0.919332
542     1  0.476108  0.523892       0  ...  0.973410  -1.0    0.0  0.919000
543     0  0.502145  0.497855       1  ...  0.972851  -1.0    0.0  0.919528

[5 rows x 10 columns]
2023-05-13 00:00:19,181:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.520851  0.479149       1  ...  0.968159  -1.0    0.0  0.926224
46     0  0.525096  0.474904       1  ...  0.967239  -1.0    0.0  0.925933
47     0  0.526307  0.473693       0  ...  0.973059  -1.0    0.0  0.918238
48     1  0.475960  0.524040       0  ...  0.973410  -1.0    0.0  0.917906
49     0  0.502145  0.497855       1  ...  0.972851  -1.0    0.0  0.919528

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24241 

self.closeSec=1683905399, self.tradeDate='20230512', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26306.9', self.close='26292.6'
127.0.0.1 - - [12/May/2023 23:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24242 

self.closeSec=1683905999, self.tradeDate='20230512', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26292.5', self.close='26291.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24243 

self.closeSec=1683906599, self.tradeDate='20230512', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26291.9', self.close='26314.5'
127.0.0.1 - - [12/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24244 

self.closeSec=1683907199, self.tradeDate='20230512', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26314.6', self.close='26307.7'
127.0.0.1 - - [13/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24245 

self.closeSec=1683907799, self.tradeDate='20230513', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26307.6', self.close='26250.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24246 

self.closeSec=1683908399, self.tradeDate='20230513', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26250.9', self.close='26354.3'
127.0.0.1 - - [13/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [12/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24242 

self.closeSec=1683905399, self.tradeDate='20230512', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26306.9', self.close='26292.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24243 

self.closeSec=1683905999, self.tradeDate='20230512', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26292.5', self.close='26291.9'
127.0.0.1 - - [12/May/2023 23:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24244 

self.closeSec=1683906599, self.tradeDate='20230512', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26291.9', self.close='26314.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24245 

self.closeSec=1683907199, self.tradeDate='20230512', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26314.6', self.close='26307.7'
127.0.0.1 - - [13/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24246 

self.closeSec=1683907799, self.tradeDate='20230513', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26307.6', self.close='26250.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24247 

self.closeSec=1683908399, self.tradeDate='20230513', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26250.9', self.close='26354.3'
127.0.0.1 - - [13/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24242 

self.closeSec=1683905399, self.tradeDate='20230512', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26306.9', self.close='26292.6'
127.0.0.1 - - [12/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24243 

self.closeSec=1683905999, self.tradeDate='20230512', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26292.5', self.close='26291.9'
127.0.0.1 - - [12/May/2023 23:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24244 

self.closeSec=1683906599, self.tradeDate='20230512', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26291.9', self.close='26314.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24245 

self.closeSec=1683907199, self.tradeDate='20230512', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26314.6', self.close='26307.7'
127.0.0.1 - - [13/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24246 

self.closeSec=1683907799, self.tradeDate='20230513', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26307.6', self.close='26250.7'
127.0.0.1 - - [13/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24247 

self.closeSec=1683908399, self.tradeDate='20230513', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26250.9', self.close='26354.3'
127.0.0.1 - - [13/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43923
self.closeSec=1683908399, self.tradeDate='20230513', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26300.4, self.close=26354.3, self.high=26398.2, self.low=26296.4, self.vol=3765.469, self.amt=99224290.6845 
127.0.0.1 - - [13/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-13 00:20:06,566:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230512   235500    235959  ...         0.0        0.0       0
5760  20230513   000000    000459  ...         0.0        0.0       0
5761  20230513   000500    000959  ...         0.0        0.0       0
5762  20230513   001000    001459  ...         0.0        0.0       0
5763  20230513   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 00:20:06,573:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683908399, self.tradeDate='20230513', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26300.4, self.close=26354.3, self.high=26398.2, self.low=26296.4, self.vol=3765.469, self.amt=99224290.6845, ukdf['pct'].iloc[-1]=0.002046 , ukdf['amount'].iloc[-1]=99224290.6845, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43924
self.closeSec=1683908699, self.tradeDate='20230513', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26354.3, self.close=26334.8, self.high=26362.0, self.low=26320.1, self.vol=1717.177, self.amt=45227887.111 
127.0.0.1 - - [13/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-13 00:25:02,224:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230513   000000    000459  ...         0.0        0.0       0
5761  20230513   000500    000959  ...         0.0        0.0       0
5762  20230513   001000    001459  ...         0.0        0.0       0
5763  20230513   001500    001959  ...         0.0        0.0       0
5764  20230513   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 00:25:02,225:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683908699, self.tradeDate='20230513', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26354.3, self.close=26334.8, self.high=26362.0, self.low=26320.1, self.vol=1717.177, self.amt=45227887.111, ukdf['pct'].iloc[-1]=-0.00074 , ukdf['amount'].iloc[-1]=45227887.111, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230512   120000    155959  1683878399  ...    723  0.214334 -1.014252    -1.0
724  20230512   160000    195959  1683892799  ...    724  0.324968 -0.572268     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '25418.39521088904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26333.94915686', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [13/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1404859.0878468, self.flagDict['side']='sell', self.tradeCount=35, self.count=1010
self.closeSec=1683907199, self.tradeDate='20230512', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26332.9, self.close=26307.7, self.high=26599.4, self.low=26254.2, self.vol=98862.763, self.amt=2610545556.95559 
2023-05-13 00:00:03,429:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683907199, self.tradeDate='20230512', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26332.9, self.close=26307.7, self.high=26599.4, self.low=26254.2, self.vol=98862.763, self.amt=2610545556.95559 
2023-05-13 00:00:03,469:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230512   040000    075959  ...   53500.320  1.441430e+09  0.004659
722  20230512   080000    115959  ...   90812.315  2.428956e+09 -0.014156
723  20230512   120000    155959  ...  131694.685  3.469452e+09 -0.010563
724  20230512   160000    195959  ...   54978.691  1.448095e+09  0.001479
725  20230512   200000    235959  ...   98862.763  2.610546e+09 -0.000961

[5 rows x 11 columns]
2023-05-13 00:00:04,868:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230512   040000    075959  1683849599  ...    721  0.274962 -0.824884    -1.0
722  20230512   080000    115959  1683863999  ...    722  0.178812 -1.164785    -1.0
723  20230512   120000    155959  1683878399  ...    723  0.214334 -1.014252    -1.0
724  20230512   160000    195959  1683892799  ...    724  0.324968 -0.572268     NaN
725  20230512   200000    235959  1683907199  ...    725  0.400387 -0.259278     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '26653.2188', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26310.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


