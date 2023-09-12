# 20230912 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34900
self.closeSec=1694506799, self.tradeDate='20230912', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25816.1, self.close=25830.0, self.high=25863.7, self.low=25816.1, self.vol=1493.934, self.amt=38610541.5937 
127.0.0.1 - - [12/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-12 16:20:05,798:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230912   155500    155959  ...         0.0        0.0       0
5952  20230912   160000    160459  ...         0.0        0.0       0
5953  20230912   160500    160959  ...         0.0        0.0       0
5954  20230912   161000    161459  ...         0.0        0.0       0
5955  20230912   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 16:20:05,801:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694506799, self.tradeDate='20230912', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25816.1, self.close=25830.0, self.high=25863.7, self.low=25816.1, self.vol=1493.934, self.amt=38610541.5937, ukdf['pct'].iloc[-1]=0.000538 , ukdf['amount'].iloc[-1]=38610541.5937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14382.97964956248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25832.08514652', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34901
self.closeSec=1694507099, self.tradeDate='20230912', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25830.0, self.close=25832.1, self.high=25853.3, self.low=25812.4, self.vol=1127.413, self.amt=29122611.333 
2023-09-12 16:25:00,787:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230912   160000    160459  ...         0.0        0.0       0
5953  20230912   160500    160959  ...         0.0        0.0       0
5954  20230912   161000    161459  ...         0.0        0.0       0
5955  20230912   161500    161959  ...         0.0        0.0       0
5956  20230912   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 16:25:00,787:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694507099, self.tradeDate='20230912', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25830.0, self.close=25832.1, self.high=25853.3, self.low=25812.4, self.vol=1127.413, self.amt=29122611.333, ukdf['pct'].iloc[-1]=8.1e-05 , ukdf['amount'].iloc[-1]=29122611.333, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14382.7728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25832.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34898 

self.closeSec=1694505599, self.tradeDate='20230912', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25814.9, self.close=25810.2, self.high=25814.9, self.low=25785.4 
127.0.0.1 - - [12/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34899 

self.closeSec=1694505899, self.tradeDate='20230912', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25810.2, self.close=25803.7, self.high=25830.1, self.low=25801.3 
127.0.0.1 - - [12/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34900 

self.closeSec=1694506199, self.tradeDate='20230912', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25805.4, self.close=25790.2, self.high=25810.0, self.low=25783.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34901 

self.closeSec=1694506499, self.tradeDate='20230912', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25790.3, self.close=25816.1, self.high=25829.9, self.low=25771.2 
127.0.0.1 - - [12/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34902 

self.closeSec=1694506799, self.tradeDate='20230912', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25816.1, self.close=25830.0, self.high=25863.7, self.low=25816.1 
127.0.0.1 - - [12/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34903 

self.closeSec=1694507099, self.tradeDate='20230912', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25830.0, self.close=25832.1, self.high=25853.3, self.low=25812.4 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-12 16:00:18,393:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230912    132959  25752.2  ...  50.416667  0.515207  0.571477
5786  20230912    135959  25631.6  ...  50.416667  0.537698  0.547007
5787  20230912    142959  25764.4  ...  50.416667  0.538931  0.523715
5788  20230912    145959  25776.6  ...  50.416667  0.535222  0.503131
5789  20230912    152959  25752.8  ...  50.416667  0.532793  0.484670

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-09-12 16:00:18,455:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.484722  0.515278       1  ...  0.977996   1.0    0.0  0.989500
538     0  0.517550  0.482450       1  ...  0.978281   1.0    0.0  0.989788
539     1  0.490635  0.509365       0  ...  0.977556   1.0    0.0  0.989054
540     1  0.480762  0.519238       0  ...  0.977085   1.0    0.0  0.988578
541     1  0.487704  0.512296       1  ...  0.979735   1.0    0.0  0.991259

[5 rows x 10 columns]
2023-09-12 16:00:18,466:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484797  0.515203       1  ...  0.977996   1.0    0.0  0.989310
46     0  0.517758  0.482242       1  ...  0.978281   1.0    0.0  0.993516
47     1  0.489933  0.510067       0  ...  0.977556   1.0    0.0  0.993239
48     1  0.480927  0.519073       0  ...  0.977085   1.0    0.0  0.989384
49     1  0.487704  0.512296       1  ...  0.979735   1.0    0.0  0.991259

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.233', 'enterprice': '25817.5', 'countrevence': '0', 'unrealprofit': '-140.50105922016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25812.52351648', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17447 

self.closeSec=1694503799, self.tradeDate='20230912', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25719.8', self.close='25740.3'
127.0.0.1 - - [12/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17448 

self.closeSec=1694504399, self.tradeDate='20230912', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25740.3', self.close='25764.5'
127.0.0.1 - - [12/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17449 

self.closeSec=1694504999, self.tradeDate='20230912', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25764.5', self.close='25850'
127.0.0.1 - - [12/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17450 

self.closeSec=1694505599, self.tradeDate='20230912', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25850', self.close='25810.2'
127.0.0.1 - - [12/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17451 

self.closeSec=1694506199, self.tradeDate='20230912', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25810.2', self.close='25790.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17452 

self.closeSec=1694506799, self.tradeDate='20230912', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25790.3', self.close='25830'
127.0.0.1 - - [12/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [12/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17450 

self.closeSec=1694503799, self.tradeDate='20230912', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25719.8', self.close='25740.3'
127.0.0.1 - - [12/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17451 

self.closeSec=1694504399, self.tradeDate='20230912', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25740.3', self.close='25764.5'
127.0.0.1 - - [12/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17452 

self.closeSec=1694504999, self.tradeDate='20230912', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25764.5', self.close='25850'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17453 

self.closeSec=1694505599, self.tradeDate='20230912', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25850', self.close='25810.2'
127.0.0.1 - - [12/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17454 

self.closeSec=1694506199, self.tradeDate='20230912', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25810.2', self.close='25790.2'
127.0.0.1 - - [12/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17455 

self.closeSec=1694506799, self.tradeDate='20230912', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25790.3', self.close='25830'
127.0.0.1 - - [12/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17450 

self.closeSec=1694503799, self.tradeDate='20230912', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25719.8', self.close='25740.3'
127.0.0.1 - - [12/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [12/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17451 

self.closeSec=1694504399, self.tradeDate='20230912', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25740.3', self.close='25764.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17452 

self.closeSec=1694504999, self.tradeDate='20230912', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25764.5', self.close='25850'
127.0.0.1 - - [12/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17453 

self.closeSec=1694505599, self.tradeDate='20230912', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25850', self.close='25810.2'
127.0.0.1 - - [12/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17454 

self.closeSec=1694506199, self.tradeDate='20230912', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25810.2', self.close='25790.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17455 

self.closeSec=1694506799, self.tradeDate='20230912', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25790.3', self.close='25830'
127.0.0.1 - - [12/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34900
self.closeSec=1694506799, self.tradeDate='20230912', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25816.1, self.close=25830.0, self.high=25863.7, self.low=25816.1, self.vol=1493.934, self.amt=38610541.5937 
127.0.0.1 - - [12/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-12 16:20:05,798:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230912   155500    155959  ...         0.0        0.0       0
5952  20230912   160000    160459  ...         0.0        0.0       0
5953  20230912   160500    160959  ...         0.0        0.0       0
5954  20230912   161000    161459  ...         0.0        0.0       0
5955  20230912   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 16:20:05,802:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694506799, self.tradeDate='20230912', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25816.1, self.close=25830.0, self.high=25863.7, self.low=25816.1, self.vol=1493.934, self.amt=38610541.5937, ukdf['pct'].iloc[-1]=0.000538 , ukdf['amount'].iloc[-1]=38610541.5937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37583.52957310068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25832.08514652', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [12/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34901
self.closeSec=1694507099, self.tradeDate='20230912', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25830.0, self.close=25832.1, self.high=25853.3, self.low=25812.4, self.vol=1127.413, self.amt=29122611.333 
2023-09-12 16:25:00,786:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230912   160000    160459  ...         0.0        0.0       0
5953  20230912   160500    160959  ...         0.0        0.0       0
5954  20230912   161000    161459  ...         0.0        0.0       0
5955  20230912   161500    161959  ...         0.0        0.0       0
5956  20230912   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 16:25:00,787:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694507099, self.tradeDate='20230912', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25830.0, self.close=25832.1, self.high=25853.3, self.low=25812.4, self.vol=1127.413, self.amt=29122611.333, ukdf['pct'].iloc[-1]=8.1e-05 , ukdf['amount'].iloc[-1]=29122611.333, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37582.9779', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25832.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230912   040000    075959  1694476799  ...    721  0.312324 -0.219917     NaN
722  20230912   080000    115959  1694491199  ...    722  0.202304 -0.523436     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '5065.8822', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25803.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=727
self.closeSec=1694505599, self.tradeDate='20230912', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25788.2, self.close=25810.2, self.high=25989.6, self.low=25600.8, self.vol=95929.589, self.amt=2472843417.31446 
127.0.0.1 - - [12/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-12 16:00:01,602:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694505599, self.tradeDate='20230912', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25788.2, self.close=25810.2, self.high=25989.6, self.low=25600.8, self.vol=95929.589, self.amt=2472843417.31446 
2023-09-12 16:00:01,633:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230911   200000    235959  ...  202776.195  5.125212e+09 -0.019084
720  20230912   000000    035959  ...   65270.071  1.639586e+09 -0.003792
721  20230912   040000    075959  ...   41241.175  1.034585e+09  0.005682
722  20230912   080000    115959  ...  109017.062  2.787754e+09  0.025355
723  20230912   120000    155959  ...   95929.589  2.472843e+09  0.000857

[5 rows x 11 columns]
2023-09-12 16:00:02,558:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230911   200000    235959  1694447999  ...    719  0.086707 -0.854904    -1.0
720  20230912   000000    035959  1694462399  ...    720  0.210671 -0.503950     NaN
721  20230912   040000    075959  1694476799  ...    721  0.312324 -0.219917     NaN
722  20230912   080000    115959  1694491199  ...    722  0.202304 -0.523436     NaN
723  20230912   120000    155959  1694505599  ...    723  0.150643 -0.666047    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '4622.98193254251', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25811.44612637', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


