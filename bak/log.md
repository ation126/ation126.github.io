# 20231009 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42580
self.closeSec=1696810799, self.tradeDate='20231009', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27868.0, self.close=27843.3, self.high=27872.8, self.low=27841.6, self.vol=607.525, self.amt=16925041.7605 
127.0.0.1 - - [09/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-09 08:20:06,204:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231009   075500    075959  ...         0.0        0.0       0
5856  20231009   080000    080459  ...         0.0        0.0       0
5857  20231009   080500    080959  ...         0.0        0.0       0
5858  20231009   081000    081459  ...         0.0        0.0       0
5859  20231009   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 08:20:06,208:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696810799, self.tradeDate='20231009', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27868.0, self.close=27843.3, self.high=27872.8, self.low=27841.6, self.vol=607.525, self.amt=16925041.7605, ukdf['pct'].iloc[-1]=-0.00089 , ukdf['amount'].iloc[-1]=16925041.7605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13633.86130044642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27843.92206667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42581
self.closeSec=1696811099, self.tradeDate='20231009', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27843.3, self.close=27838.9, self.high=27843.4, self.low=27815.0, self.vol=1264.673, self.amt=35194516.6578 
2023-10-09 08:25:00,854:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231009   080000    080459  ...         0.0        0.0       0
5857  20231009   080500    080959  ...         0.0        0.0       0
5858  20231009   081000    081459  ...         0.0        0.0       0
5859  20231009   081500    081959  ...         0.0        0.0       0
5860  20231009   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 08:25:00,854:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696811099, self.tradeDate='20231009', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27843.3, self.close=27838.9, self.high=27843.4, self.low=27815.0, self.vol=1264.673, self.amt=35194516.6578, ukdf['pct'].iloc[-1]=-0.000158 , ukdf['amount'].iloc[-1]=35194516.6578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13523.5810060626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27836.0030451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [09/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42578 

self.closeSec=1696809599, self.tradeDate='20231009', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27915.6, self.close=27901.3, self.high=27920.4, self.low=27901.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42579 

self.closeSec=1696809899, self.tradeDate='20231009', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27901.2, self.close=27892.7, self.high=27907.7, self.low=27892.7 
127.0.0.1 - - [09/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42580 

self.closeSec=1696810199, self.tradeDate='20231009', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27892.7, self.close=27865.9, self.high=27899.0, self.low=27865.9 
127.0.0.1 - - [09/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42581 

self.closeSec=1696810499, self.tradeDate='20231009', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27865.9, self.close=27868.1, self.high=27879.0, self.low=27865.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42582 

self.closeSec=1696810799, self.tradeDate='20231009', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27868.0, self.close=27843.3, self.high=27872.8, self.low=27841.6 
127.0.0.1 - - [09/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42583 

self.closeSec=1696811099, self.tradeDate='20231009', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27843.3, self.close=27838.9, self.high=27843.4, self.low=27815.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-09 08:00:17,060:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231009    052959  27892.9  ...  51.250000  0.514956  0.548177
5770  20231009    055959  27908.7  ...  51.250000  0.513310  0.540504
5771  20231009    062959  27904.0  ...  51.250000  0.502366  0.538196
5772  20231009    065959  27872.6  ...  51.250000  0.512830  0.530976
5773  20231009    072959  27903.7  ...  50.833333  0.510181  0.525464

[5 rows x 33 columns]
0.5518518518518518
acc is : 0.5518518518518518
2023-10-09 08:00:17,132:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.505121  0.494879       0  ...  0.997953   1.0    0.0  1.064218
536     1  0.498069  0.501931       0  ...  0.996830   1.0    0.0  1.063020
537     1  0.489529  0.510471       1  ...  0.997938   1.0    0.0  1.064202
538     0  0.508097  0.491903       0  ...  0.997670   1.0    0.0  1.063916
539     1  0.496597  0.503403       1  ...  0.997856   1.0    0.0  1.064115

[5 rows x 10 columns]
2023-10-09 08:00:17,145:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505284  0.494716       0  ...  0.997953   1.0    0.0  1.061255
46     1  0.498092  0.501908       0  ...  0.996830   1.0    0.0  1.060182
47     1  0.489644  0.510356       1  ...  0.997938   1.0    0.0  1.063886
48     0  0.508195  0.491805       0  ...  0.997670   1.0    0.0  1.065021
49     1  0.496597  0.503403       1  ...  0.997856   1.0    0.0  1.064115

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.669', 'enterprice': '27936.3', 'countrevence': '0', 'unrealprofit': '-807.7237921562', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27902.1741902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [09/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21287 

self.closeSec=1696807799, self.tradeDate='20231009', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27909', self.close='27896.1'

--handleKline--:  127.0.0.1 - - [09/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21288 

self.closeSec=1696808399, self.tradeDate='20231009', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27896.2', self.close='27884'
127.0.0.1 - - [09/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21289 

self.closeSec=1696808999, self.tradeDate='20231009', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27884', self.close='27912.7'
127.0.0.1 - - [09/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21290 

self.closeSec=1696809599, self.tradeDate='20231009', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27912.6', self.close='27901.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21291 

self.closeSec=1696810199, self.tradeDate='20231009', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27901.2', self.close='27865.9'
127.0.0.1 - - [09/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21292 

self.closeSec=1696810799, self.tradeDate='20231009', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27865.9', self.close='27843.3'
127.0.0.1 - - [09/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21290 

self.closeSec=1696807799, self.tradeDate='20231009', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27909', self.close='27896.1'
127.0.0.1 - - [09/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21291 

self.closeSec=1696808399, self.tradeDate='20231009', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27896.2', self.close='27884'
127.0.0.1 - - [09/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21292 

self.closeSec=1696808999, self.tradeDate='20231009', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27884', self.close='27912.7'
127.0.0.1 - - [09/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21293 

self.closeSec=1696809599, self.tradeDate='20231009', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27912.6', self.close='27901.2'
127.0.0.1 - - [09/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21294 

self.closeSec=1696810199, self.tradeDate='20231009', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27901.2', self.close='27865.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21295 

self.closeSec=1696810799, self.tradeDate='20231009', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27865.9', self.close='27843.3'
127.0.0.1 - - [09/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21290 

self.closeSec=1696807799, self.tradeDate='20231009', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27909', self.close='27896.1'
127.0.0.1 - - [09/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21291 

self.closeSec=1696808399, self.tradeDate='20231009', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27896.2', self.close='27884'
127.0.0.1 - - [09/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21292 

self.closeSec=1696808999, self.tradeDate='20231009', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27884', self.close='27912.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21293 

self.closeSec=1696809599, self.tradeDate='20231009', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27912.6', self.close='27901.2'
127.0.0.1 - - [09/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21294 

self.closeSec=1696810199, self.tradeDate='20231009', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27901.2', self.close='27865.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21295 

self.closeSec=1696810799, self.tradeDate='20231009', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27865.9', self.close='27843.3'
127.0.0.1 - - [09/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42580
self.closeSec=1696810799, self.tradeDate='20231009', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27868.0, self.close=27843.3, self.high=27872.8, self.low=27841.6, self.vol=607.525, self.amt=16925041.7605 
127.0.0.1 - - [09/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-09 08:20:06,202:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231009   075500    075959  ...         0.0        0.0       0
5856  20231009   080000    080459  ...         0.0        0.0       0
5857  20231009   080500    080959  ...         0.0        0.0       0
5858  20231009   081000    081459  ...         0.0        0.0       0
5859  20231009   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 08:20:06,206:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696810799, self.tradeDate='20231009', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27868.0, self.close=27843.3, self.high=27872.8, self.low=27841.6, self.vol=607.525, self.amt=16925041.7605, ukdf['pct'].iloc[-1]=-0.00089 , ukdf['amount'].iloc[-1]=16925041.7605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '37138.10547819047', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27843.92206667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42581
self.closeSec=1696811099, self.tradeDate='20231009', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27843.3, self.close=27838.9, self.high=27843.4, self.low=27815.0, self.vol=1264.673, self.amt=35194516.6578 
2023-10-09 08:25:00,867:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231009   080000    080459  ...         0.0        0.0       0
5857  20231009   080500    080959  ...         0.0        0.0       0
5858  20231009   081000    081459  ...         0.0        0.0       0
5859  20231009   081500    081959  ...         0.0        0.0       0
5860  20231009   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 08:25:00,867:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696811099, self.tradeDate='20231009', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27843.3, self.close=27838.9, self.high=27843.4, self.low=27815.0, self.vol=1264.673, self.amt=35194516.6578, ukdf['pct'].iloc[-1]=-0.000158 , ukdf['amount'].iloc[-1]=35194516.6578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '36843.9850980591', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27836.0030451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231008   200000    235959  1696780799  ...    719  0.100098 -1.254552    -1.0
720  20231009   000000    035959  1696795199  ...    720  0.078013 -1.290971    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '2639.31542951876', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27883.86107692', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [09/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=887
self.closeSec=1696809599, self.tradeDate='20231009', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27880.3, self.close=27901.3, self.high=27968.7, self.low=27780.4, self.vol=22355.647, self.amt=623475423.8741 
2023-10-09 08:00:01,540:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696809599, self.tradeDate='20231009', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27880.3, self.close=27901.3, self.high=27968.7, self.low=27780.4, self.vol=22355.647, self.amt=623475423.8741 
2023-10-09 08:00:01,555:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231008   120000    155959  ...  28016.932  7.825298e+08 -0.005615
718  20231008   160000    195959  ...  31071.685  8.650403e+08 -0.003345
719  20231008   200000    235959  ...  50313.962  1.401446e+09  0.003040
720  20231009   000000    035959  ...  23249.821  6.478884e+08 -0.000115
721  20231009   040000    075959  ...  22355.647  6.234754e+08  0.000750

[5 rows x 11 columns]
2023-10-09 08:00:02,236:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231008   120000    155959  1696751999  ...    717  0.150071 -1.168478    -1.0
718  20231008   160000    195959  1696766399  ...    718  0.112997 -1.241572    -1.0
719  20231008   200000    235959  1696780799  ...    719  0.100098 -1.254552    -1.0
720  20231009   000000    035959  1696795199  ...    720  0.078013 -1.290971    -1.0
721  20231009   040000    075959  1696809599  ...    721  0.083383 -1.253474    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '1758.10228178729', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27904.07377843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


