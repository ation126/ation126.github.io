# 20231008 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42196
self.closeSec=1696695599, self.tradeDate='20231008', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27925.5, self.close=27938.7, self.high=27939.6, self.low=27924.5, self.vol=190.894, self.amt=5332631.6084 
127.0.0.1 - - [08/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-08 00:20:06,131:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231007   235500    235959  ...         0.0        0.0       0
5760  20231008   000000    000459  ...         0.0        0.0       0
5761  20231008   000500    000959  ...         0.0        0.0       0
5762  20231008   001000    001459  ...         0.0        0.0       0
5763  20231008   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 00:20:06,142:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696695599, self.tradeDate='20231008', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27925.5, self.close=27938.7, self.high=27939.6, self.low=27924.5, self.vol=190.894, self.amt=5332631.6084, ukdf['pct'].iloc[-1]=0.000469 , ukdf['amount'].iloc[-1]=5332631.6084, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14943.10558487472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27937.93644872', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42197
self.closeSec=1696695899, self.tradeDate='20231008', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27938.6, self.close=27935.1, self.high=27938.7, self.low=27928.8, self.vol=163.664, self.amt=4571827.3727 
2023-10-08 00:25:00,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231008   000000    000459  ...         0.0        0.0       0
5761  20231008   000500    000959  ...         0.0        0.0       0
5762  20231008   001000    001459  ...         0.0        0.0       0
5763  20231008   001500    001959  ...         0.0        0.0       0
5764  20231008   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 00:25:00,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696695899, self.tradeDate='20231008', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27938.6, self.close=27935.1, self.high=27938.7, self.low=27928.8, self.vol=163.664, self.amt=4571827.3727, ukdf['pct'].iloc[-1]=-0.000129 , ukdf['amount'].iloc[-1]=4571827.3727, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14907.34420343784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27935.36849084', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [08/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20231003' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [08/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42196 

self.closeSec=1696694999, self.tradeDate='20231008', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27918.4, self.close=27929.1, self.high=27929.1, self.low=27915.0 
127.0.0.1 - - [08/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42197 

self.closeSec=1696695299, self.tradeDate='20231008', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27929.0, self.close=27925.6, self.high=27937.3, self.low=27918.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42198 

self.closeSec=1696695599, self.tradeDate='20231008', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27925.5, self.close=27938.7, self.high=27939.6, self.low=27924.5 
127.0.0.1 - - [08/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42199 

self.closeSec=1696695899, self.tradeDate='20231008', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27938.6, self.close=27935.1, self.high=27938.7, self.low=27928.8 
127.0.0.1 - - [08/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-08 00:00:20,973:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231007    212959  27946.0  ...  52.083333  0.538284  0.524828
5802  20231007    215959  27935.5  ...  51.666667  0.535163  0.545740
5803  20231007    222959  27922.8  ...  51.666667  0.535003  0.565321
5804  20231007    225959  27922.9  ...  51.666667  0.538769  0.581888
5805  20231007    232959  27938.9  ...  51.666667  0.539667  0.596947

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-10-08 00:00:21,044:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.490334  0.509666       0  ...  0.979065   1.0    0.0  1.063497
540     1  0.487891  0.512109       0  ...  0.979044   1.0    0.0  1.063474
541     1  0.494402  0.505598       1  ...  0.979608   1.0    0.0  1.064087
542     1  0.498430  0.501570       1  ...  0.979741   1.0    0.0  1.064232
543     1  0.495956  0.504044       0  ...  0.979166   1.0    0.0  1.063608

[5 rows x 10 columns]
2023-10-08 00:00:21,055:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490349  0.509651       0  ...  0.979065   1.0    0.0  1.062599
46     1  0.487795  0.512205       0  ...  0.979044   1.0    0.0  1.062523
47     1  0.494412  0.505588       1  ...  0.979608   1.0    0.0  1.063658
48     1  0.498447  0.501553       1  ...  0.979741   1.0    0.0  1.063803
49     1  0.495956  0.504044       0  ...  0.979166   1.0    0.0  1.063608

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.669', 'enterprice': '27936.3', 'countrevence': '0', 'unrealprofit': '-191.7189', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27928.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21095 

self.closeSec=1696692599, self.tradeDate='20231007', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27951.9', self.close='27941.4'
127.0.0.1 - - [07/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [07/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21096 

self.closeSec=1696693199, self.tradeDate='20231007', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27941.4', self.close='27904.1'
127.0.0.1 - - [07/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21097 

self.closeSec=1696693799, self.tradeDate='20231007', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27903.4', self.close='27926.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21098 

self.closeSec=1696694399, self.tradeDate='20231007', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27927', self.close='27926.4'
127.0.0.1 - - [08/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21099 

self.closeSec=1696694999, self.tradeDate='20231008', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27926.5', self.close='27929.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21100 

self.closeSec=1696695599, self.tradeDate='20231008', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27929', self.close='27938.7'
127.0.0.1 - - [08/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21098 

self.closeSec=1696692599, self.tradeDate='20231007', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27951.9', self.close='27941.4'
127.0.0.1 - - [07/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21099 

self.closeSec=1696693199, self.tradeDate='20231007', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27941.4', self.close='27904.1'

--handleKline--:  127.0.0.1 - - [07/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21100 

self.closeSec=1696693799, self.tradeDate='20231007', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27903.4', self.close='27926.8'
127.0.0.1 - - [08/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21101 

self.closeSec=1696694399, self.tradeDate='20231007', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27927', self.close='27926.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21102 

self.closeSec=1696694999, self.tradeDate='20231008', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27926.5', self.close='27929.1'
127.0.0.1 - - [08/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21103 

self.closeSec=1696695599, self.tradeDate='20231008', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27929', self.close='27938.7'
127.0.0.1 - - [08/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [07/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21098 

self.closeSec=1696692599, self.tradeDate='20231007', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27951.9', self.close='27941.4'
127.0.0.1 - - [07/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21099 

self.closeSec=1696693199, self.tradeDate='20231007', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27941.4', self.close='27904.1'
127.0.0.1 - - [07/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21100 

self.closeSec=1696693799, self.tradeDate='20231007', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27903.4', self.close='27926.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21101 

self.closeSec=1696694399, self.tradeDate='20231007', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27927', self.close='27926.4'
127.0.0.1 - - [08/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21102 

self.closeSec=1696694999, self.tradeDate='20231008', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27926.5', self.close='27929.1'
127.0.0.1 - - [08/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21103 

self.closeSec=1696695599, self.tradeDate='20231008', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27929', self.close='27938.7'
127.0.0.1 - - [08/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42196
self.closeSec=1696695599, self.tradeDate='20231008', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27925.5, self.close=27938.7, self.high=27939.6, self.low=27924.5, self.vol=190.894, self.amt=5332631.6084 
127.0.0.1 - - [08/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-08 00:20:06,127:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231007   235500    235959  ...         0.0        0.0       0
5760  20231008   000000    000459  ...         0.0        0.0       0
5761  20231008   000500    000959  ...         0.0        0.0       0
5762  20231008   001000    001459  ...         0.0        0.0       0
5763  20231008   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 00:20:06,129:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696695599, self.tradeDate='20231008', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27925.5, self.close=27938.7, self.high=27939.6, self.low=27924.5, self.vol=190.894, self.amt=5332631.6084, ukdf['pct'].iloc[-1]=0.000469 , ukdf['amount'].iloc[-1]=5332631.6084, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '40629.89364190952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27937.93644872', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [08/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42197
self.closeSec=1696695899, self.tradeDate='20231008', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27938.6, self.close=27935.1, self.high=27938.7, self.low=27928.8, self.vol=163.664, self.amt=4571827.3727 
2023-10-08 00:25:00,805:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231008   000000    000459  ...         0.0        0.0       0
5761  20231008   000500    000959  ...         0.0        0.0       0
5762  20231008   001000    001459  ...         0.0        0.0       0
5763  20231008   001500    001959  ...         0.0        0.0       0
5764  20231008   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 00:25:00,805:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696695899, self.tradeDate='20231008', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27938.6, self.close=27935.1, self.high=27938.7, self.low=27928.8, self.vol=163.664, self.amt=4571827.3727, ukdf['pct'].iloc[-1]=-0.000129 , ukdf['amount'].iloc[-1]=4571827.3727, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '40534.51711828844', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27935.36849084', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231007   120000    155959  1696665599  ...    723  0.227771 -1.107926    -1.0
724  20231007   160000    195959  1696679999  ...    724  0.243351 -1.049194    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '757.36572638942', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27927.02803114', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=879
self.closeSec=1696694399, self.tradeDate='20231007', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27929.4, self.close=27926.4, self.high=27974.8, self.low=27882.6, self.vol=17899.597, self.amt=499867055.8282 
127.0.0.1 - - [08/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-10-08 00:00:01,548:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696694399, self.tradeDate='20231007', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27929.4, self.close=27926.4, self.high=27974.8, self.low=27882.6, self.vol=17899.597, self.amt=499867055.8282 
2023-10-08 00:00:01,575:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231007   040000    075959  ...  61484.735  1.724951e+09 -0.000716
722  20231007   080000    115959  ...  26860.834  7.491186e+08 -0.000910
723  20231007   120000    155959  ...  13365.886  3.727963e+08 -0.000455
724  20231007   160000    195959  ...  28790.238  8.048066e+08  0.001837
725  20231007   200000    235959  ...  17899.597  4.998671e+08 -0.000107

[5 rows x 11 columns]
2023-10-08 00:00:02,467:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231007   040000    075959  1696636799  ...    721  0.195185 -1.229155    -1.0
722  20231007   080000    115959  1696651199  ...    722  0.259306 -1.046460    -1.0
723  20231007   120000    155959  1696665599  ...    723  0.227771 -1.107926    -1.0
724  20231007   160000    195959  1696679999  ...    724  0.243351 -1.049194    -1.0
725  20231007   200000    235959  1696694399  ...    725  0.233707 -1.051917    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '766.3293018512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27926.8224304', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


