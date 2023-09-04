# 20230904 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32596
self.closeSec=1693815599, self.tradeDate='20230904', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25985.7, self.close=25976.3, self.high=25998.6, self.low=25976.3, self.vol=372.932, self.amt=9691910.8806 
127.0.0.1 - - [04/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-04 16:20:05,630:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230904   155500    155959  ...         0.0        0.0       0
5940  20230904   160000    160459  ...         0.0        0.0       0
5941  20230904   160500    160959  ...         0.0        0.0       0
5942  20230904   161000    161459  ...         0.0        0.0       0
5943  20230904   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 16:20:05,633:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693815599, self.tradeDate='20230904', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25985.7, self.close=25976.3, self.high=25998.6, self.low=25976.3, self.vol=372.932, self.amt=9691910.8806, ukdf['pct'].iloc[-1]=-0.000366 , ukdf['amount'].iloc[-1]=9691910.8806, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12351.86452386942', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25977.93572283', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32597
self.closeSec=1693815899, self.tradeDate='20230904', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25976.3, self.close=25977.8, self.high=25980.6, self.low=25972.2, self.vol=146.93, self.amt=3816702.9068 
2023-09-04 16:25:00,769:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230904   160000    160459  ...         0.0        0.0       0
5941  20230904   160500    160959  ...         0.0        0.0       0
5942  20230904   161000    161459  ...         0.0        0.0       0
5943  20230904   161500    161959  ...         0.0        0.0       0
5944  20230904   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 16:25:00,769:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693815899, self.tradeDate='20230904', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25976.3, self.close=25977.8, self.high=25980.6, self.low=25972.2, self.vol=146.93, self.amt=3816702.9068, ukdf['pct'].iloc[-1]=5.8e-05 , ukdf['amount'].iloc[-1]=3816702.9068, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12340.10982331512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25978.77980588', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [04/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32594 

self.closeSec=1693814399, self.tradeDate='20230904', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25951.6, self.close=25953.8, self.high=25953.9, self.low=25950.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32595 

self.closeSec=1693814699, self.tradeDate='20230904', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25953.8, self.close=25969.9, self.high=25969.9, self.low=25946.7 
127.0.0.1 - - [04/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32596 

self.closeSec=1693814999, self.tradeDate='20230904', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25969.8, self.close=25977.4, self.high=25982.1, self.low=25967.4 
127.0.0.1 - - [04/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32597 

self.closeSec=1693815299, self.tradeDate='20230904', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25977.3, self.close=25985.8, self.high=25987.8, self.low=25977.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32598 

self.closeSec=1693815599, self.tradeDate='20230904', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25985.7, self.close=25976.3, self.high=25998.6, self.low=25976.3 
127.0.0.1 - - [04/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32599 

self.closeSec=1693815899, self.tradeDate='20230904', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25976.3, self.close=25977.8, self.high=25980.6, self.low=25972.2 
127.0.0.1 - - [04/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-04 16:00:18,373:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230904    132959  25969.6  ...  45.000000  0.512074  0.517544
5786  20230904    135959  25965.7  ...  44.583333  0.494776  0.522777
5787  20230904    142959  25920.4  ...  45.000000  0.514260  0.518001
5788  20230904    145959  25973.7  ...  45.000000  0.506086  0.517508
5789  20230904    152959  25952.3  ...  45.000000  0.513422  0.513363

[5 rows x 33 columns]
0.5239852398523985
acc is : 0.5239852398523985
2023-09-04 16:00:18,437:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.487532  0.512468       0  ...  0.998851  -1.0    0.0  0.978177
538     1  0.471174  0.528826       1  ...  0.996851  -1.0    0.0  0.980136
539     0  0.502217  0.497783       0  ...  0.997669  -1.0    0.0  0.979332
540     1  0.481459  0.518541       1  ...  0.996907  -1.0    0.0  0.980079
541     1  0.494000  0.506000       0  ...  0.997610  -1.0    0.0  0.979389

[5 rows x 10 columns]
2023-09-04 16:00:18,449:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488132  0.511868       0  ...  0.998851  -1.0    0.0  0.980379
46     1  0.471432  0.528568       1  ...  0.996851  -1.0    0.0  0.981002
47     0  0.502865  0.497135       0  ...  0.997669  -1.0    0.0  0.982327
48     1  0.481715  0.518285       1  ...  0.996907  -1.0    0.0  0.980953
49     1  0.494000  0.506000       0  ...  0.997610  -1.0    0.0  0.979389

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '19053.8065', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25957.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [04/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16295 

self.closeSec=1693812599, self.tradeDate='20230904', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25981.2', self.close='25972.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16296 

self.closeSec=1693813199, self.tradeDate='20230904', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25972.1', self.close='25970'
127.0.0.1 - - [04/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [04/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16297 

self.closeSec=1693813799, self.tradeDate='20230904', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25970.1', self.close='25955.3'
127.0.0.1 - - [04/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16298 

self.closeSec=1693814399, self.tradeDate='20230904', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25955.3', self.close='25953.8'
127.0.0.1 - - [04/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16299 

self.closeSec=1693814999, self.tradeDate='20230904', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25953.8', self.close='25977.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16300 

self.closeSec=1693815599, self.tradeDate='20230904', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25977.3', self.close='25976.3'
127.0.0.1 - - [04/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [04/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16298 

self.closeSec=1693812599, self.tradeDate='20230904', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25981.2', self.close='25972.1'
127.0.0.1 - - [04/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16299 

self.closeSec=1693813199, self.tradeDate='20230904', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25972.1', self.close='25970'
127.0.0.1 - - [04/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16300 

self.closeSec=1693813799, self.tradeDate='20230904', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25970.1', self.close='25955.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16301 

self.closeSec=1693814399, self.tradeDate='20230904', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25955.3', self.close='25953.8'
127.0.0.1 - - [04/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16302 

self.closeSec=1693814999, self.tradeDate='20230904', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25953.8', self.close='25977.3'
127.0.0.1 - - [04/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16303 

self.closeSec=1693815599, self.tradeDate='20230904', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25977.3', self.close='25976.3'
127.0.0.1 - - [04/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [04/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16298 

self.closeSec=1693812599, self.tradeDate='20230904', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25981.2', self.close='25972.1'
127.0.0.1 - - [04/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16299 

self.closeSec=1693813199, self.tradeDate='20230904', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25972.1', self.close='25970'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16300 

self.closeSec=1693813799, self.tradeDate='20230904', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25970.1', self.close='25955.3'
127.0.0.1 - - [04/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16301 

self.closeSec=1693814399, self.tradeDate='20230904', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25955.3', self.close='25953.8'
127.0.0.1 - - [04/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16302 

self.closeSec=1693814999, self.tradeDate='20230904', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25953.8', self.close='25977.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16303 

self.closeSec=1693815599, self.tradeDate='20230904', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25977.3', self.close='25976.3'
127.0.0.1 - - [04/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32596
self.closeSec=1693815599, self.tradeDate='20230904', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25985.7, self.close=25976.3, self.high=25998.6, self.low=25976.3, self.vol=372.932, self.amt=9691910.8806 
127.0.0.1 - - [04/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-04 16:20:05,631:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230904   155500    155959  ...         0.0        0.0       0
5940  20230904   160000    160459  ...         0.0        0.0       0
5941  20230904   160500    160959  ...         0.0        0.0       0
5942  20230904   161000    161459  ...         0.0        0.0       0
5943  20230904   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 16:20:05,640:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693815599, self.tradeDate='20230904', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25985.7, self.close=25976.3, self.high=25998.6, self.low=25976.3, self.vol=372.932, self.amt=9691910.8806, ukdf['pct'].iloc[-1]=-0.000366 , ukdf['amount'].iloc[-1]=9691910.8806, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-32166.49331837097', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25977.93572283', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32597
self.closeSec=1693815899, self.tradeDate='20230904', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25976.3, self.close=25977.8, self.high=25980.6, self.low=25972.2, self.vol=146.93, self.amt=3816702.9068 
127.0.0.1 - - [04/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-04 16:25:00,770:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230904   160000    160459  ...         0.0        0.0       0
5941  20230904   160500    160959  ...         0.0        0.0       0
5942  20230904   161000    161459  ...         0.0        0.0       0
5943  20230904   161500    161959  ...         0.0        0.0       0
5944  20230904   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-04 16:25:00,771:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693815899, self.tradeDate='20230904', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25976.3, self.close=25977.8, self.high=25980.6, self.low=25972.2, self.vol=146.93, self.amt=3816702.9068, ukdf['pct'].iloc[-1]=5.8e-05 , ukdf['amount'].iloc[-1]=3816702.9068, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-32135.14322981092', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25978.77980588', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230904   040000    075959  1693785599  ...    721  0.751855  1.007003     1.0
722  20230904   080000    115959  1693799999  ...    722  0.745069  0.976513     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-106465.58535077088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25974.20408456', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=679
self.closeSec=1693814399, self.tradeDate='20230904', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25974.1, self.close=25953.8, self.high=26005.7, self.low=25896.0, self.vol=14593.385, self.amt=378832452.1875 
127.0.0.1 - - [04/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-04 16:00:01,519:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693814399, self.tradeDate='20230904', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25974.1, self.close=25953.8, self.high=26005.7, self.low=25896.0, self.vol=14593.385, self.amt=378832452.1875 
2023-09-04 16:00:01,536:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230903   200000    235959  ...  42781.009  1.109222e+09 -0.002788
720  20230904   000000    035959  ...  31902.907  8.265704e+08  0.005391
721  20230904   040000    075959  ...  25287.093  6.575943e+08 -0.001366
722  20230904   080000    115959  ...  22003.637  5.712652e+08  0.000462
723  20230904   120000    155959  ...  14593.385  3.788325e+08 -0.000782

[5 rows x 11 columns]
2023-09-04 16:00:02,232:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230903   200000    235959  1693756799  ...    719  0.810581  1.203812     1.0
720  20230904   000000    035959  1693771199  ...    720  0.764640  1.056010     1.0
721  20230904   040000    075959  1693785599  ...    721  0.751855  1.007003     1.0
722  20230904   080000    115959  1693799999  ...    722  0.745069  0.976513     1.0
723  20230904   120000    155959  1693814399  ...    723  0.755318  0.994791     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-107633.76', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25953.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


