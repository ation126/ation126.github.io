# 20231016 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44500
self.closeSec=1697386799, self.tradeDate='20231016', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26893.9, self.close=26885.7, self.high=26893.9, self.low=26883.1, self.vol=203.543, self.amt=5473021.3114 
127.0.0.1 - - [16/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-16 00:20:13,828:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231015   235500    235959  ...         0.0        0.0       0
5760  20231016   000000    000459  ...         0.0        0.0       0
5761  20231016   000500    000959  ...         0.0        0.0       0
5762  20231016   001000    001459  ...         0.0        0.0       0
5763  20231016   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 00:20:13,847:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697386799, self.tradeDate='20231016', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26893.9, self.close=26885.7, self.high=26893.9, self.low=26883.1, self.vol=203.543, self.amt=5473021.3114, ukdf['pct'].iloc[-1]=-0.000309 , ukdf['amount'].iloc[-1]=5473021.3114, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-316.1202', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26887.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44501
self.closeSec=1697387099, self.tradeDate='20231016', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26885.6, self.close=26881.6, self.high=26887.7, self.low=26880.0, self.vol=198.935, self.amt=5347832.4304 
127.0.0.1 - - [16/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-16 00:25:03,329:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231016   000000    000459  ...         0.0        0.0       0
5761  20231016   000500    000959  ...         0.0        0.0       0
5762  20231016   001000    001459  ...         0.0        0.0       0
5763  20231016   001500    001959  ...         0.0        0.0       0
5764  20231016   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 00:25:03,335:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697387099, self.tradeDate='20231016', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26885.6, self.close=26881.6, self.high=26887.7, self.low=26880.0, self.vol=198.935, self.amt=5347832.4304, ukdf['pct'].iloc[-1]=-0.000152 , ukdf['amount'].iloc[-1]=5347832.4304, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-233.9568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26881.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1697385899, self.tradeDate='20231016', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26885.7, self.close=26900.5, self.high=26905.7, self.low=26885.1 

--ukdf-hist--: overDate='20231011' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44500 

self.closeSec=1697386199, self.tradeDate='20231016', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26900.5, self.close=26883.6, self.high=26900.6, self.low=26881.0 
127.0.0.1 - - [16/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44501 

self.closeSec=1697386499, self.tradeDate='20231016', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26883.6, self.close=26894.0, self.high=26898.8, self.low=26883.6 
127.0.0.1 - - [16/Oct/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44502 

self.closeSec=1697386799, self.tradeDate='20231016', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26893.9, self.close=26885.7, self.high=26893.9, self.low=26883.1 
127.0.0.1 - - [16/Oct/2023 00:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44503 

self.closeSec=1697387099, self.tradeDate='20231016', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26885.6, self.close=26881.6, self.high=26887.7, self.low=26880.0 
127.0.0.1 - - [16/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-16 00:00:17,696:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231015    212959  26824.3  ...  49.583333  0.527668  0.460570
5802  20231015    215959  26915.0  ...  49.583333  0.493891  0.468913
5803  20231015    222959  26849.7  ...  49.583333  0.514406  0.461449
5804  20231015    225959  26892.0  ...  49.583333  0.499651  0.465371
5805  20231015    232959  26861.8  ...  50.000000  0.510375  0.460883

[5 rows x 33 columns]
0.5569852941176471
acc is : 0.5569852941176471
2023-10-16 00:00:17,764:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.526267  0.473733       0  ...  0.918903   1.0    0.0  0.978420
540     1  0.475431  0.524569       1  ...  0.920351   1.0    0.0  0.979961
541     0  0.512309  0.487691       0  ...  0.919317   1.0    0.0  0.978861
542     1  0.488476  0.511524       1  ...  0.920091   1.0    0.0  0.979684
543     0  0.506751  0.493249       1  ...  0.920135   1.0    0.0  0.979732

[5 rows x 10 columns]
2023-10-16 00:00:17,776:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526262  0.473738       0  ...  0.918903   1.0    0.0  0.981840
46     1  0.475512  0.524488       1  ...  0.920351   1.0    0.0  0.981195
47     0  0.512439  0.487561       0  ...  0.919317   1.0    0.0  0.980358
48     1  0.488614  0.511386       1  ...  0.920091   1.0    0.0  0.981182
49     0  0.506751  0.493249       1  ...  0.920135   1.0    0.0  0.979732

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.627', 'enterprice': '27009.6', 'countrevence': '0', 'unrealprofit': '-2901.3956', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26886.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22247 

self.closeSec=1697383799, self.tradeDate='20231015', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26885.2', self.close='26884.4'
127.0.0.1 - - [15/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22248 

self.closeSec=1697384399, self.tradeDate='20231015', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26884.4', self.close='26886.5'
127.0.0.1 - - [15/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22249 

self.closeSec=1697384999, self.tradeDate='20231015', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26886.5', self.close='26885.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22250 

self.closeSec=1697385599, self.tradeDate='20231015', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26885.4', self.close='26885.6'
127.0.0.1 - - [16/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22251 

self.closeSec=1697386199, self.tradeDate='20231016', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26885.7', self.close='26883.5'
127.0.0.1 - - [16/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22252 

self.closeSec=1697386799, self.tradeDate='20231016', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26883.6', self.close='26885.7'
127.0.0.1 - - [16/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22250 

self.closeSec=1697383799, self.tradeDate='20231015', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26885.2', self.close='26884.4'
127.0.0.1 - - [15/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22251 

self.closeSec=1697384399, self.tradeDate='20231015', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26884.4', self.close='26886.5'
127.0.0.1 - - [15/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22252 

self.closeSec=1697384999, self.tradeDate='20231015', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26886.5', self.close='26885.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22253 

self.closeSec=1697385599, self.tradeDate='20231015', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26885.4', self.close='26885.6'
127.0.0.1 - - [16/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22254 

self.closeSec=1697386199, self.tradeDate='20231016', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26885.7', self.close='26883.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22255 

self.closeSec=1697386799, self.tradeDate='20231016', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26883.6', self.close='26885.7'
127.0.0.1 - - [16/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22250 

self.closeSec=1697383799, self.tradeDate='20231015', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26885.2', self.close='26884.4'
127.0.0.1 - - [15/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22251 

self.closeSec=1697384399, self.tradeDate='20231015', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26884.4', self.close='26886.5'
127.0.0.1 - - [15/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22252 

self.closeSec=1697384999, self.tradeDate='20231015', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26886.5', self.close='26885.4'
127.0.0.1 - - [16/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22253 

self.closeSec=1697385599, self.tradeDate='20231015', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26885.4', self.close='26885.6'
127.0.0.1 - - [16/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22254 

self.closeSec=1697386199, self.tradeDate='20231016', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26885.7', self.close='26883.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22255 

self.closeSec=1697386799, self.tradeDate='20231016', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26883.6', self.close='26885.7'
127.0.0.1 - - [16/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44500
self.closeSec=1697386799, self.tradeDate='20231016', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26893.9, self.close=26885.7, self.high=26893.9, self.low=26883.1, self.vol=203.543, self.amt=5473021.3114 
127.0.0.1 - - [16/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-16 00:20:13,847:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231015   235500    235959  ...         0.0        0.0       0
5760  20231016   000000    000459  ...         0.0        0.0       0
5761  20231016   000500    000959  ...         0.0        0.0       0
5762  20231016   001000    001459  ...         0.0        0.0       0
5763  20231016   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 00:20:13,866:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697386799, self.tradeDate='20231016', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26893.9, self.close=26885.7, self.high=26893.9, self.low=26883.1, self.vol=203.543, self.amt=5473021.3114, ukdf['pct'].iloc[-1]=-0.000309 , ukdf['amount'].iloc[-1]=5473021.3114, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '1619.3476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26887.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44501
self.closeSec=1697387099, self.tradeDate='20231016', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26885.6, self.close=26881.6, self.high=26887.7, self.low=26880.0, self.vol=198.935, self.amt=5347832.4304 
127.0.0.1 - - [16/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-16 00:25:03,336:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231016   000000    000459  ...         0.0        0.0       0
5761  20231016   000500    000959  ...         0.0        0.0       0
5762  20231016   001000    001459  ...         0.0        0.0       0
5763  20231016   001500    001959  ...         0.0        0.0       0
5764  20231016   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 00:25:03,346:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697387099, self.tradeDate='20231016', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26885.6, self.close=26881.6, self.high=26887.7, self.low=26880.0, self.vol=198.935, self.amt=5347832.4304, ukdf['pct'].iloc[-1]=-0.000152 , ukdf['amount'].iloc[-1]=5347832.4304, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '1400.2157', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26881.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231015   120000    155959  1697356799  ...    723  0.155730 -1.188482    -1.0
724  20231015   160000    195959  1697371199  ...    724  0.099890 -1.320283    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.1', 'enterprice': '26874.8', 'countrevence': '0', 'unrealprofit': '1631.230517472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26840.16665568', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [16/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1264537.27692, self.flagDict['side']='sell', self.tradeCount=34, self.count=927
self.closeSec=1697385599, self.tradeDate='20231015', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26840.5, self.close=26885.7, self.high=26958.0, self.low=26790.4, self.vol=26675.902, self.amt=716722154.3989 
2023-10-16 00:00:01,575:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697385599, self.tradeDate='20231015', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26840.5, self.close=26885.7, self.high=26958.0, self.low=26790.4, self.vol=26675.902, self.amt=716722154.3989 
2023-10-16 00:00:01,589:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231015   040000    075959  ...  12128.808  3.253471e+08 -0.000559
722  20231015   080000    115959  ...  10724.887  2.880777e+08  0.001304
723  20231015   120000    155959  ...   4448.772  1.195294e+08  0.000048
724  20231015   160000    195959  ...   9730.728  2.615033e+08 -0.001202
725  20231015   200000    235959  ...  26675.902  7.167222e+08  0.001688

[5 rows x 11 columns]
2023-10-16 00:00:02,240:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231015   040000    075959  1697327999  ...    721  0.550053 -0.076009     NaN
722  20231015   080000    115959  1697342399  ...    722  0.450608 -0.355997     NaN
723  20231015   120000    155959  1697356799  ...    723  0.155730 -1.188482    -1.0
724  20231015   160000    195959  1697371199  ...    724  0.099890 -1.320283    -1.0
725  20231015   200000    235959  1697385599  ...    725  0.008915 -1.541141    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.1', 'enterprice': '26874.8', 'countrevence': '0', 'unrealprofit': '-513.051328392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26885.69280952', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


