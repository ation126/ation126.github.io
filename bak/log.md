# 20230829 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30676
self.closeSec=1693239599, self.tradeDate='20230829', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26113.5, self.close=26132.0, self.high=26137.1, self.low=26113.4, self.vol=737.944, self.amt=19278090.9675 
127.0.0.1 - - [29/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-29 00:20:05,152:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230828   235500    235959  ...         0.0        0.0       0
5748  20230829   000000    000459  ...         0.0        0.0       0
5749  20230829   000500    000959  ...         0.0        0.0       0
5750  20230829   001000    001459  ...         0.0        0.0       0
5751  20230829   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 00:20:05,156:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693239599, self.tradeDate='20230829', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26113.5, self.close=26132.0, self.high=26137.1, self.low=26113.4, self.vol=737.944, self.amt=19278090.9675, ukdf['pct'].iloc[-1]=0.000708 , ukdf['amount'].iloc[-1]=19278090.9675, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10224.03813167154', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26130.73095421', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30677
self.closeSec=1693239899, self.tradeDate='20230829', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26131.6, self.close=26119.5, self.high=26131.6, self.low=26108.0, self.vol=525.22, self.amt=13717983.3689 
127.0.0.1 - - [29/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-29 00:25:00,797:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230829   000000    000459  ...         0.0        0.0       0
5749  20230829   000500    000959  ...         0.0        0.0       0
5750  20230829   001000    001459  ...         0.0        0.0       0
5751  20230829   001500    001959  ...         0.0        0.0       0
5752  20230829   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 00:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693239899, self.tradeDate='20230829', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26131.6, self.close=26119.5, self.high=26131.6, self.low=26108.0, self.vol=525.22, self.amt=13717983.3689, ukdf['pct'].iloc[-1]=-0.000478 , ukdf['amount'].iloc[-1]=13717983.3689, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10351.1958', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26121.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1693238699, self.tradeDate='20230829', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26093.4, self.close=26106.6, self.high=26112.2, self.low=26084.8 

--ukdf-hist--: overDate='20230824' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30676 

self.closeSec=1693238999, self.tradeDate='20230829', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26106.6, self.close=26110.0, self.high=26111.9, self.low=26086.7 
127.0.0.1 - - [29/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30677 

self.closeSec=1693239299, self.tradeDate='20230829', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26108.0, self.close=26113.5, self.high=26113.5, self.low=26102.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30678 

self.closeSec=1693239599, self.tradeDate='20230829', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26113.5, self.close=26132.0, self.high=26137.1, self.low=26113.4 
127.0.0.1 - - [29/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30679 

self.closeSec=1693239899, self.tradeDate='20230829', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26131.6, self.close=26119.5, self.high=26131.6, self.low=26108.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-29 00:00:17,839:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230828    212959  26126.0  ...  50.416667  0.534775  0.600349
5802  20230828    215959  26110.3  ...  50.000000  0.523666  0.586978
5803  20230828    222959  26087.0  ...  50.416667  0.533801  0.570441
5804  20230828    225959  26111.0  ...  50.416667  0.540207  0.552401
5805  20230828    232959  26126.5  ...  50.416667  0.543820  0.534093

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-08-29 00:00:17,903:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.502007  0.497993       0  ...  1.034213   1.0    0.0  0.911715
540     1  0.497791  0.502209       1  ...  1.035165   1.0    0.0  0.912554
541     0  0.511515  0.488485       1  ...  1.035775   1.0    0.0  0.913092
542     1  0.497945  0.502055       1  ...  1.036120   1.0    0.0  0.913396
543     1  0.497543  0.502457       0  ...  1.034384   1.0    0.0  0.911866

[5 rows x 10 columns]
2023-08-29 00:00:17,915:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501862  0.498138       0  ...  1.034213   1.0    0.0  0.910061
46     1  0.497550  0.502450       1  ...  1.035165   1.0    0.0  0.910559
47     0  0.511440  0.488560       1  ...  1.035775   1.0    0.0  0.912971
48     1  0.497952  0.502048       1  ...  1.036120   1.0    0.0  0.913275
49     1  0.497543  0.502457       0  ...  1.034384   1.0    0.0  0.911866

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.794', 'enterprice': '26128.9', 'countrevence': '0', 'unrealprofit': '-978.996', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26094.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15335 

self.closeSec=1693236599, self.tradeDate='20230828', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26110.9', self.close='26135.2'
127.0.0.1 - - [28/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15336 

self.closeSec=1693237199, self.tradeDate='20230828', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26135.2', self.close='26166.2'
127.0.0.1 - - [28/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15337 

self.closeSec=1693237799, self.tradeDate='20230828', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26170.8', self.close='26097.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15338 

self.closeSec=1693238399, self.tradeDate='20230828', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26097.4', self.close='26093.3'
127.0.0.1 - - [29/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15339 

self.closeSec=1693238999, self.tradeDate='20230829', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26093.4', self.close='26110'
127.0.0.1 - - [29/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15340 

self.closeSec=1693239599, self.tradeDate='20230829', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26108', self.close='26132'
127.0.0.1 - - [29/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15338 

self.closeSec=1693236599, self.tradeDate='20230828', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26110.9', self.close='26135.2'
127.0.0.1 - - [28/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15339 127.0.0.1 - - [28/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -


self.closeSec=1693237199, self.tradeDate='20230828', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26135.2', self.close='26166.2'

--handleKline--: 127.0.0.1 - - [28/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15340 

self.closeSec=1693237799, self.tradeDate='20230828', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26170.8', self.close='26097.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15341 

self.closeSec=1693238399, self.tradeDate='20230828', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26097.4', self.close='26093.3'
127.0.0.1 - - [29/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15342 

self.closeSec=1693238999, self.tradeDate='20230829', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26093.4', self.close='26110'
127.0.0.1 - - [29/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15343 

self.closeSec=1693239599, self.tradeDate='20230829', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26108', self.close='26132'
127.0.0.1 - - [29/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [28/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15338 

self.closeSec=1693236599, self.tradeDate='20230828', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26110.9', self.close='26135.2'

--handleKline--: 127.0.0.1 - - [28/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15339 

self.closeSec=1693237199, self.tradeDate='20230828', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26135.2', self.close='26166.2'
127.0.0.1 - - [28/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15340 

self.closeSec=1693237799, self.tradeDate='20230828', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26170.8', self.close='26097.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15341 

self.closeSec=1693238399, self.tradeDate='20230828', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26097.4', self.close='26093.3'
127.0.0.1 - - [29/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15342 

self.closeSec=1693238999, self.tradeDate='20230829', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26093.4', self.close='26110'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15343 

self.closeSec=1693239599, self.tradeDate='20230829', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26108', self.close='26132'
127.0.0.1 - - [29/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30676
self.closeSec=1693239599, self.tradeDate='20230829', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26113.5, self.close=26132.0, self.high=26137.1, self.low=26113.4, self.vol=737.944, self.amt=19278090.9675 
127.0.0.1 - - [29/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-29 00:20:05,152:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230828   235500    235959  ...         0.0        0.0       0
5748  20230829   000000    000459  ...         0.0        0.0       0
5749  20230829   000500    000959  ...         0.0        0.0       0
5750  20230829   001000    001459  ...         0.0        0.0       0
5751  20230829   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 00:20:05,155:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693239599, self.tradeDate='20230829', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26113.5, self.close=26132.0, self.high=26137.1, self.low=26113.4, self.vol=737.944, self.amt=19278090.9675, ukdf['pct'].iloc[-1]=0.000708 , ukdf['amount'].iloc[-1]=19278090.9675, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26491.52562968639', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26130.73095421', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [29/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30677
self.closeSec=1693239899, self.tradeDate='20230829', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26131.6, self.close=26119.5, self.high=26131.6, self.low=26108.0, self.vol=525.22, self.amt=13717983.3689 
2023-08-29 00:25:00,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230829   000000    000459  ...         0.0        0.0       0
5749  20230829   000500    000959  ...         0.0        0.0       0
5750  20230829   001000    001459  ...         0.0        0.0       0
5751  20230829   001500    001959  ...         0.0        0.0       0
5752  20230829   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 00:25:00,790:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693239899, self.tradeDate='20230829', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26131.6, self.close=26119.5, self.high=26131.6, self.low=26108.0, self.vol=525.22, self.amt=13717983.3689, ukdf['pct'].iloc[-1]=-0.000478 , ukdf['amount'].iloc[-1]=13717983.3689, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26830.6584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26121.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230828   120000    155959  1693209599  ...    723  0.170310 -0.261334     NaN
724  20230828   160000    195959  1693223999  ...    724  0.076940 -0.697728    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '176707.9156', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25993.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [29/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=639
self.closeSec=1693238399, self.tradeDate='20230828', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25992.8, self.close=26091.3, self.high=26244.6, self.low=25980.0, self.vol=68566.281, self.amt=1790877221.88296 
2023-08-29 00:00:01,562:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693238399, self.tradeDate='20230828', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25992.8, self.close=26091.3, self.high=26244.6, self.low=25980.0, self.vol=68566.281, self.amt=1790877221.88296 
2023-08-29 00:00:01,580:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230828   040000    075959  ...  11740.215  3.061151e+08 -0.000934
722  20230828   080000    115959  ...  26342.016  6.855075e+08 -0.003285
723  20230828   120000    155959  ...  30904.881  8.016251e+08 -0.003038
724  20230828   160000    195959  ...  27052.356  7.015093e+08  0.002693
725  20230828   200000    235959  ...  68566.281  1.790877e+09  0.003790

[5 rows x 11 columns]
2023-08-29 00:00:02,384:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230828   040000    075959  1693180799  ...    721  0.356459  0.461291     NaN
722  20230828   080000    115959  1693195199  ...    722  0.262611  0.118184     NaN
723  20230828   120000    155959  1693209599  ...    723  0.170310 -0.261334     NaN
724  20230828   160000    195959  1693223999  ...    724  0.076940 -0.697728    -1.0
725  20230828   200000    235959  1693238399  ...    725  0.000009 -1.132751    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '171599.9484', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26093.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


