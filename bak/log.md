# 20230908 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33748
self.closeSec=1694161199, self.tradeDate='20230908', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26201.0, self.close=26184.2, self.high=26218.4, self.low=26182.5, self.vol=848.34, self.amt=22227138.988 
127.0.0.1 - - [08/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-08 16:20:05,611:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230908   155500    155959  ...         0.0        0.0       0
5952  20230908   160000    160459  ...         0.0        0.0       0
5953  20230908   160500    160959  ...         0.0        0.0       0
5954  20230908   161000    161459  ...         0.0        0.0       0
5955  20230908   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 16:20:05,615:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694161199, self.tradeDate='20230908', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26201.0, self.close=26184.2, self.high=26218.4, self.low=26182.5, self.vol=848.34, self.amt=22227138.988, ukdf['pct'].iloc[-1]=-0.000637 , ukdf['amount'].iloc[-1]=22227138.988, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9418.1538', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26188.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33749
self.closeSec=1694161499, self.tradeDate='20230908', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26186.2, self.close=26200.8, self.high=26207.6, self.low=26180.6, self.vol=760.919, self.amt=19930110.3473 
127.0.0.1 - - [08/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-08 16:25:00,780:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230908   160000    160459  ...         0.0        0.0       0
5953  20230908   160500    160959  ...         0.0        0.0       0
5954  20230908   161000    161459  ...         0.0        0.0       0
5955  20230908   161500    161959  ...         0.0        0.0       0
5956  20230908   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 16:25:00,780:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694161499, self.tradeDate='20230908', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26186.2, self.close=26200.8, self.high=26207.6, self.low=26180.6, self.vol=760.919, self.amt=19930110.3473, ukdf['pct'].iloc[-1]=0.000634 , ukdf['amount'].iloc[-1]=19930110.3473, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9224.4435480318', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26202.5099707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [08/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33746 

self.closeSec=1694159999, self.tradeDate='20230908', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26248.8, self.close=26244.1, self.high=26253.2, self.low=26244.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33747 

self.closeSec=1694160299, self.tradeDate='20230908', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26244.0, self.close=26247.5, self.high=26247.7, self.low=26238.6 
127.0.0.1 - - [08/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33748 

self.closeSec=1694160599, self.tradeDate='20230908', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26247.5, self.close=26256.9, self.high=26257.9, self.low=26247.4 
127.0.0.1 - - [08/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33749 

self.closeSec=1694160899, self.tradeDate='20230908', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26256.8, self.close=26200.9, self.high=26256.9, self.low=26195.6 
127.0.0.1 - - [08/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33750 

self.closeSec=1694161199, self.tradeDate='20230908', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26201.0, self.close=26184.2, self.high=26218.4, self.low=26182.5 
127.0.0.1 - - [08/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33751 

self.closeSec=1694161499, self.tradeDate='20230908', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26186.2, self.close=26200.8, self.high=26207.6, self.low=26180.6 
127.0.0.1 - - [08/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-08 16:00:18,123:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230908    132959  26334.1  ...  50.416667  0.614812  0.261524
5786  20230908    135959  26340.0  ...  50.416667  0.579614  0.261794
5787  20230908    142959  26225.6  ...  50.833333  0.583190  0.260727
5788  20230908    145959  26242.5  ...  50.416667  0.573938  0.262182
5789  20230908    152959  26211.4  ...  50.833333  0.587112  0.258709

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-09-08 16:00:18,197:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.501046  0.498954       0  ...  1.015248   1.0    0.0  1.008316
538     1  0.463446  0.536554       1  ...  1.015899   1.0    0.0  1.008962
539     1  0.494430  0.505570       0  ...  1.014691   1.0    0.0  1.007763
540     1  0.477010  0.522990       1  ...  1.017072   1.0    0.0  1.010127
541     0  0.501412  0.498588       0  ...  1.015965   1.0    0.0  1.009028

[5 rows x 10 columns]
2023-09-08 16:00:18,210:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500759  0.499241       0  ...  1.015248   1.0    0.0  1.005710
46     1  0.461971  0.538029       1  ...  1.015899   1.0    0.0  1.006323
47     1  0.493788  0.506212       0  ...  1.014691   1.0    0.0  1.004734
48     1  0.476580  0.523420       1  ...  1.017072   1.0    0.0  1.009056
49     0  0.501412  0.498588       0  ...  1.015965   1.0    0.0  1.009028

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.331', 'enterprice': '25653.5', 'countrevence': '0', 'unrealprofit': '16807.19156109615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26246.74385165', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16871 

self.closeSec=1694158199, self.tradeDate='20230908', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26249.9', self.close='26272.7'
127.0.0.1 - - [08/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16872 

self.closeSec=1694158799, self.tradeDate='20230908', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26272.7', self.close='26249.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16873 

self.closeSec=1694159399, self.tradeDate='20230908', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26249.5', self.close='26248.9'
127.0.0.1 - - [08/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16874 

self.closeSec=1694159999, self.tradeDate='20230908', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26248.9', self.close='26244.1'
127.0.0.1 - - [08/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16875 

self.closeSec=1694160599, self.tradeDate='20230908', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26244', self.close='26256.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16876 

self.closeSec=1694161199, self.tradeDate='20230908', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26256.8', self.close='26184.2'
127.0.0.1 - - [08/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [08/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16874 

self.closeSec=1694158199, self.tradeDate='20230908', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26249.9', self.close='26272.7'
127.0.0.1 - - [08/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16875 

self.closeSec=1694158799, self.tradeDate='20230908', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26272.7', self.close='26249.6'
127.0.0.1 - - [08/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16876 

self.closeSec=1694159399, self.tradeDate='20230908', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26249.5', self.close='26248.9'
127.0.0.1 - - [08/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16877 

self.closeSec=1694159999, self.tradeDate='20230908', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26248.9', self.close='26244.1'
127.0.0.1 - - [08/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16878 

self.closeSec=1694160599, self.tradeDate='20230908', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26244', self.close='26256.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16879 

self.closeSec=1694161199, self.tradeDate='20230908', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26256.8', self.close='26184.2'
127.0.0.1 - - [08/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16874 

self.closeSec=1694158199, self.tradeDate='20230908', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26249.9', self.close='26272.7'
127.0.0.1 - - [08/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16875 

self.closeSec=1694158799, self.tradeDate='20230908', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26272.7', self.close='26249.6'
127.0.0.1 - - [08/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16876 

self.closeSec=1694159399, self.tradeDate='20230908', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26249.5', self.close='26248.9'
127.0.0.1 - - [08/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16877 

self.closeSec=1694159999, self.tradeDate='20230908', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26248.9', self.close='26244.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16878 

self.closeSec=1694160599, self.tradeDate='20230908', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26244', self.close='26256.9'
127.0.0.1 - - [08/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16879 

self.closeSec=1694161199, self.tradeDate='20230908', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26256.8', self.close='26184.2'
127.0.0.1 - - [08/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33748
self.closeSec=1694161199, self.tradeDate='20230908', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26201.0, self.close=26184.2, self.high=26218.4, self.low=26182.5, self.vol=848.34, self.amt=22227138.988 
127.0.0.1 - - [08/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-08 16:20:05,610:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230908   155500    155959  ...         0.0        0.0       0
5952  20230908   160000    160459  ...         0.0        0.0       0
5953  20230908   160500    160959  ...         0.0        0.0       0
5954  20230908   161000    161459  ...         0.0        0.0       0
5955  20230908   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 16:20:05,613:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694161199, self.tradeDate='20230908', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26201.0, self.close=26184.2, self.high=26218.4, self.low=26182.5, self.vol=848.34, self.amt=22227138.988, ukdf['pct'].iloc[-1]=-0.000637 , ukdf['amount'].iloc[-1]=22227138.988, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-24342.2114', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26188.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33749
self.closeSec=1694161499, self.tradeDate='20230908', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26186.2, self.close=26200.8, self.high=26207.6, self.low=26180.6, self.vol=760.919, self.amt=19930110.3473 
127.0.0.1 - - [08/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-08 16:25:00,785:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230908   160000    160459  ...         0.0        0.0       0
5953  20230908   160500    160959  ...         0.0        0.0       0
5954  20230908   161000    161459  ...         0.0        0.0       0
5955  20230908   161500    161959  ...         0.0        0.0       0
5956  20230908   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 16:25:00,785:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694161499, self.tradeDate='20230908', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26186.2, self.close=26200.8, self.high=26207.6, self.low=26180.6, self.vol=760.919, self.amt=19930110.3473, ukdf['pct'].iloc[-1]=0.000634 , ukdf['amount'].iloc[-1]=19930110.3473, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-23825.5811782313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26202.5099707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230908   040000    075959  1694131199  ...    721  0.049128 -0.974409    -1.0
722  20230908   080000    115959  1694145599  ...    722  0.174553 -0.625975    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-19788.9597', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26238.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [08/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=703
self.closeSec=1694159999, self.tradeDate='20230908', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26235.6, self.close=26244.1, self.high=26378.4, self.low=26171.0, self.vol=33675.232, self.amt=884791118.0764 
2023-09-08 16:00:01,634:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694159999, self.tradeDate='20230908', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26235.6, self.close=26244.1, self.high=26378.4, self.low=26171.0, self.vol=33675.232, self.amt=884791118.0764 
2023-09-08 16:00:01,647:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230907   200000    235959  ...   47604.669  1.223882e+09  0.002771
720  20230908   000000    035959  ...   48160.796  1.245784e+09  0.003897
721  20230908   040000    075959  ...  115647.917  3.031112e+09  0.014408
722  20230908   080000    115959  ...   36619.154  9.622821e+08 -0.000160
723  20230908   120000    155959  ...   33675.232  8.847911e+08  0.000324

[5 rows x 11 columns]
2023-09-08 16:00:02,249:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230907   200000    235959  1694102399  ...    719  0.028042 -1.034925    -1.0
720  20230908   000000    035959  1694116799  ...    720  0.020270 -1.056341    -1.0
721  20230908   040000    075959  1694131199  ...    721  0.049128 -0.974409    -1.0
722  20230908   080000    115959  1694145599  ...    722  0.174553 -0.625975    -1.0
723  20230908   120000    155959  1694159999  ...    723  0.269430 -0.364649     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-20246.89060690173', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26246.40900549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


