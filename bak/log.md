# 20231008 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42388
self.closeSec=1696753199, self.tradeDate='20231008', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27877.3, self.close=27912.0, self.high=27912.0, self.low=27867.6, self.vol=607.95, self.amt=16956893.8146 
127.0.0.1 - - [08/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-08 16:20:08,424:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231008   155500    155959  ...         0.0        0.0       0
5952  20231008   160000    160459  ...         0.0        0.0       0
5953  20231008   160500    160959  ...         0.0        0.0       0
5954  20231008   161000    161459  ...         0.0        0.0       0
5955  20231008   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 16:20:08,434:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696753199, self.tradeDate='20231008', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27877.3, self.close=27912.0, self.high=27912.0, self.low=27867.6, self.vol=607.95, self.amt=16956893.8146, ukdf['pct'].iloc[-1]=0.001241 , ukdf['amount'].iloc[-1]=16956893.8146, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14555.4552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27910.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42389
self.closeSec=1696753499, self.tradeDate='20231008', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27911.9, self.close=27922.0, self.high=27922.0, self.low=27904.9, self.vol=351.689, self.amt=9815786.8737 
2023-10-08 16:25:00,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231008   160000    160459  ...         0.0        0.0       0
5953  20231008   160500    160959  ...         0.0        0.0       0
5954  20231008   161000    161459  ...         0.0        0.0       0
5955  20231008   161500    161959  ...         0.0        0.0       0
5956  20231008   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 16:25:00,776:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696753499, self.tradeDate='20231008', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27911.9, self.close=27922.0, self.high=27922.0, self.low=27904.9, self.vol=351.689, self.amt=9815786.8737, ukdf['pct'].iloc[-1]=0.000358 , ukdf['amount'].iloc[-1]=9815786.8737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14722.5672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27922.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [08/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42386 

self.closeSec=1696751999, self.tradeDate='20231008', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27896.0, self.close=27892.4, self.high=27899.5, self.low=27892.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42387 

self.closeSec=1696752299, self.tradeDate='20231008', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27892.4, self.close=27880.0, self.high=27892.5, self.low=27880.0 
127.0.0.1 - - [08/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42388 

self.closeSec=1696752599, self.tradeDate='20231008', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27880.0, self.close=27887.3, self.high=27892.9, self.low=27877.4 
127.0.0.1 - - [08/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42389 

self.closeSec=1696752899, self.tradeDate='20231008', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27887.3, self.close=27877.4, self.high=27889.1, self.low=27860.0 
127.0.0.1 - - [08/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42390 

self.closeSec=1696753199, self.tradeDate='20231008', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27877.3, self.close=27912.0, self.high=27912.0, self.low=27867.6 
127.0.0.1 - - [08/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42391 

self.closeSec=1696753499, self.tradeDate='20231008', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27911.9, self.close=27922.0, self.high=27922.0, self.low=27904.9 
127.0.0.1 - - [08/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-08 16:00:16,880:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231008    132959  27915.3  ...  51.666667  0.513581  0.483929
5786  20231008    135959  27899.7  ...  52.083333  0.521191  0.493527
5787  20231008    142959  27925.0  ...  52.083333  0.523685  0.500273
5788  20231008    145959  27933.2  ...  51.666667  0.505740  0.521331
5789  20231008    152959  27877.7  ...  52.083333  0.509517  0.537735

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-10-08 16:00:16,939:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.486525  0.513475       1  ...  0.954930   1.0    0.0  1.063960
538     1  0.496747  0.503253       1  ...  0.955214   1.0    0.0  1.064276
539     1  0.493183  0.506817       0  ...  0.953319   1.0    0.0  1.062165
540     1  0.476420  0.523580       1  ...  0.953737   1.0    0.0  1.062630
541     1  0.498081  0.501919       1  ...  0.953819   1.0    0.0  1.062721

[5 rows x 10 columns]
2023-10-08 16:00:16,951:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486642  0.513358       1  ...  0.954930   1.0    0.0  1.068074
46     1  0.496661  0.503339       1  ...  0.955214   1.0    0.0  1.067452
47     1  0.493188  0.506812       0  ...  0.953319   1.0    0.0  1.063681
48     1  0.476553  0.523447       1  ...  0.953737   1.0    0.0  1.064674
49     1  0.498081  0.501919       1  ...  0.953819   1.0    0.0  1.062721

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.669', 'enterprice': '27936.3', 'countrevence': '0', 'unrealprofit': '-1079.3064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27890.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [08/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21191 

self.closeSec=1696750199, self.tradeDate='20231008', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27908.7', self.close='27890'
127.0.0.1 - - [08/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21192 

self.closeSec=1696750799, self.tradeDate='20231008', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27890', self.close='27880.1'
127.0.0.1 - - [08/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21193 

self.closeSec=1696751399, self.tradeDate='20231008', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27880.2', self.close='27891.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21194 

self.closeSec=1696751999, self.tradeDate='20231008', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27891.1', self.close='27892.4'
127.0.0.1 - - [08/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21195 

self.closeSec=1696752599, self.tradeDate='20231008', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27892.4', self.close='27887.3'
127.0.0.1 - - [08/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21196 

self.closeSec=1696753199, self.tradeDate='20231008', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27887.3', self.close='27912'
127.0.0.1 - - [08/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21194 

self.closeSec=1696750199, self.tradeDate='20231008', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27908.7', self.close='27890'
127.0.0.1 - - [08/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21195 

self.closeSec=1696750799, self.tradeDate='20231008', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27890', self.close='27880.1'
127.0.0.1 - - [08/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21196 

self.closeSec=1696751399, self.tradeDate='20231008', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27880.2', self.close='27891.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21197 

self.closeSec=1696751999, self.tradeDate='20231008', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27891.1', self.close='27892.4'
127.0.0.1 - - [08/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21198 

self.closeSec=1696752599, self.tradeDate='20231008', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27892.4', self.close='27887.3'
127.0.0.1 - - [08/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21199 

self.closeSec=1696753199, self.tradeDate='20231008', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27887.3', self.close='27912'
127.0.0.1 - - [08/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21194 

self.closeSec=1696750199, self.tradeDate='20231008', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27908.7', self.close='27890'
127.0.0.1 - - [08/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21195 

self.closeSec=1696750799, self.tradeDate='20231008', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27890', self.close='27880.1'
127.0.0.1 - - [08/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21196 

self.closeSec=1696751399, self.tradeDate='20231008', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27880.2', self.close='27891.1'
127.0.0.1 - - [08/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21197 

self.closeSec=1696751999, self.tradeDate='20231008', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27891.1', self.close='27892.4'
127.0.0.1 - - [08/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21198 

self.closeSec=1696752599, self.tradeDate='20231008', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27892.4', self.close='27887.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21199 

self.closeSec=1696753199, self.tradeDate='20231008', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27887.3', self.close='27912'
127.0.0.1 - - [08/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42388
self.closeSec=1696753199, self.tradeDate='20231008', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27877.3, self.close=27912.0, self.high=27912.0, self.low=27867.6, self.vol=607.95, self.amt=16956893.8146 
127.0.0.1 - - [08/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-08 16:20:08,424:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231008   155500    155959  ...         0.0        0.0       0
5952  20231008   160000    160459  ...         0.0        0.0       0
5953  20231008   160500    160959  ...         0.0        0.0       0
5954  20231008   161000    161459  ...         0.0        0.0       0
5955  20231008   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 16:20:08,435:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696753199, self.tradeDate='20231008', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27877.3, self.close=27912.0, self.high=27912.0, self.low=27867.6, self.vol=607.95, self.amt=16956893.8146, ukdf['pct'].iloc[-1]=0.001241 , ukdf['amount'].iloc[-1]=16956893.8146, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '39596.0201', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27910.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42389
self.closeSec=1696753499, self.tradeDate='20231008', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27911.9, self.close=27922.0, self.high=27922.0, self.low=27904.9, self.vol=351.689, self.amt=9815786.8737 
127.0.0.1 - - [08/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-10-08 16:25:00,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231008   160000    160459  ...         0.0        0.0       0
5953  20231008   160500    160959  ...         0.0        0.0       0
5954  20231008   161000    161459  ...         0.0        0.0       0
5955  20231008   161500    161959  ...         0.0        0.0       0
5956  20231008   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 16:25:00,789:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696753499, self.tradeDate='20231008', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27911.9, self.close=27922.0, self.high=27922.0, self.low=27904.9, self.vol=351.689, self.amt=9815786.8737, ukdf['pct'].iloc[-1]=0.000358 , ukdf['amount'].iloc[-1]=9815786.8737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '40041.7121', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27922.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231008   040000    075959  1696723199  ...    721  0.187564 -1.120572    -1.0
722  20231008   080000    115959  1696737599  ...    722  0.168992 -1.143476    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '-4721.5551', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28052.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=883
self.closeSec=1696751999, self.tradeDate='20231008', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28050.0, self.close=27892.4, self.high=28061.5, self.low=27864.6, self.vol=28016.932, self.amt=782529849.9626 
127.0.0.1 - - [08/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-08 16:00:01,504:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696751999, self.tradeDate='20231008', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28050.0, self.close=27892.4, self.high=28061.5, self.low=27864.6, self.vol=28016.932, self.amt=782529849.9626 
2023-10-08 16:00:01,522:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231007   200000    235959  ...  17899.597  4.998671e+08 -0.000107
720  20231008   000000    035959  ...  19858.010  5.539527e+08 -0.002750
721  20231008   040000    075959  ...  10265.905  2.865590e+08  0.003357
722  20231008   080000    115959  ...  23359.950  6.542793e+08  0.003822
723  20231008   120000    155959  ...  28016.932  7.825298e+08 -0.005615

[5 rows x 11 columns]
2023-10-08 16:00:02,448:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231007   200000    235959  1696694399  ...    719  0.233707 -1.051917    -1.0
720  20231008   000000    035959  1696708799  ...    720  0.219918 -1.063583    -1.0
721  20231008   040000    075959  1696723199  ...    721  0.187564 -1.120572    -1.0
722  20231008   080000    115959  1696737599  ...    722  0.168992 -1.143476    -1.0
723  20231008   120000    155959  1696751999  ...    723  0.150071 -1.168478    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '2238.96425830127', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27893.04407509', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


