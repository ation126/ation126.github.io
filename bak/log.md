# 20230914 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35284
self.closeSec=1694621999, self.tradeDate='20230914', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26254.8, self.close=26320.5, self.high=26325.4, self.low=26254.8, self.vol=2080.284, self.amt=54695723.0668 
127.0.0.1 - - [14/Sep/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-09-14 00:20:06,376:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230913   235500    235959  ...         0.0        0.0       0
5760  20230914   000000    000459  ...         0.0        0.0       0
5761  20230914   000500    000959  ...         0.0        0.0       0
5762  20230914   001000    001459  ...         0.0        0.0       0
5763  20230914   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 00:20:06,377:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694621999, self.tradeDate='20230914', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26254.8, self.close=26320.5, self.high=26325.4, self.low=26254.8, self.vol=2080.284, self.amt=54695723.0668, ukdf['pct'].iloc[-1]=0.002502 , ukdf['amount'].iloc[-1]=54695723.0668, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7432.3062', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26331.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35285
self.closeSec=1694622299, self.tradeDate='20230914', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26320.5, self.close=26315.2, self.high=26360.0, self.low=26294.6, self.vol=2340.685, self.amt=61622468.4747 
127.0.0.1 - - [14/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-14 00:25:00,788:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230914   000000    000459  ...         0.0        0.0       0
5761  20230914   000500    000959  ...         0.0        0.0       0
5762  20230914   001000    001459  ...         0.0        0.0       0
5763  20230914   001500    001959  ...         0.0        0.0       0
5764  20230914   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 00:25:00,789:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694622299, self.tradeDate='20230914', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26320.5, self.close=26315.2, self.high=26360.0, self.low=26294.6, self.vol=2340.685, self.amt=61622468.4747, ukdf['pct'].iloc[-1]=-0.000201 , ukdf['amount'].iloc[-1]=61622468.4747, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7565.02455076566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26321.66974359', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [14/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230909' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [14/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35284 

self.closeSec=1694621399, self.tradeDate='20230914', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26214.2, self.close=26196.3, self.high=26215.6, self.low=26185.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35285 

self.closeSec=1694621699, self.tradeDate='20230914', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26199.4, self.close=26254.8, self.high=26269.6, self.low=26199.4 
127.0.0.1 - - [14/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35286 

self.closeSec=1694621999, self.tradeDate='20230914', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26254.8, self.close=26320.5, self.high=26325.4, self.low=26254.8 
127.0.0.1 - - [14/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35287 

self.closeSec=1694622299, self.tradeDate='20230914', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26320.5, self.close=26315.2, self.high=26360.0, self.low=26294.6 
127.0.0.1 - - [14/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-14 00:00:18,908:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230913    212959  26204.9  ...  50.416667  0.541780  0.565056
5802  20230913    215959  26102.0  ...  50.416667  0.543294  0.547576
5803  20230913    222959  26110.7  ...  50.416667  0.551561  0.525064
5804  20230913    225959  26158.7  ...  50.833333  0.558794  0.506560
5805  20230913    232959  26201.5  ...  50.833333  0.567857  0.483245

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-09-14 00:00:18,971:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.469262  0.530738       1  ...  0.996514  -1.0    0.0  1.012675
540     1  0.493701  0.506299       1  ...  0.994678  -1.0    0.0  1.014540
541     0  0.503053  0.496947       1  ...  0.993055  -1.0    0.0  1.016196
542     0  0.505077  0.494923       1  ...  0.990993  -1.0    0.0  1.018306
543     0  0.510292  0.489708       0  ...  0.992004  -1.0    0.0  1.017267

[5 rows x 10 columns]
2023-09-14 00:00:18,982:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.469537  0.530463       1  ...  0.996514  -1.0    0.0  1.012431
46     1  0.493748  0.506252       1  ...  0.994678  -1.0    0.0  1.014261
47     0  0.503256  0.496744       1  ...  0.993055  -1.0    0.0  1.016271
48     0  0.505300  0.494700       1  ...  0.990993  -1.0    0.0  1.018381
49     0  0.510292  0.489708       0  ...  0.992004  -1.0    0.0  1.017267

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.172', 'enterprice': '26023.2', 'countrevence': '0', 'unrealprofit': '-6031.6252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26237.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17639 

self.closeSec=1694618999, self.tradeDate='20230913', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26225.5', self.close='26255.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17640 

self.closeSec=1694619599, self.tradeDate='20230913', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26256', self.close='26253.2'
127.0.0.1 - - [13/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17641 

self.closeSec=1694620199, self.tradeDate='20230913', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26253.2', self.close='26263.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17642 

self.closeSec=1694620799, self.tradeDate='20230913', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26263.6', self.close='26229.1'
127.0.0.1 - - [14/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17643 

self.closeSec=1694621399, self.tradeDate='20230914', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26229.2', self.close='26196.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17644 

self.closeSec=1694621999, self.tradeDate='20230914', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26199.4', self.close='26320.5'
127.0.0.1 - - [14/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [13/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17642 

self.closeSec=1694618999, self.tradeDate='20230913', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26225.5', self.close='26255.9'
127.0.0.1 - - [13/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17643 

self.closeSec=1694619599, self.tradeDate='20230913', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26256', self.close='26253.2'
127.0.0.1 - - [13/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17644 

self.closeSec=1694620199, self.tradeDate='20230913', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26253.2', self.close='26263.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17645 

self.closeSec=1694620799, self.tradeDate='20230913', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26263.6', self.close='26229.1'
127.0.0.1 - - [14/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17646 

self.closeSec=1694621399, self.tradeDate='20230914', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26229.2', self.close='26196.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17647 

self.closeSec=1694621999, self.tradeDate='20230914', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26199.4', self.close='26320.5'
127.0.0.1 - - [14/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17642 

self.closeSec=1694618999, self.tradeDate='20230913', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26225.5', self.close='26255.9'
127.0.0.1 - - [13/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17643127.0.0.1 - - [13/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
 

self.closeSec=1694619599, self.tradeDate='20230913', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26256', self.close='26253.2'
127.0.0.1 - - [13/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17644 

self.closeSec=1694620199, self.tradeDate='20230913', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26253.2', self.close='26263.6'
127.0.0.1 - - [14/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17645 

self.closeSec=1694620799, self.tradeDate='20230913', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26263.6', self.close='26229.1'
127.0.0.1 - - [14/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17646 

self.closeSec=1694621399, self.tradeDate='20230914', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26229.2', self.close='26196.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17647 

self.closeSec=1694621999, self.tradeDate='20230914', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26199.4', self.close='26320.5'
127.0.0.1 - - [14/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35284
self.closeSec=1694621999, self.tradeDate='20230914', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26254.8, self.close=26320.5, self.high=26325.4, self.low=26254.8, self.vol=2080.284, self.amt=54695723.0668 
127.0.0.1 - - [14/Sep/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-09-14 00:20:06,377:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230913   235500    235959  ...         0.0        0.0       0
5760  20230914   000000    000459  ...         0.0        0.0       0
5761  20230914   000500    000959  ...         0.0        0.0       0
5762  20230914   001000    001459  ...         0.0        0.0       0
5763  20230914   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 00:20:06,379:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694621999, self.tradeDate='20230914', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26254.8, self.close=26320.5, self.high=26325.4, self.low=26254.8, self.vol=2080.284, self.amt=54695723.0668, ukdf['pct'].iloc[-1]=0.002502 , ukdf['amount'].iloc[-1]=54695723.0668, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-19045.9048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26331.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [14/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35285
self.closeSec=1694622299, self.tradeDate='20230914', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26320.5, self.close=26315.2, self.high=26360.0, self.low=26294.6, self.vol=2340.685, self.amt=61622468.4747 
2023-09-14 00:25:00,791:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230914   000000    000459  ...         0.0        0.0       0
5761  20230914   000500    000959  ...         0.0        0.0       0
5762  20230914   001000    001459  ...         0.0        0.0       0
5763  20230914   001500    001959  ...         0.0        0.0       0
5764  20230914   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 00:25:00,791:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694622299, self.tradeDate='20230914', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26320.5, self.close=26315.2, self.high=26360.0, self.low=26294.6, self.vol=2340.685, self.amt=61622468.4747, ukdf['pct'].iloc[-1]=-0.000201 , ukdf['amount'].iloc[-1]=61622468.4747, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-19399.86805332381', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26321.66974359', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230913   120000    155959  1694591999  ...    723  0.210407 -0.542773     NaN
724  20230913   160000    195959  1694606399  ...    724  0.240837 -0.466636     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-17353.2195', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26195.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=735
self.closeSec=1694620799, self.tradeDate='20230913', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26184.8, self.close=26229.1, self.high=26382.0, self.low=26007.9, self.vol=100568.464, self.amt=2633160500.895 
127.0.0.1 - - [14/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-14 00:00:01,573:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694620799, self.tradeDate='20230913', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26184.8, self.close=26229.1, self.high=26382.0, self.low=26007.9, self.vol=100568.464, self.amt=2633160500.895 
2023-09-14 00:00:01,585:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230913   040000    075959  ...   40646.871  1.054920e+09 -0.008683
722  20230913   080000    115959  ...   33520.940  8.677007e+08  0.001650
723  20230913   120000    155959  ...   46656.095  1.210204e+09 -0.000054
724  20230913   160000    195959  ...   64365.198  1.679536e+09  0.012267
725  20230913   200000    235959  ...  100568.464  2.633161e+09  0.001711

[5 rows x 11 columns]
2023-09-14 00:00:02,298:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230913   040000    075959  1694563199  ...    721  0.182931 -0.601752    -1.0
722  20230913   080000    115959  1694577599  ...    722  0.191800 -0.585802     NaN
723  20230913   120000    155959  1694591999  ...    723  0.210407 -0.542773     NaN
724  20230913   160000    195959  1694606399  ...    724  0.240837 -0.466636     NaN
725  20230913   200000    235959  1694620799  ...    725  0.293882 -0.326290     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-19361.75441383683', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26230.92837179', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


