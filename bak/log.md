# 20230910 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34132
self.closeSec=1694276399, self.tradeDate='20230910', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25891.8, self.close=25891.6, self.high=25893.4, self.low=25889.7, self.vol=156.057, self.amt=4040547.2648 
127.0.0.1 - - [10/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-10 00:20:05,798:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230909   235500    235959  ...         0.0        0.0       0
5760  20230910   000000    000459  ...         0.0        0.0       0
5761  20230910   000500    000959  ...         0.0        0.0       0
5762  20230910   001000    001459  ...         0.0        0.0       0
5763  20230910   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 00:20:05,803:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694276399, self.tradeDate='20230910', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25891.8, self.close=25891.6, self.high=25893.4, self.low=25889.7, self.vol=156.057, self.amt=4040547.2648, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=4040547.2648, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13554.1758', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25891.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34133
self.closeSec=1694276699, self.tradeDate='20230910', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25891.7, self.close=25901.0, self.high=25903.8, self.low=25890.1, self.vol=444.788, self.amt=11518348.4751 
127.0.0.1 - - [10/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-10 00:25:00,798:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230910   000000    000459  ...         0.0        0.0       0
5761  20230910   000500    000959  ...         0.0        0.0       0
5762  20230910   001000    001459  ...         0.0        0.0       0
5763  20230910   001500    001959  ...         0.0        0.0       0
5764  20230910   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 00:25:00,798:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694276699, self.tradeDate='20230910', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25891.7, self.close=25901.0, self.high=25903.8, self.low=25890.1, self.vol=444.788, self.amt=11518348.4751, ukdf['pct'].iloc[-1]=0.000363 , ukdf['amount'].iloc[-1]=11518348.4751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13410.78373841514', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25901.89671561', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [10/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230905' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34132 

self.closeSec=1694275799, self.tradeDate='20230910', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25877.9, self.close=25870.0, self.high=25879.1, self.low=25870.0 
127.0.0.1 - - [10/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34133 

self.closeSec=1694276099, self.tradeDate='20230910', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25870.0, self.close=25891.7, self.high=25897.0, self.low=25870.0 
127.0.0.1 - - [10/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34134 

self.closeSec=1694276399, self.tradeDate='20230910', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25891.8, self.close=25891.6, self.high=25893.4, self.low=25889.7 
127.0.0.1 - - [10/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34135 

self.closeSec=1694276699, self.tradeDate='20230910', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25891.7, self.close=25901.0, self.high=25903.8, self.low=25890.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-10 00:00:17,509:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230909    212959  25840.1  ...  52.083333  0.479798  0.453840
5802  20230909    215959  25837.5  ...  52.083333  0.470327  0.466102
5803  20230909    222959  25812.6  ...  52.500000  0.476348  0.472117
5804  20230909    225959  25826.8  ...  52.916667  0.479090  0.479210
5805  20230909    232959  25833.3  ...  53.333333  0.491530  0.475794

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-09-10 00:00:17,574:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.480452  0.519548       0  ...  1.065787  -1.0    0.0  0.993102
540     1  0.473938  0.526062       1  ...  1.065204  -1.0    0.0  0.993644
541     1  0.486326  0.513674       1  ...  1.064940  -1.0    0.0  0.993890
542     1  0.486206  0.513794       1  ...  1.063733  -1.0    0.0  0.995018
543     1  0.497026  0.502974       1  ...  1.062935  -1.0    0.0  0.995764

[5 rows x 10 columns]
2023-09-10 00:00:17,586:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.480211  0.519789       0  ...  1.065787  -1.0    0.0  0.991823
46     1  0.474006  0.525994       1  ...  1.065204  -1.0    0.0  0.993365
47     1  0.486009  0.513991       1  ...  1.064940  -1.0    0.0  0.992745
48     1  0.485926  0.514074       1  ...  1.063733  -1.0    0.0  0.993871
49     1  0.497026  0.502974       1  ...  1.062935  -1.0    0.0  0.995764

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '-3136.3048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25882.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17063 

self.closeSec=1694273399, self.tradeDate='20230909', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25885.8', self.close='25862.5'
127.0.0.1 - - [09/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17064 

self.closeSec=1694273999, self.tradeDate='20230909', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25862.5', self.close='25882.9'
127.0.0.1 - - [09/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17065 

self.closeSec=1694274599, self.tradeDate='20230909', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25883', self.close='25886.9'
127.0.0.1 - - [10/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17066 

self.closeSec=1694275199, self.tradeDate='20230909', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25886.9', self.close='25881.9'
127.0.0.1 - - [10/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17067 

self.closeSec=1694275799, self.tradeDate='20230910', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25881.9', self.close='25870.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17068 

self.closeSec=1694276399, self.tradeDate='20230910', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25870', self.close='25891.6'
127.0.0.1 - - [10/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17066 

self.closeSec=1694273399, self.tradeDate='20230909', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25885.8', self.close='25862.5'
127.0.0.1 - - [09/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17067 

self.closeSec=1694273999, self.tradeDate='20230909', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25862.5', self.close='25882.9'
127.0.0.1 - - [09/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17068 

self.closeSec=1694274599, self.tradeDate='20230909', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25883', self.close='25886.9'
127.0.0.1 - - [10/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17069 

self.closeSec=1694275199, self.tradeDate='20230909', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25886.9', self.close='25881.9'
127.0.0.1 - - [10/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17070 

self.closeSec=1694275799, self.tradeDate='20230910', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25881.9', self.close='25870.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17071 

self.closeSec=1694276399, self.tradeDate='20230910', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25870', self.close='25891.6'
127.0.0.1 - - [10/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [09/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17066 

self.closeSec=1694273399, self.tradeDate='20230909', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25885.8', self.close='25862.5'
127.0.0.1 - - [09/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17067 

self.closeSec=1694273999, self.tradeDate='20230909', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25862.5', self.close='25882.9'

--handleKline--: 127.0.0.1 - - [09/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17068 

self.closeSec=1694274599, self.tradeDate='20230909', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25883', self.close='25886.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17069 

self.closeSec=1694275199, self.tradeDate='20230909', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25886.9', self.close='25881.9'
127.0.0.1 - - [10/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17070 

self.closeSec=1694275799, self.tradeDate='20230910', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25881.9', self.close='25870.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17071 

self.closeSec=1694276399, self.tradeDate='20230910', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25870', self.close='25891.6'
127.0.0.1 - - [10/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34132
self.closeSec=1694276399, self.tradeDate='20230910', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25891.8, self.close=25891.6, self.high=25893.4, self.low=25889.7, self.vol=156.057, self.amt=4040547.2648 
127.0.0.1 - - [10/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-10 00:20:05,797:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230909   235500    235959  ...         0.0        0.0       0
5760  20230910   000000    000459  ...         0.0        0.0       0
5761  20230910   000500    000959  ...         0.0        0.0       0
5762  20230910   001000    001459  ...         0.0        0.0       0
5763  20230910   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 00:20:05,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694276399, self.tradeDate='20230910', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25891.8, self.close=25891.6, self.high=25893.4, self.low=25889.7, self.vol=156.057, self.amt=4040547.2648, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=4040547.2648, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35373.0884', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25891.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [10/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34133
self.closeSec=1694276699, self.tradeDate='20230910', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25891.7, self.close=25901.0, self.high=25903.8, self.low=25890.1, self.vol=444.788, self.amt=11518348.4751 
2023-09-10 00:25:00,779:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230910   000000    000459  ...         0.0        0.0       0
5761  20230910   000500    000959  ...         0.0        0.0       0
5762  20230910   001000    001459  ...         0.0        0.0       0
5763  20230910   001500    001959  ...         0.0        0.0       0
5764  20230910   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 00:25:00,779:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694276699, self.tradeDate='20230910', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25891.7, self.close=25901.0, self.high=25903.8, self.low=25890.1, self.vol=444.788, self.amt=11518348.4751, ukdf['pct'].iloc[-1]=0.000363 , ukdf['amount'].iloc[-1]=11518348.4751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-34990.65808552899', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25901.89671561', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230909   120000    155959  1694246399  ...    723  0.172586 -0.639120    -1.0
724  20230909   160000    195959  1694260799  ...    724  0.151505 -0.696459    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '2121.2667', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25855.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [10/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=711
self.closeSec=1694275199, self.tradeDate='20230909', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25850.7, self.close=25881.9, self.high=25921.5, self.low=25781.5, self.vol=19660.804, self.amt=508278817.7537 
2023-09-10 00:00:01,574:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694275199, self.tradeDate='20230909', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25850.7, self.close=25881.9, self.high=25921.5, self.low=25781.5, self.vol=19660.804, self.amt=508278817.7537 
2023-09-10 00:00:01,592:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230909   040000    075959  ...  14213.770  3.678833e+08  0.000626
722  20230909   080000    115959  ...  10539.395  2.725723e+08 -0.001297
723  20230909   120000    155959  ...  10439.267  2.699424e+08  0.000178
724  20230909   160000    195959  ...  10348.675  2.676785e+08 -0.000777
725  20230909   200000    235959  ...  19660.804  5.082788e+08  0.001203

[5 rows x 11 columns]
2023-09-10 00:00:02,262:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230909   040000    075959  1694217599  ...    721  0.196249 -0.573734     NaN
722  20230909   080000    115959  1694231999  ...    722  0.183813 -0.608528    -1.0
723  20230909   120000    155959  1694246399  ...    723  0.172586 -0.639120    -1.0
724  20230909   160000    195959  1694260799  ...    724  0.151505 -0.696459    -1.0
725  20230909   200000    235959  1694275199  ...    725  0.141142 -0.724742    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '587.10631626279', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25882.03177473', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


