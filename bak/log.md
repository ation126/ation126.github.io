# 20230820 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28276
self.closeSec=1692519599, self.tradeDate='20230820', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26057.0, self.close=26059.0, self.high=26059.0, self.low=26056.9, self.vol=108.376, self.amt=2824023.4438 
127.0.0.1 - - [20/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-20 16:20:05,259:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230820   155500    155959  ...         0.0        0.0       0
5940  20230820   160000    160459  ...         0.0        0.0       0
5941  20230820   160500    160959  ...         0.0        0.0       0
5942  20230820   161000    161459  ...         0.0        0.0       0
5943  20230820   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 16:20:05,272:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692519599, self.tradeDate='20230820', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26057.0, self.close=26059.0, self.high=26059.0, self.low=26056.9, self.vol=108.376, self.amt=2824023.4438, ukdf['pct'].iloc[-1]=7.7e-05 , ukdf['amount'].iloc[-1]=2824023.4438, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11224.356', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26058.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28277
self.closeSec=1692519899, self.tradeDate='20230820', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26059.0, self.close=26061.7, self.high=26061.7, self.low=26041.4, self.vol=326.728, self.amt=8511887.7916 
2023-08-20 16:25:00,806:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230820   160000    160459  ...         0.0        0.0       0
5941  20230820   160500    160959  ...         0.0        0.0       0
5942  20230820   161000    161459  ...         0.0        0.0       0
5943  20230820   161500    161959  ...         0.0        0.0       0
5944  20230820   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 16:25:00,806:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692519899, self.tradeDate='20230820', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26059.0, self.close=26061.7, self.high=26061.7, self.low=26041.4, self.vol=326.728, self.amt=8511887.7916, ukdf['pct'].iloc[-1]=0.000104 , ukdf['amount'].iloc[-1]=8511887.7916, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11186.7558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26061.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28274 

self.closeSec=1692518399, self.tradeDate='20230820', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26067.1, self.close=26073.6, self.high=26073.6, self.low=26067.0 
127.0.0.1 - - [20/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28275 

self.closeSec=1692518699, self.tradeDate='20230820', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26073.6, self.close=26061.7, self.high=26074.2, self.low=26061.7 
127.0.0.1 - - [20/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28276 

self.closeSec=1692518999, self.tradeDate='20230820', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26061.8, self.close=26054.2, self.high=26061.8, self.low=26054.1 
127.0.0.1 - - [20/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28277 

self.closeSec=1692519299, self.tradeDate='20230820', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26054.2, self.close=26057.0, self.high=26057.0, self.low=26052.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28278 

self.closeSec=1692519599, self.tradeDate='20230820', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26057.0, self.close=26059.0, self.high=26059.0, self.low=26056.9 
127.0.0.1 - - [20/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28279 

self.closeSec=1692519899, self.tradeDate='20230820', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26059.0, self.close=26061.7, self.high=26061.7, self.low=26041.4 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-20 16:00:17,127:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230820    132959  26104.9  ...  45.000000  0.453313  0.404849
5786  20230820    135959  26134.1  ...  44.583333  0.442250  0.409328
5787  20230820    142959  26075.1  ...  44.583333  0.439629  0.415795
5788  20230820    145959  26061.1  ...  44.583333  0.437789  0.423418
5789  20230820    152959  26051.3  ...  44.583333  0.440544  0.428701

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-08-20 16:00:17,188:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510627  0.489373       0  ...  1.069976  -1.0    0.0  0.874763
538     1  0.467734  0.532266       0  ...  1.070555  -1.0    0.0  0.874290
539     1  0.487741  0.512259       0  ...  1.070957  -1.0    0.0  0.873961
540     1  0.488483  0.511517       1  ...  1.070493  -1.0    0.0  0.874340
541     1  0.495847  0.504153       1  ...  1.070041  -1.0    0.0  0.874709

[5 rows x 10 columns]
2023-08-20 16:00:17,198:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510652  0.489348       0  ...  1.069976  -1.0    0.0  0.875597
46     1  0.467991  0.532009       0  ...  1.070555  -1.0    0.0  0.875815
47     1  0.487822  0.512178       0  ...  1.070957  -1.0    0.0  0.873950
48     1  0.488495  0.511505       1  ...  1.070493  -1.0    0.0  0.875789
49     1  0.495847  0.504153       1  ...  1.070041  -1.0    0.0  0.874709

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '-210.36625678557', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26074.51153297', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14135 

self.closeSec=1692516599, self.tradeDate='20230820', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26064', self.close='26062.6'
127.0.0.1 - - [20/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14136 

self.closeSec=1692517199, self.tradeDate='20230820', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26062.5', self.close='26064.9'
127.0.0.1 - - [20/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14137 

self.closeSec=1692517799, self.tradeDate='20230820', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26064.9', self.close='26065.7'
127.0.0.1 - - [20/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14138 

self.closeSec=1692518399, self.tradeDate='20230820', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26065.6', self.close='26073.6'
127.0.0.1 - - [20/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14139 

self.closeSec=1692518999, self.tradeDate='20230820', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26073.6', self.close='26054.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14140 

self.closeSec=1692519599, self.tradeDate='20230820', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26054.2', self.close='26058.9'
127.0.0.1 - - [20/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [20/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14138 

self.closeSec=1692516599, self.tradeDate='20230820', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26064', self.close='26062.6'
127.0.0.1 - - [20/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14139 

self.closeSec=1692517199, self.tradeDate='20230820', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26062.5', self.close='26064.9'
127.0.0.1 - - [20/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14140 

self.closeSec=1692517799, self.tradeDate='20230820', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26064.9', self.close='26065.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14141 

self.closeSec=1692518399, self.tradeDate='20230820', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26065.6', self.close='26073.6'
127.0.0.1 - - [20/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14142 

self.closeSec=1692518999, self.tradeDate='20230820', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26073.6', self.close='26054.1'
127.0.0.1 - - [20/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14143 

self.closeSec=1692519599, self.tradeDate='20230820', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26054.2', self.close='26058.9'
127.0.0.1 - - [20/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14138 

self.closeSec=1692516599, self.tradeDate='20230820', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26064', self.close='26062.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14139 

self.closeSec=1692517199, self.tradeDate='20230820', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26062.5', self.close='26064.9'
127.0.0.1 - - [20/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14140 

self.closeSec=1692517799, self.tradeDate='20230820', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26064.9', self.close='26065.7'
127.0.0.1 - - [20/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14141 

self.closeSec=1692518399, self.tradeDate='20230820', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26065.6', self.close='26073.6'
127.0.0.1 - - [20/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14142 

self.closeSec=1692518999, self.tradeDate='20230820', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26073.6', self.close='26054.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14143 

self.closeSec=1692519599, self.tradeDate='20230820', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26054.2', self.close='26058.9'
127.0.0.1 - - [20/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28276
self.closeSec=1692519599, self.tradeDate='20230820', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26057.0, self.close=26059.0, self.high=26059.0, self.low=26056.9, self.vol=108.376, self.amt=2824023.4438 
127.0.0.1 - - [20/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-20 16:20:05,257:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230820   155500    155959  ...         0.0        0.0       0
5940  20230820   160000    160459  ...         0.0        0.0       0
5941  20230820   160500    160959  ...         0.0        0.0       0
5942  20230820   161000    161459  ...         0.0        0.0       0
5943  20230820   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 16:20:05,261:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692519599, self.tradeDate='20230820', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26057.0, self.close=26059.0, self.high=26059.0, self.low=26056.9, self.vol=108.376, self.amt=2824023.4438, ukdf['pct'].iloc[-1]=7.7e-05 , ukdf['amount'].iloc[-1]=2824023.4438, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29159.3991', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26058.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--: 127.0.0.1 - - [20/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28277
self.closeSec=1692519899, self.tradeDate='20230820', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26059.0, self.close=26061.7, self.high=26061.7, self.low=26041.4, self.vol=326.728, self.amt=8511887.7916 
2023-08-20 16:25:00,824:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230820   160000    160459  ...         0.0        0.0       0
5941  20230820   160500    160959  ...         0.0        0.0       0
5942  20230820   161000    161459  ...         0.0        0.0       0
5943  20230820   161500    161959  ...         0.0        0.0       0
5944  20230820   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 16:25:00,824:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692519899, self.tradeDate='20230820', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26059.0, self.close=26061.7, self.high=26061.7, self.low=26041.4, self.vol=326.728, self.amt=8511887.7916, ukdf['pct'].iloc[-1]=0.000104 , ukdf['amount'].iloc[-1]=8511887.7916, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29059.1184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26061.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230820   040000    075959  1692489599  ...    721  0.541444  0.087172     NaN
722  20230820   080000    115959  1692503999  ...    722  0.546391  0.096314     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '171718.1408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26091', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [20/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=589
self.closeSec=1692518399, self.tradeDate='20230820', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26090.9, self.close=26073.6, self.high=26153.4, self.low=26029.2, self.vol=13250.553, self.amt=345604561.8704 
2023-08-20 16:00:01,543:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692518399, self.tradeDate='20230820', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26090.9, self.close=26073.6, self.high=26153.4, self.low=26029.2, self.vol=13250.553, self.amt=345604561.8704 
2023-08-20 16:00:01,566:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230819   200000    235959  ...  50260.815  1.307815e+09  0.012200
720  20230820   000000    035959  ...  42478.706  1.109830e+09 -0.003370
721  20230820   040000    075959  ...  15244.606  3.974279e+08 -0.000934
722  20230820   080000    115959  ...  17904.105  4.672378e+08  0.000100
723  20230820   120000    155959  ...  13250.553  3.456046e+08 -0.000663

[5 rows x 11 columns]
2023-08-20 16:00:02,287:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230819   200000    235959  1692460799  ...    719  0.534194  0.074744     NaN
720  20230820   000000    035959  1692475199  ...    720  0.538999  0.083438     NaN
721  20230820   040000    075959  1692489599  ...    721  0.541444  0.087172     NaN
722  20230820   080000    115959  1692503999  ...    722  0.546391  0.096314     NaN
723  20230820   120000    155959  1692518399  ...    723  0.548425  0.103157     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '172567.12006565756', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26074.47903663', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


