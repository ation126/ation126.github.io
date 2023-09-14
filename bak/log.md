# 20230915 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35572
self.closeSec=1694708399, self.tradeDate='20230915', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26630.2, self.close=26604.2, self.high=26653.7, self.low=26602.5, self.vol=901.573, self.amt=24005982.4459 
127.0.0.1 - - [15/Sep/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-09-15 00:20:06,775:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230914   235500    235959  ...         0.0        0.0       0
5760  20230915   000000    000459  ...         0.0        0.0       0
5761  20230915   000500    000959  ...         0.0        0.0       0
5762  20230915   001000    001459  ...         0.0        0.0       0
5763  20230915   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 00:20:06,778:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694708399, self.tradeDate='20230915', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26630.2, self.close=26604.2, self.high=26653.7, self.low=26602.5, self.vol=901.573, self.amt=24005982.4459, ukdf['pct'].iloc[-1]=-0.000973 , ukdf['amount'].iloc[-1]=24005982.4459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3582.14559950016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26607.67282784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35573
self.closeSec=1694708699, self.tradeDate='20230915', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26604.2, self.close=26609.6, self.high=26614.2, self.low=26588.0, self.vol=1055.554, self.amt=28077445.9709 
2023-09-15 00:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230915   000000    000459  ...         0.0        0.0       0
5761  20230915   000500    000959  ...         0.0        0.0       0
5762  20230915   001000    001459  ...         0.0        0.0       0
5763  20230915   001500    001959  ...         0.0        0.0       0
5764  20230915   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 00:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694708699, self.tradeDate='20230915', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26604.2, self.close=26609.6, self.high=26614.2, self.low=26588.0, self.vol=1055.554, self.amt=28077445.9709, ukdf['pct'].iloc[-1]=0.000203 , ukdf['amount'].iloc[-1]=28077445.9709, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3555.3078', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26609.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [15/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230910' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35572 

self.closeSec=1694707799, self.tradeDate='20230915', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26709.5, self.close=26644.4, self.high=26712.4, self.low=26631.0 
127.0.0.1 - - [15/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35573 

self.closeSec=1694708099, self.tradeDate='20230915', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26644.4, self.close=26630.1, self.high=26644.5, self.low=26617.3 
127.0.0.1 - - [15/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35574 

self.closeSec=1694708399, self.tradeDate='20230915', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26630.2, self.close=26604.2, self.high=26653.7, self.low=26602.5 
127.0.0.1 - - [15/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35575 

self.closeSec=1694708699, self.tradeDate='20230915', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26604.2, self.close=26609.6, self.high=26614.2, self.low=26588.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-15 00:00:18,355:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230914    212959  26448.4  ...  50.833333  0.597103  0.401479
5802  20230914    215959  26648.5  ...  50.833333  0.580378  0.394173
5803  20230914    222959  26570.6  ...  50.833333  0.593962  0.379260
5804  20230914    225959  26660.1  ...  50.833333  0.600623  0.361254
5805  20230914    232959  26718.0  ...  50.416667  0.574963  0.357169

[5 rows x 33 columns]
0.5569852941176471
acc is : 0.5569852941176471
2023-09-15 00:00:18,424:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.563784  0.436216       0  ...  0.945044   1.0 -0.0016  1.024251
540     1  0.491034  0.508966       1  ...  0.948291   1.0  0.0000  1.027770
541     0  0.531537  0.468463       1  ...  0.949931   1.0  0.0000  1.029547
542     0  0.525074  0.474926       0  ...  0.945559   1.0  0.0000  1.024810
543     1  0.471928  0.528072       1  ...  0.948938   1.0  0.0000  1.028472

[5 rows x 10 columns]
2023-09-15 00:00:18,437:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.564059  0.435941       0  ...  0.945044   1.0 -0.0016  1.026594
46     1  0.491033  0.508967       1  ...  0.948291   1.0  0.0000  1.029433
47     0  0.531823  0.468177       1  ...  0.949931   1.0  0.0000  1.031336
48     0  0.525316  0.474684       0  ...  0.945559   1.0  0.0000  1.026591
49     1  0.471928  0.528072       1  ...  0.948938   1.0  0.0000  1.028472

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '2321.136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26678.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17783 

self.closeSec=1694705399, self.tradeDate='20230914', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26626.9', self.close='26585'
127.0.0.1 - - [14/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17784 

self.closeSec=1694705999, self.tradeDate='20230914', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26585', self.close='26598.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17785 

self.closeSec=1694706599, self.tradeDate='20230914', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26598.3', self.close='26649.9'
127.0.0.1 - - [14/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17786 

self.closeSec=1694707199, self.tradeDate='20230914', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26650', self.close='26680'
127.0.0.1 - - [15/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17787 

self.closeSec=1694707799, self.tradeDate='20230915', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26680', self.close='26644.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17788 

self.closeSec=1694708399, self.tradeDate='20230915', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26644.4', self.close='26604.2'
127.0.0.1 - - [15/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17786 

self.closeSec=1694705399, self.tradeDate='20230914', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26626.9', self.close='26585'
127.0.0.1 - - [14/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [14/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17787 

self.closeSec=1694705999, self.tradeDate='20230914', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26585', self.close='26598.4'
127.0.0.1 - - [14/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17788 

self.closeSec=1694706599, self.tradeDate='20230914', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26598.3', self.close='26649.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17789 

self.closeSec=1694707199, self.tradeDate='20230914', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26650', self.close='26680'
127.0.0.1 - - [15/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17790 

self.closeSec=1694707799, self.tradeDate='20230915', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26680', self.close='26644.4'
127.0.0.1 - - [15/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17791 

self.closeSec=1694708399, self.tradeDate='20230915', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26644.4', self.close='26604.2'
127.0.0.1 - - [15/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17786 

self.closeSec=1694705399, self.tradeDate='20230914', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26626.9', self.close='26585'
127.0.0.1 - - [14/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17787 

self.closeSec=1694705999, self.tradeDate='20230914', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26585', self.close='26598.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17788 

self.closeSec=1694706599, self.tradeDate='20230914', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26598.3', self.close='26649.9'
127.0.0.1 - - [14/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17789 

self.closeSec=1694707199, self.tradeDate='20230914', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26650', self.close='26680'
127.0.0.1 - - [15/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17790 

self.closeSec=1694707799, self.tradeDate='20230915', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26680', self.close='26644.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17791 

self.closeSec=1694708399, self.tradeDate='20230915', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26644.4', self.close='26604.2'
127.0.0.1 - - [15/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35572
self.closeSec=1694708399, self.tradeDate='20230915', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26630.2, self.close=26604.2, self.high=26653.7, self.low=26602.5, self.vol=901.573, self.amt=24005982.4459 
127.0.0.1 - - [15/Sep/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-09-15 00:20:06,774:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230914   235500    235959  ...         0.0        0.0       0
5760  20230915   000000    000459  ...         0.0        0.0       0
5761  20230915   000500    000959  ...         0.0        0.0       0
5762  20230915   001000    001459  ...         0.0        0.0       0
5763  20230915   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 00:20:06,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694708399, self.tradeDate='20230915', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26630.2, self.close=26604.2, self.high=26653.7, self.low=26602.5, self.vol=901.573, self.amt=24005982.4459, ukdf['pct'].iloc[-1]=-0.000973 , ukdf['amount'].iloc[-1]=24005982.4459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-8777.42750119456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26607.67282784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [15/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35573
self.closeSec=1694708699, self.tradeDate='20230915', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26604.2, self.close=26609.6, self.high=26614.2, self.low=26588.0, self.vol=1055.554, self.amt=28077445.9709 
2023-09-15 00:25:00,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230915   000000    000459  ...         0.0        0.0       0
5761  20230915   000500    000959  ...         0.0        0.0       0
5762  20230915   001000    001459  ...         0.0        0.0       0
5763  20230915   001500    001959  ...         0.0        0.0       0
5764  20230915   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 00:25:00,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694708699, self.tradeDate='20230915', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26604.2, self.close=26609.6, self.high=26614.2, self.low=26588.0, self.vol=1055.554, self.amt=28077445.9709, ukdf['pct'].iloc[-1]=0.000203 , ukdf['amount'].iloc[-1]=28077445.9709, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-8705.8504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26609.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

722  20230914   080000    115959  ...   76521.139  2.012899e+09  0.001671
723  20230914   120000    155959  ...   31772.605  8.340425e+08  0.002986
724  20230914   160000    195959  ...   35924.143  9.462548e+08  0.003771
725  20230914   200000    235959  ...  143119.371  3.803643e+09  0.009402

[5 rows x 11 columns]
2023-09-15 00:00:02,296:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230914   040000    075959  1694649599  ...    721  0.356106 -0.103098     NaN
722  20230914   080000    115959  1694663999  ...    722  0.425970  0.136540     NaN
723  20230914   120000    155959  1694678399  ...    723  0.454654  0.251118     NaN
724  20230914   160000    195959  1694692799  ...    724  0.473310  0.335618     NaN
725  20230914   200000    235959  1694707199  ...    725  0.552260  0.623661     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-45038.3229', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26680', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-45038.3229', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26680', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-09-15 00:00:09,117:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1437705.7187854', 'total': '1437705.7187854', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-09-15 00:00:09,596:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-09-15 00:00:09,597:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 53.725, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42950F1694707209595I0L65'}
2023-09-15 00:00:09,626:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:9150000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230914, closeTime:235959, close:26680.0, sign:1, total:1437705.7187854, side:buy  
127.0.0.1 - - [15/Sep/2023 00:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-09-15 00:00:09,630:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42949F1694707204045I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1694707204451846, 'quantity': '57.177', 'price': '26680', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1694707203137, 'updatetime': 1694707204451, 'tradetype': 'usdt', 'selfid': 42949, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1694707204451, 'clientorderid': '42949F1694707204045I0L65', 'price': '26680', 'quantity': '57.177', 'commission': '1525.48236', 'commissionasset': 'USDT', 'tradetime': 1694707204451, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1694707204451}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-15 00:00:09,630:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42949F1694707204045I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1694707204451846, 'quantity': '57.177', 'price': '26680', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1694707203137, 'updatetime': 1694707204451, 'tradetype': 'usdt', 'selfid': 42949, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1694707204451, 'clientorderid': '42949F1694707204045I0L65', 'price': '26680', 'quantity': '57.177', 'commission': '1525.48236', 'commissionasset': 'USDT', 'tradetime': 1694707204451, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1694707204451}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-15 00:00:10,026:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42950F1694707209595I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1694707209998627, 'quantity': '53.725', 'price': '26678.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1694707209130, 'updatetime': 1694707209998, 'tradetype': 'usdt', 'selfid': 42950, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1694707209998, 'clientorderid': '42950F1694707209595I0L65', 'price': '26678.4', 'quantity': '53.725', 'commission': '1433.29704', 'commissionasset': 'USDT', 'tradetime': 1694707209998, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1694707209998}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Sep/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-09-15 00:00:10,213:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42950F1694707209595I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1694707209998627, 'quantity': '53.725', 'price': '26678.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1694707209130, 'updatetime': 1694707209998, 'tradetype': 'usdt', 'selfid': 42950, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1694707209998, 'clientorderid': '42950F1694707209595I0L65', 'price': '26678.4', 'quantity': '53.725', 'commission': '1433.29704', 'commissionasset': 'USDT', 'tradetime': 1694707209998, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1694707209998}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Sep/2023 00:00:10] "POST / HTTP/1.1" 200 -


