# 20230423 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42165
self.closeSec=1682180399, self.tradeDate='20230423', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27640.0, self.close=27610.5, self.high=27659.8, self.low=27608.2, self.vol=3872.064, self.amt=106992898.5164 
127.0.0.1 - - [23/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-23 00:20:04,881:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230422   235500    235959  ...         0.0        0.0       0
5753  20230423   000000    000459  ...         0.0        0.0       0
5754  20230423   000500    000959  ...         0.0        0.0       0
5755  20230423   001000    001459  ...         0.0        0.0       0
5756  20230423   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 00:20:04,886:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682180399, self.tradeDate='20230423', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27640.0, self.close=27610.5, self.high=27659.8, self.low=27608.2, self.vol=3872.064, self.amt=106992898.5164, ukdf['pct'].iloc[-1]=-0.001028 , ukdf['amount'].iloc[-1]=106992898.5164, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-666707.9568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27608.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42166
self.closeSec=1682180699, self.tradeDate='20230423', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27612.4, self.close=27574.9, self.high=27616.4, self.low=27571.4, self.vol=2501.026, self.amt=69021109.659 
127.0.0.1 - - [23/Apr/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-04-23 00:25:02,131:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230423   000000    000459  ...         0.0        0.0       0
5754  20230423   000500    000959  ...         0.0        0.0       0
5755  20230423   001000    001459  ...         0.0        0.0       0
5756  20230423   001500    001959  ...         0.0        0.0       0
5757  20230423   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 00:25:02,131:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682180699, self.tradeDate='20230423', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27612.4, self.close=27574.9, self.high=27616.4, self.low=27571.4, self.vol=2501.026, self.amt=69021109.659, ukdf['pct'].iloc[-1]=-0.001289 , ukdf['amount'].iloc[-1]=69021109.659, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-664625.20693568928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27573.98902778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [23/Apr/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230418' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42729 

self.closeSec=1682179799, self.tradeDate='20230423', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27504.3, self.close=27585.7, self.high=27666.0, self.low=27491.8 
127.0.0.1 - - [23/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42730 

self.closeSec=1682180099, self.tradeDate='20230423', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27585.7, self.close=27638.9, self.high=27676.4, self.low=27562.0 
127.0.0.1 - - [23/Apr/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42731 

self.closeSec=1682180399, self.tradeDate='20230423', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27640.0, self.close=27610.5, self.high=27659.8, self.low=27608.2 
127.0.0.1 - - [23/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42732 

self.closeSec=1682180699, self.tradeDate='20230423', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27612.4, self.close=27574.9, self.high=27616.4, self.low=27571.4 
127.0.0.1 - - [23/Apr/2023 00:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-23 00:00:20,357:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230422    212959  27325.2  ...  50.833333  0.392754  0.832886
5802  20230422    215959  27272.4  ...  50.416667  0.388373  0.833376
5803  20230422    222959  27241.9  ...  50.416667  0.398982  0.829324
5804  20230422    225959  27289.2  ...  50.833333  0.435841  0.806020
5805  20230422    232959  27463.7  ...  50.833333  0.434129  0.767384

[5 rows x 33 columns]
0.5386029411764706
acc is : 0.5386029411764706
2023-04-23 00:00:20,451:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.514052  0.485948       0  ...  0.890063  -1.0  0.0000  0.905188
540     0  0.518994  0.481006       1  ...  0.888517  -1.0  0.0000  0.906760
541     0  0.536683  0.463317       1  ...  0.882832  -1.0  0.0000  0.912561
542     0  0.574072  0.425928       0  ...  0.881066   1.0 -0.0016  0.912196
543     0  0.529685  0.470315       1  ...  0.881846   1.0  0.0000  0.913003

[5 rows x 10 columns]
2023-04-23 00:00:20,474:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.514653  0.485347       0  ...  0.890063  -1.0  0.0000  0.905609
46     0  0.519599  0.480401       1  ...  0.888517  -1.0  0.0000  0.909001
47     0  0.537274  0.462726       1  ...  0.882832  -1.0  0.0000  0.912849
48     0  0.574440  0.425560       0  ...  0.881066   1.0 -0.0016  0.912484
49     0  0.529685  0.470315       1  ...  0.881846   1.0  0.0000  0.913003

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21361 

self.closeSec=1682177399, self.tradeDate='20230422', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27425.2', self.close='27452.8'
127.0.0.1 - - [22/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21362 

self.closeSec=1682177999, self.tradeDate='20230422', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27452.7', self.close='27459.1'
127.0.0.1 - - [22/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21363 

self.closeSec=1682178599, self.tradeDate='20230422', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27459.2', self.close='27438.4'
127.0.0.1 - - [23/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21364 

self.closeSec=1682179199, self.tradeDate='20230422', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27438.4', self.close='27477.1'
127.0.0.1 - - [23/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21365 

self.closeSec=1682179799, self.tradeDate='20230423', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27477.1', self.close='27585.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21366 

self.closeSec=1682180399, self.tradeDate='20230423', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27585.7', self.close='27610.5'
127.0.0.1 - - [23/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21362 

self.closeSec=1682177399, self.tradeDate='20230422', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27425.2', self.close='27452.8'
127.0.0.1 - - [22/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21363 

self.closeSec=1682177999, self.tradeDate='20230422', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27452.7', self.close='27459.1'
127.0.0.1 - - [22/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21364 

self.closeSec=1682178599, self.tradeDate='20230422', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27459.2', self.close='27438.4'
127.0.0.1 - - [23/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21365 

self.closeSec=1682179199, self.tradeDate='20230422', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27438.4', self.close='27477.1'
127.0.0.1 - - [23/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21366 

self.closeSec=1682179799, self.tradeDate='20230423', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27477.1', self.close='27585.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21367 

self.closeSec=1682180399, self.tradeDate='20230423', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27585.7', self.close='27610.5'
127.0.0.1 - - [23/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [22/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21362 

self.closeSec=1682177399, self.tradeDate='20230422', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27425.2', self.close='27452.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21363 

self.closeSec=1682177999, self.tradeDate='20230422', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27452.7', self.close='27459.1'
127.0.0.1 - - [22/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21364 

self.closeSec=1682178599, self.tradeDate='20230422', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27459.2', self.close='27438.4'
127.0.0.1 - - [22/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21365 

self.closeSec=1682179199, self.tradeDate='20230422', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27438.4', self.close='27477.1'
127.0.0.1 - - [23/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21366 

self.closeSec=1682179799, self.tradeDate='20230423', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27477.1', self.close='27585.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21367 

self.closeSec=1682180399, self.tradeDate='20230423', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27585.7', self.close='27610.5'
127.0.0.1 - - [23/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [23/Apr/2023 00:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38163
self.closeSec=1682180399, self.tradeDate='20230423', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27640.0, self.close=27610.5, self.high=27659.8, self.low=27608.2, self.vol=3872.064, self.amt=106992898.5164 
2023-04-23 00:20:02,251:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230422   235500    235959  ...         0.0        0.0       0
5753  20230423   000000    000459  ...         0.0        0.0       0
5754  20230423   000500    000959  ...         0.0        0.0       0
5755  20230423   001000    001459  ...         0.0        0.0       0
5756  20230423   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 00:20:02,301:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682180399, self.tradeDate='20230423', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27640.0, self.close=27610.5, self.high=27659.8, self.low=27608.2, self.vol=3872.064, self.amt=106992898.5164, ukdf['pct'].iloc[-1]=-0.001028 , ukdf['amount'].iloc[-1]=106992898.5164, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [23/Apr/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38164
self.closeSec=1682180699, self.tradeDate='20230423', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27612.4, self.close=27574.9, self.high=27616.4, self.low=27571.4, self.vol=2501.026, self.amt=69021109.659 
2023-04-23 00:25:02,127:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230423   000000    000459  ...         0.0        0.0       0
5754  20230423   000500    000959  ...         0.0        0.0       0
5755  20230423   001000    001459  ...         0.0        0.0       0
5756  20230423   001500    001959  ...         0.0        0.0       0
5757  20230423   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 00:25:02,128:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682180699, self.tradeDate='20230423', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27612.4, self.close=27574.9, self.high=27616.4, self.low=27571.4, self.vol=2501.026, self.amt=69021109.659, ukdf['pct'].iloc[-1]=-0.001289 , ukdf['amount'].iloc[-1]=69021109.659, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230422   120000    155959  1682150399  ...    723  0.928324  0.765001     1.0
724  20230422   160000    195959  1682164799  ...    724  0.969895  0.846018     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-52189.407', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27276.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=890
self.closeSec=1682179199, self.tradeDate='20230422', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27276.1, self.close=27477.1, self.high=27556.1, self.low=27219.5, self.vol=82203.755, self.amt=2251309949.76454 
127.0.0.1 - - [23/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-23 00:00:03,117:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682179199, self.tradeDate='20230422', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27276.1, self.close=27477.1, self.high=27556.1, self.low=27219.5, self.vol=82203.755, self.amt=2251309949.76454 
2023-04-23 00:00:03,153:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230422   040000    075959  ...  91017.726  2.482800e+09 -0.000774
722  20230422   080000    115959  ...  45729.471  1.246370e+09  0.002106
723  20230422   120000    155959  ...  36075.068  9.851259e+08 -0.001520
724  20230422   160000    195959  ...  42889.652  1.168175e+09  0.000282
725  20230422   200000    235959  ...  82203.755  2.251310e+09  0.007369

[5 rows x 11 columns]
2023-04-23 00:00:04,781:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230422   040000    075959  1682121599  ...    721  0.820729  0.542145     NaN
722  20230422   080000    115959  1682135999  ...    722  0.887550  0.685065     1.0
723  20230422   120000    155959  1682150399  ...    723  0.928324  0.765001     1.0
724  20230422   160000    195959  1682164799  ...    724  0.969895  0.846018     1.0
725  20230422   200000    235959  1682179199  ...    725  0.957747  0.797817     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-41633.892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27477.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


