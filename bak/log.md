# 20231019 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45364
self.closeSec=1697645999, self.tradeDate='20231019', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28324.8, self.close=28327.1, self.high=28355.0, self.low=28307.0, self.vol=956.57, self.amt=27093283.1773 
127.0.0.1 - - [19/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-10-19 00:20:08,011:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231018   235500    235959  ...         0.0        0.0       0
5760  20231019   000000    000459  ...         0.0        0.0       0
5761  20231019   000500    000959  ...         0.0        0.0       0
5762  20231019   001000    001459  ...         0.0        0.0       0
5763  20231019   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 00:20:08,022:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697645999, self.tradeDate='20231019', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28324.8, self.close=28327.1, self.high=28355.0, self.low=28307.0, self.vol=956.57, self.amt=27093283.1773, ukdf['pct'].iloc[-1]=8.1e-05 , ukdf['amount'].iloc[-1]=27093283.1773, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-20525.5314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28338.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45365
self.closeSec=1697646299, self.tradeDate='20231019', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28326.2, self.close=28298.6, self.high=28349.5, self.low=28287.0, self.vol=971.129, self.amt=27498692.4718 
127.0.0.1 - - [19/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-19 00:25:03,292:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231019   000000    000459  ...         0.0        0.0       0
5761  20231019   000500    000959  ...         0.0        0.0       0
5762  20231019   001000    001459  ...         0.0        0.0       0
5763  20231019   001500    001959  ...         0.0        0.0       0
5764  20231019   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 00:25:03,293:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697646299, self.tradeDate='20231019', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28326.2, self.close=28298.6, self.high=28349.5, self.low=28287.0, self.vol=971.129, self.amt=27498692.4718, ukdf['pct'].iloc[-1]=-0.001006 , ukdf['amount'].iloc[-1]=27498692.4718, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-19999.1286', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28301', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [19/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20231014' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [19/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45364 

self.closeSec=1697645399, self.tradeDate='20231019', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28284.3, self.close=28346.4, self.high=28366.8, self.low=28276.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45365 

self.closeSec=1697645699, self.tradeDate='20231019', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28345.1, self.close=28324.8, self.high=28357.8, self.low=28324.4 
127.0.0.1 - - [19/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45366 

self.closeSec=1697645999, self.tradeDate='20231019', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28324.8, self.close=28327.1, self.high=28355.0, self.low=28307.0 
127.0.0.1 - - [19/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45367 

self.closeSec=1697646299, self.tradeDate='20231019', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28326.2, self.close=28298.6, self.high=28349.5, self.low=28287.0 
127.0.0.1 - - [19/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-19 00:00:19,832:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231018    212959  28315.6  ...  51.666667  0.515883  0.622870
5802  20231018    215959  28342.4  ...  51.666667  0.511308  0.639798
5803  20231018    222959  28313.1  ...  51.666667  0.503738  0.658986
5804  20231018    225959  28271.6  ...  51.666667  0.489247  0.678036
5805  20231018    232959  28180.3  ...  52.083333  0.502124  0.690432

[5 rows x 33 columns]
0.5625
acc is : 0.5625
2023-10-19 00:00:19,903:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.506495  0.493505       0  ...  0.942103  -1.0    0.0  1.015624
540     1  0.489268  0.510732       0  ...  0.943617  -1.0    0.0  1.013992
541     1  0.481188  0.518812       0  ...  0.946595  -1.0    0.0  1.010793
542     1  0.459962  0.540038       1  ...  0.943954  -1.0    0.0  1.013612
543     0  0.516461  0.483539       0  ...  0.944746  -1.0    0.0  1.012762

[5 rows x 10 columns]
2023-10-19 00:00:19,917:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506599  0.493401       0  ...  0.942103  -1.0    0.0  1.015395
46     1  0.489454  0.510546       0  ...  0.943617  -1.0    0.0  1.014134
47     1  0.481033  0.518967       0  ...  0.946595  -1.0    0.0  1.010047
48     1  0.459978  0.540022       1  ...  0.943954  -1.0    0.0  1.012864
49     0  0.516461  0.483539       0  ...  0.944746  -1.0    0.0  1.012762

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.922', 'enterprice': '28335.6', 'countrevence': '0', 'unrealprofit': '2274.16282483126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28231.86116117', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22679 

self.closeSec=1697642999, self.tradeDate='20231018', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28244.5', self.close='28259'
127.0.0.1 - - [18/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22680 

self.closeSec=1697643599, self.tradeDate='20231018', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28259', self.close='28235.1'
127.0.0.1 - - [18/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22681 

self.closeSec=1697644199, self.tradeDate='20231018', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28235.2', self.close='28231.6'
127.0.0.1 - - [18/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22682 

self.closeSec=1697644799, self.tradeDate='20231018', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28231.6', self.close='28235.3'
127.0.0.1 - - [19/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22683 

self.closeSec=1697645399, self.tradeDate='20231019', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28235.4', self.close='28346.4'
127.0.0.1 - - [19/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22684 

self.closeSec=1697645999, self.tradeDate='20231019', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28345.1', self.close='28327.1'
127.0.0.1 - - [19/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [18/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22682 

self.closeSec=1697642999, self.tradeDate='20231018', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28244.5', self.close='28259'
127.0.0.1 - - [18/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22683 

self.closeSec=1697643599, self.tradeDate='20231018', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28259', self.close='28235.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22684 

self.closeSec=1697644199, self.tradeDate='20231018', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28235.2', self.close='28231.6'
127.0.0.1 - - [18/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22685 

self.closeSec=1697644799, self.tradeDate='20231018', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28231.6', self.close='28235.3'
127.0.0.1 - - [19/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22686 

self.closeSec=1697645399, self.tradeDate='20231019', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28235.4', self.close='28346.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22687 

self.closeSec=1697645999, self.tradeDate='20231019', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28345.1', self.close='28327.1'
127.0.0.1 - - [19/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22682 

self.closeSec=1697642999, self.tradeDate='20231018', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28244.5', self.close='28259'
127.0.0.1 - - [18/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22683 

self.closeSec=1697643599, self.tradeDate='20231018', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28259', self.close='28235.1'
127.0.0.1 - - [18/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22684 

self.closeSec=1697644199, self.tradeDate='20231018', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28235.2', self.close='28231.6'
127.0.0.1 - - [18/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22685 

self.closeSec=1697644799, self.tradeDate='20231018', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28231.6', self.close='28235.3'
127.0.0.1 - - [19/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22686 

self.closeSec=1697645399, self.tradeDate='20231019', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28235.4', self.close='28346.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22687 

self.closeSec=1697645999, self.tradeDate='20231019', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28345.1', self.close='28327.1'
127.0.0.1 - - [19/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45364
self.closeSec=1697645999, self.tradeDate='20231019', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28324.8, self.close=28327.1, self.high=28355.0, self.low=28307.0, self.vol=956.57, self.amt=27093283.1773 
127.0.0.1 - - [19/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-10-19 00:20:08,001:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231018   235500    235959  ...         0.0        0.0       0
5760  20231019   000000    000459  ...         0.0        0.0       0
5761  20231019   000500    000959  ...         0.0        0.0       0
5762  20231019   001000    001459  ...         0.0        0.0       0
5763  20231019   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 00:20:08,010:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697645999, self.tradeDate='20231019', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28324.8, self.close=28327.1, self.high=28355.0, self.low=28307.0, self.vol=956.57, self.amt=27093283.1773, ukdf['pct'].iloc[-1]=8.1e-05 , ukdf['amount'].iloc[-1]=27093283.1773, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '55518.3668', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28338.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45365
self.closeSec=1697646299, self.tradeDate='20231019', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28326.2, self.close=28298.6, self.high=28349.5, self.low=28287.0, self.vol=971.129, self.amt=27498692.4718 
127.0.0.1 - - [19/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-19 00:25:03,289:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231019   000000    000459  ...         0.0        0.0       0
5761  20231019   000500    000959  ...         0.0        0.0       0
5762  20231019   001000    001459  ...         0.0        0.0       0
5763  20231019   001500    001959  ...         0.0        0.0       0
5764  20231019   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 00:25:03,291:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697646299, self.tradeDate='20231019', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28326.2, self.close=28298.6, self.high=28349.5, self.low=28287.0, self.vol=971.129, self.amt=27498692.4718, ukdf['pct'].iloc[-1]=-0.001006 , ukdf['amount'].iloc[-1]=27498692.4718, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '54114.437', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28301', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231018   120000    155959  1697615999  ...    723  0.968668  0.467607     NaN
724  20231018   160000    195959  1697630399  ...    724  0.924896  0.401351     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '21600.7386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28334', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [19/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=945
self.closeSec=1697644799, self.tradeDate='20231018', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28327.3, self.close=28235.3, self.high=28393.2, self.low=28126.6, self.vol=58144.088, self.amt=1643344357.22743 
2023-10-19 00:00:01,513:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697644799, self.tradeDate='20231018', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28327.3, self.close=28235.3, self.high=28393.2, self.low=28126.6, self.vol=58144.088, self.amt=1643344357.22743 
2023-10-19 00:00:01,527:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231018   040000    075959  ...  24541.976  6.983148e+08 -0.004109
722  20231018   080000    115959  ...  25900.836  7.355935e+08  0.004122
723  20231018   120000    155959  ...  98876.718  2.836423e+09 -0.000481
724  20231018   160000    195959  ...  56062.116  1.592322e+09 -0.005543
725  20231018   200000    235959  ...  58144.088  1.643344e+09 -0.003248

[5 rows x 11 columns]
2023-10-19 00:00:02,256:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231018   040000    075959  1697587199  ...    721  0.992506  0.497216     NaN
722  20231018   080000    115959  1697601599  ...    722  0.946815  0.429065     NaN
723  20231018   120000    155959  1697615999  ...    723  0.968668  0.467607     NaN
724  20231018   160000    195959  1697630399  ...    724  0.924896  0.401351     NaN
725  20231018   200000    235959  1697644799  ...    725  0.859830  0.301681     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '17281.467', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28235.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


