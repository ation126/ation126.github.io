# 20230904 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32500
self.closeSec=1693786799, self.tradeDate='20230904', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25930.8, self.close=25921.5, self.high=25930.8, self.low=25914.0, self.vol=242.56, self.amt=6286923.7536 
127.0.0.1 - - [04/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-04 08:20:05,187:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230904   075500    075959  ...         0.0        0.0       0
5844  20230904   080000    080459  ...         0.0        0.0       0
5845  20230904   080500    080959  ...         0.0        0.0       0
5846  20230904   081000    081459  ...         0.0        0.0       0
5847  20230904   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 08:20:05,191:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693786799, self.tradeDate='20230904', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25930.8, self.close=25921.5, self.high=25930.8, self.low=25914.0, self.vol=242.56, self.amt=6286923.7536, ukdf['pct'].iloc[-1]=-0.000359 , ukdf['amount'].iloc[-1]=6286923.7536, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13139.181', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25921.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32501
self.closeSec=1693787099, self.tradeDate='20230904', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25921.5, self.close=25922.3, self.high=25935.8, self.low=25919.1, self.vol=168.071, self.amt=4357722.3961 
127.0.0.1 - - [04/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-04 08:25:00,781:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230904   080000    080459  ...         0.0        0.0       0
5845  20230904   080500    080959  ...         0.0        0.0       0
5846  20230904   081000    081459  ...         0.0        0.0       0
5847  20230904   081500    081959  ...         0.0        0.0       0
5848  20230904   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 08:25:00,782:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693787099, self.tradeDate='20230904', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25921.5, self.close=25922.3, self.high=25935.8, self.low=25919.1, self.vol=168.071, self.amt=4357722.3961, ukdf['pct'].iloc[-1]=3.1e-05 , ukdf['amount'].iloc[-1]=4357722.3961, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13125.255', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25922.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [04/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32498 

self.closeSec=1693785599, self.tradeDate='20230904', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25969.9, self.close=25962.1, self.high=25971.8, self.low=25955.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32499 

self.closeSec=1693785899, self.tradeDate='20230904', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25962.1, self.close=25946.1, self.high=25965.0, self.low=25946.1 
127.0.0.1 - - [04/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32500 

self.closeSec=1693786199, self.tradeDate='20230904', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25946.2, self.close=25930.3, self.high=25946.2, self.low=25930.3 
127.0.0.1 - - [04/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32501 

self.closeSec=1693786499, self.tradeDate='20230904', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25930.4, self.close=25930.8, self.high=25932.0, self.low=25915.3 
127.0.0.1 - - [04/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32502 

self.closeSec=1693786799, self.tradeDate='20230904', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25930.8, self.close=25921.5, self.high=25930.8, self.low=25914.0 
127.0.0.1 - - [04/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32503 

self.closeSec=1693787099, self.tradeDate='20230904', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25921.5, self.close=25922.3, self.high=25935.8, self.low=25919.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-04 08:00:19,023:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230904    052959  26039.7  ...  45.416667  0.520762  0.509797
5770  20230904    055959  25989.6  ...  45.416667  0.508485  0.509163
5771  20230904    062959  25956.0  ...  45.416667  0.504345  0.510711
5772  20230904    065959  25944.5  ...  45.000000  0.502168  0.513272
5773  20230904    072959  25938.5  ...  45.416667  0.504605  0.514416

[5 rows x 33 columns]
0.5203703703703704
acc is : 0.5203703703703704
2023-09-04 08:00:19,121:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.482048  0.517952       0  ...  1.001844  -1.0    0.0  0.978478
536     1  0.482014  0.517986       0  ...  1.002288  -1.0    0.0  0.978045
537     1  0.482307  0.517693       0  ...  1.002520  -1.0    0.0  0.977819
538     1  0.484869  0.515131       1  ...  1.002261  -1.0    0.0  0.978071
539     1  0.483686  0.516314       1  ...  1.001608  -1.0    0.0  0.978708

[5 rows x 10 columns]
2023-09-04 08:00:19,141:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483496  0.516504       0  ...  0.999458  -1.0    0.0  0.993178
46     1  0.482823  0.517177       0  ...  0.999901  -1.0    0.0  0.985467
47     1  0.482796  0.517204       0  ...  0.994398  -1.0    0.0  0.983294
48     1  0.485066  0.514934       1  ...  0.994141  -1.0    0.0  0.979844
49     1  0.483686  0.516314       1  ...  1.001608  -1.0    0.0  0.978708

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '18851.5814', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25964.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [04/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16247 

self.closeSec=1693783799, self.tradeDate='20230904', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25956.1', self.close='25945.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16248 

self.closeSec=1693784399, self.tradeDate='20230904', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25945.3', self.close='25943'
127.0.0.1 - - [04/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16249 

self.closeSec=1693784999, self.tradeDate='20230904', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25943', self.close='25963.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16250 

self.closeSec=1693785599, self.tradeDate='20230904', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25963.8', self.close='25962.1'
127.0.0.1 - - [04/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16251 

self.closeSec=1693786199, self.tradeDate='20230904', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25962.1', self.close='25930.4'
127.0.0.1 - - [04/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16252 

self.closeSec=1693786799, self.tradeDate='20230904', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25930.4', self.close='25921.5'
127.0.0.1 - - [04/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16250 

self.closeSec=1693783799, self.tradeDate='20230904', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25956.1', self.close='25945.2'
127.0.0.1 - - [04/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16251 

self.closeSec=1693784399, self.tradeDate='20230904', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25945.3', self.close='25943'
127.0.0.1 - - [04/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16252 

self.closeSec=1693784999, self.tradeDate='20230904', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25943', self.close='25963.9'
127.0.0.1 - - [04/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16253 

self.closeSec=1693785599, self.tradeDate='20230904', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25963.8', self.close='25962.1'
127.0.0.1 - - [04/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16254 

self.closeSec=1693786199, self.tradeDate='20230904', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25962.1', self.close='25930.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16255 

self.closeSec=1693786799, self.tradeDate='20230904', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25930.4', self.close='25921.5'
127.0.0.1 - - [04/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [04/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16250 

self.closeSec=1693783799, self.tradeDate='20230904', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25956.1', self.close='25945.2'
127.0.0.1 - - [04/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16251 

self.closeSec=1693784399, self.tradeDate='20230904', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25945.3', self.close='25943'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16252 

self.closeSec=1693784999, self.tradeDate='20230904', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25943', self.close='25963.9'
127.0.0.1 - - [04/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16253 

self.closeSec=1693785599, self.tradeDate='20230904', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25963.8', self.close='25962.1'
127.0.0.1 - - [04/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16254 

self.closeSec=1693786199, self.tradeDate='20230904', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25962.1', self.close='25930.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16255 

self.closeSec=1693786799, self.tradeDate='20230904', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25930.4', self.close='25921.5'
127.0.0.1 - - [04/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32500
self.closeSec=1693786799, self.tradeDate='20230904', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25930.8, self.close=25921.5, self.high=25930.8, self.low=25914.0, self.vol=242.56, self.amt=6286923.7536 
127.0.0.1 - - [04/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-04 08:20:05,188:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230904   075500    075959  ...         0.0        0.0       0
5844  20230904   080000    080459  ...         0.0        0.0       0
5845  20230904   080500    080959  ...         0.0        0.0       0
5846  20230904   081000    081459  ...         0.0        0.0       0
5847  20230904   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 08:20:05,191:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693786799, self.tradeDate='20230904', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25930.8, self.close=25921.5, self.high=25930.8, self.low=25914.0, self.vol=242.56, self.amt=6286923.7536, ukdf['pct'].iloc[-1]=-0.000359 , ukdf['amount'].iloc[-1]=6286923.7536, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-34266.2866', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25921.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [04/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32501
self.closeSec=1693787099, self.tradeDate='20230904', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25921.5, self.close=25922.3, self.high=25935.8, self.low=25919.1, self.vol=168.071, self.amt=4357722.3961 
2023-09-04 08:25:00,782:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230904   080000    080459  ...         0.0        0.0       0
5845  20230904   080500    080959  ...         0.0        0.0       0
5846  20230904   081000    081459  ...         0.0        0.0       0
5847  20230904   081500    081959  ...         0.0        0.0       0
5848  20230904   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 08:25:00,782:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693787099, self.tradeDate='20230904', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25921.5, self.close=25922.3, self.high=25935.8, self.low=25919.1, self.vol=168.071, self.amt=4357722.3961, ukdf['pct'].iloc[-1]=3.1e-05 , ukdf['amount'].iloc[-1]=4357722.3961, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-34229.1456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25922.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230903   200000    235959  1693756799  ...    719  0.810581  1.203812     1.0
720  20230904   000000    035959  1693771199  ...    720  0.764640  1.056010     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-104937.1908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26000.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [04/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=677
self.closeSec=1693785599, self.tradeDate='20230904', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25997.5, self.close=25962.1, self.high=26135.2, self.low=25915.0, self.vol=25287.093, self.amt=657594317.44136 
2023-09-04 08:00:01,566:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693785599, self.tradeDate='20230904', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25997.5, self.close=25962.1, self.high=26135.2, self.low=25915.0, self.vol=25287.093, self.amt=657594317.44136 
2023-09-04 08:00:01,589:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230903   120000    155959  ...  11059.332  2.864283e+08  0.003536
718  20230903   160000    195959  ...  11620.082  3.009666e+08 -0.000420
719  20230903   200000    235959  ...  42781.009  1.109222e+09 -0.002788
720  20230904   000000    035959  ...  31902.907  8.265704e+08  0.005391
721  20230904   040000    075959  ...  25287.093  6.575943e+08 -0.001366

[5 rows x 11 columns]
2023-09-04 08:00:02,605:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230903   120000    155959  1693727999  ...    717  0.789376  1.178070     1.0
718  20230903   160000    195959  1693742399  ...    718  0.814755  1.234112     1.0
719  20230903   200000    235959  1693756799  ...    719  0.810581  1.203812     1.0
720  20230904   000000    035959  1693771199  ...    720  0.764640  1.056010     1.0
721  20230904   040000    075959  1693785599  ...    721  0.751855  1.007003     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-107158.5684', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25962.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


