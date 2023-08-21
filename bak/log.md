# 20230822 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28660
self.closeSec=1692634799, self.tradeDate='20230822', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25937.6, self.close=26009.4, self.high=26021.6, self.low=25928.5, self.vol=1689.613, self.amt=43901088.1805 
127.0.0.1 - - [22/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-22 00:20:05,308:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230821   235500    235959  ...         0.0        0.0       0
5748  20230822   000000    000459  ...         0.0        0.0       0
5749  20230822   000500    000959  ...         0.0        0.0       0
5750  20230822   001000    001459  ...         0.0        0.0       0
5751  20230822   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 00:20:05,319:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692634799, self.tradeDate='20230822', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25937.6, self.close=26009.4, self.high=26021.6, self.low=25928.5, self.vol=1689.613, self.amt=43901088.1805, ukdf['pct'].iloc[-1]=0.002768 , ukdf['amount'].iloc[-1]=43901088.1805, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11979.90934454754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26004.64512821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28661
self.closeSec=1692635099, self.tradeDate='20230822', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26008.2, self.close=25986.4, self.high=26036.9, self.low=25970.0, self.vol=2191.281, self.amt=56985709.9152 
2023-08-22 00:25:00,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230822   000000    000459  ...         0.0        0.0       0
5749  20230822   000500    000959  ...         0.0        0.0       0
5750  20230822   001000    001459  ...         0.0        0.0       0
5751  20230822   001500    001959  ...         0.0        0.0       0
5752  20230822   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 00:25:00,777:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692635099, self.tradeDate='20230822', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26008.2, self.close=25986.4, self.high=26036.9, self.low=25970.0, self.vol=2191.281, self.amt=56985709.9152, ukdf['pct'].iloc[-1]=-0.000884 , ukdf['amount'].iloc[-1]=56985709.9152, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12235.3836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25986.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1692633899, self.tradeDate='20230822', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=25925.1, self.close=25949.9, self.high=25949.9, self.low=25921.1 

--ukdf-hist--: overDate='20230817' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28660 

self.closeSec=1692634199, self.tradeDate='20230822', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25950.0, self.close=25961.5, self.high=25961.5, self.low=25942.9 
127.0.0.1 - - [22/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28661 

self.closeSec=1692634499, self.tradeDate='20230822', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25961.4, self.close=25937.6, self.high=25961.7, self.low=25931.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28662 

self.closeSec=1692634799, self.tradeDate='20230822', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25937.6, self.close=26009.4, self.high=26021.6, self.low=25928.5 
127.0.0.1 - - [22/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28663 

self.closeSec=1692635099, self.tradeDate='20230822', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26008.2, self.close=25986.4, self.high=26036.9, self.low=25970.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-22 00:00:17,981:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230821    212959  25988.1  ...  45.416667  0.454276  0.635341
5802  20230821    215959  26002.0  ...  45.833333  0.488601  0.620029
5803  20230821    222959  26117.9  ...  45.416667  0.470290  0.616335
5804  20230821    225959  26045.6  ...  45.416667  0.484448  0.605277
5805  20230821    232959  26094.0  ...  45.416667  0.427798  0.623482

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-08-22 00:00:18,046:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.505247  0.494753       1  ...  1.090444  -1.0    0.0  0.883569
540     0  0.548662  0.451338       0  ...  1.093259  -1.0    0.0  0.881288
541     1  0.473521  0.526479       1  ...  1.091227  -1.0    0.0  0.882926
542     0  0.515900  0.484100       0  ...  1.101055  -1.0    0.0  0.874975
543     1  0.397278  0.602722       1  ...  1.098236  -1.0    0.0  0.877215

[5 rows x 10 columns]
2023-08-22 00:00:18,057:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505214  0.494786       1  ...  1.090444  -1.0    0.0  0.882780
46     0  0.548804  0.451196       0  ...  1.093259  -1.0    0.0  0.881975
47     1  0.473560  0.526440       1  ...  1.091227  -1.0    0.0  0.884437
48     0  0.515919  0.484081       0  ...  1.101055  -1.0    0.0  0.876472
49     1  0.397278  0.602722       1  ...  1.098236  -1.0    0.0  0.877215

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '4167.66990729444', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25926.50990476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14327 

self.closeSec=1692631799, self.tradeDate='20230821', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25974.9', self.close='25859'
127.0.0.1 - - [21/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14328 

self.closeSec=1692632399, self.tradeDate='20230821', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25852.9', self.close='25940'
127.0.0.1 - - [21/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14329 

self.closeSec=1692632999, self.tradeDate='20230821', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25942', self.close='25949'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14330 

self.closeSec=1692633599, self.tradeDate='20230821', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25949', self.close='25925.1'
127.0.0.1 - - [22/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14331 

self.closeSec=1692634199, self.tradeDate='20230822', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25925.1', self.close='25961.4'
127.0.0.1 - - [22/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14332 

self.closeSec=1692634799, self.tradeDate='20230822', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25961.4', self.close='26008.1'
127.0.0.1 - - [22/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14330 

self.closeSec=1692631799, self.tradeDate='20230821', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25974.9', self.close='25859'
127.0.0.1 - - [21/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14331 

self.closeSec=1692632399, self.tradeDate='20230821', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25852.9', self.close='25940'
127.0.0.1 - - [21/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14332 

self.closeSec=1692632999, self.tradeDate='20230821', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25942', self.close='25949'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14333 

self.closeSec=1692633599, self.tradeDate='20230821', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25949', self.close='25925.1'
127.0.0.1 - - [22/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14334 

self.closeSec=1692634199, self.tradeDate='20230822', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25925.1', self.close='25961.4'
127.0.0.1 - - [22/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14335 

self.closeSec=1692634799, self.tradeDate='20230822', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25961.4', self.close='26008.1'
127.0.0.1 - - [22/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [21/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14330 

self.closeSec=1692631799, self.tradeDate='20230821', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25974.9', self.close='25859'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14331 

self.closeSec=1692632399, self.tradeDate='20230821', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25852.9', self.close='25940'
127.0.0.1 - - [21/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14332 

self.closeSec=1692632999, self.tradeDate='20230821', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25942', self.close='25949'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14333 

self.closeSec=1692633599, self.tradeDate='20230821', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25949', self.close='25925.1'
127.0.0.1 - - [22/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14334 

self.closeSec=1692634199, self.tradeDate='20230822', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25925.1', self.close='25961.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14335 

self.closeSec=1692634799, self.tradeDate='20230822', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25961.4', self.close='26008.1'
127.0.0.1 - - [22/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28660
self.closeSec=1692634799, self.tradeDate='20230822', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25937.6, self.close=26009.4, self.high=26021.6, self.low=25928.5, self.vol=1689.613, self.amt=43901088.1805 
127.0.0.1 - - [22/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-22 00:20:05,297:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230821   235500    235959  ...         0.0        0.0       0
5748  20230822   000000    000459  ...         0.0        0.0       0
5749  20230822   000500    000959  ...         0.0        0.0       0
5750  20230822   001000    001459  ...         0.0        0.0       0
5751  20230822   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 00:20:05,301:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692634799, self.tradeDate='20230822', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25937.6, self.close=26009.4, self.high=26021.6, self.low=25928.5, self.vol=1689.613, self.amt=43901088.1805, ukdf['pct'].iloc[-1]=0.002768 , ukdf['amount'].iloc[-1]=43901088.1805, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31174.47929315239', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26004.64512821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28661
self.closeSec=1692635099, self.tradeDate='20230822', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26008.2, self.close=25986.4, self.high=26036.9, self.low=25970.0, self.vol=2191.281, self.amt=56985709.9152 
2023-08-22 00:25:00,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230822   000000    000459  ...         0.0        0.0       0
5749  20230822   000500    000959  ...         0.0        0.0       0
5750  20230822   001000    001459  ...         0.0        0.0       0
5751  20230822   001500    001959  ...         0.0        0.0       0
5752  20230822   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 00:25:00,789:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692635099, self.tradeDate='20230822', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26008.2, self.close=25986.4, self.high=26036.9, self.low=25970.0, self.vol=2191.281, self.amt=56985709.9152, ukdf['pct'].iloc[-1]=-0.000884 , ukdf['amount'].iloc[-1]=56985709.9152, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31855.8357', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25986.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230821   120000    155959  1692604799  ...    723  0.306959 -0.414992     NaN
724  20230821   160000    195959  1692619199  ...    724  0.217729 -0.616238    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '175330.7172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26020.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=597
self.closeSec=1692633599, self.tradeDate='20230821', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26020.8, self.close=25925.2, self.high=26193.6, self.low=25800.0, self.vol=78006.038, self.amt=2027997373.43094 
127.0.0.1 - - [22/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-22 00:00:01,533:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692633599, self.tradeDate='20230821', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26020.8, self.close=25925.2, self.high=26193.6, self.low=25800.0, self.vol=78006.038, self.amt=2027997373.43094 
2023-08-22 00:00:01,547:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230821   040000    075959  ...  28522.998  7.469668e+08  0.002060
722  20230821   080000    115959  ...  19223.035  5.018794e+08 -0.003790
723  20230821   120000    155959  ...  32357.559  8.432335e+08 -0.002481
724  20230821   160000    195959  ...  43891.556  1.140098e+09  0.000338
725  20230821   200000    235959  ...  78006.038  2.027997e+09 -0.003674

[5 rows x 11 columns]
2023-08-22 00:00:02,317:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230821   040000    075959  1692575999  ...    721  0.460951 -0.080190     NaN
722  20230821   080000    115959  1692590399  ...    722  0.384638 -0.242202     NaN
723  20230821   120000    155959  1692604799  ...    723  0.306959 -0.414992     NaN
724  20230821   160000    195959  1692619199  ...    724  0.217729 -0.616238    -1.0
725  20230821   200000    235959  1692633599  ...    725  0.088583 -0.907845    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '180180.53508773764', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25926.32353297', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


