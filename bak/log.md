# 20230512 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47733
self.closeSec=1683850799, self.tradeDate='20230512', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26959.4, self.close=26961.6, self.high=26989.9, self.low=26935.9, self.vol=1042.655, self.amt=28114696.8516 
127.0.0.1 - - [12/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-12 08:20:06,083:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230512   075500    075959  ...         0.0        0.0       0
5856  20230512   080000    080459  ...         0.0        0.0       0
5857  20230512   080500    080959  ...         0.0        0.0       0
5858  20230512   081000    081459  ...         0.0        0.0       0
5859  20230512   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 08:20:06,093:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683850799, self.tradeDate='20230512', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26959.4, self.close=26961.6, self.high=26989.9, self.low=26935.9, self.vol=1042.655, self.amt=28114696.8516, ukdf['pct'].iloc[-1]=8.2e-05 , ukdf['amount'].iloc[-1]=28114696.8516, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-628105.0528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26967.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47734
self.closeSec=1683851099, self.tradeDate='20230512', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26961.6, self.close=26982.4, self.high=26984.4, self.low=26954.2, self.vol=536.221, self.amt=14462217.6839 
127.0.0.1 - - [12/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-05-12 08:25:02,167:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230512   080000    080459  ...         0.0        0.0       0
5857  20230512   080500    080959  ...         0.0        0.0       0
5858  20230512   081000    081459  ...         0.0        0.0       0
5859  20230512   081500    081959  ...         0.0        0.0       0
5860  20230512   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 08:25:02,167:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683851099, self.tradeDate='20230512', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26961.6, self.close=26982.4, self.high=26984.4, self.low=26954.2, self.vol=536.221, self.amt=14462217.6839, ukdf['pct'].iloc[-1]=0.000771 , ukdf['amount'].iloc[-1]=14462217.6839, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-629025.7456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26982.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48295 

self.closeSec=1683849599, self.tradeDate='20230512', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26985.6, self.close=26956.4, self.high=26985.6, self.low=26950.0 
127.0.0.1 - - [12/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48296 

self.closeSec=1683849899, self.tradeDate='20230512', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26956.4, self.close=26965.7, self.high=26988.3, self.low=26949.3 
127.0.0.1 - - [12/May/2023 08:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48297 

self.closeSec=1683850199, self.tradeDate='20230512', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26965.7, self.close=26948.4, self.high=26977.0, self.low=26947.0 
127.0.0.1 - - [12/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48298 

self.closeSec=1683850499, self.tradeDate='20230512', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26948.5, self.close=26959.4, self.high=26959.4, self.low=26936.6 
127.0.0.1 - - [12/May/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48299 

self.closeSec=1683850799, self.tradeDate='20230512', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26959.4, self.close=26961.6, self.high=26989.9, self.low=26935.9 
127.0.0.1 - - [12/May/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48300 

self.closeSec=1683851099, self.tradeDate='20230512', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26961.6, self.close=26982.4, self.high=26984.4, self.low=26954.2 
127.0.0.1 - - [12/May/2023 08:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-12 08:00:20,091:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230512    052959  26982.0  ...  51.250000  0.428649  0.697172
5770  20230512    055959  27005.5  ...  50.833333  0.423397  0.697712
5771  20230512    062959  26966.2  ...  50.833333  0.428290  0.696311
5772  20230512    065959  26993.1  ...  50.833333  0.414547  0.702298
5773  20230512    072959  26890.0  ...  50.833333  0.420443  0.705620

[5 rows x 33 columns]
0.5370370370370371
acc is : 0.5370370370370371
2023-05-12 08:00:20,224:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.517722  0.482278       0  ...  1.016782  -1.0    0.0  0.910147
536     0  0.507705  0.492295       1  ...  1.015767  -1.0    0.0  0.911055
537     0  0.528963  0.471037       0  ...  1.019643  -1.0    0.0  0.907579
538     1  0.491746  0.508254       1  ...  1.018430  -1.0    0.0  0.908659
539     0  0.501944  0.498056       1  ...  1.017132  -1.0    0.0  0.909816

[5 rows x 10 columns]
2023-05-12 08:00:20,238:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.517700  0.482300       0  ...  1.016782  -1.0    0.0  0.909662
46     0  0.507892  0.492108       1  ...  1.015767  -1.0    0.0  0.911273
47     0  0.528924  0.471076       0  ...  1.019643  -1.0    0.0  0.905388
48     1  0.491447  0.508553       1  ...  1.018430  -1.0    0.0  0.904756
49     0  0.501944  0.498056       1  ...  1.017132  -1.0    0.0  0.909816

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [12/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24145 

self.closeSec=1683847799, self.tradeDate='20230512', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26905.3', self.close='26922.1'

--handleKline--: 127.0.0.1 - - [12/May/2023 07:40:02] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24146 

self.closeSec=1683848399, self.tradeDate='20230512', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26922.1', self.close='26970'
127.0.0.1 - - [12/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24147 

self.closeSec=1683848999, self.tradeDate='20230512', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26970.1', self.close='27010.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24148 

self.closeSec=1683849599, self.tradeDate='20230512', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27011', self.close='26956.4'
127.0.0.1 - - [12/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24149 

self.closeSec=1683850199, self.tradeDate='20230512', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26956.4', self.close='26948.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24150 

self.closeSec=1683850799, self.tradeDate='20230512', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26948.5', self.close='26961.6'
127.0.0.1 - - [12/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24146 

self.closeSec=1683847799, self.tradeDate='20230512', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26905.3', self.close='26922.1'
127.0.0.1 - - [12/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24147 

self.closeSec=1683848399, self.tradeDate='20230512', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26922.1', self.close='26970'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24148127.0.0.1 - - [12/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
 

self.closeSec=1683848999, self.tradeDate='20230512', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26970.1', self.close='27010.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24149 

self.closeSec=1683849599, self.tradeDate='20230512', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27011', self.close='26956.4'
127.0.0.1 - - [12/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24150 

self.closeSec=1683850199, self.tradeDate='20230512', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26956.4', self.close='26948.4'
127.0.0.1 - - [12/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24151 

self.closeSec=1683850799, self.tradeDate='20230512', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26948.5', self.close='26961.6'
127.0.0.1 - - [12/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24146 

self.closeSec=1683847799, self.tradeDate='20230512', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26905.3', self.close='26922.1'
127.0.0.1 - - [12/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24147 

self.closeSec=1683848399, self.tradeDate='20230512', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26922.1', self.close='26970'
127.0.0.1 - - [12/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24148 

self.closeSec=1683848999, self.tradeDate='20230512', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26970.1', self.close='27010.9'
127.0.0.1 - - [12/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24149 

self.closeSec=1683849599, self.tradeDate='20230512', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27011', self.close='26956.4'
127.0.0.1 - - [12/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24150 

self.closeSec=1683850199, self.tradeDate='20230512', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26956.4', self.close='26948.4'
127.0.0.1 - - [12/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24151 

self.closeSec=1683850799, self.tradeDate='20230512', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26948.5', self.close='26961.6'
127.0.0.1 - - [12/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43731
self.closeSec=1683850799, self.tradeDate='20230512', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26959.4, self.close=26961.6, self.high=26989.9, self.low=26935.9, self.vol=1042.655, self.amt=28114696.8516 
127.0.0.1 - - [12/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-12 08:20:06,124:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230512   075500    075959  ...         0.0        0.0       0
5856  20230512   080000    080459  ...         0.0        0.0       0
5857  20230512   080500    080959  ...         0.0        0.0       0
5858  20230512   081000    081459  ...         0.0        0.0       0
5859  20230512   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 08:20:06,133:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683850799, self.tradeDate='20230512', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26959.4, self.close=26961.6, self.high=26989.9, self.low=26935.9, self.vol=1042.655, self.amt=28114696.8516, ukdf['pct'].iloc[-1]=8.2e-05 , ukdf['amount'].iloc[-1]=28114696.8516, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [12/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43732
self.closeSec=1683851099, self.tradeDate='20230512', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26961.6, self.close=26982.4, self.high=26984.4, self.low=26954.2, self.vol=536.221, self.amt=14462217.6839 
2023-05-12 08:25:02,162:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230512   080000    080459  ...         0.0        0.0       0
5857  20230512   080500    080959  ...         0.0        0.0       0
5858  20230512   081000    081459  ...         0.0        0.0       0
5859  20230512   081500    081959  ...         0.0        0.0       0
5860  20230512   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 08:25:02,162:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683851099, self.tradeDate='20230512', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26961.6, self.close=26982.4, self.high=26984.4, self.low=26954.2, self.vol=536.221, self.amt=14462217.6839, ukdf['pct'].iloc[-1]=0.000771 , ukdf['amount'].iloc[-1]=14462217.6839, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

127.0.0.1 - - [12/May/2023 04:00:13] "POST / HTTP/1.1" 200 -
2023-05-12 04:00:13,559:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42153F1683835207954I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1683835208429291, 'quantity': '52.501', 'price': '26820.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1683835206924, 'updatetime': 1683835208429, 'tradetype': 'usdt', 'selfid': 42153, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1683835208429, 'clientorderid': '42153F1683835207954I0L65', 'price': '26820.2', 'quantity': '52.501', 'commission': '1408.0873202', 'commissionasset': 'USDT', 'tradetime': 1683835208429, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1683835208429}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/May/2023 04:00:13] "POST / HTTP/1.1" 200 -
2023-05-12 04:00:13,983:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42154F1683835213538I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1683835213944976, 'quantity': '52.436', 'price': '26818.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1683835213058, 'updatetime': 1683835213944, 'tradetype': 'usdt', 'selfid': 42154, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1683835213944, 'clientorderid': '42154F1683835213538I0L65', 'price': '26818.7', 'quantity': '52.436', 'commission': '1406.2653532', 'commissionasset': 'USDT', 'tradetime': 1683835213944, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1683835213944}], 'gatetype': 'simulator', 'handletime': 0}
2023-05-12 04:00:14,172:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42154F1683835213538I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1683835213944976, 'quantity': '52.436', 'price': '26818.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1683835213058, 'updatetime': 1683835213944, 'tradetype': 'usdt', 'selfid': 42154, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1683835213944, 'clientorderid': '42154F1683835213538I0L65', 'price': '26818.7', 'quantity': '52.436', 'commission': '1406.2653532', 'commissionasset': 'USDT', 'tradetime': 1683835213944, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1683835213944}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/May/2023 04:00:14] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1404859.0878468, self.flagDict['side']='sell', self.tradeCount=35, self.count=1006
self.closeSec=1683849599, self.tradeDate='20230512', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26831.5, self.close=26956.4, self.high=27050.8, self.low=26787.3, self.vol=53500.32, self.amt=1441430159.0916 
2023-05-12 08:00:03,509:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683849599, self.tradeDate='20230512', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26831.5, self.close=26956.4, self.high=27050.8, self.low=26787.3, self.vol=53500.32, self.amt=1441430159.0916 
2023-05-12 08:00:03,538:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230511   120000    155959  ...   39192.274  1.076570e+09  0.000087
718  20230511   160000    195959  ...   55275.014  1.514130e+09 -0.001615
719  20230511   200000    235959  ...  187266.555  5.104507e+09 -0.008283
720  20230512   000000    035959  ...  146708.743  3.948798e+09 -0.012328
721  20230512   040000    075959  ...   53500.320  1.441430e+09  0.004659

[5 rows x 11 columns]
2023-05-12 08:00:04,934:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230511   120000    155959  1683791999  ...    717  0.412500 -0.397041     NaN
718  20230511   160000    195959  1683806399  ...    718  0.412517 -0.380556     NaN
719  20230511   200000    235959  1683820799  ...    719  0.360522 -0.546813     NaN
720  20230512   000000    035959  1683835199  ...    720  0.316455 -0.690503    -1.0
721  20230512   040000    075959  1683849599  ...    721  0.274962 -0.824884    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-7213.29533971908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26956.26379853', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


