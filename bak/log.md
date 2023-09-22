# 20230923 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37876
self.closeSec=1695399599, self.tradeDate='20230923', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26606.3, self.close=26631.3, self.high=26631.3, self.low=26606.2, self.vol=535.627, self.amt=14257215.6796 
127.0.0.1 - - [23/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-23 00:20:06,505:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230922   235500    235959  ...         0.0        0.0       0
5760  20230923   000000    000459  ...         0.0        0.0       0
5761  20230923   000500    000959  ...         0.0        0.0       0
5762  20230923   001000    001459  ...         0.0        0.0       0
5763  20230923   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 00:20:06,518:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695399599, self.tradeDate='20230923', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26606.3, self.close=26631.3, self.high=26631.3, self.low=26606.2, self.vol=535.627, self.amt=14257215.6796, ukdf['pct'].iloc[-1]=0.00094 , ukdf['amount'].iloc[-1]=14257215.6796, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3254.5062', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26631.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37877
self.closeSec=1695399899, self.tradeDate='20230923', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26631.2, self.close=26623.2, self.high=26631.3, self.low=26610.2, self.vol=212.92, self.amt=5667891.9895 
2023-09-23 00:25:00,798:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230923   000000    000459  ...         0.0        0.0       0
5761  20230923   000500    000959  ...         0.0        0.0       0
5762  20230923   001000    001459  ...         0.0        0.0       0
5763  20230923   001500    001959  ...         0.0        0.0       0
5764  20230923   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 00:25:00,798:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695399899, self.tradeDate='20230923', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26631.2, self.close=26623.2, self.high=26631.3, self.low=26610.2, self.vol=212.92, self.amt=5667891.9895, ukdf['pct'].iloc[-1]=-0.000304 , ukdf['amount'].iloc[-1]=5667891.9895, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3339.9868191558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26625.0617967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1695398699, self.tradeDate='20230923', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26619.9, self.close=26606.2, self.high=26632.5, self.low=26606.1 

--ukdf-hist--: overDate='20230918' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37876 

self.closeSec=1695398999, self.tradeDate='20230923', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26606.1, self.close=26611.5, self.high=26615.0, self.low=26600.5 
127.0.0.1 - - [23/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37877 

self.closeSec=1695399299, self.tradeDate='20230923', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26611.4, self.close=26606.3, self.high=26618.7, self.low=26598.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37878 

self.closeSec=1695399599, self.tradeDate='20230923', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26606.3, self.close=26631.3, self.high=26631.3, self.low=26606.2 
127.0.0.1 - - [23/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37879 

self.closeSec=1695399899, self.tradeDate='20230923', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26631.2, self.close=26623.2, self.high=26631.3, self.low=26610.2 
127.0.0.1 - - [23/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-23 00:00:17,651:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230922    212959  26574.6  ...  48.750000  0.462068  0.486897
5802  20230922    215959  26600.0  ...  48.750000  0.461698  0.487162
5803  20230922    222959  26598.0  ...  48.750000  0.468097  0.482236
5804  20230922    225959  26620.1  ...  49.166667  0.481724  0.466426
5805  20230922    232959  26666.9  ...  48.750000  0.478252  0.454783

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-09-23 00:00:17,707:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.498892  0.501108       0  ...  0.899776  -1.0    0.0  1.030874
540     1  0.491673  0.508327       1  ...  0.899028  -1.0    0.0  1.031731
541     1  0.498262  0.501738       1  ...  0.897411  -1.0    0.0  1.033587
542     0  0.507525  0.492475       0  ...  0.897858  -1.0    0.0  1.033072
543     1  0.494232  0.505768       0  ...  0.899027  -1.0    0.0  1.031727

[5 rows x 10 columns]
2023-09-23 00:00:17,717:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498761  0.501239       0  ...  0.899776  -1.0    0.0  1.028960
46     1  0.491784  0.508216       1  ...  0.899028  -1.0    0.0  1.030597
47     1  0.498477  0.501523       1  ...  0.897411  -1.0    0.0  1.033611
48     0  0.507733  0.492267       0  ...  0.897858  -1.0    0.0  1.033096
49     1  0.494232  0.505768       0  ...  0.899027  -1.0    0.0  1.031727

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '13161.009', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26618.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18935 

self.closeSec=1695396599, self.tradeDate='20230922', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26662', self.close='26654.6'
127.0.0.1 - - [22/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18936 

self.closeSec=1695397199, self.tradeDate='20230922', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26654.5', self.close='26674.4'
127.0.0.1 - - [22/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18937 

self.closeSec=1695397799, self.tradeDate='20230922', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26674.5', self.close='26636.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18938 

self.closeSec=1695398399, self.tradeDate='20230922', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26636.4', self.close='26619.9'
127.0.0.1 - - [23/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18939 

self.closeSec=1695398999, self.tradeDate='20230923', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26619.9', self.close='26611.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18940 

self.closeSec=1695399599, self.tradeDate='20230923', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26611.4', self.close='26631.3'
127.0.0.1 - - [23/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18938 

self.closeSec=1695396599, self.tradeDate='20230922', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26662', self.close='26654.6'
127.0.0.1 - - [22/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18939 

self.closeSec=1695397199, self.tradeDate='20230922', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26654.5', self.close='26674.4'
127.0.0.1 - - [22/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18940 

self.closeSec=1695397799, self.tradeDate='20230922', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26674.5', self.close='26636.5'
127.0.0.1 - - [23/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18941 

self.closeSec=1695398399, self.tradeDate='20230922', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26636.4', self.close='26619.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18942 

self.closeSec=1695398999, self.tradeDate='20230923', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26619.9', self.close='26611.5'
127.0.0.1 - - [23/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18943 

self.closeSec=1695399599, self.tradeDate='20230923', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26611.4', self.close='26631.3'
127.0.0.1 - - [23/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18938 

self.closeSec=1695396599, self.tradeDate='20230922', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26662', self.close='26654.6'
127.0.0.1 - - [22/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18939 

self.closeSec=1695397199, self.tradeDate='20230922', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26654.5', self.close='26674.4'

--handleKline--: 127.0.0.1 - - [22/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18940 

self.closeSec=1695397799, self.tradeDate='20230922', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26674.5', self.close='26636.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18941 

127.0.0.1 - - [23/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
self.closeSec=1695398399, self.tradeDate='20230922', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26636.4', self.close='26619.9'
127.0.0.1 - - [23/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18942 

self.closeSec=1695398999, self.tradeDate='20230923', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26619.9', self.close='26611.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18943 

self.closeSec=1695399599, self.tradeDate='20230923', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26611.4', self.close='26631.3'
127.0.0.1 - - [23/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37876
self.closeSec=1695399599, self.tradeDate='20230923', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26606.3, self.close=26631.3, self.high=26631.3, self.low=26606.2, self.vol=535.627, self.amt=14257215.6796 
127.0.0.1 - - [23/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-23 00:20:06,505:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230922   235500    235959  ...         0.0        0.0       0
5760  20230923   000000    000459  ...         0.0        0.0       0
5761  20230923   000500    000959  ...         0.0        0.0       0
5762  20230923   001000    001459  ...         0.0        0.0       0
5763  20230923   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 00:20:06,517:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695399599, self.tradeDate='20230923', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26606.3, self.close=26631.3, self.high=26631.3, self.low=26606.2, self.vol=535.627, self.amt=14257215.6796, ukdf['pct'].iloc[-1]=0.00094 , ukdf['amount'].iloc[-1]=14257215.6796, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-7903.6048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26631.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [23/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37877
self.closeSec=1695399899, self.tradeDate='20230923', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26631.2, self.close=26623.2, self.high=26631.3, self.low=26610.2, self.vol=212.92, self.amt=5667891.9895 
2023-09-23 00:25:00,787:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230923   000000    000459  ...         0.0        0.0       0
5761  20230923   000500    000959  ...         0.0        0.0       0
5762  20230923   001000    001459  ...         0.0        0.0       0
5763  20230923   001500    001959  ...         0.0        0.0       0
5764  20230923   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 00:25:00,788:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695399899, self.tradeDate='20230923', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26631.2, self.close=26623.2, self.high=26631.3, self.low=26610.2, self.vol=212.92, self.amt=5667891.9895, ukdf['pct'].iloc[-1]=-0.000304 , ukdf['amount'].iloc[-1]=5667891.9895, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-8131.5838087653', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26625.0617967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230922   120000    155959  1695369599  ...    723  0.653103  0.571336     NaN
724  20230922   160000    195959  1695383999  ...    724  0.669128  0.598612     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-31355.8938', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26634', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=789
self.closeSec=1695398399, self.tradeDate='20230922', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26630.1, self.close=26619.9, self.high=26688.2, self.low=26540.6, self.vol=37446.547, self.amt=996694271.3423 
127.0.0.1 - - [23/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-23 00:00:01,573:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695398399, self.tradeDate='20230922', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26630.1, self.close=26619.9, self.high=26688.2, self.low=26540.6, self.vol=37446.547, self.amt=996694271.3423 
2023-09-23 00:00:01,602:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230922   040000    075959  ...  18947.754  5.032164e+08 -0.001275
722  20230922   080000    115959  ...  37097.683  9.863139e+08  0.002399
723  20230922   120000    155959  ...  22748.224  6.058066e+08  0.001664
724  20230922   160000    195959  ...  29532.864  7.868368e+08 -0.001155
725  20230922   200000    235959  ...  37446.547  9.966943e+08 -0.000383

[5 rows x 11 columns]
2023-09-23 00:00:02,347:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230922   040000    075959  1695340799  ...    721  0.639944  0.565536     NaN
722  20230922   080000    115959  1695355199  ...    722  0.593971  0.427436     NaN
723  20230922   120000    155959  1695369599  ...    723  0.653103  0.571336     NaN
724  20230922   160000    195959  1695383999  ...    724  0.669128  0.598612     NaN
725  20230922   200000    235959  1695398399  ...    725  0.798307  0.930515     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-32066.9118', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26620', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


