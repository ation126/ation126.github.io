# 20230824 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29332
self.closeSec=1692836399, self.tradeDate='20230824', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26454.4, self.close=26459.9, self.high=26471.5, self.low=26446.9, self.vol=419.77, self.amt=11108055.9349 
127.0.0.1 - - [24/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-24 08:20:05,162:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230824   075500    075959  ...         0.0        0.0       0
5844  20230824   080000    080459  ...         0.0        0.0       0
5845  20230824   080500    080959  ...         0.0        0.0       0
5846  20230824   081000    081459  ...         0.0        0.0       0
5847  20230824   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 08:20:05,171:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692836399, self.tradeDate='20230824', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26454.4, self.close=26459.9, self.high=26471.5, self.low=26446.9, self.vol=419.77, self.amt=11108055.9349, ukdf['pct'].iloc[-1]=0.000208 , ukdf['amount'].iloc[-1]=11108055.9349, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5629.0949225313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26460.68522745', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29333
self.closeSec=1692836699, self.tradeDate='20230824', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26459.9, self.close=26485.2, self.high=26485.2, self.low=26445.2, self.vol=635.399, self.amt=16817832.6438 
127.0.0.1 - - [24/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-24 08:25:00,781:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230824   080000    080459  ...         0.0        0.0       0
5845  20230824   080500    080959  ...         0.0        0.0       0
5846  20230824   081000    081459  ...         0.0        0.0       0
5847  20230824   081500    081959  ...         0.0        0.0       0
5848  20230824   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 08:25:00,782:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692836699, self.tradeDate='20230824', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26459.9, self.close=26485.2, self.high=26485.2, self.low=26445.2, self.vol=635.399, self.amt=16817832.6438, ukdf['pct'].iloc[-1]=0.000956 , ukdf['amount'].iloc[-1]=16817832.6438, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5289.0948', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26485.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [24/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29330 

self.closeSec=1692835199, self.tradeDate='20230824', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26398.4, self.close=26419.2, self.high=26429.7, self.low=26396.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29331 

self.closeSec=1692835499, self.tradeDate='20230824', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26419.2, self.close=26434.5, self.high=26442.2, self.low=26411.6 
127.0.0.1 - - [24/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29332 

self.closeSec=1692835799, self.tradeDate='20230824', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26434.5, self.close=26454.9, self.high=26460.5, self.low=26426.6 
127.0.0.1 - - [24/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29333 

self.closeSec=1692836099, self.tradeDate='20230824', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26454.8, self.close=26454.4, self.high=26468.7, self.low=26448.0 
127.0.0.1 - - [24/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29334 

self.closeSec=1692836399, self.tradeDate='20230824', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26454.4, self.close=26459.9, self.high=26471.5, self.low=26446.9 
127.0.0.1 - - [24/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29335 

self.closeSec=1692836699, self.tradeDate='20230824', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26459.9, self.close=26485.2, self.high=26485.2, self.low=26445.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-24 08:00:19,819:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230824    052959  26578.2  ...  52.083333  0.605241  0.193288
5770  20230824    055959  26558.0  ...  52.083333  0.541454  0.213510
5771  20230824    062959  26306.3  ...  52.083333  0.559094  0.226182
5772  20230824    065959  26398.4  ...  52.500000  0.566457  0.235324
5773  20230824    072959  26440.5  ...  52.916667  0.572945  0.241465

[5 rows x 33 columns]
0.5370370370370371
acc is : 0.5370370370370371
2023-08-24 08:00:19,906:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
535     0  0.502348  0.497652       0  ...  1.029864   1.0  0.0000  0.893432
536     1  0.405241  0.594759       1  ...  1.024552  -1.0 -0.0016  0.896611
537     0  0.514422  0.485578       1  ...  1.022980  -1.0  0.0000  0.897987
538     1  0.493804  0.506196       1  ...  1.021583  -1.0  0.0000  0.899213
539     0  0.503928  0.496072       0  ...  1.023798  -1.0  0.0000  0.897263

[5 rows x 10 columns]
2023-08-24 08:00:19,920:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.502211  0.497789       0  ...  1.029864   1.0  0.0000  0.893578
46     1  0.405384  0.594616       1  ...  1.024552  -1.0 -0.0016  0.897166
47     0  0.514511  0.485489       1  ...  1.022980  -1.0  0.0000  0.897319
48     1  0.493828  0.506172       1  ...  1.021583  -1.0  0.0000  0.899176
49     0  0.503928  0.496072       0  ...  1.023798  -1.0  0.0000  0.897263

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '-671.8978', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26425.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14663 

self.closeSec=1692833399, self.tradeDate='20230824', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26504.4', self.close='26476.6'
127.0.0.1 - - [24/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14664 

self.closeSec=1692833999, self.tradeDate='20230824', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26476.5', self.close='26440.7'
127.0.0.1 - - [24/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14665 

self.closeSec=1692834599, self.tradeDate='20230824', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26440.7', self.close='26437.4'
127.0.0.1 - - [24/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [24/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14666 

self.closeSec=1692835199, self.tradeDate='20230824', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26437.4', self.close='26419.2'
127.0.0.1 - - [24/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14667 

self.closeSec=1692835799, self.tradeDate='20230824', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26419.2', self.close='26454.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14668 

self.closeSec=1692836399, self.tradeDate='20230824', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26454.8', self.close='26459.8'
127.0.0.1 - - [24/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14666 

self.closeSec=1692833399, self.tradeDate='20230824', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26504.4', self.close='26476.6'
127.0.0.1 - - [24/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14667 

self.closeSec=1692833999, self.tradeDate='20230824', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26476.5', self.close='26440.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14668 

self.closeSec=1692834599, self.tradeDate='20230824', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26440.7', self.close='26437.4'
127.0.0.1 - - [24/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [24/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14669 

self.closeSec=1692835199, self.tradeDate='20230824', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26437.4', self.close='26419.2'
127.0.0.1 - - [24/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14670 

self.closeSec=1692835799, self.tradeDate='20230824', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26419.2', self.close='26454.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14671 

self.closeSec=1692836399, self.tradeDate='20230824', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26454.8', self.close='26459.8'
127.0.0.1 - - [24/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14666 

self.closeSec=1692833399, self.tradeDate='20230824', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26504.4', self.close='26476.6'
127.0.0.1 - - [24/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14667 

self.closeSec=1692833999, self.tradeDate='20230824', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26476.5', self.close='26440.7'
127.0.0.1 - - [24/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14668 

self.closeSec=1692834599, self.tradeDate='20230824', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26440.7', self.close='26437.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14669 

self.closeSec=1692835199, self.tradeDate='20230824', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26437.4', self.close='26419.2'
127.0.0.1 - - [24/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14670 

self.closeSec=1692835799, self.tradeDate='20230824', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26419.2', self.close='26454.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14671 

self.closeSec=1692836399, self.tradeDate='20230824', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26454.8', self.close='26459.8'
127.0.0.1 - - [24/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29332
self.closeSec=1692836399, self.tradeDate='20230824', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26454.4, self.close=26459.9, self.high=26471.5, self.low=26446.9, self.vol=419.77, self.amt=11108055.9349 
127.0.0.1 - - [24/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-24 08:20:05,158:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230824   075500    075959  ...         0.0        0.0       0
5844  20230824   080000    080459  ...         0.0        0.0       0
5845  20230824   080500    080959  ...         0.0        0.0       0
5846  20230824   081000    081459  ...         0.0        0.0       0
5847  20230824   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 08:20:05,160:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692836399, self.tradeDate='20230824', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26454.4, self.close=26459.9, self.high=26471.5, self.low=26446.9, self.vol=419.77, self.amt=11108055.9349, ukdf['pct'].iloc[-1]=0.000208 , ukdf['amount'].iloc[-1]=11108055.9349, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14236.69396727955', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26460.68522745', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29333
self.closeSec=1692836699, self.tradeDate='20230824', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26459.9, self.close=26485.2, self.high=26485.2, self.low=26445.2, self.vol=635.399, self.amt=16817832.6438 
127.0.0.1 - - [24/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-24 08:25:00,796:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230824   080000    080459  ...         0.0        0.0       0
5845  20230824   080500    080959  ...         0.0        0.0       0
5846  20230824   081000    081459  ...         0.0        0.0       0
5847  20230824   081500    081959  ...         0.0        0.0       0
5848  20230824   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 08:25:00,797:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692836699, self.tradeDate='20230824', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26459.9, self.close=26485.2, self.high=26485.2, self.low=26445.2, self.vol=635.399, self.amt=16817832.6438, ukdf['pct'].iloc[-1]=0.000956 , ukdf['amount'].iloc[-1]=16817832.6438, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-13329.9049', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26485.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230823   200000    235959  1692806399  ...    719  0.012680 -1.068013    -1.0
720  20230824   000000    035959  1692820799  ...    720  0.025848 -1.019798    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '144888.466', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26613.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=611
self.closeSec=1692835199, self.tradeDate='20230824', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26615.2, self.close=26419.2, self.high=26714.8, self.low=26201.0, self.vol=70672.879, self.amt=1870823816.42794 
127.0.0.1 - - [24/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-24 08:00:01,559:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692835199, self.tradeDate='20230824', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26615.2, self.close=26419.2, self.high=26714.8, self.low=26201.0, self.vol=70672.879, self.amt=1870823816.42794 
2023-08-24 08:00:01,572:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230823   120000    155959  ...   36125.446  9.412892e+08  0.002047
718  20230823   160000    195959  ...   31581.275  8.203121e+08 -0.004500
719  20230823   200000    235959  ...   89252.364  2.321153e+09  0.007953
720  20230824   000000    035959  ...  149537.665  3.958385e+09  0.018401
721  20230824   040000    075959  ...   70672.879  1.870824e+09 -0.007364

[5 rows x 11 columns]
2023-08-24 08:00:02,217:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230823   120000    155959  1692777599  ...    717  0.020046 -1.058495    -1.0
718  20230823   160000    195959  1692791999  ...    718  0.015548 -1.068225    -1.0
719  20230823   200000    235959  1692806399  ...    719  0.012680 -1.068013    -1.0
720  20230824   000000    035959  1692820799  ...    720  0.025848 -1.019798    -1.0
721  20230824   040000    075959  1692835199  ...    721  0.066786 -0.908375    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '154723.94259115844', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26421.70363137', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


