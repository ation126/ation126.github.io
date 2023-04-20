# 20230420 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41493
self.closeSec=1681978799, self.tradeDate='20230420', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28906.4, self.close=28884.6, self.high=28906.5, self.low=28881.2, self.vol=736.123, self.amt=21267490.7755 
127.0.0.1 - - [20/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-20 16:20:05,926:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230420   155500    155959  ...         0.0        0.0       0
5945  20230420   160000    160459  ...         0.0        0.0       0
5946  20230420   160500    160959  ...         0.0        0.0       0
5947  20230420   161000    161459  ...         0.0        0.0       0
5948  20230420   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 16:20:05,929:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681978799, self.tradeDate='20230420', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28906.4, self.close=28884.6, self.high=28906.5, self.low=28881.2, self.vol=736.123, self.amt=21267490.7755, ukdf['pct'].iloc[-1]=-0.000758 , ukdf['amount'].iloc[-1]=21267490.7755, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-743829.5184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28890.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41494
self.closeSec=1681979099, self.tradeDate='20230420', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28884.7, self.close=28914.6, self.high=28938.0, self.low=28884.6, self.vol=1541.006, self.amt=44567665.8233 
2023-04-20 16:25:01,592:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230420   160000    160459  ...         0.0        0.0       0
5946  20230420   160500    160959  ...         0.0        0.0       0
5947  20230420   161000    161459  ...         0.0        0.0       0
5948  20230420   161500    161959  ...         0.0        0.0       0
5949  20230420   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 16:25:01,594:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681979099, self.tradeDate='20230420', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28884.7, self.close=28914.6, self.high=28938.0, self.low=28884.6, self.vol=1541.006, self.amt=44567665.8233, ukdf['pct'].iloc[-1]=0.001039 , ukdf['amount'].iloc[-1]=44567665.8233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-745447.24428153152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28917.08324052', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42055 

self.closeSec=1681977599, self.tradeDate='20230420', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28870.7, self.close=28857.7, self.high=28882.6, self.low=28837.2 
127.0.0.1 - - [20/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42056 

self.closeSec=1681977899, self.tradeDate='20230420', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28857.7, self.close=28847.0, self.high=28874.9, self.low=28821.3 
127.0.0.1 - - [20/Apr/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42057 

self.closeSec=1681978199, self.tradeDate='20230420', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28847.0, self.close=28852.0, self.high=28868.7, self.low=28831.0 
127.0.0.1 - - [20/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42058 

self.closeSec=1681978499, self.tradeDate='20230420', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28852.0, self.close=28906.5, self.high=28907.0, self.low=28851.9 
127.0.0.1 - - [20/Apr/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42059 

self.closeSec=1681978799, self.tradeDate='20230420', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28906.4, self.close=28884.6, self.high=28906.5, self.low=28881.2 
127.0.0.1 - - [20/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42060 

self.closeSec=1681979099, self.tradeDate='20230420', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28884.7, self.close=28914.6, self.high=28938.0, self.low=28884.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-20 16:00:20,376:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230420    132959  28855.2  ...  50.833333  0.404294  0.736482
5786  20230420    135959  28857.7  ...  50.833333  0.409185  0.729000
5787  20230420    142959  28884.6  ...  51.250000  0.423146  0.716675
5788  20230420    145959  28962.3  ...  50.833333  0.416541  0.708685
5789  20230420    152959  28911.1  ...  50.416667  0.415117  0.701984

[5 rows x 33 columns]
0.492619926199262
acc is : 0.492619926199262
2023-04-20 16:00:20,469:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.547919  0.452081       1  ...  0.995725   1.0    0.0  1.031762
538     0  0.549512  0.450488       1  ...  0.998403   1.0    0.0  1.034538
539     0  0.562940  0.437060       0  ...  0.996642   1.0    0.0  1.032713
540     0  0.527703  0.472297       0  ...  0.996263   1.0    0.0  1.032320
541     0  0.539665  0.460335       0  ...  0.994798   1.0    0.0  1.030801

[5 rows x 10 columns]
2023-04-20 16:00:20,494:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.548780  0.451220       1  ...  0.995725   1.0    0.0  1.036356
46     0  0.549947  0.450053       1  ...  0.998403   1.0    0.0  1.037209
47     0  0.562945  0.437055       0  ...  0.996642   1.0    0.0  1.034657
48     0  0.528104  0.471896       0  ...  0.996263   1.0    0.0  1.034926
49     0  0.539665  0.460335       0  ...  0.994798   1.0    0.0  1.030801

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [20/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21025 

self.closeSec=1681975799, self.tradeDate='20230420', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28904.5', self.close='28900.2'
127.0.0.1 - - [20/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21026 

self.closeSec=1681976399, self.tradeDate='20230420', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28900.3', self.close='28890.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21027 

self.closeSec=1681976999, self.tradeDate='20230420', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28890.9', self.close='28878.5'
127.0.0.1 - - [20/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21028 

self.closeSec=1681977599, self.tradeDate='20230420', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28878.6', self.close='28857.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21029 

self.closeSec=1681978199, self.tradeDate='20230420', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28857.7', self.close='28852'
127.0.0.1 - - [20/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21030 

self.closeSec=1681978799, self.tradeDate='20230420', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28852', self.close='28884.6'
127.0.0.1 - - [20/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21026 

self.closeSec=1681975799, self.tradeDate='20230420', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28904.5', self.close='28900.2'
127.0.0.1 - - [20/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21027 

self.closeSec=1681976399, self.tradeDate='20230420', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28900.3', self.close='28890.9'
127.0.0.1 - - [20/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21028 

self.closeSec=1681976999, self.tradeDate='20230420', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28890.9', self.close='28878.5'
127.0.0.1 - - [20/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21029 

self.closeSec=1681977599, self.tradeDate='20230420', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28878.6', self.close='28857.7'
127.0.0.1 - - [20/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21030 

self.closeSec=1681978199, self.tradeDate='20230420', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28857.7', self.close='28852'
127.0.0.1 - - [20/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21031 

self.closeSec=1681978799, self.tradeDate='20230420', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28852', self.close='28884.6'
127.0.0.1 - - [20/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21026 

self.closeSec=1681975799, self.tradeDate='20230420', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28904.5', self.close='28900.2'
127.0.0.1 - - [20/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21027 

self.closeSec=1681976399, self.tradeDate='20230420', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28900.3', self.close='28890.9'
127.0.0.1 - - [20/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21028 

self.closeSec=1681976999, self.tradeDate='20230420', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28890.9', self.close='28878.5'
127.0.0.1 - - [20/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21029 

self.closeSec=1681977599, self.tradeDate='20230420', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28878.6', self.close='28857.7'
127.0.0.1 - - [20/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21030 

self.closeSec=1681978199, self.tradeDate='20230420', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28857.7', self.close='28852'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21031 

self.closeSec=1681978799, self.tradeDate='20230420', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28852', self.close='28884.6'
127.0.0.1 - - [20/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37491
self.closeSec=1681978799, self.tradeDate='20230420', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28906.4, self.close=28884.6, self.high=28906.5, self.low=28881.2, self.vol=736.123, self.amt=21267490.7755 
127.0.0.1 - - [20/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-04-20 16:20:04,864:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230420   155500    155959  ...         0.0        0.0       0
5945  20230420   160000    160459  ...         0.0        0.0       0
5946  20230420   160500    160959  ...         0.0        0.0       0
5947  20230420   161000    161459  ...         0.0        0.0       0
5948  20230420   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 16:20:04,885:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681978799, self.tradeDate='20230420', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28906.4, self.close=28884.6, self.high=28906.5, self.low=28881.2, self.vol=736.123, self.amt=21267490.7755, ukdf['pct'].iloc[-1]=-0.000758 , ukdf['amount'].iloc[-1]=21267490.7755, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [20/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37492
self.closeSec=1681979099, self.tradeDate='20230420', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28884.7, self.close=28914.6, self.high=28938.0, self.low=28884.6, self.vol=1541.006, self.amt=44567665.8233 
2023-04-20 16:25:01,590:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230420   160000    160459  ...         0.0        0.0       0
5946  20230420   160500    160959  ...         0.0        0.0       0
5947  20230420   161000    161459  ...         0.0        0.0       0
5948  20230420   161500    161959  ...         0.0        0.0       0
5949  20230420   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 16:25:01,591:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681979099, self.tradeDate='20230420', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28884.7, self.close=28914.6, self.high=28938.0, self.low=28884.6, self.vol=1541.006, self.amt=44567665.8233, ukdf['pct'].iloc[-1]=0.001039 , ukdf['amount'].iloc[-1]=44567665.8233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230420   040000    075959  1681948799  ...    721  0.375786 -0.336869     NaN
722  20230420   080000    115959  1681963199  ...    722  0.445561 -0.185512     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '30658.257', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28853.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=876
self.closeSec=1681977599, self.tradeDate='20230420', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28850.0, self.close=28857.7, self.high=29078.0, self.low=28803.5, self.vol=58959.523, self.amt=1704867257.7843 
127.0.0.1 - - [20/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-04-20 16:00:01,943:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681977599, self.tradeDate='20230420', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28850.0, self.close=28857.7, self.high=29078.0, self.low=28803.5, self.vol=58959.523, self.amt=1704867257.7843 
2023-04-20 16:00:02,003:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230419   200000    235959  ...   98329.802  2.880595e+09 -0.001778
720  20230420   000000    035959  ...   61620.315  1.802690e+09 -0.001275
721  20230420   040000    075959  ...  159240.579  4.607687e+09 -0.014224
722  20230420   080000    115959  ...   91900.129  2.647339e+09  0.001910
723  20230420   120000    155959  ...   58959.523  1.704867e+09  0.000263

[5 rows x 11 columns]
2023-04-20 16:00:03,844:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230419   200000    235959  1681919999  ...    719  0.310800 -0.475507     NaN
720  20230420   000000    035959  1681934399  ...    720  0.359029 -0.370344     NaN
721  20230420   040000    075959  1681948799  ...    721  0.375786 -0.336869     NaN
722  20230420   080000    115959  1681963199  ...    722  0.445561 -0.185512     NaN
723  20230420   120000    155959  1681977599  ...    723  0.494668 -0.082384     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '30868.317', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28857.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


