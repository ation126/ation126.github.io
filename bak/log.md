# 20230928 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39412
self.closeSec=1695860399, self.tradeDate='20230928', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26406.3, self.close=26407.2, self.high=26435.0, self.low=26382.7, self.vol=2645.279, self.amt=69869965.0067 
127.0.0.1 - - [28/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-28 08:20:06,562:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230928   075500    075959  ...         0.0        0.0       0
5856  20230928   080000    080459  ...         0.0        0.0       0
5857  20230928   080500    080959  ...         0.0        0.0       0
5858  20230928   081000    081459  ...         0.0        0.0       0
5859  20230928   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 08:20:06,566:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695860399, self.tradeDate='20230928', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26406.3, self.close=26407.2, self.high=26435.0, self.low=26382.7, self.vol=2645.279, self.amt=69869965.0067, ukdf['pct'].iloc[-1]=8e-06 , ukdf['amount'].iloc[-1]=69869965.0067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6293.1594', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26413', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39413
self.closeSec=1695860699, self.tradeDate='20230928', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26404.8, self.close=26479.9, self.high=26500.0, self.low=26404.7, self.vol=4484.173, self.amt=118647583.1386 
2023-09-28 08:25:00,797:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230928   080000    080459  ...         0.0        0.0       0
5857  20230928   080500    080959  ...         0.0        0.0       0
5858  20230928   081000    081459  ...         0.0        0.0       0
5859  20230928   081500    081959  ...         0.0        0.0       0
5860  20230928   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 08:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695860699, self.tradeDate='20230928', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26404.8, self.close=26479.9, self.high=26500.0, self.low=26404.7, self.vol=4484.173, self.amt=118647583.1386, ukdf['pct'].iloc[-1]=0.002753 , ukdf['amount'].iloc[-1]=118647583.1386, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5369.12767504674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26479.35298901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [28/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39410 

self.closeSec=1695859199, self.tradeDate='20230928', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26352.7, self.close=26359.7, self.high=26359.7, self.low=26346.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39411 

self.closeSec=1695859499, self.tradeDate='20230928', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26359.6, self.close=26350.2, self.high=26369.9, self.low=26348.5 
127.0.0.1 - - [28/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39412 

self.closeSec=1695859799, self.tradeDate='20230928', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26350.1, self.close=26349.4, self.high=26354.0, self.low=26346.8 
127.0.0.1 - - [28/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39413 

self.closeSec=1695860099, self.tradeDate='20230928', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26349.5, self.close=26407.0, self.high=26410.7, self.low=26349.4 
127.0.0.1 - - [28/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39414 

self.closeSec=1695860399, self.tradeDate='20230928', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26406.3, self.close=26407.2, self.high=26435.0, self.low=26382.7 
127.0.0.1 - - [28/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39415 

self.closeSec=1695860699, self.tradeDate='20230928', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26404.8, self.close=26479.9, self.high=26500.0, self.low=26404.7 
127.0.0.1 - - [28/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-28 08:00:16,925:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230928    052959  26246.1  ...  48.750000  0.498882  0.574561
5770  20230928    055959  26293.9  ...  48.333333  0.492440  0.584755
5771  20230928    062959  26269.0  ...  48.750000  0.503134  0.590852
5772  20230928    065959  26309.0  ...  48.750000  0.506575  0.595434
5773  20230928    072959  26322.3  ...  48.750000  0.500222  0.601702

[5 rows x 33 columns]
0.5425925925925926
acc is : 0.5425925925925926
2023-09-28 08:00:16,987:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.507623  0.492377       0  ...  0.957865  -1.0    0.0  0.989207
536     1  0.481922  0.518078       1  ...  0.956370  -1.0    0.0  0.990751
537     0  0.504874  0.495126       1  ...  0.955886  -1.0    0.0  0.991252
538     1  0.496872  0.503128       0  ...  0.956754  -1.0    0.0  0.990352
539     1  0.485314  0.514686       1  ...  0.954524  -1.0    0.0  0.992660

[5 rows x 10 columns]
2023-09-28 08:00:16,998:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508477  0.491523       0  ...  0.957865  -1.0    0.0  0.991481
46     1  0.482637  0.517363       1  ...  0.956370  -1.0    0.0  0.993040
47     0  0.505337  0.494663       1  ...  0.955886  -1.0    0.0  0.992774
48     1  0.497181  0.502819       0  ...  0.956754  -1.0    0.0  0.991323
49     1  0.485314  0.514686       1  ...  0.954524  -1.0    0.0  0.992660

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.231', 'enterprice': '26175', 'countrevence': '0', 'unrealprofit': '-4825.65134849181', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26358.96749451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19703 

self.closeSec=1695857399, self.tradeDate='20230928', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26290.1', self.close='26298.4'
127.0.0.1 - - [28/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19704 

self.closeSec=1695857999, self.tradeDate='20230928', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26298.3', self.close='26349.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19705 

self.closeSec=1695858599, self.tradeDate='20230928', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26349', self.close='26347.5'
127.0.0.1 - - [28/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19706 

self.closeSec=1695859199, self.tradeDate='20230928', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26347.4', self.close='26359.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19707 

self.closeSec=1695859799, self.tradeDate='20230928', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26359.6', self.close='26349.4'
127.0.0.1 - - [28/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19708 

self.closeSec=1695860399, self.tradeDate='20230928', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26349.5', self.close='26407.2'
127.0.0.1 - - [28/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19706 

self.closeSec=1695857399, self.tradeDate='20230928', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26290.1', self.close='26298.4'
127.0.0.1 - - [28/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19707 

self.closeSec=1695857999, self.tradeDate='20230928', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26298.3', self.close='26349.3'

--handleKline--: 127.0.0.1 - - [28/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19708 

self.closeSec=1695858599, self.tradeDate='20230928', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26349', self.close='26347.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19709 

self.closeSec=1695859199, self.tradeDate='20230928', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26347.4', self.close='26359.7'
127.0.0.1 - - [28/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19710 

self.closeSec=1695859799, self.tradeDate='20230928', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26359.6', self.close='26349.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19711 

self.closeSec=1695860399, self.tradeDate='20230928', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26349.5', self.close='26407.2'
127.0.0.1 - - [28/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19706 

self.closeSec=1695857399, self.tradeDate='20230928', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26290.1', self.close='26298.4'
127.0.0.1 - - [28/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19707 

self.closeSec=1695857999, self.tradeDate='20230928', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26298.3', self.close='26349.3'
127.0.0.1 - - [28/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19708 

self.closeSec=1695858599, self.tradeDate='20230928', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26349', self.close='26347.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19709 

self.closeSec=1695859199, self.tradeDate='20230928', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26347.4', self.close='26359.7'
127.0.0.1 - - [28/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19710 

self.closeSec=1695859799, self.tradeDate='20230928', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26359.6', self.close='26349.4'
127.0.0.1 - - [28/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19711 

self.closeSec=1695860399, self.tradeDate='20230928', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26349.5', self.close='26407.2'
127.0.0.1 - - [28/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39412
self.closeSec=1695860399, self.tradeDate='20230928', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26406.3, self.close=26407.2, self.high=26435.0, self.low=26382.7, self.vol=2645.279, self.amt=69869965.0067 
127.0.0.1 - - [28/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-28 08:20:06,557:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230928   075500    075959  ...         0.0        0.0       0
5856  20230928   080000    080459  ...         0.0        0.0       0
5857  20230928   080500    080959  ...         0.0        0.0       0
5858  20230928   081000    081459  ...         0.0        0.0       0
5859  20230928   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 08:20:06,565:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695860399, self.tradeDate='20230928', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26406.3, self.close=26407.2, self.high=26435.0, self.low=26382.7, self.vol=2645.279, self.amt=69869965.0067, ukdf['pct'].iloc[-1]=8e-06 , ukdf['amount'].iloc[-1]=69869965.0067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-16007.771', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26413', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [28/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39413
self.closeSec=1695860699, self.tradeDate='20230928', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26404.8, self.close=26479.9, self.high=26500.0, self.low=26404.7, self.vol=4484.173, self.amt=118647583.1386 
2023-09-28 08:25:00,800:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230928   080000    080459  ...         0.0        0.0       0
5857  20230928   080500    080959  ...         0.0        0.0       0
5858  20230928   081000    081459  ...         0.0        0.0       0
5859  20230928   081500    081959  ...         0.0        0.0       0
5860  20230928   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 08:25:00,800:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695860699, self.tradeDate='20230928', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26404.8, self.close=26479.9, self.high=26500.0, self.low=26404.7, self.vol=4484.173, self.amt=118647583.1386, ukdf['pct'].iloc[-1]=0.002753 , ukdf['amount'].iloc[-1]=118647583.1386, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-13543.35463517959', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26479.35298901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230927   200000    235959  1695830399  ...    719  0.070100 -1.344874    -1.0
720  20230928   000000    035959  1695844799  ...    720  0.074724 -1.326279    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-5567.9332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26258.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=821
self.closeSec=1695859199, self.tradeDate='20230928', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26258.6, self.close=26359.7, self.high=26374.9, self.low=26211.6, self.vol=22069.03, self.amt=580262187.019 
127.0.0.1 - - [28/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-28 08:00:01,535:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695859199, self.tradeDate='20230928', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26258.6, self.close=26359.7, self.high=26374.9, self.low=26211.6, self.vol=22069.03, self.amt=580262187.019 
2023-09-28 08:00:01,551:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230927   120000    155959  ...   10642.269  2.792936e+08 -0.001275
718  20230927   160000    195959  ...  109986.918  2.917954e+09  0.019879
719  20230927   200000    235959  ...  148743.729  3.936224e+09 -0.017249
720  20230928   000000    035959  ...   42907.809  1.125090e+09 -0.001438
721  20230928   040000    075959  ...   22069.030  5.802622e+08  0.003965

[5 rows x 11 columns]
2023-09-28 08:00:02,254:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230927   120000    155959  1695801599  ...    717  0.261979 -0.872222    -1.0
718  20230927   160000    195959  1695815999  ...    718  0.172633 -1.097239    -1.0
719  20230927   200000    235959  1695830399  ...    719  0.070100 -1.344874    -1.0
720  20230928   000000    035959  1695844799  ...    720  0.074724 -1.326279    -1.0
721  20230928   040000    075959  1695859199  ...    721  0.066771 -1.337522    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-10694.2892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26359.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


