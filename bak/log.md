# 20230908 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33556
self.closeSec=1694103599, self.tradeDate='20230908', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25793.9, self.close=25782.7, self.high=25797.9, self.low=25778.7, self.vol=310.298, self.amt=8001460.6072 
127.0.0.1 - - [08/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-08 00:20:05,610:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230907   235500    235959  ...         0.0        0.0       0
5760  20230908   000000    000459  ...         0.0        0.0       0
5761  20230908   000500    000959  ...         0.0        0.0       0
5762  20230908   001000    001459  ...         0.0        0.0       0
5763  20230908   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 00:20:05,618:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694103599, self.tradeDate='20230908', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25793.9, self.close=25782.7, self.high=25797.9, self.low=25778.7, self.vol=310.298, self.amt=8001460.6072, ukdf['pct'].iloc[-1]=-0.00043 , ukdf['amount'].iloc[-1]=8001460.6072, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15068.60784465564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25782.85146886', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33557
self.closeSec=1694103899, self.tradeDate='20230908', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25782.7, self.close=25799.0, self.high=25799.0, self.low=25775.8, self.vol=369.362, self.amt=9524385.5771 
2023-09-08 00:25:00,793:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230908   000000    000459  ...         0.0        0.0       0
5761  20230908   000500    000959  ...         0.0        0.0       0
5762  20230908   001000    001459  ...         0.0        0.0       0
5763  20230908   001500    001959  ...         0.0        0.0       0
5764  20230908   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 00:25:00,793:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694103899, self.tradeDate='20230908', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25782.7, self.close=25799.0, self.high=25799.0, self.low=25775.8, self.vol=369.362, self.amt=9524385.5771, ukdf['pct'].iloc[-1]=0.000632 , ukdf['amount'].iloc[-1]=9524385.5771, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14843.7234', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25799', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [08/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230903' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33556 

self.closeSec=1694102999, self.tradeDate='20230908', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25778.3, self.close=25778.1, self.high=25780.0, self.low=25760.0 
127.0.0.1 - - [08/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33557 

self.closeSec=1694103299, self.tradeDate='20230908', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25778.2, self.close=25793.8, self.high=25797.5, self.low=25769.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33558 

self.closeSec=1694103599, self.tradeDate='20230908', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25793.9, self.close=25782.7, self.high=25797.9, self.low=25778.7 
127.0.0.1 - - [08/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33559 

self.closeSec=1694103899, self.tradeDate='20230908', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25782.7, self.close=25799.0, self.high=25799.0, self.low=25775.8 
127.0.0.1 - - [08/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-08 00:00:19,653:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230907    212959  25649.1  ...  49.166667  0.474763  0.478531
5802  20230907    215959  25671.1  ...  48.750000  0.461850  0.502782
5803  20230907    222959  25633.2  ...  49.166667  0.472577  0.515000
5804  20230907    225959  25661.0  ...  49.166667  0.508319  0.500821
5805  20230907    232959  25759.9  ...  48.750000  0.497614  0.498207

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-09-08 00:00:19,740:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.487886  0.512114       0  ...  0.992319   1.0    0.0  0.984817
540     1  0.473848  0.526152       1  ...  0.993392   1.0    0.0  0.985881
541     1  0.494123  0.505877       1  ...  0.997224   1.0    0.0  0.989684
542     0  0.520720  0.479280       0  ...  0.996032   1.0    0.0  0.988501
543     1  0.491202  0.508798       1  ...  0.997483   1.0    0.0  0.989942

[5 rows x 10 columns]
2023-09-08 00:00:19,753:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487557  0.512443       0  ...  0.992319   1.0    0.0  0.984968
46     1  0.473218  0.526782       1  ...  0.993392   1.0    0.0  0.985559
47     1  0.493832  0.506168       1  ...  0.997224   1.0    0.0  0.989395
48     0  0.520448  0.479552       0  ...  0.996032   1.0    0.0  0.988213
49     1  0.491202  0.508798       1  ...  0.997483   1.0    0.0  0.989942

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.331', 'enterprice': '25653.5', 'countrevence': '0', 'unrealprofit': '3184.4044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25765.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16775 

self.closeSec=1694100599, self.tradeDate='20230907', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25780.3', self.close='25729.2'
127.0.0.1 - - [07/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16776 

self.closeSec=1694101199, self.tradeDate='20230907', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25731.5', self.close='25764'
127.0.0.1 - - [07/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16777 

self.closeSec=1694101799, self.tradeDate='20230907', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25763.9', self.close='25755.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16778 

self.closeSec=1694102399, self.tradeDate='20230907', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25755.2', self.close='25766.7'
127.0.0.1 - - [08/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16779 

self.closeSec=1694102999, self.tradeDate='20230908', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25766.7', self.close='25778.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16780 

self.closeSec=1694103599, self.tradeDate='20230908', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25778.2', self.close='25782.7'
127.0.0.1 - - [08/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16778 

self.closeSec=1694100599, self.tradeDate='20230907', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25780.3', self.close='25729.2'
127.0.0.1 - - [07/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16779 

self.closeSec=1694101199, self.tradeDate='20230907', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25731.5', self.close='25764'
127.0.0.1 - - [07/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16780 

self.closeSec=1694101799, self.tradeDate='20230907', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25763.9', self.close='25755.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16781 

self.closeSec=1694102399, self.tradeDate='20230907', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25755.2', self.close='25766.7'
127.0.0.1 - - [08/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16782 

self.closeSec=1694102999, self.tradeDate='20230908', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25766.7', self.close='25778.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16783 

self.closeSec=1694103599, self.tradeDate='20230908', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25778.2', self.close='25782.7'
127.0.0.1 - - [08/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [07/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16778 

self.closeSec=1694100599, self.tradeDate='20230907', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25780.3', self.close='25729.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16779 

self.closeSec=1694101199, self.tradeDate='20230907', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25731.5', self.close='25764'
127.0.0.1 - - [07/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16780 

self.closeSec=1694101799, self.tradeDate='20230907', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25763.9', self.close='25755.1'
127.0.0.1 - - [08/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16781 

self.closeSec=1694102399, self.tradeDate='20230907', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25755.2', self.close='25766.7'
127.0.0.1 - - [08/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16782 

self.closeSec=1694102999, self.tradeDate='20230908', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25766.7', self.close='25778.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16783 

self.closeSec=1694103599, self.tradeDate='20230908', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25778.2', self.close='25782.7'
127.0.0.1 - - [08/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33556
self.closeSec=1694103599, self.tradeDate='20230908', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25793.9, self.close=25782.7, self.high=25797.9, self.low=25778.7, self.vol=310.298, self.amt=8001460.6072 
127.0.0.1 - - [08/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-08 00:20:05,609:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230907   235500    235959  ...         0.0        0.0       0
5760  20230908   000000    000459  ...         0.0        0.0       0
5761  20230908   000500    000959  ...         0.0        0.0       0
5762  20230908   001000    001459  ...         0.0        0.0       0
5763  20230908   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 00:20:05,612:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694103599, self.tradeDate='20230908', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25793.9, self.close=25782.7, self.high=25797.9, self.low=25778.7, self.vol=310.298, self.amt=8001460.6072, ukdf['pct'].iloc[-1]=-0.00043 , ukdf['amount'].iloc[-1]=8001460.6072, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-39412.11759507074', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25782.85146886', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [08/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33557
self.closeSec=1694103899, self.tradeDate='20230908', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25782.7, self.close=25799.0, self.high=25799.0, self.low=25775.8, self.vol=369.362, self.amt=9524385.5771 
2023-09-08 00:25:00,794:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230908   000000    000459  ...         0.0        0.0       0
5761  20230908   000500    000959  ...         0.0        0.0       0
5762  20230908   001000    001459  ...         0.0        0.0       0
5763  20230908   001500    001959  ...         0.0        0.0       0
5764  20230908   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 00:25:00,795:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694103899, self.tradeDate='20230908', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25782.7, self.close=25799.0, self.high=25799.0, self.low=25775.8, self.vol=369.362, self.amt=9524385.5771, ukdf['pct'].iloc[-1]=0.000632 , ukdf['amount'].iloc[-1]=9524385.5771, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38812.345', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25799', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230907   120000    155959  1694073599  ...    723  0.024359 -1.043592    -1.0
724  20230907   160000    195959  1694087999  ...    724  0.025352 -1.041454    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '11071.50012537615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25698.66444505', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=699
self.closeSec=1694102399, self.tradeDate='20230907', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25695.5, self.close=25766.7, self.high=25824.7, self.low=25602.3, self.vol=47604.669, self.amt=1223881602.3742 
127.0.0.1 - - [08/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-08 00:00:01,634:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694102399, self.tradeDate='20230907', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25695.5, self.close=25766.7, self.high=25824.7, self.low=25602.3, self.vol=47604.669, self.amt=1223881602.3742 
2023-09-08 00:00:01,647:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230907   040000    075959  ...  19974.218  5.138199e+08  0.002648
722  20230907   080000    115959  ...  14048.498  3.619145e+08  0.003002
723  20230907   120000    155959  ...  15151.927  3.906374e+08 -0.002858
724  20230907   160000    195959  ...  14981.411  3.853597e+08 -0.002151
725  20230907   200000    235959  ...  47604.669  1.223882e+09  0.002771

[5 rows x 11 columns]
2023-09-08 00:00:02,364:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230907   040000    075959  1694044799  ...    721  0.022021 -1.049607    -1.0
722  20230907   080000    115959  1694059199  ...    722  0.023655 -1.045281    -1.0
723  20230907   120000    155959  1694073599  ...    723  0.024359 -1.043592    -1.0
724  20230907   160000    195959  1694087999  ...    724  0.025352 -1.041454    -1.0
725  20230907   200000    235959  1694102399  ...    725  0.028042 -1.034925    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '7107.33567207312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25767.99589744', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


