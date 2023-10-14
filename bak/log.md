# 20231015 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44212
self.closeSec=1697300399, self.tradeDate='20231015', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26917.9, self.close=26907.4, self.high=26926.0, self.low=26901.8, self.vol=409.1, self.amt=11010975.9882 
127.0.0.1 - - [15/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-10-15 00:20:08,254:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231014   235500    235959  ...         0.0        0.0       0
5760  20231015   000000    000459  ...         0.0        0.0       0
5761  20231015   000500    000959  ...         0.0        0.0       0
5762  20231015   001000    001459  ...         0.0        0.0       0
5763  20231015   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 00:20:08,273:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697300399, self.tradeDate='20231015', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26917.9, self.close=26907.4, self.high=26926.0, self.low=26901.8, self.vol=409.1, self.amt=11010975.9882, ukdf['pct'].iloc[-1]=-0.00039 , ukdf['amount'].iloc[-1]=11010975.9882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-611.3514', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26908.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44213
self.closeSec=1697300699, self.tradeDate='20231015', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26908.8, self.close=26902.1, self.high=26908.8, self.low=26895.2, self.vol=743.441, self.amt=19998314.4801 
127.0.0.1 - - [15/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-15 00:25:03,274:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231015   000000    000459  ...         0.0        0.0       0
5761  20231015   000500    000959  ...         0.0        0.0       0
5762  20231015   001000    001459  ...         0.0        0.0       0
5763  20231015   001500    001959  ...         0.0        0.0       0
5764  20231015   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 00:25:03,277:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697300699, self.tradeDate='20231015', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26908.8, self.close=26902.1, self.high=26908.8, self.low=26895.2, self.vol=743.441, self.amt=19998314.4801, ukdf['pct'].iloc[-1]=-0.000197 , ukdf['amount'].iloc[-1]=19998314.4801, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-516.6546', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1697299499, self.tradeDate='20231015', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26927.9, self.close=26933.3, self.high=26935.7, self.low=26905.9 

--ukdf-hist--: overDate='20231010' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44212 

self.closeSec=1697299799, self.tradeDate='20231015', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26933.2, self.close=26917.0, self.high=26937.9, self.low=26915.6 
127.0.0.1 - - [15/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44213 

self.closeSec=1697300099, self.tradeDate='20231015', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26916.9, self.close=26917.9, self.high=26923.5, self.low=26904.2 
127.0.0.1 - - [15/Oct/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44214 

self.closeSec=1697300399, self.tradeDate='20231015', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26917.9, self.close=26907.4, self.high=26926.0, self.low=26901.8 
127.0.0.1 - - [15/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44215 

self.closeSec=1697300699, self.tradeDate='20231015', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26908.8, self.close=26902.1, self.high=26908.8, self.low=26895.2 
127.0.0.1 - - [15/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-15 00:00:19,185:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231014    212959  26882.3  ...  50.416667  0.504213  0.554353
5802  20231014    215959  26871.0  ...  50.416667  0.512565  0.554002
5803  20231014    222959  26894.7  ...  50.000000  0.508488  0.555471
5804  20231014    225959  26883.7  ...  50.000000  0.504981  0.558381
5805  20231014    232959  26874.3  ...  50.000000  0.508549  0.561142

[5 rows x 33 columns]
0.5569852941176471
acc is : 0.5569852941176471
2023-10-15 00:00:19,265:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.490592  0.509408       1  ...  0.942742   1.0    0.0  0.976998
540     0  0.504626  0.495374       0  ...  0.942353   1.0    0.0  0.976595
541     1  0.493593  0.506407       0  ...  0.942020   1.0    0.0  0.976250
542     1  0.493961  0.506039       1  ...  0.942364   1.0    0.0  0.976606
543     1  0.497880  0.502120       1  ...  0.943948   1.0    0.0  0.978248

[5 rows x 10 columns]
2023-10-15 00:00:19,280:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490391  0.509609       1  ...  0.942742   1.0    0.0  0.975015
46     0  0.504401  0.495599       0  ...  0.942353   1.0    0.0  0.973275
47     1  0.493506  0.506494       0  ...  0.942020   1.0    0.0  0.974823
48     1  0.493855  0.506145       1  ...  0.942364   1.0    0.0  0.975178
49     1  0.497880  0.502120       1  ...  0.943948   1.0    0.0  0.978248

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.627', 'enterprice': '27009.6', 'countrevence': '0', 'unrealprofit': '-1914.95829694777', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26928.55042549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22103 

self.closeSec=1697297399, self.tradeDate='20231014', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26904.4', self.close='26884'
127.0.0.1 - - [14/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22104 

self.closeSec=1697297999, self.tradeDate='20231014', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26884', self.close='26899.6'

--handleKline--: 127.0.0.1 - - [14/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22105 

self.closeSec=1697298599, self.tradeDate='20231014', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26899.6', self.close='26917.9'
127.0.0.1 - - [15/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22106 

self.closeSec=1697299199, self.tradeDate='20231014', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26918', self.close='26929.2'
127.0.0.1 - - [15/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22107 

self.closeSec=1697299799, self.tradeDate='20231015', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26927.9', self.close='26917'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22108 

self.closeSec=1697300399, self.tradeDate='20231015', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26916.9', self.close='26908.7'
127.0.0.1 - - [15/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [14/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22106 

self.closeSec=1697297399, self.tradeDate='20231014', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26904.4', self.close='26884'
127.0.0.1 - - [14/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22107 

self.closeSec=1697297999, self.tradeDate='20231014', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26884', self.close='26899.6'
127.0.0.1 - - [14/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22108 

self.closeSec=1697298599, self.tradeDate='20231014', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26899.6', self.close='26917.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22109 

self.closeSec=1697299199, self.tradeDate='20231014', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26918', self.close='26929.2'
127.0.0.1 - - [15/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22110 

self.closeSec=1697299799, self.tradeDate='20231015', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26927.9', self.close='26917'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22111 

self.closeSec=1697300399, self.tradeDate='20231015', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26916.9', self.close='26908.7'
127.0.0.1 - - [15/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [14/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22106 

self.closeSec=1697297399, self.tradeDate='20231014', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26904.4', self.close='26884'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22107 

self.closeSec=1697297999, self.tradeDate='20231014', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26884', self.close='26899.6'
127.0.0.1 - - [14/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22108 

self.closeSec=1697298599, self.tradeDate='20231014', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26899.6', self.close='26917.9'
127.0.0.1 - - [14/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22109 

self.closeSec=1697299199, self.tradeDate='20231014', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26918', self.close='26929.2'
127.0.0.1 - - [15/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22110 

self.closeSec=1697299799, self.tradeDate='20231015', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26927.9', self.close='26917'
127.0.0.1 - - [15/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22111 

self.closeSec=1697300399, self.tradeDate='20231015', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26916.9', self.close='26908.7'
127.0.0.1 - - [15/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44212
self.closeSec=1697300399, self.tradeDate='20231015', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26917.9, self.close=26907.4, self.high=26926.0, self.low=26901.8, self.vol=409.1, self.amt=11010975.9882 
127.0.0.1 - - [15/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-10-15 00:20:08,273:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231014   235500    235959  ...         0.0        0.0       0
5760  20231015   000000    000459  ...         0.0        0.0       0
5761  20231015   000500    000959  ...         0.0        0.0       0
5762  20231015   001000    001459  ...         0.0        0.0       0
5763  20231015   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 00:20:08,293:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697300399, self.tradeDate='20231015', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26917.9, self.close=26907.4, self.high=26926.0, self.low=26901.8, self.vol=409.1, self.amt=11010975.9882, ukdf['pct'].iloc[-1]=-0.00039 , ukdf['amount'].iloc[-1]=11010975.9882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2406.7368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26908.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44213
self.closeSec=1697300699, self.tradeDate='20231015', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26908.8, self.close=26902.1, self.high=26908.8, self.low=26895.2, self.vol=743.441, self.amt=19998314.4801 
127.0.0.1 - - [15/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-15 00:25:03,276:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231015   000000    000459  ...         0.0        0.0       0
5761  20231015   000500    000959  ...         0.0        0.0       0
5762  20231015   001000    001459  ...         0.0        0.0       0
5763  20231015   001500    001959  ...         0.0        0.0       0
5764  20231015   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 00:25:03,279:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697300699, self.tradeDate='20231015', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26908.8, self.close=26902.1, self.high=26908.8, self.low=26895.2, self.vol=743.441, self.amt=19998314.4801, ukdf['pct'].iloc[-1]=-0.000197 , ukdf['amount'].iloc[-1]=19998314.4801, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2154.178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231014   120000    155959  1697270399  ...    723  0.832137  0.715226     1.0
724  20231014   160000    195959  1697284799  ...    724  0.866498  0.815273     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '1676.93225498179', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26862.46816457', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [15/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1263543.0464457, self.flagDict['side']='buy', self.tradeCount=33, self.count=921
self.closeSec=1697299199, self.tradeDate='20231014', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26860.1, self.close=26929.2, self.high=26930.0, self.low=26837.6, self.vol=13269.386, self.amt=356731118.5534 
2023-10-15 00:00:01,534:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697299199, self.tradeDate='20231014', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26860.1, self.close=26929.2, self.high=26930.0, self.low=26837.6, self.vol=13269.386, self.amt=356731118.5534 
2023-10-15 00:00:01,556:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231014   040000    075959  ...  93383.298  2.515112e+09  0.003048
722  20231014   080000    115959  ...  19650.989  5.285537e+08  0.002544
723  20231014   120000    155959  ...  14754.421  3.965367e+08 -0.002140
724  20231014   160000    195959  ...   9363.638  2.515109e+08 -0.000015
725  20231014   200000    235959  ...  13269.386  3.567311e+08  0.002573

[5 rows x 11 columns]
2023-10-15 00:00:02,484:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231014   040000    075959  1697241599  ...    721  0.804414  0.629649     1.0
722  20231014   080000    115959  1697255999  ...    722  0.845632  0.747851     1.0
723  20231014   120000    155959  1697270399  ...    723  0.832137  0.715226     1.0
724  20231014   160000    195959  1697284799  ...    724  0.866498  0.815273     1.0
725  20231014   200000    235959  1697299199  ...    725  0.799389  0.627588     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '4801.31098051346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26928.73704118', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


