# 20230927 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39028
self.closeSec=1695745199, self.tradeDate='20230927', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26174.3, self.close=26182.2, self.high=26197.1, self.low=26174.3, self.vol=1142.915, self.amt=29929709.8634 
127.0.0.1 - - [27/Sep/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-09-27 00:20:06,661:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230926   235500    235959  ...         0.0        0.0       0
5760  20230927   000000    000459  ...         0.0        0.0       0
5761  20230927   000500    000959  ...         0.0        0.0       0
5762  20230927   001000    001459  ...         0.0        0.0       0
5763  20230927   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 00:20:06,666:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695745199, self.tradeDate='20230927', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26174.3, self.close=26182.2, self.high=26197.1, self.low=26174.3, self.vol=1142.915, self.amt=29929709.8634, ukdf['pct'].iloc[-1]=0.000302 , ukdf['amount'].iloc[-1]=29929709.8634, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9464.05287578124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26185.30407326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39029
self.closeSec=1695745499, self.tradeDate='20230927', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26182.3, self.close=26236.8, self.high=26238.9, self.low=26182.2, self.vol=2109.567, self.amt=55299095.8772 
2023-09-27 00:25:00,811:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230927   000000    000459  ...         0.0        0.0       0
5761  20230927   000500    000959  ...         0.0        0.0       0
5762  20230927   001000    001459  ...         0.0        0.0       0
5763  20230927   001500    001959  ...         0.0        0.0       0
5764  20230927   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 00:25:00,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695745499, self.tradeDate='20230927', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26182.3, self.close=26236.8, self.high=26238.9, self.low=26182.2, self.vol=2109.567, self.amt=55299095.8772, ukdf['pct'].iloc[-1]=0.002085 , ukdf['amount'].iloc[-1]=55299095.8772, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8722.4830205469', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26238.55481685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1695744299, self.tradeDate='20230927', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26114.8, self.close=26138.1, self.high=26138.1, self.low=26100.8 

--ukdf-hist--: overDate='20230922' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [27/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39028 

self.closeSec=1695744599, self.tradeDate='20230927', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26138.1, self.close=26163.9, self.high=26163.9, self.low=26135.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39029 

self.closeSec=1695744899, self.tradeDate='20230927', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26163.9, self.close=26174.3, self.high=26174.4, self.low=26151.8 
127.0.0.1 - - [27/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39030 

self.closeSec=1695745199, self.tradeDate='20230927', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26174.3, self.close=26182.2, self.high=26197.1, self.low=26174.3 
127.0.0.1 - - [27/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39031 

self.closeSec=1695745499, self.tradeDate='20230927', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26182.3, self.close=26236.8, self.high=26238.9, self.low=26182.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-27 00:00:21,072:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230926    212959  26200.1  ...  47.083333  0.453335  0.540845
5802  20230926    215959  26184.9  ...  47.083333  0.447765  0.561624
5803  20230926    222959  26168.3  ...  46.666667  0.439317  0.582945
5804  20230926    225959  26145.6  ...  46.666667  0.455013  0.595379
5805  20230926    232959  26183.0  ...  46.666667  0.430391  0.621935

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-09-27 00:00:21,130:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.486680  0.513320       0  ...  0.981129  -1.0    0.0  0.985547
540     1  0.485258  0.514742       0  ...  0.982066  -1.0    0.0  0.984605
541     1  0.480427  0.519573       1  ...  0.980661  -1.0    0.0  0.986014
542     0  0.500149  0.499851       0  ...  0.983467  -1.0    0.0  0.983193
543     1  0.467448  0.532552       1  ...  0.983214  -1.0    0.0  0.983445

[5 rows x 10 columns]
2023-09-27 00:00:21,141:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486380  0.513620       0  ...  0.981129  -1.0    0.0  0.984453
46     1  0.485309  0.514691       0  ...  0.982066  -1.0    0.0  0.984335
47     1  0.480183  0.519817       1  ...  0.980661  -1.0    0.0  0.985698
48     1  0.499915  0.500085       0  ...  0.983467  -1.0    0.0  0.982878
49     1  0.467448  0.532552       1  ...  0.983214  -1.0    0.0  0.983445

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '26154.4747523888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26112.52681136', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [26/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19511 

self.closeSec=1695742199, self.tradeDate='20230926', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26182.3', self.close='26108.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19512 

self.closeSec=1695742799, self.tradeDate='20230926', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26108', self.close='26141.3'
127.0.0.1 - - [26/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19513 

self.closeSec=1695743399, self.tradeDate='20230926', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26139.4', self.close='26119'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19514 

self.closeSec=1695743999, self.tradeDate='20230926', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26118.9', self.close='26114.8'
127.0.0.1 - - [27/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19515 

self.closeSec=1695744599, self.tradeDate='20230927', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26114.8', self.close='26163.9'
127.0.0.1 - - [27/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19516 

self.closeSec=1695745199, self.tradeDate='20230927', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26163.9', self.close='26182.2'
127.0.0.1 - - [27/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19514 

self.closeSec=1695742199, self.tradeDate='20230926', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26182.3', self.close='26108.1'
127.0.0.1 - - [26/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19515 

self.closeSec=1695742799, self.tradeDate='20230926', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26108', self.close='26141.3'
127.0.0.1 - - [26/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19516 

self.closeSec=1695743399, self.tradeDate='20230926', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26139.4', self.close='26119'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19517 

self.closeSec=1695743999, self.tradeDate='20230926', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26118.9', self.close='26114.8'
127.0.0.1 - - [27/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19518 

self.closeSec=1695744599, self.tradeDate='20230927', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26114.8', self.close='26163.9'
127.0.0.1 - - [27/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19519 

self.closeSec=1695745199, self.tradeDate='20230927', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26163.9', self.close='26182.2'
127.0.0.1 - - [27/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19514 

self.closeSec=1695742199, self.tradeDate='20230926', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26182.3', self.close='26108.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19515 

self.closeSec=1695742799, self.tradeDate='20230926', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26108', self.close='26141.3'
127.0.0.1 - - [26/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19516 

self.closeSec=1695743399, self.tradeDate='20230926', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26139.4', self.close='26119'
127.0.0.1 - - [26/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19517 

self.closeSec=1695743999, self.tradeDate='20230926', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26118.9', self.close='26114.8'
127.0.0.1 - - [27/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19518 

self.closeSec=1695744599, self.tradeDate='20230927', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26114.8', self.close='26163.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19519 

self.closeSec=1695745199, self.tradeDate='20230927', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26163.9', self.close='26182.2'
127.0.0.1 - - [27/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39028
self.closeSec=1695745199, self.tradeDate='20230927', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26174.3, self.close=26182.2, self.high=26197.1, self.low=26174.3, self.vol=1142.915, self.amt=29929709.8634 
127.0.0.1 - - [27/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-27 00:20:06,653:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230926   235500    235959  ...         0.0        0.0       0
5760  20230927   000000    000459  ...         0.0        0.0       0
5761  20230927   000500    000959  ...         0.0        0.0       0
5762  20230927   001000    001459  ...         0.0        0.0       0
5763  20230927   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 00:20:06,667:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695745199, self.tradeDate='20230927', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26174.3, self.close=26182.2, self.high=26197.1, self.low=26174.3, self.vol=1142.915, self.amt=29929709.8634, ukdf['pct'].iloc[-1]=0.000302 , ukdf['amount'].iloc[-1]=29929709.8634, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-24464.62541505034', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26185.30407326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [27/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39029
self.closeSec=1695745499, self.tradeDate='20230927', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26182.3, self.close=26236.8, self.high=26238.9, self.low=26182.2, self.vol=2109.567, self.amt=55299095.8772 
2023-09-27 00:25:00,795:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230927   000000    000459  ...         0.0        0.0       0
5761  20230927   000500    000959  ...         0.0        0.0       0
5762  20230927   001000    001459  ...         0.0        0.0       0
5763  20230927   001500    001959  ...         0.0        0.0       0
5764  20230927   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 00:25:00,796:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695745499, self.tradeDate='20230927', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26182.3, self.close=26236.8, self.high=26238.9, self.low=26182.2, self.vol=2109.567, self.amt=55299095.8772, ukdf['pct'].iloc[-1]=0.002085 , ukdf['amount'].iloc[-1]=55299095.8772, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-22486.83954737415', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26238.55481685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230926   120000    155959  1695715199  ...    723  0.269543 -0.835454    -1.0
724  20230926   160000    195959  1695729599  ...    724  0.271739 -0.829211    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-5785.84915911508', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26262.89340293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=813
self.closeSec=1695743999, self.tradeDate='20230926', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26262.4, self.close=26114.8, self.high=26296.6, self.low=26073.8, self.vol=54593.775, self.amt=1429195748.7911 
2023-09-27 00:00:01,554:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695743999, self.tradeDate='20230926', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26262.4, self.close=26114.8, self.high=26296.6, self.low=26073.8, self.vol=54593.775, self.amt=1429195748.7911 
2023-09-27 00:00:01,574:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230926   040000    075959  ...  23377.527  6.153584e+08 -0.000908
722  20230926   080000    115959  ...  20252.450  5.326637e+08  0.001841
723  20230926   120000    155959  ...  15913.957  4.184392e+08 -0.003132
724  20230926   160000    195959  ...  29876.724  7.839168e+08  0.000232
725  20230926   200000    235959  ...  54593.775  1.429196e+09 -0.005620

[5 rows x 11 columns]
2023-09-27 00:00:02,300:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230926   040000    075959  1695686399  ...    721  0.255654 -0.872703    -1.0
722  20230926   080000    115959  1695700799  ...    722  0.263544 -0.851426    -1.0
723  20230926   120000    155959  1695715199  ...    723  0.269543 -0.835454    -1.0
724  20230926   160000    195959  1695729599  ...    724  0.271739 -0.829211    -1.0
725  20230926   200000    235959  1695743999  ...    725  0.266004 -0.852583    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '1644.77848488492', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26116.49440293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


