# 20230828 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30388
self.closeSec=1693153199, self.tradeDate='20230828', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26123.0, self.close=26115.3, self.high=26141.0, self.low=26115.3, self.vol=539.706, self.amt=14101996.074 
127.0.0.1 - - [28/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-28 00:20:04,752:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230827   235500    235959  ...         0.0        0.0       0
5748  20230828   000000    000459  ...         0.0        0.0       0
5749  20230828   000500    000959  ...         0.0        0.0       0
5750  20230828   001000    001459  ...         0.0        0.0       0
5751  20230828   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 00:20:04,755:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693153199, self.tradeDate='20230828', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26123.0, self.close=26115.3, self.high=26141.0, self.low=26115.3, self.vol=539.706, self.amt=14101996.074, ukdf['pct'].iloc[-1]=-0.000299 , ukdf['amount'].iloc[-1]=14101996.074, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10412.41574571924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26117.20391026', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30389
self.closeSec=1693153499, self.tradeDate='20230828', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26115.3, self.close=26125.0, self.high=26129.4, self.low=26111.9, self.vol=201.087, self.amt=5252170.8981 
2023-08-28 00:25:00,861:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230828   000000    000459  ...         0.0        0.0       0
5749  20230828   000500    000959  ...         0.0        0.0       0
5750  20230828   001000    001459  ...         0.0        0.0       0
5751  20230828   001500    001959  ...         0.0        0.0       0
5752  20230828   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 00:25:00,862:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693153499, self.tradeDate='20230828', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26115.3, self.close=26125.0, self.high=26129.4, self.low=26111.9, self.vol=201.087, self.amt=5252170.8981, ukdf['pct'].iloc[-1]=0.000371 , ukdf['amount'].iloc[-1]=5252170.8981, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10285.41269428728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26126.32376172', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1693152299, self.tradeDate='20230828', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26110.9, self.close=26116.7, self.high=26119.0, self.low=26108.1 

--ukdf-hist--: overDate='20230823' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [28/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30388 

self.closeSec=1693152599, self.tradeDate='20230828', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26116.7, self.close=26127.0, self.high=26130.0, self.low=26116.6 
127.0.0.1 - - [28/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30389 

self.closeSec=1693152899, self.tradeDate='20230828', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26127.0, self.close=26123.1, self.high=26127.1, self.low=26111.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30390 

self.closeSec=1693153199, self.tradeDate='20230828', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26123.0, self.close=26115.3, self.high=26141.0, self.low=26115.3 
127.0.0.1 - - [28/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30391 

self.closeSec=1693153499, self.tradeDate='20230828', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26115.3, self.close=26125.0, self.high=26129.4, self.low=26111.9 
127.0.0.1 - - [28/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-28 00:00:17,544:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230827    212959  26059.2  ...  50.416667  0.516069  0.345050
5802  20230827    215959  26073.9  ...  50.416667  0.511865  0.332595
5803  20230827    222959  26066.9  ...  50.416667  0.542598  0.323692
5804  20230827    225959  26125.1  ...  50.833333  0.547097  0.314223
5805  20230827    232959  26134.0  ...  50.833333  0.553521  0.301439

[5 rows x 33 columns]
0.5386029411764706
acc is : 0.5386029411764706
2023-08-28 00:00:17,625:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.496520  0.503480       0  ...  1.062885  -1.0    0.0  0.893415
540     1  0.489771  0.510229       1  ...  1.060512  -1.0    0.0  0.895409
541     0  0.516518  0.483482       1  ...  1.060147  -1.0    0.0  0.895718
542     0  0.502395  0.497605       1  ...  1.059623  -1.0    0.0  0.896160
543     0  0.505027  0.494973       0  ...  1.061086  -1.0    0.0  0.894923

[5 rows x 10 columns]
2023-08-28 00:00:17,639:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496522  0.503478       0  ...  1.062885  -1.0    0.0  0.894844
46     1  0.489760  0.510240       1  ...  1.060512  -1.0    0.0  0.896150
47     0  0.516504  0.483496       1  ...  1.060147  -1.0    0.0  0.895589
48     0  0.502490  0.497510       1  ...  1.059623  -1.0    0.0  0.896031
49     0  0.505027  0.494973       0  ...  1.061086  -1.0    0.0  0.894923

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '8116.4125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26114.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15191 

self.closeSec=1693150199, self.tradeDate='20230827', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26147.7', self.close='26146.9'
127.0.0.1 - - [27/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15192 

self.closeSec=1693150799, self.tradeDate='20230827', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26146.8', self.close='26139.5'
127.0.0.1 - - [27/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15193 

self.closeSec=1693151399, self.tradeDate='20230827', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26139.5', self.close='26125.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15194 

self.closeSec=1693151999, self.tradeDate='20230827', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26125.5', self.close='26110.8'
127.0.0.1 - - [28/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15195 

self.closeSec=1693152599, self.tradeDate='20230828', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26110.9', self.close='26127'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15196 

self.closeSec=1693153199, self.tradeDate='20230828', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26127', self.close='26115.3'
127.0.0.1 - - [28/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15194 

self.closeSec=1693150199, self.tradeDate='20230827', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26147.7', self.close='26146.9'
127.0.0.1 - - [27/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15195 

self.closeSec=1693150799, self.tradeDate='20230827', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26146.8', self.close='26139.5'
127.0.0.1 - - [27/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15196 

self.closeSec=1693151399, self.tradeDate='20230827', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26139.5', self.close='26125.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15197 

self.closeSec=1693151999, self.tradeDate='20230827', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26125.5', self.close='26110.8'
127.0.0.1 - - [28/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15198 

self.closeSec=1693152599, self.tradeDate='20230828', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26110.9', self.close='26127'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15199 

self.closeSec=1693153199, self.tradeDate='20230828', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26127', self.close='26115.3'
127.0.0.1 - - [28/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15194 

self.closeSec=1693150199, self.tradeDate='20230827', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26147.7', self.close='26146.9'
127.0.0.1 - - [27/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15195 

self.closeSec=1693150799, self.tradeDate='20230827', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26146.8', self.close='26139.5'
127.0.0.1 - - [27/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15196 

self.closeSec=1693151399, self.tradeDate='20230827', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26139.5', self.close='26125.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15197 

self.closeSec=1693151999, self.tradeDate='20230827', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26125.5', self.close='26110.8'
127.0.0.1 - - [28/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15198 

self.closeSec=1693152599, self.tradeDate='20230828', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26110.9', self.close='26127'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15199 

self.closeSec=1693153199, self.tradeDate='20230828', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26127', self.close='26115.3'
127.0.0.1 - - [28/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30388
self.closeSec=1693153199, self.tradeDate='20230828', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26123.0, self.close=26115.3, self.high=26141.0, self.low=26115.3, self.vol=539.706, self.amt=14101996.074 
127.0.0.1 - - [28/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-28 00:20:04,753:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230827   235500    235959  ...         0.0        0.0       0
5748  20230828   000000    000459  ...         0.0        0.0       0
5749  20230828   000500    000959  ...         0.0        0.0       0
5750  20230828   001000    001459  ...         0.0        0.0       0
5751  20230828   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 00:20:04,754:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693153199, self.tradeDate='20230828', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26123.0, self.close=26115.3, self.high=26141.0, self.low=26115.3, self.vol=539.706, self.amt=14101996.074, ukdf['pct'].iloc[-1]=-0.000299 , ukdf['amount'].iloc[-1]=14101996.074, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26993.93356903334', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26117.20391026', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [28/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30389
self.closeSec=1693153499, self.tradeDate='20230828', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26115.3, self.close=26125.0, self.high=26129.4, self.low=26111.9, self.vol=201.087, self.amt=5252170.8981 
2023-08-28 00:25:00,860:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230828   000000    000459  ...         0.0        0.0       0
5749  20230828   000500    000959  ...         0.0        0.0       0
5750  20230828   001000    001459  ...         0.0        0.0       0
5751  20230828   001500    001959  ...         0.0        0.0       0
5752  20230828   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 00:25:00,860:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693153499, self.tradeDate='20230828', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26115.3, self.close=26125.0, self.high=26129.4, self.low=26111.9, self.vol=201.087, self.amt=5252170.8981, ukdf['pct'].iloc[-1]=0.000371 , ukdf['amount'].iloc[-1]=5252170.8981, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26655.21316595748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26126.32376172', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230827   120000    155959  1693123199  ...    723  0.341607  0.162127     NaN
724  20230827   160000    195959  1693137599  ...    724  0.331191  0.162233     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '173871.298', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26049.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [28/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=633
self.closeSec=1693151999, self.tradeDate='20230827', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26049.0, self.close=26110.8, self.high=26173.6, self.low=26040.2, self.vol=21791.01, self.amt=569119482.33437 
2023-08-28 00:00:01,558:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693151999, self.tradeDate='20230827', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26049.0, self.close=26110.8, self.high=26173.6, self.low=26040.2, self.vol=21791.01, self.amt=569119482.33437 
2023-08-28 00:00:01,579:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230827   040000    075959  ...   7354.576  1.913056e+08 -0.000722
722  20230827   080000    115959  ...   9486.116  2.465406e+08  0.000208
723  20230827   120000    155959  ...   7936.958  2.065765e+08  0.000727
724  20230827   160000    195959  ...  13550.247  3.530646e+08  0.000788
725  20230827   200000    235959  ...  21791.010  5.691195e+08  0.002372

[5 rows x 11 columns]
2023-08-28 00:00:02,322:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230827   040000    075959  1693094399  ...    721  0.130818 -0.490147     NaN
722  20230827   080000    115959  1693108799  ...    722  0.354509  0.169445     NaN
723  20230827   120000    155959  1693123199  ...    723  0.341607  0.162127     NaN
724  20230827   160000    195959  1693137599  ...    724  0.331191  0.162233     NaN
725  20230827   200000    235959  1693151999  ...    725  0.315218  0.156514     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '170695.5196', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26110.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


