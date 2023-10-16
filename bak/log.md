# 20231017 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44788
self.closeSec=1697473199, self.tradeDate='20231017', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28147.5, self.close=28136.8, self.high=28171.9, self.low=28117.6, self.vol=1105.5, self.amt=31106982.2583 
127.0.0.1 - - [17/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-10-17 00:20:08,870:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231016   235500    235959  ...         0.0        0.0       0
5760  20231017   000000    000459  ...         0.0        0.0       0
5761  20231017   000500    000959  ...         0.0        0.0       0
5762  20231017   001000    001459  ...         0.0        0.0       0
5763  20231017   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 00:20:08,884:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697473199, self.tradeDate='20231017', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28147.5, self.close=28136.8, self.high=28171.9, self.low=28117.6, self.vol=1105.5, self.amt=31106982.2583, ukdf['pct'].iloc[-1]=-0.000575 , ukdf['amount'].iloc[-1]=31106982.2583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-17747.6491307313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28139.32547255', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44789
self.closeSec=1697473499, self.tradeDate='20231017', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28136.9, self.close=28115.6, self.high=28143.2, self.low=28105.5, self.vol=694.871, self.amt=19540821.3883 
127.0.0.1 - - [17/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-17 00:25:03,491:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231017   000000    000459  ...         0.0        0.0       0
5761  20231017   000500    000959  ...         0.0        0.0       0
5762  20231017   001000    001459  ...         0.0        0.0       0
5763  20231017   001500    001959  ...         0.0        0.0       0
5764  20231017   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 00:25:03,499:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697473499, self.tradeDate='20231017', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28136.9, self.close=28115.6, self.high=28143.2, self.low=28105.5, self.vol=694.871, self.amt=19540821.3883, ukdf['pct'].iloc[-1]=-0.000753 , ukdf['amount'].iloc[-1]=19540821.3883, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-17354.9863101252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28111.1290902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [17/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20231012' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44788 

self.closeSec=1697472599, self.tradeDate='20231017', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28086.7, self.close=28129.9, self.high=28145.5, self.low=28086.7 
127.0.0.1 - - [17/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44789 

127.0.0.1 - - [17/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -
self.closeSec=1697472899, self.tradeDate='20231017', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28129.9, self.close=28153.0, self.high=28169.5, self.low=28115.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44790 

self.closeSec=1697473199, self.tradeDate='20231017', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28147.5, self.close=28136.8, self.high=28171.9, self.low=28117.6 
127.0.0.1 - - [17/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44791 

self.closeSec=1697473499, self.tradeDate='20231017', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28136.9, self.close=28115.6, self.high=28143.2, self.low=28105.5 
127.0.0.1 - - [17/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-17 00:00:16,766:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231016    212959  27873.3  ...  52.500000  0.793702  0.299995
5802  20231016    215959  29470.4  ...  52.083333  0.571457  0.328360
5803  20231016    222959  27986.5  ...  52.500000  0.588566  0.351434
5804  20231016    225959  28193.0  ...  52.083333  0.587105  0.373199
5805  20231016    232959  28181.3  ...  52.083333  0.577218  0.395064

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-10-17 00:00:16,835:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.919042  0.080958       0  ...  0.949060   1.0  0.0000  1.013937
540     1  0.182250  0.817750       1  ...  0.940381  -1.0 -0.0016  1.021587
541     0  0.600176  0.399824       0  ...  0.938446   1.0 -0.0016  1.021120
542     0  0.531522  0.468478       0  ...  0.935542   1.0  0.0000  1.017960
543     1  0.496311  0.503689       0  ...  0.934317   1.0  0.0000  1.016626

[5 rows x 10 columns]
2023-10-17 00:00:16,847:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.918458  0.081542       0  ...  0.949060   1.0  0.0000  1.013401
46     1  0.183166  0.816834       1  ...  0.940381  -1.0 -0.0016  1.019824
47     0  0.600279  0.399721       0  ...  0.938446   1.0 -0.0016  1.021608
48     0  0.531746  0.468254       0  ...  0.935542   1.0  0.0000  1.018447
49     1  0.496311  0.503689       0  ...  0.934317   1.0  0.0000  1.016626

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.61', 'enterprice': '28188.2', 'countrevence': '0', 'unrealprofit': '-2913.474', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28064.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22391 

self.closeSec=1697470199, self.tradeDate='20231016', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28092.5', self.close='28090.9'
127.0.0.1 - - [16/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22392 

self.closeSec=1697470799, self.tradeDate='20231016', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28099.4', self.close='28080'
127.0.0.1 - - [16/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22393 

self.closeSec=1697471399, self.tradeDate='20231016', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28080', self.close='28076.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22394 

self.closeSec=1697471999, self.tradeDate='20231016', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28080.2', self.close='28054.1'
127.0.0.1 - - [17/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22395 

self.closeSec=1697472599, self.tradeDate='20231017', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28054.1', self.close='28129.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22396 

self.closeSec=1697473199, self.tradeDate='20231017', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28129.9', self.close='28136.8'
127.0.0.1 - - [17/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [16/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22394 

self.closeSec=1697470199, self.tradeDate='20231016', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28092.5', self.close='28090.9'
127.0.0.1 - - [16/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22395 

self.closeSec=1697470799, self.tradeDate='20231016', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28099.4', self.close='28080'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22396 

self.closeSec=1697471399, self.tradeDate='20231016', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28080', self.close='28076.4'
127.0.0.1 - - [16/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22397 

self.closeSec=1697471999, self.tradeDate='20231016', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28080.2', self.close='28054.1'
127.0.0.1 - - [17/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22398 

self.closeSec=1697472599, self.tradeDate='20231017', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28054.1', self.close='28129.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22399 

self.closeSec=1697473199, self.tradeDate='20231017', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28129.9', self.close='28136.8'
127.0.0.1 - - [17/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22394 

self.closeSec=1697470199, self.tradeDate='20231016', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28092.5', self.close='28090.9'
127.0.0.1 - - [16/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22395 

self.closeSec=1697470799, self.tradeDate='20231016', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28099.4', self.close='28080'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22396 

self.closeSec=1697471399, self.tradeDate='20231016', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28080', self.close='28076.4'
127.0.0.1 - - [16/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22397 

self.closeSec=1697471999, self.tradeDate='20231016', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28080.2', self.close='28054.1'
127.0.0.1 - - [17/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22398 

self.closeSec=1697472599, self.tradeDate='20231017', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28054.1', self.close='28129.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22399 

self.closeSec=1697473199, self.tradeDate='20231017', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28129.9', self.close='28136.8'
127.0.0.1 - - [17/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44788
self.closeSec=1697473199, self.tradeDate='20231017', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28147.5, self.close=28136.8, self.high=28171.9, self.low=28117.6, self.vol=1105.5, self.amt=31106982.2583 
127.0.0.1 - - [17/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-10-17 00:20:08,841:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231016   235500    235959  ...         0.0        0.0       0
5760  20231017   000000    000459  ...         0.0        0.0       0
5761  20231017   000500    000959  ...         0.0        0.0       0
5762  20231017   001000    001459  ...         0.0        0.0       0
5763  20231017   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 00:20:08,854:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697473199, self.tradeDate='20231017', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28147.5, self.close=28136.8, self.high=28171.9, self.low=28117.6, self.vol=1105.5, self.amt=31106982.2583, ukdf['pct'].iloc[-1]=-0.000575 , ukdf['amount'].iloc[-1]=31106982.2583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '48109.68337597955', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28139.32547255', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44789
self.closeSec=1697473499, self.tradeDate='20231017', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28136.9, self.close=28115.6, self.high=28143.2, self.low=28105.5, self.vol=694.871, self.amt=19540821.3883 
127.0.0.1 - - [17/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-17 00:25:03,485:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231017   000000    000459  ...         0.0        0.0       0
5761  20231017   000500    000959  ...         0.0        0.0       0
5762  20231017   001000    001459  ...         0.0        0.0       0
5763  20231017   001500    001959  ...         0.0        0.0       0
5764  20231017   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 00:25:03,487:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697473499, self.tradeDate='20231017', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28136.9, self.close=28115.6, self.high=28143.2, self.low=28105.5, self.vol=694.871, self.amt=19540821.3883, ukdf['pct'].iloc[-1]=-0.000753 , ukdf['amount'].iloc[-1]=19540821.3883, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '47062.4415391182', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28111.1290902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231016   120000    155959  1697443199  ...    723  1.659620  2.908893     1.0
724  20231016   160000    195959  1697457599  ...    724  1.193590  1.624672     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '-4537.1423727735', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27737.32646275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=933
self.closeSec=1697471999, self.tradeDate='20231016', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27737.0, self.close=28054.1, self.high=30720.0, self.low=27695.0, self.vol=460426.856, self.amt=13147733008.10522 
127.0.0.1 - - [17/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-10-17 00:00:01,560:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697471999, self.tradeDate='20231016', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27737.0, self.close=28054.1, self.high=30720.0, self.low=27695.0, self.vol=460426.856, self.amt=13147733008.10522 
2023-10-17 00:00:01,586:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20231016   040000    075959  ...   74881.965  2.033626e+09  0.004058
722  20231016   080000    115959  ...   30332.416  8.246226e+08  0.003007
723  20231016   120000    155959  ...  135348.480  3.756989e+09  0.022427
724  20231016   160000    195959  ...   51668.099  1.433204e+09 -0.003410
725  20231016   200000    235959  ...  460426.856  1.314773e+10  0.011432

[5 rows x 11 columns]
2023-10-17 00:00:02,330:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231016   040000    075959  1697414399  ...    721  0.326582 -0.618872    -1.0
722  20231016   080000    115959  1697428799  ...    722  0.472551 -0.214699     NaN
723  20231016   120000    155959  1697443199  ...    723  1.659620  2.908893     1.0
724  20231016   160000    195959  1697457599  ...    724  1.193590  1.624672     1.0
725  20231016   200000    235959  1697471999  ...    725  4.305991  6.740435     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '9335.0586', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28054', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


