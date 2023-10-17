# 20231018 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45076
self.closeSec=1697559599, self.tradeDate='20231018', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28440.1, self.close=28490.0, self.high=28506.3, self.low=28437.3, self.vol=1225.244, self.amt=34899963.5721 
127.0.0.1 - - [18/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-10-18 00:20:08,554:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231017   235500    235959  ...         0.0        0.0       0
5760  20231018   000000    000459  ...         0.0        0.0       0
5761  20231018   000500    000959  ...         0.0        0.0       0
5762  20231018   001000    001459  ...         0.0        0.0       0
5763  20231018   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 00:20:08,573:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697559599, self.tradeDate='20231018', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28440.1, self.close=28490.0, self.high=28506.3, self.low=28437.3, self.vol=1225.244, self.amt=34899963.5721, ukdf['pct'].iloc[-1]=0.001744 , ukdf['amount'].iloc[-1]=34899963.5721, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-22530.70943578092', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28482.78808242', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45077
self.closeSec=1697559899, self.tradeDate='20231018', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28490.0, self.close=28516.1, self.high=28536.8, self.low=28477.7, self.vol=1058.137, self.amt=30172881.1766 
127.0.0.1 - - [18/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-18 00:25:03,179:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231018   000000    000459  ...         0.0        0.0       0
5761  20231018   000500    000959  ...         0.0        0.0       0
5762  20231018   001000    001459  ...         0.0        0.0       0
5763  20231018   001500    001959  ...         0.0        0.0       0
5764  20231018   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 00:25:03,180:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697559899, self.tradeDate='20231018', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28490.0, self.close=28516.1, self.high=28536.8, self.low=28477.7, self.vol=1058.137, self.amt=30172881.1766, ukdf['pct'].iloc[-1]=0.000916 , ukdf['amount'].iloc[-1]=30172881.1766, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-22967.91485830116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28514.18298566', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1697558699, self.tradeDate='20231018', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=28445.7, self.close=28430.7, self.high=28472.2, self.low=28426.5 

--ukdf-hist--: overDate='20231013' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45076 

self.closeSec=1697558999, self.tradeDate='20231018', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28433.8, self.close=28424.7, self.high=28439.0, self.low=28410.9 
127.0.0.1 - - [18/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45077 

self.closeSec=1697559299, self.tradeDate='20231018', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28424.6, self.close=28440.4, self.high=28447.5, self.low=28424.6 
127.0.0.1 - - [18/Oct/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45078 

self.closeSec=1697559599, self.tradeDate='20231018', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28440.1, self.close=28490.0, self.high=28506.3, self.low=28437.3 
127.0.0.1 - - [18/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45079 

self.closeSec=1697559899, self.tradeDate='20231018', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28490.0, self.close=28516.1, self.high=28536.8, self.low=28477.7 
127.0.0.1 - - [18/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-18 00:00:18,974:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231017    212959  28203.5  ...  51.250000  0.542596  0.654129
5802  20231017    215959  28249.6  ...  51.666667  0.546549  0.656960
5803  20231017    222959  28276.5  ...  52.083333  0.556778  0.651571
5804  20231017    225959  28369.9  ...  52.083333  0.565714  0.639362
5805  20231017    232959  28449.7  ...  52.083333  0.565075  0.618387

[5 rows x 33 columns]
0.5588235294117647
acc is : 0.5588235294117647
2023-10-18 00:00:19,053:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.493682  0.506318       1  ...  0.945701  -1.0    0.0  1.023647
540     1  0.496500  0.503500       1  ...  0.942708  -1.0    0.0  1.026887
541     0  0.523091  0.476909       1  ...  0.940050  -1.0    0.0  1.029782
542     0  0.527844  0.472156       0  ...  0.940195  -1.0    0.0  1.029623
543     0  0.516370  0.483630       1  ...  0.940185  -1.0    0.0  1.029634

[5 rows x 10 columns]
2023-10-18 00:00:19,067:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493578  0.506422       1  ...  0.912363  -1.0    0.0  1.028865
46     1  0.496935  0.503065       1  ...  0.942708  -1.0    0.0  1.032459
47     0  0.523053  0.476947       1  ...  0.940050  -1.0    0.0  1.033734
48     0  0.527932  0.472068       0  ...  0.940195  -1.0    0.0  1.033574
49     0  0.516370  0.483630       1  ...  0.940185  -1.0    0.0  1.029634

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '22.655', 'enterprice': '28244.6', 'countrevence': '0', 'unrealprofit': '-4632.3599221855', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28449.0740641', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22535 

self.closeSec=1697556599, self.tradeDate='20231017', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28513', self.close='28445.4'
127.0.0.1 - - [17/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22536 

self.closeSec=1697557199, self.tradeDate='20231017', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28445.5', self.close='28510.2'
127.0.0.1 - - [17/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22537 

self.closeSec=1697557799, self.tradeDate='20231017', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28523.3', self.close='28452.8'

--handleKline--: 127.0.0.1 - - [18/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22538 

self.closeSec=1697558399, self.tradeDate='20231017', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28453.7', self.close='28445.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22539 

self.closeSec=1697558999, self.tradeDate='20231018', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28445.7', self.close='28423.7'
127.0.0.1 - - [18/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22540 

self.closeSec=1697559599, self.tradeDate='20231018', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28424.6', self.close='28490.1'
127.0.0.1 - - [18/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22538 

self.closeSec=1697556599, self.tradeDate='20231017', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28513', self.close='28445.4'
127.0.0.1 - - [17/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22539 

self.closeSec=1697557199, self.tradeDate='20231017', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28445.5', self.close='28510.2'
127.0.0.1 - - [17/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22540 

self.closeSec=1697557799, self.tradeDate='20231017', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28523.3', self.close='28452.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22541 

self.closeSec=1697558399, self.tradeDate='20231017', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28453.7', self.close='28445.8'
127.0.0.1 - - [18/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22542 

self.closeSec=1697558999, self.tradeDate='20231018', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28445.7', self.close='28423.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22543 

self.closeSec=1697559599, self.tradeDate='20231018', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28424.6', self.close='28490.1'
127.0.0.1 - - [18/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22538 

self.closeSec=1697556599, self.tradeDate='20231017', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28513', self.close='28445.4'
127.0.0.1 - - [17/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22539 

self.closeSec=1697557199, self.tradeDate='20231017', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28445.5', self.close='28510.2'
127.0.0.1 - - [17/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22540 

self.closeSec=1697557799, self.tradeDate='20231017', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28523.3', self.close='28452.8'
127.0.0.1 - - [17/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22541 

self.closeSec=1697558399, self.tradeDate='20231017', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28453.7', self.close='28445.8'
127.0.0.1 - - [18/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22542 

self.closeSec=1697558999, self.tradeDate='20231018', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28445.7', self.close='28423.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22543 

self.closeSec=1697559599, self.tradeDate='20231018', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28424.6', self.close='28490.1'
127.0.0.1 - - [18/Oct/2023 00:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45076
self.closeSec=1697559599, self.tradeDate='20231018', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28440.1, self.close=28490.0, self.high=28506.3, self.low=28437.3, self.vol=1225.244, self.amt=34899963.5721 
127.0.0.1 - - [18/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-10-18 00:20:08,544:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231017   235500    235959  ...         0.0        0.0       0
5760  20231018   000000    000459  ...         0.0        0.0       0
5761  20231018   000500    000959  ...         0.0        0.0       0
5762  20231018   001000    001459  ...         0.0        0.0       0
5763  20231018   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 00:20:08,547:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697559599, self.tradeDate='20231018', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28440.1, self.close=28490.0, self.high=28506.3, self.low=28437.3, self.vol=1225.244, self.amt=34899963.5721, ukdf['pct'].iloc[-1]=0.001744 , ukdf['amount'].iloc[-1]=34899963.5721, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '60866.22816916122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28482.78808242', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45077
self.closeSec=1697559899, self.tradeDate='20231018', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28490.0, self.close=28516.1, self.high=28536.8, self.low=28477.7, self.vol=1058.137, self.amt=30172881.1766 
127.0.0.1 - - [18/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-18 00:25:03,176:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231018   000000    000459  ...         0.0        0.0       0
5761  20231018   000500    000959  ...         0.0        0.0       0
5762  20231018   001000    001459  ...         0.0        0.0       0
5763  20231018   001500    001959  ...         0.0        0.0       0
5764  20231018   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 00:25:03,178:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697559899, self.tradeDate='20231018', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28490.0, self.close=28516.1, self.high=28536.8, self.low=28477.7, self.vol=1058.137, self.amt=30172881.1766, ukdf['pct'].iloc[-1]=0.000916 , ukdf['amount'].iloc[-1]=30172881.1766, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '62032.26627039806', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28514.18298566', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231017   120000    155959  1697529599  ...    723  1.401377  1.162817     1.0
724  20231017   160000    195959  1697543999  ...    724  1.211667  0.847822     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '25013.226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28411.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=939
self.closeSec=1697558399, self.tradeDate='20231017', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28408.8, self.close=28445.8, self.high=28567.7, self.low=28117.0, self.vol=98853.837, self.amt=2801736514.11182 
127.0.0.1 - - [18/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-10-18 00:00:01,538:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697558399, self.tradeDate='20231017', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28408.8, self.close=28445.8, self.high=28567.7, self.low=28117.0, self.vol=98853.837, self.amt=2801736514.11182 
2023-10-18 00:00:01,550:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231017   040000    075959  ...  45745.440  1.300854e+09  0.001202
722  20231017   080000    115959  ...  36124.470  1.023821e+09 -0.007965
723  20231017   120000    155959  ...  53558.993  1.511652e+09  0.005266
724  20231017   160000    195959  ...  53721.483  1.528497e+09  0.000018
725  20231017   200000    235959  ...  98853.837  2.801737e+09  0.001306

[5 rows x 11 columns]
2023-10-18 00:00:02,226:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231017   040000    075959  1697500799  ...    721  1.974534  2.149736     1.0
722  20231017   080000    115959  1697515199  ...    722  1.538501  1.403763     1.0
723  20231017   120000    155959  1697529599  ...    723  1.401377  1.162817     1.0
724  20231017   160000    195959  1697543999  ...    724  1.211667  0.847822     1.0
725  20231017   200000    235959  1697558399  ...    725  1.170284  0.775830     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '26640.24358026738', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28449.04143223', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


