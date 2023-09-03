# 20230904 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32404
self.closeSec=1693757999, self.tradeDate='20230904', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25862.5, self.close=25879.3, self.high=25884.0, self.low=25862.5, self.vol=377.713, self.amt=9773242.382 
127.0.0.1 - - [04/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-04 00:20:05,968:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230903   235500    235959  ...         0.0        0.0       0
5748  20230904   000000    000459  ...         0.0        0.0       0
5749  20230904   000500    000959  ...         0.0        0.0       0
5750  20230904   001000    001459  ...         0.0        0.0       0
5751  20230904   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 00:20:05,978:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693757999, self.tradeDate='20230904', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25862.5, self.close=25879.3, self.high=25884.0, self.low=25862.5, self.vol=377.713, self.amt=9773242.382, ukdf['pct'].iloc[-1]=0.000646 , ukdf['amount'].iloc[-1]=9773242.382, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13694.84972641566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25881.49846859', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32405
self.closeSec=1693758299, self.tradeDate='20230904', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25879.4, self.close=25861.5, self.high=25881.9, self.low=25859.2, self.vol=284.303, self.amt=7354743.3343 
2023-09-04 00:25:00,802:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230904   000000    000459  ...         0.0        0.0       0
5749  20230904   000500    000959  ...         0.0        0.0       0
5750  20230904   001000    001459  ...         0.0        0.0       0
5751  20230904   001500    001959  ...         0.0        0.0       0
5752  20230904   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 00:25:00,803:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693758299, self.tradeDate='20230904', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25879.4, self.close=25861.5, self.high=25881.9, self.low=25859.2, self.vol=284.303, self.amt=7354743.3343, ukdf['pct'].iloc[-1]=-0.000688 , ukdf['amount'].iloc[-1]=7354743.3343, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13971.9558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25861.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1693757099, self.tradeDate='20230904', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=25858.2, self.close=25861.1, self.high=25861.1, self.low=25830.0 

--ukdf-hist--: overDate='20230830' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [04/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32404 

self.closeSec=1693757399, self.tradeDate='20230904', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25861.1, self.close=25858.3, self.high=25869.0, self.low=25840.0 
127.0.0.1 - - [04/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32405 

self.closeSec=1693757699, self.tradeDate='20230904', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25858.2, self.close=25862.6, self.high=25867.4, self.low=25858.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32406 

self.closeSec=1693757999, self.tradeDate='20230904', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25862.5, self.close=25879.3, self.high=25884.0, self.low=25862.5 
127.0.0.1 - - [04/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32407 

self.closeSec=1693758299, self.tradeDate='20230904', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25879.4, self.close=25861.5, self.high=25881.9, self.low=25859.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-04 00:00:17,717:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230903    212959  25883.4  ...  46.250000  0.494670  0.395492
5802  20230903    215959  25923.0  ...  45.833333  0.478168  0.412942
5803  20230903    222959  25875.6  ...  45.833333  0.480789  0.427946
5804  20230903    225959  25882.7  ...  45.833333  0.492712  0.440133
5805  20230903    232959  25914.8  ...  45.833333  0.483951  0.458020

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-09-04 00:00:17,779:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.503448  0.496552       0  ...  1.002586  -1.0    0.0  0.993488
540     1  0.477378  0.522622       1  ...  1.002314  -1.0    0.0  0.993757
541     1  0.490481  0.509519       1  ...  1.001071  -1.0    0.0  0.994989
542     0  0.500083  0.499917       0  ...  1.002029  -1.0    0.0  0.994037
543     1  0.486596  0.513404       0  ...  1.003260  -1.0    0.0  0.992816

[5 rows x 10 columns]
2023-09-04 00:00:17,791:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503695  0.496305       0  ...  1.002586  -1.0    0.0  0.993801
46     1  0.477383  0.522617       1  ...  1.002314  -1.0    0.0  0.993635
47     1  0.490148  0.509852       1  ...  1.001071  -1.0    0.0  0.993140
48     1  0.499619  0.500381       0  ...  1.002029  -1.0    0.0  0.992190
49     1  0.486596  0.513404       0  ...  1.003260  -1.0    0.0  0.992816

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '21612.95494415288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25859.75688824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16199 

self.closeSec=1693754999, self.tradeDate='20230903', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25896.2', self.close='25890'
127.0.0.1 - - [03/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16200 

self.closeSec=1693755599, self.tradeDate='20230903', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25889.9', self.close='25848.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16201 

self.closeSec=1693756199, self.tradeDate='20230903', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25847.5', self.close='25845.1'
127.0.0.1 - - [03/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16202 

self.closeSec=1693756799, self.tradeDate='20230903', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25845.1', self.close='25858.2'
127.0.0.1 - - [04/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16203 

self.closeSec=1693757399, self.tradeDate='20230904', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25858.2', self.close='25858.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16204 

self.closeSec=1693757999, self.tradeDate='20230904', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25858.2', self.close='25879.3'
127.0.0.1 - - [04/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [03/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16202 

self.closeSec=1693754999, self.tradeDate='20230903', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25896.2', self.close='25890'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16203 

self.closeSec=1693755599, self.tradeDate='20230903', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25889.9', self.close='25848.4'
127.0.0.1 - - [03/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16204 

self.closeSec=1693756199, self.tradeDate='20230903', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25847.5', self.close='25845.1'
127.0.0.1 - - [03/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16205 

self.closeSec=1693756799, self.tradeDate='20230903', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25845.1', self.close='25858.2'
127.0.0.1 - - [04/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16206 

self.closeSec=1693757399, self.tradeDate='20230904', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25858.2', self.close='25858.3'
127.0.0.1 - - [04/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16207 

self.closeSec=1693757999, self.tradeDate='20230904', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25858.2', self.close='25879.3'
127.0.0.1 - - [04/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16202 

self.closeSec=1693754999, self.tradeDate='20230903', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25896.2', self.close='25890'
127.0.0.1 - - [03/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16203 

self.closeSec=1693755599, self.tradeDate='20230903', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25889.9', self.close='25848.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16204 

self.closeSec=1693756199, self.tradeDate='20230903', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25847.5', self.close='25845.1'
127.0.0.1 - - [03/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16205 

self.closeSec=1693756799, self.tradeDate='20230903', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25845.1', self.close='25858.2'
127.0.0.1 - - [04/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16206 

self.closeSec=1693757399, self.tradeDate='20230904', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25858.2', self.close='25858.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16207 

self.closeSec=1693757999, self.tradeDate='20230904', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25858.2', self.close='25879.3'
127.0.0.1 - - [04/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32404
self.closeSec=1693757999, self.tradeDate='20230904', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25862.5, self.close=25879.3, self.high=25884.0, self.low=25862.5, self.vol=377.713, self.amt=9773242.382 
127.0.0.1 - - [04/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-04 00:20:05,967:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230903   235500    235959  ...         0.0        0.0       0
5748  20230904   000000    000459  ...         0.0        0.0       0
5749  20230904   000500    000959  ...         0.0        0.0       0
5750  20230904   001000    001459  ...         0.0        0.0       0
5751  20230904   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 00:20:05,969:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693757999, self.tradeDate='20230904', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25862.5, self.close=25879.3, self.high=25884.0, self.low=25862.5, self.vol=377.713, self.amt=9773242.382, ukdf['pct'].iloc[-1]=0.000646 , ukdf['amount'].iloc[-1]=9773242.382, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35748.26937809881', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25881.49846859', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32405
self.closeSec=1693758299, self.tradeDate='20230904', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25879.4, self.close=25861.5, self.high=25881.9, self.low=25859.2, self.vol=284.303, self.amt=7354743.3343 
127.0.0.1 - - [04/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-04 00:25:00,801:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230904   000000    000459  ...         0.0        0.0       0
5749  20230904   000500    000959  ...         0.0        0.0       0
5750  20230904   001000    001459  ...         0.0        0.0       0
5751  20230904   001500    001959  ...         0.0        0.0       0
5752  20230904   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 00:25:00,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693758299, self.tradeDate='20230904', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25879.4, self.close=25861.5, self.high=25881.9, self.low=25859.2, self.vol=284.303, self.amt=7354743.3343, ukdf['pct'].iloc[-1]=-0.000688 , ukdf['amount'].iloc[-1]=7354743.3343, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36487.3184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25861.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230903   120000    155959  1693727999  ...    723  0.789376  1.178070     1.0
724  20230903   160000    195959  1693742399  ...    724  0.814755  1.234112     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-108760.65296008692', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25934.11696779', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [04/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=675
self.closeSec=1693756799, self.tradeDate='20230903', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25930.5, self.close=25858.2, self.high=26115.0, self.low=25802.8, self.vol=42781.009, self.amt=1109221501.50916 
2023-09-04 00:00:01,589:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693756799, self.tradeDate='20230903', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25930.5, self.close=25858.2, self.high=26115.0, self.low=25802.8, self.vol=42781.009, self.amt=1109221501.50916 
2023-09-04 00:00:01,606:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230903   040000    075959  ...   9378.742  2.424156e+08  0.001328
722  20230903   080000    115959  ...  10366.408  2.680259e+08 -0.000228
723  20230903   120000    155959  ...  11059.332  2.864283e+08  0.003536
724  20230903   160000    195959  ...  11620.082  3.009666e+08 -0.000420
725  20230903   200000    235959  ...  42781.009  1.109222e+09 -0.002788

[5 rows x 11 columns]
2023-09-04 00:00:02,432:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230903   040000    075959  1693699199  ...    721  0.829327  1.340573     1.0
722  20230903   080000    115959  1693713599  ...    722  0.819361  1.286562     1.0
723  20230903   120000    155959  1693727999  ...    723  0.789376  1.178070     1.0
724  20230903   160000    195959  1693742399  ...    724  0.814755  1.234112     1.0
725  20230903   200000    235959  1693756799  ...    725  0.810581  1.203812     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-113020.95549411732', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25859.70380259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


