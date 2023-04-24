# 20230424 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [24/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42549
self.closeSec=1682295599, self.tradeDate='20230424', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27546.5, self.close=27509.5, self.high=27554.1, self.low=27509.5, self.vol=1394.18, self.amt=38382240.9777 
2023-04-24 08:20:02,246:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230424   075500    075959  ...         0.0        0.0       0
5849  20230424   080000    080459  ...         0.0        0.0       0
5850  20230424   080500    080959  ...         0.0        0.0       0
5851  20230424   081000    081459  ...         0.0        0.0       0
5852  20230424   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 08:20:02,248:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682295599, self.tradeDate='20230424', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27546.5, self.close=27509.5, self.high=27554.1, self.low=27509.5, self.vol=1394.18, self.amt=38382240.9777, ukdf['pct'].iloc[-1]=-0.00134 , ukdf['amount'].iloc[-1]=38382240.9777, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-660744.5152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27509.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42550
self.closeSec=1682295899, self.tradeDate='20230424', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27509.6, self.close=27482.7, self.high=27522.2, self.low=27463.6, self.vol=1824.172, self.amt=50149842.5085 
127.0.0.1 - - [24/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-24 08:25:01,564:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230424   080000    080459  ...         0.0        0.0       0
5850  20230424   080500    080959  ...         0.0        0.0       0
5851  20230424   081000    081459  ...         0.0        0.0       0
5852  20230424   081500    081959  ...         0.0        0.0       0
5853  20230424   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 08:25:01,565:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682295899, self.tradeDate='20230424', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27509.6, self.close=27482.7, self.high=27522.2, self.low=27463.6, self.vol=1824.172, self.amt=50149842.5085, ukdf['pct'].iloc[-1]=-0.000974 , ukdf['amount'].iloc[-1]=50149842.5085, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-659137.816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27482.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43111 

self.closeSec=1682294399, self.tradeDate='20230424', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27565.1, self.close=27576.0, self.high=27583.8, self.low=27561.4 
127.0.0.1 - - [24/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43112 

self.closeSec=1682294699, self.tradeDate='20230424', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27575.9, self.close=27557.5, self.high=27576.0, self.low=27557.5 
127.0.0.1 - - [24/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43113 

self.closeSec=1682294999, self.tradeDate='20230424', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27557.5, self.close=27559.3, self.high=27577.6, self.low=27553.8 
127.0.0.1 - - [24/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43114 

self.closeSec=1682295299, self.tradeDate='20230424', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27559.4, self.close=27546.4, self.high=27559.4, self.low=27546.4 
127.0.0.1 - - [24/Apr/2023 08:15:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43115 

self.closeSec=1682295599, self.tradeDate='20230424', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27546.5, self.close=27509.5, self.high=27554.1, self.low=27509.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43116 

self.closeSec=1682295899, self.tradeDate='20230424', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27509.6, self.close=27482.7, self.high=27522.2, self.low=27463.6 
127.0.0.1 - - [24/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-24 08:00:20,199:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230424    052959  27492.0  ...  50.000000  0.469107  0.574367
5770  20230424    055959  27497.5  ...  50.000000  0.469557  0.572234
5771  20230424    062959  27499.5  ...  50.416667  0.474926  0.566967
5772  20230424    065959  27523.0  ...  50.416667  0.487595  0.554210
5773  20230424    072959  27579.7  ...  50.833333  0.495054  0.537597

[5 rows x 33 columns]
0.5333333333333333
acc is : 0.5333333333333333
2023-04-24 08:00:20,314:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.514970  0.485030       1  ...  0.879393   1.0    0.0  0.916409
536     0  0.514407  0.485593       1  ...  0.880147   1.0    0.0  0.917195
537     0  0.521508  0.478492       1  ...  0.881954   1.0    0.0  0.919078
538     0  0.527814  0.472186       1  ...  0.883038   1.0    0.0  0.920208
539     0  0.527945  0.472055       0  ...  0.881839   1.0    0.0  0.918958

[5 rows x 10 columns]
2023-04-24 08:00:20,341:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515726  0.484274       1  ...  0.879393   1.0    0.0  0.918242
46     0  0.514846  0.485154       1  ...  0.880147   1.0    0.0  0.918061
47     0  0.522194  0.477806       1  ...  0.881954   1.0    0.0  0.921710
48     0  0.528249  0.471751       1  ...  0.883038   1.0    0.0  0.920643
49     0  0.527945  0.472055       0  ...  0.881839   1.0    0.0  0.918958

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [24/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21553 

self.closeSec=1682292599, self.tradeDate='20230424', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27589.9', self.close='27613.5'
127.0.0.1 - - [24/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21554 

self.closeSec=1682293199, self.tradeDate='20230424', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27613.4', self.close='27577.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21555 

self.closeSec=1682293799, self.tradeDate='20230424', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27577.9', self.close='27558.8'
127.0.0.1 - - [24/Apr/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21556 

self.closeSec=1682294399, self.tradeDate='20230424', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27558.8', self.close='27576'
127.0.0.1 - - [24/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21557 

self.closeSec=1682294999, self.tradeDate='20230424', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27575.9', self.close='27559.3'
127.0.0.1 - - [24/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21558 

self.closeSec=1682295599, self.tradeDate='20230424', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27559.4', self.close='27509.5'
127.0.0.1 - - [24/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [24/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21554 

self.closeSec=1682292599, self.tradeDate='20230424', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27589.9', self.close='27613.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21555 

self.closeSec=1682293199, self.tradeDate='20230424', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27613.4', self.close='27577.9'
127.0.0.1 - - [24/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21556 

self.closeSec=1682293799, self.tradeDate='20230424', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27577.9', self.close='27558.8'
127.0.0.1 - - [24/Apr/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21557 

self.closeSec=1682294399, self.tradeDate='20230424', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27558.8', self.close='27576'
127.0.0.1 - - [24/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21558 

self.closeSec=1682294999, self.tradeDate='20230424', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27575.9', self.close='27559.3'
127.0.0.1 - - [24/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21559 

self.closeSec=1682295599, self.tradeDate='20230424', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27559.4', self.close='27509.5'
127.0.0.1 - - [24/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21554 

self.closeSec=1682292599, self.tradeDate='20230424', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27589.9', self.close='27613.5'
127.0.0.1 - - [24/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21555 

self.closeSec=1682293199, self.tradeDate='20230424', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27613.4', self.close='27577.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21556 

self.closeSec=1682293799, self.tradeDate='20230424', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27577.9', self.close='27558.8'
127.0.0.1 - - [24/Apr/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21557 

self.closeSec=1682294399, self.tradeDate='20230424', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27558.8', self.close='27576'
127.0.0.1 - - [24/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21558 

self.closeSec=1682294999, self.tradeDate='20230424', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27575.9', self.close='27559.3'
127.0.0.1 - - [24/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21559 

self.closeSec=1682295599, self.tradeDate='20230424', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27559.4', self.close='27509.5'
127.0.0.1 - - [24/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38547
self.closeSec=1682295599, self.tradeDate='20230424', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27546.5, self.close=27509.5, self.high=27554.1, self.low=27509.5, self.vol=1394.18, self.amt=38382240.9777 
127.0.0.1 - - [24/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-24 08:20:04,616:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230424   075500    075959  ...         0.0        0.0       0
5849  20230424   080000    080459  ...         0.0        0.0       0
5850  20230424   080500    080959  ...         0.0        0.0       0
5851  20230424   081000    081459  ...         0.0        0.0       0
5852  20230424   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 08:20:04,631:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682295599, self.tradeDate='20230424', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27546.5, self.close=27509.5, self.high=27554.1, self.low=27509.5, self.vol=1394.18, self.amt=38382240.9777, ukdf['pct'].iloc[-1]=-0.00134 , ukdf['amount'].iloc[-1]=38382240.9777, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38548
self.closeSec=1682295899, self.tradeDate='20230424', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27509.6, self.close=27482.7, self.high=27522.2, self.low=27463.6, self.vol=1824.172, self.amt=50149842.5085 
2023-04-24 08:25:01,562:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230424   080000    080459  ...         0.0        0.0       0
5850  20230424   080500    080959  ...         0.0        0.0       0
5851  20230424   081000    081459  ...         0.0        0.0       0
5852  20230424   081500    081959  ...         0.0        0.0       0
5853  20230424   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 08:25:01,563:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682295899, self.tradeDate='20230424', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27509.6, self.close=27482.7, self.high=27522.2, self.low=27463.6, self.vol=1824.172, self.amt=50149842.5085, ukdf['pct'].iloc[-1]=-0.000974 , ukdf['amount'].iloc[-1]=50149842.5085, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230423   200000    235959  1682265599  ...    719  1.054536  0.905609     1.0
720  20230424   000000    035959  1682279999  ...    720  1.042068  0.855422     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-42861.2136046047', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27453.72912302', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [24/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=898
self.closeSec=1682294399, self.tradeDate='20230424', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27453.3, self.close=27576.0, self.high=27642.6, self.low=27388.3, self.vol=37569.391, self.amt=1034168334.40928 
2023-04-24 08:00:03,084:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682294399, self.tradeDate='20230424', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27453.3, self.close=27576.0, self.high=27642.6, self.low=27388.3, self.vol=37569.391, self.amt=1034168334.40928 
2023-04-24 08:00:03,133:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230423   120000    155959  ...  32611.861  9.003692e+08  0.005787
718  20230423   160000    195959  ...  49943.657  1.378846e+09 -0.002592
719  20230423   200000    235959  ...  70478.522  1.940022e+09 -0.006246
720  20230424   000000    035959  ...  74820.167  2.056871e+09 -0.000251
721  20230424   040000    075959  ...  37569.391  1.034168e+09  0.004469

[5 rows x 11 columns]
2023-04-24 08:00:04,741:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230423   120000    155959  1682236799  ...    717  1.089573  1.040425     1.0
718  20230423   160000    195959  1682251199  ...    718  1.183101  1.241545     1.0
719  20230423   200000    235959  1682265599  ...    719  1.054536  0.905609     1.0
720  20230424   000000    035959  1682279999  ...    720  1.042068  0.855422     1.0
721  20230424   040000    075959  1682294399  ...    721  1.101631  0.980042     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-36379.5263898381', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27577.15456746', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


