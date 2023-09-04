# 20230905 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32692
self.closeSec=1693844399, self.tradeDate='20230905', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25824.6, self.close=25810.6, self.high=25836.5, self.low=25806.6, self.vol=560.008, self.amt=14458914.5393 
127.0.0.1 - - [05/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-09-05 00:20:05,261:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230904   235500    235959  ...         0.0        0.0       0
5748  20230905   000000    000459  ...         0.0        0.0       0
5749  20230905   000500    000959  ...         0.0        0.0       0
5750  20230905   001000    001459  ...         0.0        0.0       0
5751  20230905   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 00:20:05,264:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693844399, self.tradeDate='20230905', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25824.6, self.close=25810.6, self.high=25836.5, self.low=25806.6, self.vol=560.008, self.amt=14458914.5393, ukdf['pct'].iloc[-1]=-0.000542 , ukdf['amount'].iloc[-1]=14458914.5393, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14683.5744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25810.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32693
self.closeSec=1693844699, self.tradeDate='20230905', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25810.6, self.close=25842.4, self.high=25849.1, self.low=25794.9, self.vol=622.772, self.amt=16078563.1997 
2023-09-05 00:25:00,775:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230905   000000    000459  ...         0.0        0.0       0
5749  20230905   000500    000959  ...         0.0        0.0       0
5750  20230905   001000    001459  ...         0.0        0.0       0
5751  20230905   001500    001959  ...         0.0        0.0       0
5752  20230905   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 00:25:00,775:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693844699, self.tradeDate='20230905', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25810.6, self.close=25842.4, self.high=25849.1, self.low=25794.9, self.vol=622.772, self.amt=16078563.1997, ukdf['pct'].iloc[-1]=0.001232 , ukdf['amount'].iloc[-1]=16078563.1997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14234.30995302228', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25842.76083922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1693843499, self.tradeDate='20230905', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=25803.9, self.close=25817.4, self.high=25824.1, self.low=25797.3 

--ukdf-hist--: overDate='20230831' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32692 

self.closeSec=1693843799, self.tradeDate='20230905', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25817.5, self.close=25853.5, self.high=25869.0, self.low=25815.3 
127.0.0.1 - - [05/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32693127.0.0.1 - - [05/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -
 

self.closeSec=1693844099, self.tradeDate='20230905', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25850.3, self.close=25824.6, self.high=25854.9, self.low=25822.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32694 

self.closeSec=1693844399, self.tradeDate='20230905', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25824.6, self.close=25810.6, self.high=25836.5, self.low=25806.6 
127.0.0.1 - - [05/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32695 

self.closeSec=1693844699, self.tradeDate='20230905', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25810.6, self.close=25842.4, self.high=25849.1, self.low=25794.9 
127.0.0.1 - - [05/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-05 00:00:18,498:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230904    212959  25845.1  ...  44.166667  0.484315  0.595283
5802  20230904    215959  25892.3  ...  44.166667  0.476143  0.609800
5803  20230904    222959  25870.9  ...  44.166667  0.473602  0.624723
5804  20230904    225959  25864.1  ...  44.166667  0.464465  0.643612
5805  20230904    232959  25839.9  ...  43.750000  0.452323  0.651877

[5 rows x 33 columns]
0.5091911764705882
acc is : 0.5091911764705882
2023-09-05 00:00:18,552:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.499729  0.500271       0  ...  1.000800  -1.0    0.0  0.977707
540     1  0.481967  0.518033       0  ...  1.001059  -1.0    0.0  0.977453
541     1  0.485715  0.514285       0  ...  1.001996  -1.0    0.0  0.976539
542     1  0.479892  0.520108       0  ...  1.003275  -1.0    0.0  0.975292
543     1  0.474739  0.525261       0  ...  1.003392  -1.0    0.0  0.975178

[5 rows x 10 columns]
2023-09-05 00:00:18,563:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499978  0.500022       0  ...  1.000800  -1.0    0.0  0.979317
46     1  0.481978  0.518022       0  ...  1.001059  -1.0    0.0  0.978363
47     1  0.485403  0.514597       0  ...  1.001996  -1.0    0.0  0.975915
48     1  0.480050  0.519950       0  ...  1.003275  -1.0    0.0  0.974669
49     1  0.474739  0.525261       0  ...  1.003392  -1.0    0.0  0.975178

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '23197.7743599', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25799.4127', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16343 

self.closeSec=1693841399, self.tradeDate='20230904', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25747.1', self.close='25807'
127.0.0.1 - - [04/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16344 

self.closeSec=1693841999, self.tradeDate='20230904', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25806.9', self.close='25856.6'
127.0.0.1 - - [04/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16345 

self.closeSec=1693842599, self.tradeDate='20230904', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25856.6', self.close='25800.9'
127.0.0.1 - - [05/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16346 

self.closeSec=1693843199, self.tradeDate='20230904', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25801', self.close='25803.9'
127.0.0.1 - - [05/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16347 

self.closeSec=1693843799, self.tradeDate='20230905', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25803.9', self.close='25850.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16348 

self.closeSec=1693844399, self.tradeDate='20230905', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25850.3', self.close='25810.6'
127.0.0.1 - - [05/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [04/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16346 

self.closeSec=1693841399, self.tradeDate='20230904', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25747.1', self.close='25807'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16347 

self.closeSec=1693841999, self.tradeDate='20230904', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25806.9', self.close='25856.6'
127.0.0.1 - - [04/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16348 

self.closeSec=1693842599, self.tradeDate='20230904', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25856.6', self.close='25800.9'
127.0.0.1 - - [04/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16349 

self.closeSec=1693843199, self.tradeDate='20230904', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25801', self.close='25803.9'
127.0.0.1 - - [05/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16350 

self.closeSec=1693843799, self.tradeDate='20230905', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25803.9', self.close='25850.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16351 

self.closeSec=1693844399, self.tradeDate='20230905', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25850.3', self.close='25810.6'
127.0.0.1 - - [05/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16346 

self.closeSec=1693841399, self.tradeDate='20230904', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25747.1', self.close='25807'
127.0.0.1 - - [04/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16347 

self.closeSec=1693841999, self.tradeDate='20230904', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25806.9', self.close='25856.6'
127.0.0.1 - - [04/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16348 

self.closeSec=1693842599, self.tradeDate='20230904', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25856.6', self.close='25800.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16349 

self.closeSec=1693843199, self.tradeDate='20230904', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25801', self.close='25803.9'
127.0.0.1 - - [05/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16350 

self.closeSec=1693843799, self.tradeDate='20230905', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25803.9', self.close='25850.2'
127.0.0.1 - - [05/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16351 

self.closeSec=1693844399, self.tradeDate='20230905', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25850.3', self.close='25810.6'
127.0.0.1 - - [05/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32692
self.closeSec=1693844399, self.tradeDate='20230905', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25824.6, self.close=25810.6, self.high=25836.5, self.low=25806.6, self.vol=560.008, self.amt=14458914.5393 
127.0.0.1 - - [05/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-09-05 00:20:05,258:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230904   235500    235959  ...         0.0        0.0       0
5748  20230905   000000    000459  ...         0.0        0.0       0
5749  20230905   000500    000959  ...         0.0        0.0       0
5750  20230905   001000    001459  ...         0.0        0.0       0
5751  20230905   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 00:20:05,262:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693844399, self.tradeDate='20230905', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25824.6, self.close=25810.6, self.high=25836.5, self.low=25806.6, self.vol=560.008, self.amt=14458914.5393, ukdf['pct'].iloc[-1]=-0.000542 , ukdf['amount'].iloc[-1]=14458914.5393, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38385.2235', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25810.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32693
self.closeSec=1693844699, self.tradeDate='20230905', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25810.6, self.close=25842.4, self.high=25849.1, self.low=25794.9, self.vol=622.772, self.amt=16078563.1997 
2023-09-05 00:25:00,779:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230905   000000    000459  ...         0.0        0.0       0
5749  20230905   000500    000959  ...         0.0        0.0       0
5750  20230905   001000    001459  ...         0.0        0.0       0
5751  20230905   001500    001959  ...         0.0        0.0       0
5752  20230905   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 00:25:00,779:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693844699, self.tradeDate='20230905', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25810.6, self.close=25842.4, self.high=25849.1, self.low=25794.9, self.vol=622.772, self.amt=16078563.1997, ukdf['pct'].iloc[-1]=0.001232 , ukdf['amount'].iloc[-1]=16078563.1997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37187.02367052998', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25842.76083922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230904   120000    155959  1693814399  ...    723  0.755318  0.994791     1.0
724  20230904   160000    195959  1693828799  ...    724  0.824849  1.177341     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-112231.0956', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25873.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [05/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=681
self.closeSec=1693843199, self.tradeDate='20230904', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25877.9, self.close=25803.9, self.high=25961.5, self.low=25707.5, self.vol=53696.797, self.amt=1386592227.9635 
2023-09-05 00:00:01,601:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693843199, self.tradeDate='20230904', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25877.9, self.close=25803.9, self.high=25961.5, self.low=25707.5, self.vol=53696.797, self.amt=1386592227.9635 
2023-09-05 00:00:01,622:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230904   040000    075959  ...  25287.093  6.575943e+08 -0.001366
722  20230904   080000    115959  ...  22003.637  5.712652e+08  0.000462
723  20230904   120000    155959  ...  14593.385  3.788325e+08 -0.000782
724  20230904   160000    195959  ...  20972.285  5.434324e+08 -0.002921
725  20230904   200000    235959  ...  53696.797  1.386592e+09 -0.002863

[5 rows x 11 columns]
2023-09-05 00:00:02,596:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230904   040000    075959  1693785599  ...    721  0.751855  1.007003     1.0
722  20230904   080000    115959  1693799999  ...    722  0.745069  0.976513     1.0
723  20230904   120000    155959  1693814399  ...    723  0.755318  0.994791     1.0
724  20230904   160000    195959  1693828799  ...    724  0.824849  1.177341     1.0
725  20230904   200000    235959  1693843199  ...    725  0.426232  0.042741     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-116215.8348', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25803.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


