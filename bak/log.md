# 20230506 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45909
self.closeSec=1683303599, self.tradeDate='20230506', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29581.6, self.close=29580.2, self.high=29693.0, self.low=29572.2, self.vol=7604.883, self.amt=225275452.9436 
127.0.0.1 - - [06/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-06 00:20:06,797:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230505   235500    235959  ...         0.0        0.0       0
5760  20230506   000000    000459  ...         0.0        0.0       0
5761  20230506   000500    000959  ...         0.0        0.0       0
5762  20230506   001000    001459  ...         0.0        0.0       0
5763  20230506   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 00:20:06,814:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683303599, self.tradeDate='20230506', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29581.6, self.close=29580.2, self.high=29693.0, self.low=29572.2, self.vol=7604.883, self.amt=225275452.9436, ukdf['pct'].iloc[-1]=-4.1e-05 , ukdf['amount'].iloc[-1]=225275452.9436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-786607.59058247104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29601.08261404', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45910
self.closeSec=1683303899, self.tradeDate='20230506', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29580.1, self.close=29551.7, self.high=29629.0, self.low=29522.0, self.vol=4374.846, self.amt=129376349.5782 
2023-05-06 00:25:02,185:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230506   000000    000459  ...         0.0        0.0       0
5761  20230506   000500    000959  ...         0.0        0.0       0
5762  20230506   001000    001459  ...         0.0        0.0       0
5763  20230506   001500    001959  ...         0.0        0.0       0
5764  20230506   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 00:25:02,185:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683303899, self.tradeDate='20230506', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29580.1, self.close=29551.7, self.high=29629.0, self.low=29522.0, self.vol=4374.846, self.amt=129376349.5782, ukdf['pct'].iloc[-1]=-0.000963 , ukdf['amount'].iloc[-1]=129376349.5782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-783641.96', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29551.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [06/May/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230501' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46473 

self.closeSec=1683302999, self.tradeDate='20230506', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29545.5, self.close=29536.7, self.high=29653.2, self.low=29530.0 
127.0.0.1 - - [06/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46474 

self.closeSec=1683303299, self.tradeDate='20230506', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29537.2, self.close=29581.4, self.high=29619.1, self.low=29537.2 
127.0.0.1 - - [06/May/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46475 

self.closeSec=1683303599, self.tradeDate='20230506', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29581.6, self.close=29580.2, self.high=29693.0, self.low=29572.2 
127.0.0.1 - - [06/May/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [06/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46476 

self.closeSec=1683303899, self.tradeDate='20230506', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29580.1, self.close=29551.7, self.high=29629.0, self.low=29522.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-06 00:00:22,227:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5801  20230505    212959  28939.2  ...    51.25  0.513045  0.515763
5802  20230505    215959  28991.9  ...    51.25  0.541972  0.509062
5803  20230505    222959  29163.8  ...    51.25  0.539384  0.503780
5804  20230505    225959  29150.1  ...    51.25  0.554500  0.492081
5805  20230505    232959  29244.9  ...    51.25  0.561860  0.477767

[5 rows x 33 columns]
0.5496323529411765
acc is : 0.5496323529411765
2023-05-06 00:00:22,315:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.501384  0.498616       1  ...  0.883986  -1.0    0.0  1.062786
540     0  0.536765  0.463235       0  ...  0.884398  -1.0    0.0  1.062290
541     1  0.497191  0.502809       1  ...  0.881525  -1.0    0.0  1.065742
542     0  0.523529  0.476471       1  ...  0.880094  -1.0    0.0  1.067473
543     0  0.534146  0.465854       1  ...  0.878438  -1.0    0.0  1.069480

[5 rows x 10 columns]
2023-05-06 00:00:22,334:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501130  0.498870       1  ...  0.883986  -1.0    0.0  1.054379
46     0  0.537661  0.462339       0  ...  0.884398  -1.0    0.0  1.058695
47     1  0.497673  0.502327       1  ...  0.881525  -1.0    0.0  1.064961
48     0  0.524012  0.475988       1  ...  0.880094  -1.0    0.0  1.066691
49     0  0.534146  0.465854       1  ...  0.878438  -1.0    0.0  1.069480

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23233 

self.closeSec=1683300599, self.tradeDate='20230505', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29182.1', self.close='29292.3'
127.0.0.1 - - [05/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23234 

self.closeSec=1683301199, self.tradeDate='20230505', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29292.3', self.close='29232.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23235 

self.closeSec=1683301799, self.tradeDate='20230505', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29232.5', self.close='29288.4'
127.0.0.1 - - [05/May/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23236 

self.closeSec=1683302399, self.tradeDate='20230505', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29288.4', self.close='29347.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23237 

self.closeSec=1683302999, self.tradeDate='20230506', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29347.5', self.close='29536.7'
127.0.0.1 - - [06/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23238 

self.closeSec=1683303599, self.tradeDate='20230506', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29537.2', self.close='29580.2'
127.0.0.1 - - [06/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [05/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23234 

self.closeSec=1683300599, self.tradeDate='20230505', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29182.1', self.close='29292.3'
127.0.0.1 - - [05/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23235 

self.closeSec=1683301199, self.tradeDate='20230505', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29292.3', self.close='29232.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23236 

self.closeSec=1683301799, self.tradeDate='20230505', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29232.5', self.close='29288.4'
127.0.0.1 - - [05/May/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23237 

self.closeSec=1683302399, self.tradeDate='20230505', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29288.4', self.close='29347.4'
127.0.0.1 - - [06/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23238 

self.closeSec=1683302999, self.tradeDate='20230506', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29347.5', self.close='29536.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23239 

self.closeSec=1683303599, self.tradeDate='20230506', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29537.2', self.close='29580.2'
127.0.0.1 - - [06/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23234 

self.closeSec=1683300599, self.tradeDate='20230505', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29182.1', self.close='29292.3'
127.0.0.1 - - [05/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23235 

self.closeSec=1683301199, self.tradeDate='20230505', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29292.3', self.close='29232.5'
127.0.0.1 - - [05/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23236 

self.closeSec=1683301799, self.tradeDate='20230505', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29232.5', self.close='29288.4'
127.0.0.1 - - [05/May/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23237 

self.closeSec=1683302399, self.tradeDate='20230505', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29288.4', self.close='29347.4'
127.0.0.1 - - [06/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23238 

self.closeSec=1683302999, self.tradeDate='20230506', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29347.5', self.close='29536.7'
127.0.0.1 - - [06/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23239 

self.closeSec=1683303599, self.tradeDate='20230506', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29537.2', self.close='29580.2'
127.0.0.1 - - [06/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41907
self.closeSec=1683303599, self.tradeDate='20230506', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29581.6, self.close=29580.2, self.high=29693.0, self.low=29572.2, self.vol=7604.883, self.amt=225275452.9436 
127.0.0.1 - - [06/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-06 00:20:06,740:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230505   235500    235959  ...         0.0        0.0       0
5760  20230506   000000    000459  ...         0.0        0.0       0
5761  20230506   000500    000959  ...         0.0        0.0       0
5762  20230506   001000    001459  ...         0.0        0.0       0
5763  20230506   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 00:20:06,756:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683303599, self.tradeDate='20230506', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29581.6, self.close=29580.2, self.high=29693.0, self.low=29572.2, self.vol=7604.883, self.amt=225275452.9436, ukdf['pct'].iloc[-1]=-4.1e-05 , ukdf['amount'].iloc[-1]=225275452.9436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41908
self.closeSec=1683303899, self.tradeDate='20230506', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29580.1, self.close=29551.7, self.high=29629.0, self.low=29522.0, self.vol=4374.846, self.amt=129376349.5782 
127.0.0.1 - - [06/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-06 00:25:02,162:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230506   000000    000459  ...         0.0        0.0       0
5761  20230506   000500    000959  ...         0.0        0.0       0
5762  20230506   001000    001459  ...         0.0        0.0       0
5763  20230506   001500    001959  ...         0.0        0.0       0
5764  20230506   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 00:25:02,163:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683303899, self.tradeDate='20230506', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29580.1, self.close=29551.7, self.high=29629.0, self.low=29522.0, self.vol=4374.846, self.amt=129376349.5782, ukdf['pct'].iloc[-1]=-0.000963 , ukdf['amount'].iloc[-1]=129376349.5782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230505   120000    155959  1683273599  ...    723  0.498481 -0.439408     NaN
724  20230505   160000    195959  1683287999  ...    724  0.483032 -0.484612     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '9217.4614', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29144', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [06/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=968
self.closeSec=1683302399, self.tradeDate='20230505', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29137.6, self.close=29347.4, self.high=29437.5, self.low=28618.3, self.vol=192645.919, self.amt=5611955720.14394 
2023-05-06 00:00:03,204:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683302399, self.tradeDate='20230505', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29137.6, self.close=29347.4, self.high=29437.5, self.low=28618.3, self.vol=192645.919, self.amt=5611955720.14394 
2023-05-06 00:00:03,250:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230505   040000    075959  ...   29440.989  8.483901e+08 -0.001980
722  20230505   080000    115959  ...  115027.039  3.359784e+09  0.012523
723  20230505   120000    155959  ...   52721.949  1.537098e+09 -0.004386
724  20230505   160000    195959  ...   44104.482  1.282999e+09  0.002705
725  20230505   200000    235959  ...  192645.919  5.611956e+09  0.007200

[5 rows x 11 columns]
2023-05-06 00:00:05,345:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230505   040000    075959  1683244799  ...    721  0.437957 -0.626680    -1.0
722  20230505   080000    115959  1683259199  ...    722  0.462259 -0.551894     NaN
723  20230505   120000    155959  1683273599  ...    723  0.498481 -0.439408     NaN
724  20230505   160000    195959  1683287999  ...    724  0.483032 -0.484612     NaN
725  20230505   200000    235959  1683302399  ...    725  0.502555 -0.420950     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '-457.8364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29351.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


