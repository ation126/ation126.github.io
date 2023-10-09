# 20231010 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42772
self.closeSec=1696868399, self.tradeDate='20231010', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27452.0, self.close=27491.1, self.high=27504.8, self.low=27440.4, self.vol=1064.992, self.amt=29263148.6743 
127.0.0.1 - - [10/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-10-10 00:20:06,840:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231009   235500    235959  ...         0.0        0.0       0
5760  20231010   000000    000459  ...         0.0        0.0       0
5761  20231010   000500    000959  ...         0.0        0.0       0
5762  20231010   001000    001459  ...         0.0        0.0       0
5763  20231010   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 00:20:06,848:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696868399, self.tradeDate='20231010', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27452.0, self.close=27491.1, self.high=27504.8, self.low=27440.4, self.vol=1064.992, self.amt=29263148.6743, ukdf['pct'].iloc[-1]=0.001457 , ukdf['amount'].iloc[-1]=29263148.6743, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-8775.7571375628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27495.0706978', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42773
self.closeSec=1696868699, self.tradeDate='20231010', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27490.6, self.close=27510.4, self.high=27539.4, self.low=27486.5, self.vol=2197.305, self.amt=60466427.526 
127.0.0.1 - - [10/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-10-10 00:25:00,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231010   000000    000459  ...         0.0        0.0       0
5761  20231010   000500    000959  ...         0.0        0.0       0
5762  20231010   001000    001459  ...         0.0        0.0       0
5763  20231010   001500    001959  ...         0.0        0.0       0
5764  20231010   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 00:25:00,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696868699, self.tradeDate='20231010', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27490.6, self.close=27510.4, self.high=27539.4, self.low=27486.5, self.vol=2197.305, self.amt=60466427.526, ukdf['pct'].iloc[-1]=0.000702 , ukdf['amount'].iloc[-1]=60466427.526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-9012.85131746868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27512.09598718', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1696867499, self.tradeDate='20231010', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27433.1, self.close=27453.5, self.high=27467.4, self.low=27342.0 

--ukdf-hist--: overDate='20231005' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [10/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42772 

self.closeSec=1696867799, self.tradeDate='20231010', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27455.0, self.close=27489.0, self.high=27502.5, self.low=27441.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42773 

self.closeSec=1696868099, self.tradeDate='20231010', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27489.0, self.close=27451.1, self.high=27489.0, self.low=27427.7 
127.0.0.1 - - [10/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42774 

self.closeSec=1696868399, self.tradeDate='20231010', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27452.0, self.close=27491.1, self.high=27504.8, self.low=27440.4 
127.0.0.1 - - [10/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42775 

self.closeSec=1696868699, self.tradeDate='20231010', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27490.6, self.close=27510.4, self.high=27539.4, self.low=27486.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-10 00:00:17,496:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231009    212959  27425.4  ...  50.416667  0.389238  0.629563
5802  20231009    215959  27450.1  ...  50.833333  0.409561  0.638367
5803  20231009    222959  27505.8  ...  51.250000  0.412859  0.645594
5804  20231009    225959  27517.8  ...  50.833333  0.405744  0.655388
5805  20231009    232959  27486.6  ...  50.833333  0.414799  0.661846

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-10-10 00:00:17,569:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495194  0.504806       1  ...  0.974745  -1.0    0.0  1.040082
540     0  0.508454  0.491546       1  ...  0.974419  -1.0    0.0  1.040430
541     1  0.498827  0.501173       0  ...  0.975421  -1.0    0.0  1.039360
542     1  0.484657  0.515343       1  ...  0.974538  -1.0    0.0  1.040301
543     0  0.505025  0.494975       0  ...  0.977315  -1.0    0.0  1.037337

[5 rows x 10 columns]
2023-10-10 00:00:17,580:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495302  0.504698       1  ...  0.974745  -1.0    0.0  1.041441
46     0  0.508479  0.491521       1  ...  0.974419  -1.0    0.0  1.039797
47     1  0.498945  0.501055       0  ...  0.975421  -1.0    0.0  1.039325
48     1  0.484747  0.515253       1  ...  0.974538  -1.0    0.0  1.040266
49     0  0.505025  0.494975       0  ...  0.977315  -1.0    0.0  1.037337

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.618', 'enterprice': '27520.8', 'countrevence': '0', 'unrealprofit': '2089.2509618239', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27432.33988645', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21383 

self.closeSec=1696865399, self.tradeDate='20231009', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27496.4', self.close='27511.5'
127.0.0.1 - - [09/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21384 

self.closeSec=1696865999, self.tradeDate='20231009', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27511.4', self.close='27505'
127.0.0.1 - - [09/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21385 

self.closeSec=1696866599, self.tradeDate='20231009', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27505', self.close='27455.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21386 

self.closeSec=1696867199, self.tradeDate='20231009', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27455.7', self.close='27433.1'
127.0.0.1 - - [10/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21387 

self.closeSec=1696867799, self.tradeDate='20231010', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27433.1', self.close='27489'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21388 

self.closeSec=1696868399, self.tradeDate='20231010', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27489', self.close='27491.1'
127.0.0.1 - - [10/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21386 

self.closeSec=1696865399, self.tradeDate='20231009', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27496.4', self.close='27511.5'
127.0.0.1 - - [09/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21387 

self.closeSec=1696865999, self.tradeDate='20231009', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27511.4', self.close='27505'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21388 

self.closeSec=1696866599, self.tradeDate='20231009', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27505', self.close='27455.8'
127.0.0.1 - - [09/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21389 

self.closeSec=1696867199, self.tradeDate='20231009', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27455.7', self.close='27433.1'
127.0.0.1 - - [10/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21390 

self.closeSec=1696867799, self.tradeDate='20231010', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27433.1', self.close='27489'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21391 

self.closeSec=1696868399, self.tradeDate='20231010', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27489', self.close='27491.1'
127.0.0.1 - - [10/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [09/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21386 

self.closeSec=1696865399, self.tradeDate='20231009', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27496.4', self.close='27511.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21387 

self.closeSec=1696865999, self.tradeDate='20231009', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27511.4', self.close='27505'
127.0.0.1 - - [09/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21388 

self.closeSec=1696866599, self.tradeDate='20231009', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27505', self.close='27455.8'
127.0.0.1 - - [10/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21389 

self.closeSec=1696867199, self.tradeDate='20231009', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27455.7', self.close='27433.1'
127.0.0.1 - - [10/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21390 

self.closeSec=1696867799, self.tradeDate='20231010', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27433.1', self.close='27489'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21391 

self.closeSec=1696868399, self.tradeDate='20231010', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27489', self.close='27491.1'
127.0.0.1 - - [10/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42772
self.closeSec=1696868399, self.tradeDate='20231010', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27452.0, self.close=27491.1, self.high=27504.8, self.low=27440.4, self.vol=1064.992, self.amt=29263148.6743 
127.0.0.1 - - [10/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-10-10 00:20:06,839:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231009   235500    235959  ...         0.0        0.0       0
5760  20231010   000000    000459  ...         0.0        0.0       0
5761  20231010   000500    000959  ...         0.0        0.0       0
5762  20231010   001000    001459  ...         0.0        0.0       0
5763  20231010   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 00:20:06,846:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696868399, self.tradeDate='20231010', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27452.0, self.close=27491.1, self.high=27504.8, self.low=27440.4, self.vol=1064.992, self.amt=29263148.6743, ukdf['pct'].iloc[-1]=0.001457 , ukdf['amount'].iloc[-1]=29263148.6743, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '24181.4167869898', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27495.0706978', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [10/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42773
self.closeSec=1696868699, self.tradeDate='20231010', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27490.6, self.close=27510.4, self.high=27539.4, self.low=27486.5, self.vol=2197.305, self.amt=60466427.526 
2023-10-10 00:25:00,799:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231010   000000    000459  ...         0.0        0.0       0
5761  20231010   000500    000959  ...         0.0        0.0       0
5762  20231010   001000    001459  ...         0.0        0.0       0
5763  20231010   001500    001959  ...         0.0        0.0       0
5764  20231010   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 00:25:00,799:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696868699, self.tradeDate='20231010', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27490.6, self.close=27510.4, self.high=27539.4, self.low=27486.5, self.vol=2197.305, self.amt=60466427.526, ukdf['pct'].iloc[-1]=0.000702 , ukdf['amount'].iloc[-1]=60466427.526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '24813.75305985238', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27512.09598718', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231009   120000    155959  1696838399  ...    723  0.080186 -1.217978    -1.0
724  20231009   160000    195959  1696852799  ...    724  0.067976 -1.229082    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '21294.81563486192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27455.95318864', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [10/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=891
self.closeSec=1696867199, self.tradeDate='20231009', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27456.0, self.close=27433.1, self.high=27567.2, self.low=27358.2, self.vol=60969.452, self.amt=1674700013.5914 
2023-10-10 00:00:01,554:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696867199, self.tradeDate='20231009', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27456.0, self.close=27433.1, self.high=27567.2, self.low=27358.2, self.vol=60969.452, self.amt=1674700013.5914 
2023-10-10 00:00:01,578:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231009   040000    075959  ...  22355.647  6.234754e+08  0.000750
722  20231009   080000    115959  ...  26462.524  7.379817e+08  0.000380
723  20231009   120000    155959  ...  18808.510  5.240199e+08 -0.003876
724  20231009   160000    195959  ...  93264.706  2.572383e+09 -0.012509
725  20231009   200000    235959  ...  60969.452  1.674700e+09 -0.000830

[5 rows x 11 columns]
2023-10-10 00:00:02,306:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231009   040000    075959  1696809599  ...    721  0.083383 -1.253474    -1.0
722  20231009   080000    115959  1696823999  ...    722  0.082445 -1.234409    -1.0
723  20231009   120000    155959  1696838399  ...    723  0.080186 -1.217978    -1.0
724  20231009   160000    195959  1696852799  ...    724  0.067976 -1.229082    -1.0
725  20231009   200000    235959  1696867199  ...    725  0.091458 -1.143627    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '22295.5058', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27433', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


