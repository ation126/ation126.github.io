# 20231016 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44596
self.closeSec=1697415599, self.tradeDate='20231016', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27146.5, self.close=27122.9, self.high=27152.0, self.low=27110.4, self.vol=1115.227, self.amt=30251052.9329 
127.0.0.1 - - [16/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-10-16 08:20:08,179:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231016   075500    075959  ...         0.0        0.0       0
5856  20231016   080000    080459  ...         0.0        0.0       0
5857  20231016   080500    080959  ...         0.0        0.0       0
5858  20231016   081000    081459  ...         0.0        0.0       0
5859  20231016   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 08:20:08,182:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697415599, self.tradeDate='20231016', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27146.5, self.close=27122.9, self.high=27152.0, self.low=27110.4, self.vol=1115.227, self.amt=30251052.9329, ukdf['pct'].iloc[-1]=-0.000869 , ukdf['amount'].iloc[-1]=30251052.9329, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3599.871', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27123.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44597
self.closeSec=1697415899, self.tradeDate='20231016', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27122.8, self.close=27129.3, self.high=27141.6, self.low=27120.0, self.vol=348.931, self.amt=9465896.3059 
127.0.0.1 - - [16/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-16 08:25:02,802:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231016   080000    080459  ...         0.0        0.0       0
5857  20231016   080500    080959  ...         0.0        0.0       0
5858  20231016   081000    081459  ...         0.0        0.0       0
5859  20231016   081500    081959  ...         0.0        0.0       0
5860  20231016   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 08:25:02,814:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697415899, self.tradeDate='20231016', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27122.8, self.close=27129.3, self.high=27141.6, self.low=27120.0, self.vol=348.931, self.amt=9465896.3059, ukdf['pct'].iloc[-1]=0.000236 , ukdf['amount'].iloc[-1]=9465896.3059, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3670.22877373482', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27128.45226007', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44594 

self.closeSec=1697414399, self.tradeDate='20231016', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27121.2, self.close=27139.8, self.high=27141.1, self.low=27121.2 
127.0.0.1 - - [16/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44595 

self.closeSec=1697414699, self.tradeDate='20231016', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27139.8, self.close=27149.1, self.high=27150.0, self.low=27115.3 
127.0.0.1 - - [16/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44596 

self.closeSec=1697414999, self.tradeDate='20231016', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27149.9, self.close=27171.3, self.high=27176.4, self.low=27149.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44597 

self.closeSec=1697415299, self.tradeDate='20231016', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27171.2, self.close=27146.5, self.high=27179.9, self.low=27141.5 
127.0.0.1 - - [16/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44598 

self.closeSec=1697415599, self.tradeDate='20231016', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27146.5, self.close=27122.9, self.high=27152.0, self.low=27110.4 
127.0.0.1 - - [16/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44599 

self.closeSec=1697415899, self.tradeDate='20231016', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27122.8, self.close=27129.3, self.high=27141.6, self.low=27120.0 
127.0.0.1 - - [16/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-16 08:00:20,024:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231016    052959  27193.9  ...  50.833333  0.607728  0.329841
5770  20231016    055959  27153.2  ...  51.250000  0.611405  0.337064
5771  20231016    062959  27164.4  ...  51.250000  0.636315  0.335704
5772  20231016    065959  27245.4  ...  50.833333  0.563589  0.350417
5773  20231016    072959  27085.6  ...  50.833333  0.544875  0.368857

[5 rows x 33 columns]
0.5537037037037037
acc is : 0.5537037037037037
2023-10-16 08:00:20,107:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.495551  0.504449       1  ...  0.963644   1.0    0.0  0.987018
536     0  0.512696  0.487304       1  ...  0.966514   1.0    0.0  0.989957
537     0  0.539450  0.460550       0  ...  0.960852   1.0    0.0  0.984158
538     1  0.453619  0.546381       0  ...  0.959185   1.0    0.0  0.982450
539     1  0.472666  0.527334       1  ...  0.962771   1.0    0.0  0.986124

[5 rows x 10 columns]
2023-10-16 08:00:20,125:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496026  0.503974       1  ...  0.929673   1.0    0.0  0.991821
46     0  0.513000  0.487000       1  ...  0.932442   1.0    0.0  0.992478
47     0  0.539790  0.460210       0  ...  0.960852   1.0    0.0  0.984594
48     1  0.453683  0.546317       0  ...  0.959185   1.0    0.0  0.982686
49     1  0.472666  0.527334       1  ...  0.962771   1.0    0.0  0.986124

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.627', 'enterprice': '27009.6', 'countrevence': '0', 'unrealprofit': '3082.54047688419', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27140.06685897', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [16/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22295 

self.closeSec=1697412599, self.tradeDate='20231016', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27030.9', self.close='27038.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22296 

self.closeSec=1697413199, self.tradeDate='20231016', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27038.7', self.close='27071.2'
127.0.0.1 - - [16/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22297 

self.closeSec=1697413799, self.tradeDate='20231016', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27071.2', self.close='27127.1'
127.0.0.1 - - [16/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22298 

self.closeSec=1697414399, self.tradeDate='20231016', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27127', self.close='27139.8'
127.0.0.1 - - [16/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22299 

self.closeSec=1697414999, self.tradeDate='20231016', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27139.8', self.close='27171.3'
127.0.0.1 - - [16/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22300 

self.closeSec=1697415599, self.tradeDate='20231016', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27171.2', self.close='27122.9'
127.0.0.1 - - [16/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [16/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22298 

self.closeSec=1697412599, self.tradeDate='20231016', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27030.9', self.close='27038.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22299 

self.closeSec=1697413199, self.tradeDate='20231016', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27038.7', self.close='27071.2'
127.0.0.1 - - [16/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22300 

self.closeSec=1697413799, self.tradeDate='20231016', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27071.2', self.close='27127.1'
127.0.0.1 - - [16/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22301 

self.closeSec=1697414399, self.tradeDate='20231016', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27127', self.close='27139.8'
127.0.0.1 - - [16/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22302 

self.closeSec=1697414999, self.tradeDate='20231016', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27139.8', self.close='27171.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22303 

self.closeSec=1697415599, self.tradeDate='20231016', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27171.2', self.close='27122.9'
127.0.0.1 - - [16/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22298 

self.closeSec=1697412599, self.tradeDate='20231016', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27030.9', self.close='27038.7'
127.0.0.1 - - [16/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22299 

self.closeSec=1697413199, self.tradeDate='20231016', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27038.7', self.close='27071.2'

--handleKline--:  127.0.0.1 - - [16/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22300 

self.closeSec=1697413799, self.tradeDate='20231016', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27071.2', self.close='27127.1'
127.0.0.1 - - [16/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22301 

self.closeSec=1697414399, self.tradeDate='20231016', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27127', self.close='27139.8'
127.0.0.1 - - [16/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22302 

self.closeSec=1697414999, self.tradeDate='20231016', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27139.8', self.close='27171.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22303 

self.closeSec=1697415599, self.tradeDate='20231016', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27171.2', self.close='27122.9'
127.0.0.1 - - [16/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44596
self.closeSec=1697415599, self.tradeDate='20231016', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27146.5, self.close=27122.9, self.high=27152.0, self.low=27110.4, self.vol=1115.227, self.amt=30251052.9329 
127.0.0.1 - - [16/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-10-16 08:20:08,177:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231016   075500    075959  ...         0.0        0.0       0
5856  20231016   080000    080459  ...         0.0        0.0       0
5857  20231016   080500    080959  ...         0.0        0.0       0
5858  20231016   081000    081459  ...         0.0        0.0       0
5859  20231016   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 08:20:08,201:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697415599, self.tradeDate='20231016', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27146.5, self.close=27122.9, self.high=27152.0, self.low=27110.4, self.vol=1115.227, self.amt=30251052.9329, ukdf['pct'].iloc[-1]=-0.000869 , ukdf['amount'].iloc[-1]=30251052.9329, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10377.1954', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27123.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44597
self.closeSec=1697415899, self.tradeDate='20231016', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27122.8, self.close=27129.3, self.high=27141.6, self.low=27120.0, self.vol=348.931, self.amt=9465896.3059 
127.0.0.1 - - [16/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-16 08:25:02,801:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231016   080000    080459  ...         0.0        0.0       0
5857  20231016   080500    080959  ...         0.0        0.0       0
5858  20231016   081000    081459  ...         0.0        0.0       0
5859  20231016   081500    081959  ...         0.0        0.0       0
5860  20231016   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-16 08:25:02,815:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697415899, self.tradeDate='20231016', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27122.8, self.close=27129.3, self.high=27141.6, self.low=27120.0, self.vol=348.931, self.amt=9465896.3059, ukdf['pct'].iloc[-1]=0.000236 , ukdf['amount'].iloc[-1]=9465896.3059, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10564.84139125987', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27128.45226007', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231015   200000    235959  1697385599  ...    719  0.008915 -1.541141    -1.0
720  20231016   000000    035959  1697399999  ...    720  0.062670 -1.360868    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.1', 'enterprice': '26874.8', 'countrevence': '0', 'unrealprofit': '-7667.88', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27037.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1264537.27692, self.flagDict['side']='sell', self.tradeCount=34, self.count=929
self.closeSec=1697414399, self.tradeDate='20231016', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27030.1, self.close=27139.8, self.high=27456.1, self.low=27000.9, self.vol=74881.965, self.amt=2033626035.76352 
127.0.0.1 - - [16/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-16 08:00:01,565:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697414399, self.tradeDate='20231016', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27030.1, self.close=27139.8, self.high=27456.1, self.low=27000.9, self.vol=74881.965, self.amt=2033626035.76352 
2023-10-16 08:00:01,609:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231015   120000    155959  ...   4448.772  1.195294e+08  0.000048
718  20231015   160000    195959  ...   9730.728  2.615033e+08 -0.001202
719  20231015   200000    235959  ...  26675.902  7.167222e+08  0.001688
720  20231016   000000    035959  ...  33515.848  9.044073e+08  0.005371
721  20231016   040000    075959  ...  74881.965  2.033626e+09  0.004058

[5 rows x 11 columns]
2023-10-16 08:00:02,284:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231015   120000    155959  1697356799  ...    717  0.155730 -1.188482    -1.0
718  20231015   160000    195959  1697371199  ...    718  0.099890 -1.320283    -1.0
719  20231015   200000    235959  1697385599  ...    719  0.008915 -1.541141    -1.0
720  20231016   000000    035959  1697399999  ...    720  0.062670 -1.360868    -1.0
721  20231016   040000    075959  1697414399  ...    721  0.326582 -0.618872    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.1', 'enterprice': '26874.8', 'countrevence': '0', 'unrealprofit': '-12528.724564899', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27140.80264469', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


