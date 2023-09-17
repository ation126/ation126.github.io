# 20230917 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36340
self.closeSec=1694938799, self.tradeDate='20230917', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26507.6, self.close=26496.8, self.high=26507.6, self.low=26493.9, self.vol=209.177, self.amt=5542924.625 
127.0.0.1 - - [17/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-17 16:20:06,423:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230917   155500    155959  ...         0.0        0.0       0
5952  20230917   160000    160459  ...         0.0        0.0       0
5953  20230917   160500    160959  ...         0.0        0.0       0
5954  20230917   161000    161459  ...         0.0        0.0       0
5955  20230917   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 16:20:06,443:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694938799, self.tradeDate='20230917', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26507.6, self.close=26496.8, self.high=26507.6, self.low=26493.9, self.vol=209.177, self.amt=5542924.625, ukdf['pct'].iloc[-1]=-0.000407 , ukdf['amount'].iloc[-1]=5542924.625, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5127.5532', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26496.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36341
self.closeSec=1694939099, self.tradeDate='20230917', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26496.7, self.close=26502.9, self.high=26503.0, self.low=26494.7, self.vol=118.265, self.amt=3133992.9724 
127.0.0.1 - - [17/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-17 16:25:00,793:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230917   160000    160459  ...         0.0        0.0       0
5953  20230917   160500    160959  ...         0.0        0.0       0
5954  20230917   161000    161459  ...         0.0        0.0       0
5955  20230917   161500    161959  ...         0.0        0.0       0
5956  20230917   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 16:25:00,793:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694939099, self.tradeDate='20230917', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26496.7, self.close=26502.9, self.high=26503.0, self.low=26494.7, self.vol=118.265, self.amt=3133992.9724, ukdf['pct'].iloc[-1]=0.00023 , ukdf['amount'].iloc[-1]=3133992.9724, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5041.212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26502.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [17/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36338 

self.closeSec=1694937599, self.tradeDate='20230917', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26497.0, self.close=26482.5, self.high=26497.1, self.low=26476.0 
127.0.0.1 - - [17/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36339 

self.closeSec=1694937899, self.tradeDate='20230917', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26482.6, self.close=26497.4, self.high=26497.4, self.low=26480.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36340 

self.closeSec=1694938199, self.tradeDate='20230917', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26497.3, self.close=26482.1, self.high=26499.6, self.low=26482.0 
127.0.0.1 - - [17/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36341 

self.closeSec=1694938499, self.tradeDate='20230917', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26482.1, self.close=26507.6, self.high=26511.2, self.low=26482.0 
127.0.0.1 - - [17/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36342 

self.closeSec=1694938799, self.tradeDate='20230917', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26507.6, self.close=26496.8, self.high=26507.6, self.low=26493.9 
127.0.0.1 - - [17/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36343 

self.closeSec=1694939099, self.tradeDate='20230917', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26496.7, self.close=26502.9, self.high=26503.0, self.low=26494.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-17 16:00:17,431:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230917    132959  26540.5  ...  53.333333  0.512136  0.572873
5786  20230917    135959  26521.9  ...  53.333333  0.514341  0.560618
5787  20230917    142959  26528.2  ...  52.916667  0.512899  0.550418
5788  20230917    145959  26524.5  ...  53.333333  0.516410  0.537755
5789  20230917    152959  26534.2  ...  53.333333  0.515185  0.526952

[5 rows x 33 columns]
0.5608856088560885
acc is : 0.5608856088560885
2023-09-17 16:00:17,495:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.489979  0.510021       1  ...  0.943543   1.0    0.0  1.028512
538     1  0.495243  0.504757       0  ...  0.943404   1.0    0.0  1.028361
539     1  0.492351  0.507649       1  ...  0.943756   1.0    0.0  1.028744
540     1  0.496658  0.503342       0  ...  0.943642   1.0    0.0  1.028620
541     1  0.492342  0.507658       0  ...  0.941914   1.0    0.0  1.026736

[5 rows x 10 columns]
2023-09-17 16:00:17,506:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490413  0.509587       1  ...  0.943543   1.0    0.0  1.029953
46     1  0.495414  0.504586       0  ...  0.943404   1.0    0.0  1.029147
47     1  0.492354  0.507646       1  ...  0.943756   1.0    0.0  1.029271
48     1  0.496920  0.503080       0  ...  0.943642   1.0    0.0  1.029275
49     1  0.492342  0.507658       0  ...  0.941914   1.0    0.0  1.026736

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '-2815.452', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26487.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18167 

self.closeSec=1694935799, self.tradeDate='20230917', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26532.4', self.close='26531'
127.0.0.1 - - [17/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18168 

self.closeSec=1694936399, self.tradeDate='20230917', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26531.1', self.close='26519.7'
127.0.0.1 - - [17/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18169 

self.closeSec=1694936999, self.tradeDate='20230917', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26519.6', self.close='26500'
127.0.0.1 - - [17/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18170 

self.closeSec=1694937599, self.tradeDate='20230917', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26500.1', self.close='26482.6'
127.0.0.1 - - [17/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18171 

self.closeSec=1694938199, self.tradeDate='20230917', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26482.6', self.close='26482.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18172 

self.closeSec=1694938799, self.tradeDate='20230917', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26482.1', self.close='26496.8'
127.0.0.1 - - [17/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18170 

self.closeSec=1694935799, self.tradeDate='20230917', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26532.4', self.close='26531'
127.0.0.1 - - [17/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18171 127.0.0.1 - - [17/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -


self.closeSec=1694936399, self.tradeDate='20230917', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26531.1', self.close='26519.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18172 

self.closeSec=1694936999, self.tradeDate='20230917', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26519.6', self.close='26500'
127.0.0.1 - - [17/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18173 

self.closeSec=1694937599, self.tradeDate='20230917', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26500.1', self.close='26482.6'
127.0.0.1 - - [17/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18174 

self.closeSec=1694938199, self.tradeDate='20230917', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26482.6', self.close='26482.1'
127.0.0.1 - - [17/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18175 

self.closeSec=1694938799, self.tradeDate='20230917', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26482.1', self.close='26496.8'
127.0.0.1 - - [17/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [17/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18170 

self.closeSec=1694935799, self.tradeDate='20230917', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26532.4', self.close='26531'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18171 

self.closeSec=1694936399, self.tradeDate='20230917', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26531.1', self.close='26519.7'
127.0.0.1 - - [17/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [17/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18172 

self.closeSec=1694936999, self.tradeDate='20230917', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26519.6', self.close='26500'
127.0.0.1 - - [17/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18173 

self.closeSec=1694937599, self.tradeDate='20230917', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26500.1', self.close='26482.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18174 

self.closeSec=1694938199, self.tradeDate='20230917', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26482.6', self.close='26482.1'
127.0.0.1 - - [17/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18175 

self.closeSec=1694938799, self.tradeDate='20230917', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26482.1', self.close='26496.8'
127.0.0.1 - - [17/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36340
self.closeSec=1694938799, self.tradeDate='20230917', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26507.6, self.close=26496.8, self.high=26507.6, self.low=26493.9, self.vol=209.177, self.amt=5542924.625 
127.0.0.1 - - [17/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-17 16:20:06,433:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230917   155500    155959  ...         0.0        0.0       0
5952  20230917   160000    160459  ...         0.0        0.0       0
5953  20230917   160500    160959  ...         0.0        0.0       0
5954  20230917   161000    161459  ...         0.0        0.0       0
5955  20230917   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 16:20:06,446:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694938799, self.tradeDate='20230917', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26507.6, self.close=26496.8, self.high=26507.6, self.low=26493.9, self.vol=209.177, self.amt=5542924.625, ukdf['pct'].iloc[-1]=-0.000407 , ukdf['amount'].iloc[-1]=5542924.625, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12899.0693', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26496.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36341
self.closeSec=1694939099, self.tradeDate='20230917', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26496.7, self.close=26502.9, self.high=26503.0, self.low=26494.7, self.vol=118.265, self.amt=3133992.9724 
127.0.0.1 - - [17/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-17 16:25:00,794:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230917   160000    160459  ...         0.0        0.0       0
5953  20230917   160500    160959  ...         0.0        0.0       0
5954  20230917   161000    161459  ...         0.0        0.0       0
5955  20230917   161500    161959  ...         0.0        0.0       0
5956  20230917   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 16:25:00,795:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694939099, self.tradeDate='20230917', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26496.7, self.close=26502.9, self.high=26503.0, self.low=26494.7, self.vol=118.265, self.amt=3133992.9724, ukdf['pct'].iloc[-1]=0.00023 , ukdf['amount'].iloc[-1]=3133992.9724, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12668.7951', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26502.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230917   040000    075959  1694908799  ...    721  0.483101  0.617305     1.0
722  20230917   080000    115959  1694923199  ...    722  0.465218  0.558486     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-8873.0521369525', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26513.2431431', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [17/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1431863.74296, self.flagDict['side']='buy', self.tradeCount=23, self.count=757
self.closeSec=1694937599, self.tradeDate='20230917', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26511.1, self.close=26482.6, self.high=26560.7, self.low=26476.0, self.vol=12207.039, self.amt=323759118.996 
2023-09-17 16:00:01,522:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694937599, self.tradeDate='20230917', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26511.1, self.close=26482.6, self.high=26560.7, self.low=26476.0, self.vol=12207.039, self.amt=323759118.996 
2023-09-17 16:00:01,534:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230916   200000    235959  ...  15417.259  4.088440e+08 -0.000645
720  20230917   000000    035959  ...  19314.111  5.127177e+08  0.001155
721  20230917   040000    075959  ...   9029.999  2.396382e+08  0.000856
722  20230917   080000    115959  ...  24901.582  6.592066e+08 -0.001349
723  20230917   120000    155959  ...  12207.039  3.237591e+08 -0.001075

[5 rows x 11 columns]
2023-09-17 16:00:02,172:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230916   200000    235959  1694879999  ...    719  0.386956  0.223744     NaN
720  20230917   000000    035959  1694894399  ...    720  0.370838  0.172720     NaN
721  20230917   040000    075959  1694908799  ...    721  0.483101  0.617305     1.0
722  20230917   080000    115959  1694923199  ...    722  0.465218  0.558486     NaN
723  20230917   120000    155959  1694937599  ...    723  0.321356  0.008056     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-10479.9239005055', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26483.33394322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


